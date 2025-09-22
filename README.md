# 2023–2024 NBA Player Stats: Playoffs Data Analysis

An analytical report on player performance and trends during the 2023–2024 NBA Playoffs.  
This repository contains the written report, project structure for reproducibility, and pointers to the dataset and methods used.

## 🔍 What’s inside
- **/report/**: Final PDF report (_2023-2024 NBA Playoff Performance Analysis Written Report.pdf_)
- **/data/**: Placeholder folders for raw and processed data (data files are **not** tracked)
- **/notebooks/**: Jupyter/Colab notebooks (add your analysis here if you want to share code)
- **/scripts/**: Optional Python/R scripts (e.g., data cleaning, metric calculations)
- **/figures/**: Static images exported from dashboards/plots
- **/docs/**: Any additional docs, exports, or images for the README

## 🌐 Interactive Dashboard
Explore the Tableau dashboards here: [Tableau Public – NBA Playoffs Analysis](https://public.tableau.com/views/NbaPlayoff2022-23Stats/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## 📄 Final report
- **PDF**: [`report/2023-2024_NBA_Playoff_Performance_Analysis_Written_Report.pdf`](report/2023-2024_NBA_Playoff_Performance_Analysis_Written_Report.pdf)

## 🧰 Methods (high level)
- Calculated **Net Rating (ORtg – DRtg)** to categorize team performance.
- Ranked **PPG** vs **Defensive Contribution** to identify balanced two-way players.
- Highlighted **U23** prospects with usage and net rating context.
- Identified **Offensive Gamechangers** using **Points + Assists** and color-coded **True Shooting %**.
- Built a composite **Defensive Metric** from SPG, BPG, and DRtg (scaled) to rank defenders.

> If you expose code, place your calculations in `/notebooks` or `/scripts` with clear docstrings and comments.

## 🗂️ Data
- **Source (Kaggle)**: 2023–2024 NBA Player Stats (Playoffs)  
  Shouqi, M. S. (2024). *2023–2024 NBA Player Stats (Playoffs)* [Dataset]. Kaggle. https://www.kaggle.com/datasets/mohamedsaqibshouqi/2023-2024-nba-player-stats-playoffs

> ⚠️ **Data policy**: Raw data files are intentionally **excluded** from version control. See `/data/.gitignore` for the pattern.  
> To reproduce the analysis, download the dataset from Kaggle and place files under `/data/raw`.

## ▶️ Quick start (recommended workflow)
1. **Clone** this repo
   ```bash
   git clone https://github.com/<your-username>/nba-playoffs-2023-2024-report.git
   cd nba-playoffs-2023-2024-report
   ```
2. **Add data** (not tracked):
   - Download the Kaggle dataset and place CSVs under `data/raw/`
3. (Optional) **Run notebooks / scripts**:
   - Put analysis notebooks in `/notebooks` and export any figures to `/figures`
4. **Open the report**:
   - `report/2023-2024_NBA_Playoff_Performance_Analysis_Written_Report.pdf`

## 💡 Reproducibility notes
- Keep large/raw files out of git (use `/data` as working area).
- If you later share code, consider adding an `environment.yml` or `requirements.txt`.

## 📜 Citation
If you reference this work, cite the dataset and this report:

**Dataset (APA):**  
Shouqi, M. S. (2024). *2023–2024 NBA Player Stats (Playoffs)* [Dataset]. Kaggle. https://www.kaggle.com/datasets/mohamedsaqibshouqi/2023-2024-nba-player-stats-playoffs

**This report:**  
Shahidi, R. (2025). *2023–2024 NBA Player Stats: Playoffs Data Analysis* (Report).

## 🛡️ License
This repository is released under the **MIT License** (see `LICENSE`).

---

**Author:** Ryan Shahidi  
**Contact:** rshahidi7@gmail.com · https://github.com/rshahidi7 · https://www.linkedin.com/in/ryanshahidi
