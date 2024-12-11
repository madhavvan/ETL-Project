# ETL-Project

            # Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.


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
        <h2>Key Tools and Technologies Used</h2>
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

    <div class="hover-card">
        <h2>Summary of the Deliverables</h2>
        <p>The ETL project deliverables include a thorough overview of the pipeline's design, implementation, and value. The project includes:</p>
        <ul>
            <li>A <strong>Python code repository</strong> showcasing scripts for extracting, processing, and loading healthcare data via the FHIR API, including comprehensive error handling and integration.</li>
            <li>A professional <strong>GitHub Pages website</strong> documenting the entire project with an introduction, BPMN workflow diagrams, Use Case diagrams, and team contributions.</li>
            <li>Visual insights displaying <strong>patient data trends</strong> and key analytics, highlighting the pipeline's practical uses.</li>
            <li>A brief <strong>presentation</strong> outlining the ETL pipeline's features, challenges, and lessons learned, emphasizing its role in improving healthcare data interoperability.</li>
            <li>Documentation of each team member's <strong>contributions, duties, and reflections</strong>, fostering collaboration and transparency.</li>
         </ul>
            <p>These deliverables collectively demonstrate the ETL pipeline's effectiveness in accelerating healthcare data exchange and analytics.</p>
    </div>

</div>

<style>
    /* Styling for Hover Cards with Decorative Section Colors */
    .hover-card {
        background: linear-gradient(135deg, #F8F8FF, #D8BFD8); /* Match the top decorative section gradient */
        padding: 20px;
        border-radius: 15px;
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3); /* Subtle shadow */
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
        transform: translateY(-8px); /* Pop-Up Effect */
        box-shadow: 0 12px 20px rgba(0, 0, 0, 0.4); /* Enhanced Shadow on Hover */
    }

    /* For responsive alignment */
    @media (max-width: 768px) {
        .hover-card {
            width: 90%; /* Full width for smaller screens */
        }
    }
</style>



[Back to Home](index.md)

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
    </style>
</head>
<body>


    <footer>
        <p>&copy; 2024 ETL Project. All Rights Reserved.</p>
    </footer>

</body>
</html>

