# DataForge: AWS Data Lakehouse Architecture

A portfolio case study documenting a proposed AWS-based data lakehouse architecture, including ingestion, storage zones, transformation, governance, analytics, and operational considerations.

> **Contribution transparency:** My contribution to the original DataForge project was documentation. This repository is an architecture/documentation showcase; it does not claim that I implemented or deployed the AWS infrastructure.

## Contents
- Architecture overview and Mermaid diagram
- Data lifecycle and storage-zone conventions
- Service selection rationale
- Security, governance, and observability considerations
- Example infrastructure checklist and cost assumptions
- Architecture decision records

## Architecture at a glance
The proposed design uses Amazon S3 as the durable storage layer, AWS Glue for cataloguing and ETL orchestration, and Athena for serverless SQL analytics. Event-driven ingestion and access controls are described as design choices, not deployed resources.

See [docs/architecture.md](docs/architecture.md).

## Status
Design documentation only. No AWS account, deployed resources, credentials, or live pipeline are included.
