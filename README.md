<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="team.me.at landing page" width="880">
  </picture>
</p>

<h1 align="center">team.me.at</h1>

<p align="center"><strong>Team up with me at... the people who build alongside me.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/status-live-171717?style=flat-square" alt="Status: live">
  <img src="https://img.shields.io/badge/license-source--available-404040?style=flat-square" alt="License: source-available">
  <img src="https://img.shields.io/badge/part%20of-me.at-737373?style=flat-square" alt="Part of me.at">
</p>

<p align="center">
  <a href="https://team.me.at">Website</a> ·
  <a href="#features">Features</a> ·
  <a href="#how-it-works">How it works</a> ·
  <a href="#built-with">Built with</a>
</p>

If you want to build something with me, you should be able to see who already does and where to start. I built team.me.at as the collaborator and open-source team hub for my `*.me.at` family: a curated, consent-gated roster of collaborators and contributors, and calls to action that route anyone who wants to join toward the right existing channel. It is deliberately separate from hiring and scheduling, with no applicant workflow and no user input. For now the team is one person.

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/overview-dark.svg">
    <img src=".github/assets/overview.svg" alt="team.me.at at a glance: curated roster, consent first, enrichment never adds, ways to join" width="880">
  </picture>
</p>

## Why

- **Consent before publication**: nobody appears on the roster without opting in, and a withdrawal takes them off it.
- **Curated, not scraped**: membership comes only from the roster itself. GitHub data can decorate a listed person but never add one.
- **No form to fill in**: joining means a link to an existing channel, not an applicant workflow.

## Features

- **Curated roster**: adding a person is a data edit, not a layout change, and each entry links to their GitHub profile or site.
- **Consent first**: a person must opt in before being published, and a withdrawal removes them from the public roster.
- **Optional GitHub enrichment**: when enabled, GitHub data can decorate people already on the roster but can never add membership. It is cached and degrades gracefully when unavailable.
- **Machine-readable roster**: the same team is published as `/humans.txt`.
- **Ways to join**: calls to action route to meet.me.at, hire.me.at and GitHub instead of a form.
- **Live projects at a glance**: a short list of the family projects the team works on.

## How it works

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/flow-dark.svg">
    <img src=".github/assets/flow.svg" alt="How team.me.at works: opt in, add, enrich, publish, join" width="880">
  </picture>
</p>

A collaborator opts in, and one data edit adds them to the roster. If enrichment is switched on, cached GitHub details decorate the people already listed. The same list is published as the page and as `/humans.txt`, and anyone who wants to join is pointed to meet.me.at, hire.me.at or GitHub.

## Built with

<p>
  <img src="https://img.shields.io/badge/Next.js-16-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js 16">
  <img src="https://img.shields.io/badge/React-19-171717?style=flat-square&logo=react&logoColor=white" alt="React 19">
  <img src="https://img.shields.io/badge/TypeScript-5-262626?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Tailwind%20CSS-4-404040?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS 4">
  <img src="https://img.shields.io/badge/GitHub-Octokit-525252?style=flat-square&logo=github&logoColor=white" alt="GitHub API via Octokit">
</p>

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- GitHub API (Octokit) for optional roster enrichment
- No app-owned backend

## Part of the me.at family

team.me.at is one of my [`*.me.at`](https://me.at) apps. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

Source-available. See [LICENSE](LICENSE).
