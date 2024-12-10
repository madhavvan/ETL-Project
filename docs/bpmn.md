# ETL Project Overview




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======

<span style="font-family: 'Comic Sans MS', cursive, sans-serif; font-size: 2.5rem; color: #FFD700; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.4);">
Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.
</span>

<div style="background: linear-gradient(135deg, #89CFF0, #00AEEF); padding: 20px; border-radius: 10px; margin: 20px auto; width: 90%; max-width: 1200px; box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2); text-align: center;">
</div>


<img alt="img.png" height="500" src="img.png" width="800" style="border: 5px solid #FFD700; border-radius: 15px; box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3); margin: 20px auto; display: block;">

<div style="background: #00509E; color: #FFD700; border-radius: 15px; padding: 20px; margin: 20px auto; width: 90%; max-width: 1000px; box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4); text-align: justify;">
<p>The diagram illustrates the ETL process from extraction to loading, with decision points and key tasks highlighted.</p>
</div>

<div style="background: #004080; color: #F0F8FF; padding: 20px; border-radius: 15px; margin: 20px auto; width: 90%; max-width: 1000px; box-shadow: 0 8px 16px rgba(0, 0, 0, 0.4); text-align: justify;">
<h3 style="color: #FFD700; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5);">The BPMN Model</h3>
<p>The BPMN model represents the referral and treatment process for a patient transitioning from a Primary Care Clinic to a hospital for specialist care. The workflow is divided into three key pools: Primary Care Clinic, Hospital Administration, and Specialist, each signifying distinct roles in the patient care process.</p>

<p>The process begins in the Primary Care Clinic, where the care plan is created, patient medical records are updated, and follow-up care is scheduled. After these initial steps, the referral is sent to the hospital for specialist intervention.</p>

<p>In the Hospital Administration pool, the hospital receives and reviews the referral. A decision gateway assesses the validity of the referral. If valid, the patient is registered at the hospital. If not, a clarification request is sent back to the Primary Care Clinic, ensuring accuracy and preventing delays.</p>

<p>The Specialist pool handles the core treatment phase. The specialist evaluates the patient and determines the next steps. If no further care is needed, the patient is discharged with instructions for continued care, if necessary, at the Primary Care Clinic. If additional treatment is required, the specialist provides care and refers the patient back to the Primary Care Clinic for follow-up.</p>

<p>This BPMN model emphasizes accurate decision-making, seamless communication, and continuity of care. It ensures all stakeholders—Primary Care Clinic, hospital administration, and specialists—work collaboratively to deliver efficient and patient-focused outcomes.</p>
</div>

[Back to Home](index.md)

