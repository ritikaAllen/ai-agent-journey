# Phase 1 — Foundations Progress Tracker

> 8 weeks · 1–2 hrs/day · 4 GitHub projects  
> ✅ = Done · ☐ = Pending · ⭐ = Milestone project  
> Updated automatically with each push.

---

## Week 1–2 · Data Foundations

| Status | Day | Task | Sub-step | Commit |
|--------|-----|------|----------|--------|
| ✅ | Day 1 | NumPy — arrays & reshape | Create arrays: `np.array`, zeros, ones, arange, linspace | `d8bfa2f` |
| ✅ | Day 1 | NumPy — arrays & reshape | Shape & dimensions: `.shape`, `.ndim`, `.size`, `.dtype` | `d8007e8` |
| ✅ | Day 1 | NumPy — arrays & reshape | Reshape: `.reshape()`, `-1` wildcard, why shape matters for AI | `d8007e8` |
| ✅ | Day 2 | NumPy — slicing & broadcasting | Slicing 1D & 2D: `arr[2:5]`, `arr[::-1]`, `matrix[:, 1]` | `d8007e8` |
| ✅ | Day 2 | NumPy — slicing & broadcasting | Broadcasting rules: add arrays of different shapes | `d8007e8` |
| ✅ | Day 2 | NumPy — slicing & broadcasting | AI connection: image `(H,W,3)`, token batch `(batch, seq_len)` | `d8007e8` |
| ✅ | Day 3 | Pandas — creating & reading | `pd.read_csv`, `df.head()`, `df.info()`, `df.describe()` | `ea191df` |
| ✅ | Day 3 | Pandas — indexing & selecting | `iloc`, `loc`, conditional selection, setting index | `e15caa0` |
| ✅ | Day 4 | Pandas — summary & grouping | `.mean()`, `.unique()`, `.value_counts()`, `.map()` | `980fed0` |
| ✅ | Day 4 | Pandas — grouping & sorting | `groupby`, `sort_values`, multi-index | `b97f9bf` |
| ✅ | Day 4 | Pandas — data types & missing | `.isnull()`, `.fillna()`, `.dropna()`, `.astype()` | `157d817` |
| ☐ | Day 5 | Data Cleaning — missing values | Drop, fill mean/median/mode, ffill strategies | — |
| ☐ | Day 5 | Data Cleaning — scaling & encoding | MinMaxScaler, StandardScaler; why models need scaling | — |
| ☐ | Day 5 | Data Cleaning — dates & encoding | Parse dates properly, fix UTF-8 encoding errors | — |
| ☐ | Day 5 | Data Cleaning — inconsistent data | Fix typos and inconsistent entries with fuzzy matching | — |
| ☐ | Day 6–7 | Data Visualisation — Seaborn | Line, bar, scatter, histograms with Seaborn | — |
| ☐ | Day 6–7 | Data Visualisation — subplots | Subplots, heatmaps, colour encoding | — |
| ☐ | Day 8–10 ⭐ | Project 1 — Dataset Explorer | Choose a Kaggle dataset | — |
| ☐ | Day 8–10 ⭐ | Project 1 — Dataset Explorer | Clean: handle nulls, fix types, normalise | — |
| ☐ | Day 8–10 ⭐ | Project 1 — Dataset Explorer | Answer 5 business questions with Pandas | — |
| ☐ | Day 8–10 ⭐ | Project 1 — Dataset Explorer | Produce 3 Seaborn charts, each answering one question | — |
| ☐ | Day 8–10 ⭐ | Project 1 — Dataset Explorer | Write README: dataset, questions, findings, learnings | — |

---

## Week 3–4 · ML Intuition

| Status | Day | Task | Sub-step | Commit |
|--------|-----|------|----------|--------|
| ☐ | Day 11 | 3Blue1Brown — neural net intuition | Video 1: What is a neural network? (~19 min) | — |
| ☐ | Day 11 | 3Blue1Brown — neural net intuition | Video 2: Gradient descent, how neural nets learn (~21 min) | — |
| ☐ | Day 11 | 3Blue1Brown — neural net intuition | Video 3 & 4: Backpropagation + calculus (~24 min) | — |
| ☐ | Day 12 | Intro to ML — decision trees | How models work, first ML model with decision tree | — |
| ☐ | Day 12 | Intro to ML — model validation | Train/test split, MAE, underfitting vs overfitting | — |
| ☐ | Day 13 | Intro to ML — random forests | Why random forests beat single decision trees | — |
| ☐ | Day 13 | Intermediate ML — missing & categorical | Handle missing values, encode categorical variables | — |
| ☐ | Day 14 | Intermediate ML — pipelines & CV | sklearn Pipeline, cross-validation | — |
| ☐ | Day 14 | Intermediate ML — XGBoost | Gradient boosting, `n_estimators`, early stopping | — |
| ☐ | Day 15 | Feature Engineering | Mutual information, create new features, K-Means as feature | — |
| ☐ | Day 16–17 | fast.ai — Lesson 1 & 2 | Train image classifier; deploy to Hugging Face Spaces | — |
| ☐ | Day 17–18 | fast.ai — Lesson 3 & 4 | Neural net foundations; NLP classification with transformers | — |
| ☐ | Day 18 | Google ML Crash Course | Linear/Logistic Regression, Neural Nets, Embeddings, LLMs module | — |
| ☐ | Day 19–20 ⭐ | Project 2 — First ML Model | Explore Titanic dataset: survival rates by class, sex, age | — |
| ☐ | Day 19–20 ⭐ | Project 2 — First ML Model | Clean data: fill Age nulls, encode Sex and Embarked | — |
| ☐ | Day 19–20 ⭐ | Project 2 — First ML Model | Train RandomForestClassifier, tune max_depth and n_estimators | — |
| ☐ | Day 19–20 ⭐ | Project 2 — First ML Model | Evaluate: accuracy, confusion matrix, classification_report | — |
| ☐ | Day 19–20 ⭐ | Project 2 — First ML Model | Write README: approach, accuracy, what you learned | — |

