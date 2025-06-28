
# Sleep‑Behavior Analysis 📊😴

Analyse the impact of night‑time screen‑time, caffeine intake, daily activity, and room temperature on sleep duration and perceived sleep quality.  
The project ships with a **synthetic, but realistic 90‑day dataset** and a full Jupyter notebook that explores correlations, visualises patterns, and clusters users into sleep‑profile segments.

---

## Project structure

```
.
├─ data/
│  └─ sleep_behavior.csv        # 90‑day synthetic dataset
├─ notebooks/
│  └─ sleep_behavior_analysis.ipynb
├─ requirements.txt
└─ README.md
```

---

## Quick start

```bash
# 1. Clone the repo
git clone https://github.com/<your‑user>/sleep‑behavior-analysis.git
cd sleep‑behavior-analysis

# 2. Create a virtual environment and install dependencies
python -m venv .venv
source .venv/bin/activate   # Windows → .venv\Scripts\activate
pip install -r requirements.txt

# 3. Launch Jupyter
jupyter notebook notebooks/sleep_behavior_analysis.ipynb
```

If `data/sleep_behavior.csv` is missing, the notebook automatically regenerates the dataset.

---

## Notebook walk‑through

1. **Load & preview data** – discover the schema and basic stats.  
2. **Exploratory Data Analysis (EDA)** – distribution plots, box‑plots, scatterplots.  
3. **Correlation heat‑map** – identify key features linked to sleep duration.  
4. **Clustering** – K‑Means groups users into three archetypes:  
   - _High‑energy short‑sleepers_  
   - _Balanced sleepers_  
   - _Low‑activity poor‑sleepers_  
5. **Insights & next steps** – lays out potential extensions (wearable data, predictive models, personalised recommendations).

---

## How the synthetic data are generated

See the first cell in the notebook (or `scripts/generate_data.py`, if you extract the code) – NumPy draws realistic distributions for bed‑times, wake‑up times, caffeine, steps, etc., then tags each day with a **sleep_quality** label (`good | average | poor`) based on simple heuristics.

---

## Extending the project

* Swap in your own real data – preserve column names or adjust the load step.  
* Add feature‑engineering (e.g. rolling averages, circadian‑rhythm features).  
* Train a supervised classifier to *predict* `sleep_quality` from the numeric features.  
* Deploy results as a Streamlit or Dash dashboard.

---

## License

MIT – feel free to fork and build on top of this!

---

*Created with by **babak**, 2025.*
