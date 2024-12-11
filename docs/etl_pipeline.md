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

<style>
    /* Card Styling */
    .etl-card {
        background: linear-gradient(135deg, #FFEBF0, #FFF1D6); /* Loving gradient with soft pink and peach */
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
        color: #FF69B4; /* Hot Pink for a loving header */
        text-align: center;
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        margin-bottom: 20px;
        font-size: 2rem;
    }

    .etl-card h3 {
        color: #FF6F61; /* Soft Coral for subheaders */
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
        background: linear-gradient(135deg, #FFF5E5, #FFD9E8); /* Softer gradient transition on hover */
    }
</style>

![img_11.png](img_11.png)

## Extraction
- Uses Python to connect to FHIR APIs.

## Transformation
- Data is cleaned and formatted for the target API.

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
