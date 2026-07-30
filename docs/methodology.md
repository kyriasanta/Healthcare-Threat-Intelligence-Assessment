# Analytical Methodology

## Study design

This project uses a descriptive, retrospective analysis of **146** vulnerabilities added to the CISA Known Exploited Vulnerabilities Catalog between **January 07, 2026** and **June 29, 2026**.

## Dataset summary

- Records: 146
- Unique vendors: 69
- Critical: 5
- High: 5
- Moderate: 98
- Low: 38
- Known ransomware campaign association: 19

## Prioritization model

| Factor | Maximum points |
|---|---:|
| Plausible healthcare technology relevance | 3 |
| Internet-facing or remote-access relevance | 2 |
| Known ransomware campaign association | 3 |
| Technical-impact indicator | 3 |
| Remediation urgency | 2 |
| Operational impact | 3 |

Priority thresholds: Critical 13-16; High 9-12; Moderate 5-8; Low 0-4.

## Research and ATT&CK standards

Vendor advisories, CISA, NIST NVD, and MITRE ATT&CK were prioritized. ATT&CK mappings are labeled as observed, assessed, or conditional. Unsupported post-compromise behavior is omitted.

## Limitations

Northstar Regional Health is fictional. No real asset inventory, scanner output, logs, architecture, or business-impact data were used. The scoring model is educational and is not independently validated.
