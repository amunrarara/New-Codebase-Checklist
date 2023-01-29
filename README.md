# New Codebase Outline - In Order of Operations

The following document is offered for free to the public under the GNU Free Documentation License: https://www.gnu.org/licenses/fdl-1.3.html

## High-Level Use Case Survey

---

- Business requirements
- Design review
- Integrations with existing in-house platform(s)

## Project Management

---

- Platform
    - Jira | ZenHub | Asana | Monday | ClickUp | Favro | Notion
- Structure
    - Agile | Kanban | Scrum | Ad-hoc

## Architectural Decisions

---

- JS Framework
    - Static | SSR | SSG | SPA
- Server Requirements
    - Persistent (Linux) | Edge (On-Demand)
- Remote Repository
    - GitHub | GitBucket
- Database
    - Relational (MySQL | PostgreSQL | MariaDB) |
    - Document (Firebase | MongoDB)
    - Key-Value (Redis)
    - Centralized | Distributed
    - On-Premises | Cloud
- Asset Storage
    - S3 | Cloudflare
- Log Drain
- Analytics

## Repository

---

**Local**

- Init
- main | staging | dev > workspace-feature-task

**Remote**

- Create account(s)
- Init push
- Pull guards
- Issue tracking

## Dev Environment

---

- VS Code + Docker Dev Environment

## Monorepo Structure

---

- Frontend Application(s)
    - Web Client
    - Mobile Client
    - Admin Client
- Backend Services
    - API
- Shared - Utilities and Components

## Initial Dependencies and Configs

---

- Framework
    - Remote sources
    - HTTP Header hooks
    - Package transpiling (monorepo shared utils)
- TypeScript
    - Base URL + non-relative import remapping
    - References (monorepo shared utils)
- Monorepo Tooling
    - TurboRepo | NX | Lerna
- Linting
    - ESLint
- Precommit
    - Husky
    - lint-staged
- CSS Utility Classes
    - Tailwind | Bootstrap
- Testing
    - Cypress | Jest | Mocha | Puppeteer

- Common utilities
    - lodash | classNames | redirects | error classes | hooks

## CSS Globals

---

- Overrides
- Colors
- Fonts
- Custom utility classes

## Deployment Overview and Setup

---

- Collect DNS information
- Client Hosting environment
    - Vercel | AWS | Firebase | Linode | Cloudflare
- Database Hosting environment
- CI/CD Pipeline
- Log Drain
- Analytics
- Anything Dockerized?
- Regions?
- Projected # of users?

## Mock Services

---

- APIs
- ORM / Database
- Emulators
- NEXT_PUBLIC_ Env Vars (if using NextJs)

## Components Library

---

- Buttons

## Identity + Access Management

---

- Authentication
- Authorization
- Roles
- User Data

## Backend Development

---

- API
    - Auto-documentation
    - Security
- Database

## Frontend Development

---

- Navigation
    - Responsive Navbar
- Layouts
    - Inject meta tags
- Hero Areas
- Footers
