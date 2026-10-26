# Welcome to my GitHub 👋

I'm a Senior Data Engineer with over 10 years of experience in data analytics, reporting and architecture. I'm currently part of an AI Enablement team, where I build the structure and foundation for AI-native development and agentic workflows across engineering teams.

I studied Management Engineering at the University of Waterloo and later completed a Master of Management in Artificial Intelligence at Queen's University, which is where my work shifted toward applied AI. Along the way I earned a Certificate in Machine Learning from York University, and I'm currently studying for the PMI Certified Professional in Managing AI (PMI-CPMAI), a certification in AI project management.

Below are the personal and academic projects I've worked on.

---

## 🎓 Academic

### [SLM Risk Governance Agent](https://github.com/bjjkim91-dev/slm-risk-governance-agent)

📁 Repo: [bjjkim91-dev/slm-risk-governance-agent](https://github.com/bjjkim91-dev/slm-risk-governance-agent)

Compliance teams spend 20 to 40 hours per assessment reading a regulation, writing risk statements, matching them to controls and then to process steps, and the result still differs from one analyst to the next. This agent does the first draft of all three steps. You upload a regulation, a control inventory and a process narrative. It proposes a MECE risk register in the COSO shape with the source clause quoted on every row, maps the approved risks to controls, then places those controls on the process steps, and you approve, reject or edit each phase before the next one runs. Everything runs locally through Ollama on a Qwen2.5-7B fine-tuned per phase with QLoRA, so no document leaves the machine. It ends with coverage counts, unmapped risks flagged, and an Excel or PDF export.

![Demo: approving the phase 3 governance map and reaching the summary verdict](https://raw.githubusercontent.com/bjjkim91-dev/slm-risk-governance-agent/main/docs/images/demo.gif)

▶️ [Watch the full 5-minute demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7441666828239593472/)

### [POS CleanScan](https://github.com/bjjkim91-dev/pos-cleanscan)

📁 Repo: [bjjkim91-dev/pos-cleanscan](https://github.com/bjjkim91-dev/pos-cleanscan)

Capstone project with Coca-Cola Canada. Retailers send Coke their point-of-sale data, and every retailer writes the same product differently: NUKA COLA QUANTUM 12X355ML CANS, NUKA QNTM 12PK, NC QUANTUM ZERO SGR 355ML X12. We built CleanScan to parse those raw strings into ten clean, structured fields, brand, flavour, category, sub-brand, calorie tier, pack, size, count, product name and product group, ready for storage and analytics. Rules and fuzzy dictionary matching handle the easy part. A Llama 3.2 3B fine-tuned with LoRA on Coke's own labelled history makes the final call on every field, running locally with no API cost. On a blind holdout of 1,023 real rows it reached 79% macro accuracy across nine attributes, with brand at 88%, pack count at 90% and product name at 82%, about 30 points above the rule-based approach it replaced. Coke's data stays private, so the sample rows here are fictional: Nuka-Cola, Slurm and Brawndo. The pipeline, the trained adapter, the training scripts and the fifteen-slide walkthrough are the real ones.

![One product, three retailer strings, one clean record](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/hero-before-after.png)

![Ten rows in, ten clean records out](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/ten-rows.png)

![One row traced through all six stages](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/row-trace.png)

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
