# Gerrard Lewu

**Cloud & DevOps Engineer · AWS · Terraform · Linux · CI/CD**

I'm an early-career engineer based in Cape Town, South Africa. I build secure cloud infrastructure, automate delivery workflows and develop applications, with production-facing experience as a Full Stack Engineer Intern at Studio Venturis.

I'm interested in junior and associate Cloud and DevOps opportunities where I can contribute to reliable delivery, troubleshooting and practical automation while learning from an experienced team.

[Portfolio](https://gerrardlewu.online/) · [LinkedIn](https://www.linkedin.com/in/gerrardlewu/) · [Email](mailto:gerrardlewu@gmail.com)

## Selected engineering work

### Secure AWS Infrastructure

A repeatable foundation for a small cloud workload, defined in Terraform. I built private EC2 compute with Systems Manager access, controlled outbound connectivity, encrypted and versioned S3 storage, and protected remote Terraform state.

The deployment record documents validation of those controls. The architecture notes explain the cost and availability trade-offs, including a single NAT Gateway and a workload that is not highly available.

**Tools:** AWS, Terraform, Linux, VPC, EC2, IAM, S3, Systems Manager.

[Repository](https://github.com/Gerrard-Lewu/aws-01-secure-infrastructure) · [Deployment evidence](https://github.com/Gerrard-Lewu/aws-01-secure-infrastructure/blob/main/docs/evidence/2026-07-25-core-deployment.md)

### AWS Cloud Resume

My portfolio doubles as a cloud delivery project: CloudFront serves the site from a private S3 origin, with a Lambda Function URL and DynamoDB supporting its visitor counter.

I configured GitHub Actions to deploy the site and invalidate the CloudFront cache. The workflow uses OIDC role assumption for short-lived AWS access. Troubleshooting the IAM trust policy taught me to inspect identity claims rather than guess at deployment failures.

**Tools:** S3, CloudFront, Lambda, DynamoDB, GitHub Actions, OIDC.

[Live portfolio](https://gerrardlewu.online/) · [Deployment workflow](https://github.com/Gerrard-Lewu/aws-cloud-resume/blob/main/.github/workflows/deploy-frontend.yml)

### Reachwick

A self-hosted workspace for managing leads, campaign drafts, sequences and schedules. I developed the application with owner authentication, SQLite persistence, suppression lists and backup/restore workflows.

The published v0.1.0 release includes an SBOM and checksums. Lead and campaign planning are implemented; email delivery, mailbox sync and team accounts remain planned.

**Tools:** React, TypeScript, Fastify, SQLite.

[Repository](https://github.com/Gerrard-Lewu/reachwick) · [Release and artifacts](https://github.com/Gerrard-Lewu/reachwick/releases/tag/v0.1.0)

### Dynamic Solvents

A freight company website and private operations workspace. I contributed end-to-end design and full-stack development around connected freight jobs, movements, assignments and documents, with scoped staff and client views.

The goal is clearer ownership and handovers, with staff and clients working from information relevant to their role instead of scattered spreadsheets and message threads.

[Public project summary](https://gerrardlewu.online/#work) · [Company website](https://dynamicsolvents.co.za/)

## Professional experience

**Full Stack Engineer Intern — Studio Venturis · June 2026–present**

I contribute to application and integration work, investigate defects, and support testing, deployments and post-release verification. GitHub workflows, technical documentation and issue follow-through help me communicate changes and outstanding problems with engineers and stakeholders.

## Working toolkit and credentials

- **Infrastructure:** AWS, Terraform, Linux, IAM and cloud networking; Azure through project and internship work.
- **Delivery and containers:** Git, GitHub Actions, Docker; Kubernetes and Helm in portfolio projects.
- **Programming and data:** Python, Bash, TypeScript, Java, C#/.NET, SQL and REST APIs.

**Certifications:** AWS Certified Solutions Architect – Associate · Microsoft Certified: Azure Administrator Associate.

Also: AWS Certified Cloud Practitioner · Azure Fundamentals · OCI Foundations Associate.

## Current focus

I'm planning [AWS monitoring and operational automation](https://github.com/Gerrard-Lewu/aws-02-automated-monitoring), covering metrics, logs, dashboards and alerts for the infrastructure foundation. Implementation and deployment remain ahead.

I use ChatGPT and Codex to support research and development, alongside source inspection, review, testing and verification of the resulting work.
