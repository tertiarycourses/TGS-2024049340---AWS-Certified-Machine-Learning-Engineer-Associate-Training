# TGS-2024049340 - AWS Certified Machine Learning Engineer Associate Training

> Course: AWS Certified Machine Learning Engineer Associate Training  
> Course Code: TGS-2024049340  
> Register here: https://www.tertiarycourses.com.sg/wsq-aws-certified-machine-learning-engineer-associate-training.html

Hands-on AWS Certified Machine Learning Engineer Associate labs for learners preparing for the AWS Certified Machine Learning Engineer - Associate exam. The labs cover data preparation, feature engineering, data quality, model development, training, tuning, evaluation, deployment, orchestration, monitoring, security, cost optimization, and exam-style review.

## Courseware

| Item | Description |
| --- | --- |
| [Learner Guide](LG-AWS-Certified-Machine-Learning-Engineer-Associate-Training.md) | Detailed step-by-step guide for completing the labs and preparing final deliverables. |
| [Lab Guide](labs/README.md) | Lab catalogue grouped by AWS ML engineering skill area. |
| [Tools Reference](labs/tools.md) | Recommended AWS tools, cost-safety notes, and learner setup checklist. |

## How to Use

1. Create or use an AWS account provided by your trainer.
2. Create a working folder named `TGS-2024049340-AWS-MLA-Labs`.
3. Complete the labs in sequence because later labs reuse S3, SageMaker, IAM, model registry, endpoints, monitoring, and pipeline concepts.
4. Record screenshots, notebooks, SQL snippets, feature notes, model metrics, and configuration notes for each lab.
5. Delete paid resources when the lab asks you to clean up.

## Lab Catalogue

### Domain 1 - Data Preparation for Machine Learning

| Lab | Title | Focus |
| --- | --- | --- |
| [Lab 1](labs/lab-01-account-iam-s3-ml-data-lake.md) | Account Safety, IAM, S3 ML Data Lake, and Data Formats | IAM, S3, encryption, CSV/JSON/Parquet/ORC, SageMaker access |
| [Lab 2](labs/lab-02-data-ingestion-feature-engineering-quality.md) | Data Ingestion, Transformation, Feature Engineering, and Data Quality | Glue, Data Wrangler, DataBrew, Feature Store, bias and quality checks |

### Domain 2 - ML Model Development

| Lab | Title | Focus |
| --- | --- | --- |
| [Lab 3](labs/lab-03-modeling-approach-sagemaker-ai-services.md) | Modeling Approach, SageMaker Algorithms, JumpStart, and AI Services | Algorithm selection, SageMaker built-ins, Bedrock, Rekognition, Translate, Transcribe |
| [Lab 4](labs/lab-04-training-tuning-model-registry.md) | Training, Hyperparameter Tuning, and Model Registry | Training jobs, script mode, AMT, regularization, model versions, registry |
| [Lab 5](labs/lab-05-model-evaluation-performance-bias.md) | Model Evaluation, Performance Metrics, and Bias Analysis | Confusion matrix, F1, ROC/AUC, overfitting, Clarify, explainability |

### Domain 3 - Deployment, Orchestration, Monitoring, and Security

| Lab | Title | Focus |
| --- | --- | --- |
| [Lab 6](labs/lab-06-deployment-endpoints-inference-infrastructure.md) | Deployment Infrastructure, Endpoints, Batch Transform, and Auto Scaling | Real-time endpoints, serverless inference, batch transform, autoscaling, containers |
| [Lab 7](labs/lab-07-mlops-pipelines-cicd-orchestration.md) | MLOps Pipelines, CI/CD, and Workflow Orchestration | SageMaker Pipelines, Step Functions, CodePipeline, model approval, IaC |
| [Lab 8](labs/lab-08-monitoring-security-cost-exam-review.md) | Monitoring, Security, Cost Optimization, and Exam Review | Model Monitor, CloudWatch, data drift, IAM, KMS, VPC, cost, timed review |

## Reference

- AWS Certified Machine Learning Engineer - Associate exam guide: https://docs.aws.amazon.com/pdfs/aws-certification/latest/machine-learning-engineer-associate-01/machine-learning-engineer-associate-01.pdf
- Course registration: https://www.tertiarycourses.com.sg/wsq-aws-certified-machine-learning-engineer-associate-training.html
- AWS Documentation: https://docs.aws.amazon.com/
- Amazon SageMaker AI documentation: https://docs.aws.amazon.com/sagemaker/

## Free Tools Used

- AWS Free Tier eligible services where possible
- AWS Management Console
- Amazon SageMaker AI
- Amazon S3
- AWS Glue
- Amazon Athena
- Amazon CloudWatch
- AWS Step Functions
- AWS Pricing Calculator
