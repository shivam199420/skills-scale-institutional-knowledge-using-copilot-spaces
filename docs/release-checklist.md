# Release Checklist (lightweight)

Use this checklist before any production deployment. Tailor for major/minor/patch releases as needed.

Pre-release (staging)
- [ ] All PRs merged for this release
- [ ] CI green and security scans passed
- [ ] Migration steps documented (if any)
- [ ] Backups/snapshots created (if applicable)
- [ ] Release notes draft completed
- [ ] Instrumentation verified in staging (metrics, logs, traces)
- [ ] Smoke tests configured and passing in staging
- [ ] Support/Customer Success notified of upcoming release (if customer-impacting)

Release window (production)
- [ ] Deployment window scheduled and stakeholders informed
- [ ] Run deployment pipeline to production (automated where possible)
- [ ] Run smoke tests in production
- [ ] Monitor key dashboards / alerts for anomalies for the first 30–60 minutes
- [ ] Post-deploy verification checklist completed by Delivery Lead / SRE

Post-release
- [ ] Confirm no high-severity alerts or customer impact
- [ ] Update status in project board and release notes
- [ ] Capture any follow-up action items and assign owners
- [ ] Schedule retrospective if release had significant changes or incidents
