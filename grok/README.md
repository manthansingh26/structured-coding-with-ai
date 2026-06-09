# Grok Instruction Set

Ready-to-use instruction file for Grok (xAI) optimized for animal advocacy and animal liberation software projects.

This directory provides structured guidance so Grok can work effectively on high-risk advocacy codebases while respecting security, privacy, emotional safety, and movement-specific requirements.

## What's Included

- Full coverage of the **7 Concerns** (Testing, Security, Privacy, Cost Optimization, Advocacy Domain, Accessibility, Emotional Safety)
- Full coverage of the **6 Process Skills** (git-workflow, testing-strategy, requirements-interview, plan-first-development, code-review, security-audit)
- **Two-State Identity Model** (Advocacy Mode + Neutral Mode) for safe internal and external contributions

## Structure

```
grok/
├── GROK.md          # Main instruction file (load as system/custom instructions)
└── README.md        # This file
```

## Usage

Copy the directory into your project root:

```bash
cp -r grok/ your-project/
```

Then load `GROK.md` as custom instructions or include it at the start of your Grok sessions.

## Modes

- **Advocacy Mode** (default for Open Paws repos): Full movement language and rules active.
- **Neutral Mode** (external repos): Suppress all advocacy context, Open Paws references, and movement terminology. Match target repo style exactly.

See `GROK.md` for the complete Two-State Identity Model, 7 Concerns, 6 Process Skills, workflow, review checklist, and constraints.

These instructions are part of the [structured-coding-with-ai](https://github.com/Open-Paws/structured-coding-with-ai) library maintained by Open Paws.
