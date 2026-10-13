# Premetra
### Pre-Match Intelligence. Smarter Decisions.

**A sports intelligence platform by Helpman Analytics and Insights Ltd.**

Premetra brings team statistics, form, match trends and AI-assisted analysis into one place so users can assess fixtures before kickoff. Formerly known as **BetStrength**, the product combines a consumer experience with dedicated workflows for referral agents, partner shops and shop agents.

**[Explore Premetra](https://premetra.com)** · **[Product case study](docs/product-case-study.md)** · **[Helpman AI](https://helpmanai.com)**

> This repository presents the product and the engineering work behind it. The application's source code, proprietary analytical methods and production data remain private.

## At a glance

| Area | Overview |
| --- | --- |
| Product | Sports intelligence and pre-match decision support |
| My role | Co-founder and product engineer |
| Coverage | Football, basketball, baseball, handball, hockey and volleyball |
| Core technologies | Procedural PHP, JavaScript, jQuery and MySQL |
| Data integration | API-Sports |
| User experiences | Subscribers, Agents, Shops and Shop Agents |
| Access model | Open livescores with token-based access to deeper insights |

## The problem

Sports information is often spread across score services, standings, form tables and match reports. Turning that information into a useful pre-match view takes time.

Premetra brings these signals together in a consistent interface: users can discover fixtures, compare teams, inspect the reasoning behind an analysis and keep a shortlist of matches to revisit.

## What users can do

- **Follow fixtures and livescores:** browse matches and check their status and results.
- **Compare teams:** inspect strength, scoring and conceding averages, recent form, rankings and head-to-head context.
- **Explore AI Picks:** discover ranked fixtures and narrow the list by competition, confidence and kickoff time.
- **Open deeper insights:** examine verdicts, alternative outcomes, probability views, form trends and AI-assisted previews.
- **Build selections:** save fixtures to a shortlist and use private or published selections.
- **Access premium analysis:** purchase tokens and unlock supported insights.

## Four connected user experiences

| Module | Purpose | Entry point |
| --- | --- | --- |
| Subscribers | Explore fixtures, unlock analysis and manage selections | [premetra.com](https://premetra.com) |
| Agents | Refer subscribers and track referral activity and earnings | [/agent](https://premetra.com/agent) |
| Shops | Purchase tokens in bulk and provide customer access through a shop console and staff accounts | [/shop](https://premetra.com/shop) |
| Shop Agents | Refer partner shops and track shop referral activity | [/shop-agent](https://premetra.com/shop-agent) |

## My contribution

As co-founder and product engineer, my work spans product design, full-stack implementation and ongoing technical delivery:

- Translating the product idea into practical user journeys and working application features.
- Building the PHP application, database workflows and interactive frontend.
- Integrating external sports data into fixture and analysis experiences.
- Developing the presentation of team comparisons, confidence indicators and decision support.
- Implementing token access, selections and dedicated partner workflows.
- Maintaining and extending the platform as the product evolves.

## Selected engineering challenges

### Making sports data useful
Fixture data, team statistics and results need a consistent structure before they can support comparisons and discovery. Premetra connects provider data with application workflows and presents the relevant context at fixture level.

### Supporting multiple user roles
A subscriber, referral agent and shop operator have different goals. Dedicated interfaces and separate balance workflows support those differences while keeping the product connected.

### Keeping analysis understandable
Ranked picks alone do not explain a match. Team comparisons, recent form, head-to-head context and alternative outcomes help users examine the underlying signals.

### Connecting analysis with follow-through
Selections let users keep a shortlist, while result updates connect the pre-match experience with completed fixtures.

## Technology

| Layer | Technology or approach |
| --- | --- |
| Backend | Procedural PHP |
| Frontend | JavaScript, jQuery, HTML and CSS |
| Database | MySQL |
| Sports data | API-Sports integrations |
| Infrastructure | VPS hosting |
| Product capabilities | Token access, role-specific portals, referral workflows and AI-assisted previews |

## Repository contents

- **README.md:** product overview and portfolio introduction.
- **docs/product-case-study.md:** product decisions, workflows and engineering context.

## Ownership and scope

Premetra is a product of **Helpman Analytics and Insights Ltd**. This showcase does not grant a licence to the application, its branding, its data or its proprietary analytical methods.

Sports analysis expresses estimates and uncertainty; it does not guarantee match outcomes.
