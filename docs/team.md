# ETL Project Overview

Welcome to the ETL project website. This project demonstrates the ETL pipeline using Python and FHIR APIs.




[Home](index.md) | [BPMN Model](bpmn.md) | [Use Case Model](use_case.md) | [ETL Pipeline](etl_pipeline.md) | [Insights](insights.md) | [Team Contributions](team.md) | [About](about.md)
=======
FHIR (Fast Healthcare Interoperability Resources) is a standard established by HL7 International to promote the electronic transmission of healthcare information. FHIR APIs (Application Programming Interfaces) are essential to this standard, providing formal mechanisms for accessing and sharing healthcare data across multiple operating systems.

Key features:
FHIR APIs provide a resource-based structure, separating data into modular "resources" (e.g., Patient, Observation, Medication) that are reusable and scalable (HL7 International, n.d.).
 RESTful Design: FHIR APIs adhere to RESTful principles, allowing data interaction using common HTTP methods such as GET, POST, PUT, and DELETE (Mandel et al. 2016).
 Interoperability: FHIR APIs enable smooth data transmission across Electronic Health Records (EHRs), mobile applications, cloud platforms, and other healthcare systems (ONC, n.d).
Role in Healthcare Data Exchange:
FHIR APIs support interoperability and conform with standards such as the Cures Act Final Rule, ensuring safe and consistent data transmission among providers, payers, and patients (ONC, n.d.).
 Real-Time Access: They allow for real-time data exchange, which improves clinical decision-making and care coordination (Mandel et al. 2016).
 Patient Empowerment: By allowing patients to access and share their health information with third-party applications, FHIR APIs promote patient-centered treatment.
 Integration Ease: They facilitate easier to integrate legacy systems with current healthcare technology, lowering implementation complexity (HL7 International, n.d).

Explanation of BPMN Model

The BPMN model illustrates the patient referral process from a Primary Care Clinic to a Hospital and Specialist. This model is divided into three key pools: Primary Care Clinic, Hospital Administration, and Specialist, with each representing specific roles in the referral workflow. 

1. Primary Care Clinic:  
   The process begins when a patient is referred by their primary care provider. The clinic receives the care plan, updates the patient’s medical records, and schedules follow-up care. Once these tasks are completed, the referral is sent to the hospital.

2. Hospital Administration:  
   The hospital receives the referral, and the administration reviews it. At this stage, there is a decision gateway to assess whether the referral is valid. If the referral is valid, the patient is registered at the hospital for further evaluation. If the referral is invalid, a clarification request is sent back to the primary care clinic to ensure accuracy. This step ensures the seamless flow of accurate information to avoid any delays or missteps in patient care.

3. Specialist’s Process:  
   After the patient is registered, the specialist evaluates the patient to determine if treatment is required. If no further care is needed, the patient is discharged with instructions. If treatment is necessary, the specialist provides care and reassesses whether follow-up care is required. If yes, the patient is referred to the primary care clinic. If no additional care is needed, the patient is discharged with proper documentation and instructions.

The BPMN model captures the critical interactions between the clinic, hospital, and specialist, highlighting decision points that prevent errors, ensure timely care, and maintain communication across the entities. It also ensures the patient’s journey is clear, well-coordinated, and focused on achieving the best possible outcomes.