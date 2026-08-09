# Guangzhe Zhu — AI Product Portfolio

面向 AI 产品经理岗位的脱敏作品集，聚焦 **AI 应用评测、Agent / 多模态产品、数据闭环与 Human-in-the-loop**。

This portfolio presents sanitized product case studies and candidate-owned public code. It does **not** contain employer source code, internal requirement documents, private communications, credentials, raw user data, medical images, or model weights.

## Selected work

| Case | Product focus | Evidence highlights | Public artifact |
|---|---|---|---|
| [Offline Multimodal Retrieval](case-studies/amazon-offline-multimodal-retrieval.md) | Privacy-first local retrieval, MVP and acceptance gates | Recall@5 90%, MRR@10 0.860, 600 regression cases | Sanitized case study |
| [Cross-platform Data Intelligence](case-studies/google-data-intelligence.md) | Data quality, controlled inputs, reproducible research | 804-record review, 32.46% duplicate rate, 99.75% required-field completeness | Case study + [quant code](https://github.com/Filberte/quant-strategies) |
| [Vision AI Evaluation](case-studies/microsoft-vision-ai-evaluation.md) | Model selection, structured output and segmentation evaluation | 385-image clean holdout, 100% structured-output compliance | Sanitized case study |
| [Medical AI Evaluation](case-studies/medical-ai-evaluation.md) | Leakage audit, patient-level split and risk-oriented HITL | 2,006-image audit, 97.7% legacy test leakage | Sanitized case study |
| [Account Entry & Recovery](case-studies/bytedance-account-entry.md) | PRD, abnormal flows, acceptance and AI-assisted recovery | 24 reviewable requirements, 36 GWT acceptance cases | Sanitized case study |
| [Long-form Novel Agent](case-studies/long-form-novel-agent.md) | Long-context consistency, human review and Evaluation | 156 chapters, fixed synthetic QA F1 0.840 → 0.979 | Sanitized case study |
| [Multimodal Content Workflow](case-studies/multimodal-content-workflow.md) | Scope control, multi-model orchestration and media QC | 2-minute master, A/V drift 7.637 s → 0.098 s | Sanitized case study |
| [AvatarSpeak](case-studies/avatarspeak.md) | Multilingual MT + TTS contract for a digital-human workflow | 64/64 requests, 12/12 routes | [Public source](https://github.com/Filberte/avatarspeak-translation-service) |

## How to read the portfolio

Each case separates:

1. the product problem and target users;
2. decisions and scope trade-offs;
3. Evaluation design and acceptance evidence;
4. limitations and ownership boundaries.

Metrics are reported only when backed by retained local evidence. Post-internship reproduction or enhancement is explicitly separated from internship-period delivery.

## Public repositories

- [AvatarSpeak Translation Service](https://github.com/Filberte/avatarspeak-translation-service)
- [Quant Strategies](https://github.com/Filberte/quant-strategies)

## Disclosure

Company names describe the context in which the work was performed and do not imply endorsement. This repository contains only sanitized, candidate-authored summaries or separately licensed public code. No confidential or personally identifiable material is included.

