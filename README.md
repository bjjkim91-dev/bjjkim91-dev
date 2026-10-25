<h1 align="center">Hey, I'm bjjkim91-dev 👋</h1>

<p align="center">
  Data engineer by day. The rest of the time I build the things I wish existed: a finance app that reads my bank statements, language-model tools for messy data, a hex-board strategy game, and a live database viewer for a football sim.<br/>
  Everything here is finished, screenshotted, and runs with one command.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama" />
  <img src="https://img.shields.io/badge/Godot_4-478CBF?style=for-the-badge&logo=godotengine&logoColor=white" alt="Godot 4" />
</p>

---

## Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/bjjkim91-dev/flambed-squirrel"><img src="https://raw.githubusercontent.com/bjjkim91-dev/flambed-squirrel/main/docs/images/months-review-fold.png" alt="Flambed Squirrel monthly review" /></a>
      <h3><a href="https://github.com/bjjkim91-dev/flambed-squirrel">🐿️ Flambed Squirrel</a></h3>
      <p>Privacy-first FIRE planner. Upload Canadian bank statements, see what a usual month costs you, find out when work becomes optional. Parsers for six banks, encrypted Postgres with row-level security, and a coach that reads the numbers and writes the takeaway.</p>
      <p><sub>React · FastAPI · Supabase · Recharts · Playwright</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/bjjkim91-dev/risk-governance-agent"><img src="https://raw.githubusercontent.com/bjjkim91-dev/risk-governance-agent/main/docs/images/04-phase3-governance-map.png" alt="Risk Governance Agent phase 3 map" /></a>
      <h3><a href="https://github.com/bjjkim91-dev/risk-governance-agent">🛡️ Risk Governance Agent</a></h3>
      <p>Regulation in, governance register out. Three phases: regulation to risks, risks to controls, controls to process narratives, with a human approving every row. Qwen2.5-7B fine-tuned with QLoRA, one adapter per phase, all local through Ollama.</p>
      <p><sub>Python · Streamlit · Ollama · PEFT</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/bjjkim91-dev/pos-cleanscan"><img src="https://raw.githubusercontent.com/bjjkim91-dev/pos-cleanscan/main/docs/images/hero-before-after.png" alt="POS CleanScan before and after" /></a>
      <h3><a href="https://github.com/bjjkim91-dev/pos-cleanscan">🧹 POS CleanScan</a></h3>
      <p>Messy retailer point-of-sale strings to ten clean product attributes. N-gram fingerprints, fuzzy dictionary matching, 700+ rules, a product-name grammar, and a LoRA-tuned Llama 3.2 3B that makes the final call. 85% exact match on a real holdout; synthetic data in the repo.</p>
      <p><sub>Python · transformers · RapidFuzz · bitsandbytes</sub></p>
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/bjjkim91-dev/fallen-empire"><img src="https://raw.githubusercontent.com/bjjkim91-dev/fallen-empire/main/docs/images/play.png" alt="Fallen Empire mid-game board" /></a>
      <h3><a href="https://github.com/bjjkim91-dev/fallen-empire">⚔️ Fallen Empire</a></h3>
      <p>Hex-board strategy game about the scramble after an empire falls. Twelve factions, a card deck, a battle model built on troops, morale and discipline, and a scoring AI with a win plan per faction. All pixel art generated in code; balance tested with a headless simulator.</p>
      <p><sub>Godot 4 · GDScript</sub></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/bjjkim91-dev/fm26-db-viewer"><img src="https://raw.githubusercontent.com/bjjkim91-dev/fm26-db-viewer/main/docs/images/03-profile.png" alt="FM26 DB Viewer player profile" /></a>
      <h3><a href="https://github.com/bjjkim91-dev/fm26-db-viewer">⚽ FM26 DB Viewer</a></h3>
      <p>Live database viewer and editor for Football Manager 26, decoded from the game's own runtime type information with no published offsets. Loads 38,000 people in five seconds, filters on any column, writes verified edits back with a journal and undo. Plus a Korean assistant-coach persona.</p>
      <p><sub>Python · FastAPI · ctypes · reverse engineering</sub></p>
    </td>
    <td width="50%" valign="top">
      <h3>🍺 Next: brew log site</h3>
      <p>A homebrew recipe and batch-tracking website. Coming once the first five are polished.</p>
    </td>
  </tr>
</table>

<p align="center"><sub>Sample data in every repo is synthetic or from a game. Nothing personal, nothing licensed.</sub></p>
