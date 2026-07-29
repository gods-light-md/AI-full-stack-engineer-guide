# Bonus Extras
### Useful things that weren't asked for directly, added because they close obvious gaps in a plan like this

---

## 1. Current 2026 market snapshot (so your plan is grounded, not guessed)
- AI Engineer roles are consolidating into a hybrid profile: ML fundamentals + GenAI frameworks (LangChain etc.) + MLOps/deployment — companies are explicitly hiring for this combination rather than narrow specialists.
- Generic "ML Engineer" job titles are fragmenting into distinct paths: Applied ML Engineer, ML Platform/Infrastructure Engineer, LLM/AI Engineer, AI Product Engineer, Responsible AI specialist — worth deciding which of these you're aiming for by month 4–5.
- PyTorch remains the dominant deep learning framework in job postings — prioritize it over TensorFlow if you must choose.
- Employers increasingly prioritize demonstrated projects and production judgment over certificates — reinforces everything in `03` and `05`.
- MLOps and infrastructure-adjacent skills are among the fastest-growing and hardest-to-fill demand areas — don't treat modules 13/14 in your original roadmap image as optional.
- Reported 2026 salary ranges vary widely by region and seniority; treat any specific number you see online as directional, not a guarantee — verify current figures for your market before negotiating.

*(Sources consulted: Scaler AI Engineer Roadmap 2026, 365 Data Science ML Job Outlook 2026, Acceler8 Talent 2026 ML Roles report, HeroHunt.ai Fastest Growing AI Roles 2026, Medium/Santosh Rout "Top AI & ML Jobs Dominating 2026" — accessed July 2026.)*

## 2. Portfolio project specs (concrete, not vague "build a project")
Your roadmap image already suggests good project ideas (heart disease prediction, face recognition attendance, AI chatbot/LLM app, resume screening AI, image classifier, object detection, e-commerce/recommendation system, AI agent with RAG). For each project you build, include these 6 things or it doesn't count as portfolio-ready:
1. A one-paragraph problem statement (what real problem does this solve).
2. An architecture diagram (even hand-drawn/Excalidraw is fine).
3. The actual deployed link (not just code).
4. A short demo video or GIF (recruiters skim; they won't run your code).
5. A "decisions & tradeoffs" section — what you chose and why, what you'd change with more time.
6. Clean, commented code with a requirements.txt/environment file so anyone can reproduce it.

## 3. A minimal interview-prep layer (not in your original ask, but you'll need it around week 30+)
- **Technical:** be ready to whiteboard your own project's pipeline, explain one algorithm deeply (whichever you used most), and answer basic system-design-for-ML questions (how would you scale this, how would you monitor drift).
- **Behavioral:** have 3 stories ready in STAR format (Situation, Task, Action, Result) — ideally pulled from real moments in your projects (a bug you fixed, a tradeoff you made under time pressure, a mistake you caught).
- **Take-home/live coding:** practice basic Python/data manipulation problems weekly starting week 25 onward — 20–30 minutes, 2x/week is enough; don't turn this into a second curriculum.

## 4. Tool-stack cheat sheet (so you're not guessing which of 3 options to pick)
| Category | Default pick | Alternative (only switch if you have a specific reason) |
|---|---|---|
| Deep learning framework | PyTorch | TensorFlow |
| GenAI orchestration | LangChain | LlamaIndex |
| Vector DB | ChromaDB (local, simple) | FAISS / Pinecone (production scale) |
| Backend | FastAPI | Flask |
| Deployment/cloud | AWS (largest job-market footprint) | Azure / GCP |
| Experiment tracking | MLflow | Weights & Biases |
| Fast AI demo UI | Streamlit or Gradio | React (only if you want full frontend control) |
| Database | PostgreSQL | MongoDB (if your data is more document-like) |

## 5. Communities worth being part of (quality over quantity, matches `04`)
- A focused Discord/Slack around your chosen specialization (LangChain, Hugging Face, or a local AI/ML meetup group) rather than huge generic "learn AI" servers.
- Kaggle — even without competing seriously, reading top notebooks on datasets you've also worked with is a fast way to see better technique.
- GitHub Discussions on 1–2 libraries you actually use.

## 6. A note on avoiding shiny-object syndrome with new tools
New frameworks and models will launch constantly during your 9-month journey — that's guaranteed. Rule: **don't switch your core stack mid-project.** Note new tools in a running "watchlist," evaluate the list once a month, and only adopt something new when starting your *next* project, never mid-build.

## 7. Realistic budget note
Most of this roadmap is learnable free (official docs, free tiers of cloud providers, free course content, YouTube, open datasets). Paid bootcamps/subscriptions can accelerate structure and mentorship but are not required to hit the milestones in `01` and `02` — don't let budget be a blocker to starting.

## 8. Physical/mental sustainability (rarely mentioned in roadmaps, quietly the #1 dropout cause)
- Protect one full rest day per week (built into `02`'s weekly rhythm) — this isn't optional, it's what makes month 6 possible.
- Expect motivation dips around week 8–10 and week 20–22 (common pattern after the "beginner excitement" fades and again mid-specialization when things get genuinely hard). Knowing it's coming makes it easier to push through rather than assume something's wrong with you.
