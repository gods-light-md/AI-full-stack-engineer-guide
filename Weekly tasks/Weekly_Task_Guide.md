# Weekly Task Guide
### Execution layer for `Realistic_Journey.md` — 36 weeks, ~10–15 hrs/week

Each week follows the same rhythm so you never have to think about *how* to study, only *what*:
- **Mon–Tue:** learn the concept (course/docs/video)
- **Wed–Fri:** build something small with it (not a tutorial clone — a variation)
- **Sat:** review + write a short note in your own words (this is what makes it stick)
- **Sun:** rest, or catch-up buffer (protect this — burnout kills more learners than difficulty does)

---

## Weeks 1–5 · Foundation & Math
- **W1:** Python syntax, data structures, functions, OOP basics. Build: a CLI tool (to-do list or unit converter).
- **W2:** Git & GitHub properly (branches, PRs, .gitignore). Push everything from W1 with real commit history.
- **W3:** Linear algebra — vectors, matrices, dot product, eigenvalues (intuition only). Build: implement matrix multiplication from scratch, no libraries.
- **W4:** Probability & statistics — distributions, mean/variance, Bayes' theorem. Build: a small script analyzing a public dataset's stats by hand + with Pandas.
- **W5:** Calculus for ML — derivatives, gradients, chain rule intuition. Review week: write a 1-page note "why does gradient descent work?"

## Weeks 6–11 · Data & Classical ML
- **W6:** NumPy + Pandas deep dive. Build: clean a messy public dataset (Kaggle) end-to-end.
- **W7:** Matplotlib/Seaborn, EDA (exploratory data analysis) as a discipline. Build: an EDA notebook with 5+ visual insights on a new dataset.
- **W8:** Feature engineering + preprocessing pipelines (Scikit-learn Pipelines). Build: preprocessing pipeline reusable across 2 datasets.
- **W9:** Regression + classification algorithms (linear/logistic, decision trees). Build: baseline model on your Project 1 dataset.
- **W10:** Ensemble methods — Random Forest, XGBoost, LightGBM. Build: improve Project 1's accuracy with ensembling; document the before/after.
- **W11:** Model evaluation done properly (cross-validation, precision/recall/F1, confusion matrix, avoiding leakage). **Ship Project 1.**

## Weeks 12–18 · Deep Learning + Specialization Track
- **W12:** Neural network fundamentals from scratch (no framework) — forward/backward pass on a toy dataset.
- **W13:** Switch to PyTorch. Rebuild the W12 network in PyTorch. Learn training loops, DataLoaders.
- **W14:** CNNs (if CV track) or tokenization/embeddings (if NLP track). Build: first model in your chosen track.
- **W15:** Transfer learning (CV) or transformer architecture basics (NLP). Build: fine-tune a pretrained model.
- **W16:** Hugging Face (NLP) or YOLO/object detection (CV). Build: a working detector/classifier demo.
- **W17:** Model optimization — regularization, hyperparameter tuning, avoiding overfitting.
- **W18:** Polish + document. **Ship Project 2.**

## Weeks 19–23 · Generative AI & LLMs
- **W19:** Prompt engineering fundamentals — few-shot, chain-of-thought, structured outputs. Build: a prompt-testing notebook comparing 3 approaches on one task.
- **W20:** LangChain or LlamaIndex basics — chains, agents, memory.
- **W21:** Embeddings + vector databases (FAISS or ChromaDB). Build: embed and search your own document set.
- **W22:** RAG architecture — retrieval + generation pipeline end-to-end.
- **W23:** AI agents (tool-use, multi-step reasoning). **Ship Project 3** (RAG chatbot or AI agent).

## Weeks 24–28 · Backend + Deployment
- **W24:** FastAPI fundamentals — routes, request/response models, async basics. Build: wrap Project 3's model as an API.
- **W25:** Docker — Dockerfile, images, containers. Containerize your FastAPI app.
- **W26:** Cloud basics (pick one: AWS/Azure/GCP) — deploy the container, environment variables, basic security.
- **W27:** CI/CD basics (GitHub Actions) — auto-test and auto-deploy on push.
- **W28:** MLflow for experiment tracking + basic monitoring concepts. **Ship Project 4** (Project 3, now live on a URL).

## Weeks 29–31 · Frontend Enough to Ship
- **W29:** HTML/CSS/JS refresher — just enough to be dangerous.
- **W30:** Streamlit or Gradio (fast) OR React basics if you want a "real" frontend for your portfolio piece.
- **W31:** Wire your frontend to your deployed API from W26–28. Ship the UI update.

## Weeks 32–36 · Capstone + Employability Sprint
- **W32:** Scope your capstone (combine everything: ML/DL + GenAI + backend + frontend + DB). Write the architecture doc *before* coding.
- **W33:** Build the core pipeline.
- **W34:** Build the API + database layer (PostgreSQL/MongoDB).
- **W35:** Build/polish the frontend, deploy fully, record a 2-minute demo video, write the README (problem, architecture, decisions, results, what you'd improve).
- **W36:** Resume + GitHub profile + LinkedIn rebuild around the capstone. Start applying (see `06_Bonus_Extras.md`). Begin `04_Professional_Influence_Building.md` in earnest if you haven't already.

---

## Weekly Non-Negotiables (every single week, regardless of topic)
1. **Ship something**, even small — a script, a notebook, a PR. Passive learning weeks are where momentum dies.
2. **Write one paragraph** in your own words about what you learned. If you can't explain it simply, you didn't learn it — you copied it.
3. **Commit to GitHub** at least 3 times. A green contribution graph is a side-effect of doing the work, not a goal in itself — don't fake commits.
4. **Skip nothing above your current week.** If W14's content is hard, stay on W14 an extra 2–3 days rather than jumping ahead — see `Deep_Learning_Without_Rabbit_Holes.md` for exactly how to know when to move on vs. when you're stuck for the wrong reasons.
