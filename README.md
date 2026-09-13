# ADS501-Consultancy-Project

ADS-501 Consultancy Project — Duolingo vocabulary retention analysis



\## Getting the Data



Due to file size, dataset files are \*\*not stored in this GitHub repository\*\* and

are shared separately via Google Drive instead.



\### Option A: Use the pre-filtered dataset (recommended, fastest)

1\. Download `duolingoFrDe.csv` from this link: \[PASTE YOUR GOOGLE DRIVE LINK HERE]

2\. Place it in a `data/` folder in your local copy of this repo

3\. Open `notebooks/dataExploration.ipynb` — it's already set up to read from this file



\### Option B: Regenerate it yourself from the raw dataset

1\. Download the raw dataset (`settles.acl16.learning\_traces.13m.csv.gz`, \~379 MB)

&#x20;  from Harvard Dataverse:

&#x20;  https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/N8XJME

2\. Place it in your local `data/` folder

3\. Run through `notebooks/dataExploration.ipynb` to filter it down to French and

&#x20;  German learners and reproduce `duolingoFrDe.csv` yourself



\*\*Note:\*\* the `data/` folder is intentionally excluded from Git (see `.gitignore`)

because these files exceed GitHub's 100 MB per-file limit.

