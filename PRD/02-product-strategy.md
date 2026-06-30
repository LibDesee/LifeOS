# 02 Product Strategy

<!-- TOC -->
- [Metadata](#metadata)
- [Purpose](#purpose)
- [Scope](#scope)
- [Dependencies](#dependencies)
- [Related Documents](#related-documents)
- [Definitions](#definitions)
- [Requirements](#requirements)
- [Content](#content)
- [Open Questions](#open-questions)
- [TODO](#todo)
- [Changelog](#changelog)
<!-- /TOC -->

## Metadata

| Field | Value |
|---|---|
| Title | 02 Product Strategy |
| Version | 0.2.0 |
| Status | Draft |
| Owner | TODO |
| Last Updated | 2026-06-30 |

## Purpose

Define the product strategy for LifeOS based on the current product goal, primary user, direction, priorities, principles, long-term strategy, and success criteria.

## Scope

- Product goal.
- Primary user.
- Product direction.
- Key principles.
- Initial priorities.
- Long-term strategy.
- Success criteria.

## Dependencies

| Dependency | Type | Status |
|---|---|---|
| Samsung Health | Data source | Initial priority |
| Calendar | Data source | Initial priority |
| Tasks | Data source | Initial priority |
| Notes | Data source | Initial priority |
| Additional data sources | Data source | TODO |

## Related Documents

- [01 Vision](01-vision.md)
- [03 Product Principles](03-product-principles.md)
- [09 Data Sources](09-data-sources.md)
- [13 Integrations](13-integrations.md)
- [20 Privacy](20-privacy.md)
- [AI Brain](08-ai-brain.md)
- [Storage Architecture](../Architecture/storage-architecture.md)
- [Sync Architecture](../Architecture/sync-architecture.md)

## Definitions

| Term | Definition |
|---|---|
| Primary User | The first user of the system: the owner of LifeOS. |
| Local First | TODO |
| Integration-first Architecture | TODO |
| Continuous Knowledge Growth | TODO |

## Requirements

| ID | Requirement | Priority | Status |
|---|---|---|---|
| STR-001 | LifeOS MUST create a personal system that unifies all user data in one place. | High | Draft |
| STR-002 | LifeOS MUST help the user better understand their own life. | High | Draft |
| STR-003 | The first user of LifeOS MUST be the owner of LifeOS. | High | Draft |
| STR-004 | LifeOS MUST be created primarily for personal use. | High | Draft |
| STR-005 | Future architecture SHOULD allow LifeOS to be used by other people. | Medium | Draft |
| STR-006 | LifeOS MUST develop gradually. | High | Draft |
| STR-007 | LifeOS SHOULD connect primary data sources first. | High | Draft |
| STR-008 | The number of integrations SHOULD increase over time. | High | Draft |
| STR-009 | Architecture MUST support scaling without a full system rewrite. | High | Draft |
| STR-010 | LifeOS MUST follow Local First. | High | Draft |
| STR-011 | The user MUST own all data. | High | Draft |
| STR-012 | AI MUST assist the user. | High | Draft |
| STR-013 | LifeOS SHOULD support continuous knowledge growth. | High | Draft |
| STR-014 | LifeOS SHOULD follow an integration-first architecture. | High | Draft |
| STR-015 | The human MUST make the final decision. | High | Draft |

## Content

### Product Strategy

#### Product Goal

Create a personal system that unifies all user data in one place and helps the user better understand their own life.

#### Primary User

The first user of the system is the owner of LifeOS.

LifeOS is created primarily for personal use.

In the future, the architecture SHOULD allow other people to use LifeOS.

#### Product Direction

LifeOS develops gradually.

Primary data sources are connected first.

Later, the number of integrations SHOULD constantly increase.

The architecture MUST support scaling without a full system rewrite.

#### Key Principles

| Principle | Requirement |
|---|---|
| Local First | LifeOS MUST follow Local First. |
| User owns all data | The user MUST own all data. |
| AI assists the user | AI MUST assist the user. |
| Continuous knowledge growth | LifeOS SHOULD support continuous knowledge growth. |
| Integration-first architecture | LifeOS SHOULD follow an integration-first architecture. |
| Human makes the final decision | The human MUST make the final decision. |

#### Initial Priorities

The first data sources are:

| Source | Priority | Status |
|---|---|---|
| Samsung Health | Initial | Draft |
| Calendar | Initial | Draft |
| Tasks | Initial | Draft |
| Notes | Initial | Draft |
| Other sources | Later | TODO |

#### Long-Term Strategy

LifeOS gradually becomes the central place for storing knowledge about the user's life.

Each new integration SHOULD increase the quality of AI analysis.

#### Success Criteria

The user can:

| Criterion | Status |
|---|---|
| See the full picture of their life. | Draft |
| Understand the causes of ongoing changes. | Draft |
| Receive useful recommendations. | Draft |
| Not lose important information. | Draft |

## Open Questions

- Which sources are included after Samsung Health, Calendar, Tasks, and Notes?
- What architectural constraints are required to support scaling without a full system rewrite?
- What does integration-first architecture formally mean?
- How is AI analysis quality measured?
- What defines a useful recommendation?

## TODO

- [ ] Define Local First in this product strategy context.
- [ ] Define integration-first architecture.
- [ ] Define continuous knowledge growth.
- [ ] Define the source rollout order after the initial priorities.
- [ ] Define success measurements.

## Changelog

| Date | Version | Change |
|---|---|---|
| 2026-06-30 | 0.1.0 | Created PRD document. |
| 2026-06-30 | 0.2.0 | Filled product strategy from Task 005 source material. |
