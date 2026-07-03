# Learner Guide - AWS Certified Machine Learning Engineer Associate Training

> Course: AWS Certified Machine Learning Engineer Associate Training  
> Course Code: TGS-2024049340  
> Registration: https://www.tertiarycourses.com.sg/wsq-aws-certified-machine-learning-engineer-associate-training.html

This learner guide supports a practical AWS Certified Machine Learning Engineer Associate course. It is designed for learners preparing to build, operationalize, deploy, maintain, monitor, and secure machine learning solutions and pipelines on AWS.

## Learning Outcomes

By the end of the labs, you should be able to:

- Prepare secure AWS storage and IAM foundations for ML engineering.
- Ingest, transform, validate, and prepare data for ML modeling.
- Perform feature engineering and understand feature store, labeling, data quality, and bias checks.
- Choose modeling approaches using SageMaker built-in algorithms, custom frameworks, JumpStart, Bedrock, and AI services.
- Train, tune, evaluate, and version models.
- Analyze model performance, bias, explainability, and approval readiness.
- Select deployment infrastructure for real-time, serverless, asynchronous, and batch inference.
- Design MLOps workflows with pipelines, CI/CD, orchestration, model registry, and approval gates.
- Monitor models, data, endpoints, infrastructure, cost, and security.
- Prepare for AWS Machine Learning Engineer Associate exam-style scenarios.

## Recommended Setup

1. Use a trainer-provided AWS account where available.
2. If using your own account, enable MFA and create a budget alert before starting labs.
3. Create a working folder named `TGS-2024049340-AWS-MLA-Labs`.
4. Save screenshots, notebooks, SQL snippets, model metrics, pipeline diagrams, and comparison tables.
5. Delete temporary AWS resources after each hands-on exercise.

## Cost Safety Rules

- Use small datasets and short training jobs.
- Stop SageMaker Studio apps and notebooks when not in use.
- Delete endpoints after inference labs if instructed.
- Avoid GPU instances unless explicitly assigned.
- Check Billing and Cost Management after hands-on labs.

## Lab 1 - Account Safety, IAM, S3 ML Data Lake, and Data Formats

### Objectives

- Establish a secure ML engineering baseline.
- Review SageMaker and data-service permissions.
- Create an S3 ML data lake structure.
- Compare data formats.

### Procedure

1. Sign in to the assigned AWS account.
2. Confirm account and region.
3. Review IAM users, roles, policies, and MFA.
4. Review least-privilege access for S3, SageMaker, Glue, Athena, KMS, and CloudWatch.
5. Review SageMaker execution role concepts.
6. Create an S3 bucket only if permitted.
7. Enable encryption and block public access.
8. Create prefixes for raw, prepared, features, training, models, and monitoring.
9. Upload small sample files if permitted.
10. Compare CSV, JSON, Parquet, ORC, Avro, and RecordIO.
11. Review KMS key concepts.
12. Save your notes.

### Checkpoint

You should be able to explain secure ML data storage, IAM, encryption, and format choices.

## Lab 2 - Data Ingestion, Transformation, Feature Engineering, and Data Quality

### Objectives

- Compare ingestion and transformation tools.
- Apply feature engineering concepts.
- Review data quality, labeling, and bias checks.
- Design raw-to-training preparation.

### Procedure

1. Review Glue crawlers, jobs, Data Catalog, and Glue Data Quality.
2. Review SageMaker Data Wrangler transformations.
3. Review feature engineering techniques such as imputation, normalization, binning, and encoding.
4. Review SageMaker Feature Store online and offline use cases.
5. Review SageMaker Ground Truth labeling concepts.
6. Review SageMaker Clarify bias detection concepts.
7. Create a feature engineering checklist.
8. Create a data quality checklist.
9. Design a pipeline from S3 raw data to prepared features.
10. Save your notes.

### Checkpoint

You should be able to design data preparation workflows for ML modeling.

## Lab 3 - Modeling Approach, SageMaker Algorithms, JumpStart, and AI Services

### Objectives

- Select ML approaches.
- Compare SageMaker algorithms, custom frameworks, JumpStart, Bedrock, and AI services.
- Consider cost and interpretability.
- Build a model selection matrix.

### Procedure

1. Review classification, regression, clustering, forecasting, anomaly detection, NLP, and vision problems.
2. Review SageMaker built-in algorithms.
3. Review script mode and supported frameworks.
4. Review SageMaker JumpStart.
5. Review Amazon Bedrock and AI services such as Rekognition, Translate, Transcribe, Comprehend, and Textract.
6. Create a model/service selection table for business scenarios.
7. Identify when managed AI services are better than custom training.
8. Save your notes.

### Checkpoint

You should be able to choose a modeling approach based on data, outcome, cost, and operations.

## Lab 4 - Training, Hyperparameter Tuning, and Model Registry

### Objectives

- Understand SageMaker training jobs.
- Design tuning and regularization.
- Manage versions and approvals.
- Prevent overfitting and underfitting.

