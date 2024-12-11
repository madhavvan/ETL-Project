# ETL-Project




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======



<img
    alt="img.png"
    height="700"
    src="img.png"
    width="1100"
    style="border: 5px solid #F0F8FF; border-radius: 15px; box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3); margin: 20px auto; display: block; transition: transform 0.3s ease, box-shadow 0.3s ease;"
    class="hover-image"
/>

<style>
    /* Hover Effect for Image */
    .hover-image:hover {
        transform: translateY(-10px); /* Pop-Up Effect */
        box-shadow: 0 15px 30px rgba(0, 0, 0, 0.5); /* Enhanced Shadow on Hover */
    }
</style>



<div style="background: #4B0082; padding: 40px;">
    <!-- Box 1: Overview -->
    <div class="hover-box" style="background: #E6E6FA; color: #333333; padding: 30px; border-radius: 15px; margin: 20px auto; width: 100%; max-width: 1100px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.2); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem; transition: transform 0.3s ease, box-shadow 0.3s ease;">
        <h3 style="color: #6A5ACD; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); font-size: 2rem;">Overview</h3>
        <p>The BPMN model represents the referral and treatment process for a patient transitioning from a Primary Care Clinic to a hospital for specialist care. The workflow is divided into three key pools: Primary Care Clinic, Hospital Administration, and Specialist, each signifying distinct roles in the patient care process.</p>
    </div>

    <!-- Box 2: Primary Care Clinic -->
    <div class="hover-box" style="background: #D8BFD8; color: #333333; padding: 30px; border-radius: 15px; margin: 20px auto; width: 100%; max-width: 1100px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.2); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem; transition: transform 0.3s ease, box-shadow 0.3s ease;">
        <h3 style="color: #6A5ACD; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); font-size: 2rem;">Primary Care Clinic</h3>
        <p>The process begins in the Primary Care Clinic, where the care plan is created, patient medical records are updated, and follow-up care is scheduled. After these initial steps, the referral is sent to the hospital for specialist intervention.</p>
    </div>

    <!-- Box 3: Hospital Administration -->
    <div class="hover-box" style="background: #E6E6FA; color: #333333; padding: 30px; border-radius: 15px; margin: 20px auto; width: 100%; max-width: 1100px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.2); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem; transition: transform 0.3s ease, box-shadow 0.3s ease;">
        <h3 style="color: #6A5ACD; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); font-size: 2rem;">Hospital Administration</h3>
        <p>In the Hospital Administration pool, the hospital receives and reviews the referral. A decision gateway assesses the validity of the referral. If valid, the patient is registered at the hospital. If not, a clarification request is sent back to the Primary Care Clinic, ensuring accuracy and preventing delays.</p>
    </div>

    <!-- Box 4: Specialist -->
    <div class="hover-box" style="background: #D8BFD8; color: #333333; padding: 30px; border-radius: 15px; margin: 20px auto; width: 100%; max-width: 1100px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.2); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem; transition: transform 0.3s ease, box-shadow 0.3s ease;">
        <h3 style="color: #6A5ACD; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); font-size: 2rem;">Specialist</h3>
        <p>The Specialist pool handles the core treatment phase. The specialist evaluates the patient and determines the next steps. If no further care is needed, the patient is discharged with instructions for continued care, if necessary, at the Primary Care Clinic. If additional treatment is required, the specialist provides care and refers the patient back to the Primary Care Clinic for follow-up.</p>
    </div>

    <!-- Box 5: Conclusion -->
    <div class="hover-box" style="background: #E6E6FA; color: #333333; padding: 30px; border-radius: 15px; margin: 20px auto; width: 100%; max-width: 1100px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.2); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem; transition: transform 0.3s ease, box-shadow 0.3s ease;">
        <h3 style="color: #6A5ACD; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.1); font-size: 2rem;">Conclusion</h3>
        <p>This BPMN model emphasizes accurate decision-making, seamless communication, and continuity of care. It ensures all stakeholders—Primary Care Clinic, hospital administration, and specialists—work collaboratively to deliver efficient and patient-focused outcomes.</p>
    </div>
</div>

<style>
    .hover-box:hover {
        transform: translateY(-10px);
        box-shadow: 0 15px 25px rgba(0, 0, 0, 0.3);
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
            font-family: 'Arial', sans-serif;
            background: #C3B9E5; 
            margin: 0;
            padding: 0;
            line-height: 1.6;
            position: relative;
            overflow-x: hidden; /* Prevent horizontal scrolling */
            min-height: 200vh; /* Ensures scrolling is possible */
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

  






