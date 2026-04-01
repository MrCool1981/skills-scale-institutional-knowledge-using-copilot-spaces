# OctoAcme — Role-aware Release Checklist

This checklist maps release responsibilities to role owners. Use it for Minor/Major releases; adapt for Patch releases.

## Pre-release (owner in parentheses)
- [ ] Release window scheduled and communicated (Release Manager)
- [ ] Release scope confirmed and approved by PdM (PdM)
- [ ] All PRs merged and feature flags configured as needed (Developers)
- [ ] CI passes and security scans completed (Developers / Platform)
- [ ] Regression suite run and green (QA Automation / QA)
- [ ] Release notes drafted and reviewed (Technical Writer)
- [ ] Support playbook and escalation path prepared (Customer Support Liaison)
- [ ] Rollback / mitigation plan documented (Release Manager / Platform)

## Deployment (owner in parentheses)
- [ ] Run deployment to staging and execute smoke tests (Release Manager / Platform / QA)
- [ ] Run migrations and DB checks if applicable (Developers / Platform)
- [ ] Deploy to production (automated pipeline preferred) (Platform / Release Manager)
- [ ] Execute post-deploy verification checklist (QA / Developers)
- [ ] Announce release to stakeholders and support channels (Release Manager / Technical Writer)

## Post-release (owner in parentheses)
- [ ] Monitor key metrics and alerts for 1–24 hours (Platform / Developers)
- [ ] Triage and document any customer issues (Customer Support Liaison)
- [ ] Update public release notes and KB (Technical Writer)
- [ ] Run a short post-release retro if incidents occurred (Release Manager / PM)
- [ ] Close release ticket and capture learnings (PM / Release Manager)

## Rollback decision tree (simplified)
- Is there a critical customer-impacting failure?
  - Yes → Trigger rollback plan and notify stakeholders (Release Manager)
  - No → Triage hotfix with Developers and monitor
- If rollback is performed:
  - Execute automated rollback (Platform) or manual revert (Developers)
  - Verify health, communicate status, and run a blameless postmortem (PM / Release Manager)

## Notes
- Update this checklist per release type; for emergency patches follow the incident playbook.
- Use the Risk Register to record release-specific risks and owners.
