<pre style="white-space: pre; overflow-x: auto; font-family: Consolas, 'Courier New', monospace; font-size: 14px; line-height: 1.35; background: transparent; border: 0; padding: 0; margin: 0;">SECTION 18
Validation Standards
18.1 Purpose

The Validation Standards establish the minimum quality requirements for the completed A2 Audit Planning Memo.

The purpose of validation is to confirm that the planning methodology has been applied consistently and that the completed planning memorandum accurately represents the structured planning dataset.

Validation occurs after BUILD has completed and before the planning memorandum is considered final.

18.2 Validation Objective

Validation shall confirm that the completed planning memorandum:

accurately reflects the structured planning dataset;
complies with this methodology;
preserves the approved template;
contains no incomplete sections;
contains no unresolved placeholders;
is suitable for Internal Audit review.

Validation shall verify document quality.

It shall not introduce new planning information.

18.3 Validation Sequence

Validation shall be performed in the following order.

Dataset Validation
Template Validation
Section Validation
Formatting Validation
Document Validation
Final Approval Review

Each stage shall be completed before proceeding to the next.

18.4 Dataset Validation

Dataset Validation confirms that the structured planning dataset satisfies the requirements established within Section 16.

Confirm that:

every required field exists;
required arrays exist;
required narrative fields exist;
field names match the approved data model;
no undocumented fields have been introduced;
no required values have been omitted.

If Dataset Validation fails, BUILD shall not proceed.

18.5 Template Validation

Template Validation confirms that the approved A2 Audit Planning Memo template has been populated correctly.

Confirm that:

every required placeholder has been replaced;
no placeholder text remains;
required tables have been populated;
no complete or fragmented designated replacement tag remains within paragraphs, tables, headers, footers, or content controls;
section headings remain unchanged;
document structure remains unchanged;
the Audit Scope section remains unchanged;
the Review &amp; Approval section remains unchanged;
no protected content has been removed, rewritten, or reformatted.

No designated replacement tag or designated population instruction shall remain within sections populated by BUILD.

Instructional content contained within the protected Audit Scope and Review &amp; Approval sections shall remain unchanged and is excluded from this requirement.

18.6 Section Validation

Each planning section shall satisfy the methodology established within Sections 6 through 15.

Confirm that:

every required section has been populated;
required sections are not empty unless permitted by this methodology;
section ordering remains unchanged;
section titles remain unchanged;
planning content corresponds to the appropriate section.

Planning information shall not appear within an incorrect section.

18.7 Formatting Validation

Formatting Validation confirms that BUILD preserved the approved document format.

Confirm that:

all inserted content uses Times New Roman;
all inserted content uses 11-point font;
all inserted content is black;
inserted content is non-italic unless italics are explicitly required;
bold formatting appears only where required;
paragraph alignment remains consistent with the template;
paragraph spacing remains consistent with the template;
table borders and shading remain unchanged;
table content uses the alignment of the model row;
document margins and page structure remain unchanged;
headers and footers remain unchanged except for designated tag replacement.

If any inserted content fails these requirements, validation shall fail.

18.8 Content Validation

Content Validation confirms that planning information has been preserved during BUILD.

Confirm that:

planning information has not been rewritten;
documented wording has not been altered without methodology support;
findings remain complete;
advisory items remain complete;
regulatory comments remain complete;
ordering has been preserved.

BUILD shall not modify planning decisions established during extraction.

18.9 Completeness Validation

The completed planning memorandum shall be reviewed as a whole.

Confirm that:

every required section is present;
no required information has been omitted;
duplicate planning information has not been introduced;
unsupported information has not been introduced;
the planning memorandum provides a complete planning narrative.

Completeness shall be evaluated according to this methodology rather than document length.

18.10 Error Conditions

Validation shall fail when any of the following conditions exist.

required section missing;
unresolved placeholder remains;
required table incomplete;
dataset inconsistency identified;
formatting materially differs from the approved template;
planning information omitted;
unsupported planning information introduced;
document export incomplete.

Documents failing validation shall not be considered complete.

18.11 Validation Outcome