---

## Week 5–6 · Neural Nets & Transformers

| Status | Day | Task | Sub-step | Commit |
|--------|-----|------|----------|--------|
| ☐ | Day 21 | Intro to NLP — text classification | Tokenisation, bag of words, text vectorisation | — |
| ☐ | Day 21 | Intro to NLP — word vectors | Word vectors, semantic similarity, word2vec intuition | — |
| ☐ | Day 22 | Intro to Deep Learning — layers | Dense layers, activation functions (ReLU, sigmoid) | — |
| ☐ | Day 22 | Intro to Deep Learning — training | SGD, batch size, epochs, learning rate, early stopping | — |
| ☐ | Day 23 | fast.ai — Lesson 5 | Build neural net from scratch: matrix multiply, activations, gradients | — |
| ☐ | Day 24 | fast.ai — Lesson 6 | Random forests from scratch; why ensembles work; feature importance | — |
| ☐ | Day 25 | Karpathy GPT — Session 1 | First ~60 min: tokenisation, bigram model, embeddings setup | — |
| ☐ | Day 26 | Karpathy GPT — Session 2 | Second ~60 min: self-attention, multi-head attention, transformer block | — |
| ☐ | Day 27 | Tokenisation hands-on | Install tiktoken, tokenise sentences, count tokens | — |
| ☐ | Day 28 | Attention — implement from scratch | Scaled dot-product attention in NumPy; visualise attention weights | — |
| ☐ | Day 29–30 ⭐ | Project 3 — nanoGPT on custom text | Clone nanoGPT repo | — |
| ☐ | Day 29–30 ⭐ | Project 3 — nanoGPT on custom text | Choose text dataset (100KB+) | — |
| ☐ | Day 29–30 ⭐ | Project 3 — nanoGPT on custom text | Prepare data: run data prep script, check train.bin / val.bin | — |
| ☐ | Day 29–30 ⭐ | Project 3 — nanoGPT on custom text | Train model: watch validation loss drop | — |
| ☐ | Day 29–30 ⭐ | Project 3 — nanoGPT on custom text | Generate text samples; write README with example outputs | — |

---

## Week 7–8 · APIs & First LLM Call

| Status | Day | Task | Sub-step | Commit |
|--------|-----|------|----------|--------|
| ☐ | Day 31 | Anthropic API — setup | Create account, get API key, store in `.env`, add to `.gitignore` | — |
| ☐ | Day 31 | Anthropic API — first call | Install `anthropic` SDK, make first working API call | — |
| ☐ | Day 31 | Anthropic API — Q&A script | Build Q&A loop: user inputs question, Claude answers | — |
| ☐ | Day 32–33 | GitHub portfolio — repo structure | Set up clean repo with subfolders per project | — |
| ☐ | Day 32–33 | GitHub portfolio — READMEs | Write/improve README for each project | — |
| ☐ | Day 33 | GitHub portfolio — commit hygiene | Review commit messages; use conventional commits | — |
| ☐ | Day 34–38 ⭐ | Project 4 — Data + Claude Pipeline | Choose dataset, load and analyse with Pandas | — |
| ☐ | Day 34–38 ⭐ | Project 4 — Data + Claude Pipeline | Extract 5 key statistics as a formatted string | — |
| ☐ | Day 34–38 ⭐ | Project 4 — Data + Claude Pipeline | Send summary to Claude via Anthropic API | — |
| ☐ | Day 34–38 ⭐ | Project 4 — Data + Claude Pipeline | Parse Claude's response, print insights cleanly | — |
| ☐ | Day 34–38 ⭐ | Project 4 — Data + Claude Pipeline | Polish into a single CLI Python script | — |
| ☐ | Day 34–38 ⭐ | Project 4 — Data + Claude Pipeline | Write README with architecture, example output, how to run | — |
| ☐ | Day 39–40 | Phase 1 review & gap check | Explain tokens / attention / overfitting without notes | — |
| ☐ | Day 39–40 | Phase 1 review & gap check | List any concepts still unclear → first Phase 2 questions | — |
| ☐ | Day 39–40 | Phase 1 review & gap check | Confirm: 4 projects live ✅ · 8 Kaggle certificates ✅ | — |
