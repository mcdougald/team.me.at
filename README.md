<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset=".github/assets/hero-dark.png">
    <img src=".github/assets/hero.png" alt="team.me.at landing page" width="880">
  </picture>
</p>

# team.me.at

Team up with me at... the people who build alongside Trevor McDougald.

team.me.at is the collaborator and open-source team hub for the `*.me.at` family. It publishes a curated, consent-gated roster of collaborators and contributors and routes anyone who wants to join toward the right existing channel. It is deliberately separate from hiring and scheduling: there is no applicant workflow and no user input. For now the team is one person.

**Live:** [team.me.at](https://team.me.at)

## Features

- **Curated roster**: adding a person is a data edit, not a layout change, and each entry links to their GitHub profile or site.
- **Consent first**: a person must opt in before being published, and a withdrawal removes them from the public roster.
- **Optional GitHub enrichment**: when enabled, GitHub data can decorate people already on the roster but can never add membership. It is cached and degrades gracefully when unavailable.
- **Machine-readable roster**: the same team is published as `/humans.txt`.
- **Ways to join**: calls to action route to meet.me.at, hire.me.at and GitHub instead of a form.
- **Live projects at a glance**: a short list of the family projects the team works on.

## Built with

- Next.js 16 (App Router), React 19, TypeScript
- Tailwind CSS 4
- GitHub API (Octokit) for optional roster enrichment
- No app-owned backend

## Part of the me.at family

team.me.at is one of the [`*.me.at`](https://me.at) apps by Trevor McDougald. They share one design system, account, and app shell. Development happens in a private monorepo; this repository is the project's public-facing home.

## License

See [LICENSE](LICENSE).