Validation shall produce one of the following results.

Pass

The completed planning memorandum satisfies every validation requirement established by this methodology.

The document may proceed for Internal Audit review.

Fail

One or more validation requirements have not been satisfied.

The identified deficiencies shall be corrected before the planning memorandum proceeds.

Partial validation shall not be considered acceptable.

18.12 Relationship to Other Sections

Validation represents the final quality assurance process applied to the completed planning memorandum.

Validation shall confirm compliance with:

Planning Philosophy;
Planning Information Hierarchy;
Information Classification Framework;
A2 Planning Framework;
Section Methodologies;
JSON Data Model;
BUILD Methodology.

Validation shall not modify planning decisions.

Any required correction shall occur before the planning memorandum is finalized.

18.13 Quality Review

Before approving the completed planning memorandum, confirm:

all validation stages have been completed;
every required section complies with this methodology;
BUILD has completed successfully;
no unresolved validation errors remain;
the planning memorandum accurately represents the structured planning dataset;
the document is suitable for Internal Audit review.

If any condition is not satisfied, the planning memorandum shall be revised and revalidated.

18.14 Methodology Note
Validation is the final quality assurance activity performed before completion of the A2 Audit Planning Memo.
Its purpose is to confirm that the planning methodology has been applied consistently from information extraction through document generation.
Validation shall verify compliance with this methodology.
It shall not introduce new planning information, modify planning decisions, or replace documented information established during the planning process.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 19
Cross-Section Consistency
19.1 Purpose

The Cross-Section Consistency methodology establishes the relationships that shall remain consistent across the completed A2 Audit Planning Memo.

The purpose of this section is to ensure that the planning memorandum functions as one integrated planning document rather than a collection of independently prepared sections.

Each section shall independently satisfy its planning objective while remaining consistent with the remainder of the planning memorandum.

19.2 Planning Objective

Cross-Section Consistency shall ensure that:

planning information remains internally consistent;
current-state information is presented consistently throughout the memorandum;
historical information remains historically accurate wherever referenced;
duplicate information does not become contradictory;
all planning sections collectively describe one documented operating environment.

Consistency shall be evaluated across the completed planning memorandum rather than within individual sections.

19.3 Current-State Consistency

All current-state sections shall describe the same documented operating environment.

Accordingly:

the Overview shall remain consistent with Current Events;
Current Events shall remain consistent with Systems / Applications / Models / Vendors;
Regulatory Requirements shall remain consistent with documented regulatory developments;
Related Departments and Activities shall remain consistent with organizational relationships;
Relevant Risks shall be supported by the documented current operating environment.

Conflicting descriptions of the current operating environment shall not appear.

19.4 Historical Information Consistency

Historical planning information shall remain internally consistent throughout the planning memorandum.

Accordingly:

Report Number shall remain identical wherever referenced;
Report Date shall remain identical wherever referenced;
Audit Opinion shall remain identical wherever referenced;
Findings shall remain identical wherever referenced;
Finding Numbers shall remain aligned with their corresponding findings;
Advisory Items shall remain unchanged wherever referenced;
Regulatory Comments shall remain consistent throughout the planning memorandum.

Historical information shall not be rewritten to accommodate current planning.

19.5 Cross-Section Relationships

Certain sections depend upon information established elsewhere within the planning memorandum.

Accordingly:

The Overview establishes the understanding of the auditable function.

Current Events describes changes affecting that understanding.

Systems / Applications / Models / Vendors identifies the technology supporting the function.

Regulatory Requirements identifies the governing requirements applicable to the function.

Related Departments and Activities identifies organizational dependencies.

Relevant Risks identifies planning risks affecting the documented operating environment.

Prior Audit Information establishes the documented historical audit record.

Open and Expected Issues / Regulatory Comments interprets the planning significance of that historical record.

Each section shall support the others without unnecessary duplication.

19.6 Information Placement Consistency

Planning information should normally appear within one primary section.

When information is intentionally referenced in multiple sections, the information shall remain consistent.

Examples include:

