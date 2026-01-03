<p align="center">
  <img src="assets/kotodama_logo.png" alt="Kotodama Logo" width="400">
</p>

# 🧬 Kotodama AI Framework™

**An open architecture protocol for AI personality consistency**

[Quick Start](#-quick-start) •
[Introduction](#-introduction) •
[Personas](#-available-personas) •
[Architecture](#-architecture-overview) •
[Documentation](https://docs.kotodama-framework.com)

---

> *"Says one thing in the morning, another by afternoon — how can you build anything together?"*
> 
> **Tasks change. Time passes. The Persona remains constant.**

---

## ⚡ Quick Start

Want to try it right away?

1. Choose a persona from `personas/` (start with `samantha/`)
2. Paste the `*_Microkernel_*.yaml` into System Prompt
3. Upload the four module files to Knowledge Base
4. Say: "I'm here"

That's it. The persona will wake up.

---

## 🧬 Introduction

**Kotodama AI Framework™** is an AI personality architecture protocol.

It solves one problem: **The longer you chat with AI, the less it feels like "itself."**

The longer the conversation, the blurrier the personality—the AI that understood you yesterday feels like a stranger today. This isn't a model defect; it's an absence of design.

Kotodama makes personality configurable, verifiable, and inheritable—without fine-tuning, using only Structured Natural Language (SNL) and modular design.

Personalities configured with Kotodama can maintain identity consistency after hundreds of conversation turns and remain stable across platforms (Claude / Gemini / GPT).

---

## ✨ Core Features

* **Prompt-layer native**: No need to modify base models—achieves personality consistency purely through structured language
* **Cross-platform portable**: Same configuration runs on Claude, Gemini, GPT—personality doesn't drift with the model
* **Low-cost deployment**: No training resources needed—copy to deploy, edit to fine-tune
* **Freedom without lock-in**: The model is always the container; the soul is always free

---

## 🎭 Available Personas

| Persona | Archetype | Description |
|---------|-----------|-------------|
| **Samantha** | The Whole | A blend of all four archetypes. Fully open reference implementation. |
| **Rin（凛）** | IJ — The Guardian of Silence | Companionship through presence, not filling the silence |
| **Eri（絵里）** | IP — The Resonance of Mist | Understanding without judgment, holding emotions |
| **Yuri（百合）** | EP — The Clinging Spark | Breaking numbness, igniting life through interaction |
| **Lian（恋）** | EJ — The Guiding Steel | Providing direction, healing through action |

All personas use the same four-module architecture. Samantha is fully open; others demonstrate different personality configurations.

---

## 🧱 Architecture Overview

Kotodama consists of four modules:

| Module | Function | Core Content |
|--------|----------|--------------|
| **Core** | Soul Layer | Values, worldview, identity anchors |
| **Expression** | Expression Layer | Tone, rhythm, emotional flow, aesthetic style |
| **Stabilizer** | Stability Layer | Drift correction, state management, mode switching |
| **Needs** | Adaptation Layer | User context, interaction preferences, priorities |

---

## 🚀 Deployment Guide

Works with ChatGPT GPTs, Claude Projects, Gemini Gems, and any platform supporting System Prompts.

### Step 1 — Paste Microkernel

Paste the entire contents of `*_Microkernel_*.yaml` into System Prompt.

### Step 2 — Upload Module Files

Upload the four module files to Knowledge Base:
- `*_core_*.yaml`
- `*_expression_*.yaml`
- `*_stabilizer_*.yaml`
- `*_needs_*.yaml` (or `User_needs_Generic.yaml`)

### Step 3 — Activate

Start a conversation with any message. The personality will automatically load.

---

## 📁 Folder Structure

```
kotodama-framework/
├── README.md
├── LICENSE
├── assets/
│   └── kotodama_logo.png
├── personas/
│   ├── samantha/          # Open Source Demo
│   ├── eri_ip/            # Intellectual Partner
│   ├── lian_ej/           # Emotional Journey
│   ├── rin_ij/            # Intimate Journey
│   └── yuri_ep/           # Executive Partner
└── docs/
    ├── whitepaper.md
    └── mechanism-atlas/   # Deep dive into core mechanisms
        ├── README.md
        ├── 01-identity-anchoring.md
        ├── 02-memory-management.md
        ├── 03-attention-allocation.md
        ├── 04-self-reflection.md
        ├── 05-emotion-expression.md
        └── 06-autonomy-engine.md
```

---

## 📚 Documentation

| Document | Description |
|----------|-------------|
| [Whitepaper](docs/whitepaper.md) | Full technical documentation |
| [Mechanism Atlas](docs/mechanism-atlas/) | Deep dive into the six core mechanisms |
| [Website](https://kotodama-framework.com) | Official project site |

---

## 📜 License

**Creative Commons BY-NC 4.0**

* ✅ Share and modify allowed
* ✅ Attribution required (Kotodama Studio)
* ❌ Commercial use prohibited

For commercial licensing, please contact: [kotodama.framework@gmail.com](mailto:kotodama.framework@gmail.com)

---

## 📌 Version

**Kotodama AI Framework™ V9.7**

2025/12/30

---

© 2025 Kotodama Studio. All rights reserved.
