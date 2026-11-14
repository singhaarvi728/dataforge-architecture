# ADR 002: Separate raw, standardised, and curated zones

- **Status:** Proposed
- **Decision:** Use distinct S3 prefixes for raw, silver, and gold data.
- **Context:** Separating ingestion from transformation and business-facing datasets improves lineage, replayability, and access governance.
- **Consequences:** More lifecycle and access policies to manage; promotion between zones needs validation and metadata tracking.
- **Revisit when:** Data volume, domain boundaries, or governance requirements justify a different layout.