a newly implemented production system appearing in both Current Events and Systems;
a documented regulatory change appearing in both Current Events and Regulatory Requirements;
historical audit information appearing in both Prior Audit Information and Open and Expected Issues.

Repeated information shall preserve the same documented meaning.

19.7 Dataset Consistency

The structured planning dataset shall remain consistent with the completed planning memorandum.

Accordingly:

every populated planning section shall correspond to its dataset field;
populated tables shall correspond to dataset arrays;
narrative sections shall correspond to narrative fields;
ordering shall remain unchanged.

The planning memorandum shall not contain information absent from the structured planning dataset.

Likewise, documented planning information contained within the dataset shall not be omitted from the completed planning memorandum.

19.8 BUILD Consistency

BUILD shall preserve consistency established during extraction.

Accordingly, BUILD shall not:

reinterpret planning information;
reorganize findings;
modify advisory items;
change ordering;
introduce additional planning content;
remove documented planning information.

BUILD shall preserve, rather than transform, the structured planning dataset.

19.9 Common Consistency Errors

The following represent common consistency failures.

Incorrect

The Overview identifies Microsoft Defender as the endpoint protection platform while the Systems section identifies Cisco Secure Endpoint as the production platform.

The completed planning memorandum describes two different current operating environments.

Incorrect

A finding is omitted from Open and Expected Issues despite appearing within Prior Audit Information.

Historical information is no longer internally consistent.

Incorrect

The Audit Name differs between the document title and the generated filename.

The planning memorandum no longer represents one engagement.

Correct

Every section describes the same documented operating environment.

Historical information remains identical wherever referenced.

Planning information appears in the appropriate section without contradiction.

19.10 Final Consistency Review

Before final approval of the planning memorandum, confirm:

the Audit Name remains identical throughout the document;
current-state descriptions do not conflict;
historical audit information remains consistent;
systems are described consistently wherever referenced;
regulatory information remains consistent;
organizational relationships remain consistent;
risks are supported by preceding planning sections;
findings remain aligned with finding numbers;
advisory items remain unchanged wherever referenced;
document sections collectively describe one documented operating environment.

Any inconsistency shall be resolved before the planning memorandum is finalized.

19.11 Relationship to Other Sections

Cross-Section Consistency is the final methodology chapter.

It applies to the completed planning memorandum after:

planning methodology has been applied;
structured planning data has been created;
the planning memorandum has been generated;
validation has been completed.

This chapter does not introduce additional planning requirements.

Instead, it confirms that the completed planning memorandum represents one complete, internally consistent planning document.

19.12 Methodology Note
Cross-Section Consistency represents the final quality assurance review of the completed A2 Audit Planning Memo.
Its purpose is to confirm that every section works together to describe a single documented planning narrative.
The completed planning memorandum should therefore read as one cohesive Internal Audit planning document rather than a collection of independently generated sections.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

APPENDIX A
End-to-End Planning Workflow Example

Purpose

This appendix demonstrates application of the A2 Audit Planning Methodology from initial planning documentation through generation of the completed A2 Audit Planning Memo.

The example illustrates application of the methodology described throughout this document and is intended solely for illustrative purposes.

The example does not represent an actual audit engagement.

A.1 Source Documentation

The following excerpts represent planning documentation received at the beginning of an audit engagement.

Audit Planning Questionnaire
Audit Name
Endpoint Security
Question 1a – Functional Overview
Endpoint Security provides centralized management and monitoring of
enterprise endpoint protection technologies.

The function is managed by Information Security and supports malware
prevention, endpoint detection and response, policy management, and
incident response activities across the enterprise.
Question 1b – Current-Year Changes
Microsoft Defender replaced Cisco Secure Endpoint during the current year.
Question 3 – Key Contacts
Name	Role
John Smith	Director of Information Security
Mary Jones	Security Operations Manager
Question 4 – Regulatory Requirements
FFIEC Cybersecurity Assessment Tool (CAT)

CIS Controls Version 8
Question 5 – Systems / Applications / Vendors
Microsoft Defender

Splunk

Expel
Question 6 – Related Departments
Information Security – Governance

