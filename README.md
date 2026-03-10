# LAB M2-W1-Lab02: Pandas Manipulation, Visualization & Statistical Risk Thinking

Welcome to Module 2 wekk 1's Lab! In this scenario, you are acting as an **Audit Lead** for a Hospital Finance Board. 

Your goal is to investigate clinical billing data, identify statistical risks (like right-skewness and heteroscedasticity) that break the assumptions of Ordinary Least Squares (OLS), and build a leakage-free machine learning pipeline.

---

### 🏗️ Required Project Structure

Since you are building a professional Machine Learning pipeline, your code cannot live in a single messy folder. During **STEP 1** of your lab instructions, you will need to build the following exact directory structure. 



```text
M2-W2-Lab01/
├── configs/           ← All paths and settings (config.yaml)
├── data/
│   ├── raw/           ← Put the original CSV here (Never modify this!)
│   └── processed/     ← Your cleaned data goes here
├── reports/
│   ├── figures/       ← Your diagnostic plots
│   ├── statistics/    ← Automated statistical summaries
│   └── risk_notes.md  ← YOUR final audit brief
├── notebooks/         ← Your scratchpad for EDA
├── requirements.txt   ← Python library dependencies (Provided)
├── README.md          ← You are here
└── src/               ← Your automated Python modules
    ├── data/          (utils.py, cleaning.py)
    ├── EDA/           (visualize.py, statistics.py)
    ├── features/      (build_features.py)
    └── models/        (train.py, predict.py)
