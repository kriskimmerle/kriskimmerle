# Hey, I'm Kris 👋

I'm obsessed with the messy, practical side of AI governance. The gap between frameworks on paper and systems that work. I build tools to explore that space. Mostly Python, mostly zero-dependency, all open source.

[![Substack](https://img.shields.io/badge/Substack-AI%20Risk%20Praxis-orange?style=flat-square&logo=substack)](https://airiskpraxis.substack.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/kriskimmerle/)

---

## 🤖 AI Agent Security

Tools and frameworks for securing autonomous AI agents. From static analysis to runtime posture scanning.

| Tool | What it does | Rules |
|------|-------------|-------|
| [**agentlint**](https://github.com/kriskimmerle/agentlint) | Security auditor for AGENTS.md / .cursorrules / CLAUDE.md | 19 rules, supply chain focus |
| [**agentscan**](https://github.com/kriskimmerle/agentscan) | Multi-agent permission surface scanner | 9 agents, cross-agent analysis |
| [**agentdrift**](https://github.com/kriskimmerle/agentdrift) | Track changes to agent instruction files via git history | 20 rules, timeline view |
| [**sandboxaudit**](https://github.com/kriskimmerle/sandboxaudit) | Audit AI agent sandbox isolation | 11 rules, runtime probes |
| [**contextaudit**](https://github.com/kriskimmerle/contextaudit) | AI agent instruction quality analyzer | 19 rules, effectiveness focus |
| [**injectguard**](https://github.com/kriskimmerle/injectguard) | Offline prompt injection scanner | 19 rules, risk scoring |
| [**mcplint**](https://github.com/kriskimmerle/mcplint) | MCP configuration security linter | 17 rules, secret detection |

| Framework | What it is |
|-----------|-----------|
| [**secure-openclaw-patterns**](https://github.com/kriskimmerle/secure-openclaw-patterns) | Defense-in-depth security patterns for OpenClaw agents (32 threats, 12 defenses, 90+ item checklist) |
| [**agent-security-patterns**](https://github.com/kriskimmerle/agent-security-patterns) | Platform-agnostic threat model for autonomous AI agents |
| [**staged-autonomy-patterns**](https://github.com/kriskimmerle/staged-autonomy-patterns) | Enterprise-safe autonomous agent governance with HITL gates |

## 🔒 Security Auditors

Static analysis tools that catch misconfigurations before they hit production. All zero-dependency, CI-ready, A-F graded.

| Tool | What it audits | Rules |
|------|---------------|-------|
| [**dockaudit**](https://github.com/kriskimmerle/dockaudit) | Dockerfiles | 27 rules, secret detection |
| [**composeaudit**](https://github.com/kriskimmerle/composeaudit) | docker-compose.yml | 15 rules, 20 dangerous caps |
| [**ghaaudit**](https://github.com/kriskimmerle/ghaaudit) | GitHub Actions workflows | 10 rules, script injection |
| [**ciaudit**](https://github.com/kriskimmerle/ciaudit) | CI/CD pipeline efficiency & cost | 15 rules, cost/speed |
| [**makeaudit**](https://github.com/kriskimmerle/makeaudit) | Makefiles | 17 rules, bashism detection |
| [**sshlint**](https://github.com/kriskimmerle/sshlint) | ~/.ssh/config | 22 rules, weak crypto, key perms |
| [**hookaudit**](https://github.com/kriskimmerle/hookaudit) | Git hooks, .gitattributes, Husky, pre-commit | 18 rules |
| [**apilint**](https://github.com/kriskimmerle/apilint) | OpenAPI/Swagger specs | 20 rules, security focus |
| [**patchaudit**](https://github.com/kriskimmerle/patchaudit) | Git diffs/patches | 14 rules, security-relevant changes |
| [**secretage**](https://github.com/kriskimmerle/secretage) | Secret rotation compliance in .env | 8 rules, SOC2/PCI/HIPAA profiles |
| [**lockaudit**](https://github.com/kriskimmerle/lockaudit) | Package lock files (npm, yarn, poetry, pip, cargo, go) | 14 rules, typosquatting |

## 🛡️ Supply Chain & Code Security

| Tool | What it does |
|------|-------------|
| [**typosafe**](https://github.com/kriskimmerle/typosafe) | Detect typosquatting attacks in Python dependencies |
| [**vibecheck**](https://github.com/kriskimmerle/vibecheck) | Security scanner for AI/vibe-coded Python |
| [**straudit**](https://github.com/kriskimmerle/straudit) | Find invisible chars, homoglyphs, BiDi attacks (Trojan Source) |
| [**busfactor**](https://github.com/kriskimmerle/busfactor) | Code ownership & bus factor analysis for git repos |
| [**dotguard**](https://github.com/kriskimmerle/dotguard) | .env file validator, secret detection, environment differ |
| [**skelcheck**](https://github.com/kriskimmerle/skelcheck) | Python project packaging validator |

## 🔧 Developer Productivity

| Tool | What it does |
|------|-------------|
| [**readmeaudit**](https://github.com/kriskimmerle/readmeaudit) | README quality & completeness auditor (24 rules, auto-detects project type) |
| [**gitdigest**](https://github.com/kriskimmerle/gitdigest) | Git repo activity summarizer with sparklines and contributor stats |
| [**gitaudit**](https://github.com/kriskimmerle/gitaudit) | Git repository health checker (secrets, size, stale branches) |
| [**depfresh**](https://github.com/kriskimmerle/depfresh) | Dependency freshness checker — find stale/abandoned packages |
| [**linkrot**](https://github.com/kriskimmerle/linkrot) | Dead link checker for documentation |
| [**doctest-md**](https://github.com/kriskimmerle/doctest-md) | Test Python code blocks in Markdown files |
| [**confcheck**](https://github.com/kriskimmerle/confcheck) | JSON/YAML/TOML config validator |
| [**migratecfg**](https://github.com/kriskimmerle/migratecfg) | Cross-ecosystem config migration detector (40+ rules) |
| [**migratepy**](https://github.com/kriskimmerle/migratepy) | Python version migration checker (AST-based) |
| [**logparse**](https://github.com/kriskimmerle/logparse) | Structured log analyzer with auto-format detection |
| [**reqdiff**](https://github.com/kriskimmerle/reqdiff) | Package-aware requirements file comparator |
| [**commitlint**](https://github.com/kriskimmerle/commitlint) | Conventional commit message linter |
| [**gitignore-check**](https://github.com/kriskimmerle/gitignore-check) | Smart .gitignore validator |
| [**tokcount**](https://github.com/kriskimmerle/tokcount) | LLM token estimator — 23 models, cost estimation, zero deps |
| [**reexplain**](https://github.com/kriskimmerle/reexplain) | Regex explainer & tester with backtracking detection |
| [**cronparse**](https://github.com/kriskimmerle/cronparse) | Cron expression parser, explainer, and linter |
| [**envlock**](https://github.com/kriskimmerle/envlock) | Requirements completeness auditor |
| [**procspy**](https://github.com/kriskimmerle/procspy) | Single-process deep inspector (files, network, env, children) |
| [**procwatch**](https://github.com/kriskimmerle/procwatch) | Process monitor and resource tracker |
| [**pathaudit**](https://github.com/kriskimmerle/pathaudit) | PATH and environment variable debugger |

## 🌐 Network & HTTP Tools

| Tool | What it does |
|------|-------------|
| [**headercheck**](https://github.com/kriskimmerle/headercheck) | HTTP security header analyzer |
| [**certaudit**](https://github.com/kriskimmerle/certaudit) | SSL/TLS certificate analyzer |
| [**portmap**](https://github.com/kriskimmerle/portmap) | Friendly local port listener display |
| [**portprobe**](https://github.com/kriskimmerle/portprobe) | Port scanner with banner grabbing |
| [**httpecho**](https://github.com/kriskimmerle/httpecho) | HTTP request inspector server |
| [**mockapi**](https://github.com/kriskimmerle/mockapi) | Instant mock REST API from JSON files |
| [**diffapi**](https://github.com/kriskimmerle/diffapi) | API response schema drift detector |

## 📐 Frameworks

| Project | What it is |
|---------|-----------|
| [**rai-framework**](https://github.com/kriskimmerle/rai-framework) | Practical Responsible AI framework with risk tiers, lifecycle gates, and templates |
| [**ralph**](https://github.com/kriskimmerle/ralph) | Minimal, file-based agent loop for autonomous coding |
| [**benchit**](https://github.com/kriskimmerle/benchit) | Python code benchmarking tool with comparison and memory profiling |

---

### Philosophy

Every tool here is **zero-dependency, stdlib-only Python**. Single file. Works everywhere Python runs. No pip install needed. Just download and go.

I write about what I'm learning building RealPage's AI governance program. If you're figuring out AI governance at your org, I'm always happy to compare notes.