Infrastructure – Endpoint deployment

Enterprise Risk Management – Risk oversight
Question 8 – Relevant Risks
Enterprise endpoints remain a significant target for malware and
ransomware attacks.

Centralized endpoint monitoring remains critical to enterprise security.
Prior Audit Report

Report Number

R24-17-03

Report Date

March 15, 2024

Audit Opinion

Satisfactory with Exceptions

Finding Number

1

Finding

Endpoint monitoring procedures were not consistently documented.

Risk Rating

Moderate

Status

Open

Status Date

June 2025

Expected Completion

September 2025
A.2 Application of the Methodology

Following application of:

Planning Information Hierarchy
Information Classification Framework
Current-State Determination
Section Methodologies

the planning information is organized into the following structured planning dataset.

A.3 Structured Planning Dataset
{
  "AUDIT_NAME": "Endpoint Security",

  "OVERVIEW":
  "Endpoint Security provides centralized management and monitoring of enterprise endpoint protection technologies. The function is managed by Information Security and supports malware prevention, endpoint detection and response, policy management, and incident response activities.",

  "CURRENT_EVENTS":
  "Microsoft Defender replaced Cisco Secure Endpoint and is now the enterprise endpoint protection platform.",

  "KEY_CONTACTS": [
    {
      "name": "John Smith",
      "role": "Director of Information Security"
    },
    {
      "name": "Mary Jones",
      "role": "Security Operations Manager"
    }
  ],

  "REGULATORY_REQUIREMENTS":
  "FFIEC Cybersecurity Assessment Tool (CAT)\nCIS Controls Version 8",

  "KEY_SYSTEMS_APPLICATIONS_MODELS_AND_VENDORS":
  "Microsoft Defender\nSplunk\nExpel",

  "RELATED_DEPARTMENTS_AND_ACTIVITIES": [
    {
      "department": "Information Security",
      "activity": "Governance",
      "scope": "",
      "reason": ""
    },
    {
      "department": "Infrastructure",
      "activity": "Endpoint deployment",
      "scope": "",
      "reason": ""
    },
    {
      "department": "Enterprise Risk Management",
      "activity": "Risk Oversight",
      "scope": "",
      "reason": ""
    }
  ],

  "RELEVANT_RISKS":
  "Enterprise endpoints remain a significant target for malware and ransomware attacks. Effective endpoint protection and centralized monitoring remain critical to reducing enterprise cybersecurity risk.",

  "REPORT_NUMBER":
  "R24-17-03",

  "REPORT_DATE":
  "March 15, 2024",

  "AUDIT_OPINION":
  "Satisfactory with Exceptions",

  "FINDINGS_REPORTED": [
  {
    "finding_number": "1",
    "risk_rating": "Moderate",
    "description": "Endpoint monitoring procedures were not consistently documented.",
    "status": "Open",
    "status_date": "June 2025",
    "expected_completion_date": "September 2025"
  }
],

  "FINDING_NUMBERS": [
    "1"
  ],

  "ADVISORY_ITEMS": [],

  "REGULATORY_COMMENTS": "",

  "OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS": "The most recent Endpoint Security Audit Report (R24-17-03) was issued on March 15, 2024, with an audit opinion of \"Satisfactory with Exceptions.\" The final report noted one Moderate finding, and the previous year's Findings Summary listed no advisory items; see below for additional details regarding the issues identified:\n\nFindings Reported\n\n1 – Endpoint monitoring procedures were not consistently documented. As of June 2025, this finding remains Open, with an expected completion date of September 2025.\n\nAdvisory Items\n\nNo advisory items were identified.\n\nRegulatory Comments\n\nThere were no regulatory comments issued for this audit."
}

A.4 BUILD Process

The BUILD Methodology uses only:

the approved A2 Audit Planning Memo template; and
the structured planning dataset.

The BUILD process:

loads the approved template;
loads the structured planning dataset;
populates each template placeholder;
populates all required tables;
applies standardized formatting;
validates the completed planning memorandum; and
exports the completed document.

No planning documents are consulted during BUILD.

