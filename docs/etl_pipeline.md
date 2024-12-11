# ETL-Project





[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======

# ETL Pipeline Documentation

<div class="etl-card">
    <h2>ETL Pipeline Documentation</h2>
    <h3>1. Overview</h3>
    <p>
        The ETL (Extract, Transform, Load) pipeline is a structured process to automate the movement of healthcare data between systems. It ensures that patient and condition data is retrieved, cleaned, formatted, and loaded into a target system in a consistent and reliable manner. This pipeline focuses on API interactions and adheres to healthcare data standards like HL7 FHIR and SNOMED CT.
    </p>

    <h3>Pipeline Components</h3>
    <ol>
        <li>
            <strong>Extraction:</strong> Retrieving patient and condition data from a source FHIR-compliant API.
        </li>
        <li>
            <strong>Transformation:</strong> Cleaning, structuring, and enriching the extracted data to meet the requirements of the target API.
        </li>
        <li>
            <strong>Loading:</strong> Posting the transformed data into the target API, while ensuring data integrity.
        </li>
    </ol>
</div>

<div class="image-container">
    <img src="img_11.png" alt="ETL Image">
</div>


## Extraction
- Uses Python to connect to FHIR APIs.
<div class="etl-card">
    <h2>Extraction Process</h2>
    <p>
        The extraction process involved retrieving data from two main APIs:
    </p>
    <h3>1. FHIR Server for OpenEMR</h3>
    <ul>
        <li><strong>Base URL:</strong> <a href="https://in-info-web20.luddy.indianapolis.iu.edu/apis/default/fhir" target="_blank">https://in-info-web20.luddy.indianapolis.iu.edu/apis/default/fhir</a></li>
        <li><strong>Endpoints:</strong>
            <ul>
                <li><code>/Patient</code>: Retrieve patient details by ID or query parameters.</li>
                <li><code>/Condition</code>: Fetch patient-specific medical conditions.</li>
            </ul>
        </li>
        <li><strong>Authentication:</strong>
            <ul>
                <li>Used OAuth 2.0 for authentication.</li>
                <li>Token management was performed by accessing the endpoint:</li>
                <li><strong>Token URL:</strong> <a href="https://in-info-web20.luddy.indianapolis.iu.edu/oauth2/default/token" target="_blank">https://in-info-web20.luddy.indianapolis.iu.edu/oauth2/default/token</a></li>
                <li>Refresh tokens were stored and updated using utility scripts.</li>
            </ul>
        </li>
    </ul>

    <h3>2. SNOMED CT</h3>
    <ul>
        <li><strong>Base URL:</strong> <a href="http://159.65.173.51:8080/v1/snomed" target="_blank">http://159.65.173.51:8080/v1/snomed</a></li>
        <li><strong>Endpoints:</strong>
            <ul>
                <li><code>/concepts/{concept_id}</code>: Retrieve basic information for a given SNOMED concept.</li>
                <li><code>/concepts/{concept_id}/extended</code>: Retrieves hierarchical parent relationships of the given SNOMED CT concept.</li>
                <li><code>/concepts/{concept_id}/descriptions</code>: Fetches the descriptions or terms associated with a specific SNOMED CT concept.</li>
            </ul>
        </li>
        <li><strong>Authentication:</strong> No authentication was required.</li>
    </ul>
</div>

## Transformation
- Data is cleaned and formatted for the target API.
- 
<div class="etl-card">
    <h2>Transformation Phase</h2>
    <p>
        The transformation phase ensures data is clean, standardized, and formatted to match the target API’s schema. This phase involves:
    </p>
    <ul>
        <li><strong>Validation and Normalization:</strong> Ensuring fields like dates (ISO 8601) and addresses are consistent and error-free.</li>
        <li><strong>Clinical Data Mapping:</strong> Mapping clinical data to SNOMED CT codes using ECL queries for standardization.</li>
        <li><strong>Handling Missing/Invalid Values:</strong> Addressing incomplete or incorrect data to maintain integrity.</li>
    </ul>
    <p>
        The following tools and techniques are integral to the transformation process:
    </p>
    <ul>
        <li><strong>Requests Library:</strong> Used for interacting with APIs, sending data, and retrieving responses.</li>
        <li><strong>Print Function:</strong> Extensively utilized for debugging and verifying data transformations.</li>
        <li><strong>Python Libraries:</strong>
            <ul>
                <li><strong>json:</strong> Streamlines data parsing and formatting.</li>
                <li><strong>datetime:</strong> Facilitates date manipulation and formatting.</li>
            </ul>
        </li>
    </ul>
</div>


<style>
    /* Card Styling */
    .etl-card {
        background: linear-gradient(135deg, #F0FFF0, #E0FFE0); /* Soft gradient with light greens */
        padding: 30px;
        border-radius: 15px;
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
        margin: 20px auto;
        max-width: 800px;
        font-family: 'Georgia', serif;
        color: #333;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .etl-card h2 {
        color: #006400; /* Dark green for the header */
        text-align: center;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        margin-bottom: 20px;
        font-size: 2rem;
    }

    .etl-card h3 {
        color: #228B22; /* Forest green for subheaders */
        text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3);
        margin-bottom: 15px;
        font-size: 1.5rem;
    }

    .etl-card p, .etl-card ol {
        font-size: 1.2rem;
        line-height: 1.8;
        text-align: justify;
    }

    .etl-card ol {
        list-style: decimal inside;
        padding-left: 20px;
    }

    .etl-card ol li {
        margin-bottom: 10px;
    }

    /* Hover Effect */
    .etl-card:hover {
        transform: scale(1.05); /* Slight zoom-in effect */
        box-shadow: 0 12px 20px rgba(0, 0, 0, 0.4); /* Deeper shadow on hover */
        background: linear-gradient(135deg, #E8FFE8, #D0FFD0); /* Brighter gradient transition on hover */
    }

    /* Image Container Styling */
    .image-container {
        text-align: center;
        margin: 30px auto;
    }

    .image-container img {
        max-width: 100%;
        height: auto;
        border-radius: 10px;
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
    }

    /* Body Styling for Bright Green Background */
    body {
        background-color: #7CFC00; /* Bright green background */
    }
</style>






## Loading
- Processed data is posted back to the target API.

[Back to Home](index.md)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ETL Project Overview</title>

    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #CCFFCC;  
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }
        /* Header Styles */
        h1 {
            font-size: 2.8rem;
            color: #4B0082;
            text-align: center;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }
</head>
<body>
