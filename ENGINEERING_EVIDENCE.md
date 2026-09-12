# Engineering Evidence

This portfolio uses **public case studies for architecture and engineering decisions** while keeping commercial source repositories private where they contain customer data, credentials, operational details, or proprietary implementation.

The goal is not to replace source code with marketing language. Each featured case study points to a real engineering system with private verification artifacts behind it.

## Evidence by project

| Project | Verification model retained in private source |
|---|---|
| **[FB Groups](https://github.com/LEVENT-AY/fb-groups-case-study)** | Separate evidence domains for source, built/staged extension, loaded browser runtime, backend/dashboard runtime, and external-platform acceptance; immutable-artifact production delivery and guarded runtime verification. |
| **[Souketwensa CRM](https://github.com/LEVENT-AY/souketwensa-crm-case-study)** | Dedicated CI workflows for pull-request verification, database proof, hot verification, and production delivery; tenant-aware application/data boundaries and integration-state reconciliation. |
| **[Aya Cloud](https://github.com/LEVENT-AY/aya-cloud-case-study)** | Production Docker workflow, controlled edge routing, environment/secret separation, customer-vs-private operations boundaries, and explicit application-health verification. |
| **[Kovoyo](https://github.com/LEVENT-AY/kovoyo-case-study)** | Melos-managed multi-app Flutter monorepo, shared domain/data/realtime/geo/testing packages, PostgreSQL/PostGIS RLS + pgTAP coverage, and physical-device mobile validation. |
| **[Dalilk in Turkey](https://github.com/LEVENT-AY/dalilk-in-turkey-case-study)** | Physical Android device screenshots and UI-hierarchy captures, Arabic encoding/integrity standards and repair reports, service-specific verification documentation, and operational review workflows. |
| **[Trendyol Syria](https://github.com/LEVENT-AY/trendyol-syria-case-study)** | End-to-end Docker verification stack covering canonical PostgreSQL ingestion, transactional outbox, Redis projections, deterministic OpenSearch indexing, and the read-optimized product API. |

## What is intentionally public

- sanitized system architecture;
- product and engineering scope;
- technology choices;
- key design decisions and failure boundaries;
- non-sensitive verification methodology;
- the specific areas I designed, implemented, operated, or verified.

## What stays private

- customer or tenant data;
- credentials, tokens, environment values, and private hostnames;
- private account identities and operational records;
- commercial source code where publishing it would expose IP or security-sensitive implementation details;
- unreviewed production screenshots that may contain personal or customer information.

## Technical interview walkthroughs

Where confidentiality permits, private-source architecture and implementation details can be discussed or walked through during a technical interview. Any walkthrough remains scoped to non-sensitive engineering material; customer data, credentials, and protected operational information are never shared.

A useful technical-interview path is to start with the case study closest to the role, then drill into architecture trade-offs, verification strategy, failure modes, and production debugging decisions.

This policy is deliberate: **public evidence should be useful enough to evaluate engineering judgment without turning production systems into public attack surfaces or giving away commercial source code.**

[← Back to the engineering profile](https://github.com/LEVENT-AY)
