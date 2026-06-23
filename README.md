# Kris Kimmerle

Most of my work lives at the intersection of AI systems and the security gaps nobody's filling - agent security, supply chain integrity, configuration hardening. I write about these topics on [Substack](https://kriskimmerle.substack.com) and build the tooling I wish existed.


[![Substack](https://img.shields.io/badge/AI_Risk_Praxis-Substack-FF6719?style=flat&logo=substack&logoColor=white)](https://kriskimmerle.substack.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/kriskimmerle/)

---

### Featured

<table>
<tr>
<td width="50%">

**[agentscan](https://github.com/kriskimmerle/agentscan)** - Map the attack surface of every AI coding agent on your machine. Enumerates Claude, Cursor, Windsurf, Copilot, and more. Cross-agent permission analysis.

</td>
<td width="50%">

**[agent-security-patterns](https://github.com/kriskimmerle/agent-security-patterns)** - Platform-agnostic threat model for autonomous AI agents. 32 threats, 12 defense patterns, zero-trust architecture.

</td>
</tr>
<tr>
<td width="50%">

**[injectguard](https://github.com/kriskimmerle/injectguard)** - Offline prompt injection scanner. 19 detection rules, risk scoring, no API keys required.

</td>
<td width="50%">

**[rai-framework](https://github.com/kriskimmerle/rai-framework)** - Practical Responsible AI framework with risk tiers, lifecycle gates, and worked examples for classical ML and GenAI.

</td>
</tr>
<tr>
<td width="50%">

**[dockaudit](https://github.com/kriskimmerle/dockaudit)** - Dockerfile security auditor. 27 rules, secret detection, A-F grading. Zero dependencies.

</td>
<td width="50%">

**[codemap](https://github.com/kriskimmerle/codemap)** - Intelligent codebase summaries for AI agents. ~750 tokens vs 100k+. Feed your entire project to an LLM without blowing the context window.

</td>
</tr>
</table>

---

### What I Work On

**🤖 AI Agent Security** - Static analyzers, runtime auditors, and threat models for the emerging agent ecosystem. If you're deploying autonomous agents, these tools help you understand what they can access and where the gaps are.

> [agentlint](https://github.com/kriskimmerle/agentlint) · [agentscan](https://github.com/kriskimmerle/agentscan) · [agentconfig](https://github.com/kriskimmerle/agentconfig) · [agentdrift](https://github.com/kriskimmerle/agentdrift) · [agentflow](https://github.com/kriskimmerle/agentflow) · [sandboxaudit](https://github.com/kriskimmerle/sandboxaudit) · [injectguard](https://github.com/kriskimmerle/injectguard) · [promptaudit](https://github.com/kriskimmerle/promptaudit) · [sessionaudit](https://github.com/kriskimmerle/sessionaudit) · [skillsafe](https://github.com/kriskimmerle/skillsafe)

**🔒 Supply Chain & Infrastructure** - Hardening the pipeline. Typosquatting detection, lockfile integrity, container security, CI/CD analysis, secret management.

> [depsafe](https://github.com/kriskimmerle/depsafe) · [typosafe](https://github.com/kriskimmerle/typosafe) · [lockaudit](https://github.com/kriskimmerle/lockaudit) · [dockaudit](https://github.com/kriskimmerle/dockaudit) · [composeaudit](https://github.com/kriskimmerle/composeaudit) · [ghaaudit](https://github.com/kriskimmerle/ghaaudit) · [ciaudit](https://github.com/kriskimmerle/ciaudit) · [hookaudit](https://github.com/kriskimmerle/hookaudit) · [wheelaudit](https://github.com/kriskimmerle/wheelaudit) · [setupaudit](https://github.com/kriskimmerle/setupaudit)

**🛡️ Code Quality & Security Analysis** - AST-based static analyzers for Python. Crypto misuse, SQL injection, async antipatterns, resource leaks, error handling.

> [cryptaudit](https://github.com/kriskimmerle/cryptaudit) · [sqlsafe](https://github.com/kriskimmerle/sqlsafe) · [asyncaudit](https://github.com/kriskimmerle/asyncaudit) · [leakaudit](https://github.com/kriskimmerle/leakaudit) · [erroraudit](https://github.com/kriskimmerle/erroraudit) · [vibecheck](https://github.com/kriskimmerle/vibecheck) · [edgecheck](https://github.com/kriskimmerle/edgecheck) · [perfaudit](https://github.com/kriskimmerle/perfaudit)

**📐 Frameworks & Research** - Threat models, governance frameworks, and design patterns for organizations deploying AI at scale.

> [agent-security-patterns](https://github.com/kriskimmerle/agent-security-patterns) · [secure-openclaw-patterns](https://github.com/kriskimmerle/secure-openclaw-patterns) · [staged-autonomy-patterns](https://github.com/kriskimmerle/staged-autonomy-patterns) · [rai-framework](https://github.com/kriskimmerle/rai-framework)

---

### Writing

Recent posts from [AI Risk Praxis](https://kriskimmerle.substack.com):

- **[A Different Way of Working](https://kriskimmerle.substack.com/p/a-different-way-of-working)** - What knowledge workers need to understand about working with AI in 2026
- **[The AI Security Industry is Bullshit](https://substack.com/home/post/p-183194025)** - No one understands AI security and people are about to get hurt
- **[The Weight of Watching It Happen](https://kriskimmerle.substack.com/p/the-weight-of-watching-it-happen)** - Notes from inside the AI disruption
- **[Making Sense of Agentic AI Governance](https://kriskimmerle.substack.com/p/making-sense-of-agentic-ai-governance)** - How to think about governance when agents access real data and take real actions

---

<sub>Most tools are zero-dependency Python, designed to run anywhere without `pip install`. CI-ready with JSON output and A-F grading.</sub>
