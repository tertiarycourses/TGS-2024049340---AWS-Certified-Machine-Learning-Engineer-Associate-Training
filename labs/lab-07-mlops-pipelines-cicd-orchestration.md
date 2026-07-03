# Lab 7 - MLOps Pipelines, CI/CD, and Workflow Orchestration

## Objectives

- Design an ML workflow from data preparation to deployment.
- Compare SageMaker Pipelines, Step Functions, CodePipeline, and EventBridge.
- Add approval, validation, rollback, and monitoring gates.
- Understand infrastructure as code and automation patterns.

## Scenario

Production ML requires orchestration across data, training, evaluation, model registration, deployment, and monitoring. This lab designs an MLOps pipeline.

## Steps

1. Open SageMaker Pipelines or review its documentation.
2. Review pipeline steps such as processing, training, tuning, condition, register model, and callback.
3. Open Step Functions and review workflow orchestration concepts.
4. Open CodePipeline and CodeBuild for CI/CD concepts.
5. Open EventBridge and review event-driven triggers.
6. Create a comparison table for SageMaker Pipelines, Step Functions, CodePipeline, and EventBridge.
7. Design an ML pipeline with ingest, validate, feature engineering, train, tune, evaluate, register, approve, deploy, and monitor steps.
8. Add failure paths and retry behavior.
9. Add human approval for model promotion.
10. Identify where IaC such as CloudFormation, CDK, or SageMaker project templates could be used.
11. Identify where version control and artifact storage are used.
12. Save your pipeline design.

## Deliverables

- MLOps orchestration comparison table
- End-to-end ML pipeline design
- Approval and rollback notes
- CI/CD and IaC notes

## Checkpoint

You should be able to describe how automated ML workflows move models from development to production safely.
