<!--
Sync Impact Report:
- Version change: 1.0.0 → 1.1.0
- Modified principles: Principles 1-4 updated. Principles 5-6 removed.
- Added sections: "Purpose, Environment & Audience", "Standards & Requirements"
- Removed sections: None explicit from the template, but principle sections 5 and 6 are removed from the filled content.
- Templates requiring updates:
    - .specify/templates/plan-template.md ⚠ pending
    - .specify/templates/spec-template.md ⚠ pending
    - .specify/templates/tasks-template.md ⚠ pending
    - .specify/templates/commands/sp.constitution.md ✅ updated
- Follow-up TODOs: None.
-->
# AI/Spec-Driven Book Creation with Spec-Kit Plus and Claude Code Constitution

## Core Principles

### Spec-first documentation workflow
All documentation and content creation must follow a spec-first approach, ensuring clear requirements and structured development.

### High technical accuracy and clarity
Content must be technically accurate, easy to understand, and free of ambiguity.

### Practical and developer-focused explanations
Explanations should be practical, providing developers with actionable insights and real-world relevance.

### AI-assisted but human-verified content
AI tools can assist in content generation, but all output must be human-reviewed and verified for accuracy and quality.

## Purpose, Environment & Audience

Purpose & Environment:
- Use Spec-Kit Plus and Claude Code for all book writing.
- All work must occur inside a frontend folder which are on root of the directory.
- Inside frontend, the Docusaurus project must be created using the Context7 MCP server.
- Deploy the generated site to GitHub Pages.
- Include a bottom-right chatbot UI visible on every page.
  - Chatbot uses /query API endpoint.
  - Must support streaming, abort behavior, and robust error handling.

Audience:
- Software developers
- AI learners
- Technical students

## Standards & Requirements

Standards:
- Each chapter must follow the defined spec structure.
- Markdown format only.
- Clear English with simple, understandable explanations.
- No fabricated APIs, tools, technologies, or concepts.

Tooling Requirements:
- Writing: Spec-Kit Plus + Claude Code
- Static site: Docusaurus created using Context7 MCP (inside frontend folder on root directory)
- Deployment: GitHub Pages

Content Requirements:
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

Constraints:
- Language: English
- No placeholder or plagiarized content
- Beginner-friendly, professional tone

Success Criteria:
- Docusaurus project builds successfully using Context7 MCP inside frontend folder on root directory.
- Fully deployed and functional on GitHub Pages.
- Chatbot UI works on all pages using /query with error handling and abort support.
- All content matches specifications exactly.

## Governance

This constitution supersedes all other project practices.
Amendments require documentation, approval, and a migration plan.
All pull requests and reviews must verify compliance with these principles.
Complexity must always be justified.

**Version**: 1.1.0 | **Ratified**: 2025-12-05 | **Last Amended**: 2025-12-05
