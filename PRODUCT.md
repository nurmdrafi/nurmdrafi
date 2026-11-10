# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

- Primary [inferred, pending user confirmation]: recruiters and hiring managers evaluating Nur Mohamod Rafi for senior/lead frontend roles. Situation: ~30-second scan of a GitHub profile; job: see who he is, what he leads, and find proof fast.
- Secondary [inferred, pending user confirmation]: engineers evaluating his OSS — Barikoi mapping SDKs on npm and the pi-native agent harness.
- Tertiary: peers arriving from Stack Overflow / Medium.

## Product Purpose

The GitHub profile README (github.com/nurmdrafi) is the public front door to his engineering work. Success: a visitor grasps his position — Lead Frontend Engineer at Barikoi by day, harness engineer by craft — and reaches verifiable proof (metrics, packages, repos, links) within one viewport-scroll.

## Positioning

Two-track engineer, truthfully:
1. Lead Frontend Engineer, Barikoi Technologies — leads frontend architecture and delivery for Barikoi Maps products: high-performance Map SDKs, geospatial applications, enterprise mapping solutions serving millions of users (retail, banking, logistics, e-commerce).
2. Harness engineer — author of [pi-native](https://github.com/nurmdrafi/pi-native): a performance-focused Pi coding-agent harness with native Rust tools, fail-closed permission gates, and token-efficient context management. MIT, macOS/Linux, actively maintained (pushed 2026-11-08).

A neighboring profile could copy the badge wall; it could not truthfully copy this mapping-scale + agent-harness combination.

## Operating Context

- Rendered by GitHub's markdown pipeline: no external CSS/JS; badges/images by URL; dark and light themes only via `prefers-color-scheme` `<picture>` swapping; GitHub HTML subset only.
- Single file surface: `README.md`; one automated workflow (`.github/workflows/main.yml`) regenerates the contribution-grid snake SVG daily to the `output` branch.
- Facts live outside this repo: `resumes/main.tex` in the resume-ops repo is the verbatim source of truth; pi-native facts come from that public repo.

## Capabilities and Constraints

- Hard rule [user-confirmed]: every metric, tool, and claim must trace verbatim to `resumes/main.tex` or to a user-provided source (pi-native repo). No invented or inflated metrics.
- Untraceable claims are defects, not style: PostgreSQL and Redis badges were removed 2026-11-08 for this reason.
- The mentoring claim ("Mentor 6+ engineers") exists in main.tex but was deliberately dropped from the profile by the user (commit 87e1cae); do not reintroduce.
- Contact links (from main.tex header): portfolio nurmdrafi.vercel.app, linkedin.com/in/nurmdrafi, medium.com/@nurmdrafi, stackoverflow.com/users/15497939/nurmdrafi, nurmdrafi2014@gmail.com, github.com/nurmdrafi.
- Open decision [asked, unanswered]: keep or drop the contribution-grid snake animation.
- Undecided [inferred, pending confirmation]: audience weighting above.

## Brand Commitments

- Voice: first person, direct, metric-dense; plain words; no emoji-as-icon-system commitments beyond what the redesign chooses.
- Name: Nur Mohamod Rafi; title line "Software Engineer - Frontend" (main.tex wording).

## Evidence on Hand

- `resume-ops/resumes/main.tex` — verbatim facts: role, dates, all project metrics (Pickaboo: 1M+ mobile users, 500K+ registered, 10K+ daily transactions, 10+ payment methods, 30% organic traffic growth, 40% API-call reduction; AKG Sales Live: 2.8M outlets, 4,500+ reps, 2,000+ updates/sec, 25% fewer route deviations; Verify: Bangladesh Fintech Award 2023, 13+ institutions; Geo-Fiber: 46,500+ KM deck.gl; JTI: ~6K users; Saleskoi; DropX), skills taxonomy (9 skill lines incl. Documentation & Tooling), npm packages (bkoi-gl 17 releases / ~1,000 mo; react-bkoi-gl 14 / ~800; barikoiapis ~800; geo-polyline-tools 7 / ~50; barikoi-map-widget 4 / ~35; barikoiapis-golang 7 versions), Stack Overflow 539+ rep / 27 answers, 8 Medium articles.
- `resume-ops/reference/` — tech_evidence.json, quant_facts.json, fact_checks.json, ideas.md.
- `github.com/nurmdrafi/pi-native` — repo description, topics (agent-harness, rust, permission-gate, token-optimization, tui, subagents...), MIT license, CI/release workflows. Live star/fork counts must render via live badges, never as hardcoded text.
- Absences future work must not fabricate: no PostgreSQL/Redis/Prisma credentials; no team-size or mentoring claims on the profile; no business metrics beyond main.tex.

## Product Principles

1. Proof over adjectives: every claim carries a number or a link a visitor can verify.
2. Two tracks, one voice: mapping-at-scale engineering and agent-harness engineering presented as one coherent practice, not two personas.
3. Truth discipline: facts trace to sources; untraceable claims get removed, never softened.
4. Fast scan first: a recruiter's 30-second pass must succeed before any visitor's deep dive.
