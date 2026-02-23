# Bo Nix 2024 Passing Analysis:

This project digs into where and how effectively Bo Nix threw the ball in 2024. By categorizing every pass attempt along two axes (throw depth and field location) we can get a clearer picture of his strengths and tendencies as a passer.

Analysis includes:
- Completion % by throw depth (Short, Medium, Deep)
- Completion % by field location (Left, Middle, Right)
- Completion % against each 2024 opponent
- Heatmap visualizations of passing zones
- An interactive ipywidgets tool to click through and explore game-level stats

# Project Strucutre:
Bo_Nix_Analysis_Project/
│
├── Heatmaps/                          # Heatmap visualizations of pass zones (Utilizes custom dataset)
├── Prediction & Completion Analysis/  # Completion % breakdowns by depth, location & opponent (Utilizes custom dataset)
├── Target Accuracy & Interactive Tool/ # ipywidgets-based interactive stat explorer (Utilizes custom dataset)
├── .gitignore
└── README.md

# Tools & Libraries:
- Python: Core language utilized
- Pandas: Data loading and data manipulation
- Matplotlib: Utilized for graph and visual creation
- Seaborn: Utilized for styling graphs and specifically heatmaps
- Jupyter Notebook: Main IDE environment used for its favorable utility in performing data analysis
- ipywidgets: Utilized in the interactive tool to allow for a user to toggle what stats they want to filter for

# How to Get Started:

1.)
git clone https://github.com/hsamala688/Bo_Nix_Analysis_Project.git
cd Bo_Nix_Analysis_Project

2.)
pip install pandas matplotlib seaborn ipywidgets jupyter

3.)
jupyter notebook

# Sample Outputs:

The project generates bar graphs showing Bo Nix's completion rate broken down by:
- Throw depth: How does his accuracy change on short vs. deep balls?
- Field location: Is he more accurate throwing left, right, or down the middle?
- Opponent: Which defenses gave him the most trouble?
Heatmaps provide a spatial view of his passing zones and tendencies across the field.

# Data Source:

Play-by-Play data sourced from nflverse, nfldatapy, and NFLsavant.com

## Example Visulations:

<img width="856" height="534" alt="Screenshot 2025-10-10 at 6 56 08 PM" src="https://github.com/user-attachments/assets/3e62ac8f-2360-47f9-977b-4b6745b2cecb" />



<img width="812" height="524" alt="Screenshot 2025-10-10 at 7 13 30 PM" src="https://github.com/user-attachments/assets/afeaba25-70a6-45fa-b2eb-28dcc458aa62" />
