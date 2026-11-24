# Supply Chain Planning Portfolio

Supply chain and Kinaxis consultant with a Japanese bilingual background. I work across Kinaxis RapidResponse / Maestro (demand planning), SAP S/4HANA Sales (order-to-cash), and enterprise support, and I have worked directly with global and Japanese clients in the consumer goods, chemicals, beverage, and semiconductor sectors.

This repository collects my working notes, templates, and small tools. Everything is generalized: there is no client data, no client names, and no confidential project material.

## Experience at a glance

| Period | Role | Focus |
|---|---|---|
| 2025 to present | Demand Planning Maestro consultant (Accenture Strategy and Consulting) | End-to-end Kinaxis demand planning implementation for a US chemical client: statistical forecasting, consensus demand, S&OP workbooks, validation, migration requirements |
| May 2025 to Oct 2025 | Bilingual technical support analyst | Japanese semiconductor client: SAP S/4HANA sales ticket support, documentation translation, requirement gathering in both languages |
| May 2024 to Nov 2024 | Bilingual technical support analyst | SAP AMS for a Japanese beverage company: SAP SD order-to-cash from transition to go-live, health checks, KT |
| Dec 2019 to Apr 2024 | Assistant technical service engineer (Fujitsu Consulting India) | Private cloud operations on VMware for Japanese clients, ServiceNow ticketing, vendor coordination |

See `case-studies/` for the detail behind each one.

## Certifications

- Kinaxis RapidResponse Solution Consultant Level 1, with the Demand Planning and Aggregate Supply Planning application badges
- SAP Certified Application Associate, SAP S/4HANA Sales (Private Cloud)
- SAP IBP basics (trained)
- Anaplan Level 1
- Japanese: NAT-TEST Q3, JLPT N4, N2 in progress

## Repository guide

| Folder | Contents |
|---|---|
| `kinaxis-notes/` | Ten structured notes: data model, resource authoring, demand planning, supply planning, integration, access control, troubleshooting, migration, a certification study map, and a glossary |
| `sap-sd-notes/` | Organizational structure, master data, order-to-cash, pricing, schedule lines, special processes, an AMS runbook, and a reference of common transactions and tables |
| `support-and-operations/` | Incident, problem, and change practice, ticket handling, KT and SOP writing |
| `cloud-infrastructure-notes/` | VMware and network fundamentals from private cloud operations |
| `japanese-for-it-consulting/` | English to Japanese glossary for supply chain, SAP, and IT work, plus business email phrases |
| `case-studies/` | Anonymized write-ups of the engagements above |
| `templates/` | Plain CSV and Markdown templates: KT, UAT, cutover, validation, RAID log, ticket log, SOP, status report |
| `tools/` | Python tools (standard library only): forecast accuracy metrics and a source-versus-target data comparison for migration validation |
| `japanese-n2-flashcards/` | Offline flashcard app with work-related N2 vocabulary |

## Skills

- **Planning:** demand planning, statistical forecasting, consensus demand, S&OP, aggregate supply planning, what-if scenario analysis, forecast accuracy and bias
- **Kinaxis:** RapidResponse and Maestro, data model, resource authoring, data integration, access control, migration analysis
- **SAP:** S/4HANA Sales and Distribution, order-to-cash, pricing, schedule line categories, returns and memos, AMS support
- **Delivery:** requirement gathering, UAT, cutover, JIRA task breakdown, KT delivery, client liaison
- **Operations:** ServiceNow, VMware administration, network basics, vendor coordination
- **Languages:** Japanese (bilingual working proficiency), English, Tamil, Telugu, German (basic)

## Tools quick start

```
cd tools
python3 forecast_metrics.py sample-data/forecast_sample.csv
python3 data_compare.py sample-data/source.csv sample-data/target.csv --keys part,site
python3 -m unittest discover tests
```

## Contact

LinkedIn: https://www.linkedin.com/in/pavithra-bhavani-shankar-a09064194/

## License

MIT, see `LICENSE`. Notes are my own study material, not official documentation. Check product behaviour against the official documentation for your version.
