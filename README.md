# Richard Ugo

### Senior Cloud / DevOps Engineer

**Azure • AWS • Terraform • Kubernetes • AKS • EKS • Azure DevOps • GitHub Actions • Python • Boto3 • OPA/Rego • Cloud Networking • Security & Governance**

I design and automate enterprise cloud platforms with a focus on Infrastructure as Code, CI/CD, Kubernetes, policy as code, private networking, identity, and operational automation. This GitHub profile contains sanitized reference implementations of engineering patterns I have worked with professionally. It does not contain employer or customer proprietary code.

## Engineering Portfolio

| Area | Demonstrated here |
|---|---|
| Infrastructure as Code | Reusable Terraform modules, environment configuration, networking, Key Vault, monitoring and governance |
| CI/CD | Terraform validation, planning, security/policy gates, deployment controls and post-deployment validation |
| Kubernetes | AKS platform provisioning, Deployments, Services, ingress, HPA, health probes and release validation |
| Policy as Code | OPA/Rego controls, policy tests, Terraform plan evaluation and Azure Policy |
| Python Automation | Terraform plan JSON analysis and Kubernetes deployment-health validation |
| Cloud Security | Managed identity, RBAC, private connectivity, Key Vault and policy guardrails |
| Multi-cloud | Azure-focused implementations with AWS/EKS/Boto3 reference implementations being expanded |

## Featured Projects

### [AKS Platform with Terraform](https://github.com/ugochuk/aks-platform-terraform)
Production-minded AKS reference architecture with Terraform and Kubernetes manifests. The repository covers managed identity, networking, ACR integration, autoscaling, ingress and workload configuration. It also includes Python release-validation automation that evaluates desired vs. available/ready/updated replicas and rollout health so CI/CD can fail fast when a deployment is unhealthy.

**Technologies:** Terraform • AKS • Kubernetes • Python • kubectl • GitHub Actions • Azure

### [Azure Enterprise Landing Zone](https://github.com/ugochuk/azure-enterprise-landing-zone)
Reusable Terraform foundation for Azure networking, Key Vault, monitoring and governance across environment configurations. The repository also demonstrates Python automation for parsing Terraform `plan_output.json` style data, classifying resource creates, updates, deletes and replacements, validating required plan metadata and publishing a CI artifact for downstream review.

**Technologies:** Terraform • Azure • Python • GitHub Actions • VNets • Key Vault • Azure Policy • Log Analytics

### [Azure Policy + OPA/Rego Governance](https://github.com/ugochuk/azure-policy-opa-governance)
Policy-as-Code implementation combining OPA/Rego pre-deployment controls with Azure Policy. Includes security policies, deterministic Rego tests, compliant/noncompliant Terraform examples, Terraform-plan evaluation patterns and automated CI policy gates.

**Technologies:** OPA • Rego • Azure Policy • Terraform • GitHub Actions • DevSecOps

### [Terraform CI/CD with GitHub Actions](https://github.com/ugochuk/terraform-cicd-github-actions)
Infrastructure delivery workflow demonstrating Terraform validation, planning, security scanning, Azure authentication, deployment controls and post-deployment verification.

**Technologies:** Terraform • GitHub Actions • CI/CD • Azure • TFLint • Trivy

## Resume-to-Code Map

The portfolio is intentionally organized so technical claims can be inspected as code rather than existing only as resume keywords.

| Professional capability | Portfolio evidence |
|---|---|
| Reusable Terraform infrastructure | `azure-enterprise-landing-zone/modules/` and `aks-platform-terraform/terraform/` |
| Terraform plan automation with Python | `azure-enterprise-landing-zone/scripts/terraform_plan_summary.py` |
| Automated AKS release validation | `aks-platform-terraform/scripts/validate_aks_release.py` |
| Kubernetes workload configuration | `aks-platform-terraform/kubernetes/` |
| OPA/Rego policy as code | `azure-policy-opa-governance/policies/` and `tests/` |
| CI/CD automation | `.github/workflows/` across the featured repositories |
| Private Azure platform patterns | Azure landing-zone networking and Key Vault modules |

## Technical Stack

**Cloud:** Microsoft Azure, AWS, GCP, OCI  
**Containers:** Kubernetes, AKS, EKS, Docker, Helm, kubectl  
**Infrastructure as Code:** Terraform, CloudFormation, ARM  
**Policy as Code:** OPA/Rego, Azure Policy  
**CI/CD:** Azure DevOps, GitHub Actions, YAML pipelines, Git  
**Automation:** Python, Boto3, Go, PowerShell, Azure CLI, REST APIs, JSON, YAML  
**Azure:** VNets, Private Endpoints, Private DNS, Key Vault, Managed Identities, RBAC, ACR, Azure Monitor, App Service, Functions, Cosmos DB, Azure SQL, Storage  
**AWS:** EC2, VPC, IAM, EKS, ECR, CloudFormation and multi-account automation patterns

## Architecture Approach

My reference implementations emphasize reusable modules over one-off resource definitions, private connectivity over unnecessary public exposure, identity-based access over embedded credentials, automated validation over manual review, environment promotion over configuration drift, and operational checks that can be executed consistently by CI/CD.

## Certifications

- Microsoft Certified: Cybersecurity Architect Expert
- Microsoft Certified: Azure Solutions Architect Expert
- Microsoft Certified: DevOps Engineer Expert
- AWS Certified Solutions Architect – Professional
- AWS Certified Security – Specialty
- Google Cloud Professional Cloud Architect
- Google Cloud Professional Cloud Security Engineer
- Microsoft Certified: Azure Network Engineer Associate
- HashiCorp Certified: Terraform Associate

## About the Code

These repositories are portfolio-safe implementations designed to demonstrate engineering approaches and technical patterns without publishing employer/customer source code, internal infrastructure identifiers, credentials, proprietary architecture, or confidential data.

## Contact

**GitHub:** [github.com/ugochuk](https://github.com/ugochuk)  
**Email:** richardugo50@gmail.com  
**Location:** Vancouver, Washington
