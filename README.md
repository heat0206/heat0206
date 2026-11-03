<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=26&pause=1200&color=7AA2F7&center=true&vCenter=true&width=620&lines=Hi%2C+I%27m+Heet+Mankad+%F0%9F%91%8B;Full-stack+%2B+AI%2FML+engineer+in+the+making;I+ship+things+end-to-end" alt="Hi, I'm Heet Mankad" />

**B.Tech CSE @ PDEU '28 · CGPA 9.65/10 · SIH 2025 National 2nd Runner-Up**

<a href="https://www.linkedin.com/in/heet-mankad"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:heetmankad06@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://bahikhata.dev"><img src="https://img.shields.io/badge/Bahikhata-Live-2FBF71?style=for-the-badge&logo=vercel&logoColor=white" /></a>

<img src="https://komarev.com/ghpvc/?username=heat0206&label=PROFILE+VIEWS&style=flat-square&color=7aa2f7" />
<img src="https://img.shields.io/github/followers/heat0206?style=flat-square&color=7aa2f7&labelColor=1a1b27&label=FOLLOWERS" />
<img src="https://img.shields.io/badge/OPEN_TO-SWE%20%2F%20AI--ML%20INTERNSHIPS-9ece6a?style=flat-square&labelColor=1a1b27" />

</div>

<br/>

```yaml
name        : Heet Mankad
role        : CS undergrad · software engineer in the making
location    : Gujarat, India
education   : B.Tech CSE @ Pandit Deendayal Energy University (2024–2028)
focus       : [full-stack engineering, AI/ML systems, developer tooling]
currently   : building an AI flashcard generator · grinding DSA in C++ · open-source
open_to     : [software engineering internships, AI/ML internships, OSS collabs]
```

---

### 🧩 Open Source

