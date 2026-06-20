
# AI-Enabled Radiology Workflow using BPMN 2.0

This project presents a BPMN 2.0 workflow model for an end-to-end radiology process, integrating healthcare systems and standards such as HIS, RIS, PACS, HL7, DICOM, and AI-assisted analysis.

## Workflow Overview

The workflow follows the patient's imaging journey from registration and imaging order creation, through scheduling, image acquisition, DICOM archiving, AI-assisted analysis, radiologist validation, and final report delivery back to the HIS.

## Main Components

- Hospital Information System (HIS)
- Radiology Information System (RIS)
- PACS
- AI Engine
- Radiologists
- Modality Technologists

## Key Concepts

- HL7 ORM imaging orders
- Modality Worklist retrieval
- DICOM image acquisition and archiving
- AI-generated findings
- Structured radiology reporting
- HL7 ORU result messages
- Accession Number as the central workflow identifier

## Workflow Snapshot

![Workflow Snapshot](Workflow_Snapshot.png)

## Files

- `Radiology_Workflow.bpmn` — BPMN 2.0 source file
- `Workflow_Snapshot.png` — visual snapshot of the workflow

## Future Enhancements

- FHIR integration
- Critical findings notification
- AI triage workflow
- Voice recognition reporting
- Peer review process
