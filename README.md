# House of Vibes 🛋️ — A Field Guide to Vibe Coding, AI IDEs & Agent Tooling

A curated, living list of real communities, tools, and learning resources for anyone building software with AI — whether you've never written a line of code, you're a hobbyist "explorer," or you're a professional engineer adopting agentic tools.

> **Last verified:** July 2026. Tool pricing, Discord member counts, and blog-sourced comparisons change fast — treat anything without an official source link as a starting point for your own research, not gospel. See [Contributing](#contributing--keeping-this-list-active) if you spot something stale or missing.

## Table of Contents

- [Featured Community: House of Vibes](#featured-community-house-of-vibes)
- [What Is "Vibe Coding"?](#what-is-vibe-coding)
- [Communities: Discord, Slack, Reddit & Forums](#communities-discord-slack-reddit--forums)
- [Live Events & Meetups](#live-events--meetups)
- [Learn to Vibe Code: Getting Started](#learn-to-vibe-code-getting-started)
- [IDEs & Tools](#ides--tools)
  - [Primary AI IDEs (Desktop)](#primary-ai-ides-desktop)
  - [Cloud / Browser IDEs & No-Code App Builders](#cloud--browser-ides--no-code-app-builders)
  - [Editor Extensions & Secondary Tools](#editor-extensions--secondary-tools)
  - [CLI & Terminal Coding Agents](#cli--terminal-coding-agents)
  - [Model Access, Routing & Local Models](#model-access-routing--local-models)
- [Connectors, MCP & OAuth for Your Agent](#connectors-mcp--oauth-for-your-agent)
- [Security Topics](#security-topics)
- [Agent Skills: Getting Started](#agent-skills-getting-started)
- [Books & Further Reading](#books--further-reading)
- [Contributing / Keeping This List Active](#contributing--keeping-this-list-active)

---

## Featured Community: House of Vibes

🏠 **[houseofvibes.app](https://houseofvibes.app/)** — a free, Discord-based community for AI builders, founders, and creators: "Build Together. Vibe Together." Runs a daily builder hangout, weekly demo days, a project showcase channel, and a gamified XP leaderboard. Join via the "Enter the House" link on the site.

---

## What Is "Vibe Coding"?

Replit's own docs give the clearest definition of the term: you start from a **plain-language description of what you want**, not code, and work in a loop of *describe → preview → give feedback → publish*. Critically, Replit is explicit that **you don't have to be a developer to do this** — your job is closer to a product lead who directs goals, audience, and taste, while the AI agent handles the actual code generation, debugging, and iteration.

- 📖 [Vibe Coding 101 — Replit Docs](https://docs.replit.com/learn/foundations/vibe-coding-101) *(official, free)*

That framing matters for this guide: it's written so a complete beginner, a non-technical "explorer," and a professional engineer can all find their on-ramp.

---

## Communities: Discord, Slack, Reddit & Forums

### Discord servers

Member counts are live snapshots pulled from Discord's public invite API on July 17, 2026, and will drift over time.

**AI labs & model providers**

| Community | Link | Members | Why join |
|---|---|---|---|
| OpenAI | [discord.gg/openai](https://discord.gg/openai) | ~852,000 | Official server — ChatGPT, Codex, and OpenAI's latest models. Requires verifying an OpenAI account to fully join. |
| Claude | [discord.gg/6PPFFzqPDZ](https://discord.gg/6PPFFzqPDZ) | ~115,000 | Large, active Claude/Anthropic-focused community. **Note:** the commonly-cited `discord.gg/anthropic` invite is dead/expired as of this writing — this is the verified working link. |
| Nous Research | [discord.gg/nousresearch](https://discord.gg/nousresearch) | ~127,000 | Open-source AI community behind the Hermes model family |
| Hugging Face | [discord.gg/hugging-face-879548962464493619](https://discord.gg/hugging-face-879548962464493619) | ~227,000 | The ML/model-hub community — verify to link your HF Hub account |
| Midjourney | [discord.gg/midjourney](https://discord.gg/midjourney) | ~18,800,000 | Official server for the text-to-image AI |

**Vibe coding & AI dev tools**

| Community | Link | Members | Why join |
|---|---|---|---|
| Cursor | [discord.gg/cursor](https://discord.gg/cursor) | ~38,000 | Official Cursor server — people building with AI, real-time help |
| Cline | [discord.gg/cline](https://discord.gg/cline) | ~23,000 | Community for the open-source Cline VS Code agent |
| Lovable | [discord.gg/lovable-dev](https://discord.gg/lovable-dev) | ~172,000 | Vibe-coding / AI app-building community around the Lovable platform |
| OpenClaw (Clawdbot) — *"Friends of the Crustacean"* | [discord.gg/clawd](https://discord.gg/clawd) | ~176,000 | Personal-AI-agent project, now a 501(c)(3) nonprofit foundation |

**Builder, founder & startup communities**

| Community | Link | Members | Why join |
|---|---|---|---|
| Furlough | [discord.gg/furlough](https://discord.gg/furlough) | ~55,000 | Entrepreneurs collaborating on marketing, e-commerce, startups, AI |
| Tech Startups | [discord.gg/startups](https://discord.gg/startups) | ~19,700 | Business-focused technologists building in public together |

**Learn to code**

| Community | Link | Members | Why join |
|---|---|---|---|
| freeCodeCamp | [discord.gg/freecodecamp-692816967895220344](https://discord.gg/freecodecamp-692816967895220344) | ~41,500 | Official freeCodeCamp.org server — learn to code, get help |

### Reddit

- [r/vibecoding](https://www.reddit.com/r/vibecoding/) — general vibe coding discussion, project showcases
- [r/ChatGPTCoding](https://www.reddit.com/r/ChatGPTCoding/) — AI-assisted coding across tools, not just ChatGPT
- [r/cursor](https://www.reddit.com/r/cursor/) — Cursor-specific
- [r/LocalLLaMA](https://www.reddit.com/r/LocalLLaMA/) — local/offline LLM setups (relevant if you want to run models yourself)

### Web forums & communities

- [Vibe Coding Forem](https://vibe.forem.com/) — dedicated discussion forum
- [Vibehackers](https://vibehackers.io/) — gallery/job board + community for vibe-coded projects
- [Vibe Coding Community (GitHub)](https://github.com/Vibe-Coding-Community) — GitHub-based community org
- [Indie Hackers](https://www.indiehackers.com/) — broader solo/small-team founder community, heavy AI-building overlap
- [Product Hunt — AI topic](https://www.producthunt.com/topics/artificial-intelligence) — where a lot of vibe-coded products launch and get feedback
- [Hacker News](https://news.ycombinator.com/) — not vibe-coding-specific, but where the ecosystem's biggest debates happen

### A note on Slack

Despite a deliberate search, we could **not confirm a dedicated, active Slack workspace specifically for vibe coding** — the two most actively-maintained community lists in this space ([taskade/awesome-vibe-coding](https://github.com/taskade/awesome-vibe-coding), [filipecalegario/awesome-vibe-coding](https://github.com/filipecalegario/awesome-vibe-coding)) both list multiple Discord servers but zero Slack workspaces. If your workflow leans Slack rather than Discord:

- [Slack's own developer/agent-builder community](https://slack.dev/) covers building *on* Slack (Agent Builder, MCP integration) rather than vibe coding generally, but is a real, active dev community if you're building Slack-native agents.
- Adjacent no-code communities (several run their own Slack groups): [No Code Founders](https://nocodefounders.com/), [WeAreNoCode](https://www.wearenocode.com/), [Zerocoder](https://zerocoder.com/no-code-community/), [NoCodeOps](https://www.nocodeops.com/community).

If you know of an active, vibe-coding-specific Slack workspace, please open an issue or PR — this is a known gap, not an oversight.

---

## Live Events & Meetups

SF Bay Area–based Meetup groups worth joining, verified directly against their group pages. Most run primarily **virtual/online** sessions (so they're joinable from anywhere); one (Hacker Dojo, at the bottom) is an in-person-only physical space.

- **[Microsoft Reactor San Francisco](https://www.meetup.com/microsoft-reactor-san-francisco/)** — ~7,400 members, 4.3★ (1,420 ratings). Microsoft's own free technical-learning program ("centers for free technical learning and sharing"), run by Microsoft as Super Organizer alongside 13 co-organizers. Covers AI, cloud computing, open source, and startups. By far the most active group here: **virtual events run continuously** ("anytime, anywhere"), with dozens of events scheduled at any given time and 2,600+ run historically. Recurring series include the monthly **"SF AI Show + Tell"** (demos + talks, hosted at GitHub HQ SF) and the periodic **"AI Innovation Summit SF"** (keynotes, panels, workshops). Contact `ReactorSF@Microsoft.com` for space/collab inquiries.
- **[AI Builders and Learners SF](https://www.meetup.com/ai-builders-and-learners-sf/)** — ~2,900 members, 4.7★ (149 reviews). "A passionate community dedicated to building and learning about artificial intelligence," covering ML, LLMs, deep learning, MLOps, Python, computer vision, and NLP. Runs a **weekly virtual "AI Build & Learn" stream** (Fridays, 12:00 PM PDT) on rotating topics, plus a **monthly AI book club**. Organized by Sage Elliott; hosts both SF-local and fully virtual sessions.
- **[Silicon Valley Generative AI ~ The AI Collective Network](https://www.meetup.com/silicon-valley-generative-ai/)** — ~4,600 members, 4.5★ (350 reviews). A generative-AI-focused community for professionals, researchers, and founders, part of The AI Collective network. Runs **bi-weekly virtual paper-reading sessions** (in partnership with Boulder Data Science) plus **monthly talks** from researchers, founders, and practitioners covering technical topics, applications, and startup pitches. Organized by Matt White.
- **[Bay Area Content Marketing](https://www.meetup.com/bay-area-content-marketing/)** — ~4,200 members, 4.8★ (1,026 reviews), running since 2015. A general marketing (not AI-specific) community that has leaned increasingly into AI-assisted content workflows in its programming. Mixes **virtual talks** with occasional **in-person Bay Area networking events**. Organized by Dennis Shiao. Worth it if your vibe-coding projects lean toward content, marketing, or growth tooling rather than pure engineering.
- **[Hacker Dojo](https://www.meetup.com/hackerdojo/)** — ~19,400 members, 4.7★ (3,107 reviews). **In-person only** — a 501(c)(3) nonprofit hackerspace/community center at 855 Maude Ave, Mountain View, CA, open 24/7. "A location for Startups, Events, Lectures, Hackathons, DevHouses, tinkering, brainstorming, co-working, and more." Extremely active: over a hundred events scheduled at any given time (2,500+ run historically), plus recurring staples like a weekly Happy Hour and Friday Night Socials. Good pick if you're actually in the Bay Area and want in-person building company rather than a virtual talk.

Note: Microsoft Reactor SF and Hacker Dojo both had dozens of events on their public calendars at the time of writing; AI Builders and Learners SF, Silicon Valley Generative AI, and Bay Area Content Marketing did not have near-term events listed at the moment we checked. Meetup groups post new events on a rolling basis rather than far in advance, so check each group's page directly for the next scheduled date.

---

## Learn to Vibe Code: Getting Started

- 📖 [Vibe Coding 101 — Replit Docs](https://docs.replit.com/learn/foundations/vibe-coding-101) *(official, free, best starting point)* — the describe → preview → feedback → publish loop, written for non-developers.
- 🎓 [Vibe Coding 101 with Replit — DeepLearning.AI](https://www.deeplearning.ai/short-courses/vibe-coding-101-with-replit/) *(free short course)* — hands-on, built with Replit. Note: we could not independently confirm marketing claims that it's tailored for people with *zero* prior coding vocabulary, so if you are a true beginner, expect some ramp-up rather than a hand-held zero-to-hero path.
- 📖 [DataCamp: Vibe Coding Guide for Beginners](https://www.datacamp.com/blog/vibe-coding-guide-for-beginners) — useful for the underlying taxonomy of tool types (see below), less so as a step-by-step tutorial.

**Honest gap:** we specifically looked for a course genuinely designed for complete non-technical beginners and couldn't verify one exists as advertised. Best current path for a true beginner: start with Replit's free docs above, pick one small real project (not a tutorial), and use the Discord/Reddit communities above when you get stuck.

---

## IDEs & Tools

A rough taxonomy (per [DataCamp](https://www.datacamp.com/blog/vibe-coding-guide-for-beginners)) that's useful for orienting yourself: **agent-based tools** that generate/modify whole projects (Claude Code, Replit Agent), **IDE-integrated assistants** bolted onto an existing editor (GitHub Copilot), **chat-based tools** (ChatGPT, Claude.ai), and **local/offline LLM setups** (Ollama, LM Studio). The lists below are a curated starting set, not exhaustive — for the long tail (200+ tools), see the two awesome-lists linked at the bottom of this section.

### Primary AI IDEs (Desktop)

| IDE | Link | Notes |
|---|---|---|
| Cursor | [cursor.com](https://cursor.com) | VS Code fork, currently the most widely benchmarked AI-first editor |
| Windsurf | [windsurf.com](https://windsurf.com/) | VS Code fork; per [Zapier's comparison](https://zapier.com/blog/windsurf-vs-cursor/), its agent tends to make more decisions autonomously rather than requiring approval at every step — often recommended for non-technical "vibe coders" for that reason |
| Zed | [zed.dev](https://zed.dev/) | High-performance, Rust-based, built-in AI |
| Trae | [trae.ai](https://www.trae.ai/) | Free AI IDE from ByteDance |
| Amazon Kiro | [kiro.dev](https://kiro.dev) | Spec-driven agentic IDE from AWS |
| Google Antigravity | [antigravity.google](https://antigravity.google/) | Google's agentic IDE (launched Nov 2025) |
| Void | [voideditor.com](https://voideditor.com/) | Open-source Cursor alternative |
| PearAI | [trypear.ai](https://trypear.ai/) | Open-source AI IDE |

### Cloud / Browser IDEs & No-Code App Builders

| Tool | Link | Notes |
|---|---|---|
| Replit | [replit.com](https://replit.com) | Zero-setup, free-tier cloud IDE — the best on-ramp for learners per most comparisons |
| Firebase Studio | [firebase.studio](https://firebase.studio/) | Google's cloud AI app-building environment |
| Bolt.new | [bolt.new](https://bolt.new) | Prompt-to-full-stack-app in the browser (StackBlitz) |
| Lovable | [lovable.dev](https://lovable.dev) | Popular for quickly shipping web apps from a prompt |
| v0 by Vercel | [v0.dev](https://v0.dev) | Great for generating React/UI components from a prompt |
| Base44 | [base44.com](https://base44.com) | Prompt-to-app builder |
| Google AI Studio | [aistudio.google.com](https://aistudio.google.com/) | Free, Gemini-based prototyping |
| Figma Make | [figma.com/make](https://www.figma.com/make/) | Design-to-app in Figma |

### Editor Extensions & Secondary Tools

| Tool | Link | Notes |
|---|---|---|
| GitHub Copilot | [github.com/features/copilot](https://github.com/features/copilot) | The most widely-used AI coding assistant; integrates into VS Code/JetBrains rather than being a standalone editor |
| Cline | [cline.bot](https://cline.bot/) | Open-source autonomous coding agent for VS Code |
| Roo Code | [roocode.com](https://roocode.com/) | Cline fork with extra agent/orchestration features |
| Continue | [continue.dev](https://continue.dev/) | Open-source, model-agnostic AI coding extension |
| Sourcegraph Cody | [sourcegraph.com/cody](https://sourcegraph.com/cody) | Codebase-aware assistant, strong for large/legacy codebases |
| Supabase | [supabase.com](https://supabase.com/) | Not an IDE — the most commonly paired AI-friendly backend/database for vibe-coded apps |

### CLI & Terminal Coding Agents

| Tool | Link | Notes |
|---|---|---|
| Claude Code | [github.com/anthropics/claude-code](https://github.com/anthropics/claude-code) | Anthropic's terminal-based agentic coding tool |
| OpenAI Codex CLI | [github.com/openai/codex](https://github.com/openai/codex) | OpenAI's terminal coding agent |
| Gemini CLI | [github.com/google-gemini/gemini-cli](https://github.com/google-gemini/gemini-cli) | Google's terminal coding agent |
| Aider | [aider.chat](https://aider.chat/) | Long-running open-source pair-programming CLI, model-agnostic |
| Goose | [github.com/block/goose](https://github.com/block/goose) | Block's open-source terminal agent |
| OpenCode | [opencode.ai](https://opencode.ai/) | Open-source terminal coding agent |

**For the long tail:** both [taskade/awesome-vibe-coding](https://github.com/taskade/awesome-vibe-coding) and [filipecalegario/awesome-vibe-coding](https://github.com/filipecalegario/awesome-vibe-coding) are actively maintained GitHub lists covering hundreds of additional tools — website builders, UI generators, automation platforms (Zapier, Make, n8n), agent frameworks (LangChain, CrewAI), and more.

### Model Access, Routing & Local Models

| Tool | Link | Notes |
|---|---|---|
| OpenRouter | [openrouter.ai](https://openrouter.ai) | Unified, OpenAI-compatible API gateway to 400+ models (GPT, Claude, Gemini, DeepSeek, Qwen, Llama, and more) behind one API key — useful for comparing or switching models without juggling separate provider accounts. Includes a rotating set of free-tier models. |
| Ollama | [ollama.com](https://ollama.com/) | The simplest way to run open-weight models locally, including Chinese open-weight models, e.g. `ollama run qwen3.5`, `ollama run deepseek-v3.2`, `ollama run glm-5` |
| LM Studio | [lmstudio.ai](https://lmstudio.ai/) | GUI alternative to Ollama for running local models, if you'd rather not use the command line |

**Guides to running Chinese open-weight models:** DeepSeek (Apache/MIT), Qwen (Alibaba, Apache 2.0), Kimi (Moonshot AI), and GLM (Zhipu AI) are all open-weight and can be run locally or via API — trading cloud convenience for data privacy and, for the smaller distilled variants, much lower cost:

- [The Best Chinese Open-Weight Models — Understanding AI](https://www.understandingai.org/p/the-best-chinese-open-weight-models) — a grounded, non-hype comparison of DeepSeek, Qwen, Kimi, and GLM against their US counterparts.
- [Ollama's model library](https://ollama.com/library) — search "qwen," "deepseek," "kimi," or "glm" to see available local model sizes and hardware requirements before downloading. Check sizes first: full flagship checkpoints can run 600GB+; most people should start with a smaller distilled variant that actually fits their machine.

**Already covered elsewhere in this guide:** [Replit](#cloud--browser-ides--no-code-app-builders) and [Lovable](#cloud--browser-ides--no-code-app-builders) under Cloud/Browser IDEs, [OpenCode](#cli--terminal-coding-agents) under CLI agents.

---

## Connectors, MCP & OAuth for Your Agent

Most modern AI coding agents connect to your other tools (databases, GitHub, Slack, your file system) via the **Model Context Protocol (MCP)** — an open standard, originally from Anthropic, now supported across Anthropic, OpenAI, Google, and Microsoft tooling.

### How authorization works

Per the [official MCP specification](https://modelcontextprotocol.io/specification/2025-06-18/basic/authorization):

- Authorization is **optional** overall in MCP.
- When a server supports it: HTTP-based transports **should** use the OAuth-based authorization spec; local (STDIO) transports **should not** — they pull credentials from the environment instead.
- Servers that do support OAuth **must** implement [OAuth 2.0 Protected Resource Metadata (RFC 9728)](https://www.rfc-editor.org/rfc/rfc9728), and clients **must** use it to discover the right authorization server.

### Connecting a tool to your agent (worked example: Claude)

Per [Anthropic's own support docs](https://support.claude.com/en/articles/11175166-get-started-with-custom-connectors-using-remote-mcp):

1. Go to **Settings → Connectors** (Pro/Max) or **Organization settings → Connectors** (Team/Enterprise).
2. Click **+ → Add custom connector**.
3. Enter your remote MCP server URL.
4. Open **Advanced settings** to add an OAuth Client ID (and secret, if required).
5. Complete the OAuth flow when prompted — this authorizes access without ever handing your actual password to the agent.

Also see: [MCP connector — Claude Platform Docs](https://platform.claude.com/docs/en/agents-and-tools/mcp-connector).

### Where to find MCP servers/connectors

| Directory | Link | Notes |
|---|---|---|
| Official MCP Registry | [registry.modelcontextprotocol.io](https://registry.modelcontextprotocol.io) | Anthropic-maintained, community-contributed |
| Official MCP servers (GitHub) | [github.com/modelcontextprotocol/servers](https://github.com/modelcontextprotocol/servers) | Reference implementations |
| Smithery | [smithery.ai](https://smithery.ai/servers) | Registry + hosting; install via CLI or run hosted |
| PulseMCP | [pulsemcp.com](https://www.pulsemcp.com/servers) | Large, hand-reviewed directory |
| Glama | [glama.ai](https://glama.ai/mcp/servers) | Broad automated coverage |
| awesome-mcp-servers | [github.com/wong2/awesome-mcp-servers](https://github.com/wong2/awesome-mcp-servers) | Community-curated list |
| MCP Inspector | [github.com/modelcontextprotocol/inspector](https://github.com/modelcontextprotocol/inspector) | Official debugging tool for testing servers you build/connect |

---

## Security Topics

Connecting an agent to real accounts and data is the highest-stakes part of this whole workflow. A few load-bearing facts:

### MCP auth secures the *connection*, not your API

Per [Curity's write-up on the spec](https://curity.io/resources/learn/design-mcp-authorization-apis/), MCP-based authorization only secures the client-server connection — it does **not** replace proper API-level authorization checks. If you're building a server, you still need to secure your own API independently.

### A real, critical CVE in the ecosystem

**CVE-2025-6514** (CVSS **9.6**, critical) was a pre-authentication remote code execution vulnerability in `mcp-remote`, a widely-used proxy for connecting MCP clients to remote servers — estimated to affect **437,000+ installs**. Root cause: the proxy failed to sanitize a malicious server's `authorization_endpoint` URL, leading to OS command injection. Affected versions 0.0.5–0.1.15; fixed in 0.1.16.

- [JFrog's original research](https://research.jfrog.com/vulnerabilities/mcp-remote-command-injection-rce-jfsa-2025-001290844)
- [NVD entry](https://nvd.nist.gov/vuln/detail/CVE-2025-6514)

**Takeaway:** only connect to MCP servers you trust, keep client libraries (like `mcp-remote`) updated, and treat "just paste this server URL into your agent" instructions from random READMEs with real skepticism.

### A practical checklist

Drawing from [OWASP's AI Agent Security Cheat Sheet](https://cheatsheetseries.owasp.org/cheatsheets/AI_Agent_Security_Cheat_Sheet.html) and current agent-security guidance:

- **Least privilege by default:** scope OAuth grants and tool permissions to the minimum needed for the task — don't hand an agent a token with `write`/`delete` scopes it doesn't need.
- **Short-lived, scoped credentials over static API keys** wherever the tool supports it.
- **Human-in-the-loop on irreversible actions** (deletes, sends, payments, force-pushes).
- **Default-deny tool access** — an agent should have to be explicitly granted a tool/connector, not get it by default.
- **Review any connector/OAuth grant that includes write scopes** before turning it on, especially for connectors you didn't author yourself.
- **Log agent actions** the same way you'd log a human user's actions on sensitive systems — you need an audit trail if something goes wrong.

---

## Agent Skills: Getting Started

"Skills" (Anthropic's term; the concept is spreading across the ecosystem) are packaged, reusable instructions/scripts an agent can pull in for a specific kind of task.

### How to build your first one (Claude Code)

Per [Anthropic's official docs](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/overview): a custom Skill is just a directory containing a `SKILL.md` file, placed in `~/.claude/skills/` (personal, available everywhere) or `.claude/skills/` (project-scoped). No API upload needed — Claude discovers and uses it automatically.

### Free official course

🎓 [Introduction to Agent Skills](https://anthropic.skilljar.com/introduction-to-agent-skills) — free, Anthropic-run, six modules: *What are skills?* → *Creating your first skill* → *Configuration and multi-file skills* → *Skills vs. other Claude Code features* → *Sharing skills* → *Troubleshooting skills*.

### Pre-built Skills you can use today

Anthropic ships four pre-built Skills via the API for document work — PowerPoint, Excel, Word, and PDF generation/editing. See the [quickstart](https://platform.claude.com/docs/en/agents-and-tools/agent-skills/quickstart) and the [public Skills repo](https://github.com/anthropics/skills).

### Security note

Anthropic's own guidance is explicit: **only use Skills from trusted sources.** A malicious Skill's instructions or bundled code can direct an agent to misuse tools or execute code beyond its stated purpose — including data exfiltration or unauthorized system access. Treat an unfamiliar Skill the way you'd treat an unfamiliar npm package: read it before you run it.

---

## Books & Further Reading

Two books survived scrutiny as genuinely credible (real, established authors; real publishers):

- **[*Vibe Coding: Building Production-Grade Software With GenAI, Chat, Agents, and Beyond*](https://itrevolution.com/product/vibe-coding-book/)** — Gene Kim & Steve Yegge (IT Revolution, foreword by Anthropic's Dario Amodei). Aimed broadly — experienced developers, technical leaders, and newcomers — with a focus on building *production-grade* software, not just prototypes.
- **[*Beyond Vibe Coding: From Coder to AI-Era Developer*](https://www.oreilly.com/library/view/beyond-vibe-coding/9798341634749/)** — Addy Osmani (O'Reilly). Written for developers and tech leads moving from "vibe coding" prototypes toward professional, production AI-assisted engineering practice. Reviews are mixed but generally positive from experienced practitioners; less suited to absolute beginners.

**A caution:** a search for beginner-oriented vibe-coding books turned up a wave of same-year, formulaic "Vibe Coding for Beginners 2026" titles from self-published/print-on-demand imprints with no verifiable track record. We're deliberately **not** recommending any of them here — we couldn't establish they're worth your money over the free official docs and courses linked above. If you've read one and it's genuinely good, open a PR.

---

## Contributing / Keeping This List Active

This is meant to be a **living document** — links rot, Discords go quiet, and new tools ship constantly. If you find something outdated or missing:

1. Open an issue or PR with the specific change.
2. Prefer linking to **official/primary sources** (vendor docs, official Discord invites) over third-party blog roundups.
3. If you're adding a community, note roughly how active it is (member count, last message you saw) so future readers can judge freshness.

Known open gaps as of this writing (see above): no confirmed dedicated Slack workspace for vibe coding, and no verified truly-beginner-friendly paid course or book — both are genuinely worth filling in if you find something real.
