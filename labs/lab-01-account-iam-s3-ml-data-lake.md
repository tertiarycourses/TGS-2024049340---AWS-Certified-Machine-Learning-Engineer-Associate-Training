# Lab 1 - Account Safety, IAM, S3 ML Data Lake, and Data Formats

## Objectives

- Configure a safe AWS learning baseline for ML engineering.
- Review IAM roles, policies, and least privilege for SageMaker and data services.
- Create an S3 ML data lake structure if permitted.
- Compare common ML data formats.

## Scenario

Machine learning projects require secure access, controlled storage, and data formats that support training and inference workflows. This lab establishes the baseline for later ML tasks.

## Steps

1. Sign in to the AWS account assigned by your trainer.
2. Confirm you are in the correct region.
3. Open IAM and review users, roles, groups, and policies.
4. Verify MFA where permitted.
5. Review least-privilege access for S3, SageMaker, Glue, Athena, KMS, and CloudWatch.
6. Open SageMaker and review execution role concepts.
7. Open S3.
8. Create a bucket only if your trainer permits it.
9. Enable default encryption.
10. Keep Block Public Access enabled.
11. Create prefixes named `raw/`, `prepared/`, `features/`, `training/`, `models/`, and `monitoring/`.
12. Upload small sample CSV and JSON files to `raw/` if permitted.
13. Review object metadata and storage class.
14. Create a table comparing CSV, JSON, Parquet, ORC, Avro, and RecordIO.
15. Record which formats are best for analytics, streaming, and training workflows.
16. Open KMS and review customer managed key concepts.
17. Save your notes.

## Deliverables

- IAM and least-privilege notes
- S3 ML data lake prefix structure
- Data format comparison table
- Encryption and cost safety notes

## Checkpoint

You should be able to explain how IAM, S3, encryption, and data formats support ML engineering on AWS.
