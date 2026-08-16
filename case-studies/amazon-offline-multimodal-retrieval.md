# Offline Multimodal Retrieval

[Public source and evaluation evidence](https://github.com/Filberte/offline-multimodal-retrieval)

> Sanitized internship case study. No employer code or internal documents are included.

## Problem

Design a Windows retrieval product for privacy-sensitive, network-restricted and accessibility-oriented users who need to recover forgotten local content without uploading files or opening a network port.

## Product decisions

- Converted the requirement into a verifiable local-retrieval task and defined the PRD/MVP, eight-week roadmap and acceptance gates.
- Prioritized TXT/PDF/DOCX/JPG/PNG parsing and local text-image retrieval; excluded cloud synchronization and online OCR from the MVP.
- Connected Python and Flutter through JSON Lines to keep the application local and auditable.

## Evaluation

- Engineering text-query set: Recall@5 **90%**, MRR@10 **0.860**.
- Final real-model path validated text and image retrieval across retained local test files and preset queries.
- Regression baseline: **600/600** cases passed; release blocker count was **0**.

## Scope boundary

The portfolio records product logic, architecture and evaluation methodology only. Source code, employer requirement documents, releases, datasets, model caches and evidence archives remain private.
