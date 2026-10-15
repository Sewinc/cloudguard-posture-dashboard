# Development Action Items

## 1. Backend and API
- Define data models for findings, cloud accounts, affected resources, severity, and remediation status.
- Create APIs to retrieve findings and finding details.
- Support filtering by severity, cloud provider, account, and status.
- Add pagination and consistent error responses.

## 2. Frontend
- Implement the Security Overview, Findings, and Finding Details screens.
- Build search, filters, sorting, and pagination.
- Add loading, empty, and error states.
- Implement the confirmation step before a finding is marked as resolved.

## 3. Cloud Integrations
- Define a normalized finding format across supported cloud providers.
- Display the source provider and affected account for each finding.
- Validate how finding severity and status are mapped between integrations.

## 4. Security and Auditability
- Enforce role-based access to findings and remediation actions.
- Record status changes with the actor and timestamp.
- Ensure users can only access resources permitted by their role.

## 5. QA and Validation
- Test filtering and search across different cloud providers.
- Verify severity labels and finding details remain consistent across screens.
- Test loading, empty, error, and permission-denied states.
- Validate the prototype workflow with representative security engineers.

## Definition of Done
- Users can find and filter security findings.
- Users can open a finding and understand its potential impact and recommended remediation.
- Status changes provide clear feedback and are auditable.
- Core workflows pass functional and usability testing.

**Note:** These are proposed development actions for a product concept. Technical implementation details should be validated with engineering and security stakeholders.
