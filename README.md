# FIFA 20 Player Analysis & Clustering
**Domain:** Sports | **Type:** EDA + Unsupervised ML

## Overview
Analysis of 18,278 FIFA 20 players across 100+ attributes. 
Includes complete EDA and KMeans clustering to identify player archetypes.

## Key Findings
- England produces the most players. Uruguay and Brazil produce the highest quality.
- Players peak at age 27-28 and decline sharply after 33.
- Right Wingers earn the most among offensive positions.
- 4 player clusters identified: Defenders, Attackers, Light Attackers, Box-to-Box Midfielders.

## Tech Stack
Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## Project Structure
- `fifa20.ipynb` — main notebook
- `players_20.csv` — dataset

## Models Used
KMeans Clustering with K=4 (selected via Elbow Method)
