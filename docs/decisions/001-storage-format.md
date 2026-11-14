# ADR 001: Columnar format for curated analytics

- **Status:** Proposed
- **Decision:** Prefer Apache Parquet with compression for curated analytical tables.
- **Context:** The target workload is SQL analytics over object storage. Columnar layouts can reduce bytes scanned when queries project a subset of columns.
- **Consequences:** Requires schema discipline and compatible readers. Small-file compaction and partition design must be considered. Raw source payloads may remain in their original format for replay.
- **Revisit when:** Consumers or source formats require a different interoperability or latency profile.
