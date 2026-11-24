<p align="center">
  <img src="banner.png" alt="ZekeLabs" width="100%">
</p>

<h3 align="center">AI-built software, in real use.</h3>

<p align="center">
  <a href="https://zekelabs.dev">zekelabs.dev</a>
</p>

---

| Build | Status | What it is |
|---|---|---|
| **Legacy RPG restoration** | ![in build](https://img.shields.io/badge/-in%20build-6e7681) | A 2000s online RPG running again on a current Windows PC with no source code: client patched in place, text recovered, interface redrawn with AI |
| **Kalsys** | ![live](https://img.shields.io/badge/-live-2ea44f) | MCP server that gives AI clients one memory across sessions and projects. Each session opens on the right context; every change is checked |
| **Fateweaver** | ![live](https://img.shields.io/badge/-live-2ea44f) | Free AION 2 overlay for Windows: DPS meter, party HP, PvP tracking, timers and cube alerts. [Releases](https://github.com/ZekeLabs/fateweaver-releases) |
| **The Digital Novice** | ![live](https://img.shields.io/badge/-live-2ea44f) | Plain-English scam and fraud newsletter that finds, writes, fact-checks, illustrates and sends each issue itself, and skips a day rather than send a bad one |
| **Utility billing system** | ![in rollout](https://img.shields.io/badge/-in%20rollout-d29922) | Invoicing, payments and a customer portal for a utility with 200+ accounts. Private |

## How it's built

```mermaid
flowchart LR
    A[Scope and architecture] --> B[LRF rules]
    B --> C[AI agents build and test]
    C --> D[Review]
    D --> E[Release]
    E -. lessons .-> B
```

Every build runs under the Layered Reasoning Framework (LRF): the rules, open items and session history live in Kalsys, so each agent session starts with the right context and every change is checked before it ships.

---

<sub>Code is private. Write-ups and demos at <a href="https://zekelabs.dev">zekelabs.dev</a>.</sub>
