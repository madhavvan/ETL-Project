# ETL Project Overview




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======



<img alt="img.png" height="500" src="img.png" width="800" style="border: 5px solid #F0F8FF; border-radius: 15px; box-shadow: 0 10px 20px rgba(0, 0, 0, 0.3); margin: 20px auto; display: block;">

<div style="background: #4B0082; color: #F0F8FF; border-radius: 15px; padding: 30px; margin: 20px auto; width: 90%; max-width: 1000px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.4); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem;">
    <p>The diagram illustrates the ETL process from extraction to loading, with decision points and key tasks highlighted.</p>
</div>

<div style="background: #6A5ACD; color: #F0F8FF; padding: 30px; border-radius: 15px; margin: 20px auto; width: 90%; max-width: 1000px; box-shadow: 0 12px 16px rgba(0, 0, 0, 0.4); text-align: justify; font-family: 'Georgia', serif; font-size: 1.5rem;">
    <h3 style="color: #FFD700; text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.5); font-size: 2rem;">The BPMN Model</h3>
    <p>The BPMN model represents the referral and treatment process for a patient transitioning from a Primary Care Clinic to a hospital for specialist care. The workflow is divided into three key pools: Primary Care Clinic, Hospital Administration, and Specialist, each signifying distinct roles in the patient care process.</p>

    <p>The process begins in the Primary Care Clinic, where the care plan is created, patient medical records are updated, and follow-up care is scheduled. After these initial steps, the referral is sent to the hospital for specialist intervention.</p>

    <p>In the Hospital Administration pool, the hospital receives and reviews the referral. A decision gateway assesses the validity of the referral. If valid, the patient is registered at the hospital. If not, a clarification request is sent back to the Primary Care Clinic, ensuring accuracy and preventing delays.</p>

    <p>The Specialist pool handles the core treatment phase. The specialist evaluates the patient and determines the next steps. If no further care is needed, the patient is discharged with instructions for continued care, if necessary, at the Primary Care Clinic. If additional treatment is required, the specialist provides care and refers the patient back to the Primary Care Clinic for follow-up.</p>

    <p>This BPMN model emphasizes accurate decision-making, seamless communication, and continuity of care. It ensures all stakeholders—Primary Care Clinic, hospital administration, and specialists—work collaboratively to deliver efficient and patient-focused outcomes.</p>
</div>


[Back to Home](index.md)

