# Democracy Game | AI-Mediated Civic Arena & Policy Synthesis

[![EU Datathon 2021 Finalist](https://img.shields.io/badge/EU%20Datathon-2021%20Finalist-blue.svg)](https://europa.eu/)
[![Incubation](https://img.shields.io/badge/Incubator-Orange%20Grove%20(NL%20Embassy)-orange.svg)](https://orangegrove.eu/)
[![License](https://img.shields.io/badge/License-MIT-emerald.svg)](LICENSE)
[![GitHub Pages](https://img.shields.io/badge/Deployment-GitHub%20Pages-purple.svg)](https://mitsaken.github.io/democracy-game/)

> **"Where Public Debate Becomes Measurable Policy."**  
> An evidence-grounded civic arena that restructures public debate into a gamified, fact-checked deliberations ecosystem powered by European Union open datasets, Pol.is consensus clustering, and cognitive debiasing.

---

## 🏛️ Background & Genesis

Democracy Game was conceived in **Brussels (Etterbeek, 2018)** during service at the European Parliament alongside Greek MEP Giorgos Grammatikakis. It addresses the systemic disconnect between digital natives (ages 15–29) and formal democratic institutions, tackling political alienation and weaponized misinformation through empirical triangulation.

* **Finalist Recognition:** EU Datathon 2021 (Publications Office of the European Union / EU Open Data Days).
* **Incubation:** Orange Grove (Embassy of the Netherlands in Greece).
* **Founding Leadership:** 
  * **Dimitra Giannaki** &mdash; Founder & Team Leader, EU Affairs & Policy
  * **Dimitrios Lampiris** &mdash; Co-Founder (Supporting Role: Strategy & Product Architecture)

---

## 🚀 Key Platform Features & Competitor Benchmarks

1. **Structured Deliberation Architecture (Kialo-inspired):** Decomposes complex legislation into binary Pro/Con argument branches with verifiable factual grounding.
2. **Ground Truth Engine (Meedan / Snopes-inspired):** Real-time verification leveraging official EU data streams:
   * **Eurostat Air Emissions Accounts:** `env_ac_ainah_r2`
   * **European Labour Force Survey (LFS):** `lfsa_eisn2`
   * **Youth Unemployment & NUTS-2 Indices:** `une_rt_m`
   * **Tenders Electronic Daily (TED) & CORDIS**
   * **Stanford Internet Observatory Disinformation Index**
3. **Consensus Topology Mapping (Pol.is & vTaiwan-inspired):** Real-time Principal Component Analysis (PCA) isolating bridge statements across polarized voting clusters.
4. **Civic Reputation Ladder (DebateIsland-inspired):** 4-tier gamification progression (Verified Deliberator &rarr; Evidence Architect &rarr; Policy Synthesizer &rarr; Civic Ambassador).
5. **Direct-to-MEP Policy Brief Synthesis (Decidim & CitizenLab-inspired):** Algorithmic distillation of consensus debates into structured legislative draft briefs (e.g. Article 3.2 Consensus Drafts) deliverable to MEPs and municipal councils.
6. **Behavioral Cognitive Model ($B = M \times A \times T$):** Fogg behavior model and Kahneman/Tversky heuristic loops replacing cynicism with civic habits.

---

## 🌐 Live Deployment

The platform is deployed live via GitHub Pages at:  
👉 **[https://mitsaken.github.io/democracy-game/](https://mitsaken.github.io/democracy-game/)**

Local execution:
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`.

---

## ⚖️ License & Attribution

Conceived & developed by Dimitrios Lampiris & Dimitra Giannaki. Built for transparent, data-driven citizen empowerment.
