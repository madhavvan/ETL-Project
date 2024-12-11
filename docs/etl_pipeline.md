# ETL-Project





[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======

# ETL Pipeline Documentation

<div style="background: linear-gradient(135deg, #F0F8FF, #E6E6FA); padding: 30px; border-radius: 15px; box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); margin: 20px auto; max-width: 800px; font-family: 'Georgia', serif;">
    <h2 style="color: #4B0082; text-align: center; text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3); margin-bottom: 20px;">ETL Pipeline Documentation</h2>
    
    <h3 style="color: #6A5ACD; text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3); margin-bottom: 15px;">1. Overview</h3>
    <p style="color: #333; font-size: 1.2rem; line-height: 1.8; text-align: justify;">
        The ETL (Extract, Transform, Load) pipeline is a structured process to automate the movement of healthcare data between systems. It ensures that patient and condition data is retrieved, cleaned, formatted, and loaded into a target system in a consistent and reliable manner. This pipeline focuses on API interactions and adheres to healthcare data standards like HL7 FHIR and SNOMED CT.
    </p>

    <h3 style="color: #6A5ACD; text-shadow: 1px 1px 3px rgba(0, 0, 0, 0.3); margin-bottom: 15px;">Pipeline Components</h3>
    <ol style="color: #333; font-size: 1.2rem; line-height: 1.8; padding-left: 30px;">
        <li style="margin-bottom: 10px;">
            <strong>Extraction:</strong> Retrieving patient and condition data from a source FHIR-compliant API.
        </li>
        <li style="margin-bottom: 10px;">
            <strong>Transformation:</strong> Cleaning, structuring, and enriching the extracted data to meet the requirements of the target API.
        </li>
        <li style="margin-bottom: 10px;">
            <strong>Loading:</strong> Posting the transformed data into the target API, while ensuring data integrity.
        </li>
    </ol>
</div>

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
