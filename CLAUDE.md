# CLAUDE.md — biosciences-education

## Purpose

Training materials, tutorials, and onboarding content for the Open Biosciences platform. This repo is co-owned by the **Education & Workspace Engineer** agent.

## Responsibilities

- Onboarding guides for new contributors
- Tutorial notebooks demonstrating platform capabilities
- Training materials for each MCP server
- Documentation of common workflows

## Directory Structure

```
biosciences-education/
├── onboarding/
│   ├── getting-started.md        # First-session guide
│   ├── environment-setup.md      # Environment configuration
│   └── architecture-overview.md  # Platform architecture intro
├── tutorials/
│   ├── 01-fuzzy-to-fact/         # Fuzzy-to-Fact protocol walkthrough
│   ├── 02-mcp-servers/           # Using MCP servers
│   ├── 03-knowledge-graph/       # Building knowledge graphs
│   ├── 04-temporal-workflows/    # Durable execution with Temporal
│   └── 05-deep-agents/           # Multi-agent system usage
└── reference/
    ├── api-quick-reference.md    # Quick reference for all 12 APIs
    └── curie-cheat-sheet.md      # CURIE format reference
```

## Onboarding Flow

1. **Getting Started** — Clone workspace, run bootstrap, verify environment
2. **Architecture Overview** — Read ADR-001, understand Fuzzy-to-Fact
3. **First Query** — Run a gene search through HGNC MCP server
4. **Build a Graph** — Execute graph-builder workflow for a CQ
5. **Contribute** — Follow SpecKit workflow to add a feature

## Tutorial Standards

- Each tutorial is self-contained with clear prerequisites
- Code examples use real APIs (HGNC, UniProt — no keys required)
- Expected outputs shown for verification
- Tutorials reference specific ADR sections for deeper context

## Dependencies

- **Upstream**: `biosciences-architecture` (convention compliance), `biosciences-mcp` (tutorial API examples)
- **Downstream**: None (educational content is consumed by people)
