# Raghav Chhabra
### Data science · Analytics · Data engineering

I'm completing my **M.S. in Machine Learning and Data Science at Northwestern University (December 2026)**. I like turning messy data into tools people can use—from explainable sports models to automated data workflows and expense-management products.

My experience includes data quality and automation at Roche, language-model work at T-Mobile, and analytics across healthcare and automotive teams.

[LinkedIn](https://www.linkedin.com/in/raghav-chhabraa/) · [Trace](https://teamtracer.app)

## Selected projects

### [NBA Matchup Predictor](https://github.com/raghavchhabra123/nba-matchup-predictor)
**Predictive modeling · Model evaluation · Interactive analytics**

An interactive Streamlit dashboard that breaks a matchup into team strength, home court, rest, and player-availability scenarios. The point-spread engine converts an expected scoring margin into a win probability.

- **Reproduced chronological evaluation:** 67.79% accuracy across 2,462 games; log loss 0.6035 and Brier score 0.2082. Elo alone scores 67.83% accuracy; the difference is within the paired uncertainty interval.
- Results apply to the historical Elo + home-court + rest engine, **not** the live app's projected-roster, player-availability, or travel adjustments.
- The audited pipeline adds training-only preprocessing, rolling development folds, per-game predictions, leakage regression tests and automated evaluation checks. The evaluation seasons have already been inspected, so these are retrospective results rather than an untouched final test.

**Tools:** Python, pandas, NumPy, Streamlit  
[Live demo](https://nba-matchup-predictor.streamlit.app/) · [Code & methodology](https://github.com/raghavchhabra123/nba-matchup-predictor) · [Saved evaluation](https://github.com/raghavchhabra123/nba-matchup-predictor/blob/main/models/metrics_tier1.json)

### [Formula 1 Data Pipeline](https://github.com/1haochen/mlds_f1_project)
**Data engineering · Workflow orchestration · Analytics-ready data**

A team project using OpenF1 data to build a reproducible racing-data pipeline. My work focused on the end-to-end pipeline and Airflow branching for full versus incremental loads.

- Connects API ingestion, transformation, and storage.
- Supports analysis of tyre and stint information.
- Documented setup with Docker and Airflow.

**Tools:** Python, SQL, Apache Airflow, Docker, SQLite  
[Team repository & setup](https://github.com/1haochen/mlds_f1_project)

### [Object Detection Under Distribution Shift](https://github.com/raghavchhabra123/object-detection-generalization)
**Computer vision · Experimental analysis · Generalization**

A five-person team project comparing YOLOv8 models on traffic imagery and synthetic examples, examining how performance changes outside the original test distribution.

- YOLOv8m's reported mAP@50 falls from **0.860 on the test set to 0.153 on synthetic data**.
- Demonstrates why a strong in-distribution score is not enough to establish robustness.
- Metrics are in the repository; example predictions are in the team's project report.

**Tools:** Python, YOLOv8  
[Experiments & results](https://github.com/raghavchhabra123/object-detection-generalization)

### [Trace — Expense Management](https://teamtracer.app)
**Co-founder, Product · Workflow design · Applied AI**

An expense-management platform shaped by research into seven procurement tools and feedback from small-business operators and accountants. We shifted the product toward approvals before spending, rather than only tracking expenses afterward.

- Built on a serverless AWS stack with an append-only audit trail.
- Uses Amazon Textract for receipt processing.
- Connects product research with operational workflows and implementation.

**Tools:** AWS Lambda, DynamoDB, S3, Cognito, Textract  
[Product](https://teamtracer.app) · Public product overview; source code is not linked here.

## Technical toolkit

**Analysis & modeling:** Python, SQL, statistics, machine learning, pandas, NumPy  
**Data & infrastructure:** Snowflake, PySpark, Airflow, Docker, AWS, GCP  
**Communication:** Tableau, Power BI, stakeholder reporting, product research

## What I'm looking for

Data science, data analyst, data engineering, analytics engineering, and product analytics opportunities. Available for full-time work starting **January 4, 2027**.

For project evaluation, start with the linked README and evidence above. Earlier coursework and exploratory notebooks remain in my repositories but are not the primary portfolio.
