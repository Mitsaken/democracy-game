# Democracy Game | AI-Mediated Civic Arena & Policy Synthesis

[![EU Datathon 2021 Finalist](https://img.shields.io/badge/EU%20Datathon-2021%20Finalist-blue.svg)](https://europa.eu/)
[![Incubation](https://img.shields.io/badge/Incubator-Orange%20Grove%20(NL%20Embassy)-orange.svg)](https://orangegrove.eu/)
[![License](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-purple.svg)](https://pages.github.com/)

> **"Where Public Debate Becomes Measurable Policy."**  
> An evidence-grounded civic arena that restructures public debate into a gamified, fact-checked deliberations ecosystem powered by European Union open datasets and cognitive debiasing.

---

## 🏛️ Background & Genesis

Democracy Game was conceived in **Brussels (Etterbeek, 2018)** during service at the European Parliament alongside Greek MEP Giorgos Grammatikakis. It addresses the systemic disconnect between digital natives (ages 15–29) and formal democratic institutions, tackling political alienation and weaponized misinformation through empirical triangulation.

* **Finalist:** EU Datathon 2021 (Publications Office of the European Union / EU Open Data Days).
* **Incubation:** Orange Grove (Embassy of the Netherlands in Greece).
* **Founding Team:** Dimitra Giannaki, Konstantinos Kalafatakis, Dimitrios Lampiris, Olga Dourou.

---

## 🚀 Key Platform Features

1. **Live Virtual Townhall Arena:** Structured deliberative rooms (#EU-GREEN-DEAL-2030, Youth Housing, Digital Rights) where arguments are scored for rhetorical integrity.
2. **Ground Truth Engine (EU Open Data):** Real-time verification leveraging official EU data streams:
   * **Eurostat Air Emissions Accounts:** `env_ac_ainah_r2`
   * **European Labour Force Survey (LFS):** `lfsa_eisn2`
   * **Youth Unemployment & NUTS-2 Indices:** `une_rt_m`
   * **Tenders Electronic Daily (TED) & CORDIS**
   * **Stanford Internet Observatory Disinformation Index**
3. **Automated Policy Synthesis Canvas:** Algorithmic distillation of verified debate inputs into structured legislative draft briefs (e.g. Article 3.2 Consensus Drafts) deliverable to MEPs and municipal councils.
4. **Behavioral Cognitive Model ($B = M \times A \times T$):**
   * **Motivation:** Status recognition, rhetorical league tournaments, tangible policy impact.
   * **Ability:** Complex EU directives summarized into micro-arguments and pre-verified data cards.
   * **Trigger:** Deliberation calls timed to real parliamentary and municipal legislative agendas.

---

## 🌐 Instant Local Deployment

The web platform is completely self-contained in `index.html` (zero build-step required).

Simply open `index.html` in any modern web browser or serve it with Python:

```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

---

## 🚢 Publishing to GitHub Pages

1. Create a new repository named `democracy-game` on GitHub.
2. Link your local repository and push:
   ```bash
   git remote add origin https://github.com/Mitsaken/democracy-game.git
   git branch -M main
   git push -u origin main
   ```
3. In your GitHub repository settings:
   * Go to **Settings** &rarr; **Pages**.
   * Under **Build and deployment** &rarr; **Branch**, select `main` and `/ (root)`.
   * Click **Save**.
4. Your site will be live at:
   `https://Mitsaken.github.io/democracy-game/`

---

## ⚖️ License & Attribution

Conceived & developed by the Democracy Game team. Built for transparent, data-driven citizen empowerment.
