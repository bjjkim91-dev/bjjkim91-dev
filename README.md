# Welcome to my GitHub 👋

I'm a Senior Data Engineer with over 10 years of experience in data analytics, reporting and architecture. I'm currently part of an AI Enablement team, where I build the structure and foundation for AI-native development and agentic workflows across engineering teams.

I studied Management Engineering at the University of Waterloo and later completed a Master of Management in Artificial Intelligence at Queen's University, which is where my work shifted toward applied AI. Along the way I earned a Certificate in Machine Learning from York University, and I'm currently studying for the PMI Certified Professional in Managing AI (PMI-CPMAI), a certification in AI project management.

Below are the personal and academic projects I've worked on.

---

## 🎓 Academic

### [SLM Risk Governance Agent](https://github.com/bjjkim91-dev/slm-risk-governance-agent)

📁 Repo: [bjjkim91-dev/slm-risk-governance-agent](https://github.com/bjjkim91-dev/slm-risk-governance-agent)

A compliance agent that turns a regulation into a governance register, with a human approving every step.

**The problem.** Compliance teams spend 20 to 40 hours per assessment reading a regulation, writing risk statements, matching them to controls and then to process steps, and the result still differs from one analyst to the next.

**What it does.** You upload a regulation, a control inventory and a process narrative. The agent drafts all three steps:

1. Regulation to risks: a MECE risk register in the COSO shape, with the source clause quoted on every row.
2. Risks to controls: each approved risk mapped to the controls that mitigate it.
3. Controls to process steps: each control placed on the process narrative.

You approve, reject or edit each phase before the next one runs. It ends with coverage counts, unmapped risks flagged, and an Excel or PDF export.

**How it runs.** Everything is local through Ollama on a Qwen2.5-7B fine-tuned per phase with QLoRA, so no document leaves the machine.

![Demo: approving the phase 3 governance map and reaching the summary verdict](https://raw.githubusercontent.com/bjjkim91-dev/slm-risk-governance-agent/main/docs/images/demo.gif)

▶️ [Watch the full 5-minute demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7441666828239593472/)

### [Coca-Cola POS CleanScan](https://github.com/bjjkim91-dev/pos-cleanscan)

📁 Repo: [bjjkim91-dev/pos-cleanscan](https://github.com/bjjkim91-dev/pos-cleanscan)

Capstone project with Coca-Cola Canada: a machine learning pipeline that turns raw retailer point-of-sale strings into clean, structured product data for storage and analytics.

**The problem.** Retailers send Coca-Cola their point-of-sale data, and every retailer writes the same product differently: `NUKA COLA QUANTUM 12X355ML CANS`, `NUKA QNTM 12PK`, `NC QUANTUM ZERO SGR 355ML X12`. One product, three strings, no shared key.

**What it does.** CleanScan parses each raw line into ten fields, brand, flavour, category, sub-brand, calorie tier, pack, size, count, product name and product group, each one locked to a dictionary of valid values. Rules and fuzzy dictionary matching settle the easy fields first, then a language model makes the final call on every field.

**The model.** We tried OpenAI's hosted model first, then fine-tuned a small local model, a Llama 3.2 3B with LoRA on Coca-Cola's own labelled history. It met the required performance while running for free on a desktop GPU, with no API cost and no data leaving the machine.

**The result.** On a blind holdout of 1,023 real rows: 79% macro accuracy across nine attributes, with brand at 88%, pack count at 90% and product name at 82%.

Coca-Cola's data stays private, so the sample rows here are fictional: Nuka-Cola, Slurm and Brawndo. The pipeline, the trained adapter, the training scripts and the slides are the real ones.

![One product, three retailer strings, one clean record](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/hero-before-after.png)

![Ten rows in, ten clean records out](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/ten-rows.png)

![One row traced through all six stages](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/row-trace.png)

### [Spaceship Titanic, class tournament](https://github.com/bjjkim91-dev/spaceship-titanic-tournament)

An in-class machine learning tournament on Kaggle's Spaceship Titanic problem; this entry took first place. SQL cleaning, a last-name feature that turned out to matter, seven models, Optuna tuning and a stacked ensemble, all in one script.

![Seven models, two feature sets, three ensembles](https://raw.githubusercontent.com/bjjkim91-dev/spaceship-titanic-tournament/main/docs/images/model-comparison.png)

## 🏦 Banking Personalization App

### [Grove](https://github.com/bjjkim91-dev/grove)

Upload your Canadian bank statements, see what a usual month costs you, and find out when work becomes optional. Privacy first, with a small coach that writes the takeaway.

![Grove](https://raw.githubusercontent.com/bjjkim91-dev/grove/main/docs/images/months-review-fold.png)

### Grove dev base

The management system behind Grove: skills, worklog and engineering guidance so humans and AI agents develop and log the same way. Built for AI-native development. *Coming soon.*

## 🎮 Games

### [FM Manager Assistant](https://github.com/bjjkim91-dev/fm26-db-viewer)

For Football Manager 26.

- Game assistant: a Korean assistant-coach persona that reads the live game.
- DB viewer and editor: the game's database decoded live, filterable, with verified edits and undo.

![FM Manager Assistant](https://raw.githubusercontent.com/bjjkim91-dev/fm26-db-viewer/main/docs/images/03-profile.png)

### [Fallen Empire](https://github.com/bjjkim91-dev/fallen-empire)

Board game. A hex-board strategy game in Godot, and the first game I built myself. Twelve factions, a card deck, and an AI opponent.

![Fallen Empire](https://raw.githubusercontent.com/bjjkim91-dev/fallen-empire/main/docs/images/play.png)

---

*Sample data in every repo is synthetic or from a game. Nothing personal, nothing licensed.*
