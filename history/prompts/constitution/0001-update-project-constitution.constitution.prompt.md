---
id: 0001
title: Update Project Constitution
stage: constitution
date: 2025-12-05
surface: agent
model: claude-sonnet-4-5-20250929
feature: none
branch: main
user: Muhammad Talha
command: /sp.constitution
labels: ["governance", "project-setup"]
links:
  spec: null
  ticket: null
  adr: null
  pr: null
files:
  - .specify/memory/constitution.md
tests:

---

## Prompt

```text
Project:AI/Spec-Driven Book Creation with Spec-Kit Plus and Claude Code
  Purpose & Environment
  - Use Spec-Kit Plus and Claude Code for all book writing.
  - All work must occur inside a frontend folder which are on root of the directory.
  - Inside frontend, the Docusaurus project must be created using the Context7 MCP server.
  - Deploy the generated site to GitHub Pages.
  - Include a bottom-right chatbot UI visible on every page.
    - Chatbot uses /query API endpoint.
    - Must support streaming, abort behavior, and robust error handling.

  Audience
  - Software developers
  - AI learners
  - Technical students
  Core Principles
  - Spec-first documentation workflow
  - High technical accuracy and clarity
  - Practical and developer-focused explanations
  - AI-assisted but human-verified content
  Standards
  - Each chapter must follow the defined spec structure.
  - Markdown format only.
  - Clear English with simple, understandable explanations.
  - No fabricated APIs, tools, technologies, or concepts.

  Tooling Requirements
  - Writing: Spec-Kit Plus + Claude Code
  - Static site: Docusaurus created using Context7 MCP (inside frontend folder on root directory)
  - Deployment: GitHub Pages

  Content Requirements
  - Course covers 13 weeks, organized as:
    - 5 chapters
    - 1 hardware requirements section
    - 1 final assessment section
  - Each chapter must contain 4 topics.
  - Each topic must include:
    - Headings
    - Explanations
    - Bullet points
    - Tables or examples where appropriate
  Constraints
  - Language: English
  - No placeholder or plagiarized content
  - Beginner-friendly, professional tone

  Success Criteria
  - Docusaurus project builds successfully using Context7 MCP inside frontend folder on root directory.
  - Fully deployed and functional on GitHub Pages.
  - Chatbot UI works on all pages using /query with error handling and abort support.
  - All content matches specifications exactly.
```

## Response snapshot

```text
The project constitution has been updated to version 1.1.0 (minor version bump due to new principles and sections).

Templates requiring updates:
- .specify/templates/plan-template.md ⚠ pending
- .specify/templates/spec-template.md ⚠ pending
- .specify/templates/tasks-template.md ⚠ pending

Suggested commit message: `docs: amend constitution to v1.1.0 (principle additions + governance update)`
```

## Outcome

- ✅ Impact: Constitution updated to reflect project requirements and principles.
- 🧪 Tests: N/A
- 📁 Files: 1 file modified: .specify/memory/constitution.md
- 🔁 Next prompts: Address pending template updates (plan, spec, tasks).
- 🧠 Reflection: Successfully updated project constitution. Ensured all placeholders are filled and consistency report is included.

## Evaluation notes (flywheel)

- Failure modes observed: None
- Graders run and results (PASS/FAIL): N/A
- Prompt variant (if applicable): N/A
- Next experiment (smallest change to try): N/A
