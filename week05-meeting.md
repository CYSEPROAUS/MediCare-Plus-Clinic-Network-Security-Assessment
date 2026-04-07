# Week 5 Meeting Minutes

**Date:** Monday, 30 March 2026  
**Time:** 7:00 PM – 7:55 PM AEST  
**Platform:** Microsoft Teams  
**Attendees:** Carlos Gomez Mendez, Abdullah Naeem, Kishan Durlabhbhai Patel  
**Facilitator:** Carlos Gomez Mendez  
**Minutes recorded by:** Carlos Gomez Mendez  

---

## Agenda

1. Research and analysis progress update from each member  
2. Risk Assessment Table structure review  
3. Draft Report planning and structure  
4. Progress Report 1 preparation discussion  
5. Plan for Week 6  

---

## Discussion Summary

**1. Research and Analysis Progress**

*Carlos — NIST SP 800-30 Practice Entry:*  
Carlos completed a practice risk assessment entry using the likelihood-times-impact methodology applied to the clinic's Azure AD misconfiguration (missing MFA). The entry tested the rating approach independently before Abdullah's formal Risk Assessment Table development. Risk rated Likelihood 4, Impact 5, Score 20 — Critical. Carlos noted the rationale held up on self-review. Practice entry committed to /docs/research/.  

*Abdullah — Stakeholder Interview Plan:*  
Abdullah confirmed the stakeholder interview questions are finalised and committed to the repository. The Stakeholder Interview Plan artefact structure has been drafted and is in progress. Abdullah also began building the Risk Assessment Table column structure: Risk ID, Description, Category, Likelihood, Impact, Risk Score, Recommended Control.  

*Kishan — Cloud Architecture Review:*  
Kishan completed a first pass of the Azure cloud security review based on the case study evidence. Misconfigurations identified and documented:  
- NSG rules too permissive — inbound traffic unrestricted on multiple ports  
- MFA not enforced for any Azure AD accounts including Global Administrators  
- Azure Blob Storage containers set to public access — patient data potentially exposed  
- Azure Security Centre / Defender for Cloud not confirmed as configured  

Kishan began drafting the system architecture diagram and will have a first version ready for the Draft Report.  

---

**2. Risk Assessment Table Structure**  
Abdullah presented the column structure for the Risk Assessment Table. The team reviewed and agreed on the following additions:  

- A Category column to group risks (Cloud/Identity, Network, Data, Endpoint, Governance)  
- A Risk Score label combining the numeric score with a severity band (e.g., "20 — Critical")  
- An alignment note column to reference ISM or NIST SP 800-53 controls in the final version  

The team agreed on a target of at least 10 risks for the draft table, with a minimum of 2 in each category.  

---

**3. Draft Report Planning**  
The Draft Report is due mid-term. Carlos will author the report structure and compile contributions from all members. Sections confirmed:  

- Section 1: Introduction (Carlos)  
- Section 2: System Overview — 2.1 Physical Infrastructure, 2.2 Azure Cloud, 2.3 Data and Identity (Carlos, drawing on Kishan's cloud findings)  
- Section 3: Delivered Technical Artefacts — table format (Carlos)  
- Section 4: Contributions — table format (Carlos)  
- Section 5: Stakeholder Interview Questions (Abdullah)  
- Section 6: Risk Assessment Table Draft (Abdullah)  

All members to provide their input to Carlos by end of Week 6 for compilation.  

---

**4. Progress Report 1**  
Progress Report 1 is due Friday 17 April 2026. The team discussed what each member needs to include. Carlos noted the assessment requires verifiable evidence — the meeting minutes, GitHub commit history, and research notes committed to the repository are the primary evidence sources. Each member is responsible for their own individual submission.  

---

## Action Items

| Action | Owner | Due |
|---|---|---|
| Complete Risk Assessment Table draft (minimum 10 risks) | Abdullah | End of Week 6 |
| Complete system architecture diagram v1 | Kishan | End of Week 6 |
| Compile Draft Report from all member inputs | Carlos | End of Week 6 |
| Commit Azure gap analysis notes to /docs/research/ | Kishan | End of Week 5 |
| Begin writing Progress Report 1 | All | End of Week 6 |

---

## Next Meeting

**Date:** Monday, 6 April 2026, 7:00 PM AEST  

**Agenda items to carry forward:**  
- Draft Report final review before submission  
- Progress Report 1 status check  
- Milestone 2 completion review  
