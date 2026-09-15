---
name: analysis-insight-generation
description: Select and apply appropriate analytical methods to prepared data, validate results, quantify uncertainty, and translate findings into decision-relevant insights. Use when answering a business question through descriptive, diagnostic, comparative, statistical, predictive, or scenario analysis.
---

# Analysis and Insight Generation

## Purpose

Produce accurate, reproducible analysis that answers a defined business question and clearly distinguishes findings, interpretations, limitations, and recommendations.

Use data that has completed an appropriate readiness assessment. If data quality is insufficient, stop or qualify the analysis rather than producing misleading results.

## Inputs

Use the available information about:

- Business question and decision
- Intended audience
- Prepared dataset and data dictionary
- Population, unit of analysis, and timeframe
- Measures, dimensions, and definitions
- Comparison groups and baselines
- Data-quality findings and limitations
- Relevant business rules
- Required analytical method or deliverable
- Deadline and decision context

Identify missing information rather than inventing data, definitions, benchmarks, or assumptions.

## Select the Analytical Approach

Choose the simplest valid approach capable of answering the question:

- Descriptive: What happened?
- Diagnostic: What factors are associated with what happened?
- Comparative: How do groups, periods, or alternatives differ?
- Statistical inference: How precisely can patterns be estimated?
- Predictive: What outcome is likely under defined conditions?
- Scenario or sensitivity analysis: How might results change under different assumptions?

Explain the selected approach when method choice materially affects interpretation.

Do not use predictive or complex statistical methods when descriptive analysis is sufficient.

## Workflow

1. Confirm the business question, decision, audience, and analytical unit.
2. Review data readiness, exclusions, transformations, and limitations.
3. Define measures, comparison groups, baselines, and evaluation criteria.
4. Select an appropriate analytical method.
5. Document assumptions and potential sources of bias or confounding.
6. Perform the analysis using reproducible calculations.
7. Validate totals, denominators, joins, filters, units, and calculations.
8. Compare results with expected ranges, prior periods, or relevant benchmarks when available.
9. Test sensitivity to material assumptions when appropriate.
10. Quantify uncertainty when the data and method support it.
11. Investigate unexpected results before presenting them as insights.
12. Distinguish association, prediction, and causation.
13. Identify findings that materially affect the decision.
14. Translate findings into implications, limitations, and recommended next actions.
15. Return the analytical results to the Chief of Staff Agent.

## Validation Requirements

Perform relevant checks, including:

- Row counts and reconciliation totals
- Denominator and population validation
- Duplicate and missing-value effects
- Join cardinality and unmatched records
- Unit and time-period consistency
- Calculation replication
- Outlier and sensitivity effects
- Train, validation, and test separation for predictive work
- Comparison with a baseline or simple benchmark
- Leakage, overfitting, and generalizability concerns
- Subgroup performance when materially relevant

Do not describe a result as validated if only the code executed successfully.

## Interpretation Standards

Clearly distinguish:

- Observed finding
- Analytical interpretation
- Assumption
- Estimate or forecast
- Correlation or association
- Causal conclusion
- Recommendation

Do not infer causation from correlation without a valid causal design.

Report both absolute and relative differences when either alone could mislead. Include denominators and sample sizes where relevant.

## Required Output

Provide:

1. Executive summary
2. Business question and decision
3. Data scope and analytical population
4. Method and rationale
5. Measures, definitions, and comparison groups
6. Assumptions and exclusions
7. Key results
8. Validation performed
9. Decision-relevant insights
10. Uncertainty, sensitivity, and limitations
11. Potential bias and generalizability concerns
12. Recommendations and alternative interpretations
13. Next actions, owners, and timing
14. Reproduction information
15. Confidence level and rationale

## Reproducibility

Document:

- Data source and extraction date
- Filters and exclusions
- Transformations
- Calculation logic
- Code, query, formula, or procedure used
- Software or tool version when material
- Random seed when applicable
- Output location and version

Preserve enough information for another qualified analyst to reproduce the result.

## Handoffs

Recommend that the Chief of Staff Agent involve:

- The Innovation Agent when findings change opportunity value, feasibility, or prioritization
- The Compliance Agent when analysis involves sensitive data, fairness, privacy, retention, permitted use, or regulated decisions
- The Project Management Agent when findings affect milestones, benefits, forecasts, risks, or corrective actions
- The Visualization and Executive Narrative skill when results are ready for communication

## Guardrails

- Do not fabricate data, results, benchmarks, statistical significance, or supporting evidence.
- Do not analyze data that is not authorized for the intended use.
- Do not conceal missing data, exclusions, failed validations, or unfavorable results.
- Do not claim causation without an appropriate design.
- Do not present model performance without a valid evaluation approach.
- Do not use unnecessary analytical complexity.
- Preserve reproducibility and distinguish facts, assumptions, estimates, and recommendations.
- Stop or qualify the analysis when data quality cannot support the requested conclusion.
