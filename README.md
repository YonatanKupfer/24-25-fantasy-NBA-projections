# NBA Fantasy Basketball Draft Projections and Rankings

Welcome to the NBA Fantasy Basketball Draft Projections and Rankings repository! This project aims to create accurate projections and draft rankings for fantasy basketball leagues using machine learning models and statistical analysis.

## 📋 Project Overview
This project analyzes the last three NBA seasons' data to project player performances for the upcoming 2024-2025 season. The main goal is to provide fantasy basketball enthusiasts with an accurate draft ranking based on projected player statistics in a 9-category head-to-head league format.

### 🏀 Fantasy Basketball Categories
The projections and rankings are tailored for a 9-category H2H league with the following categories:
- Field Goal Percentage (FG%)
- Free Throw Percentage (FT%)
- Points (PTS)
- Three-Pointers Made (3P)
- Assists (AST)
- Rebounds (REB)
- Blocks (BLK)
- Steals (STL)
- Turnovers (TO)

## 🔧 Installation and Setup

1. **Clone the Repository**
   ```
   https://github.com/YonatanKupfer/24-25-fantasy-NBA-projections.git
   ```
 ## ⚙️ Usage
1. **Running Jupyter Notebooks**
Open the relevant .ipynb file to start working with the data, projections, and draft rankings.

2. **Data Preprocessing**
Run the cells in the notebook to clean and process the raw data. This step handles missing values, team changes, and aggregates the per-game statistics.

3. **Model Training**
Train the machine learning models for each of the 9 categories by executing the relevant cells in the notebook. The script uses Random Forest and XGBoost models to project stats and stores the trained models for future use.

4. **Generating Draft Rankings**
The notebook will guide you through generating the draft rankings based on your league's settings. The final rankings will be displayed within the notebook and can be exported as a CSV file.

## 📊 Methodology
**Data Analysis and Feature Engineering**
* Processed three seasons of NBA data to extract key statistics per game.
* Adjusted projections based on player experience, age, and team changes.
* Incorporated weighted averages to handle incomplete or limited data for younger players.
  
**Machine Learning Models**
* Random Forest model was used to predict each fantasy category.
* Hyperparameter tuning was performed to optimize model performance.
* The models were validated using k-fold cross-validation.

**Draft Rankings**
* Calculated fantasy values using z-scores for each category, adjusted by the projected number of games played.
* Applied positional multipliers and category weights to reflect league-specific nuances.
* Combined model projections with expert rankings to generate accurate draft rankings.

## 🎯 Future Improvements
* Integrating injury reports and player news for dynamic projections.
* Adding support for custom league settings (e.g., different scoring formats, auction drafts).
* Expanding to include DFS (Daily Fantasy Sports) projections and analysis.

## 💡 Contributions
Contributions are welcome! Feel free to open an issue or submit a pull request for bug fixes, feature enhancements, or any other improvements.

## 🤝 Acknowledgements
- [Basketball-Reference](https://www.basketball-reference.com/) for providing comprehensive NBA statistics.
- The fantasy basketball community for offering valuable insights and inspiration.
- The developers of open-source Python libraries such as `pandas`, `scikit-learn`, and `matplotlib` that made this project possible.
- Fantasy basketball experts and analysts whose projections and rankings guided the model tuning process.

## 📧 Contact
For any questions or suggestions, feel free to reach out via email: [yonatank50@gmail.com].

Happy drafting! 🏀
