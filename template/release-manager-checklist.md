```markdown
# Release Manager Checklist (Template)

Purpose: Standardized checklist for Release Managers to validate release readiness and coordinate deployments.

Pre-release
- [ ] Release scope and changelog documented
- [ ] All PRs merged and linked to issues
- [ ] CI: all unit and integration tests passing
- [ ] Security scans completed (SAST/Dependency scanning)
- [ ] DB migration plan reviewed and rollback plan defined
- [ ] Release notes drafted and reviewed
- [ ] Stakeholders and support teams notified of release window
- [ ] Backup/snapshot plan (if applicable) prepared

Staging
- [ ] Deploy to staging environment
- [ ] Run smoke tests and validate key user flows
- [ ] Performance/latency checks for critical endpoints
- [ ] Verify monitoring, logging, and alerting are active

Production
- [ ] Confirm deployment window and on-call availability
- [ ] Perform production deployment (automated pipeline preferred)
- [ ] Run post-deploy verifications and smoke tests
- [ ] Monitor dashboards and alerts for 30–60 minutes (or defined window)
- [ ] Communicate release completion to stakeholders

Post-release
- [ ] Triage any incidents; trigger incident playbook if needed
- [ ] Capture action items and retrospective notes
- [ ] Confirm knowledge transfer to support team and update runbooks
```
