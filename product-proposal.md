# CloudGuard — Product Proposal

## 1. Problem Statement

Security engineers managing multiple cloud accounts need a centralized way to identify, prioritize, and track cloud misconfigurations. Without clear prioritization and remediation guidance, identifying and resolving high-risk findings can take unnecessary time.

## 2. Target User

**Cloud Security Engineer**

A technical user responsible for monitoring cloud configurations, investigating security findings, and coordinating remediation across multiple cloud accounts.

**Primary need:** Quickly identify urgent risks, understand their impact, and track remediation.

## 3. Proposed Solution

The MVP includes three connected screens:

- **Security Overview:** Summarizes open findings, critical and high-severity risks, and connected cloud accounts.
- **Findings:** Supports search and filtering by severity, cloud provider, account, and status.
- **Finding Details:** Shows the potential impact, affected resource, recommended remediation, and status actions.

## 4. Feature Prioritization

**P0 — MVP**
- Centralized findings list and severity indicators.
- Search and essential filters.
- Finding details with remediation guidance.
- Remediation status tracking and confirmation before resolution.

**P1 — Future Iteration**
- Finding ownership and assignment.
- Bulk actions and saved filters.
- Historical trends and remediation reporting.

The MVP focuses on the core workflow: identify, investigate, and track a finding.

## 5. Success Metrics

- Median time to identify a critical finding.
- Median time from discovery to verified remediation.
- Percentage of high-priority findings resolved within the agreed SLA.
- Task completion rate during usability testing.

Baselines and targets should be established after initial user research.

## 6. Development Action Items

- **Backend:** Define data models and APIs for findings, accounts, severity, and remediation status.
- **Cloud integrations:** Normalize findings from supported cloud providers.
- **Frontend:** Implement search, filters, pagination, detail views, and loading/error/empty states.
- **Security and QA:** Enforce role-based access, audit status changes, and test key workflows.

## Assumptions to Validate

Validate with security engineers whether severity-based prioritization, multi-account visibility, and remediation guidance address their main workflow challenges.

**Scope:** This is a product design concept, not a live cloud security monitoring system.
