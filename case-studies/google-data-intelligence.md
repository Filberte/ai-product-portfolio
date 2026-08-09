# Cross-platform Data Intelligence

> Sanitized internship case study. Raw platform data, account state and collection scripts are not published.

## Problem

Create a reproducible public-content research pipeline for international-logistics research while controlling duplicate records, identity boundaries and downstream account or brand risk.

## Product decisions

- Defined keyword discovery, detail/comment parsing, structured schema, GraphQL log analysis and DOM fallback as one data-product chain.
- Treated completeness, deduplication and identity boundaries as quality gates rather than cleanup after ingestion.
- Generated 30 controlled candidate records for human review and kept outbound sending disabled by default.

## Evaluation

- Reviewed **804** public comments.
- Identified a **32.46%** raw duplicate rate and **99.75%** required-field completeness.
- For a separate quantitative research track, processed **282,779** records and designed **48** parameter simulations with T-1 constraints and explicit simulation/live boundaries.

## Public artifact

The candidate-owned quantitative implementations are available in [quant-strategies](https://github.com/Filberte/quant-strategies). The repository retains original and fixed versions so look-ahead-risk corrections remain auditable.