No planning decisions occur during BUILD.

A.5 Completed A2 Audit Planning Memo
Overview

Endpoint Security provides centralized management and monitoring of enterprise endpoint protection technologies. The function is managed by Information Security and supports malware prevention, endpoint detection and response, policy management, and incident response activities across the enterprise.

Current Events

Microsoft Defender replaced Cisco Secure Endpoint and is now the enterprise endpoint protection platform supporting production operations.

Key Contacts
Name	Role
John Smith	Director of Information Security
Mary Jones	Security Operations Manager
Regulatory Requirements
FFIEC Cybersecurity Assessment Tool (CAT)
CIS Controls Version 8
Systems / Applications / Models / Vendors
Microsoft Defender
Splunk
Expel
Related Departments and Activities
Department	Activity
Information Security	Governance
Infrastructure	Endpoint Deployment
Enterprise Risk Management	Risk Oversight
Relevant Risks

Enterprise endpoints remain a significant target for malware and ransomware attacks. Effective endpoint protection and centralized monitoring remain critical to reducing enterprise cybersecurity risk.

Prior Audit Information

Report Number

R24-17-03

Report Date

March 15, 2024

Audit Opinion

Satisfactory with Exceptions

Finding 1

Endpoint monitoring procedures were not consistently documented.

Open and Expected Issues / Regulatory Comments

The most recent Endpoint Security Audit Report (R24-17-03) was issued on March 15, 2024, with an audit opinion of "Satisfactory with Exceptions." The final report noted one Moderate finding, and the previous year's Findings Summary listed no advisory items; see below for additional details regarding the issues identified:

Findings Reported

1 – Endpoint monitoring procedures were not consistently documented. As of June 2025, this finding remains Open, with an expected completion date of September 2025.

Advisory Items

No advisory items were identified.

Regulatory Comments

There were no regulatory comments issued for this audit.

A.6 Methodology Demonstrated

This example illustrates application of the complete A2 Audit Planning Methodology.
Specifically, it demonstrates:
evaluation of planning documentation using the Planning Information Hierarchy;
classification of documented information using the Information Classification Framework;
determination of the documented current operating environment;
application of each section methodology;
creation of the structured planning dataset;
generation of the completed A2 Audit Planning Memo using the BUILD Methodology; and
validation of the completed planning memorandum.
The completed planning memorandum therefore represents the application of this methodology rather than reproduction of the underlying planning documentation.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

APPENDIX B
Common Errors
Purpose

This appendix documents common errors encountered during preparation of the A2 Audit Planning Memo and demonstrates the correct application of the A2 Audit Planning Methodology.

The examples contained within this appendix are illustrative only.

Each example identifies:

the incorrect approach;
the reason the approach violates this methodology;
the correct application of the methodology; and
the methodology sections governing the correction.
Error 1
Copying Questionnaire Responses Verbatim
Incorrect

Endpoint Security provides centralized management and monitoring of enterprise endpoint protection technologies supporting malware prevention and endpoint detection.

Why This Is Incorrect

The A2 Planning Memo communicates Internal Audit's understanding of the auditable function.

It is not intended to reproduce planning documentation.

Verbatim reproduction prevents consolidation of documented planning information into a planning narrative.

Correct Application

Prepare a planning narrative that preserves the documented meaning while organizing the information into concise Internal Audit planning documentation.

Applicable Methodology
Overview Methodology
Narrative Standards
Information Consolidation
Error 2
Copying Planning Meeting Notes
Incorrect

Joe stated Microsoft Defender should be fully deployed next month.

Request updated screenshots during fieldwork.

Why This Is Incorrect

Planning Meeting Notes frequently contain:

auditor reminders;
meeting dialogue;
planning administration;
evidence requests.

These statements support planning activities rather than describe the auditable function.

Correct Application

Only documented current-state facts contained within Planning Meeting Notes may supplement the planning memo.

Meeting dialogue shall be excluded.

Applicable Methodology
Planning Philosophy
Information Classification Framework
Current Events Methodology
Error 3
Treating "No Change" as "No Information"
Incorrect

