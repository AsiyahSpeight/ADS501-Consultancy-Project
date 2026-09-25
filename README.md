# ADS501-Consultancy-Project

ADS-501 Consultancy Project — Bridging the Hiring Gap: A Data-Driven Analysis 
of ATS Screening Friction on LinkedIn

## Project Overview

This project examines whether job postings with more specific or numerous 
skill requirements show a different views-to-applies conversion pattern than 
postings with broader requirements, using a dataset of scraped LinkedIn job 
postings. The goal is to distinguish genuine talent scarcity from 
recruiting-system friction at the level of individual job postings, in 
support of the broader question of how automated screening and posting 
design may affect who applies for a role.

## Project Status

- **Module 2** (Background, Organization, Problem Area, Current Solution): Complete
- **Module 3** (Initial Data Collection Report, Selection Criteria, Data Description Report): Complete
- **Module 4** (Explore Data, Data Quality Report, Determine Data Mining Goals): EDA complete, 
  written sections in progress

## Repository Structure

- `notebooks/jobPostingsExploration.ipynb` — full exploratory data analysis, following an 
  8-step EDA framework, with 14 visualizations and written interpretations
- `data/` — not tracked in Git (see below)

## Getting the Data

Due to file size, dataset files are **not stored in this GitHub repository**
and are shared separately via Google Drive instead.

1. Download `jobs.zip` from this link: https://drive.google.com/drive/folders/1p9VPNsOrfkIMw6AhzF9wAoWhFVG6ez-I?usp=drive_link
2. Place it in a `data/` folder in your local copy of this repo
3. Unzip it so the folder structure matches: `data/companies/`, `data/jobs/`, 
   `data/mappings/`, and `data/postings.csv`
4. Open `notebooks/jobPostingsExploration.ipynb` and run all cells top to bottom

**Note:** the `data/` folder is intentionally excluded from Git (see
`.gitignore`) because these files exceed GitHub's 100 MB per-file limit.

## Dataset Source

Arshkon. (2024). *LinkedIn job postings (2023–2024)* [Data set]. Kaggle. 
https://www.kaggle.com/datasets/arshkon/linkedin-job-postings
