# Hi, I'm Viacheslav Bochkarev 👋

I build **ViBo** — memory that makes AI agents actually remember, and tools that keep them honest.

## 🗄 Free and open source (start here)

| Project | What it is |
|---|---|
| [**CloudArc**](https://github.com/vnbochkarev-netizen/cloudarc) | Pack a 10 GiB folder into one `.vibo` archive at a **flat ~26 MiB peak RSS** (25.9 MiB pack / 31.2 MiB unpack, 1→10 GiB), and read its index over HTTP range requests without fetching the payload. Apache-2.0 · [docs site](https://vnbochkarev-netizen.github.io/cloudarc/) |
| [**memory-shield**](https://github.com/vnbochkarev-netizen/memory-shield) | Poisoning defense for agent memory: snapshots, quarantine, masked secrets (MIT, zero deps) |
| [**context-compactor**](https://github.com/vnbochkarev-netizen/context-compactor) | Condense long agent sessions into handoff memory |
| [**skill-injection-scanner**](https://github.com/vnbochkarev-netizen/skill-injection-scanner) | Find hidden instructions and prompt-injection in agent skills |
| [**cloudarc-bounded-memory-benchmark**](https://github.com/vnbochkarev-netizen/cloudarc-bounded-memory-benchmark) | The benchmark harness and CI gates behind CloudArc's numbers |

## 🧠 ViBo ecosystem

| Project | What it is | Grade |
|---|---|---|
| [**ViBo-memory**](https://github.com/vnbochkarev-netizen/ViBo-memory) | Persistent memory for AI agents: semantic search, L1/L2/L3 encryption, 50-150× token savings | A |
| [**ViBo-SkillQA**](https://github.com/vnbochkarev-netizen/ViBo-SkillQA) | Test & certify agent skills: 7 automated checks, grade A-D, CI-ready | A |
| [**vibo-mcp**](https://github.com/vnbochkarev-netizen/vibo-mcp) | Memory for any MCP agent — one line: `npx @vibo/mcp` | — |
| [**n8n-nodes-vibo**](https://github.com/vnbochkarev-netizen/n8n-nodes-vibo) | ViBo memory node for n8n workflows | — |
| [**haystack-vibo**](https://github.com/vnbochkarev-netizen/haystack-vibo) | Persistent memory + token savings for Haystack pipelines | — |
| [**ViBo-selfdeed**](https://github.com/vnbochkarev-netizen/ViBo-selfdeed) | Autonomous mission skill: grill → plan → execute → learn | — |

## 🛠 What I work on
- Bounded-memory storage and large-archive tooling
- Agent memory & context compression
- Skill certification & QA automation
- Prompt-injection defense, agent orchestration

## 📫 Contact
- Web: https://wwwvibo.com
- Telegram: [@ViBomemorybot](https://t.me/ViBomemorybot)
- Email: hello@wwwvibo.com
