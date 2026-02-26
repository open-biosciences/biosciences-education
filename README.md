# biosciences-education

Training materials, tutorials, and onboarding guides for the Open Biosciences platform.

Part of the [Open Biosciences](https://github.com/open-biosciences) multi-repo platform.

## Status

**Wave 4 — Not Started.** This repo will be authored after the core platform (Waves 1–3) is
stable. Content creation depends on having working MCP servers, agent workflows, and durable
execution pipelines in place before tutorials can be written and validated.

## Role

Make the platform accessible. `biosciences-education` is the learning layer of the platform —
training materials, tutorials, and onboarding docs that help two distinct audiences start
using the platform effectively:

| Audience | Who they are | What they need |
|----------|-------------|----------------|
| **Researchers** | Domain scientists using AI-assisted biosciences workflows | Step-by-step tutorials grounded in real research scenarios; no deep engineering knowledge required |
| **Contributors** | Developers extending the platform (new MCP servers, skills, agents) | Onboarding guides, SpecKit SDLC walkthroughs, architecture orientation |

## What Will Be Here (Wave 4)

All content is new — this repo has no predecessor. It will be authored from scratch during Wave 4.

### Training Materials

- Researcher-facing introductions to AI-assisted biosciences workflows
- Conceptual guides to the Fuzzy-to-Fact protocol and knowledge graph queries
- Overviews of each MCP server tier and what data it provides

### Tutorials

- **Running your first MCP query** — connect to [biosciences-mcp](https://github.com/open-biosciences/biosciences-mcp), search a gene, resolve a CURIE
- **Building a research workflow with Fuzzy-to-Fact** — fuzzy discovery to strict CURIE lookup end-to-end
- **Using SpecKit to add a new MCP server** — specification-driven development walkthrough (ADR-003)
- **Setting up and running the Deep Agents research platform** — LangGraph supervisor with 7 specialist agents

### Onboarding Guides

- Getting started for new contributors: clone workspace, run bootstrap, verify environment
- Architecture orientation: read ADR-001, understand platform conventions
- First contribution: follow SpecKit workflow to add a feature

### Platform Walkthroughs

- Competency question (CQ) workflows grounded in real biosciences research scenarios
- Knowledge graph exploration using Graphiti + Neo4j
- Temporal durable workflow execution examples

## Related Repos

| Repo | Relationship |
|------|-------------|
| [biosciences-workspace-template](https://github.com/open-biosciences/biosciences-workspace-template) | Same owner — handles environment setup and bootstrap; education handles learning the platform |
| [biosciences-mcp](https://github.com/open-biosciences/biosciences-mcp) | 12 FastMCP servers documented and demonstrated in tutorials |
| [biosciences-architecture](https://github.com/open-biosciences/biosciences-architecture) | ADRs and SpecKit conventions referenced throughout training content |
| [biosciences-deepagents](https://github.com/open-biosciences/biosciences-deepagents) | LangGraph multi-agent system covered in Deep Agents tutorial |

## Agent Ownership

**Education & Workspace Engineer (Agent 9)** — also owns
[biosciences-workspace-template](https://github.com/open-biosciences/biosciences-workspace-template).

## License

MIT
