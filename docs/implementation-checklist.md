# Implementation Readiness Checklist

This checklist is a planning aid, not evidence of deployment.

## Discovery
- [ ] Inventory source systems, owners, formats, and update frequency.
- [ ] Define data classification, residency, retention, and deletion requirements.
- [ ] Estimate daily volume, growth, latency, and concurrency.
- [ ] Define consumers and measurable data-quality expectations.

## Platform
- [ ] Define account/environment boundaries and network controls.
- [ ] Create private S3 buckets and lifecycle policies.
- [ ] Define IAM roles and KMS key policies.
- [ ] Configure catalog, ETL orchestration, and query workgroups.
- [ ] Add infrastructure as code and peer review.

## Reliability
- [ ] Implement schema validation and quarantine paths.
- [ ] Add idempotency, retries, and replay procedures.
- [ ] Instrument logs, metrics, dashboards, and alarms.
- [ ] Define backup, recovery, and incident runbooks.

## Cost and governance
- [ ] Set budgets and alerts.
- [ ] Enable query limits and monitor scanned bytes.
- [ ] Review access by data classification.
- [ ] Document lineage, ownership, and retention.
