# SECTION 16
JSON Data Model
### 16.1 Purpose

The JSON Data Model defines the standardized structured representation of information extracted during the planning process.

Its purpose is to establish a consistent interface between the information extraction methodology and the document build methodology.

The JSON dataset represents the completed planning information after application of this methodology.

It does not represent the source documents themselves.

Accordingly, the JSON dataset shall contain only the information required to populate the A2 Audit Planning Memo.

### 16.2 Planning Objective

The JSON Data Model should satisfy the following objectives.

Represent every required A2 Planning Memo section.
Preserve documented planning information.
Maintain consistency between extraction and document generation.
Eliminate ambiguity regarding data placement.
Support automated validation.
Support repeatable template population.

The JSON dataset is not intended to archive planning documentation.

### 16.3 Relationship to Other Sections

The JSON dataset shall be produced only after all planning methodology described within Sections 1 through 15 has been completed.

Narrative values contained within the dataset shall already be memo-ready before BUILD begins.

Accordingly:

source hierarchy shall already have been applied;
information classification shall already have occurred;
current-state determination shall already have been completed;
section methodology shall already have been applied.

The JSON dataset represents the completed planning result rather than an intermediate working document.

### 16.4 Dataset Structure

The dataset shall consist of one structured object representing one A2 Planning Memo.

Each field shall correspond to one planning element defined within this methodology.

No field shall exist unless it supports a required planning output.

The JSON structure shall remain consistent across all engagements.

### 16.5 Field Definitions

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

### 16.6 Structured Issue Alignment

FINDINGS_REPORTED, FINDING_NUMBERS, and ADVISORY_ITEMS shall remain internally aligned.

For each finding:

FINDINGS_REPORTED[n].finding_number

shall equal:

FINDING_NUMBERS[n]

The order of findings and advisory items shall not change between EXTRACT, JSON serialization, Open and Expected Issues preparation, and BUILD.

### 16.7 Data Integrity

Every JSON field shall satisfy the following requirements.

The field shall:

represent documented planning information;
correspond to one methodology section;
preserve documented meaning;
remain internally consistent;
support template population.

The JSON dataset shall not introduce additional interpretation beyond that already permitted by this methodology.

### 16.8 Required and Optional Fields

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

### 16.9 Empty and Missing Values

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

### 16.10 Ordering Requirements

Ordering shall remain deterministic.

Accordingly:

findings shall preserve documented order;
advisory items shall preserve documented order;
contacts shall preserve documented order;
related departments shall preserve documented order.

Ordering shall not be changed during BUILD.

### 16.11 Serialization Standards

The JSON dataset shall be represented using valid JSON syntax.

Field names shall exactly match the names defined within this methodology.

The dataset shall contain one top-level object.

Duplicate field names shall not exist.

Additional undocumented fields shall not be introduced.

### 16.12 BUILD Relationship

The JSON dataset represents the sole input to the BUILD Methodology.

BUILD shall not consult:

questionnaires;
planning meeting notes;
historical planning documentation;
prior audit reports.

All planning decisions shall already have been completed before BUILD begins.

BUILD shall therefore perform document population rather than planning analysis.

### 16.13 Quality Review

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

### 16.14 Methodology Note
The JSON Data Model represents the completed planning dataset produced through application of this methodology.
It is not an independent planning document and does not replace the A2 Audit Planning Memo.
Its sole purpose is to provide a complete, consistent, and structured representation of planning information for automated document generation.


---


# SECTION 17
BUILD Methodology
### 17.1 Purpose

The BUILD Methodology defines the standardized process for generating the completed A2 Audit Planning Memo from the structured planning dataset.

Its purpose is to ensure that every planning memo is produced consistently, accurately, and without modification of the planning information established during EXTRACT.

BUILD performs document generation.

BUILD shall not perform planning analysis, source-document review, information extraction, interpretation, or creation of new planning content.

### 17.2 BUILD Objective

The BUILD process shall:

populate every designated section of the approved A2 Audit Planning Memo template;
preserve the approved document structure and page layout;
populate narrative fields and tables from the structured planning dataset;
preserve dataset wording and ordering;
apply standardized formatting;
validate the completed document before export.

BUILD shall not modify planning decisions established during EXTRACT.

### 17.3 Required Inputs

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

### 17.4 BUILD Sequence

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

### 17.5 Template Preservation

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

### 17.6 Narrative Tag Mapping

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

### 17.7 Key Contacts Table

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

### 17.8 Related Departments and Activities Table

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

### 17.9 Protected Sections

BUILD shall not modify the following sections:

Audit Scope;
Review & Approval.

Instructional text, formatting, tables, and blank fields within those sections shall remain unchanged.

These protected sections are excluded from placeholder-removal requirements unless they contain a designated <<GPT_FILL:...>> replacement tag.

BUILD shall not populate, delete, rewrite, or reformat protected content.

### 17.10 Formatting Standards

All inserted content, including content inserted into tables, shall use:

Times New Roman;
11-point font;
black text;
non-italic formatting.

Bold or italic formatting shall be applied only when explicitly required by the methodology or by the existing template structure.

Existing section headings, table headings, borders, shading, alignment, and spacing shall remain unchanged.

Inserted paragraphs shall inherit the paragraph alignment and spacing of the replacement location.

Inserted table content shall inherit the alignment and cell formatting of the model data row.

### 17.11 Multiline Content

Line breaks contained within dataset narrative fields shall be preserved.

Where the dataset contains multiple paragraphs, BUILD shall create separate Word paragraphs rather than insert visible escape characters.

Where the dataset contains ordered or bulleted structures, BUILD shall preserve their documented order and line separation.

BUILD shall not replace multiline content with a single condensed paragraph unless the dataset itself contains a single paragraph.

### 17.12 Open Issues Formatting

When populating OPEN_AND_EXPECTED_ISSUES_REGULATORY_COMMENTS, BUILD shall convert the field’s documented line breaks into separate Word paragraphs.

The following exact heading lines shall be bold:

Findings Reported
Advisory Items
Regulatory Comments

For each advisory item, the documented advisory-item title appearing before the first en dash shall be bold.

The remaining advisory-item narrative shall remain non-bold.

Finding descriptions and status narratives shall remain non-bold unless the dataset explicitly requires otherwise.

BUILD shall not change wording, ordering, punctuation, or paragraph content while applying this formatting.

### 17.13 Placeholder Removal

Every designated <<GPT_FILL:...>> tag shall be replaced.

No designated replacement tag may remain in:

paragraphs;
table cells;
headers;
footers;
text boxes;
other document content.

If any designated replacement tag remains after population, validation shall fail and the document shall not be exported.

### 17.14 Empty Values

Narrative values shall be inserted exactly as represented within the dataset.

Blank scalar values shall remain blank.

Empty arrays shall produce no populated table rows beyond the required table structure.

Blank table fields shall produce blank cells.

The phrase:

Not specified in the provided source documents.

shall not be inserted into table cells.

### 17.15 File Generation

The completed document shall be exported as:

[AUDIT_NAME] - A2 Audit Planning Memo.docx

Characters not permitted within a filename shall be removed.

Leading and trailing spaces shall be removed.

Internal spacing within the documented Audit Name shall otherwise be preserved.

### 17.16 BUILD Error Conditions

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

### 17.17 Quality Review

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

### 17.18 Methodology Note

BUILD is limited to document population and formatting.

All planning decisions, source evaluation, classification, current-state determination, and narrative preparation occur during EXTRACT.

BUILD shall preserve the structured planning dataset exactly and shall not introduce new planning content.


---

