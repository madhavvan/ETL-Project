# ETL-Project





[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======


# Use Case Diagram

## Overview
The use case diagram outlines the actors and interactions in the ETL pipeline process.

![img_10.png](img_10.png)


<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 20px; margin: 20px auto; max-width: 1200px;">

    <!-- Card 1: Use Case Overview -->
    <div class="use-case-card" style="background: linear-gradient(135deg, #FFE4E1, #FFB6C1);">
        <h2>The Use Case Model</h2>
        <p>The Use Case Model illustrates the integration of the Hospital Referral Management System (HRMS), Electronic Health Record (EHR) System, and Clinical Decision Support System (CDSS) to optimize patient care, referrals, and clinical decision-making.</p>
    </div>

    <!-- Card 2: HRMS -->
    <div class="use-case-card" style="background: linear-gradient(135deg, #E6E6FA, #D8BFD8);">
        <h2>Hospital Referral Management System</h2>
        <p>The HRMS streamlines the referral process by enabling Primary Care Physicians to refer patients to hospitals and collaborate with Care Coordinators. It facilitates communication of treatment plans and management of follow-ups.</p>
    </div>

    <!-- Card 3: EHR System -->
    <div class="use-case-card" style="background: linear-gradient(135deg, #F0FFF0, #98FB98);">
        <h2>Electronic Health Record System</h2>
        <p>The EHR system serves as a secure central repository for storing, retrieving, and updating patient data. It ensures stakeholders have access to accurate and up-to-date information for informed decision-making.</p>
    </div>

    <!-- Card 4: CDSS -->
    <div class="use-case-card" style="background: linear-gradient(135deg, #FFFACD, #FFD700);">
        <h2>Clinical Decision Support System</h2>
        <p>The CDSS analyzes data from the EHR system to provide actionable recommendations, such as diagnostic tests, treatment options, or discharge instructions, enhancing clinical workflows and improving patient outcomes.</p>
    </div>

    <!-- Card 5: Integrated Model -->
    <div class="use-case-card" style="background: linear-gradient(135deg, #ADD8E6, #87CEEB);">
        <h2>Integrated Model</h2>
        <p>The integrated model emphasizes collaboration and data-driven decision-making. It begins with patient referrals through HRMS, continues with data management in the EHR system, and leverages CDSS insights for treatment plans. Follow-ups are managed efficiently, ensuring continuity of care and improved patient outcomes.</p>
    </div>
</div>

<style>
    /* Styling for Cards */
    .use-case-card {
        padding: 20px;
        border-radius: 15px;
        box-shadow: 0 8px 16px rgba(0, 0, 0, 0.3);
        width: 100%;
        max-width: 450px;
        font-family: 'Georgia', serif;
        color: #333;
        text-align: justify;
        transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .hover-card h2 {
        color: #4B0082; /* Violet for headers */
        text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        font-size: 1.5rem;
        margin-bottom: 10px;
        text-align: center;
        line-height: 1.2; /* Adjust line-height for multiline text */
        word-spacing: 2px; /* Optional: Adjust spacing for words */
    }

    .use-case-card:hover {
        transform: translateY(-8px); /* Slight pop-up effect */
        box-shadow: 0 12px 20px rgba(0, 0, 0, 0.4); /* Enhanced shadow on hover */
    }

    @media (max-width: 768px) {
        .use-case-card {
            max-width: 100%; /* Full width on smaller screens */
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
            font-family: 'Arial', sans-serif;
            background-color: #ADD8E6;  /* Lavender background */
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
