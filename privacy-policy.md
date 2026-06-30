# Privacy Policy — CM Gantt Power BI Visual

**Publisher:** IshtanDeng  
**Contact:** ishtandeng@gmail.com  
**Effective date:** 29 June 2026  
**Last updated:** 29 June 2026

## 1. Overview

This Privacy Policy describes how the **CM Gantt** Power BI custom visual ("the Visual") handles data. The Visual is published by **IshtanDeng** and distributed through Microsoft AppSource.

---

## 2. Data processed by the Visual

The Visual processes data that you supply through the Power BI field wells:

| Data field | Purpose |
|---|---|
| Task ID, Task Name | Render task labels in the chart |
| Start Date, End Date | Position task bars on the timeline |
| % Complete | Draw progress fill inside bars |
| Dependencies | Draw dependency arrows between tasks |
| Category / Phase | Group tasks into swimlanes |
| Resource | Display in tooltips |
| Milestone Flag | Render milestone markers |
| Status, Color Field | Determine bar colours |

All of this data originates from your own Power BI data model. You control what data is mapped to the Visual.

---

## 3. Data storage and transmission

**The Visual does not store, collect, or transmit any data.**

All computation — dependency parsing, critical path calculation, SVG rendering — is performed entirely within the Power BI client (Desktop, Service, or Embedded) on the end user's device or within the Microsoft Power BI cloud environment. No data is sent to any server operated by IshtanDeng or any third party.

The Visual makes **no external network requests** of any kind.

---

## 4. Cookies and tracking

The Visual does not use cookies, local storage, session storage, or any other tracking mechanism.

---

## 5. Personal data

The Visual does not collect personal data about end users. If your Power BI data model contains personal data (such as employee names in the Resource field), that data is processed locally by Power BI to render the chart and is subject to your organisation's own data governance and Microsoft's [Power BI Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement).

---

## 6. Third-party libraries

The Visual uses the following open-source libraries. These libraries run entirely within the Power BI client and do not transmit data externally.

| Library | Version | Licence |
|---|---|---|
| D3.js | 7.x | ISC |
| powerbi-visuals-api | 5.3.x | MIT |
| powerbi-visuals-utils-formattingmodel | 6.x | MIT |
| powerbi-visuals-utils-interactivityutils | 6.x | MIT |
| powerbi-visuals-utils-tooltiputils | 6.x | MIT |
| powerbi-visuals-utils-dataviewutils | 6.x | MIT |

---

## 7. Children's privacy

The Visual is a business productivity tool intended for adult professionals. It is not directed at children under the age of 13 and does not knowingly process data relating to children.

---

## 8. Changes to this policy

We may update this Privacy Policy when the Visual's data-handling behaviour changes. The **Last updated** date at the top of this document will reflect any revisions. Continued use of the Visual after a policy update constitutes acceptance of the revised policy.

---

## 9. Contact

For questions about this Privacy Policy:

**IshtanDeng**  
Email: ishtandeng@gmail.com  
GitHub: https://github.com/ishtandeng/CM-Gantt/issues
