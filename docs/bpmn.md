# ETL Project Overview




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



<div class="hover-box" style="background: #6A5ACD; color: #F0F8FF; padding: 30px; border-radius: 15px; margin: 20px auto; width: 100%; max-width: 1100px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.4); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem; transition: transform 0.3s ease, box-shadow 0.3s ease;">
    <h3 style="color: #FFD700; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5); font-size: 2rem;">The BPMN Model</h3>
    <p>The BPMN model represents the referral and treatment process for a patient transitioning from a Primary Care Clinic to a hospital for specialist care. The workflow is divided into three key pools: Primary Care Clinic, Hospital Administration, and Specialist, each signifying distinct roles in the patient care process.</p>

    <p>The process begins in the Primary Care Clinic, where the care plan is created, patient medical records are updated, and follow-up care is scheduled. After these initial steps, the referral is sent to the hospital for specialist intervention.</p>

    <p>In the Hospital Administration pool, the hospital receives and reviews the referral. A decision gateway assesses the validity of the referral. If valid, the patient is registered at the hospital. If not, a clarification request is sent back to the Primary Care Clinic, ensuring accuracy and preventing delays.</p>

    <p>The Specialist pool handles the core treatment phase. The specialist evaluates the patient and determines the next steps. If no further care is needed, the patient is discharged with instructions for continued care, if necessary, at the Primary Care Clinic. If additional treatment is required, the specialist provides care and refers the patient back to the Primary Care Clinic for follow-up.</p>

    <p>This BPMN model emphasizes accurate decision-making, seamless communication, and continuity of care. It ensures all stakeholders—Primary Care Clinic, hospital administration, and specialists—work collaboratively to deliver efficient and patient-focused outcomes.</p>
</div>

<style>
    /* Hover Effect for 3D Pop-Up */
    .hover-box:hover {
        transform: translateY(-10px); /* Pop-Up Effect */
        box-shadow: 0 15px 25px rgba(0, 0, 0, 0.5); /* Enhanced Shadow on Hover */
    }
</style>



<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ETL Project Overview</title>

    <style>
        /* General Styling */
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(135deg, #8A2BE2, #E6E6FA); /* Vibrant Lavender Gradient */
            margin: 0;
            padding: 0;
            line-height: 1.6;
            position: relative;
            overflow-x: hidden; /* Prevent horizontal scrolling */
            min-height: 200vh; /* Ensures scrolling is possible */
        }

        /* Border Themes */
        body::before,
        body::after {
            content: '';
            position: absolute;
            width: 300px;
            height: 300px;
            background: linear-gradient(135deg, #FFD700, #FF6347); /* Golden to Tomato Gradient */
            border-radius: 50%;
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.3);
            z-index: -1;
        }

        body::before {
            top: -100px;
            left: -100px;
            animation: move 6s infinite ease-in-out;
        }

        body::after {
            bottom: -100px;
            right: -100px;
            animation: move 6s infinite ease-in-out reverse;
        }

        /* Animated Glow Borders */
        @keyframes move {
            0%, 100% {
                transform: scale(1) translate(0, 0);
            }
            50% {
                transform: scale(1.2) translate(50px, 50px);
            }
        }

        /* Card Styling */
        .content {
            max-width: 900px;
            margin: 50px auto;
            padding: 30px;
            background: rgba(255, 255, 255, 0.9); /* Semi-transparent White */
            border-radius: 20px;
            box-shadow: 0 15px 25px rgba(0, 0, 0, 0.2);
            text-align: center;
        }

        .content h1 {
            font-size: 2.5rem;
            color: #4B0082; /* Indigo */
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.3);
        }

        .content p {
            font-size: 1.2rem;
            color: #555;
            line-height: 1.8;
        }

        /* Additional Content Section for Scroll Testing */
        .additional-content {
            max-width: 900px;
            margin: 50px auto;
            padding: 20px;
            background: rgba(255, 255, 255, 0.8);
            border-radius: 20px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
            font-size: 1.2rem;
            color: #333;
        }
    </style>
</head>
<body>

    <div class="content">
        <h1>ETL Project Overview</h1>
        <p>Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.</p>
    </div>

    <div class="additional-content">
        <h2>Additional Section</h2>
        <p>This is extra content added to ensure scrolling functionality works as intended. The page is designed to be visually appealing while allowing smooth navigation. Add more content as needed to test the scrolling behavior.</p>
    </div>

</body>
</html>


[Back to Home](index.md)

