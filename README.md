# LifeOS

<!-- TOC -->
- [Project Description](#project-description)
- [Project Goals](#project-goals)
- [Philosophy](#philosophy)
- [Repository Structure](#repository-structure)
- [Documentation Rules](#documentation-rules)
- [Naming Conventions](#naming-conventions)
- [Document Index](#document-index)
- [Project Status](#project-status)
- [Documentation Roadmap](#documentation-roadmap)
- [Changelog](#changelog)
<!-- /TOC -->

## Project Description

LifeOS is a personal operating system for a human life.

LifeOS is not a habit tracker, not an RPG, and not another AI chat interface.

The long-term goal is to become a local-first digital copy of the user: collecting user data, storing it locally, connecting it, analyzing it with AI, and supporting better decision-making.

## Project Goals

| Goal | Status |
|---|---|
| Define product requirements | TODO |
| Define system architecture | TODO |
| Define data architecture | TODO |
| Define AI architecture | TODO |
| Define privacy and security model | TODO |
| Define platform strategy | TODO |

## Philosophy

- The system MUST prioritize user ownership of data.
- The system MUST avoid invented product claims in documentation.
- The system SHOULD make decisions traceable to documented requirements.
- The system MAY evolve over years through versioned decisions and research.

## Repository Structure

| Directory | Purpose |
|---|---|
| [PRD](PRD/) | Product requirements documentation. |
| [Architecture](Architecture/) | System architecture and technical design. |
| [Docs](Docs/) | General documentation. |
| [Research](Research/) | Research notes and source-backed analysis. |
| [AI](AI/) | AI, memory, reasoning, and context documentation. |
| [Database](Database/) | Data model, entities, relationships, migrations. |
| [API](API/) | API specifications and contracts. |
| [Integrations](Integrations/) | External integration specifications. |
| [Android](Android/) | Android platform documentation. |
| [Windows](Windows/) | Windows platform documentation. |
| [Design](Design/) | UX, UI, and design system documentation. |
| [Assets](Assets/) | Project assets and media. |
| [Diagrams](Diagrams/) | Shared diagrams. |
| [ADR](ADR/) | Architecture Decision Records. |
| [Templates](Templates/) | Reusable documentation templates. |
| [Glossary](Glossary/) | Project terminology. |
| [Meetings](Meetings/) | Meeting notes. |
| [Roadmap](Roadmap/) | Planning and roadmap documents. |

## Documentation Rules

- Documentation MUST use Markdown.
- Requirements MUST use RFC2119 keywords: MUST, MUST NOT, SHOULD, SHOULD NOT, MAY.
- Unknown information MUST be written as `TODO`.
- Documents MUST include metadata: title, version, status, owner, and last updated.
- Decisions with architectural impact MUST be captured in [ADR](ADR/).
- Diagrams SHOULD use Mermaid when appropriate.
- Links SHOULD be relative and point to repository documents.
- Documents MUST avoid speculative functionality.

## Naming Conventions

| Item | Convention | Example |
|---|---|---|
| Markdown files | `kebab-case.md` | `system-context.md` |
| Numbered PRD files | `NN-topic.md` | `00-overview.md` |
| ADR files | `NNNN-title.md` | `0001-record-architecture-decision.md` |
| Headings | Title Case | `## Open Questions` |
| Status values | `Draft`, `Review`, `Approved`, `Deprecated` | `Draft` |

## Document Index

### Core

- [Universal Document Template](Templates/universal-document.md)
- [Glossary](Glossary/glossary.md)
- [ADR Template](ADR/0000-template.md)

### PRD

- [00 Overview](PRD/00-overview.md)
- [01 Vision](PRD/01-vision.md)
- [02 Product Strategy](PRD/02-product-strategy.md)
- [03 Product Principles](PRD/03-product-principles.md)
- [04 User Personas](PRD/04-user-personas.md)
- [05 User Stories](PRD/05-user-stories.md)
- [06 Functional Requirements](PRD/06-functional-requirements.md)
- [07 Non Functional Requirements](PRD/07-non-functional-requirements.md)
- [08 AI Brain](PRD/08-ai-brain.md)
- [09 Data Sources](PRD/09-data-sources.md)
- [10 Knowledge Graph](PRD/10-knowledge-graph.md)
- [11 Data Model](PRD/11-data-model.md)
- [12 Database](PRD/12-database.md)
- [13 Integrations](PRD/13-integrations.md)
- [14 API](PRD/14-api.md)
- [15 Backend](PRD/15-backend.md)
- [16 Android](PRD/16-android.md)
- [17 Windows](PRD/17-windows.md)
- [18 Desktop](PRD/18-desktop.md)
- [19 Security](PRD/19-security.md)
- [20 Privacy](PRD/20-privacy.md)
- [21 Analytics](PRD/21-analytics.md)
- [22 UX](PRD/22-ux.md)
- [23 UI](PRD/23-ui.md)
- [24 Screens](PRD/24-screens.md)
- [25 Notifications](PRD/25-notifications.md)
- [26 Settings](PRD/26-settings.md)
- [27 Roadmap](PRD/27-roadmap.md)
- [28 Risks](PRD/28-risks.md)
- [29 Testing](PRD/29-testing.md)
- [30 Deployment](PRD/30-deployment.md)
- [31 Future](PRD/31-future.md)

### Architecture

- [Architecture Overview](Architecture/architecture-overview.md)
- [System Context](Architecture/system-context.md)
- [Component Diagram](Architecture/component-diagram.md)
- [Deployment Diagram](Architecture/deployment-diagram.md)
- [Data Flow](Architecture/data-flow.md)
- [Event Flow](Architecture/event-flow.md)
- [AI Pipeline](Architecture/ai-pipeline.md)
- [Storage Architecture](Architecture/storage-architecture.md)
- [Sync Architecture](Architecture/sync-architecture.md)
- [Offline First](Architecture/offline-first.md)
- [Security Architecture](Architecture/security-architecture.md)

### Database

- [ER Diagram](Database/er-diagram.md)
- [Entity List](Database/entity-list.md)
- [Relationships](Database/relationships.md)
- [Naming Convention](Database/naming-convention.md)
- [Indexes](Database/indexes.md)
- [Migration Rules](Database/migration-rules.md)

### AI

- [Memory System](AI/memory-system.md)
- [Knowledge Graph](AI/knowledge-graph.md)
- [Recommendation Engine](AI/recommendation-engine.md)
- [Embeddings](AI/embeddings.md)
- [Context Builder](AI/context-builder.md)
- [Prompt System](AI/prompt-system.md)
- [Reasoning](AI/reasoning.md)
- [Planning](AI/planning.md)
- [Agents](AI/agents.md)

### Integrations

- [Samsung Health](Integrations/samsung-health.md)
- [Google Calendar](Integrations/google-calendar.md)
- [Google Tasks](Integrations/google-tasks.md)
- [Google Drive](Integrations/google-drive.md)
- [Google Photos](Integrations/google-photos.md)
- [Gmail](Integrations/gmail.md)
- [Chrome](Integrations/chrome.md)
- [Windows](Integrations/windows.md)
- [Android](Integrations/android.md)
- [Wear OS](Integrations/wear-os.md)
- [Obsidian](Integrations/obsidian.md)
- [Telegram](Integrations/telegram.md)
- [WhatsApp](Integrations/whatsapp.md)
- [Spotify](Integrations/spotify.md)
- [YouTube](Integrations/youtube.md)
- [Location History](Integrations/location-history.md)
- [Bank APIs](Integrations/bank-apis.md)

## Project Status

| Area | Status |
|---|---|
| Documentation infrastructure | Draft |
| Product requirements | TODO |
| Architecture | TODO |
| Implementation | TODO |

## Documentation Roadmap

- [x] Create documentation repository structure.
- [x] Add universal templates.
- [x] Add PRD skeleton.
- [x] Add architecture, AI, database, and integration skeletons.
- [ ] Fill PRD with validated requirements.
- [ ] Create first ADRs.
- [ ] Add source-backed research documents.

## Changelog

| Date | Version | Change |
|---|---|---|
| 2026-06-30 | 0.1.0 | Created documentation bootstrap. |
