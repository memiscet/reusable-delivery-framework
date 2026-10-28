# Working in this repository

Read README.md and docs/file-contracts.md before changing framework behavior.

The seven canonical skills live in skills/. They can be read directly by any assistant; do not assume a particular editor discovers that folder automatically. See docs/using-skills.md for integration.

For project work, use the explicit project path and deliverable ID. Read project.yaml and the project's documents. Keep plans, summaries, and reviews in deliveries/<ID>/ inside that project. Never select work silently or overwrite another project's files.

Preserve the user's project scope and technology choices. A missing prerequisite or an unresolved decision that affects correctness should be reported, rather than filled in as a fact. Record nonblocking assumptions. The framework does not grant permission to publish, deploy, send messages, or change live services.

Validate changed artifacts with scripts/validate.py. For tooling changes run python -m unittest discover -s tests -v. Keep schemas, templates, examples, instructions, and documentation consistent when changing contracts. Do not claim a deliverable passed based only on schema validation.
