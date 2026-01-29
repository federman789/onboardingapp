# Onboarding Learning Portal — Work Sample Repository (Sanitised)

This repository contains **supporting artefacts** from an enterprise **Power Platform onboarding learning portal** project delivered (Power Apps + Dataverse + Power Automate, with usage monitoring via Application Insights).  
It’s intended as a companion to my CV bullet point, showing how I document, validate, and improve solutions in a real delivery context.

Some of the content has been greyed out or modified for privacy purposes.


## Folder guide
### 01_PM_Docs
Project/program materials used to align stakeholders and delivery teams. Includes:
 [01_FY22 Onboarding App]: A presentation with screenshots used to give context to stakeholders who are getting their feet wet with the user experience
 [02_Bill of Materials Template]: A bill of materials template used by program managers to deliver the learning content details which they require to be displayed to learners (new employees) from specific roles in their programs/solution areas. This document was built by us to streamline the information gathering process.
 
### 02_App_Documentation
Application documentation, including:
 - [01_Data_Model]: Data model diagram and data dictionary for the relational database used in the solution
 - [02_App_Documentation]: A user guide and technical documentation document for stakeholders who want to understand better how the app works and pulls learning content from the back end.

### 03_Accessibility
Materials from an accessibility review and remediation workstream, including:
- [01._Onboarding_App_Accessibility:_Summary_(Internal)] : Nextant internal presentation for internal technical team (Nextant Solutions), explaining the Accessibility workstream within the Onboarding app project, and the general effort implications of making a Power App fully accessible according to technical standards.
- [02._Context-Canvas_Apps_Power_Apps_Best_Practices-_AccessibleDesign_v1]: Document provided by the MSFT Accessibility team to introduce accessibility standards.
- [03._Onboarding_app-inclusive_design_consult_07192022] : Initial visually aided diagnosis from the MSFT Accessibility team, highlighting main accessibility issues at a high level.
- [04._Onboarding_app_Accessibility_bugs] : Detailed board for progress tracking of accessibility bugs resolution. Each line item maps to a workitem in Azure Dev Ops.  

### 04_UAT_New_Feature
- UAT materials for a new feature release (test instructions, session approach, and evidence of validation with business testers). The feature allows the user to select the experience that they want: based on their selection they'd see higher priority assets only or the full default content.

### 05_Solution_Package
- Solution export/package artefact. These are included as reference only and may require environment-specific dependencies (connections, environment variables, security roles) to import. Also includes a snip of the OnStart code of the front end experience (Canvas App)

