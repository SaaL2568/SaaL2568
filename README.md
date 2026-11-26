<!--
  hi! this is your GitHub profile README.
  to make it live: create a PUBLIC repo named exactly "SaaL2568" and drop this file in as README.md.
  palette: mint #4E9E86 · blue #5B87B8 · ink #3D5A63 · cream #F7FBFA
  wave gradient: #A8DCC3 → #A9CBEC
-->

<div align="center">

<img src="assets/header.svg" width="100%" alt="hi, i'm samuel" />

<a href="https://github.com/SaaL2568">
  <img src="https://readme-typing-svg.demolab.com?font=Quicksand&weight=600&size=20&pause=1400&color=4E9E86&center=true&vCenter=true&width=700&lines=i+build+RAG+systems+that+cite+their+sources;retrieval%2C+grounding%2C+guardrails+%26+observability;currently%3A+a+drug-info+RAG+app+%26+a+word-predicting+keyboard;ask+me+about+retrieval%2C+IEMs%2C+QMK%2C+or+side+projects" alt="typing intro" />
</a>

<br/>

<img src="https://img.shields.io/badge/open%20to%20collaborations-4E9E86?style=flat-square" alt="open to collaborations" />

</div>

<br/>

<p align="center">
  i'm <b>Samuel</b> — a final-year B.Tech CSE (AI &amp; ML) student at Christ University, Bengaluru,
  with an Honours in Cyber Security. i build retrieval-augmented AI that answers with citations instead of confidence.
</p>

<p align="center">
  i care about the part after something is built: making it observable, making it fail loudly instead of silently,
  and figuring out why it broke. on the side, i make small tools for problems i personally find annoying.
</p>

<br/>

<p align="center"><sub>· · · · · · · · · ·</sub></p>

<h3 align="center">what i focus on</h3>

> <img src="https://img.shields.io/badge/featured-5B87B8?style=flat-square" alt="featured" />
>
> **Drug Information Assistant** — a retrieval-augmented chatbot that answers questions from official FDA prescribing information. Every answer is grounded in the retrieved text, cites the exact page it came from, and refuses when the best chunk is below the similarity threshold or the question is out of scope — no model call, no guess.
>
> `Python` `FastAPI` `bge-small-en-v1.5` `Chroma` `Ollama` `Next.js` · **[source](https://github.com/SaaL2568/cts-hackathon)**
>
> <sub>PDF → page-aware chunks → bge-small-en-v1.5 → Chroma → top-5 → similarity gate at 0.7 → llama3.1 → cited answer</sub>

<p align="center">
  <sub>the guardrail sits before generation, not after. if retrieval is weak, the correct answer is <i>"not in the label."</i></sub>
</p>

<br/>

<h3 align="center">what i'm into</h3>

- **Retrieval that stays honest** — answers that come only from evidence, cite the page they used, and refuse when the evidence is thin. it's the most interesting part of working with models.
- **Systems that fail loudly** — structured logs you can reconstruct a bad run from, timeouts that actually fire, watchdogs, and explicit error states instead of quiet degradation.
- **The part after it's built** — observability, failure handling, and root-cause work. the side of software that only shows up in production.
- **Signals over time** — recurrence plots and recurrence quantification on chaotic and climate data, from a research internship at IIIT Kottayam's FACTS-H lab. it's the same instinct as reading a metrics graph instead of a single error.
- **Small tools for real annoyances** — a Windows app for earphone channel imbalance, a keyboard that predicts your next letter, an extension that remembers products for me.

<br/>

<h3 align="center">where i've worked</h3>

- **NovaForge.ai** · technical intern, 2026 — FastAPI backends for two AI products: a clinical document pipeline that turns scanned case sheets into discharge-summary drafts with field-level provenance, and a planning-intelligence platform where i built the retrieval layer and insight reports.
- **IIIT Kottayam, FACTS-H Lab** · research intern, 2025 — nonlinear time series analysis with recurrence plots and recurrence quantification on chaotic and climate data.

<br/>

<h3 align="center">side projects</h3>

| # | project | what it does | built with |
| :-: | :--- | :--- | :--- |
| 01 | **[WordHalo](https://github.com/SaaL2568/WordHalo)** | Lights up the next letter on your keyboard before you consciously think of it — per-key RGB meets a language model. | `Python` `QMK` `NLP` |
| 02 | **[hand-of-driver](https://github.com/SaaL2568/hand-of-driver)** | Drive a simulated car with your hands in front of a webcam. Smooth steering from MediaPipe, discrete commands from YOLO11. | `Python` `OpenCV` `YOLO` |
| 03 | **[hearequalornah](https://github.com/SaaL2568/hearequalornah)** | Plays a tone in each ear, measures the difference with your microphone, then fixes the imbalance in Windows. Free, offline. | `C#` `WPF` `NAudio` |
| 04 | **[TrackFinder](https://github.com/SaaL2568/TrackFinder)** | Finds an artist's most-played songs and turns them into a playlist, so you don't have to. | `JavaScript` `Spotify API` |
| 05 | **Magpie** | A Chrome extension that collects everything about a product you like — specs, images, screenshots, notes — into one personal catalogue. In progress, not published yet. | `JavaScript` `Chrome MV3` |

<br/>

<h3 align="center">the toolbox</h3>

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cs,js,ts,react,nextjs,nodejs,fastapi,threejs,tailwind,dotnet,pytorch,opencv,sklearn,git,github,linux,vscode&theme=light&perline=9" alt="tech stack" />
</p>

<br/>

<h3 align="center">my github, in numbers</h3>

<p align="center">
  <img height="168" src="https://github-readme-stats.vercel.app/api?username=SaaL2568&show_icons=true&hide_border=true&bg_color=F7FBFA&title_color=4E9E86&text_color=5A6E75&icon_color=6E9BD1&include_all_commits=true&count_private=true" alt="github stats" />
  <img height="168" src="https://github-readme-stats.vercel.app/api/top-langs/?username=SaaL2568&layout=compact&hide_border=true&bg_color=F7FBFA&title_color=4E9E86&text_color=5A6E75&langs_count=8" alt="top languages" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=SaaL2568&hide_border=true&background=F7FBFA&ring=4E9E86&fire=6E9BD1&currStreakLabel=5B87B8&sideLabels=5A6E75&dates=8A9AA0&currStreakNum=3D5A63&sideNums=3D5A63" alt="commit streak" />
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=SaaL2568&bg_color=F7FBFA&color=5B87B8&line=4E9E86&point=6E9BD1&area=true&hide_border=true&custom_title=my%20little%20commit%20trail" alt="activity graph" />
</p>

<br/>

<h3 align="center">when i'm not coding</h3>

<p align="center">
  chasing channel imbalance in my IEMs &nbsp;·&nbsp; rebuilding my keyboard layout again &nbsp;·&nbsp; reading about nonlinear dynamics
</p>

<br/>

<div align="center">

<img src="assets/footer.svg" width="100%" alt="thanks for stopping by" />

<sub>made with pastel, patience, and far too many side projects</sub>

</div>
