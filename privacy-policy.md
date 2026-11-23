# Privacy Policy — CM Gantt Power BI Visual

**Publisher:** IshtanDeng  
**Contact:** support@ishtan.com.au  
**Effective date:** 29 June 2026  
**Last updated:** 23 November 2026

## 1. Overview

This Privacy Policy describes how the **CM Gantt** Power BI custom visual ("the Visual") handles data. The Visual is published by **IshtanDeng**, distributed free of charge through Microsoft AppSource, and licensed under the Standard Contract for Microsoft's commercial marketplace.

---

## 2. Data processed by the Visual

The Visual processes only the data you add to its field wells in Power BI:

| Data field | Purpose |
|---|---|
| Task ID, Task Name | Show task labels in the chart and task list |
| Start Date, End Date | Position task bars on the timeline |
| % Complete | Draw the progress fill inside bars |
| Dependencies | Draw dependency arrows and calculate the critical path |
| Category / Phase | Group tasks into collapsible phases |
| Resource | Show the task owner in the task list and tooltips |
| Milestone Flag | Draw milestone markers |
| Status, Color Field | Choose bar colours |

All of this data comes from your own Power BI data model, and you decide which fields the Visual receives.

---

## 3. Data storage and transmission

**The Visual does not collect or transmit any data, and it does not send data to the publisher or any third party.**

All processing (reading the fields, parsing dependencies, calculating the critical path and drawing the chart) happens inside Power BI, either in Power BI Desktop on your device or in the Power BI service. The Visual makes **no network requests** of any kind and does not request network access from Power BI.

The only information the Visual saves is part of the report itself. Like any Power BI visual, its formatting options (such as colours, time scale and toggles) are saved in the report by Power BI. To keep colours consistent when the report is filtered, these options also include the list of **Status** and **Category / Phase** values that the colour settings apply to. This information stays inside your Power BI report, is managed by Power BI like the rest of the report, and is never sent to the publisher.

---

## 4. Cookies and tracking

The Visual does not use cookies, local storage, session storage or any other browser storage, and it contains no analytics, telemetry or tracking of any kind.

---

## 5. Personal data

The Visual does not collect personal data about the people who use it. If your Power BI data model contains personal data (for example, employee names in the Resource field), that data is processed within Power BI only to draw the chart, and it remains subject to your organisation's data governance and to the [Microsoft Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement), which covers Power BI.

---

## 6. Third-party libraries

The Visual includes the following open-source components. They run entirely inside Power BI and do not transmit data.

| Library | Version | Licence |
|---|---|---|
| D3.js | 7.x | ISC |
| powerbi-visuals-utils-formattingmodel | 6.x | MIT |
| powerbi-visuals-api (Power BI visuals API definitions) | 5.11 | MIT |

---

## 7. Children's privacy

The Visual is a business productivity tool intended for professional use. It is not directed at children under the age of 13 and does not knowingly process data relating to children.

---

## 8. Changes to this policy

We may update this Privacy Policy if the Visual's handling of data changes. The **Last updated** date at the top of this page shows when it last changed. Continued use of the Visual after an update means you accept the revised policy.

---

## 9. Contact

For questions about this Privacy Policy:

**Ishtandeng Tech**  
Email: support@ishtan.com.au  
GitHub: https://github.com/ishtandeng/CM-Gantt-Public/issues
