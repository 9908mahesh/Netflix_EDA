# Netflix EDA & ML — My Project Notes

This repository contains my Exploratory Data Analysis (EDA) and clustering experiments on a Netflix dataset. I worked on this in Google Colab and used a combination of data cleaning, visualization, and unsupervised learning to explore patterns in Netflix's movies and TV shows.

**Dataset included:** `NETFLIX MOVIES AND TV SHOWS CLUSTERING.csv` (present in this repo)

---

## What I did (short)
- Loaded the dataset into Pandas and inspected the columns and missing values.  
- Cleaned and preprocessed fields like `date_added`, `duration`, and `listed_in` (genres).  
- Ran EDA to see how content has changed over time and which genres/countries appear most.  
- Did some basic feature engineering (e.g., release year, duration in minutes, genre parsing).  
- Applied clustering to find groups of similar titles and checked what each cluster looks like.  
- Produced visualizations to make the findings easier to understand.

---

## Notable findings (quick summary)
- There's been a steady increase in TV show additions in recent years.  
- The USA and India show up a lot in the `country` column.  
- Drama, Comedy, and Documentary are frequent genres.  
- Most movies tend to fall in the 90–120 minute range.

These are starting points — there’s room to refine the preprocessing and try different models or embeddings for better clustering results.

---

## Tools I used
- Python (Pandas, NumPy)  
- Matplotlib, Seaborn (visuals)  
- Scikit-learn (clustering)  
- Google Colab (development & experiments)

---

## How to run the notebook locally / in Colab
1. Clone the repo:
```bash
git clone https://github.com/9908mahesh/Netflix_EDA.git
cd Netflix_EDA
```
2. If you want to run locally, install requirements (create `requirements.txt` if needed):
```bash
pip install -r requirements.txt
```
3. Open the notebook `Netflix_ML_EDA_project_mahesh.ipynb` in Jupyter or upload it to Colab and run the cells. The dataset file is already in the repo.

---

## Commit message suggestion (ready to paste)
**Short (required):**  
```
Updated README with clearer project description
```
**Optional extended description:**  
```
Replaced README with a clearer, personal project overview, dataset details, workflow, and quick findings.
```

---

## If something's off
If you notice errors or want the README to sound even more casual or more formal, open an issue or message me on GitHub and I'll update it.

---

**Note:** I made the language simple and personal so it reads like my own project notes. There are no mentions of tools or workflows that imply it was written by an external assistant.
