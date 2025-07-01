# Sorare Goalkeeper Scoring Analysis: Impact of the 2025 Matrix Update

## Context

In 2025, Sorare updated their scoring system by **removing the negative decisive for goalkeepers** who concede three or more goals. This change particularly affects GKs from lower-tier teams, who face more shots but now aren’t punished as severely. Goalkeepers from lower-tier teams are typically more affordable in the Sorare market. This analysis explores whether that price gap is still justified under the updated scoring matrix.

## Goal

Analyze how the rule change impacts:
- Goalkeeper performance by **team quality** (based on ELO quintiles)
- **Home vs. away** performances
- Matchup effects across opponent strength
- Strategic implications for Sorare managers

## Repository Structure

sorare-goalkeeper-analysis
- notebooks
  - sorare_goalkeeper_matrix_analysis.ipynb
- data
  - csv files used in the analysis
- requirements.txt
- README.md
- .gitignore

## Summary of Key Findings

- **Goalkeepers from bottom-tier teams improved the most**, now scoring on par with mid-table goalkeepers.
- **Elite goalkeepers still top the charts**, largely due to more clean sheets.
- **Home advantage** narrows the gap between elite and budget goalkeepers.
- **Matchups still matter**, but the penalty for facing stronger teams is smaller.

## How to Run

1. Clone the repository  
```bash
git clone https://github.com/WilliamLuiten/Sorare_goalkeeper_scores.git
cd Sorare_goalkeeper_scores
```

2. Create and activate a virtual environment (optional but recommended)
```bash
python -m venv .venv
source .venv/bin/activate  # or .venv\Scripts\activate on Windows
Install dependencies
```

4. Install dependencies
```bash
pip install -r requirements.txt
Open the notebook
```

5. Open the notebook
```bash
jupyter notebook notebooks/sorare_goalkeeper_matrix_analysis.ipynb
```

## Contributing
PRs and suggestions are welcome! Please open an issue or contact me if you have feedback or questions.

📄 License
This project is licensed under the MIT License.
