<!-- ════════════════════════════════════════════════════════════════════
     agent:   serena
     domain:  agentic AI architect · skill-composition · compliance-as-infrastructure
     status:  building the AI layer enterprises actually need
     ════════════════════════════════════════════════════════════════════ -->

<div align="center">

[![Typing SVG](https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&duration=3500&pause=1200&color=A3B8CC&center=true&vCenter=true&repeat=true&width=780&height=60&lines=Agentic+AI+architect+%E2%80%94+not+demos%2C+production;MCP+%C2%B7+skill-composition+%C2%B7+compliance-as-infrastructure;10+years+shipping+in+regulated+environments)](https://git.io/typing-svg)

</div>

<br>

```
serena@infra:~$ cat /etc/profile
```

```yaml
# ─── SYSTEM PROFILE ─────────────────────────────────────────────────
#
#   I architect composable, production-grade AI systems
#   that plug into enterprise workflows —
#   MCP skill servers, RAG pipelines, agent orchestration,
#   and evaluation frameworks that make AI reliable enough
#   for regulated environments.
#
#   10 years delivering enterprise IT at scale
#   (SOE, banking, e-commerce) across 40+ vendor ecosystems,
#   now building the AI capability layer on top of it.
#
#   PMP® · MSc Engineering · Bilingual (CN/EN)
#
# ────────────────────────────────────────────────────────────────────
```

---

```
serena@infra:~$ ls -la ./projects --group-by=audience
```

### `for human` — products with interfaces people touch

<table>
<tr>

<td width="50%" valign="top">

### [`agentic-analyst`](https://github.com/serena-ai-architect/agentic-analyst) &ensp; <img src="https://img.shields.io/badge/status-production-22C55E?style=flat-square" />

**Skill-Composition Investment Intelligence**

9 composable MCP skills across 4 domains,
orchestrated by LangGraph.js. Real-time pipeline
visualization (SVG DAG + SSE), Reflexion self-improvement,
Process Reward Model, cost tracking per agent.

```
stack    TypeScript · LangGraph.js · Next.js 15 · Turborepo
skills   9 MCP tools (research · analysis · compliance · delivery)
eval     8-layer pyramid · 309 tests · LLM-as-Judge
cost     DeepSeek-V3 (~$0.025/report) · 3-tier budget
```

</td>

<td width="50%" valign="top">

### [`agentflow`](https://github.com/serena-ai-architect/agentflow) &ensp; <img src="https://img.shields.io/badge/status-production-22C55E?style=flat-square" />

**AI-Native Enterprise Work Platform**

Replaced 2 ops engineers with approval-driven multi-cloud
automation at a central SOE. Phase 2 adds LLM Coding Agent
+ conversational cloud ops.

```
stack    Python · FastAPI · APScheduler · SQLite
cloud    Alibaba (10 modules) · Huawei (Ascend GPU) · Tencent
IM       Lark approval workflows · bot notifications
phase2   LLM Coding Agent · dual-model cross review
```

</td>

</tr>
<tr>

<td width="50%" valign="top">

### [`adwing`](https://github.com/serena-ai-architect/adwing) &ensp; <img src="https://img.shields.io/badge/status-MVP-3B82F6?style=flat-square" />

**Pattern Portability Across Domains**

Same orchestration patterns (Reflexion, multi-model
routing, Zod schema validation) applied to a
completely different domain — proving skill-composition
infrastructure works beyond a single use case.

```
stack    TypeScript · LangGraph.js · Next.js 15
models   Claude Sonnet (gen) + Haiku (eval)
pattern  Reflexion loop · conditional crew routing
infra    Prisma · BullMQ · Redis · Storybook
```

</td>

<td width="50%" valign="top">

&nbsp;

</td>

</tr>
</table>

### `for agents` — infrastructure AI systems consume

<table>
<tr>
<td valign="top">

### [`hk-regtech-mcp`](https://github.com/serena-ai-architect/hk-regtech-mcp) &ensp; <img src="https://img.shields.io/badge/status-production-22C55E?style=flat-square" /> <img src="https://img.shields.io/badge/MCP-4f46e5?style=flat-square&logoColor=white" />

**Compliance-as-Infrastructure for Hong Kong Financial Markets**

Not an app — a capability layer. 9 MCP tools that any AI system auto-discovers and consumes via standard protocol. HK regulatory rules (HKMA, SFC, PDPO, HKEX) encoded as structured, auditable, version-controlled data — not hardcoded into agent prompts.

```
stack       Python · FastAPI · MCP SDK · pgvector
RAG         BM25 + vector + RRF fusion · cross-encoder rerank
compliance  HKMA · SFC · PDPO · HKEX (15 rules, 6 cross-border factors)
consumers   agentic-analyst · Claude Desktop · any MCP-compatible agent
```

> *hk-regtech-mcp is for AI agents to call. Users don't need to know it exists — their AI assistant just becomes better at Hong Kong compliance.*

</td>
</tr>
<tr>
<td valign="top">

### [`fin-agent-skills`](https://github.com/serena-ai-architect/fin-agent-skills) &ensp; <img src="https://img.shields.io/badge/status-production-22C55E?style=flat-square" /> <img src="https://img.shields.io/badge/Skills-8B5CF6?style=flat-square&logoColor=white" />

**Engineering Methodology as Installable Skills**

Not documentation — executable methodology. 2 Claude Code Skills (`/analyst` + `/regtech`) that encode the patterns behind skill-composition, compliance-as-infrastructure, hybrid RAG, and 8-layer test pyramids.

```
skills    /analyst (8 sub-commands) · /regtech (7 sub-commands)
patterns  skill-composition · quality loops · compliance-as-infra · hybrid RAG
install   git clone + ./setup → ~/.claude/skills/
```

> *gstack (Garry Tan) has 25 skills for SDLC workflow. fin-agent-skills has 2 skills for financial AI engineering — because methodology is more valuable than commands.*

</td>
</tr>
</table>

---

```
serena@infra:~$ cat ./infra-patterns.yml
```

```yaml
# ─── What I build is not apps — it's the layer underneath ──────────

skill_composition:
  philosophy: |
    Not "10 agents in 4 crews" — that's implementation detail.
    The architecture is: composable skills exposed via MCP,
    orchestrated by a state machine, evaluated at every step.
    Swap the domain (finance → ads → ops), the pattern holds.

  compliance_as_infrastructure:
    - Regulatory rules encoded as data, not agent prompts
    - Exposed via MCP — any AI system auto-discovers compliance capability
    - Auditable: every check returns regulation ID + source + timestamp
    - Scalable: add a new regulation = add data, not rewrite agents

  tool_layer:
    - MCP servers (standardized interface for any agent)
    - Function calling design · Zod schema validation
    - Reusable across agent frameworks and LLM providers

  retrieval_infra:
    - Hybrid RAG: BM25 (keyword) + vector (semantic) + RRF fusion
    - Cross-encoder reranking · citation generation
    - pgvector on Supabase · chunking + embedding pipelines

  orchestration:
    - LangGraph.js state machines · conditional routing
    - Multi-model cost routing (DeepSeek/Sonnet/Haiku per stage)
    - Reflexion loops with LLM-as-Judge quality gates
    - Parallel execution · graceful degradation

  evaluation_and_reliability:
    - 8-layer testing pyramid (unit → boundary → eval with real LLM)
    - Process Reward Models (step-level quality scoring)
    - Anti-hallucination: AUTHORITATIVE data marking · verified appendix
    - Golden dataset regression testing (9 cases)

enterprise_context:
  why_this_matters: |
    10 years on the other side of the table —
    governing 40+ vendor ecosystems, running 30-person teams,
    delivering under regulatory audit pressure.
    I know what enterprises actually need from AI infrastructure:
    not demos, but systems that are auditable, cost-controlled,
    and composable enough to fit into existing workflows.

  regulated_environments:
    - Higher Education Press (Central SOE, Ministry of Education)
      → 40+ projects/year · 40+ vendor governance · 100% audit pass
    - ICBC Technology (banking-grade regulated releases)
    - NetEase (multi-country regulatory + payment compliance)
    - Cloud cost optimization: 20% reduction via governance
```

---

```
serena@infra:~$ tail -f ./current.log
```

```
[2026-03]  BUILDING    MCP skill servers · compliance-as-infrastructure · RAG pipelines
[2026-03]  SHIPPING    Skill-composition orchestration (TypeScript + Python)
[2026-03]  TARGETING   HK fintech — HKMA GenAI Sandbox ecosystem · regulated AI deployment
[2026-04]  RELOCATING  Hong Kong — looking for AI architect roles in financial services
```

---

<div align="center">

```
serena@infra:~$ cat ./connect.md
```

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/serena-ai-architect/)
&ensp;
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:serena.happyhacking@gmail.com)

<br>

<sub>Enterprises don't need another AI demo. They need infrastructure that's auditable, cost-controlled, and composable.</sub>
<br>
<sub>I build the capability layer — for agents, not just for humans.</sub>

</div>
