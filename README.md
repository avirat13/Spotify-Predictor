# Spotify Popularity Predictor

Analyzed a dataset of 100,000+ Spotify tracks to uncover what makes a song popular. The project covers end to end data cleaning, feature engineering, exploratory data analysis, and a decision tree classifier that predicts whether a song will have high, mid, or low popularity based on its audio features.

---

## Findings

- **Loudness and danceability are the strongest drivers of popularity**
- **High popularity songs score significantly higher in danceability and energy**
- **Instrumental songs tend to perform poorly in popularity scores**
- **The pop and dance genres consistently rank highest in average popularity**
- **Melancholic and intense moods produce the least popular songs on average**
- **High popularity songs cluster around valence 0.5-0.7 and energy 0.6-0.8**

---

## Tech Stack
- Python, pandas, numpy
- scikit-learn (decision tree classifier)
- seaborn, matplotlib
- Power BI (dashboard)

---

## Project Structure
```
spotify-project/
  data/          # raw and cleaned csv files
  outputs/       # charts and power bi ready export
  notebooks/     # jupyter notebooks
  README.md
```

---

## Model
Decision tree classifier trained on 80k+ songs with features: danceability, energy, valence, loudness, acousticness, instrumentalness. Predicts popularity tier as High, Mid, or Low.

---

## Author
made by avirat13 — feel free to fork and build on it.
