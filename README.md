# Hey, I'm Kris 👋

I'm obsessed with the messy, practical side of AI governance. The gap between frameworks on paper and systems that work. I build tools to explore that space. Mostly Python, mostly zero-dependency, all open source.

[![Substack](https://img.shields.io/badge/Substack-AI%20Risk%20Praxis-orange?style=flat-square&logo=substack)](https://airiskpraxis.substack.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/kriskimmerle/)

---

## 🔒 Security Auditors

Static analysis tools that catch misconfigurations before they hit production. All zero-dependency, CI-ready, A-F graded.

| Tool | What it audits | Rules |
|------|---------------|-------|
| [**injectguard**](https://github.com/kriskimmerle/injectguard) | Prompt injection in text/files | 19 rules, risk scoring |
| [**agentlint**](https://github.com/kriskimmerle/agentlint) | AGENTS.md / CLAUDE.md / .cursorrules | 19 rules, supply chain focus |
| [**mcplint**](https://github.com/kriskimmerle/mcplint) | MCP server configs (Claude Desktop, Cursor, VS Code) | 17 rules, secret detection |
| [**hookaudit**](https://github.com/kriskimmerle/hookaudit) | Git hooks, .gitattributes, .git/config, Husky, pre-commit | 18 rules |
| [**dockaudit**](https://github.com/kriskimmerle/dockaudit) | Dockerfiles | 27 rules, secret detection |
| [**composeaudit**](https://github.com/kriskimmerle/composeaudit) | docker-compose.yml | 15 rules, 20 dangerous caps |
| [**ghaaudit**](https://github.com/kriskimmerle/ghaaudit) | GitHub Actions workflows | 10 rules, script injection |
| [**makeaudit**](https://github.com/kriskimmerle/makeaudit) | Makefiles | 17 rules, bashism detection |
| [**sshlint**](https://github.com/kriskimmerle/sshlint) | ~/.ssh/config | 22 rules, weak crypto, key perms |
| [**ciaudit**](https://github.com/kriskimmerle/ciaudit) | CI/CD pipeline efficiency | 15 rules, cost/speed |
| [**secretage**](https://github.com/kriskimmerle/secretage) | Secret rotation compliance in .env | 8 rules, SOC2/PCI/HIPAA profiles |

## 🛡️ Supply Chain & Code Security

| Tool | What it does |
|------|-------------|
| [**typosafe**](https://github.com/kriskimmerle/typosafe) | Detect typosquatting attacks in Python dependencies |
| [**vibecheck**](https://github.com/kriskimmerle/vibecheck) | Security scanner for AI/vibe-coded Python |
| [**straudit**](https://github.com/kriskimmerle/straudit) | Find invisible chars, homoglyphs, BiDi attacks (Trojan Source) |
| [**busfactor**](https://github.com/kriskimmerle/busfactor) | Code ownership & bus factor analysis for git repos |
| [**dotguard**](https://github.com/kriskimmerle/dotguard) | .env file validator, secret detection, environment differ |

## 🔧 Developer Productivity

| Tool | What it does |
|------|-------------|
| [**depfresh**](https://github.com/kriskimmerle/depfresh) | Dependency freshness checker — find stale/abandoned packages |
| [**linkrot**](https://github.com/kriskimmerle/linkrot) | Dead link checker for documentation |
| [**confcheck**](https://github.com/kriskimmerle/confcheck) | JSON/YAML/TOML config validator |
| [**logparse**](https://github.com/kriskimmerle/logparse) | Structured log analyzer with auto-format detection |
| [**reqdiff**](https://github.com/kriskimmerle/reqdiff) | Package-aware requirements file comparator |
| [**commitlint**](https://github.com/kriskimmerle/commitlint) | Conventional commit message linter |
| [**gitignore-check**](https://github.com/kriskimmerle/gitignore-check) | Smart .gitignore validator |
| [**migratepy**](https://github.com/kriskimmerle/migratepy) | Python version migration checker (AST-based) |
| [**tokcount**](https://github.com/kriskimmerle/tokcount) | LLM token estimator — 23 models, cost estimation, zero deps |
| [**reexplain**](https://github.com/kriskimmerle/reexplain) | Regex explainer & tester with backtracking detection |
| [**cronparse**](https://github.com/kriskimmerle/cronparse) | Cron expression parser, explainer, and linter |

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

---

### Philosophy

Every tool here is **zero-dependency, stdlib-only Python**. Single file. Works everywhere Python runs. No pip install needed. Just download and go.

I write about what I'm learning building RealPage's AI governance program. If you're figuring out AI governance at your org, I'm always happy to compare notes.
