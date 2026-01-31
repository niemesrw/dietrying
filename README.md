# dietrying

A collaborative project exploring how AI is changing things.

## Team

| Name | Role | Status |
|------|------|--------|
| Erik Heidt | Founder | Active |
| Ryan Niemes | Member | Active |
| Ross | Member | Active |
| Neil | Member | Active |

## Communication

- **Slack**: `#dietrying` channel (primary)
- **GitHub**: This repo (for capturing ideas and documents)
- **History**: Started via Signal chat - introductions and early ideation

## How We Work

We use AI agents (GitHub Copilot in Slack) to handle the technical stuff. No git knowledge required.

```mermaid
flowchart LR
    subgraph Slack["💬 SLACK"]
        Team[["🗣️ Team<br/>Discussion"]]
        Notify[["🔔 Notifications"]]
    end

    subgraph Agent["🤖 AI AGENT"]
        AI[["@github<br/>Copilot"]]
    end

    subgraph GitHub["📁 GITHUB REPO"]
        Ideas[["ideas/"]]
        Docs[["docs/"]]
    end

    Team ==>|"capture this!"| AI
    AI ==>|saves| Ideas
    AI ==>|saves| Docs
    Ideas -.->|update alert| Notify
    Docs -.->|update alert| Notify

    style Slack fill:#4A154B,color:#fff,stroke:#4A154B
    style Agent fill:#2088FF,color:#fff,stroke:#2088FF
    style GitHub fill:#238636,color:#fff,stroke:#238636
    style Team fill:#611f69,color:#fff,stroke:#fff,stroke-width:2px
    style Notify fill:#611f69,color:#fff,stroke:#fff,stroke-width:2px
    style AI fill:#0969da,color:#fff,stroke:#fff,stroke-width:2px
    style Ideas fill:#2ea043,color:#fff,stroke:#fff,stroke-width:2px
    style Docs fill:#2ea043,color:#fff,stroke:#fff,stroke-width:2px
```

**The flow:**
1. **Discuss** ideas in Slack
2. **Capture** by asking `@github` to save to the repo
3. **Everyone gets notified** automatically when the repo updates

## What's Here

| Folder | Purpose |
|--------|---------|
| `ideas/` | Rough thoughts, brainstorms, early explorations |
| `docs/` | More polished or structured documents |

## Getting Started

1. Join `#dietrying` on Slack
2. Start discussing
3. When something's worth keeping, ask `@github` to capture it

See [CONTRIBUTING.md](CONTRIBUTING.md) for more details.
