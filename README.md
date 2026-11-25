# Spotify Global Trends 2026 Analysis

An exploratory data analysis examining how viral popularity (`viral_score`) relates to long-term chart longevity (`days`) across music genres on Spotify in 2026.

---

## Project Overview
- **Notebook:** [`spotify_global_trends_2026_analysis.ipynb`](spotify_global_trends_2026_analysis.ipynb)
- **Dataset Source:** [Spotify Global Trends 2026 on Kaggle](https://www.kaggle.com/datasets/mkaur1141/spotify-global-top-songs-2026) *(178 tracks across 13 features)*
- **Tools Used:** Python, Pandas, SQLite, Seaborn, Matplotlib

---

## Research Objectives
1. Which 3 genres gained the highest average `viral_score` (among genres with at least 10 tracks)?
2. Within those top 3 genres, does genre affect how many days a song stays on the chart?
3. Are there specific songs that stayed on the chart for an unusually long time (top 10% of days) despite having a below-average `viral_score`, and which genres do those tracks belong to?

---

## Key Findings  
- **Highest Average Virality:** K-Pop (17,553,166.40), Rock (14,341,186.43), and Pop (13,847,265.28) achieved the highest average viral scores among genres with 10+ tracks.  
- **Chart Staying Power:** Among those top 3 genres, Rock (736.86 average days) and Pop (630.57 average days) remained on the chart far longer than K-Pop (15.67 average days).  
- **Sustained Longevity Outliers:** 11 tracks reached the top 10% of chart duration despite below-average viral scores, led by Pop (6 tracks), followed by R&B (2), Rock (1), Indie Rock (1), and Hip Hop (1).  

---

## Takeaway
High initial virality does not guarantee long-term chart longevity. Playlist curators and marketing teams should avoid dropping tracks with modest initial viral scores too early, as genres like Pop and Rock show strong gradual staying power.
