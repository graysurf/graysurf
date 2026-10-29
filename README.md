## About Me

Backend and platform engineer with 10+ years across distributed services, data platforms, and cloud-native
delivery on Kubernetes. I turn unsettled requirements and tangled
system boundaries into clear structures that teams can build on — and lately, into workflows where AI coding agents do the
same.

I build tools that let coding agents do real engineering work reliably — and I run them that way every day.

Most of what I write now lives in **[Sympoies](https://github.com/sympoies)**: open-source CLIs, runtime policies, and dashboards
for teams of AI coding agents (Claude Code, Codex, local models) working side by side with humans.
The tools are extracted from a private setup where several agents work in parallel under a coordinator, with code review,
test-first gates, release gates, and hands-on acceptance before anything counts as done.

## What I work on

**Agent tooling and runtime**

- [**nils-cli**](https://github.com/sympoies/nils-cli) — a Rust workspace of focused CLIs with automation-first JSON contracts:
  Git helpers (`git-cli`, `git-scope`), forge automation (`forge-cli` for GitHub/GitLab PRs and issues), agent session
  management (`agent-session`), validated commits (`semantic-commit`), API testing (`api-rest`, `api-gql`, `api-grpc`,
  `api-websocket`), evidence and devlog tools, and more. Installable from the [Homebrew tap](https://github.com/sympoies/homebrew-tap).
- [**agent-runtime-kit**](https://github.com/sympoies/agent-runtime-kit) — one shared source of truth for agent skills, hooks,
  and policies across Codex, Claude, and Hermes.
- [**agent-sandbox**](https://github.com/sympoies/agent-sandbox) — a pinned Linux container that validates an agent toolchain
  combination before it reaches real hosts.

**Visibility for humans**

- [**salon**](https://github.com/sympoies/salon) — a self-hostable, container-first chat workspace for working with coding
  agents from a browser: start a session, talk to it, and reconnect to the same session later. Early stage; it already
  powers the shared core of my own agent console.
- [**symphony-board**](https://github.com/sympoies/symphony-board) — a read-only, cross-provider board for GitHub/GitLab issues,
  PRs/MRs, activity, and typed relationships.
- [**host-monitor**](https://github.com/sympoies/host-monitor) — a central, read-only dashboard for Linux host resources,
  services, containers, probes, and journal errors.

**Developer environment**

- [**zsh-kit**](https://github.com/sympoies/zsh-kit) — a modular, self-contained Zsh environment.
- [**night-owl-cli**](https://github.com/sympoies/night-owl-cli) — a synchronized Night Owl theme for the whole terminal.
- [**nils-alfredworkflow**](https://github.com/sympoies/nils-alfredworkflow) — Alfred workflows for macOS.

## What I'm good at

- **Backend and platform architecture** — service boundaries, API and data-model design, and shared backend baselines that
  keep many projects consistent.
- **Data platforms** — Spark, ELK, PostgreSQL, Elasticsearch, and Neo4j pipelines and query systems at billions-of-records scale.
- **Multi-agent engineering workflows** — dispatch, review lanes, merge queues, acceptance, handoff, and recovery when sessions
  stall or get compacted.
- **CLI and contract design** — small composable tools with stable JSON output, typed errors, and deterministic exit codes that
  both people and agents can rely on.
- **Languages** — Rust, TypeScript / Node.js, Go, Java / Spring Boot, Python, Scala, and shell.
- **Cloud-native delivery and CI** — Docker, Kubernetes, AWS, GCP; GitHub Actions and GitLab CI; test-first gates, scoped CI,
  nightly and release validation, Homebrew distribution.
- **Self-hosted infrastructure** — running services, monitoring, and local LLM inference on a small fleet of Linux and macOS hosts.

## How I work

Evidence over claims: an agent saying "done" is a claim; a passing test, a reviewed diff, and a hands-on check are evidence.
Tools should make the right thing the default and explain how to fix the wrong thing.

Interested in agent tooling or want to compare notes? Open an issue or a discussion on any Sympoies repo.
