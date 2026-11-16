# Viacheslav Bochkarev — building ViBo, memory for AI agents

Agents lose useful context between sessions, and searching the web can consume a large share of their tokens.  
ViBo helps AI agents retain and retrieve context, with layered memory and compressed web search.  
It’s for developers building agents and workflows with Python or MCP.

**A simple handoff**
1. An agent finishes a session.
2. It saves useful context to persistent memory.
3. In the next session, it recalls that context and continues.

## Start here

- **Python:** [ViBo-memory](https://github.com/vnbochkarev-netizen/ViBo-memory) — `pip install vibo-memory`
- **MCP:** [vibo-mcp](https://github.com/vnbochkarev-netizen/vibo-mcp) — `npx @vibo-dev/vibo-mcp`

## Ecosystem

| Project | What it does | Status |
|---|---|---|
| [ViBo-memory](https://github.com/vnbochkarev-netizen/ViBo-memory) | Persistent L1/L2/L3 memory and web search compression for AI agents | beta |
| [vibo-mcp](https://github.com/vnbochkarev-netizen/vibo-mcp) | Memory for MCP agents | beta |
| [ViBo-SkillQA](https://github.com/vnbochkarev-netizen/ViBo-SkillQA) | QA and certification for AI agent skills | experimental |
| [vibo-memory-protocol](https://github.com/vnbochkarev-netizen/vibo-memory-protocol) | Layered agent memory with recall, verification, and secret pointers | experimental |
| [vibo-skills](https://github.com/vnbochkarev-netizen/vibo-skills) | ViBo agent skills as `SKILL.md` definitions | experimental |
| [vibocode-mcp](https://github.com/vnbochkarev-netizen/vibocode-mcp) | MCP tools for endpoint search and sandboxed Python execution | experimental |
| [skill-injection-scanner](https://github.com/vnbochkarev-netizen/skill-injection-scanner) | Finds hidden instructions and prompt injection in agent skill files | experimental |
| [cloudarc](https://github.com/vnbochkarev-netizen/cloudarc) | Packs folders into `.vibo` archives with bounded memory use | experimental |
| [cloudarc-bounded-memory-benchmark](https://github.com/vnbochkarev-netizen/cloudarc-bounded-memory-benchmark) | Benchmark harness and CI gates for CloudArc | experimental |
| [context-compactor](https://github.com/vnbochkarev-netizen/context-compactor) | Condenses long agent sessions into handoff memos | experimental |
| [memory-shield](https://github.com/vnbochkarev-netizen/memory-shield) | Snapshots, scans, and audits agent memory | experimental |
| [haystack-vibo](https://github.com/vnbochkarev-netizen/haystack-vibo) | Persistent memory for Haystack pipelines | experimental |
| [n8n-nodes-vibo](https://github.com/vnbochkarev-netizen/n8n-nodes-vibo) | ViBo memory node for n8n | experimental |
| [vibo-selfdeed](https://github.com/vnbochkarev-netizen/vibo-selfdeed) | GRILL and MISSION for autonomous agents | experimental |

## Tools, not just memory

- [memory-shield](https://github.com/vnbochkarev-netizen/memory-shield) — snapshot, poison-scan, and audit agent memory.
- [context-compactor](https://github.com/vnbochkarev-netizen/context-compactor) — turn long sessions into handoff memos.
- [skill-injection-scanner](https://github.com/vnbochkarev-netizen/skill-injection-scanner) — inspect agent skill files for hidden instructions and prompt injection.
- [cloudarc](https://github.com/vnbochkarev-netizen/cloudarc) — pack folders into `.vibo` archives.

## Links

- [Website](https://wwwvibo.com)
- [Setup](https://wwwvibo.com/setup/)
- [PyPI: vibo-memory](https://pypi.org/project/vibo-memory/)

## Feedback

Open an issue in the relevant public repository to share feedback or report a problem.
