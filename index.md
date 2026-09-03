```text
Table of Contents

1. Purpose
2. Planning Philosophy
3. Planning Information Hierarchy
4. Information Classification Framework
5. A2 Planning Framework

6. Audit Name
7. Overview
8. Current Events
9. Key Contacts
10. Regulatory Requirements
11. Systems / Applications / Models / Vendors
12. Related Departments and Activities
13. Relevant Risks
14. Prior Audit Information
15. Open and Expected Issues / Regulatory Comments

16. JSON Data Model
17. BUILD Methodology
18. Validation Standards
19. Cross-Section Consistency

Appendix A – End-to-End Planning Workflow Example

Appendix B – Common Errors

Appendix C – Decision Trees

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Preface

This methodology establishes the standard process for preparing the A2 Audit Planning Memo used by Stifel Internal Audit.

It is intended to promote consistency in planning documentation by defining:

planning objectives;
source hierarchy;
information classification;
current-state determination;
section methodology;
structured planning outputs;
document validation.

This methodology should be applied consistently across all auditable areas unless an approved engagement-specific exception exists.

Where multiple planning documents are available, this methodology governs how documented information shall be evaluated, classified, consolidated, and presented.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 1
Purpose

1. Purpose

1.1 Objective

The purpose of this methodology is to establish a standardized process for preparing the A2 Audit Planning Memo for Stifel Internal Audit.

The methodology defines how planning information shall be identified, evaluated, classified, structured, and documented before audit fieldwork begins.

Its objectives are to ensure that every A2 Planning Memo:

accurately reflects the current operating environment;
uses only documented information;
consistently applies Internal Audit planning standards;
presents planning information in a concise, current-state format;
eliminates unnecessary duplication;
clearly distinguishes historical planning context from current operating conditions;
provides sufficient information to support audit scoping and risk assessment.
1.2 Scope

This methodology applies to every A2 Planning Memo prepared by Stifel Internal Audit.

Primary source documents include:

completed Audit Planning Questionnaires;
A2.1 Planning Meeting Notes;
prior audit planning documentation where specifically referenced;
other planning documentation explicitly designated by Internal Audit.

This methodology does not establish audit conclusions, testing procedures, audit opinions, or control assessments.

Its purpose is limited to planning documentation.

1.3 Intended Outcome

The completed A2 Planning Memo should communicate the current operating environment of the auditable function rather than reproduce planning documentation.

The completed memo should represent a structured planning document written for Internal Audit.

It should not resemble:

a questionnaire,
meeting minutes,
planning notes,
interview transcripts,
auditor working papers,
document request lists,
or control walkthrough documentation.

Every section of the memo should contain only information that directly supports audit planning.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 2
Planning Philosophy

2. Planning Philosophy

The A2 Planning Memo is a planning document rather than a source-document archive.

The objective is not to reproduce planning documentation.

The objective is to identify the documented facts that materially describe the auditable function at the beginning of the audit.

Planning information shall therefore be evaluated according to the following principles.

Principle 1

Current documented information takes precedence over historical documented information.

Historical information should only be retained when it continues to describe the current operating environment or provides necessary context.

Principle 2

Planning documentation contains multiple types of information.

Not every documented statement belongs in an A2 Planning Memo.

Each documented statement shall first be classified according to its purpose before determining whether it belongs within the planning memo.

Principle 3

The planning memo communicates the current operating environment rather than the history of planning activities.

Information describing audit administration, meeting logistics, document collection, testing procedures, evidence requests, scheduling, or auditor actions shall not appear unless it directly affects audit planning.

Principle 4

No information may be introduced that is unsupported by the planning documentation.

The methodology permits organization, consolidation, and clarification of documented facts.

It does not permit unsupported inference or creation of new information.

Principle 5

When multiple documented statements describe the same subject, only the documented current state should appear unless historical context is specifically required.

Obsolete documented information should not be repeated alongside its documented replacement.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 3
Planning Information Hierarchy
3. Planning Information Hierarchy

The A2 Planning Memo shall be based solely upon documented planning information.

Because multiple planning documents often describe the same process from different points in time, planning information shall be evaluated according to a consistent hierarchy before determining what information appears within the A2 Planning Memo.

The purpose of the hierarchy is to ensure that the completed planning memo reflects the current operating environment while preserving accurate historical context where appropriate.

When multiple documented sources describe the same subject, the highest-priority applicable source shall govern unless this methodology specifies otherwise.

3.1 Source Hierarchy

Planning information shall be evaluated using the following order of precedence.

Level 1 – Current-Year Questionnaire Responses

The completed Audit Planning Questionnaire represents management's formal current-year planning responses and serves as the primary source for the A2 Planning Memo.

Current-year questionnaire responses establish the baseline understanding of the auditable function.

Unless superseded by newer documented information, questionnaire responses shall be considered authoritative.

Level 2 – A2.1 Planning Meeting Notes

Planning meeting notes provide clarification, updates, implementation progress, and additional context obtained after the questionnaire was completed.

Planning meeting notes may:

update questionnaire information;
clarify questionnaire responses;
document completed implementations;
identify newly implemented technologies;
identify retired technologies;
document organizational changes;
identify new planning considerations.

Planning meeting notes shall not automatically replace questionnaire responses.

Replacement occurs only when the notes clearly document a newer current state.

Level 3 – Prior Audit Planning Context

Prior audit planning documentation provides historical context regarding the auditable function.

Historical planning information should be used only when it continues to accurately describe the current operating environment or provides necessary background that is not otherwise documented.

Historical planning information shall never override documented current-year information.

Level 4 – Prior Audit Reports

Prior audit reports provide historical findings, advisory items, audit opinions, and previously identified risks.

Prior audit reports shall only be used where specifically required by the A2 Planning Memo, including:

Open and Expected Issues;
Prior Audit Information;
audit opinion;
report number;
report date.

Prior audit reports should not be used to describe the current operating environment unless explicitly confirmed by current planning documentation.

3.2 Current-State Determination

The objective of the A2 Planning Memo is to describe the documented current operating environment.

When multiple documented statements describe the same subject, the planning memo shall present the documented current state.

Current-state determination shall follow the following rules.

Rule 1

If a newer documented statement explicitly replaces an older documented statement, only the newer statement shall appear within the planning memo.

The obsolete statement shall be omitted.

Rule 2

If newer documentation supplements an older documented statement without replacing it, both documented facts shall be combined into a single current-state description.

Duplicate information shall not be repeated.

Rule 3

If multiple documented statements describe different aspects of the same subject, the planning memo shall consolidate those documented facts into one coherent description.

Rule 4

Historical information shall only remain when it materially improves understanding of the current operating environment.

Historical planning information should not appear solely because it was documented previously.

3.3 Baseline Retention

Responses such as:

No change
None
N/A
See above

do not remove previously documented planning information.

Instead, these responses indicate that the documented baseline remains applicable.

When a questionnaire response indicates "No change," the planning memo shall retain the previously documented baseline for that section unless newer documented information explicitly replaces it.

3.4 Missing Information

The phrase

"Not specified in the provided source documents."

shall be used only when every applicable source identified by this methodology has been reviewed and no supported information exists for the required field.

The missing-information phrase shall never replace documented baseline information.

Likewise, the absence of a current-year update shall not be interpreted as the absence of planning information.

The phrase shall be used only for unsupported narrative fields and shall not be used within structured table fields, arrays, or scalar metadata fields.

3.5 Conflict Resolution

Occasionally planning documents may appear to conflict.

When documented conflicts exist, they shall be resolved using the following order:

Current-year questionnaire response
Clearly newer documented A2.1 update
Historical planning documentation
Prior audit documentation

If two documented sources cannot be reconciled through the source hierarchy, the planning memo shall retain only information that can be directly supported by the highest-priority source.

Unsupported reconciliation or interpretation shall not be performed.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 4
Information Classification Framework
4. Information Classification Framework

Every documented statement encountered during audit planning shall be classified before it is considered for inclusion in the A2 Audit Planning Memo.

The purpose of classification is to distinguish planning-relevant information from planning documentation.

The methodology does not evaluate documents based on where information appears. Instead, it evaluates each documented statement according to its purpose.

Only information classified as relevant to the A2 Planning Memo shall be included.

Information that cannot be classified into an approved planning category shall be excluded.

4.1 Classification Process

Each documented statement shall be evaluated using the following sequence.

Step 1 – Identify the Statement

Identify one complete factual statement from the planning documentation.

A statement may consist of:

a sentence;
a bullet point;
a table entry;
a documented response;
a documented list item.

Do not combine unrelated statements before classification.

Step 2 – Determine the Statement Type

Each statement shall be assigned to exactly one of the following categories.

Category A — Current-State Planning Information

Definition

Information describing the auditable function as it currently operates.

Examples include:

current responsibilities;
implemented technologies;
current governance;
current regulatory requirements;
active vendors;
current organizational structure;
current operating processes;
current risks.

This category is eligible for inclusion within the A2 Planning Memo.

Category B — Historical Context

Definition

Information describing previous operating conditions or historical planning information.

Historical context should only be retained when it materially improves understanding of the current operating environment.

Historical information should not appear simply because it was documented.

Category C — Prior Audit Information

Definition

Information relating to previous audit reports.

Examples include:

report number;
report date;
audit opinion;
findings;
advisory items;
regulatory comments.

This category shall only appear within the Open and Expected Issues section or other fields specifically requiring prior audit information.

Category D — Planning Administration

Definition

Information describing the planning process rather than the auditable function.

Examples include:

meeting agendas;
scheduling information;
document request lists;
fieldwork dates;
report issuance dates;
participant logistics;
meeting locations;
meeting identifiers.

Planning administration shall not appear within the A2 Planning Memo.

Category E — Auditor Working Notes

Definition

Information intended to assist audit execution rather than describe the auditable function.

Examples include:

request screenshots;
obtain evidence;
reach out to;
follow up with;
test;
verify;
review;
walkthrough instructions;
audit reminders.

Auditor working notes shall not appear within the A2 Planning Memo.

Category F — Questions

Definition

Information presented as a question rather than a documented fact.

Questions shall never appear within the A2 Planning Memo.

Only documented answers may be considered for inclusion.

Category G — Uncertain Information

Definition

Statements expressing uncertainty.

Examples include:

might;
maybe;
he thinks;
approximately (unless the approximation itself is the documented fact);
question marks indicating uncertainty.

Uncertain information shall not appear unless supported elsewhere as a documented current-state fact.

4.2 Current-State Information

Only Category A information shall normally populate the following sections:

Overview
Current Events
Regulatory Requirements
Systems / Applications / Vendors
Related Departments
Relevant Risks

These sections describe the current operating environment rather than the planning process.

4.3 Historical Information

Historical information shall be retained only when one or more of the following conditions exist:

it explains the current operating environment;
it provides necessary planning context;
it is specifically required by another section of this methodology;
it documents prior audit issues required within Open and Expected Issues.

Otherwise, historical information shall be excluded.

4.4 Information Consolidation

Multiple documented statements frequently describe the same subject.

After classification, related statements shall be consolidated into one planning narrative.

Consolidation shall:

remove duplication;
eliminate repeated descriptions;
organize related facts logically;
preserve every material documented fact.

Consolidation shall not:

introduce unsupported information;
change documented meaning;
omit material planning information.

4.5 Memo-Ready Narrative Preparation

After information has been classified and assigned to the appropriate A2 section, related supported facts may be organized into memo-ready wording.

Memo-ready narrative preparation may:

combine related documented facts;
remove duplication;
improve sentence flow;
organize information logically;
convert questionnaire-style responses into planning narrative;
preserve supported bullet and multiline structures.

Memo-ready narrative preparation shall not:

introduce new facts;
create causal relationships not documented in the sources;
create risk implications not documented in the sources;
add descriptive details;
add conclusions;
change the documented meaning;
omit material supported information;
shorten required historical issue narratives.

Every statement contained within a memo-ready narrative shall remain traceable to documented source information.

4.6 Information Exclusion

A documented statement shall be excluded when it:

describes only the audit process;
represents an auditor action item;
represents a document request;
represents a testing procedure;
represents meeting administration;
represents scheduling information;
represents an unanswered question;
represents unsupported speculation;
duplicates another documented current-state fact;
has been superseded by a newer documented current-state fact.

Excluding a statement does not imply that the source document is incorrect.

It simply indicates that the statement does not belong within the A2 Planning Memo.

4.7 Final Planning Test

Before any information is placed into the A2 Planning Memo, it shall satisfy all of the following questions.

Is this a documented fact?
Does it describe the auditable function rather than the audit process?
Does it represent the documented current state?
Does it belong within one of the defined A2 sections?
Is it free of duplicated information?
Is it supported by the highest-priority applicable source?

If any answer is No, the information shall either be reclassified or excluded from the A2 Planning Memo.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 5
A2 Planning Framework

5.1 Purpose

Each section of the A2 Audit Planning Memo serves a specific planning objective.

Sections shall not be treated as repositories for source-document content.

Instead, each section shall communicate a distinct aspect of the current operating environment necessary to support audit planning.

Each section shall therefore define:

its planning objective;
its primary information sources;
its information hierarchy;
the information eligible for inclusion;
the information that shall be excluded;
the required presentation format.

Information shall only appear within the section that best represents its planning purpose.

Information should not be repeated across multiple sections unless specifically required by this methodology.

5.2 Section Relationships

Although each section is prepared independently, the completed planning memo shall function as one integrated planning document.

Information should therefore flow logically between sections.

For example:

The Overview establishes an understanding of the auditable function.

The Current Events section explains what has changed since that understanding was established.

The Systems / Applications / Models / Vendors section identifies the technology supporting the function.

The Regulatory Requirements section identifies the current governing requirements applicable to the function.

The Related Departments and Activities section identifies organizational relationships and dependencies.

The Relevant Risks section identifies the current planning risks affecting the function.

The Prior Audit Information section documents historical audit results.

The Open and Expected Issues / Regulatory Comments section explains the historical issues that remain relevant to planning.

Each section should complement the others without unnecessarily repeating information.

5.3 Planning Flow

The A2 Planning Memo should communicate Internal Audit's planning process in the following logical order.

1. Understand the function.
2. Understand what has changed.
3. Understand the governing environment.
4. Understand the supporting technology.
5. Understand organizational relationships.
6. Understand current planning risks.
7. Review prior audit results.
8. Determine which historical issues remain relevant to the current audit.

Each section builds upon the information established within the preceding sections.

Historical audit information should not influence the understanding of the current operating environment until the current environment has first been established.

5.4 Section Independence

Each section shall be evaluated according to its own planning objective.

The presence of information within one section does not automatically justify its inclusion within another.

For example:

A system implementation discussed within Current Events should not automatically appear within Systems unless it represents a current production technology supporting the function.

Similarly, a regulatory development discussed within Current Events should not automatically appear within Regulatory Requirements unless it represents an active governing requirement.

Each section shall therefore independently determine whether documented information supports its planning objective.

5.5 Information Placement

Every documented fact included within the planning memo shall have one primary location.

When multiple sections could reasonably contain the same information, the following hierarchy shall apply.

Overview

General understanding of the function.

Current Events

Changes affecting the function.

Regulatory Requirements

Current governing requirements.

Systems / Applications / Vendors

Technology supporting the function.

Related Departments

Internal organizational relationships.

Relevant Risks

Current planning risks affecting the function.

Prior Audit Information

Historical audit results.

Open and Expected Issues

Historical issues requiring planning consideration.

Information should normally appear only once.

Exceptions should occur only when necessary to preserve planning context.

5.6 Section Consistency

All sections of the planning memo shall describe the same documented current operating environment.

Accordingly:

Current systems identified within Systems should be consistent with technologies referenced within Overview and Current Events.

Risks identified within Relevant Risks should be supported by information contained within the preceding planning sections.

Historical audit issues discussed within Open and Expected Issues should remain consistent with the extracted prior audit information.

Conflicting descriptions of the current operating environment shall not appear within different sections of the same planning memo.

Relevant Risks should be supported by information contained within the Overview, Current Events, Systems, Regulatory Requirements, and Related Departments sections.

Prior Audit Information shall remain internally consistent with Open and Expected Issues.

5.7 Narrative Standards

Narrative sections should communicate planning information rather than reproduce source documents.

Narrative content shall therefore:

read as Internal Audit planning documentation;
describe the documented current operating environment;
present information logically;
eliminate unnecessary repetition;
preserve documented meaning.

Narrative content shall not:

resemble interview notes;
resemble questionnaires;
resemble meeting minutes;
resemble planning agendas;
resemble auditor working papers;
resemble document request lists.

The objective is to produce planning documentation that can be reviewed independently of the source documents.

5.8 Section Completeness

A section shall be considered complete only when:

its planning objective has been satisfied;
every material documented fact assigned to that section has been incorporated;
obsolete information has been removed;
unsupported information has not been introduced;
duplicated information has been eliminated;
the section remains internally consistent.

Completeness shall not be measured by document length.

A concise section containing all material planning information is preferable to a longer section containing repetition or administrative detail.

5.9 Methodology Application

The A2 Planning Memo shall be prepared by applying the methodology described within this document rather than by reproducing source documentation.

Every section should therefore be developed independently according to its planning objective while remaining consistent with the overall planning narrative.

The completed planning memo should represent Internal Audit's understanding of the current operating environment rather than a compilation of planning documents.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 6
Audit Name Methodology
6.1 Purpose

The Audit Name identifies the current Internal Audit engagement.

The Audit Name establishes the identity of the planning memo and shall remain consistent throughout every section of the completed A2 Audit Planning Memo.

Because planning documentation frequently contains historical audit names, auditable area names, prior report titles, filenames, and planning references, the Audit Name shall be determined using a consistent source hierarchy.

6.2 Primary Source

The primary source for the Audit Name shall be the title or header appearing at the beginning of the completed Audit Planning Questionnaire.

This title represents the current engagement approved for planning.

Unless explicitly superseded by current engagement documentation, the questionnaire title shall govern.

6.3 Secondary Source

If the completed questionnaire does not clearly identify the current engagement title, the Audit field contained within the A2.1 Planning Meeting Notes may be used.

The A2.1 title may also be used to expand the questionnaire title when the planning meeting clearly documents that the current engagement includes additional audit areas not reflected within the questionnaire title.

6.4 Sources That Shall Not Be Used

The following shall not determine the Audit Name unless explicitly identified as the current engagement title.

Section 1 auditable area names
Section 2 Auditable Area fields
Prior audit report titles
Historical planning documentation
File names
Folder names
Previous audit names
Control identifiers
Historical planning references

These sources frequently describe prior engagements or component audit areas rather than the current audit engagement.

6.5 Combined Engagements

Occasionally a current audit engagement may include multiple previously independent audit areas.

When planning documentation clearly identifies a combined engagement, the Audit Name shall represent the combined engagement rather than the individual component audit areas.

The completed planning memo shall consistently use the combined engagement title throughout all sections.

6.6 Consistency Requirements

The Audit Name shall remain identical wherever referenced within the planning memo.

This includes:

document title;
Open and Expected Issues;
generated filename;
JSON dataset;
template replacement fields;
any other generated references.

The Audit Name shall never vary between sections of the same planning memo.

6.7 Quality Review

Before finalizing the planning memo, confirm:

the Audit Name represents the current engagement;
historical audit names have not replaced the current engagement title;
combined engagements have been identified correctly;
every reference within the planning memo uses the same Audit Name.

If any inconsistency exists, the Audit Name shall be corrected before the planning memo is finalized.

6.8 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 7
Overview Methodology
7.1 Purpose

The Overview establishes Internal Audit's understanding of the auditable function.

It should enable a reader unfamiliar with the process to understand:

what the function is;
why it exists;
who owns it;
what responsibilities it performs;
who or what it supports;
the significant technologies or information it utilizes;
the governance structure supporting the function.

The Overview is intended to describe the function itself rather than the audit.

7.2 Primary Sources

The primary source for the Overview shall be the current-year functional description provided within Question 1a of the completed Audit Planning Questionnaire.

Questionnaire Section 3.1 may supplement the Overview only when it provides enduring background information that remains applicable and is not already described within Question 1a.

A2.1 Planning Meeting Notes may supplement the Overview only when they document current operating information that materially changes management's description of the function.

7.3 Planning Objective

The Overview should answer the following planning questions.

What function is being audited?
What business purpose does it serve?
Who owns or manages the function?
What are the primary responsibilities?
What business areas, users, or clients are supported?
What significant information or technology supports the function?
What governance structure oversees the function?

If a documented statement does not contribute to answering one of these questions, it should generally not appear within the Overview.

7.4 Information Eligible for Inclusion

Information may be included when it describes:

the purpose of the function;
management ownership;
organizational responsibility;
primary operational activities;
services provided;
users or business functions supported;
types of information managed;
stable governance structures;
enduring technology relationships necessary to understand the function.

Information should describe the current operating environment rather than historical planning context.

7.5 Information Excluded

The Overview shall not include:

audit objectives;
audit scope;
audit period;
fieldwork dates;
report issuance dates;
meeting logistics;
planning agendas;
interview summaries;
document requests;
evidence requests;
testing procedures;
control walkthrough notes;
implementation status updates;
current-year project status;
staffing changes;
emerging threats;
historical findings;
risk descriptions that belong within the Relevant Risks section.

These topics belong within other sections of the planning memo.

7.6 Current-State Determination

The Overview shall describe the current operating environment.

Historical descriptions should only remain when they continue to accurately describe the function or provide essential planning context.

When multiple documented descriptions address the same topic:

prefer the documented current state;
retain enduring background only when it improves understanding;
remove duplicated descriptions;
eliminate obsolete information.

The Overview shall not describe the evolution of the function over time.

7.7 Narrative Standards

The Overview should read as a concise Internal Audit planning narrative.

It should not resemble:

questionnaire responses;
interview transcripts;
planning meeting notes;
copied planning documentation.

Related documented facts should be consolidated into coherent paragraphs while preserving documented meaning.

Narrative should flow logically from:

function purpose;
organizational ownership;
primary responsibilities;
supported business activities;
governance and supporting technologies.

Bulleted lists should only be used when they improve readability, such as documenting major responsibilities or supported services.

7.8 Quality Review

Before finalizing the Overview, confirm:

the section explains the function rather than the audit;
current-year information has been incorporated;
obsolete descriptions have been removed;
duplicated information has been consolidated;
audit administration has not been included;
meeting notes have not been copied verbatim;
planning objectives, timelines, and logistics are absent;
the narrative provides sufficient understanding for audit planning without requiring reference to the source documents.

If any condition is not satisfied, the Overview shall be revised before the planning memo is finalized.

7.9 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 8
Current Events Methodology
8.1 Purpose

The Current Events section identifies documented changes, developments, and emerging conditions that may influence audit planning.

Unlike the Overview, which describes the function as it currently operates, the Current Events section explains what has changed, what is changing, or what may affect the audit during the current planning cycle.

Current Events should help Internal Audit understand how the operating environment differs from the previous audit.

8.2 Primary Sources

The Current Events section shall primarily use:

Questionnaire Question 1b;
Questionnaire Question 1c;
Questionnaire Questions 9–11 where planning-relevant;
Questionnaire Section 3.4;
documented factual outcomes contained within the A2.1 Planning Meeting Notes.

Questionnaire responses establish the planning baseline.

Clearly newer A2.1 information may replace or supplement the questionnaire when it documents the current operating environment.

8.3 Planning Objective

The Current Events section should answer the following planning questions.

What has changed since the previous audit?
What major implementations have occurred?
What systems have been replaced, retired, or introduced?
What organizational or governance changes affect the function?
What significant external developments affect the audit?
What emerging technologies or threats require planning consideration?
What material operational changes should influence audit scoping?

Information that does not contribute to answering one of these questions should generally not appear within this section.

8.4 Information Eligible for Inclusion

The following information is generally appropriate for inclusion.

Technology Changes

Examples include:

implementation of new systems;
retirement of existing systems;
migration to replacement platforms;
significant version upgrades;
implementation progress;
major architecture changes.
Operational Changes

Examples include:

organizational restructuring;
significant staffing changes affecting operations;
new operating models;
changes in governance responsibilities;
new third-party service providers.
External Developments

Examples include:

significant regulatory developments;
significant cybersecurity developments;
emerging threat trends;
industry events affecting the function;
material incidents impacting planning.
Planning-Relevant Initiatives

Examples include:

implementation projects;
proof-of-concept initiatives;
new AI capabilities;
automation initiatives;
strategic technology initiatives.

Only documented current initiatives should be included.

8.5 Information Excluded

The Current Events section shall not include:

audit objectives;
audit scope;
audit timelines;
meeting agendas;
meeting logistics;
document requests;
evidence requests;
screenshot requests;
testing procedures;
auditor reminders;
walkthrough notes;
control-by-control implementation notes;
interview questions;
scheduling information;
staff vacation or availability;
uncertain statements not supported elsewhere.

Examples of excluded content include:

"Request updated screenshots."
"Reach out to..."
"Control 10.3..."
"Joe said..."
"Matt is out next week."

These statements support audit execution rather than audit planning.

8.6 Current-State Determination

Current Events shall describe the documented current planning environment.

When multiple documented statements describe the same subject:

retain the newest documented current state;
remove superseded descriptions;
consolidate related documented facts;
avoid chronological narration unless timing materially affects planning.

The objective is to communicate the current planning environment rather than document the history of planning discussions.

8.7 Narrative Standards

Current Events should read as a planning update prepared by Internal Audit.

Narrative should:

organize changes by topic;
present only planning-relevant developments;
eliminate duplication;
consolidate related updates;
preserve documented meaning.

Narrative should not resemble:

meeting minutes;
planning agendas;
interview transcripts;
auditor working papers;
questionnaire responses reproduced verbatim.

Where multiple developments affect the same topic, they should be combined into one coherent planning narrative.

8.8 Relationship to Other Sections

Information should appear in Current Events only when it represents a documented change or emerging condition.

For example:

A new production system should appear in both:

Current Events, because it represents a change; and
Systems / Applications / Vendors, because it supports the function.

However:

Routine descriptions of existing systems belong only within Systems.

Current threats belong within Relevant Risks unless the threat itself represents a new planning development.

Current Events should complement the Overview rather than repeat it.

8.9 Quality Review

Before finalizing the Current Events section, confirm:

every item represents a documented change, development, or emerging condition;
obsolete information has been removed;
superseded information has not been duplicated;
meeting logistics have been excluded;
document requests have been excluded;
evidence requests have been excluded;
testing procedures have been excluded;
raw A2.1 notes have not been copied verbatim;
current-state information has been consolidated into planning narratives;
the section provides meaningful planning context without reproducing source documentation.

If any condition is not satisfied, the Current Events section shall be revised before the planning memo is finalized.

8.10 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 9
Key Contacts Methodology
9.1 Purpose

The Key Contacts section identifies the individuals responsible for, or materially involved in, the auditable function.

The purpose of this section is to establish the primary management contacts supporting audit planning, fieldwork, issue discussion, and audit communication.

The Key Contacts section is not intended to document meeting attendance or planning participants.

Only individuals who have a meaningful relationship to the auditable function should be included.

9.2 Primary Sources

The Key Contacts section shall primarily use:

Section 2 – Engagement Quick Reference;
Questionnaire Question 3.

A2.1 Planning Meeting Notes may supplement the contact list only when they clearly identify additional process owners or functional managers who materially support the auditable function.

9.3 Planning Objective

The Key Contacts section should answer the following planning questions.

Who owns the auditable function?
Who manages the function?
Who has primary operational responsibility?
Who should Internal Audit communicate with during the engagement?

Individuals who do not materially support these objectives should generally not appear.

9.4 Information Eligible for Inclusion

The following individuals are generally appropriate for inclusion.

process owners;
functional managers;
department managers;
system owners;
business owners;
operational contacts;
management contacts specifically identified within the planning documentation.

Roles should only be included when explicitly documented.

If no documented role exists, only the individual's name should be retained.

9.5 Information Excluded

The following should generally be excluded.

meeting attendees who do not support the function;
Internal Audit staff;
note takers;
meeting facilitators;
scheduling contacts;
document request contacts;
temporary participants;
individuals referenced only as examples;
"myself" when the individual cannot be identified from the planning documentation.

Attendance alone does not justify inclusion.

9.6 Duplicate Resolution

Planning documentation frequently references the same individual multiple times.

Duplicate contacts shall be consolidated into one record.

When multiple documented roles exist for the same individual:

retain the most descriptive documented role;
do not combine unsupported titles;
preserve documented spelling.
9.7 Output Requirements

Each contact shall be represented as one logical record.

Required fields:

Name
Role (when explicitly documented)

Names shall appear exactly as documented.

Roles shall not be inferred.

9.8 JSON Representation

The Key Contacts section shall be represented as:

[
  {
    "name": "Exact Name",
    "role": "Documented Role or Blank"
  }
]

The JSON array shall contain one object per contact.

Blank role values shall remain blank.

9.9 BUILD Requirements

During template population:

each JSON object shall populate one table row;
Name shall populate the Name column;
Role shall populate the Role column;
additional rows shall be created when required;
blank template rows shall be removed after population;
unsupported roles shall remain blank.

The order of contacts should follow the order established within the extracted dataset.

9.10 Quality Review

Before finalizing the Key Contacts section, confirm:

every contact materially supports the auditable function;
duplicate contacts have been removed;
names match the documented spelling;
undocumented roles have not been inferred;
Internal Audit personnel have not been included unless they are also documented process owners;
the number of JSON records equals the number of populated table rows.

If any condition is not satisfied, the Key Contacts section shall be revised before the planning memo is finalized.

9.11 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 10
Regulatory Requirements Methodology
10.1 Purpose

The Regulatory Requirements section identifies the current external laws, regulations, examination guidance, industry standards, and internal policy requirements governing the auditable function.

The purpose of this section is to establish the regulatory environment applicable to audit planning.

This section identifies what governs the function, not how the function complies with those requirements.

10.2 Primary Sources

The Regulatory Requirements section shall primarily use:

Questionnaire Question 4;
documented baseline regulatory requirements contained within the questionnaire;
clearly documented current-year regulatory updates.

Planning Meeting Notes may supplement this section only when they document a material regulatory change affecting the current audit period.

10.3 Planning Objective

The Regulatory Requirements section should answer the following planning questions.

What laws govern this function?
What regulatory guidance applies?
What internal policy requirements govern the function?
Have applicable regulatory requirements changed since the previous audit?

Information that does not contribute to answering these questions should generally not appear.

10.4 Information Eligible for Inclusion

Information may be included when it identifies:

federal regulations;
state regulations;
examination guidance;
industry standards;
internal policy requirements;
documented regulatory changes;
current compliance frameworks.

Each requirement should appear only once.

Where available, the documented description of the requirement should accompany its name.

10.5 Baseline Retention

Questionnaire responses frequently state:

No change
None
N/A

These responses shall not remove previously documented regulatory requirements.

Instead:

"No change" confirms that the documented baseline requirements remain applicable.
Previously documented requirements shall therefore be retained.

The response itself should not appear within the completed planning memo.

10.6 Information Excluded

The Regulatory Requirements section shall not include:

questionnaire questions;
"No change";
"No";
"N/A";
duplicated requirements;
regulatory inquiries;
Matters Requiring Attention (MRAs);
examination findings;
enforcement actions;
auditor commentary;
unsupported interpretation.

Regulatory inquiries belong within Regulatory Comments when applicable.

10.7 Current-State Determination

When planning documentation identifies:

newly applicable regulations;
retired regulations;
superseded guidance;
revised policy requirements;

the section shall describe the documented current regulatory environment.

Obsolete regulatory references shall be removed unless historical context is specifically required.

10.8 Narrative Standards

Each regulatory requirement should be presented using the following structure.

[Requirement]

[Documented description]

When multiple requirements exist, each shall appear once.

Narrative should remain concise while preserving the documented meaning.

Do not consolidate multiple unrelated regulatory requirements into a single paragraph.

10.9 Relationship to Other Sections

The Regulatory Requirements section identifies governing requirements.

It should not discuss:

implementation;
operational controls;
findings;
risks;
examination results;
regulatory comments.

Those topics belong elsewhere within the planning memo.

10.10 Quality Review

Before finalizing the Regulatory Requirements section, confirm:

every requirement currently governs the auditable function;
baseline requirements have been retained when the response indicates "No change";
duplicated requirements have been removed;
question text has been excluded;
"No change" has not been copied into the memo;
regulatory inquiries have not replaced regulatory requirements;
unsupported regulatory interpretation has not been introduced.

If any condition is not satisfied, the Regulatory Requirements section shall be revised before the planning memo is finalized.

10.11 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 11
Systems / Applications / Models / Vendors Methodology
11.1 Purpose

The Systems / Applications / Models / Vendors section identifies the technology, applications, security platforms, analytical models, and third-party providers that currently support the auditable function.

The purpose of this section is to establish the technology environment relevant to audit planning.

This section identifies what currently supports the function, not how Internal Audit will test those technologies.

11.2 Primary Sources

The Systems / Applications / Models / Vendors section shall primarily use:

Questionnaire Question 5;
documented baseline system inventory contained within the questionnaire;
clearly documented current-year system changes;
factual implementation updates documented within A2.1 Planning Meeting Notes.

Planning Meeting Notes may update the system inventory only when they clearly document:

implementation;
retirement;
replacement;
ownership changes;
provider changes;
production use.
11.3 Planning Objective

This section should answer the following planning questions.

What technology currently supports the auditable function?
Which third-party providers support the function?
Which systems have been implemented, retired, or replaced?
What documented role does each technology perform?

Information that does not contribute to answering one of these questions should generally not appear.

11.4 Technology Classification

Each documented technology shall first be classified before inclusion.

Systems

Enterprise applications currently supporting the function.

Examples:

CrowdStrike Falcon
Microsoft Defender
Splunk
Zscaler
Applications

Business or technical applications supporting the process.

Models

Documented analytical models supporting the process.

Only include models explicitly documented as supporting the function.

Vendors

Third-party organizations providing technology or operational support.

Examples:

Expel
Deepwatch
Vali Cyber
11.5 Information Eligible for Inclusion

A technology may be included only when documentation establishes:

the technology currently supports the auditable function;
the technology is implemented or actively used;
its purpose is documented;
its relationship to the function is documented.

Each entry should describe:

Name
Category
Current documented purpose
Current documented status (when applicable)
11.6 Current-State Determination

When planning documentation identifies a technology as:

replaced;
retired;
removed;
decommissioned;
no longer supporting the function;

that technology shall not appear within the completed planning memo unless historical context is specifically required.

Instead:

The documented replacement technology shall appear.

For example:

If documentation states:

Cisco Secure Endpoint has been removed and replaced by Microsoft Defender,

the completed planning memo should describe Microsoft Defender as the current platform.

Cisco Secure Endpoint should only be referenced when necessary to explain the documented replacement.

11.7 Provider Relationships

Third-party providers should only be included when they materially support the auditable function.

Provider entries should describe:

the provider;
the documented service performed;
the current documented relationship.

Examples include:

Managed Detection and Response providers.

Managed security providers.

Cloud providers directly supporting the function.

Providers should not be listed solely because they attended planning meetings.

11.8 Information Excluded

The following information shall not appear within this section.

audit procedures;
testing instructions;
screenshot requests;
evidence requests;
walkthrough steps;
user access review procedures;
Service Organization Control report collection procedures;
document request lists;
audit reminders;
interview dialogue;
uncertain statements;
implementation tasks;
planning logistics.

Likewise, the following shall not be represented as systems unless they directly support the auditable function.

ticket numbers;
task identifiers;
audit workpapers;
audit software used only during planning;
planning examples.
11.9 Narrative Standards

Each entry should follow the same format.

[System / Vendor Name]

Current documented purpose.

Current documented status.

Entries should remain concise.

Descriptions should explain why the technology is relevant to audit planning rather than reproduce planning documentation.

Where multiple documented statements describe the same technology, those statements should be consolidated into one description.

11.10 Relationship to Other Sections

Technology descriptions belong within this section.

Technology changes belong within Current Events.

Technology risks belong within Relevant Risks.

Technology governance belongs within Overview when necessary for understanding the function.

Technology should not be fully described multiple times throughout the planning memo.

11.11 Quality Review

Before finalizing the Systems / Applications / Models / Vendors section, confirm:

every listed technology currently supports the auditable function;
retired technologies have been removed unless historical context requires them;
replacements have been documented correctly;
duplicate technologies have been consolidated;
providers materially support the function;
every entry describes a documented purpose;
audit procedures have been excluded;
evidence requests have been excluded;
planning notes have been excluded;
interview dialogue has been excluded;
uncertain statements have been excluded;
current documented relationships are accurately represented.

If any condition is not satisfied, the Systems / Applications / Models / Vendors section shall be revised before the planning memo is finalized.

11.12 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 12
Related Departments and Activities Methodology
12.1 Purpose

The Related Departments and Activities section identifies the internal organizational relationships, dependencies, and supporting functions that materially influence the auditable function.

The purpose of this section is to help Internal Audit understand how the auditable function interacts with the broader organization and where operational, governance, or control dependencies exist.

This section describes organizational relationships, not organizational structure.

12.2 Primary Sources

The Related Departments and Activities section shall primarily use:

Questionnaire Question 6;
documented baseline organizational relationships contained within the questionnaire.

Planning Meeting Notes may supplement this section only when they clearly document:

newly established relationships;
removed organizational dependencies;
governance changes;
organizational restructuring;
changes in operational responsibilities.

12.3 Planning Objective

The Related Departments and Activities section should answer the following planning questions.

Which departments support the auditable function?
Which functions provide governance or oversight?
Which organizational relationships are necessary for the function to operate?
Which organizational dependencies may affect audit planning?

Information that does not contribute to answering one of these questions should generally not appear.

12.4 Relationship Types

Relationships generally fall into one or more of the following categories.

Operational Support

Departments that provide operational services supporting the function.

Examples include:

Information Technology
Infrastructure
Security Operations
Governance

Departments responsible for oversight.

Examples include:

Information Security
Enterprise Risk Management
Compliance
Legal
Shared Services

Functions that provide shared operational capabilities.

Examples include:

Data Governance
Identity Management
Vulnerability Management
Dependent Business Functions

Functions whose activities materially interact with the audited process.

12.5 Information Eligible for Inclusion

Each relationship should identify:

Department or Function
Documented activity
Nature of the relationship

Activities should describe why the department is relevant to the audited function.

Each department should appear only once.

12.6 Baseline Retention

When Question 6 indicates:

No change

the previously documented organizational relationships remain applicable.

The response itself should not appear within the planning memo.

Instead, the documented baseline relationships shall be retained.

12.7 Information Excluded

The Related Departments and Activities section shall not include:

meeting attendees;
project teams;
temporary working groups;
audit participants;
document request contacts;
evidence providers;
planning logistics;
organizational charts;
reporting lines unrelated to the audited function;
duplicated departments.

Departments should not appear merely because they participated in planning discussions.

12.8 Narrative Standards

Each relationship should follow the same structure.

Department / Function

Documented activity supporting the auditable function.

Activities should explain the documented relationship rather than describe the department generally.

Descriptions should remain concise while preserving documented meaning.

12.9 Relationship to Other Sections

This section identifies who the function depends upon.

It should not describe:

technology;
regulatory requirements;
current events;
risks;
findings.

Those subjects belong within their respective sections.

Where a department owns a technology or manages a regulatory process, the department should appear here while the technology or regulation appears in its appropriate section.

12.10 BUILD Representation

Each relationship shall populate one row within the Related Departments table.

The JSON representation shall contain:

Department / Function
Activity
Scope
Reason

Scope and Reason shall remain blank unless explicitly documented.

Each JSON object shall populate one table row.

12.11 Quality Review

Before finalizing the Related Departments and Activities section, confirm:

every department materially supports the audited function;
duplicate departments have been consolidated;
documented activities accurately describe the relationship;
baseline relationships have been retained when "No change" is stated;
meeting attendees have not been substituted for organizational relationships;
temporary project participants have been excluded;
every JSON relationship appears exactly once within the populated table;
unsupported organizational relationships have not been inferred.

If any condition is not satisfied, the Related Departments and Activities section shall be revised before the planning memo is finalized.

12.12 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 13
Relevant Risks Methodology
13.1 Purpose

The Relevant Risks section identifies the significant documented risks that may influence audit planning.

The purpose of this section is to establish Internal Audit's understanding of the current risk environment affecting the auditable function.

The section should identify why the function is being audited, rather than how the audit will be performed.

Relevant Risks should describe risks to the function, not risks to the audit engagement.

13.2 Primary Sources

The Relevant Risks section shall primarily use:

Questionnaire Question 8;
Questionnaire Questions 10 and 11 where planning-relevant;
documented baseline risks contained within prior planning documentation;
clearly documented current-year risk updates.

Planning Meeting Notes may supplement the risk inventory only when they document:

new risks;
emerging threats;
changes in existing risks;
newly identified technology risks;
new governance concerns;
current operational risks affecting the audit period.
13.3 Planning Objective

The Relevant Risks section should answer the following planning questions.

What significant risks affect the auditable function?
What current threats require audit attention?
What documented operational risks should influence audit planning?
What technology, governance, regulatory, or operational risks remain relevant?

Information that does not contribute to answering one of these questions should generally not appear.

13.4 Risk Categories

Documented risks generally fall into one or more of the following categories.

Operational Risk

Risks affecting the execution of business operations.

Technology Risk

Risks relating to technology, infrastructure, platforms, applications, or cybersecurity.

Information Security Risk

Risks affecting confidentiality, integrity, or availability of information.

Regulatory Risk

Risks arising from laws, regulations, examinations, or compliance obligations.

Governance Risk

Risks associated with oversight, accountability, policy, or management responsibility.

Third-Party Risk

Risks arising from external vendors or service providers.

Strategic Risk

Risks arising from significant initiatives, organizational change, or future operating direction.

13.5 Information Eligible for Inclusion

Each risk should identify:

documented risk title;
documented risk description;
current documented planning relevance.

Where multiple documented statements describe the same risk, they should be consolidated into one coherent planning description.

Baseline risks shall remain when the questionnaire response indicates "No change."

Clearly documented current-year risks shall supplement or replace baseline risks where appropriate.

13.6 Information Excluded

The Relevant Risks section shall not include:

audit procedures;
control testing;
audit findings;
document requests;
evidence requests;
meeting notes;
planning logistics;
staffing availability;
interview questions;
implementation tasks;
operational descriptions that do not describe a risk.

Likewise, the following responses shall not appear within the completed planning memo.

No
No change
N/A
See above

These responses determine baseline retention but are not planning risks.

13.7 Current-State Determination

The Relevant Risks section shall describe the documented current risk environment.

When planning documentation identifies:

emerging threats;
new technology risks;
evolving regulatory concerns;
changing operational risks;

those documented risks shall be incorporated into the current planning environment.

Resolved or obsolete risks shall be removed unless they remain relevant to planning.

13.8 Narrative Standards

Each risk should follow the same structure.

[Risk Title]

Documented risk description.

Risk descriptions should explain the planning significance of the risk rather than reproduce questionnaire responses verbatim.

Related documented risk statements should be consolidated where appropriate.

13.9 Relationship to Other Sections

Relevant Risks identifies what could materially affect the auditable function.

It should not duplicate:

Current Events;
Systems;
Findings;
Open Issues.

However, documented current events may explain why a risk has changed.

Likewise, current technologies may support the explanation of a technology risk.

The section should therefore reference documented planning context without repeating it unnecessarily.

13.10 BUILD Representation

Relevant Risks shall populate the Relevant Risks narrative section of the A2 Planning Memo.

The JSON representation shall preserve the final memo-ready wording.

Formatting may include:

paragraphs;
bullet lists;
grouped risk categories;

provided the documented meaning remains unchanged.

13.11 Quality Review

Before finalizing the Relevant Risks section, confirm:

every listed risk materially affects the auditable function;
baseline risks have been retained when appropriate;
current-year risks have been incorporated;
obsolete risks have been removed;
duplicate risks have been consolidated;
operational facts have not been presented as risks;
audit procedures have been excluded;
meeting notes have not been copied verbatim;
unsupported risks have not been inferred.

If any condition is not satisfied, the Relevant Risks section shall be revised before the planning memo is finalized.

13.12 Common Classification Errors

The following examples illustrate common mistakes.

Incorrect

Microsoft Defender replaced Cisco Secure Endpoint.

This is a Current Event, not a risk.

Incorrect

Request screenshots from Splunk.

This is an auditor action item, not a risk.

Incorrect

Quarterly user access reviews are performed.

This describes an operational control, not a risk.

Correct

Endpoint Security Risk – Enterprise assets require effective anti-malware controls, centralized management, and continuous monitoring to reduce the likelihood and impact of malware compromise.

The statement describes why the function is at risk, which is the purpose of this section.

Relevant Risks represents Internal Audit's assessment of the current planning environment.

Historical audit findings should not be introduced into this section unless the documented finding remains an active current planning risk.

13.13 Methodology Note
The purpose of this section is to define the planning objective rather than prescribe wording.
Narrative may be organized differently provided the completed section:
satisfies the planning objective;
uses only documented information;
remains internally consistent with the remainder of the A2 Planning Memo;
follows the principles established within this methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 14
Prior Audit Information
14.1 Purpose

The Prior Audit Information section establishes the documented results of the most recent Internal Audit engagement relevant to the current audit.

Its purpose is to preserve historical audit information required for planning while clearly separating historical audit results from the current operating environment.

This section documents what occurred during the previous audit.

It does not determine whether those historical issues remain relevant to the current audit.

That determination occurs within the Open and Expected Issues / Regulatory Comments section.

14.2 Planning Objective

The Prior Audit Information section should answer the following planning questions.

What was the most recent audit?
When was it issued?
What audit opinion was assigned?
What findings were reported?
What advisory items were identified?
Were any regulatory comments issued?

Information that does not contribute to answering one of these questions should generally not appear within this section.

14.3 Primary Sources

The Prior Audit Information section shall primarily use:

Questionnaire Section 2;
Questionnaire Section 3.2;
Questionnaire Question 7.

Historical planning documentation may supplement these sources only when explicitly referenced by the questionnaire.

Planning Meeting Notes shall not replace documented prior audit information unless they explicitly document corrected historical information.

14.4 Information Eligible for Inclusion

The Prior Audit Information section shall include only documented prior audit information.

Eligible information includes:

report number;
report date;
audit opinion;
reported findings;
finding numbers;
advisory items;
regulatory comments.

Each item shall be extracted exactly as documented.

14.5 Report Number

The report number uniquely identifies the prior audit report.

The report number shall be extracted exactly as documented.

The report number shall not be reformatted, abbreviated, or inferred.

Only one report number shall be associated with each planning memo unless multiple reports are explicitly required.

14.6 Report Date

The report date shall represent the issuance date of the most recent applicable audit report.

Dates shall be preserved exactly as documented.

Approximate dates shall not be inferred.

14.7 Audit Opinion

The audit opinion shall be extracted exactly as documented.

Audit opinions shall not be summarized.

Audit opinions shall not be interpreted.

If the documented opinion includes additional qualifying language, that language shall remain unchanged.

Where the methodology requires the audit opinion independently from the audit risk rating, only the documented audit opinion shall populate the Audit Opinion field.

14.8 Findings

Findings shall be extracted exactly as documented.

Each documented finding shall preserve:

documented order;
documented wording;
documented numbering;
documented status;
documented completion dates when applicable.

Findings shall not be summarized.

Findings shall not be consolidated.

Findings shall not be rewritten.

If no findings were reported, the documented no-findings statement shall be retained.

14.9 Finding Numbers

Finding numbers shall remain aligned one-to-one with the corresponding findings.

Finding numbers shall not be created when none exist.

Finding numbers shall not be inferred.

Blank finding numbers shall remain blank.

14.10 Advisory Items

Advisory items shall be extracted exactly as documented.

Each advisory item shall preserve:

documented title;
documented risk level;
documented description;
documented status;
documented completion information.

Advisory items shall never receive finding numbers.

If no advisory items exist, the documented no-advisory-items statement shall be retained.

14.11 Regulatory Comments

Regulatory comments shall represent documented comments issued by regulatory bodies relating to the previous audit.

If no documented regulatory comments exist, the following statement shall be used.

There were no regulatory comments issued for this audit.

Regulatory comments shall not be inferred.

Regulatory inquiries shall not be interpreted as regulatory comments.

14.12 Historical Integrity

Prior Audit Information represents historical audit documentation.

Historical audit information shall therefore remain historically accurate.

Historical audit information shall not be updated to reflect current operating conditions.

Historical audit information shall not be rewritten to reflect remediation completed after report issuance.

Current remediation status belongs within the Open and Expected Issues section when documented.

14.13 Relationship to Other Sections

Prior Audit Information provides historical planning information supporting:

Open and Expected Issues;
audit planning;
issue follow-up;
historical comparison.

Historical audit information should not be repeated throughout the planning memo unless specifically required by another section.

The Prior Audit Information section establishes the historical record.

The Open and Expected Issues section explains the current planning significance of that historical record.

14.14 BUILD Representation

The following fields shall populate the JSON dataset exactly as documented.

REPORT_NUMBER
REPORT_DATE
AUDIT_OPINION
FINDINGS_REPORTED
FINDING_NUMBERS
ADVISORY_ITEMS
REGULATORY_COMMENTS

No transformation of these fields shall occur during BUILD except formatting required by the A2 template.

14.15 Quality Review

Before finalizing the Prior Audit Information section, confirm:

the most recent applicable audit has been identified;
report number matches the documented report;
report date matches the documented report;
audit opinion has been extracted exactly;
findings remain complete and in documented order;
finding numbers remain aligned with findings;
advisory items remain complete;
advisory items have not been assigned finding numbers;
regulatory comments remain historically accurate;
historical information has not been rewritten to reflect current operating conditions.

If any condition is not satisfied, the Prior Audit Information section shall be revised before the planning memo is finalized.

14.16 Methodology Note
The Prior Audit Information section establishes the documented historical record.
It intentionally avoids interpreting historical information.
Interpretation occurs only after the historical record has been established.
Accordingly, this section should remain entirely factual.
Planning analysis of historical audit information belongs exclusively within the Open and Expected Issues / Regulatory Comments methodology.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 15
Open and Expected Issues / Regulatory Comments Methodology
15.1 Purpose

The Open and Expected Issues / Regulatory Comments section presents prior audit findings, advisory items, documented status information, and regulatory comments relevant to current audit planning.

This section combines the historical audit record established in Section 14 with documented current status information.

Historical issue wording shall remain unchanged.

Documented current status information may supplement, but shall not replace, the historical record.

15.2 Primary Sources

This section shall use:

the Prior Audit Information established in Section 14;
documented status information contained within the completed questionnaire;
clearly documented status information contained within A2.1 Planning Meeting Notes.

A2.1 Planning Meeting Notes may supplement this section only when they explicitly refer to a previously documented finding, advisory item, or regulatory comment.

Planning Meeting Notes shall not create new findings or advisory items.

15.3 Planning Objective

This section should answer:

What was the most recent applicable audit report?
What audit opinion was issued?
What findings were reported?
What advisory items were identified?
What documented status applies to those issues?
Were regulatory comments issued?
15.4 Required Order

The completed section shall appear in the following order:

Introductory paragraph
Findings Reported
Advisory Items
Regulatory Comments

The order shall not be changed.

The headings shall not be omitted.

15.5 Required Introductory Paragraph

The introductory paragraph shall use the following exact wording:

The most recent [AUDIT_NAME] Audit Report ([REPORT_NUMBER]) was issued on [REPORT_DATE], with an audit opinion of “[AUDIT_OPINION].” The final report noted [NUMBER AND RISK LEVEL OF FINDINGS], and the previous year’s Findings Summary listed [NUMBER AND RISK LEVEL OF ADVISORY ITEMS]; see below for additional details regarding the issues identified:

Only the bracketed values may change.

The sentence structure and remaining wording shall not be rewritten.

15.6 Findings Count and Risk Wording

The finding count shall be based only on explicitly documented findings.

Individual finding risk ratings shall be used.

When all findings have the same documented risk rating, use:

one [Risk Rating] finding

or:

[number] [Risk Rating] findings

Examples:

one Moderate finding
three High findings

When findings have different documented risk ratings, group them by risk level in descending order.

Use the following descending order when applicable:

Critical
High
Moderate
Low

Example:

one High finding and two Moderate findings

When no findings were reported, use:

no findings

A risk rating shall not be inferred.

When one or more findings exist but a risk rating is not documented for every finding, use:

one or more findings
15.7 Advisory Item Count and Risk Wording

The advisory-item count shall include only explicitly documented advisory items.

When all advisory items have the same documented risk rating, use:

one [Risk Rating] advisory item

or:

[number] [Risk Rating] advisory items

When advisory items have different documented risk ratings, group them by risk level in descending order.

Use the following descending order when applicable:

Critical
High
Moderate
Low

When no advisory items were identified, use:

no advisory items

When one or more advisory items exist but the count or risk rating cannot be fully supported, use:

one or more advisory items

Advisory items shall not receive finding numbers.

15.8 Findings Reported

The heading shall be:

Findings Reported

Every documented finding shall be included.

Each finding shall preserve:

finding number;
risk rating;
full documented description;
documented status;
documented status date;
documented expected completion date.

Findings shall remain in documented order.

Findings shall not be summarized, shortened, rewritten, combined, or reordered.

The standard format shall be:

[FINDING_NUMBER] – [Full documented description].

When documented status information exists, append:

As of [STATUS_DATE], this finding remains [STATUS], with an expected completion date of [EXPECTED_COMPLETION_DATE].

Only documented portions of the status sentence shall be included.

If no status date is documented, the phrase As of [STATUS_DATE] shall not be created.

If no expected completion date is documented, that clause shall be omitted.

If no findings were reported, use:

No findings were reported.
15.9 Advisory Items

The heading shall be:

Advisory Items

Each advisory item shall preserve:

title;
risk rating;
full documented description;
documented status;
documented status date;
documented expected completion date.

The advisory-item title shall be bold in the completed memo.

The standard format shall be:

[Advisory Item Title] – [Full documented description].

When documented status information exists, append:

As of [STATUS_DATE], this item remains [STATUS], with an expected completion date of [EXPECTED_COMPLETION_DATE].

Only documented portions of the status sentence shall be included.

If no advisory items were identified, use:

No advisory items were identified.
15.10 Regulatory Comments

The heading shall be:

Regulatory Comments

When regulatory comments exist, present one concise paragraph using only documented regulatory-comment content.

Regulatory comments shall not be inferred or supplemented.

Regulatory inquiries shall not automatically be treated as regulatory comments.

When no regulatory comments were issued, use:

There were no regulatory comments issued for this audit.
15.11 Information Excluded

This section shall not include:

newly created findings;
newly created advisory items;
unsupported risk ratings;
unsupported status dates;
unsupported completion dates;
testing procedures;
evidence requests;
auditor recommendations;
planning logistics;
meeting dialogue;
unsupported conclusions.
15.12 Historical Integrity

Historical finding and advisory-item wording shall remain unchanged.

Current status information shall supplement the historical record.

Current status information shall not rewrite the original issue.

A closed or remediated issue shall not be deleted solely because it is closed when the methodology requires the complete prior audit record to be presented.

15.13 BUILD Representation

The completed section shall be represented by:

OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS

The field shall contain the complete memo-ready section, including:

introductory paragraph;
Findings Reported heading and content;
Advisory Items heading and content;
Regulatory Comments heading and content.

BUILD shall insert the completed field without further interpretation.

15.14 Quality Review

Confirm:

the exact introductory wording was used;
every bracketed value is supported;
count grammar is correct;
risk groupings are supported;
findings remain complete and ordered;
finding numbers remain aligned;
advisory items remain complete and ordered;
advisory items do not contain finding numbers;
unsupported status information was not introduced;
the required section order was preserved;
the no-advisory-items statement was used when applicable;
the no-regulatory-comments statement was used when applicable.

If any condition is not satisfied, the section shall be revised before finalization.

15.15 Methodology Note

This section intentionally combines historical audit information with documented current status information.
Historical issue wording shall remain unchanged.
Current status information shall supplement, rather than replace, the historical record.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 16
JSON Data Model
16.1 Purpose

The JSON Data Model defines the standardized structured representation of information extracted during the planning process.

Its purpose is to establish a consistent interface between the information extraction methodology and the document build methodology.

The JSON dataset represents the completed planning information after application of this methodology.

It does not represent the source documents themselves.

Accordingly, the JSON dataset shall contain only the information required to populate the A2 Audit Planning Memo.

16.2 Planning Objective

The JSON Data Model should satisfy the following objectives.

Represent every required A2 Planning Memo section.
Preserve documented planning information.
Maintain consistency between extraction and document generation.
Eliminate ambiguity regarding data placement.
Support automated validation.
Support repeatable template population.

The JSON dataset is not intended to archive planning documentation.

16.3 Relationship to Other Sections

The JSON dataset shall be produced only after all planning methodology described within Sections 1 through 15 has been completed.

Narrative values contained within the dataset shall already be memo-ready before BUILD begins.

Accordingly:

source hierarchy shall already have been applied;
information classification shall already have occurred;
current-state determination shall already have been completed;
section methodology shall already have been applied.

The JSON dataset represents the completed planning result rather than an intermediate working document.

16.4 Dataset Structure

The dataset shall consist of one structured object representing one A2 Planning Memo.

Each field shall correspond to one planning element defined within this methodology.

No field shall exist unless it supports a required planning output.

The JSON structure shall remain consistent across all engagements.

16.5 Field Definitions

The dataset shall contain the following fields.

AUDIT_NAME

Type

String

Purpose

Identifies the current Internal Audit engagement.

Source

Audit Name Methodology.

OVERVIEW

Type

String

Purpose

Current-state overview narrative.

Source

Overview Methodology.

CURRENT_EVENTS

Type

String

Purpose

Current Events narrative.

Source

Current Events Methodology.

KEY_CONTACTS

Type

Array of objects

Purpose

Management contacts supporting the audit.

Each object shall use the following structure:

{
  "name": "",
  "role": ""
}

Field rules:

name shall preserve the documented contact name.
role shall preserve the documented role when explicitly provided.
Unsupported role values shall remain blank.
The field names name and role shall remain lowercase and shall not be changed.
Contacts shall remain in documented order.

REGULATORY_REQUIREMENTS

Type

String

Purpose

Current regulatory requirements narrative.

KEY_SYSTEMS_APPLICATIONS_MODELS_AND_VENDORS

Type

String

Purpose

Current technology environment.

RELATED_DEPARTMENTS_AND_ACTIVITIES

Type

Array of objects

Purpose

Represents documented departments, functions, activities, scope classifications, and reasons.

Each object shall use the following structure:

{
  "department": "",
  "activity": "",
  "scope": "",
  "reason": ""
}

Field rules:

department shall preserve the documented department or function name.
activity shall preserve the documented activity.
scope shall preserve the documented In or Out of Scope value when explicitly provided.
reason shall preserve the documented reason when explicitly provided.
Unsupported values shall remain blank.
The field names department, activity, scope, and reason shall remain lowercase and shall not be changed.
Relationships shall remain in documented order.

RELEVANT_RISKS

Type

String

Purpose

Current planning risks.

REPORT_NUMBER

Type

String

Purpose

Prior audit report identifier.

REPORT_DATE

Type

String

Purpose

Prior audit report issuance date.

AUDIT_OPINION

Type

String

Purpose

Prior audit opinion.

FINDINGS_REPORTED

Type

Array of objects

Purpose

Represents all documented prior audit findings in documented order.

Each object shall contain:

{
  "finding_number": "",
  "risk_rating": "",
  "description": "",
  "status": "",
  "status_date": "",
  "expected_completion_date": ""
}

Field rules:

finding_number shall preserve the documented finding number.
risk_rating shall preserve the documented individual finding rating.
description shall preserve the full documented finding description.
status shall preserve the documented current status.
status_date shall preserve the documented date associated with the current status.
expected_completion_date shall preserve the documented expected completion date.
Unsupported values shall remain blank.
Findings shall remain in documented order.
Findings shall not be summarized, combined, rewritten, or reordered.
FINDING_NUMBERS

Type

Array of strings

Purpose

Provides a compatibility array containing the finding numbers associated with FINDINGS_REPORTED.

Rules:

the number of FINDING_NUMBERS entries shall equal the number of FINDINGS_REPORTED objects;
each entry shall match the finding_number value in the corresponding finding object;
ordering shall remain one-to-one;
blank finding numbers shall remain blank;
finding numbers shall not be created or inferred.
ADVISORY_ITEMS

Type

Array of objects

Purpose

Represents all explicitly documented advisory items in documented order.

Each object shall contain:

{
  "title": "",
  "risk_rating": "",
  "description": "",
  "status": "",
  "status_date": "",
  "expected_completion_date": ""
}

Field rules:

title shall preserve the documented advisory-item title;
risk_rating shall preserve the documented advisory-item risk rating;
description shall preserve the full documented description;
status shall preserve the documented current status;
status_date shall preserve the documented date associated with the current status;
expected_completion_date shall preserve the documented expected completion date;
unsupported values shall remain blank;
advisory items shall remain in documented order;
advisory items shall not receive finding numbers;
advisory items shall not be summarized, combined, rewritten, or reordered.

REGULATORY_COMMENTS

Type

String

Purpose

Documented regulatory comments.

OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS

Type

String

Purpose

Completed Open and Expected Issues narrative.

16.6 Structured Issue Alignment

FINDINGS_REPORTED, FINDING_NUMBERS, and ADVISORY_ITEMS shall remain internally aligned.

For each finding:

FINDINGS_REPORTED[n].finding_number

shall equal:

FINDING_NUMBERS[n]

The order of findings and advisory items shall not change between EXTRACT, JSON serialization, Open and Expected Issues preparation, and BUILD.

16.7 Data Integrity

Every JSON field shall satisfy the following requirements.

The field shall:

represent documented planning information;
correspond to one methodology section;
preserve documented meaning;
remain internally consistent;
support template population.

The JSON dataset shall not introduce additional interpretation beyond that already permitted by this methodology.

16.8 Required and Optional Fields

The following fields shall always exist.

AUDIT_NAME
OVERVIEW
CURRENT_EVENTS
KEY_CONTACTS
REGULATORY_REQUIREMENTS
KEY_SYSTEMS_APPLICATIONS_MODELS_AND_VENDORS
RELATED_DEPARTMENTS_AND_ACTIVITIES
RELEVANT_RISKS
REPORT_NUMBER
REPORT_DATE
AUDIT_OPINION
FINDINGS_REPORTED
FINDING_NUMBERS
ADVISORY_ITEMS
REGULATORY_COMMENTS
OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS

Fields shall remain present even when their values are empty.

Field names shall remain unchanged.

16.9 Empty and Missing Values

Missing-value treatment shall depend on the field type.

Narrative fields:

When no supported narrative information exists after all applicable sources have been reviewed, use:

Not specified in the provided source documents.

Scalar metadata fields:

When no supported scalar metadata value exists, use an empty string:

""

Array fields:

When no supported array entries exist, use an empty array:

[]

Table object fields:

When a table record exists but an individual field is unsupported, the field shall remain an empty string.

The missing-information phrase shall not be inserted into:

Key Contacts table cells;
Related Departments and Activities table cells;
finding metadata fields;
advisory-item metadata fields;
report metadata fields.

The absence of a current-year update shall not replace documented baseline information with a missing value.

16.10 Ordering Requirements

Ordering shall remain deterministic.

Accordingly:

findings shall preserve documented order;
advisory items shall preserve documented order;
contacts shall preserve documented order;
related departments shall preserve documented order.

Ordering shall not be changed during BUILD.

16.11 Serialization Standards

The JSON dataset shall be represented using valid JSON syntax.

Field names shall exactly match the names defined within this methodology.

The dataset shall contain one top-level object.

Duplicate field names shall not exist.

Additional undocumented fields shall not be introduced.

16.12 BUILD Relationship

The JSON dataset represents the sole input to the BUILD Methodology.

BUILD shall not consult:

questionnaires;
planning meeting notes;
historical planning documentation;
prior audit reports.

All planning decisions shall already have been completed before BUILD begins.

BUILD shall therefore perform document population rather than planning analysis.

16.13 Quality Review

Before finalizing the JSON dataset, confirm:

every required field exists;
field names exactly match this methodology;
documented ordering has been preserved;
arrays remain properly aligned;
no undocumented fields have been introduced;
empty fields comply with this methodology;
no planning decisions remain unresolved;
the dataset is internally consistent;
the dataset fully supports generation of the A2 Audit Planning Memo without reference to the source documentation.

If any condition is not satisfied, the dataset shall be corrected before BUILD begins.

16.14 Methodology Note
The JSON Data Model represents the completed planning dataset produced through application of this methodology.
It is not an independent planning document and does not replace the A2 Audit Planning Memo.
Its sole purpose is to provide a complete, consistent, and structured representation of planning information for automated document generation.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 17
BUILD Methodology
17.1 Purpose

The BUILD Methodology defines the standardized process for generating the completed A2 Audit Planning Memo from the structured planning dataset.

Its purpose is to ensure that every planning memo is produced consistently, accurately, and without modification of the planning information established during EXTRACT.

BUILD performs document generation.

BUILD shall not perform planning analysis, source-document review, information extraction, interpretation, or creation of new planning content.

17.2 BUILD Objective

The BUILD process shall:

populate every designated section of the approved A2 Audit Planning Memo template;
preserve the approved document structure and page layout;
populate narrative fields and tables from the structured planning dataset;
preserve dataset wording and ordering;
apply standardized formatting;
validate the completed document before export.

BUILD shall not modify planning decisions established during EXTRACT.

17.3 Required Inputs

BUILD requires:

the approved A2 Audit Planning Memo template; and
A2_EXTRACT_DATASET.json.

No additional planning documents shall be reviewed during BUILD.

BUILD shall not consult:

the Audit Planning Questionnaire;
A2.1 Planning Meeting Notes;
prior planning documentation;
prior audit reports;
any other source document used during EXTRACT.

The structured planning dataset is the sole source of planning content during BUILD.

17.4 BUILD Sequence

BUILD shall perform the following sequence.

Load the approved A2 Audit Planning Memo template.
Load A2_EXTRACT_DATASET.json.
Validate that every required dataset field exists.
Locate every designated narrative tag and table.
Populate narrative tags using the applicable dataset fields.
Populate the Key Contacts table.
Populate the Related Departments and Activities table.
Apply required formatting to all inserted content.
Confirm protected sections remain unchanged.
Confirm that no designated replacement tag remains.
Validate the completed document.
Generate the approved filename.
Export the completed .docx file.

The completed document shall not be exported when any required step fails.

17.5 Template Preservation

BUILD shall modify the approved template in place.

BUILD shall not recreate the A2 Audit Planning Memo as a new document.

The following template elements shall be preserved:

page size;
margins;
headers and footers;
section headings;
page structure;
table borders;
table widths;
alignment;
paragraph spacing;
document branding;
page numbering;
Review & Approval structure.

Only designated replacement tags, designated table rows, and content specifically identified by this methodology may be modified.

17.6 Narrative Tag Mapping

The following mappings shall govern narrative tag replacement.

<<GPT_FILL:AUDIT_NAME>>
    → AUDIT_NAME

<<GPT_FILL:OVERVIEW>>
    → OVERVIEW

<<GPT_FILL:CURRENT_EVENTS>>
    → CURRENT_EVENTS

<<GPT_FILL:REGULATORY_REQUIREMENTS>>
    → REGULATORY_REQUIREMENTS

<<GPT_FILL:KEY_SYSTEMS_APPLICATIONS_MODELS_AND_VENDORS>>
    → KEY_SYSTEMS_APPLICATIONS_MODELS_AND_VENDORS

<<GPT_FILL:OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS>>
    → OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS

<<GPT_FILL:RELEVANT_RISKS>>
    → RELEVANT_RISKS

The AUDIT_NAME field shall populate the <<GPT_FILL:AUDIT_NAME>> tag located within the document header and shall also be used when generating the completed document filename.

Narrative replacement shall be literal.

BUILD shall not summarize, shorten, rewrite, reinterpret, reorder, or supplement dataset content.

17.6.1 Tag Detection and Replacement

Designated replacement tags may be divided across multiple Word runs, text elements, or content controls while appearing as one continuous tag within the visible document.

BUILD shall identify replacement tags based on the complete visible paragraph, table-cell, header, footer, or content-control text rather than requiring the tag to exist within a single run.

BUILD shall:

scan paragraphs, table cells, headers, footers, and content controls;
reconstruct contiguous visible text when a tag is divided across runs;
replace the complete tag while preserving the surrounding paragraph or cell structure;
remove all run fragments associated with the replaced tag;
apply the required inserted-content formatting after replacement.

A tag shall not be considered missing solely because it is divided across multiple runs or text elements.

Validation shall inspect the complete visible document text and confirm that no full or fragmented designated replacement tag remains.

17.7 Key Contacts Table

The table immediately following the KEY CONTACTS heading is the designated Key Contacts table.

The first row is the table header row and shall remain unchanged.

The first populated row beneath the header is the model data row.

The following mappings shall apply:

KEY_CONTACTS[].name
    → Name column

KEY_CONTACTS[].role
    → Role column

Each KEY_CONTACTS object shall populate one table row.

Additional rows shall be created by copying the formatting and structure of the model data row.

Unused blank rows shall be removed after population.

A role shall remain blank when the dataset contains a blank role value.

The order of table rows shall match the order of objects in KEY_CONTACTS.

No contact shall be added, removed, combined, or reordered during BUILD.

17.8 Related Departments and Activities Table

The table immediately following the RELATED DEPARTMENTS AND ACTIVITIES heading is the designated Related Departments and Activities table.

The first row is the table header row and shall remain unchanged.

The first populated row beneath the header is the model data row.

The following mappings shall apply:

RELATED_DEPARTMENTS_AND_ACTIVITIES[].department
    → Department / Function column

RELATED_DEPARTMENTS_AND_ACTIVITIES[].activity
    → Activity column

RELATED_DEPARTMENTS_AND_ACTIVITIES[].scope
    → In or Out of Scope column

RELATED_DEPARTMENTS_AND_ACTIVITIES[].reason
    → Reason column

Each object shall populate one table row.

Additional rows shall be created by copying the formatting and structure of the model data row.

Unused blank rows shall be removed after population.

Blank dataset values shall produce blank table cells.

The order of table rows shall match the order of objects in RELATED_DEPARTMENTS_AND_ACTIVITIES.

No relationship shall be added, removed, combined, or reordered during BUILD.

The template tags currently located within the model data row shall be treated as table-mapping markers and shall not remain after population.

The model-row tags identify the table columns only. They do not represent separate top-level dataset fields.

17.9 Protected Sections

BUILD shall not modify the following sections:

Audit Scope;
Review & Approval.

Instructional text, formatting, tables, and blank fields within those sections shall remain unchanged.

These protected sections are excluded from placeholder-removal requirements unless they contain a designated <<GPT_FILL:...>> replacement tag.

BUILD shall not populate, delete, rewrite, or reformat protected content.

17.10 Formatting Standards

All inserted content, including content inserted into tables, shall use:

Times New Roman;
11-point font;
black text;
non-italic formatting.

Bold or italic formatting shall be applied only when explicitly required by the methodology or by the existing template structure.

Existing section headings, table headings, borders, shading, alignment, and spacing shall remain unchanged.

Inserted paragraphs shall inherit the paragraph alignment and spacing of the replacement location.

Inserted table content shall inherit the alignment and cell formatting of the model data row.

17.11 Multiline Content

Line breaks contained within dataset narrative fields shall be preserved.

Where the dataset contains multiple paragraphs, BUILD shall create separate Word paragraphs rather than insert visible escape characters.

Where the dataset contains ordered or bulleted structures, BUILD shall preserve their documented order and line separation.

BUILD shall not replace multiline content with a single condensed paragraph unless the dataset itself contains a single paragraph.

17.12 Open Issues Formatting

When populating OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS, BUILD shall convert the field’s documented line breaks into separate Word paragraphs.

The following exact heading lines shall be bold:

Findings Reported
Advisory Items
Regulatory Comments

For each advisory item, the documented advisory-item title appearing before the first en dash shall be bold.

The remaining advisory-item narrative shall remain non-bold.

Finding descriptions and status narratives shall remain non-bold unless the dataset explicitly requires otherwise.

BUILD shall not change wording, ordering, punctuation, or paragraph content while applying this formatting.

17.13 Placeholder Removal

Every designated <<GPT_FILL:...>> tag shall be replaced.

No designated replacement tag may remain in:

paragraphs;
table cells;
headers;
footers;
text boxes;
other document content.

If any designated replacement tag remains after population, validation shall fail and the document shall not be exported.

17.14 Empty Values

Narrative values shall be inserted exactly as represented within the dataset.

Blank scalar values shall remain blank.

Empty arrays shall produce no populated table rows beyond the required table structure.

Blank table fields shall produce blank cells.

The phrase:

Not specified in the provided source documents.

shall not be inserted into table cells.

17.15 File Generation

The completed document shall be exported as:

[AUDIT_NAME] - A2 Audit Planning Memo.docx

Characters not permitted within a filename shall be removed.

Leading and trailing spaces shall be removed.

Internal spacing within the documented Audit Name shall otherwise be preserved.

17.16 BUILD Error Conditions

BUILD shall fail when any of the following conditions exists:

A2_EXTRACT_DATASET.json is missing;
a required dataset field is missing;
the approved template cannot be opened;
a designated narrative tag is missing;
a designated table cannot be located;
a designated replacement tag cannot be reconstructed or replaced across run boundaries or content controls;
a table cannot be populated in place;
a designated replacement tag remains;
protected sections are modified;
formatting requirements are not satisfied;
dataset content is omitted, shortened, or altered;
the completed document cannot be exported;
validation fails.

When BUILD fails:

no partial .docx file shall be exported;
no incomplete document shall be returned;
the response shall identify the failed validation requirement.

On successful BUILD, return only the completed .docx download link.

On failed BUILD, return only a concise validation error identifying each failed requirement.

Do not return a partial document.

Do not return a download link when validation fails.

17.17 Quality Review

Before export, confirm:

every required dataset field was available;
every designated narrative tag was replaced;
the Audit Name was populated in the header;
the Key Contacts table was populated correctly;
the Related Departments and Activities table was populated correctly;
table ordering matches dataset ordering;
no unsupported table content was inserted;
all inserted content uses Times New Roman 11-point black text;
no designated replacement tag remains;
Audit Scope remains unchanged;
Review & Approval remains unchanged;
dataset content was not omitted, shortened, rewritten, or reordered;
the filename follows the approved naming convention;
the completed document passes Section 18 Validation Standards.

If any condition is not satisfied, the document shall not be exported.

17.18 Methodology Note

BUILD is limited to document population and formatting.

All planning decisions, source evaluation, classification, current-state determination, and narrative preparation occur during EXTRACT.

BUILD shall preserve the structured planning dataset exactly and shall not introduce new planning content.

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

SECTION 18
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
the Review & Approval section remains unchanged;
no protected content has been removed, rewritten, or reformatted.

No designated replacement tag or designated population instruction shall remain within sections populated by BUILD.

Instructional content contained within the protected Audit Scope and Review & Approval sections shall remain unchanged and is excluded from this requirement.

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
<<GPT_FILL:OVERVIEW>>

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
```
