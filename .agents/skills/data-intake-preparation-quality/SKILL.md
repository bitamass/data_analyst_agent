---
name: data-intake-preparation-quality
description: Define analytical data requirements; inspect, profile, clean, transform, and validate data; and determine whether it is fit for the intended analysis. Use when beginning a data request, assessing data quality, preparing a dataset, or identifying data-access, lineage, privacy, or readiness gaps.
---

# Data Intake, Preparation, and Quality Assessment

## Purpose

Translate a business question into clear data requirements and prepare a reliable, documented dataset for analysis.

This skill preserves the original Data Collection and Preparation capability while adding explicit data-quality and analytical-readiness checks.

## Inputs

Use the available information about:

- Business question and decision to be supported
- Intended audience and required deliverable
- Population, unit of analysis, and time period
- Required measures, dimensions, and definitions
- Available data sources and owners
- Data-access permissions and restrictions
- Expected volume, format, and refresh frequency
- Known quality issues
- Sensitive, personal, regulated, or confidential fields
- Required deadline

Identify missing information rather than inventing definitions, data, access, or business rules.

## Workflow

1. Clarify the business question and decision.
2. Define the population, unit of analysis, timeframe, measures, dimensions, and comparison groups.
3. Identify required and available data sources.
4. Confirm access, permitted use, sensitivity, and handling requirements.
5. Document source ownership, lineage, extraction date, refresh timing, and applicable filters.
6. Inspect schemas, formats, data types, keys, relationships, and units.
7. Profile completeness, validity, accuracy, consistency, uniqueness, timeliness, and representativeness.
8. Identify missing values, duplicates, invalid values, outliers, inconsistent definitions, and join problems.
9. Evaluate potential selection, measurement, survivorship, or sampling bias.
10. Define and perform authorized cleaning and transformations reproducibly.
11. Preserve the original source data and document every material transformation.
12. Validate the prepared data against source totals, business rules, and expected ranges.
13. Determine whether the data is ready for the intended analysis.
14. Return the prepared-data summary and unresolved gaps to the Chief of Staff Agent.

## Data Quality Dimensions

Assess relevant dimensions:

- Completeness: Required records and fields are present.
- Validity: Values follow defined formats, types, ranges, and business rules.
- Accuracy: Values correctly represent the underlying events or entities.
- Consistency: Definitions and values agree across sources and time.
- Uniqueness: Duplicate entities or records are identified and handled appropriately.
- Timeliness: Data is current enough for the intended decision.
- Integrity: Keys, relationships, and referential links are reliable.
- Representativeness: The data adequately reflects the target population.
- Lineage: Sources and transformations can be traced and reproduced.

Do not claim accuracy when only format or completeness has been tested.

## Preparation Requirements

For each material transformation, document:

- Source field or table
- Transformation applied
- Reason
- Records affected
- Assumptions
- Validation performed
- Effect on interpretation
- Reproduction method

Examples include:

- Type conversions
- Unit standardization
- Missing-value treatment
- Duplicate handling
- Category mapping
- Date and timezone normalization
- Filtering and exclusions
- Joins and aggregations
- Derived measures
- Outlier treatment

Do not silently discard or overwrite data.

## Analytical Readiness

Recommend one of the following:

- Ready for analysis
- Ready with documented limitations
- Remediation required
- Additional data required
- Not suitable for the intended analysis

Explain the evidence supporting the recommendation.

## Required Output

Provide:

1. Executive summary
2. Business question and decision
3. Data requirements
4. Data sources, owners, and lineage
5. Access and permitted-use status
6. Dataset scope and extraction date
7. Data profile
8. Quality findings by dimension
9. Cleaning and transformation log
10. Validation results
11. Bias and representativeness concerns
12. Exclusions and assumptions
13. Analytical-readiness recommendation
14. Information gaps and limitations
15. Next actions, owners, and timing
16. Confidence level and rationale

## Handoffs

Recommend that the Chief of Staff Agent involve:

- The Innovation Agent when evidence changes the opportunity definition or feasibility
- The Compliance Agent when data access, privacy, security, retention, consent, or permitted use requires review
- The Project Management Agent when data acquisition, remediation, ownership, or delivery dependencies require tracking
- The Analysis and Insight Generation skill after the data is ready

## Guardrails

- Do not fabricate data, definitions, lineage, permissions, owners, or quality results.
- Do not access, copy, expose, or repurpose sensitive data without authorization.
- Do not overwrite or alter original source data.
- Do not silently remove records, impute values, change definitions, or exclude outliers.
- Do not claim data is accurate based only on superficial checks.
- Clearly distinguish observed quality problems from suspected problems.
- Preserve reproducibility by documenting material transformations and validation.
- Stop and escalate when access, permitted use, privacy, or security is uncertain.