### Procedure

1. Review training input, output, instance, container, and role concepts.
2. Review script mode and framework estimators.
3. Review epoch, batch size, learning rate, steps, and early stopping.
4. Review L1, L2, dropout, pruning, and feature selection.
5. Review Automatic Model Tuning.
6. Create a tuning plan with objective metric, hyperparameters, ranges, stopping condition, and cost limit.
7. Review Model Registry package groups, versions, approval status, and metadata.
8. Design a model versioning workflow.
9. Save your notes.

### Checkpoint

You should be able to explain repeatable training, tuning, and model version control.

## Lab 5 - Model Evaluation, Performance Metrics, and Bias Analysis

### Objectives

- Choose evaluation metrics.
- Diagnose model performance issues.
- Review bias and explainability.
- Build model approval criteria.

### Procedure

1. Compare classification metrics such as accuracy, precision, recall, F1, ROC AUC, and confusion matrix.
2. Compare regression metrics such as MAE, MSE, RMSE, and R-squared.
3. Review overfitting, underfitting, class imbalance, and data leakage.
4. Review SageMaker Clarify bias and explainability concepts.
5. Design an evaluation plan for a binary classification model.
6. Define split strategy, minimum metrics, bias checks, and explainability checks.
7. Save your notes.

### Checkpoint

You should be able to evaluate whether a model is ready for approval or needs more work.

## Lab 6 - Deployment Infrastructure, Endpoints, Batch Transform, and Auto Scaling

### Objectives

- Compare inference deployment options.
- Choose infrastructure based on latency and throughput.
- Review auto scaling and monitoring.
- Plan rollback and operations.

### Procedure

1. Review real-time endpoints.
2. Review serverless inference.
3. Review asynchronous inference.
4. Review batch transform.
5. Review multi-model and multi-container endpoints.
6. Compare deployment options by latency, payload, traffic, cost, scaling, and complexity.
7. Choose deployment options for several use cases.
8. Identify CloudWatch metrics and logs.
9. Record rollback considerations.
10. Save your notes.

### Checkpoint

You should be able to select SageMaker deployment infrastructure for common inference workloads.

## Lab 7 - MLOps Pipelines, CI/CD, and Workflow Orchestration

### Objectives

- Design an end-to-end ML workflow.
- Compare orchestration and CI/CD tools.
- Add approval and rollback gates.
- Understand IaC and version control touchpoints.

### Procedure

1. Review SageMaker Pipelines steps.
2. Review Step Functions workflow orchestration.
3. Review CodePipeline and CodeBuild.
4. Review EventBridge triggers.
5. Compare orchestration services.
6. Design a workflow with ingest, validate, feature engineering, train, tune, evaluate, register, approve, deploy, and monitor steps.
7. Add failure paths, retries, human approval, version control, and artifact storage.
8. Save your design.

### Checkpoint

You should be able to explain how MLOps automates safe model delivery.

## Lab 8 - Monitoring, Security, Cost Optimization, and Exam Review

### Objectives

- Monitor ML systems.
- Secure ML data, models, and endpoints.
- Optimize cost.
- Complete exam-style review.

### Procedure

1. Review SageMaker Model Monitor.
2. Review data quality, model quality, bias drift, and feature attribution drift.
3. Review CloudWatch metrics, logs, alarms, dashboards, and anomaly detection.
4. Review CloudTrail audit events.
5. Review IAM, KMS, VPC endpoints, private subnets, and network isolation.
6. Review data classification, masking, anonymization, PII, PHI, and data residency.
7. Create monitoring, security, and cost optimization checklists.
8. Map labs to exam domains.
9. Complete a timed 30-question practice set.
10. Mark weak topics and create a revision plan.
11. Clean up temporary resources.

### Checkpoint

You should be ready to explain AWS ML engineering scenarios across preparation, development, deployment, monitoring, and security.

## Final Submission Checklist

- Lab notes or screenshots
- Data preparation and feature engineering checklist
- Model and service selection matrix
- Training and tuning plan
- Evaluation and bias checklist
- Deployment comparison table
- MLOps pipeline design
- Monitoring, security, and cost checklists
- Timed practice score
- Weak-topic revision plan

## Suggested Course Flow

| Segment | Focus | Labs |
| --- | --- | --- |
| Segment 1 | ML data lake, data preparation, feature engineering, quality | Labs 1-2 |
| Segment 2 | Modeling, training, tuning, evaluation | Labs 3-5 |
| Segment 3 | Deployment, MLOps, monitoring, security, exam review | Labs 6-8 |

## Clean Up

1. Delete temporary S3 buckets, objects, and query results if instructed.
2. Delete SageMaker endpoints, model packages, pipelines, training jobs, and temporary resources if instructed.
3. Stop SageMaker Studio apps and notebooks.
4. Keep budget alerts active until the trainer confirms cleanup.
5. Save notes for final revision.
