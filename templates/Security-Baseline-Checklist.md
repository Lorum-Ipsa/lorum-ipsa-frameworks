# Security Baseline Checklist  
Lorum Ipsa – Public Framework Reference

---

## Purpose

This checklist defines minimum structural security expectations for a managed digital publishing environment.

It establishes:

- Baseline hardening standards  
- Access control discipline  
- Monitoring expectations  
- Update governance  
- Documentation requirements  

This checklist is framework-level and does not replace formal audits or regulatory compliance.

---

## 1. Infrastructure Ownership & Control

- [ ] Domain ownership verified  
- [ ] Registrar access documented  
- [ ] Hosting provider identified  
- [ ] Infrastructure portability confirmed  
- [ ] Content export feasibility validated  

Dependency without transferability increases systemic risk.

---

## 2. Access Control Baseline

- [ ] Administrative roles explicitly defined  
- [ ] Role-based access control applied  
- [ ] Least-privilege principle enforced  
- [ ] Shared credentials eliminated  
- [ ] Multi-factor authentication enabled (where supported)  
- [ ] Access inventory documented  
- [ ] Periodic access review schedule defined  

Unrestricted administrative access violates baseline discipline.

---

## 3. Authentication & Credential Governance

- [ ] Strong password policy enforced  
- [ ] Credential storage method defined  
- [ ] Secure exchange procedures used  
- [ ] Default credentials removed  
- [ ] Inactive accounts disabled  

Credentials represent a primary attack surface.

---

## 4. Configuration Hardening

- [ ] Default services reviewed  
- [ ] Unused services disabled  
- [ ] Administrative interfaces restricted  
- [ ] Debug modes disabled in production  
- [ ] Error disclosure minimized  
- [ ] Public file permissions reviewed  

Production systems must operate in restrictive mode.

---

## 5. Monitoring & Logging

- [ ] Administrative activity logging enabled  
- [ ] Authentication events recorded  
- [ ] System change events tracked  
- [ ] Log retention expectations defined  
- [ ] Monitoring responsibility assigned  

Visibility is a security control.

---

## 6. Update & Patch Governance

- [ ] Update cadence defined  
- [ ] Major upgrades evaluated before deployment  
- [ ] Dependency review performed  
- [ ] Post-update verification procedure defined  
- [ ] Rollback feasibility considered  

Uncontrolled updates create instability.

---

## 7. Backup & Recovery Posture

- [ ] Backup frequency defined  
- [ ] Backup storage location identified  
- [ ] Restoration feasibility validated  
- [ ] Recovery responsibility assigned  
- [ ] Backup integrity periodically tested  

Backup without restoration testing is incomplete.

---

## 8. Data Handling Awareness

- [ ] Data sensitivity categories defined  
- [ ] Data minimization principle applied  
- [ ] Third-party integrations reviewed  
- [ ] Retention expectations documented  

Minimizing unnecessary exposure reduces risk surface.

---

## 9. Change Management Baseline

- [ ] Change documentation process defined  
- [ ] Configuration changes logged  
- [ ] Role authority for changes defined  
- [ ] Client notification thresholds clarified  

Untracked changes introduce hidden fragility.

---

## 10. Integration Risk Separation

- [ ] External integrations reviewed  
- [ ] API keys scoped appropriately  
- [ ] Economic/token systems isolated (if applicable)  
- [ ] No custodial private key storage on publishing infrastructure  

Risk domains must remain separated.

---

## 11. Documentation & Records

- [ ] System configuration documented  
- [ ] Access inventory current  
- [ ] Risk register updated  
- [ ] Review cadence scheduled  
- [ ] Escalation pathway defined  

Documentation is treated as a security control.

---

## Non-Compliance Indicators

A system fails baseline security expectations if:

- Administrative access is undocumented  
- Updates occur without governance  
- No logging visibility exists  
- Backups are untested  
- Integration boundaries are undefined  

---

## Review Cadence

Recommended baseline reassessment:

- Quarterly for stable environments  
- After major system change  
- Following security incident  
- Upon new integration  

Security posture must be continuously validated.

---

## Closing Principle

Security is not an add-on.

Security is structural discipline applied consistently.

Baseline standards prevent avoidable fragility.  
Documentation prevents silent drift.  
Stability precedes expansion.

Durability is the objective.
