# Intune Endpoint Health Assessment Checklist

Use this as a discovery aid. Mark an item **In scope**, **Out of scope**, or **Not verified**; do not assume that a missing setting is automatically a defect. Capture the evidence location and review date, not sensitive values.

## 1. Scope and context

- [ ] Business units, platforms, device ownership, and approximate device counts agreed
- [ ] Assessment period, stakeholders, and written authorization recorded
- [ ] Intune, Entra ID, and related services in scope agreed
- [ ] Licensing and relevant operating requirements confirmed with the client
- [ ] Change activity excluded unless separately approved

## 2. Enrollment and inventory

- [ ] Enrollment methods and restrictions reviewed
- [ ] Enrollment experience and platform coverage reviewed
- [ ] Recent enrollment failures and trends reviewed
- [ ] Managed, stale, duplicate, and inactive device records reviewed
- [ ] Ownership and user affinity approach reviewed where applicable

## 3. Compliance and configuration

- [ ] Compliance policies reviewed by platform and assignment
- [ ] Noncompliant devices and grace-period behavior reviewed
- [ ] Configuration profiles, assignment scope, and conflicts reviewed
- [ ] Security baselines and overlapping settings reviewed
- [ ] Exceptions, exclusions, and break-glass handling documented

## 4. Applications and updates

- [ ] Required and available application assignments reviewed
- [ ] Install failures and supersedence/dependency issues reviewed
- [ ] App protection or managed application controls reviewed if in scope
- [ ] Windows update rings and feature/update policies reviewed if in scope
- [ ] macOS update controls reviewed if in scope

## 5. Endpoint security

- [ ] Endpoint security policies and assignment coverage reviewed
- [ ] Defender onboarding/health signals reviewed if licensed and in scope
- [ ] Disk encryption policy and reporting reviewed
- [ ] Firewall and endpoint protection posture reviewed
- [ ] Local administrator approach reviewed
- [ ] Remediation and detection scripts reviewed for ownership, scope, and reporting

## 6. Identity and access

- [ ] Entra device join and registration assumptions reviewed
- [ ] Conditional Access dependencies on device state reviewed with the identity owner
- [ ] MFA and emergency access considerations discussed with the client
- [ ] Any access policy gaps are described as observations, not changed during assessment

## 7. Operations and governance

- [ ] Role assignments and least-privilege approach reviewed
- [ ] Naming, ownership, and change documentation reviewed
- [ ] Monitoring, alerting, and recurring operational review discussed
- [ ] Support handoff and escalation path documented
- [ ] Risks, assumptions, exclusions, and evidence gaps recorded

## Finding record

For each finding, record:

- **ID and title:**
- **Area:**
- **Evidence reference and date:**
- **Observed condition:**
- **Potential impact:**
- **Severity:** Critical / High / Medium / Low / Informational
- **Recommendation:**
- **Effort and dependencies:**
- **Suggested owner and target timeframe:**
- **Validation method:**

Severity should reflect the client’s context and exposure. Explain the reasoning; avoid presenting a score as an objective guarantee.
