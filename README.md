# Artur Chernikov

Frontend engineer. React, white-label platforms at scale. Tbilisi, Georgia.

Almost everything I've built is in private repositories, so here is the short version.

## What I do

For the past three years I've worked on B2B white-label platforms in iGaming, where one
site template ships as dozens of independent brands, each with its own config, theme,
assets and mirror domains.

**Main platform** — 33 React templates and 200+ brands in development and maintenance.
Main contributor across 120+ repositories, five templates built end to end. Grew the
shared internal libraries — components, payments, game mechanics (fortune wheel, free
spins, jackpot, live bet feed) — and shipped them into every template as versioned npm
packages.

**New platform, from scratch** — frontend lead for the past year: first as the only
frontend developer, later leading one more. Designed the platform core (Redux Toolkit
store, API layer, config provider) and released it as a versioned private package, so
each template upgrades on its own schedule. First brands were live within a month;
9 templates and 47 brands run on it today. Re-architecting the templates dropped a
template's direct dependencies from ~66 to ~20 — updating shared logic became a version
bump instead of editing every site by hand.

## What I'm good at

- **Multi-brand architecture** — one template, dozens of brands driven by config, theme
  and assets; deploys across mirror domains
- **Internal library design** — versioned npm packages, private registry, keeping
  business logic out of templates
- **Performance on catalog-heavy pages** — list virtualization for several thousand
  items, lazy loading, web-vitals, Sentry, PWA
- **Integrations** — payment providers with crypto-address validation, social login,
  anti-fraud, push, live chat, GTM and marketing tracking
- **AI tooling** — Claude Code skills with eval sets, so an agent solves routine tasks
  the same way every time

## Stack

React 18, Redux Toolkit, React Router, JavaScript, TypeScript, SCSS, styled-components,
Tailwind, Vite, Webpack, GitLab CI/CD, Playwright, Vitest, Node.

## Right now

Building **Focus** — a DAW with an AI producer. TypeScript across the stack, Tauri
desktop, spec-first development with CI gates. I own billing end to end, auth, and the
agent tooling.

Publishing independent implementations of the architecture I work with daily, written
from scratch: a white-label starter and a UI kit for iGaming mechanics. Links will
appear here as they land.

## Contact

- Email — arturka.sheldon@gmail.com
- Telegram — [@catslegion](https://t.me/catslegion)
