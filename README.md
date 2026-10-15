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

**Note:** This repository presents a design concept. The dashboard is not a live cloud security monitoring system.
