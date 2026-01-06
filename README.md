# Azure DevOps CI/CD Pipeline with IaC Validation

## Project Overview
This project demonstrates a complete CI/CD pipeline using GitHub Actions and Microsoft Azure.
The pipeline validates Infrastructure as Code (IaC) written in Bicep before allowing any deployment,
ensuring safe, repeatable, and cost-controlled cloud operations.

## Technologies Used
- Azure
- GitHub Actions
- Azure CLI
- Bicep (Infrastructure as Code)
- Git & GitHub

## Pipeline Stages
1. **CI – Validation**
   - Checks out source code
   - Authenticates securely to Azure using a Service Principal
   - Validates Bicep templates to prevent broken infrastructure deployments

2. **Controlled CD (Simulated)**
   - Uses environment-based manual approvals
   - Simulates a deployment to a DEV environment
   - Prevents accidental production changes

## Security & Cost Control
- Secrets managed using GitHub repository secrets
- Manual approval gates protect deployments
- No automatic production deployments
- Infrastructure is validated before creation to prevent unnecessary costs

## Key DevOps Concepts Demonstrated
- CI/CD pipeline design
- Infrastructure as Code
- Secure cloud authentication
- Environment-based approvals
- Failure handling and rollback concepts
- Cost-aware cloud engineering

## Why This Project Matters
This project reflects real-world DevOps practices used in enterprise environments such as banking,
telecommunications, and cloud service providers.