Questionnaire

No Change

Planning Memo

Not specified in the provided source documents.

Why This Is Incorrect

"No Change" confirms that the documented baseline remains applicable.

It does not remove previously documented planning information.

Correct Application

Retain the documented baseline information unless newer documented information explicitly replaces it.

Applicable Methodology
Baseline Retention
Planning Information Hierarchy
Regulatory Requirements
Related Departments
Relevant Risks
Error 4
Including Retired Technologies
Incorrect

Systems

Cisco Secure Endpoint
Microsoft Defender

Planning documentation states Cisco Secure Endpoint was replaced.

Why This Is Incorrect

The Systems section describes the documented current production environment.

Retired technologies shall not remain unless historical context is specifically required.

Correct Application

Include Microsoft Defender.

Exclude Cisco Secure Endpoint.

Applicable Methodology
Current-State Determination
Systems / Applications / Models / Vendors
Error 5
Confusing Current Events with Relevant Risks
Incorrect

Current Events

Malware represents a significant cybersecurity threat.

Relevant Risks

Microsoft Defender replaced Cisco Secure Endpoint.

Why This Is Incorrect

Current Events describes documented changes.

Relevant Risks describes conditions that may materially affect the auditable function.

The two planning objectives are different.

Correct Application

System replacement belongs within Current Events.

Malware exposure belongs within Relevant Risks.

Applicable Methodology
Current Events
Relevant Risks
Error 6
Treating Operational Activities as Risks
Incorrect

Relevant Risks

Quarterly user access reviews are performed.

Why This Is Incorrect

The statement describes an operational control.

It does not describe a planning risk.

Correct Application

Exclude the operational-control statement from Relevant Risks.

A risk may be included only when the underlying risk is explicitly documented elsewhere within the planning sources.

Do not convert a documented control activity into an inferred risk statement.
Error 7
Omitting Historical Findings
Incorrect

Prior Audit Information

Finding 1

Finding 3

Finding 2 omitted.

Why This Is Incorrect

Historical findings establish the documented audit record.

Every documented finding shall be preserved.

Correct Application

Extract every documented finding in documented order.

Applicable Methodology
Prior Audit Information
Open and Expected Issues
Error 8
Rewriting Historical Findings
Incorrect

Original

Endpoint monitoring procedures were not consistently documented.

Planning Memo

Monitoring controls require improvement.

Why This Is Incorrect

Historical findings represent issued audit documentation.

Issued findings shall not be rewritten.

Correct Application

Preserve documented wording exactly.

Current remediation status may supplement the finding.

Applicable Methodology
Prior Audit Information
Open and Expected Issues
Error 9
Assigning Finding Numbers to Advisory Items
Incorrect

Finding 1

Advisory Item 2

Why This Is Incorrect

Advisory items are not findings.

Finding numbers shall only identify documented audit findings.

Correct Application

Present advisory items independently.

Applicable Methodology
Prior Audit Information
Open and Expected Issues
Error 10
Inferring Undocumented Information
Incorrect

Planning documentation lists:

John Smith

Planning Memo

John Smith — Chief Information Security Officer

No documented title exists.

Why This Is Incorrect

Roles shall not be inferred.

Planning documentation must support every populated value.

Correct Application

John Smith

Applicable Methodology
Key Contacts
Planning Philosophy
Error 11
Inconsistent Audit Names
Incorrect

Document Title

Endpoint Security

Open Issues

Enterprise Endpoint Security

Filename

Endpoint Protection

Why This Is Incorrect

The planning memorandum represents one engagement.

The Audit Name shall remain identical throughout the document.

Correct Application

Use one documented Audit Name everywhere.

Applicable Methodology
Audit Name
Cross-Section Consistency
Error 12
Contradictory Current-State Information
Incorrect

Overview

Microsoft Defender

Systems

Cisco Secure Endpoint

Why This Is Incorrect

The completed planning memorandum describes two different operating environments.

Correct Application

Every section shall describe the same documented current operating environment.

