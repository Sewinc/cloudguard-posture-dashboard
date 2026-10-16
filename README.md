# CloudGuard — Cloud Posture Dashboard

A UX/Product Management assignment focused on helping cloud security engineers identify, prioritize, and track cloud misconfigurations across multiple cloud accounts.

## Problem

Security engineers managing multiple cloud environments need a centralized view of security findings. Without clear prioritization, filtering, and remediation guidance, identifying and resolving high-risk misconfigurations can take unnecessary time.

## Target User

**Cloud Security Engineer**

A technical user responsible for monitoring cloud configurations, investigating security findings, and coordinating remediation across cloud accounts.

## Proposed Solution

This concept includes three core screens:

1. **Security Overview** — summarizes open findings, critical and high-severity risks, and connected cloud accounts.
2. **Findings** — enables users to search and filter findings by severity, cloud provider, account, and status.
3. **Finding Details** — explains the potential impact, identifies the affected resource, and provides remediation guidance and status actions.

## Key Design Decisions

- Surface high-priority findings to support faster risk assessment.
- Provide focused filters to narrow findings across providers and accounts.
- Include remediation guidance alongside affected resource details.
- Add a confirmation step before marking a finding as resolved.

## Success Metrics

- Median time to identify a critical finding.
- Median time from discovery to verified remediation.
- Percentage of high-priority findings resolved within the agreed SLA.
- Task completion rate in usability testing.

Targets should be defined after establishing a baseline.

## Deliverables

- Three-screen Figma wireframe and prototype.
- Product rationale and prioritization.
- Development action items.

## Design Deliverables

- **Figma Prototype:** https://www.figma.com/proto/71yoBgoENtDZPO99VMdwfX/Cloud-Posture-Dashboard_Product-Mgmt-Trainee-Problem-Statement?node-id=3065-5029&t=uaW0IGKXWyuOJuoD-1&scaling=min-zoom&content-scaling=fixed&page-id=0%3A1&starting-point-node-id=3065%3A5029
- **Figma Design File:** https://www.figma.com/design/71yoBgoENtDZPO99VMdwfX/Cloud-Posture-Dashboard_Product-Mgmt-Trainee-Problem-Statement?node-id=3109-412&t=Sv4xO7pYnrhZepCD-1
- **Wireframe Exports:** See the [`wireframes/`](./wireframes/) directory.
- **Assignment Walkthrough Video:** https://drive.google.com/file/d/1u9BJWE1us3kuLtyCmyLkc4YcoptRJTIJ/view?usp=sharing

The prototype demonstrates the core flow from the security overview to findings and finding details, including the remediation confirmation step.

**Note:** This repository presents a design concept. The dashboard is not a live cloud security monitoring system.
