 # Mood Detection Using a Music Recommendation System

## Practicum Project

This repository contains the practicum project for developing a mood detection–based music recommendation system using data science techniques.

## Project Overview
This practicum project develops a mood detection–based music recommendation system using Spotify song metadata and audio features. Two publicly available Spotify datasets are used: spotify_dataset_1 (primary) and spotify_dataset_2 (supplementary). The datasets are harmonized by aligning shared audio features and metadata, then combined to improve coverage and robustness. Mood-related characteristics are inferred from interpretable audio features such as valence, energy, danceability, and tempo to generate personalized music recommendations.

## Repository Structure

data/
    raw/            # Original datasets (not tracked)
    processed/      # Cleaned datasets
notebooks/        # Jupyter notebooks for analysis and modeling
src/              # Reusable source code
reports/
figures/        # Generated plots and figures

## Tools and Technologies
- Python
- pandas, NumPy
- scikit-learn
- Jupyter Notebook

## Status
Week 1 completed.  
Week 2: Data preprocessing and exploratory data analysis (in progress).