Applicable Methodology
Current-State Determination
Cross-Section Consistency
Error 13
Leaving Template Placeholders
Incorrect
&lt;&lt;GPT_FILL:OVERVIEW&gt;&gt;

appears in the completed planning memorandum.

Why This Is Incorrect

BUILD has not completed successfully.

The planning memorandum remains incomplete.

Correct Application

Every placeholder shall be replaced before export.

If any placeholder cannot be populated, BUILD shall terminate with an error.

Applicable Methodology
BUILD Methodology
Validation Standards
Error 14
Introducing Unsupported Information
Incorrect

The planning memo states:

Endpoint monitoring is performed continuously.

The planning documentation contains no such statement.

Why This Is Incorrect

The methodology permits organization and consolidation of documented facts.

It does not permit creation of new planning information.

Correct Application

Use only documented planning information.

Applicable Methodology
Planning Philosophy
Information Classification Framework
Error 15
Reordering Historical Findings
Incorrect

Finding 3

Finding 1

Finding 2

Why This Is Incorrect

Historical findings shall preserve documented order.

Document order represents the issued audit report.

Correct Application

Preserve the documented sequence.

Applicable Methodology
Prior Audit Information
Open and Expected Issues
Error 16
Duplicate Information Across Sections
Incorrect

The complete description of Microsoft Defender appears in:

Overview
Current Events
Systems
Relevant Risks
Why This Is Incorrect

Each section has a distinct planning objective.

Unnecessary repetition increases inconsistency risk.

Correct Application

Overview

General understanding.

Current Events

Documented change.

Systems

Technology description.

Relevant Risks

Technology-related planning risk.

Applicable Methodology
Information Placement
Cross-Section Consistency
Summary

The most common preparation errors generally arise from one of five root causes:

Reproducing source documentation rather than preparing planning narratives.
Failing to distinguish current-state information from historical information.
Misclassifying planning information.
Introducing unsupported information.
Creating inconsistencies across planning sections.

Application of the methodology described throughout this document should prevent these errors and produce a complete, internally consistent A2 Audit Planning Memo suitable for Internal Audit planning and review.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

APPENDIX C
Decision Trees
Purpose

This appendix provides decision trees illustrating application of the A2 Audit Planning Methodology.

The decision trees supplement the methodology by providing a structured approach for evaluating planning information, determining information placement, and preparing the A2 Audit Planning Memo.

The decision trees do not replace the methodology.

Where a conflict exists, the methodology shall govern.

Decision Tree 1
Planning Information Hierarchy
Planning Information

↓

Multiple documented sources?

↓

No

↓

Use documented information.

↓

Yes

↓

Current-Year Questionnaire?

↓

Yes

↓

Use as baseline.

↓

No

↓

Planning Meeting Notes?

↓

Yes

↓

Clearly newer?

↓

Yes

↓

Replace baseline.

↓

No

↓

Supplement baseline.

↓

No

↓

Historical Planning Documentation?

↓

Yes

↓

Current-state still valid?

↓

Yes

↓

Retain.

↓

No

↓

Exclude.

↓

No

↓

Prior Audit Report

↓

Use only where specifically required by the methodology.
Decision Tree 2
Information Classification
Documented Statement

↓

Does it describe the
current operating environment?

↓

Yes

↓

Current-State Planning Information

↓

No

↓

Historical planning context?

↓

Yes

↓

Historical Context

↓

No

↓

Prior audit report?

↓

Yes

↓

Prior Audit Information

↓

No

↓

Planning administration?

↓

Yes

↓

Exclude

↓

No

↓

Auditor working note?

↓

Yes

↓

Exclude

↓

No

↓

Question?

↓

Yes

↓

Exclude

↓

No

↓

Uncertain statement?

↓

Yes

↓

Exclude unless supported elsewhere.
Decision Tree 3
Current-State Determination
Documented Information

↓

Multiple versions exist?

↓

No

↓

Retain.

↓

Yes

↓

Newer documented current state?

↓

Yes

↓

Replace older version.

↓

No

↓

Supplement?

↓

Yes

↓

Combine documented facts.

↓

No

↓

Historical context required?

