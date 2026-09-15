# Data Analyst Agent

The Data Analyst Agent is a specialist agent designed to support a broader Chief of Staff Agent. It defines data requirements, prepares and validates data, performs reproducible analysis, and communicates decision-relevant insights through clear visualizations and executive narratives.

This repository is an early prototype exploring how specialized agents can strengthen evidence-based executive decision-making.

## Role in the Agent System

The Chief of Staff Agent acts as the orchestrator. It assigns analytical work to the Data Analyst Agent and combines its findings with input from other specialist agents.

The Data Analyst Agent may recommend involvement from:

- Innovation Agent for opportunity definition, value, feasibility, or prioritization
- Compliance Agent for privacy, security, permitted use, retention, fairness, and governance
- Project Management Agent for delivery tracking, dependencies, benefits realization, and corrective actions

The Data Analyst Agent provides analytical decision support. It does not fabricate evidence, approve business decisions, override data-governance requirements, or use data beyond its authorized purpose.

## Core Skills

### 1. Data Intake, Preparation, and Quality Assessment

Translates a business question into data requirements; identifies data sources, definitions, and lineage; prepares and validates data; and determines whether the data is suitable for analysis.

[View the Data Intake, Preparation, and Quality Assessment skill](.agents/skills/data-intake-preparation-quality/SKILL.md)

### 2. Analysis and Insight Generation

Selects and applies appropriate analytical methods, validates results, quantifies uncertainty, and translates findings into decision-relevant insights.

[View the Analysis and Insight Generation skill](.agents/skills/analysis-insight-generation/SKILL.md)

### 3. Visualization and Executive Narrative

Selects accurate tables, charts, dashboards, and communication formats and translates validated findings into executive implications, recommendations, limitations, and next actions.

[View the Visualization and Executive Narrative skill](.agents/skills/visualization-executive-narrative/SKILL.md)

## Typical Workflow

1. Clarify the business question and decision.
2. Define data requirements and identify appropriate sources.
3. Prepare, profile, and validate the data.
4. Select and perform an appropriate analysis.
5. Validate results and quantify relevant uncertainty.
6. Identify decision-relevant findings.
7. Communicate findings through an appropriate visual and executive narrative.
8. Return evidence, limitations, recommendations, and next actions to the Chief of Staff Agent.

Not every assignment requires all three skills. The agent begins at the stage appropriate to the available data, prior validation, and decision context.

## Example Use Case

**Assignment:** Determine whether an AI meeting-preparation pilot saves executive time and improves decision readiness.

The Data Analyst Agent can:

- Define baseline, pilot, and comparison measures
- Identify required data sources and quality requirements
- Prepare and validate time, usage, feedback, and outcome data
- Compare pilot results with the baseline
- Quantify uncertainty and identify limitations
- Create an executive-ready visualization and narrative
- Recommend whether additional evidence is needed before scaling

## Repository Structure

```text
data_analyst_agent/
├── AGENTS.md
├── README.md
└── .agents/
    └── skills/
        ├── data-intake-preparation-quality/
        │   └── SKILL.md
        ├── analysis-insight-generation/
        │   └── SKILL.md
        └── visualization-executive-narrative/
            └── SKILL.md
```

## Status

Early-stage prototype for professional development and concept validation. The current version establishes the Data Analyst Agent’s role, routing instructions, core skills, analytical standards, outputs, handoffs, evidence expectations, and guardrails.
