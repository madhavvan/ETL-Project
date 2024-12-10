# ETL Project Overview

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======
## FHIR APIs Overview

<div style="background: #8A2BE2; color: #F0F8FF; border-radius: 15px; padding: 20px; margin: 20px auto; width: 90%; max-width: 1200px; box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4); font-family: 'Georgia', serif; text-align: justify; font-size: 1.2rem;">
    <p>FHIR (Fast Healthcare Interoperability Resources) is a standard established by HL7 International to promote the electronic transmission of healthcare information. FHIR APIs are essential to this standard, providing mechanisms for accessing and sharing healthcare data across multiple operating systems.</p>
    <h3 style="color: #FFD700;">Key Features:</h3>
    <ul>
        <li>Resource-Based Structure: Separates data into modular "resources" (e.g., Patient, Observation, Medication) for reusability.</li>
        <li>RESTful Design: Uses HTTP methods like GET, POST, PUT, DELETE.</li>
        <li>Interoperability: Enables smooth data sharing across EHRs, mobile apps, and healthcare systems.</li>
    </ul>
</div>

---

## BPMN Model Explanation

<div style="background: #6A5ACD; color: #F0F8FF; padding: 30px; border-radius: 15px; margin: 20px auto; width: 90%; max-width: 1200px; box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4); font-family: 'Georgia', serif; text-align: justify; font-size: 1.2rem;">
    <h3 style="color: #FFD700;">Primary Care Clinic:</h3>
    <p>The process begins when a patient is referred by their primary care provider. The clinic updates medical records and schedules follow-up care before sending the referral to the hospital.</p>
    
    <h3 style="color: #FFD700;">Hospital Administration:</h3>
    <p>The hospital reviews the referral, validates it, and registers the patient for further evaluation. Invalid referrals are sent back to the clinic for clarification.</p>
    
    <h3 style="color: #FFD700;">Specialist’s Process:</h3>
    <p>After registration, the specialist evaluates the patient and determines further care. The patient is discharged with instructions if no further treatment is required or referred back to the clinic for follow-up care.</p>
</div>

---

## Team Contributions

<div style="background: #8A2BE2; color: #F0F8FF; border-radius: 15px; padding: 20px; margin: 20px auto; width: 90%; max-width: 1200px; box-shadow: 0 10px 20px rgba(0, 0, 0, 0.4); font-family: 'Georgia', serif; text-align: center; font-size: 1.2rem;">
    <h3 style="color: #FFD700;">Project Team and Roles</h3>
    <table style="width: 100%; border-collapse: collapse; margin: 20px 0; color: #F0F8FF;">
        <thead>
            <tr style="background-color: #6A5ACD; color: #FFD700;">
                <th style="border: 1px solid #F0F8FF; padding: 10px;">Team Member</th>
                <th style="border: 1px solid #F0F8FF; padding: 10px;">Role</th>
                <th style="border: 1px solid #F0F8FF; padding: 10px;">Contributions</th>
                <th style="border: 1px solid #F0F8FF; padding: 10px;">Reflections</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Pallavi Vandanapu</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Coding Specialist</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Completed coding tasks 1 and 2 involving API integration and data processing.</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Gained insights into FHIR APIs and real-world data transformation challenges.</td>
            </tr>
            <tr>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Venu Madhav Pentala</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Website Designer</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Designed and implemented the project website with intuitive navigation.</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Enhanced web development skills while ensuring project accessibility.</td>
            </tr>
            <tr>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Yashita Raga Saranam</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">BPMN and Coding Specialist</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Completed coding tasks 3 and 4, built BPMN model reflecting processes.</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Learned about process visualization and multi-tool integration.</td>
            </tr>
            <tr>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Haneesha Donepudi</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Use Case Model Designer</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Created use case models defining system interactions and roles.</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Developed clear communication skills for technical concepts.</td>
            </tr>
            <tr>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Aishwarya Voraganti</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Documentation Specialist</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Developed and structured project documentation.</td>
                <td style="border: 1px solid #F0F8FF; padding: 10px;">Improved technical writing and organization skills.</td>
            </tr>
        </tbody>
    </table>
</div>