**🔧 [PicadoLabs/build-with-ai](https://github.com/PicadoLabs/build-with-ai)** — *merged Nov 2026*
`feat(init): add non-interactive initialization` · [PR #235](https://github.com/PicadoLabs/build-with-ai/pull/235)
> `npx build-with-ai init` used to hang outside a TTY — breaking CI, Docker, and agent-driven setups. I added a zero-prompt path so the tool works headlessly.

- Added `-y/--yes`, `--template`, `--name`, `--level`, `--idea` flags, with `--yes` filling only missing values
- Built-in template IDs now resolve alongside local paths and HTTP(S) URLs
- Fails fast with named missing flags when stdin isn't a terminal; re-init guards with `--force`
- **6 commits · 987 additions across 6 files**, with unit, re-init, CLI integration, and e2e coverage
- Merged after maintainer review — [see the diff](https://github.com/PicadoLabs/build-with-ai/pull/235/files)

**🧠 [open-inspect/background-agents](https://github.com/open-inspect/background-agents)** — *merged Jun 2026*
`Improve formatting for get-task-status tool calls` · [PR #725](https://github.com/open-inspect/background-agents/pull/725)
> Traced the data flow across a production TypeScript/React codebase and reworked how agent tool calls render in the web UI, iterating through code review and architecture discussion on custom renderers.

---

### 🔭 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

**[📊 Bahikhata](https://github.com/heat0206/Bahikhata)** · [live ↗](https://bahikhata.dev)

<a href="https://github.com/heat0206/Bahikhata"><img src="https://github-readme-stats.shion.dev/api/pin/?username=heat0206&repo=Bahikhata&theme=tokyonight&hide_border=true&border_radius=10" /></a>

Job & internship application tracker — deployed and in daily use.
`React` `Node/Express` `MongoDB` `JWT`
- bcrypt + httpOnly cookie auth with per-user data isolation
- Claude tool-calling chatbot for natural-language CRUD
- Background polling auto-closes past online assessments

</td>
<td width="50%" valign="top">

**[🎓 Smart Attendance System](https://github.com/heat0206/SIH_Project)** · *SIH '25 National 2nd Runner-Up*

<a href="https://github.com/heat0206/SIH_Project"><img src="https://github-readme-stats.shion.dev/api/pin/?username=heat0206&repo=SIH_Project&theme=tokyonight&hide_border=true&border_radius=10" /></a>

Offline-first attendance for rural schools.
`React` `Firebase` `ESP32-CAM` `RFID`
- **~40–50%** less manual attendance time per class
- **~25–30%** better record accuracy — proxy entries eliminated
- Hardware + frontend + cloud built for intermittent networks

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[🛡️ Secure Agentic AI Tool](https://github.com/heat0206/agentic-ai-project)**

<a href="https://github.com/heat0206/agentic-ai-project"><img src="https://github-readme-stats.shion.dev/api/pin/?username=heat0206&repo=agentic-ai-project&theme=tokyonight&hide_border=true&border_radius=10" /></a>

A Python agent that edits real codebases through sandboxed tools.
`Python` `Gemini API` `Sandboxing`
- Modified **10+ source files** while blocking unauthorized filesystem access
- Least-privilege tool contracts, modular execution

</td>
<td width="50%" valign="top">

**[⚖️ Algorithmic Bias Audit](https://github.com/heat0206/AIF-8A-Bias-Audit-Portfolio)**

<a href="https://github.com/heat0206/AIF-8A-Bias-Audit-Portfolio"><img src="https://github-readme-stats.shion.dev/api/pin/?username=heat0206&repo=AIF-8A-Bias-Audit-Portfolio&theme=tokyonight&hide_border=true&border_radius=10" /></a>

Fairness audit of a credit-scoring model on **50,000 records**.
`Fairlearn` `SHAP` `scikit-learn`
- Four-Fifths Rule violations across gender, geography, age
- **5 mitigation strategies** benchmarked; mapped to RBI FPC & DPDPA 2023

</td>
</tr>
</table>

**🌱 YUWA / Ecolympics Verification Platform** — *JPMorganChase Code for Good 2026*
A role-based platform for an NGO to run the full submission lifecycle: upload → validation → human verification → Drive sync → scoring → shortlist → jury → leaderboard. Built on Supabase (PostgreSQL + Auth) and the Google Drive API, with activity-aware validation for file type/size, deadlines, GPS metadata, duplicates, and external links.

---

### 🛠️ Tech Stack

<div align="center">

<img src="https://skillicons.dev/icons?i=c,cpp,python,js,ts,react,nodejs,express,tailwind,vite,firebase,supabase,mongodb,mysql,git,docker,aws,linux,bash&perline=18" />

<br/><br/>

![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-EB5E28?style=flat-square&logo=xgboost&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Firebase](https://img.shields.io/badge/Firestore-FFCA28?style=flat-square&logo=firebase&logoColor=black)
![Gemini](https://img.shields.io/badge/Gemini_API-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32--CAM-E7352C?style=flat-square&logo=espressif&logoColor=white)

</div>

---

### 📈 GitHub, by the numbers

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=heat0206&theme=tokyonight&no-frame=true&no-bg=true&column=7&margin-w=8&margin-h=8" />

<br/>

<img height="165" src="https://github-readme-stats.shion.dev/api?username=heat0206&show_icons=true&theme=tokyonight&hide_border=true&border_radius=10&include_all_commits=true&count_private=true" />
<img height="165" src="https://streak-stats.demolab.com/?user=heat0206&theme=tokyonight&hide_border=true&border_radius=10" />

<br/>

<img height="165" src="https://github-readme-stats.shion.dev/api/top-langs/?username=heat0206&theme=tokyonight&hide_border=true&border_radius=10&layout=compact&langs_count=8" />

<br/>

<img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=heat0206&theme=tokyo-night&hide_border=true&radius=10&area=true&custom_title=Contribution%20Activity" />

</div>



<div align="center">
  <img width="100%" src="https://raw.githubusercontent.com/heat0206/heat0206/output/snake-dark.svg" alt="Contribution snake" />
</div>


---

### 🌱 Currently

- 🚀 **[spendsage](https://github.com/heat0206/spendsage)** — festival-aware AI money planner, built at the PayPal AI Hackathon
- 🧠 An **AI-powered flashcard generator**
- 🎯 **Unblur** — helping CS students figure out which part of the field fits them
- 📚 DSA & competitive programming in C++ — graphs, DP, greedy, backtracking
- 🔐 Web security via PicoCTF — SSTI, header exploits, directory enumeration

---

### 🤝 Let's connect

<div align="center">

<a href="https://www.linkedin.com/in/heet-mankad"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
<a href="mailto:heetmankad06@gmail.com"><img src="https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
<a href="https://github.com/heat0206?tab=repositories"><img src="https://img.shields.io/badge/All%20Repos-181717?style=for-the-badge&logo=github&logoColor=white" /></a>

<br/><br/>

*"Talk is cheap. Show me the code." — Linus Torvalds*

</div>
