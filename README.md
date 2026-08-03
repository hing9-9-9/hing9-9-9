# Heegyeong Chung (정희경)

**Undergraduate Researcher — Structured Financial Data · Applied AI Engineering**

B.S. candidate in Information Systems (major) and Industrial Engineering (double major)
at Hanyang University, Seoul.

I work on turning things that were not previously measured into numbers that can support a decision.
My main interests are the **explainability of models trained on structured (tabular) data**, and the
conditions under which predictive performance actually translates into sound operational judgement.

📧 dipi1631@hanyang.ac.kr &nbsp;·&nbsp; 🔗 [LinkedIn](https://linkedin.com/in/hgchung04)

---

## Selected Work

### [SemanticCreditCard](https://github.com/hing9-9-9/SemanticCreditCard) &nbsp;`Python`

An end-to-end experimental pipeline for credit-card fraud detection on semantically meaningful
transaction features.

- Compares Logistic Regression, Random Forest, XGBoost and LightGBM under a **time-based split**
  that reflects realistic deployment conditions.
- Handles extreme class imbalance **without resampling** — model selection is standardised on
  **PR-AUC**, operational quality is measured with **Precision@K** and **Card-Day Precision@K**,
  and the decision threshold is fixed on the validation set by maximising **F2**.
- Produces explainability and **explanation-stability** artefacts (SHAP, LIME, permutation
  importance, ALE/PDP), including repeated-run attribution analysis.

### [CHAI-Student/CRK-model-HG](https://github.com/CHAI-Student/CRK-model-HG) &nbsp;`Python` `FastAPI` `TensorRT`

The decision and settlement service for an unmanned smart vending machine — **primary author, 91 commits**
in an industry–academia project.

- Determines *what was taken and how many* from camera footage and load-cell readings alone,
  then finalises the payment amount. All inference runs **on-device** on a Jetson Orin Nano.
- Redesigned the internals while **preserving the external API contract**: 15 decision strategies
  reduced to 4 paths, 4 settlement layers to 2.
- **17 system invariants** (no double charging, no provisional value entering billing, and so on)
  are enforced through types and interfaces rather than documentation.
- **406 automated tests**, `ruff`, and GitHub Actions CI run continuously.

### [yonggi-nael-kkang](https://github.com/hjo0225/yonggi-nael-kkang) &nbsp;`TypeScript` `React`

A platform that certifies reusable-container use at baseball stadiums and turns it into a
collectible game-day record.

- Built for the Kakao Impact *Tech for Impact Campus* programme;
  received the **Innovative Technology Award**.

### [IS-NEW-WEB](https://github.com/hing9-9-9/IS-NEW-WEB) &nbsp;`TypeScript`

The official website of the Department of Information Systems, Hanyang University —
rebuilt independently to replace an outsourced system.

---

## Technical Skills

| Area | Tools |
| --- | --- |
| **Languages** | Python (primary), TypeScript / JavaScript, SQL |
| **Data & ML** | pandas, NumPy, SciPy, scikit-learn, Optuna, XGBoost, LightGBM, PyTorch |
| **Explainable AI** | SHAP, LIME, permutation importance, ALE / PDP |
| **Backend & Tooling** | FastAPI, pytest, ruff, GitHub Actions, uv, Git, Linux |
| **Edge Inference** | Jetson Orin Nano, TensorRT, ffmpeg / NVDEC |
| **Web** | React, Next.js, Node.js, MongoDB |

---

## Languages

Korean (native) · English (OPIc IH) · Japanese (JLPT N2)
