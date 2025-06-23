
# Category Themes and Regulatory Sources

This document explains how category-level quality system themes were developed for the compliance mapping assets. It also outlines the regulatory frameworks used, the logic behind category grouping, and a glossary of terms for cross-functional clarity.

---

## 1. Why Category Themes Matter

Organizing compliance requirements by QMS theme (e.g., Deviation Management, Training & Qualification) allows teams to:

- Translate dense regulatory clauses into clear ownership areas
- Support collaboration between QA, MSAT, and process engineering teams
- Build system structure that supports ISO-to-GMP scalability

These themes also serve as the anchor for cross-framework mapping, SOP template alignment, and internal documentation maturity reviews.

---

## 2. Frameworks Used in Mapping Assets

The following regulatory frameworks were parsed and mapped across the two main tools in this folder:

- **ISO 9001:2015** – General industry quality management systems  
- **ISO 13485** – Quality systems for medical devices  
- **21 CFR 820** – FDA Quality System Regulation (devices)  
- **21 CFR 210/211** – GMP regulations for drugs  
- **ICH Q10** – Pharmaceutical Quality System framework

These frameworks were selected because of their relevance to manufacturing teams operating in ISO-certified, FDA-regulated, or pharma-compliant environments.

The mapping outputs were AI-assisted and spot-checked against publicly available summaries and official framework documentation for alignment. Frameworks such as **EU GMP Volume 4** and **PIC/S PE 009** were not explicitly included in the spreadsheets, but their structural similarities informed naming conventions and category logic during theme consolidation. Users are expected to validate all final mappings and examples against their own company’s QA standards and auditor expectations.

---

## 3. How Themes Were Consolidated

Where frameworks overlapped or used similar concepts, themes were grouped under shared categories. For example:

| Theme                     | Mapped Across These Frameworks (as applicable)         |
|--------------------------|--------------------------------------------------------|
| Deviation Management     | 21 CFR 820.100, ICH Q10.2, ISO 9001 clause 8.7         |
| Training & Qualification | ISO 9001 clause 7.2, ICH Q10.1, ISO 13485 clause 6.2   |
| Change Control           | ISO 9001 clauses 6.3, 7.5.6, ICH Q10.3, 21 CFR 820.30  |
| Document Control         | ISO 9001 clause 7.5, ICH Q10.1, 21 CFR 211.180         |

These categories allow cross-functional teams to frame their responsibilities using a simplified, reusable vocabulary — without losing traceability to original frameworks.

---

## 4. How This Supports the Toolkit Structure

Each asset in the `quality-compliance-starter-kit` is linked back to one or more category themes.

This provides:
- A stable backbone for SOP and tracker design
- Filtering logic in the clause breakdown table
- Compatibility with dashboarding or automated QA reporting
- Future scalability to support ISO, FDA, or hybrid QMS environments

If your organization already has internal categories or compliance pillars, this system can be adapted to reflect them.

---

## 5. Glossary

| Term               | Definition                                                                 |
|--------------------|---------------------------------------------------------------------------|
| QMS                | Quality Management System                                                 |
| CAPA               | Corrective and Preventive Action                                           |
| NCR                | Nonconformance Report                                                     |
| Deviation          | Documented departure from approved process or expectation                 |
| Change Control     | Formal process for evaluating and implementing modifications               |
| Function           | Team or role responsible for executing or reviewing an activity           |
| Owner              | Individual directly accountable for a requirement, record, or tool        |
| MSAT               | Manufacturing Sciences and Technology – typically owns scale-up processes |
| QA Review          | Independent review by quality staff for compliance or closure             |


## 6. Toolkit Asset-to-Theme Map

The table below maps each asset in this repository to the QMS theme(s) it supports. This is intended to help users understand how individual components of the starter kit align with broader compliance priorities and support scalable system development.

| Asset Filename                                      | Folder        | Linked Theme(s)                                              |
|-----------------------------------------------------|---------------|---------------------------------------------------------------|
| audit_log_v1_20250621.xlsx                          | /templates/   | Deviation Management, CAPA, QA Review                         |
| sop_template_v1_20250621.docx                       | /templates/   | Document Control, Change Management                           |
| training_matrix_v1_20250623.xlsx                    | /trackers/    | Training & Qualification                                      |
| change_tracker_v1_20250623.xlsx                     | /trackers/    | Change Management, CAPA                                       |
| implementation_timeline_v1_20250623.xlsx            | /trackers/    | Operational Planning, Cross-functional Coordination           |
| asset_ownership_table_v1_20250623.xlsx              | /trackers/    | Management Responsibility, Function Accountability            |
| compliance_clause_breakdown_table_v1_20250621.xlsx  | /reference/   | All QMS Themes (Filterable)                                   |
| cross-framework_mapping_matrix_v1_20250621.xlsx     | /reference/   | All QMS Themes (Cross-mapped across frameworks)               |

---

*For usage details of the mapping spreadsheets, see the [`README.md`](./README.md) file in this folder.*
