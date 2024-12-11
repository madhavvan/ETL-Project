# ETL-Project

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.


[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======


<div style="display: flex; flex-direction: row; justify-content: space-between; gap: 5px; flex-wrap: wrap; margin: 20px auto; width: 1100%; max-width: 1200px;">

    <!-- Card 1: Introduction -->
    <div class="hover-card">
        <h2>Introduction to Our ETL Project</h2>
        <p>Data interoperability is an important challenge in the current healthcare environment, as many systems collect and handle a wide range of clinical and patient data.</p>
        <p>Our ETL (Extract, Transform, Load) project aims to address this issue by developing an efficient pipeline for extracting data from FHIR APIs, transforming it into a consistent format, and loading it into target systems. This initiative helps healthcare companies make informed decisions, expedite workflows, and improve patient outcomes.</p>
    </div>

    <!-- Card 2: Purpose -->
    <div class="hover-card">
        <h2>Purpose of the ETL Pipeline</h2>
        <p>The major goal of the ETL pipeline is to provide seamless interoperability across healthcare systems while assuring accurate and efficient data transmission. By combining data from diverse systems, the pipeline improves healthcare companies' decision-making capacity, analytics, and patient care results.</p>
        <ul>
            <li><strong>Interoperability:</strong> To guarantee that data from diverse healthcare systems are seamlessly integrated utilizing FHIR standards.</li>
            <li><strong>Data Standardization:</strong> Transform raw, unstructured data into a clean, uniform format.</li>
            <li><strong>Analytics Enablement:</strong> Gather data for downstream analytics aiding clinical decision-making and operational insights.</li>
            <li><strong>Error Handling and Automation:</strong> Handle API complexity, assure data integrity, and automate common activities to improve efficiency.</li>
        </ul>
    </div>

    <!-- Card 3: Keys and Technologies Used -->
    <div class="hover-card">
        <h2>Keys and Technologies Used</h2>
        <p>The ETL project incorporates a range of modern tools and technologies to provide smooth data extraction, transformation, and loading in the healthcare area.</p>
        <ul>
            <li><strong>Python:</strong> Serves as the pipeline's backbone, enabling rapid scripting and reliable error handling during API interactions.</li>
            <li><strong>FHIR API:</strong> Follows HL7 standards to ensure uniform healthcare data exchange.</li>
            <li><strong>JSON Structures:</strong> Formats and transforms data during the extraction and transformation stages.</li>
            <li><strong>Primary Care EHR FHIR Server:</strong> Loads and stores processed data.</li>
            <li><strong>Camunda BPMN Modeler:</strong> Visualizes workflows for better understanding.</li>
            <li><strong>GitHub Pages:</strong> Hosts the project website with rich documentation, visuals, and resources.</li>
            <li><strong>Hermes Terminology Server:</strong> Enables mapping of healthcare terminology, such as parent-child connections in SNOMED CT.</li>
        </ul>
    </div>

</div>

<style>
    /* Styling for Hover Cards */
    .hover-card {
        background: linear-gradient(135deg, #E6E6FA, #F0FFF0); /* Gradient background */
        padding: 20px;
        border-radius: 15px;
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        width: 80%; 
        min-width: 300px;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
        font-family: 'Georgia', serif;
        color: #333;
        text-align: justify;
    }

    .hover-card h2 {
        color: #6A5ACD; /* Violet for headers */
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        font-size: 1.5rem;
        margin-bottom: 15px;
        text-align: center;
    }

    .hover-card ul {
        margin-top: 10px;
        padding-left: 20px;
    }

    .hover-card ul li {
        margin-bottom: 10px;
    }

    .hover-card:hover {
        transform: translateY(-10px); /* Pop-Up Effect */
        box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5); /* Enhanced Shadow on Hover */
    }

    /* For responsive alignment */
    @media (max-width: 768px) {
        .hover-card {
            width: 100%; /* Full width for smaller screens */
        }
    }
</style>


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
            font-family: 'Georgia', serif;
            background-color: #E6E6FA; /* Lavender background */
            margin: 0;
            padding: 0;
            line-height: 1.6;
            color: #333;
            overflow-x: hidden; /* Prevent horizontal scrolling */
        }

        /* Header Styles */
        h1 {
            font-size: 2.8rem;
            color: #4B0082;
            text-align: center;
            margin-bottom: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }

        /* Decorative Section */
        .decorative-section {
            background: linear-gradient(135deg, #F8F8FF, #D8BFD8);
            padding: 40px;
            border-radius: 15px;
            margin: 20px auto;
            width: 90%;
            max-width: 1200px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        .decorative-section h2 {
            color: #6A5ACD;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
            font-size: 2.5rem;
            margin-bottom: 20px;
        }

        .decorative-section p {
            font-size: 1.2rem;
            color: #333;
            line-height: 1.8;
            text-align: justify;
            margin: 0 auto;
            max-width: 900px;
        }

        .decorative-section ul {
            list-style-type: disc;
            padding-left: 40px;
            text-align: left;
            max-width: 900px;
            margin: 20px auto 0;
            font-size: 1.2rem;
            color: #333;
        }

        .decorative-section ul li {
            margin-bottom: 10px;
        }
    </style>
</head>
<body>

    <h1>ETL-Project</h1>

    <div class="decorative-section">
        <h2>Introduction to Our ETL Project</h2>
        <p>
            Data interoperability is an important challenge in the current healthcare environment, as many systems collect and handle a wide range of clinical and patient data. Our ETL (Extract, Transform, Load) project aims to address this issue by developing an efficient pipeline for extracting data from FHIR APIs, transforming it into a consistent, accessible format, and loading it into target systems to increase accessibility and usability. This initiative focuses on using standardized data sharing protocols to help healthcare companies make more informed decisions, expedite workflows, and improve patient outcomes.
        </p>

        <h2>Purpose of the ETL Pipeline</h2>
        <p>
            The major goal of the ETL pipeline is to provide seamless interoperability across healthcare systems while assuring accurate and efficient data transmission. By combining data from diverse systems, the pipeline improves healthcare companies' decision-making capacity, analytics, and patient care results.
        </p>

        <ul>
            <li><strong>Interoperability:</strong> To guarantee that data from diverse healthcare systems are seamlessly integrated utilizing FHIR standards.</li>
            <li><strong>Data Standardization:</strong> It is the process of transforming raw, unstructured data into a clean, uniform format that can be used appropriately.</li>
            <li><strong>Analytics Enablement:</strong> To gather data for downstream analytics that will aid clinical decision-making and operational insights.</li>
            <li><strong>Error Handling and Automation:</strong> To handle API complexity, assure data integrity, and automate common activities to improve efficiency.</li>
        </ul>
    </div>

    <!-- Navigation Section -->
    <nav style="text-align: center; margin: 30px 0;">
        <a href="index.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">Home</a> |
        <a href="bpmn.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">BPMN Model</a> |
        <a href="use_case.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">Use Case Model</a> |
        <a href="etl_pipeline.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">ETL Pipeline</a> |
        <a href="insights.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">Insights</a> |
        <a href="team.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">Team Contributions</a> |
        <a href="about.md" style="color: #4B0082; text-decoration: none; font-size: 1.2rem;">About</a>
    </nav>

</body>
</html>




