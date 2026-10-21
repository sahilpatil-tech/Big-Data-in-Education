# Big Data in Education: Analyzing Factors That Influence Student Academic Performance

A literature review exploring how big data, educational data mining, and learning analytics can help understand and predict student academic performance.

**Author:** Sahil Patil  
**Program:** Master of Computer Applications (MCA)  
**Institution:** R. C. Patel Institute of Management Research and Development, Shirpur  
**Project Guide:** Dr. Manoj Sonawne

## Overview

Educational institutions collect data through student information systems, learning management systems, attendance records, assessments, and online learning platforms. Analyzing these sources can help identify patterns associated with academic performance and support timely educational interventions.

This research reviews selected literature published primarily between 2014 and 2025. It examines student performance predictors, machine learning approaches, evaluation methods, research gaps, and responsible use of predictive analytics in education.

**Research status:** Literature review and conceptual system design. This project does not report a newly trained model or a completed software prototype.

## Research Objectives

- Identify academic, behavioral, demographic, social, and environmental factors associated with student performance.
- Review statistical and machine learning methods used for academic performance prediction.
- Examine the trade-offs between model performance, interpretability, and data requirements.
- Explore responsible early-warning systems that support students.
- Discuss privacy, fairness, transparency, and human oversight.

## Research Questions

1. Which student and learning-context factors are commonly reported as predictors of academic outcomes?
2. Which statistical and machine learning methods are used, and what trade-offs do they involve?
3. How can predictions support early intervention while protecting privacy, fairness, and student agency?

## Research Documents

- **Research paper:** [`research-paper/Big_Data_in_Education_.pdf`](research-paper/Big_Data_in_Education_.pdf)
- **Presentation:** [`presentation/Big_Data_in_Education.pptx`](presentation/Big_Data_in_Education.pptx)

## System Architecture

The conceptual architecture brings together educational data sources, data ingestion and storage, data preparation, predictive modelling, evaluation, and educational interventions.

![System Architecture](diagrams/01_system_architecture.png)

## Educational Analytics Workflow

The workflow describes the process from defining the research target and collecting permitted data to preparing features, comparing models, reviewing results, and monitoring interventions.

![Educational Analytics Workflow](diagrams/02_workflow_analytics_pipeline.png)

## Responsible Early-Warning Cycle

The proposed cycle places educator review between risk estimation and student support. Predictions are intended to encourage supportive action, not automatic punishment or labeling.

![Responsible Early-Warning Cycle](diagrams/03_workflow_early_warning_cycle.png)

## Research Methodology

The paper uses a literature-review approach to synthesize findings from selected publications. The proposed review process includes literature identification, screening, eligibility assessment, data extraction, and thematic synthesis.

The source draft does not contain a complete reproducible search log or screening counts. The work is therefore presented as a narrative literature review rather than a completed systematic review.

![Research Methodology](diagrams/04_research_methodology.png)

## Data-Flow Diagrams

### Level 0: Context Diagram

Shows the conceptual interactions between the Student Performance Analytics System, students and data owners, institutional systems, educators, and administrators.

![DFD Level 0](diagrams/05_dfd_level0_context.png)

### Level 1: Detailed Data Flow

Shows the proposed processing stages, including data collection, validation, feature engineering, model training, risk explanation, educator intervention, and monitoring.

![DFD Level 1](diagrams/06_dfd_level1.png)

## Key Themes

- Prior academic achievement and assessment results
- Attendance and online learning engagement
- Student context, social support, and access to learning resources
- Predictive modelling and evaluation metrics
- Information leakage and generalization
- Privacy, fairness, interpretability, and human oversight

## Limitations and Future Work

The current work is a literature synthesis and conceptual design, not an empirical experiment. Future work includes documenting the search and screening process, verifying bibliographic metadata, developing a study-by-study evidence table, and evaluating the effectiveness and fairness of educational interventions.

## Repository Structure

```text
big-data-in-education/
├── README.md
├── research-paper/
├── presentation/
├── diagrams/
└── references/
```

## Academic Integrity

Research findings and performance metrics should be interpreted in the context of their original publications. References, source attribution, and any applicable institutional requirements should be verified before academic submission or public distribution.

## Author

**Sahil Patil**  
MCA Student | Academic Research in Educational Data Analytics


