# Richard Ugo

### Senior Cloud / DevOps Engineer

**Azure • AWS • Terraform • Kubernetes • AKS • EKS • Observability • OpenTelemetry • Prometheus • Grafana • Azure Monitor • CloudWatch • CI/CD • Python • OPA/Rego**

I design and automate enterprise cloud platforms with a focus on Infrastructure as Code, CI/CD, Kubernetes, policy as code, private networking, identity, and operational automation. This GitHub profile contains sanitized reference implementations of engineering patterns I have worked with professionally. It does not contain employer or customer proprietary code.

## Engineering Portfolio

| Area | Demonstrated here |
|---|---|
| Infrastructure as Code | Reusable Terraform modules, Azure foundations, AKS/EKS platforms and CloudFormation patterns |
| CI/CD | Terraform validation, planning, security/policy gates and post-deployment validation |
| Kubernetes | AKS and EKS infrastructure, Kubernetes workloads, autoscaling, ingress and release validation |
| Observability & SRE | Metrics, logs, traces, SLOs, error budgets, dashboards, alerting and incident runbooks across Azure and AWS |
| Policy as Code | OPA/Rego controls, policy tests, Terraform plan evaluation and Azure Policy |
| Python Automation | Terraform plan analysis, Kubernetes release validation and AWS multi-account resource inventory |
| Cloud Security | IAM/RBAC, managed identities, private connectivity, Key Vault and policy guardrails |
| Multi-cloud | Hands-on reference implementations spanning Azure and AWS with architecture experience across GCP and OCI |

## Featured Projects

### [Multi-Cloud Observability Platform](https://github.com/ugochuk/cloud-observability-platform)
Production-minded observability reference implementation for AKS and EKS. Uses Terraform and OpenTelemetry to connect application and Kubernetes telemetry with Azure Monitor, Application Insights, Log Analytics, Amazon CloudWatch, AWS X-Ray, managed Prometheus and managed Grafana. Includes SLOs, error budgets, alert rules, dashboards and evidence-driven incident runbooks.

**Technologies:** Azure • AWS • AKS • EKS • Terraform • OpenTelemetry • Prometheus • Grafana • Azure Monitor • Application Insights • Log Analytics • CloudWatch • X-Ray • SLOs • Alerting

### [AKS Platform with Terraform](https://github.com/ugochuk/aks-platform-terraform)
Production-minded AKS reference architecture with Terraform and Kubernetes manifests. Includes Python release-validation automation that evaluates desired, available, ready and updated replicas plus rollout health so CI/CD can fail fast when deployments are unhealthy.

**Technologies:** Terraform • AKS • Kubernetes • Python • kubectl • GitHub Actions • Azure

### [Azure Enterprise Landing Zone](https://github.com/ugochuk/azure-enterprise-landing-zone)
Reusable Terraform foundation for Azure networking, Key Vault, monitoring and governance. Also demonstrates Python automation for parsing Terraform plan JSON, classifying resource creates, updates, deletes and replacements, validating plan metadata and publishing CI artifacts.

**Technologies:** Terraform • Azure • Python • GitHub Actions • VNets • Key Vault • Azure Policy • Log Analytics

### [Azure Policy + OPA/Rego Governance](https://github.com/ugochuk/azure-policy-opa-governance)
Policy-as-Code implementation combining OPA/Rego pre-deployment controls with Azure Policy. Includes security policies, Rego tests, compliant/noncompliant Terraform examples, Terraform-plan evaluation patterns and automated CI policy gates.

**Technologies:** OPA • Rego • Azure Policy • Terraform • GitHub Actions • DevSecOps

### [Terraform CI/CD with GitHub Actions](https://github.com/ugochuk/terraform-cicd-github-actions)
Infrastructure delivery workflow demonstrating Terraform validation, planning, security scanning, Azure authentication, deployment controls and post-deployment verification.

**Technologies:** Terraform • GitHub Actions • CI/CD • Azure • TFLint • Trivy

## Resume-to-Code Map

| Professional capability | Portfolio evidence |
|---|---|
| Reusable Terraform infrastructure | `azure-enterprise-landing-zone/modules/`, `aks-platform-terraform/terraform/`, `cloud-observability-platform/terraform/` |
| Terraform plan automation with Python | `azure-enterprise-landing-zone/scripts/terraform_plan_summary.py` |
| Automated AKS release validation | `aks-platform-terraform/scripts/validate_aks_release.py` |
| Multi-cloud observability | `cloud-observability-platform/terraform/`, `kubernetes/`, `dashboards/`, `slos/` and `runbooks/` |
| AWS observability infrastructure | `cloud-observability-platform/terraform/aws/` |
| Azure observability infrastructure | `cloud-observability-platform/terraform/azure/` |
| Kubernetes workload configuration | `aks-platform-terraform/kubernetes/` |
| OPA/Rego policy as code | `azure-policy-opa-governance/policies/` and `tests/` |
| CI/CD automation | `.github/workflows/` across the portfolio |

## Technical Stack

**Cloud:** Microsoft Azure, AWS, GCP, OCI  
**Containers:** Kubernetes, AKS, EKS, Docker, Helm, kubectl  
**Infrastructure as Code:** Terraform, CloudFormation, ARM  
**Policy as Code:** OPA/Rego, Azure Policy  
**CI/CD:** Azure DevOps, GitHub Actions, YAML pipelines, Git  
**Automation:** Python, Boto3, Go, PowerShell, Azure CLI, REST APIs, JSON, YAML  
**Observability:** OpenTelemetry, Prometheus, Grafana, metrics, logs, traces, SLIs, SLOs, error budgets, alerting, dashboards, incident runbooks  
**Azure:** VNets, Private Endpoints, Private DNS, Key Vault, Managed Identities, RBAC, ACR, Azure Monitor, Application Insights, Log Analytics, App Service, Functions, Cosmos DB, Azure SQL, Storage  
**AWS:** EC2, VPC, subnets, security groups, IAM, EKS, ECR, CloudFormation, CloudWatch, X-Ray, Amazon Managed Prometheus, Amazon Managed Grafana, SNS, multi-account automation

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
