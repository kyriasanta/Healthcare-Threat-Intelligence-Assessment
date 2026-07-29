# Collection Plan

## Primary Data Source

CISA Known Exploited Vulnerabilities Catalog

Purpose:
Identify vulnerabilities with documented evidence of active exploitation.

Fields expected to support the analysis include:

- CVE identifier
- Vendor
- Product
- Vulnerability name
- Date added to the catalog
- Required remediation action
- Remediation due date
- Known ransomware campaign use
- Description
- Notes
- CWE classification, when provided

## Supporting Sources

For the highest-priority vulnerabilities, supporting information may be
collected from:

1. CISA advisories
2. NIST National Vulnerability Database
3. Original vendor security advisories
4. MITRE ATT&CK
5. Other authoritative government publications

## Collection Period

The analysis includes vulnerabilities added to the CISA catalog between
January 1, 2026, and June 30, 2026.

## Collection Rules

- Preserve the original dataset without modification.
- Record the date the dataset was downloaded.
- Separate observed facts from analytical assessments.
- Prefer primary and authoritative sources.
- Avoid exploit code, malware samples, and intrusive testing.
- Record conflicting or missing information.
- Cite the source for every vulnerability profile.

## Intelligence Gaps

The project does not have access to:

- Northstar Regional Health's actual asset inventory
- Patch-management data
- Vulnerability scanner results
- Security logs
- Exposure-management data
- Business-impact assessments
- Third-party vendor contracts
