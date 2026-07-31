# Contributing to the Unified Update Experience Framework

Thank you for your interest in contributing to the Unified Update Experience Framework for the Android Ecosystem. This document explains how to contribute in ways that maintain the project’s research integrity, product-focus, and long-term stewardship.

Table of contents

- Principles
- Ways to contribute
- Filing issues
- Submitting pull requests
- Research contributions and data handling
- Reproducibility and documentation requirements
- Coding, style, and small scripts
- Review and merge process
- Security, sensitive information, and reporting
- Recognition and citation
- Contact

Principles

- Research-first: contributions should support reproducible research, clear provenance, and transparent methodology.
- Evidence-based: proposals that assert findings should include methods, data provenance, and references or be clearly labeled as design proposals or speculation.
- Privacy- and ethics-aware: do not add personally identifiable data or confidential materials to the public repository.
- Product & UX focus: prioritize clarity, user-centered rationale, and trade-offs relevant to product teams and stakeholders.

Ways to contribute

- File issues to report problems, propose features, or suggest research directions.
- Submit pull requests that add or improve documentation, methods, templates, diagrams, or non-proprietary analysis artifacts.
- Propose reproducible study protocols, pre-registrations, and evaluation templates.
- Provide literature references, curated resources, or constructive reviews of existing materials.

Filing issues

- Use issues to describe a single, actionable request: a bug in documentation, a missing reference, a research question, or a proposal for new work.
- Include a clear title, reproducible steps (for bugs), and an explanation of why the change matters.
- Label suggestions: (maintainers will apply labels) 'bug', 'documentation', 'proposal', 'research', 'ethics', 'enhancement'.
- For sensitive topics (security, privacy), follow the Security section below rather than posting details publicly.

Submitting pull requests (PRs)

- Fork the repository and create a branch in the fork for your changes. Use a descriptive branch name (e.g., docs/literature-review, research/protocol-device-update-survey).
- Make small, focused PRs when possible — each PR should address one logical change.
- Include a clear PR description that summarizes:
  - What the change is and why it’s needed.
  - Any supporting evidence, references, or links to discussion issues.
  - If applicable, a reproducibility checklist that documents how changes were generated (scripts, data sources, commands).
- Where a PR introduces new research artifacts (protocols, analysis), add a short `README.md` in the relevant directory that documents provenance and usage.
- Avoid adding raw or proprietary data. Instead, include sample sanitized extracts or instructions for obtaining and preparing permitted datasets.

Required contents for research-oriented PRs

When a PR adds research artifacts (analysis, evaluation, or experimental methods), include all of the following unless explicitly not applicable:

- A plain-language summary describing the artifact and its purpose.
- A reproducibility checklist or README that documents the steps to reproduce figures/tables (include commands, software versions, and data sources).
- A clear data provenance statement: what data was used, how it was obtained, any licensing constraints, and whether it is included or externally referenced.
- Licensing and attribution information for any third-party materials.
- Any ethical approvals or IRB references if human-subject data was used (sanitized public outputs only; raw data must not be committed).

Reproducibility and documentation requirements

- Prefer human-readable, machine-actionable documentation (README.md, CITATION.cff, and lightweight scripts) over opaque binary files.
- Where analysis is included, prefer notebooks or scripts with pinned dependency versions and a short environment setup section.
- Keep large or restricted datasets out of the repository. Use external links, data access instructions, or dataset manifests.

Coding, style, and small scripts

- This repository is primarily documentation- and research-focused. When code is included it should be:
  - Small, well-documented utilities or analysis scripts intended to reproduce figures or process public data.
  - Accompanied by usage instructions and a short example.
  - Licensed and attributed explicitly.
- Preferred languages for analysis: Python (notebooks, scripts). If you add language-specific files, include a README explaining the runtime and dependencies.
- Formatting and linting: keep scripts simple. Maintain consistent formatting and include a brief note of the expected interpreter or runtime.

Review and merge process

- Maintainer: ALi8744 (Ali Nasser Al‑Essa) is the primary repository maintainer and will review contributions.
- PR reviews: maintainers will review PRs for clarity, reproducibility, and compliance with repository policies. Reviews may request edits or clarification.
- Merging: maintainers may merge PRs after at least one approval and when all CI checks (if present) pass.

Security, sensitive information, and reporting

- Do not include secrets, credentials, or PII in issues, PRs, or commits.
- If you discover a security vulnerability or sensitive data exposure, do not post it publicly. Contact the maintainer by opening an issue labeled 'security' with minimal details, or use the repository's security notification mechanism if available. If you need to share sensitive files, request a secure channel from the maintainer.

Recognition and citation

- Contributors will be acknowledged in relevant documents (e.g., README/AUTHORS) with their GitHub username and preferred name if they opt in.
- If you contribute research artifacts that are used in publications or reports, the repository maintainer will coordinate citation and acknowledgement.
- For reproducible artifacts, add a CITATION.cff or a short citation file in the artifact’s directory where appropriate.

Privacy, ethics, and data handling

- Never commit raw interview transcripts, recordings, or PII to this public repository.
- When proposing studies involving human subjects, include an ethics statement and IRB or equivalent approval details in the methods README; do not include raw sensitive data.
- Use sanitized, aggregated, or synthetic examples when demonstrating data processing in the repository.

License and contribution agreement

- All contributions to this repository are, by default, licensed under the repository license (CC BY 4.0 for documentation and non-code content). If you provide code, clearly indicate the intended license in the relevant file or directory.
- By contributing, you confirm you have the right to submit the material and that it does not violate third-party rights.

Administrative and governance notes

- The project aims to adopt standard governance files (CODE_OF_CONDUCT.md, LICENSE, SECURITY.md) during the foundation phase. Please follow those documents once they exist.
- If you are proposing sustained collaboration or want to be listed as a collaborator, open an issue describing your role, expectations, and affiliations.

Questions and contact

- For questions or to propose a large contribution, open an issue describing your proposal with sufficient detail to start a discussion.
- Maintainer contact: https://github.com/ALi8744

Thank you for helping build a high-quality, research-oriented project. Your careful contributions preserve the repository’s integrity and help the project remain a useful public resource.