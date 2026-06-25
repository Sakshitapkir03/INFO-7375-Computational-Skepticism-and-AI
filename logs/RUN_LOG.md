# RUN_LOG.md

Date: 2026-06-24

## What was built

Built the personal search data layer for the Reallocation Engine:

- search/resume.json
- search/profile.yml
- search/gaps.md
- search/private-notes.md added locally and excluded from git
- AI_USE_DISCLOSURE.md

## Three attestation errors corrected in resume.json

1. Normalized inconsistent date formats across education, work experience, certification, and project records.
2. Removed unsupported inferred leadership language so the record stays limited to evidence from the resume.
3. Kept STEM eligibility out of resume.json because it belongs in profile.yml and should remain uncertain until verified with DSO records.

## Top gap from gaps.md

The top gap is distributed systems and asynchronous backend design. I have backend API and full-stack evidence, but I need stronger public evidence of queue-based processing, worker services, failure handling, and scalable backend architecture.

## Row killed and why

Killed row: Machine learning model training from scratch.

Reason: This gap does not match my target role. I am targeting backend, full-stack, and AI application engineering roles, not research ML roles focused on training models from scratch.

## Field corrected in profile.yml

The STEM eligibility field was corrected to:

stem_eligible: "uncertain"

This avoids treating STEM eligibility as confirmed before DSO verification.

The unemployment days field was intentionally left unset because I could not verify the exact value from my official records at the time of attestation.

## Verification check

### resume.json

Every job, project, degree, skill, and certification entry is structured and traceable to the resume or a verifiable project/work record. The structured record was reviewed to ensure that experience, dates, skills, and responsibilities remained supported by the resume and verifiable evidence.

### profile.yml

Visa constraints reflect current F-1 OPT context, the authorization end date, uncertain STEM eligibility, and future sponsorship requirement. Unemployment days were not guessed.

### gaps.md

Every gap is tied to evidence from O*NET, BLS, an example job posting pattern, or the sponsorship gate defined in profile.yml. Plans describe evidence-producing outputs such as deployed projects, documented architecture, tests, CI, and screening checklists.
