# Hi, I'm Doğukan Filiz 👋

Computer Engineering graduate (GPA 3.70) building end-to-end ML systems for **fraud & risk detection**. Focused on the full analytical workflow — data prep, model benchmarking, deployment, and interpreting results. Seeking a **Data Analyst / Data Scientist** role in risk, fraud, or customer analytics.

- 🎓 B.Sc. Computer Engineering, Ankara University (2022–2026)
- 🎓 Associate Degree, Computer Programming, Ufuk University (2020–2022, GPA 3.88)
- 📍 Ankara, Turkey
- 📫 dogukanfiliz@hotmail.com

## 🚀 Featured Project

### [Deepfake Voice Fraud Detection](https://github.com/dogukan-filiz/deepfake-voice-fraud-detection)
End-to-end system detecting AI-generated speech for banking call-center and telephony authentication scenarios, where cloned voices can bypass voice-biometric identity checks.

- Evaluated an **SSL+AASIST** model (XLSR-300M self-supervised frontend + graph-attention classifier): **77.8% accuracy**, 0.79 weighted F1, ~1.2s mean inference latency (p95: 2.1s)
- Uncovered severe domain shift under cross-domain conditions (re-recorded/telephony-degraded audio): accuracy dropped to 50.6%
- Redesigned around a **four-tier fallback chain**, adding a broad-domain model (DF Arena 1B, trained across 8 corpora) for robustness under acoustic degradation
- Deployed full-stack: FastAPI inference backend, Vite + React dashboard (file upload + live mic capture), MongoDB with JSON fallback, 16/16 unit tests passing

## 🛠️ Tech Stack

**Data & ML:** Python (pandas, NumPy, scikit-learn, PyTorch), SQL, Matplotlib, Seaborn
**Databases:** PostgreSQL, MySQL, MongoDB
**Tools & Frameworks:** Git, FastAPI, React, Jupyter, Kaggle
**Other Languages:** C#, Java, C, JavaScript, HTML/CSS

## 💼 Experience

- **HAVELSAN** — Test Automation Software Team Intern (Jul–Aug 2025)
- **ArveOn Bilişim** — Intern, ASP.NET & PostgreSQL (Aug–Sep 2021)

## 🌐 Languages

Turkish (Native) · English (B2)
