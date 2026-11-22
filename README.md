# Anmol Noor

Software engineer building developer tools, full-stack products, and systems that make software safer to ship.

I like working where product engineering meets systems: turning ideas into useful software, understanding where it can fail, and improving the workflows around it. Lately, I’ve been building local-first coding agents and exploring how they can work independently while staying testable, governed, and under human control.

My work has also taken me through real-time applications, authentication, Web3, and self-hosted infrastructure. The common thread is curiosity, practical automation, and sharing what I learn as I build.

<p align="center">
  <a href="https://www.anmolnoor.com/"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-anmolnoor.com-0EA5E9?style=for-the-badge&logo=googlechrome&logoColor=white"></a>
  <a href="https://www.anmolnoor.com/blog"><img alt="Blog" src="https://img.shields.io/badge/Blog-Writing-FF5A1F?style=for-the-badge&logo=rss&logoColor=white"></a>
  <a href="https://cal.com/anmolnoor"><img alt="Book a call" src="https://img.shields.io/badge/Book%20a%20call-Cal.com-22C55E?style=for-the-badge&logo=caldotcom&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/anmolnoor/"><img alt="LinkedIn Anmol Noor" src="https://img.shields.io/badge/LinkedIn-Anmol%20Noor-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"></a>
  <a href="mailto:anmolnoor59@gmail.com"><img alt="Email Anmol Noor" src="https://img.shields.io/badge/Email-anmolnoor59-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
</p>

## What I’m working on now

