# AAI-501 – Team Project Status Update Form

Prepared November 14, 2026


## Team Number

4


## Team Leader/Representative

Jagan Bakkiyanathan


## Full Names of Team Members

1. Jagan Bakkiyanathan
2. Francisco Gutierrez
3. Shahbaj Singh


## Title of Your Project

Predicting E-commerce Purchases and Interpreting Visitor Behavior Using Machine Learning


## Short Description of Your Project and Objectives

Our project will investigate how online shopping session behavior relates to purchasing intentions. We plan to compare classification models and explain the browsing and visitor characteristics associated with purchases. A proposed extension beyond standard purchase/no-purchase classification is to test whether a smaller set of features retains useful predictive performance compared with all eligible features. We will also examine patterns for new and returning visitors.
Planned work includes exploratory analysis of correlated features and potential confounding, comparison of at least two classifiers, and evaluation of precision, recall, F1, and precision-recall performance alongside accuracy. Logistic regression and random forest are proposed candidates; final choices will depend on course coverage and initial analysis. We will explain the balance between predictive performance, interpretability, and the business consequences of prediction errors.


## Name of Your Selected Dataset

Online Shoppers Purchasing Intention Dataset


## Description of Your Selected Dataset

Source: UCI Machine Learning Repository. The existing dataset-selection research documents 12,330 shopping sessions, 17 predictors, and one binary target, Revenue (purchase/no purchase), for 18 variables total. Predictors cover page counts and durations, bounce and exit rates, page values, month, visitor type, traffic source, browser, operating system, region, special-day proximity, and weekend status. The documented target distribution is 1,908 purchasing sessions and 10,422 non-purchasing sessions. Actual downloaded-file dimensions and data quality remain to be checked.
Dataset: https://archive.ics.uci.edu/dataset/468/online+shoppers+purchasing+intention+dataset


## Are you using and practicing GitHub for version control and collaboration?

Yes. The repository contains project requirements and a dataset-selection planning notebook, with recorded commits. Continued team collaboration and implementation will be tracked there.
https://github.com/frangu617/AAI-501-Final-Project


## How many times have your members met in the last two weeks?

Approximately four meetings (about twice per week), based on the current team estimate.


## Specific Contributions by Team Member

All students should contribute equally. Individual details not documented below require confirmation.


### Jagan Bakkiyanathan

Team leader/representative. Named on the original project proposal. Specific completed tasks and ongoing responsibilities beyond the representative role: to be confirmed.


### Francisco Gutierrez

Documented project requirements in the repository and prepared the dataset-selection notebook comparing three UCI datasets, including proposed experiments, evaluation metrics, preprocessing issues, and a recommended project scope. Git history records these contributions.


### Shahbaj Singh

Team member. Specific completed tasks and ongoing responsibilities: to be confirmed.


## Comments / Roadblocks

Current status: The project proposal and dataset-selection planning notebook are available. The notebook is a planning document; it does not contain executed data preparation or modeling experiments. No model performance results are available yet.
Next steps: Obtain and inspect the selected dataset; reserve a held-out test set; examine class imbalance, distributions, correlated features, and visitor subgroups; build preprocessing pipelines and baseline models; compare full and reduced feature sets using consistent validation. Feature selection and preprocessing will be fitted on training data only.
Issues to resolve: Finalize the distinctive research question and algorithm choices; check when session features would actually be available for prediction, including PageValues; avoid causal interpretations of observational relationships; and confirm each member's responsibilities so contributions remain balanced. No specific technical blocker has been documented.


AI assistance: OpenAI Codex assisted in drafting and formatting this status update from the team proposal, repository, planning notebook, instructor feedback, and information supplied by Francisco Gutierrez. No experimental results were generated for this update.