# Premetra: Product and Engineering Case Study

[Back to the showcase](../README.md) · [Visit Premetra](https://premetra.com)

## Context

Premetra, formerly BetStrength, is a sports intelligence product from Helpman Analytics and Insights Ltd. Its central purpose is to make pre-match information easier to explore and compare.

My role combines co-founder responsibilities with product engineering: defining useful workflows, implementing the application and extending it across consumer and partner experiences.

## Product approach

The product connects three activities:

1. **Discover:** browse fixtures or use ranked AI Picks and filters to find relevant matches.
2. **Assess:** open a fixture and inspect team comparisons, trends and decision-support views.
3. **Organise:** save relevant fixtures to a selection and revisit them as results become available.

This sequence keeps the experience focused on what the user needs to do with the information.

## Subscriber journey

A visitor can begin with livescores. A registered user can purchase tokens, unlock supported analysis and inspect fixture details.

The analysis experience brings together team strength, scoring and conceding indicators, recent form, head-to-head context and confidence information. AI-assisted previews provide an additional explanation layer.

Selections serve as a shortlist. Users can organise fixtures privately or use the publishing workflow for supported selections.

## Partner journeys

### Agents

Agents use a dedicated portal to refer subscribers and track referral activity and earnings. This creates a distribution workflow alongside the consumer product.

### Shops

Partner shops purchase tokens in bulk and use a dedicated console to provide analysis access to customers. Staff accounts support operation beyond a single shop login.

The shop experience includes dedicated livescore and AI Picks pages, with purchases and unlocking managed through shop workflows.

### Shop Agents

Shop Agents focus on bringing partner shops onto the platform. Their dedicated experience separates shop recruitment from subscriber referrals.

## Engineering decisions

### Procedural PHP

The application uses procedural PHP rather than a framework. This reflects my preferred development approach and gives me direct control over request handling and application workflows.

### Structured fixture records

Fixture records connect provider identifiers, competition information, kickoff times, match status, analysis and completed results. A consistent fixture representation supports discovery, detail views and result updates.

### Separate balances for distinct workflows

Subscriber tokens, agent earnings and shop balances serve different purposes. Separate workflows reflect those differences in the application rather than treating every balance as interchangeable.

### Filters that support discovery

Country and league search, confidence bands, kickoff windows and sorting help users navigate large fixture lists. These controls connect discovery to the user's available time and preferred competitions.

### Multiple analysis views

A fixture can be assessed through team comparisons, recent-form indicators, outcome probability views and an AI-assisted preview. These views provide complementary context instead of relying on a single headline verdict.

### Results connected to selections

Saved fixtures and published selections connect to result updates, supporting a workflow that continues after kickoff.

## Scope of my work

| Area | Contribution |
| --- | --- |
| Product planning | Feature definition and user journeys |
| Backend development | PHP application logic and database workflows |
| Frontend development | Interactive interfaces and analysis presentation |
| Data integration | Sports provider integration and fixture processing |
| Commercial workflows | Tokens, unlocks and referrals |
| Partner experiences | Agent, shop and shop-agent workflows |
| Ongoing delivery | Maintenance, fixes and feature extensions |

## What this project demonstrates

- Taking a product from an idea into a working web platform.
- Building across frontend, backend and relational data workflows.
- Turning external data into user-facing product features.
- Designing connected experiences for several user roles.
- Supporting access, partner operations and referral workflows.
- Maintaining an evolving application over time.

## Evidence and boundaries

The [live product](https://premetra.com) provides the public reference for the platform. Some experiences require an account or tokens.

This case study describes the product and my contribution. It does not publish source code, customer data, credentials, internal commercial documents or proprietary calculation rules. No audited performance or scale claims are made here.
