# AvatarSpeak Multilingual Translation Service

AvatarSpeak was a University of Queensland DECO3801 capstone project: a multilingual speech-translation workflow connected to a lip-synced digital human.

## Candidate-owned module

- FastAPI service connecting NLLB-200 machine translation and XTTS v2 speech synthesis.
- Four API contracts, six bidirectional language routes and 16 kHz mono PCM-16 audio/base64 output.
- Error separation, readiness checks and partial-success behavior so an audio failure could preserve the translated text.

## Validation

- **64/64** real requests completed.
- **12/12** bidirectional routes and 15 contract regression checks passed.
- The capstone received the highest project score in its topic group; the external industry mentor requested the project code after completion.

## Public source

[github.com/Filberte/avatarspeak-translation-service](https://github.com/Filberte/avatarspeak-translation-service)

The public repository contains only the translation-service module authored by the candidate and preserves the boundary with the wider team project.