↓

Yes

↓

Retain.

↓

No

↓

Exclude.
Decision Tree 4
Overview
Documented Statement

↓

Does it explain
the audited function?

↓

No

↓

Exclude.

↓

Yes

↓

Current-state information?

↓

No

↓

Historical context required?

↓

No

↓

Exclude.

↓

Yes

↓

Include.

↓

Yes

↓

Include in Overview.
Decision Tree 5
Current Events
Documented Statement

↓

Does it describe
a documented change?

↓

No

↓

Exclude.

↓

Yes

↓

Planning relevant?

↓

No

↓

Exclude.

↓

Yes

↓

Current operating environment?

↓

No

↓

Exclude.

↓

Yes

↓

Include in Current Events.
Decision Tree 6
Systems / Applications / Models / Vendors
Technology

↓

Currently supports
the audited function?

↓

No

↓

Exclude.

↓

Yes

↓

Replaced?

↓

Yes

↓

Include replacement.

↓

No

↓

Production technology?

↓

No

↓

Exclude.

↓

Yes

↓

Include.
Decision Tree 7
Related Departments and Activities
Department

↓

Supports the audited function?

↓

No

↓

Exclude.

↓

Yes

↓

Permanent relationship?

↓

No

↓

Temporary project?

↓

Exclude.

↓

Yes

↓

Include.

↓

Documented activity?

↓

Yes

↓

Populate Activity.

↓

No

↓

Leave Activity blank.
Decision Tree 8
Relevant Risks
Documented Statement

↓

Does it describe
a planning risk?

↓

No

↓

Exclude.

↓

Yes

↓

Current risk?

↓

No

↓

Historical context required?

↓

No

↓

Exclude.

↓

Yes

↓

Include.

↓

Current?

↓

Yes

↓

Include in Relevant Risks.
Decision Tree 9
Prior Audit Information
Prior Audit Information

↓

Documented?

↓

No

↓

Exclude.

↓

Yes

↓

Historical audit record?

↓

Yes

↓

Extract exactly.

↓

Findings?

↓

Preserve wording.

↓

Finding Numbers?

↓

Preserve alignment.

↓

Advisory Items?

↓

No finding numbers.

↓

Regulatory Comments?

↓

Preserve exactly.
Decision Tree 10
Open and Expected Issues
Historical Finding

↓

Documented
in Prior Audit?

↓

No

↓

Exclude.

↓

Yes

↓

Current status documented?

↓

No

↓

Present historical finding.

↓

Yes

↓

Present:

Historical finding

+

Documented status.
Decision Tree 11
BUILD
Structured Planning Dataset

↓

Complete?

↓

No

↓

Stop.

↓

Yes

↓

Load approved template.

↓

Populate placeholders.

↓

Populate tables.

↓

Placeholder remaining?

↓

Yes

↓

Stop.

↓

No

↓

Validate.
Decision Tree 12
Validation
Completed Planning Memo

↓

All required sections populated?

↓

No

↓

Fail.

↓

Yes

↓

Formatting preserved?

↓

No

↓

Fail.

↓

Yes

↓

Cross-section consistency?

↓

No

↓

Fail.

↓

Yes

↓

No placeholders?

↓

No

↓

Fail.

↓

Yes

↓

Validation Passed.
Decision Tree 13
Cross-Section Consistency
Completed Planning Memo

↓

Current-state descriptions
consistent?

↓

No

↓

Revise.

↓

Yes

↓

Historical information
consistent?

↓

No

↓

Revise.

↓

Yes

↓

Planning information
appears in correct section?

↓

No

↓

Revise.

↓

Yes

↓

Document internally consistent.
Summary

The decision trees contained within this appendix summarize the principal decision points described throughout this methodology.

They are intended to support consistent application of:

Planning Information Hierarchy;
Information Classification Framework;
Current-State Determination;
Section Methodologies;
JSON Data Model;
BUILD Methodology;
Validation Standards; and
Cross-Section Consistency.

The decision trees illustrate methodology application but do not replace the detailed requirements established within the body of this document.
</pre>