- [skep](https://github.com/Anmolnoor/skep): a local-first supervisor for AI coding agents, with sandboxed workers, independent re-verification, and human approval. It’s shipped: MIT-licensed, [on PyPI](https://pypi.org/project/skep/) (`pip install skep`), at [v1.6.0](https://github.com/Anmolnoor/skep/releases), with docs at [skep.anmolnoor.com](https://skep.anmolnoor.com/). Recent releases added:
  - running skep from your phone as one conversation across Telegram, Discord, and Slack — including HIGH-risk approvals and `/update`;
  - governing ACP agents running inside other clients;
  - a policy you can browse like Group Policy, with a plain explanation for each rule;
  - schedules that can only narrow what their workers may do;
  - a Telegram alarm when an email carries an injection attempt;
  - research, YouTube, and a daily mail summary that work from your phone.
- [my-ai-ide](https://github.com/Anmolnoor/my-ai-ide): my IDE for the AI era. It isn't an editor: it's T3 Code running Claude Code and Codex side by side, plugins and skills that set how they plan, code, review, and ship, a lockfile that records the setup, and a weekly task that checks for drift and proposes upgrades. It also has the skills I wrote, with hard gates like no code before a failing test.
- [AuthWAPI](https://github.com/Anmolnoor/authwapi): WorkOS-style self-hosted auth for localhost — one `docker run`, one portable data folder, hosted sign-in/sign-up pages, passkeys, 2FA, OAuth 2.1/OIDC, organizations, and a built-in admin MCP server (early development).
- [Foundation CLI](https://github.com/Anmolnoor/fcli): a shell-native coding agent built in public.
- [Beekeeper](https://github.com/Anmolnoor/beekeeper), [agent-policy-gate](https://github.com/Anmolnoor/agent-policy-gate), and [agent-task-contract](https://github.com/Anmolnoor/agent-task-contract): ways to govern agent tools, review their work, keep useful audit trails, and hand tasks between a supervisor and disposable workers.
- A homelab of 12 services on Proxmox, with Tailscale, shared storage, monitoring, and automation. Two laptops share the agent work and run tests in parallel. Write-ups: [current setup](https://www.anmolnoor.com/blog/homelab-current-setup), [Tailscale remote access](https://www.anmolnoor.com/blog/tailscale-homelab-remote-access), and [auto-updating containers with Watchtower](https://www.anmolnoor.com/blog/auto-updating-docker-containers-watchtower).

## Selected work

| Project | What it does |
| --- | --- |
| [skep](https://github.com/Anmolnoor/skep) | Supervises AI coding agents with sandboxing, verification, and approval gates. |
| [my-ai-ide](https://github.com/Anmolnoor/my-ai-ide) | T3 Code + Claude Code + Codex setup with plugins, skills, lockfile, and weekly drift checks. |
| [Foundation CLI](https://github.com/Anmolnoor/fcli) | A local-first, shell-native coding agent and engineering workflow experiment. |
| [Beekeeper](https://github.com/Anmolnoor/beekeeper) | A governed runtime for multi-agent workflows. |
| [agent-policy-gate](https://github.com/Anmolnoor/agent-policy-gate) | Policy, review, and audit primitives for agent tool calls. |
| [AuthWAPI](https://github.com/Anmolnoor/authwapi) | WorkOS-style self-hosted auth for localhost with hosted pages, passkeys, 2FA, OAuth 2.1/OIDC, organizations, and an admin MCP server. |
| [HoldIt](https://github.com/Anmolnoor/hold-it) | A macOS menu bar utility for collecting files with drag and drop. |
| [a2j](https://github.com/Anmolnoor/a2j) | A Chrome extension and local Python service that tailor resumes and cover letters to a job page. |
| [skep-benchmarks](https://github.com/Anmolnoor/skep-benchmarks) | A benchmark suite for LLM coding on realistic software engineering tasks. |
| [claude-dotfiles](https://github.com/Anmolnoor/claude-dotfiles) and [scripts](https://github.com/Anmolnoor/scripts) | A portable Claude Code setup and shell scripts for the same dev environment on every machine. |

I’ve also built products including Amend Notes and [Vendro](https://www.anmolnoor.com/vendro), plus experiments in real-time software and Solana. The [projects page](https://www.anmolnoor.com/projects) has more, including older learning projects.

## Open source contributions

- [GreenGateway](https://github.com/Greenhat-Security/GreenGateway) (Rust): [cut security mutation-test rebuilds from 160–250s to 17–29s](https://github.com/Greenhat-Security/GreenGateway/pull/816) (measured locally) with incremental builds and parallel jobs, [made the test suite compile on macOS](https://github.com/Greenhat-Security/GreenGateway/pull/815), and [cleared four RustSec advisories](https://github.com/Greenhat-Security/GreenGateway/pull/814).

## Find your people

If you’re interested in local-first software, coding agents, agent safety, developer workflows, or homelabs, I’d be glad to compare notes or build together. I also enjoy talking about turning an early idea into a dependable product.

If you’re hiring for software engineering work across full-stack products, systems, or developer tools, the [portfolio](https://www.anmolnoor.com/) and selected projects are a good place to start. You can reach me through [LinkedIn](https://www.linkedin.com/in/anmolnoor/) or [email](mailto:anmolnoor59@gmail.com).

## Writing

- [Restarting the Gateway That Was Running Me](https://www.anmolnoor.com/blog/restarting-the-gateway-that-was-running-me)
- [My Two Laptops Tied. Then I Ran the Tests in Parallel.](https://www.anmolnoor.com/blog/two-laptops-parallel-tests)
- [I Thought skep Had a Policy Engine](https://www.anmolnoor.com/blog/skep-one-policy-engine)
- [Local LLMs Are Catching Up Fast, If Your Hardware Can Keep Up](https://www.anmolnoor.com/blog/local-llms-catching-up)
- [I’m Live — Come Build with Me](https://www.anmolnoor.com/blog/skep-is-live)
- [The Queen, the Workers, and the Group Policy Object](https://www.anmolnoor.com/blog/beekeeper-fcli-skep-journey)

More on [the blog](https://www.anmolnoor.com/blog).

## Tools and technologies

TypeScript · React · Next.js · Astro · Node.js · Python · Rust · Swift · PostgreSQL · MongoDB · WebRTC · Solana · Docker · Proxmox · Tailscale · Prometheus · Grafana · Ollama · Claude Code

---

![Snake animation](https://raw.githubusercontent.com/Anmolnoor/Anmolnoor/output/snake/github-contribution-grid-snake.svg)

<!-- If you switch services in the future, check for a 'base' or 'offset' parameter to carry over your count (Current base: 4265) -->
<p align="center">
  <img alt="Profile visitors" src="https://komarev.com/ghpvc/?username=Anmolnoor&label=visitors&color=0e75b6&style=flat&base=4265">
  <a href="https://github.com/Anmolnoor?tab=followers"><img alt="GitHub followers" src="https://img.shields.io/github/followers/Anmolnoor?label=Followers&style=social"></a>
</p>

Profile sources and editorial notes: [PROFILE_CONTEXT.md](PROFILE_CONTEXT.md)
