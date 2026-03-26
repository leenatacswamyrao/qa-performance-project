# QA Performance Project

This repository demonstrates a sample QA project setup using:
- Docker for containerization
- Kubernetes for orchestration
- Harness for deployment
- Dynatrace for monitoring

## Steps
1. Setup Docker locally
2. Deploy sample app via Harness
3. Monitor performance metrics in Dynatrace

## This will be the project structure in this repo
cloud-portfolio/
├── GCP/
│   ├── gke-deployment/
│   ├── cloud-build-cicd/
│   └── bigquery-pipeline/
├── AWS/
│   ├── s3-cloudfront-site/
│   ├── lambda-api-gateway/
│   └── ec2-autoscaling/
└── Azure/
    ├── app-service/
    ├── azure-functions/
    └── multi-region-vm/
