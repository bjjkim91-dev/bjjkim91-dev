# Welcome to my GitHub 👋

I'm a Senior Data Engineer with over 10 years of experience in data analytics, reporting and architecture. I'm currently part of an AI Enablement team, where I build the structure and foundation for AI-native development and agentic workflows across engineering teams.

I studied Management Engineering at the University of Waterloo and later completed a Master of Management in Artificial Intelligence at Queen's University, which is where my work shifted toward applied AI. Along the way I earned a Certificate in Machine Learning from York University, and I'm currently studying for the PMI Certified Professional in Managing AI (PMI-CPMAI), a certification in AI project management.

Below are the personal and academic projects I've worked on.

---

## 🎓 Academic

### [SLM Risk Governance Agent](https://github.com/bjjkim91-dev/risk-governance-agent)

Compliance teams spend 20 to 40 hours per assessment reading a regulation, writing risk statements, matching them to controls and then to process steps, and the result still differs from one analyst to the next. This agent does the first draft of all three steps. You upload a regulation, a control inventory and a process narrative. It proposes a MECE risk register in the COSO shape with the source clause quoted on every row, maps the approved risks to controls, then places those controls on the process steps, and you approve, reject or edit each phase before the next one runs. Everything runs locally through Ollama on a Qwen2.5-7B fine-tuned per phase with QLoRA, so no document leaves the machine. It ends with coverage counts, unmapped risks flagged, and an Excel or PDF export.

![Demo: approving the phase 3 governance map and reaching the summary verdict](https://raw.githubusercontent.com/bjjkim91-dev/risk-governance-agent/main/docs/images/demo.gif)

▶️ [Watch the full 5-minute demo on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7441666828239593472/)

![Upload one document per role](https://raw.githubusercontent.com/bjjkim91-dev/risk-governance-agent/main/docs/images/01-upload.png)

![Phase 1: risk register with source quotes, severity and category](https://raw.githubusercontent.com/bjjkim91-dev/risk-governance-agent/main/docs/images/02-phase1-risks.png)

![Phase 2: risk to control matrix](https://raw.githubusercontent.com/bjjkim91-dev/risk-governance-agent/main/docs/images/03-phase2-controls.png)

![Summary and verdict with coverage counts and export](https://raw.githubusercontent.com/bjjkim91-dev/risk-governance-agent/main/docs/images/05-summary-verdict.png)

### [POS Scan](https://github.com/bjjkim91-dev/pos-cleanscan)

Messy retailer point-of-sale strings turned into clean product attributes. Rules and fuzzy matching first, a LoRA-tuned Llama for the final call.

![POS CleanScan](https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/hero-before-after.png)

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
