<!--
SYNC IMPACT REPORT
Version: 0.0.2 -> 0.0.3
Change Type: PATCH (Added specific tech stack requirements)

Modified Principles:
- Updated: Technology Stack (React, Node.js, TypeScript)

Added Sections:
- None

Templates Status:
- .specify/templates/plan-template.md: ✅ Compatible
- .specify/templates/spec-template.md: ✅ Compatible
- .specify/templates/tasks-template.md: ✅ Compatible

Follow-up TODOs:
- None
-->
# CQube Solutions Website Constitution

## Core Principles

### I. Static & Secure Architecture
The website MUST be architected as a static site (JAMstack). All pages MUST be pre-rendered at build time. No dynamic server-side rendering (SSR) is permitted on the serving layer. This ensures maximum performance and minimizes the attack surface.

### II. Visual Elegance & Experience
Design MUST be "elegant"—prioritizing clean layout, consistent typography, and smooth, purposeful animations. The site MUST be fully responsive (mobile-first). Accessibility (WCAG 2.1 AA) is a non-negotiable component of elegance.

### III. Security by Design
Security is paramount. A strict Content Security Policy (CSP) MUST be implemented. Dependencies MUST be minimized, pinned, and regularly scanned. No sensitive data or credentials shall be stored in the client-side code.

### IV. Content-Driven
Content structure MUST be separated from presentation. Semantic HTML MUST be used to ensure SEO visibility and accessibility. The site structure should intuitively guide the user to information about CQube Solutions.

### V. Test Coverage
All code MUST be covered by automated tests. This includes unit tests for logic and integration/end-to-end tests for critical user journeys. No feature is considered complete without passing tests.

### VI. Local Portability
The project MUST be able to be run locally from a developer's machine with minimal setup. Documentation (e.g., `README.md`) must provide clear instructions for local execution. All dependencies must be manageable via standard package managers.

## Technology Stack

- **Core**: React with TypeScript.
- **Environment**: Node.js.
- **Framework**: Next.js (Static Export) or Vite.
- **Styling**: Tailwind CSS for consistent, maintainable design systems.
- **Deployment**: Static hosting (e.g., Vercel, Netlify, AWS S3+CloudFront).

## Quality & Deployment

- **CI/CD**: Automated pipelines MUST run linting, type checking, and build verification on every commit.
- **Performance**: Lighthouse performance scores SHOULD exceed 90 across all categories.

## Governance

This Constitution supersedes all other practices. Amendments require a Pull Request with justification and team approval.
Versioning follows Semantic Versioning (SemVer 2.0.0).

**Version**: 0.0.3 | **Ratified**: 2026-01-03 | **Last Amended**: 2026-01-03
