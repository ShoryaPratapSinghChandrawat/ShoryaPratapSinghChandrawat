# GitHub profile review and maintenance guide

This guide explains how the profile is positioned, what it demonstrates today,
and what needs stronger evidence before presenting it as a cybersecurity or
ethical-hacking portfolio.

## Current positioning

**Primary profile:** first-year B.Tech CSE (AI/ML) student building applied
AI/ML and full-stack software.

**Secondary evidence:** secure application engineering practices in Doorway
Relay and MerchantShield AI, plus a reproducible audio-spoofing detection
research project in AudioGuard.

This is not yet a specialist penetration-testing, exploit-development, or
vulnerability-research portfolio. Do not claim professional ethical-hacking
experience on the basis of the current repositories.

## Featured repository order

Recommended profile pins (set them manually in GitHub profile settings):

1. `MerchantShield-AI` — most extensive applied-AI/full-stack product prototype.
2. `doorway-relay` — strongest visible secure application engineering evidence.
3. `audioguard-deepfake-audio-detection` — reproducible ML research and error analysis.
4. `qff2026-phase1-s1-ising_chain` — team simulation research with exact-reference checks.
5. `FlipTrace-Decision-Reversal-Detection-Analytics-Platform` — browser systems and data processing.
6. `Projects` — curated index for learning and creative builds.

The exact profile-pinning and bio changes are not applied by this GitHub repository connector; they require the GitHub profile settings UI.

For a dedicated cybersecurity internship application, reorder the first three
only after you publish a focused security lab/tool with reproducible evidence.

## What the public work supports

| Repository | Defensible evidence | Do not claim |
| --- | --- | --- |
| MerchantShield AI | FastAPI/React system; provenance labels; explicit Sandbox boundaries; human-approved actions; 215-test historical baseline; two later safety regression tests added but not yet verified | Production payment software, live PayPal verification, live Gemini verification, actual dispute submission, measured merchant outcomes |
| Doorway Relay | Auth/session handling, CSRF protection, rate limiting, migrations, synthetic event handling, secret-handling guidance, automated local tests | Ring-verified integration, live WHEP behavior, production-ready service |
| AudioGuard | ASVspoof 2019 LA research experiments; SVM/CNN comparison; EER/AUC metrics; error and robustness analysis | Universal deepfake detection, real-world product accuracy, full-dataset robustness from the fixed subset |
| QFF 2026 | Team simulation work; VQE experiments; exact-reference checks; processor/noise analysis | Quantum hardware execution or quantum advantage |
| FlipTrace | Browser-only decision-history processing; Web Workers; IndexedDB; local analysis | Validated psychological/personality inference or backend SaaS |
| Projects | Coursework, mini-projects, creative builds | Production maturity for every folder |

## Public profile improvements completed

- Focused the profile summary on applied AI/ML, full-stack engineering and
  secure application design.
- Added explicit security-related project evidence without claiming
  professional penetration-testing experience.
- Removed an unverified Doorway Relay deployment badge.
- Linked Doorway Relay's contributor guidance.
- Updated the MerchantShield test count to distinguish the historical 215-test
  run from two new regression tests awaiting a verified execution.
- Clarified that QFF 2026 is a team project.
- Clarified AudioGuard's unpublished demo-video status and the limited nature of
  its two manual demo smoke tests.
- Updated the Projects index to surface concrete Doorway Relay security controls.

## Remaining manual GitHub settings

The GitHub connector used for this audit can read and update repository files,
but it cannot change account-level profile settings or repository pins.

- Set the recommended pinned repository order above.
- Set the profile bio to a concise, role-aligned and truthful statement, for
  example:

  `B.Tech CSE (AI/ML) | Applied AI/ML • Full-stack • Secure application engineering`

- Keep your LinkedIn headline and About section consistent with your current
  education and demonstrable projects.

## Highest-value next evidence for cybersecurity roles

1. Build a small, intentionally vulnerable local lab (Docker/VM only) and write
   a threat model, attack narrative, remediation, and retest report.
2. Publish a defensive tool with tests and safe-by-default behavior, such as a
   dependency/configuration audit helper or HTTP security-header checker.
3. Complete a few well-documented CTF/lab challenges and publish writeups that
   explain the vulnerability class, root cause, impact, remediation and
   verification. Do not publish real target details or weaponised instructions.
4. Make one or two meaningful external contributions to established
   security-focused projects. Seek maintainer review; do not create self-merged
   PRs and present them as independent endorsements.
5. Add a threat model and security review to Doorway Relay and MerchantShield.
   Separate implemented controls from tests, assumptions and unverified
   provider behavior.

## Review standard

A strong profile is a curated, verifiable sample of work, not a guaranteed
score. Stars, follower count, badges, graphics and keyword density are not a
substitute for code quality, technical explanation, responsible testing,
collaboration, and evidence of real use.
