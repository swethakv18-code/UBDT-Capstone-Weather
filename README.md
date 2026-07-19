
🚀 SpaceX Launch Analysis Project
Overview
This repository presents a comprehensive data‑science workflow analyzing SpaceX Falcon 9 launch outcomes. The project follows the IBM Data Science Capstone (Coursera) structure, progressing from data collection to predictive modeling.

##Contents
| Notebook | Description |
| **01_data_collection_api** | Retrieves launch data using the SpaceX REST API. |
| **02_webscraping** | Extracts additional launch details from public web sources. |
| **03_data_wrangling** | Cleans, merges, and prepares datasets for analysis. |
| **04_eda_sql** | Performs SQL‑based exploratory analysis using SQLite. |
| **05_eda_dataviz** | Visualizes launch patterns and success rates. |
| **06_launch_site_location** | Maps launch sites and analyzes geospatial factors. |
| **07_dash_app** | Builds an interactive dashboard using Plotly Dash. |
| **08_machine_learning_prediction** | Trains classification models to predict launch success. |


##Tools & Libraries
Python, pandas, NumPy, scikit‑learn
Plotly Dash, Folium, SQLite
SpaceX API, BeautifulSoup


Getting Started
###Clone the repository:

bash
git clone https://github.com/<your‑username>/spacex‑launch‑analysis.git

###Install dependencies:

bash
pip install -r requirements.txt
Run notebooks sequentially in JupyterLab or VS Code.

###Launch the dashboard:

bash
python 07_spacex_dash_app-skv.py


#Results
The machine learning models I tested (logistic regression and decision tree) achieved around 85% accuracy in predicting launch success.

From my analysis, a few important patterns stood out:

Booster reuse plays a major role in whether a launch succeeds.

Launch site location matters — sites closer to the equator tend to support better payload efficiency.

The interactive dashboard I built makes it easy to explore success rates by site, booster version, and payload class.

My Insights
Working through this project helped me connect data collection, wrangling, visualization, and prediction into one workflow. The biggest takeaway was seeing how data from multiple sources (API + web scraping) can be combined to give a richer picture of launch outcomes. Building the dashboard also gave me hands‑on practice with Plotly Dash, which made the results more engaging and easier to interpret.


Objective
The goal of this project was not only to predict the likelihood of successful Falcon 9 launches, but also to practice the full data‑science pipeline — from collecting raw data through APIs and web scraping, to cleaning and visualizing it, and finally applying machine learning models. By completing each stage, I strengthened my skills in data wrangling, exploratory analysis, geospatial visualization, and predictive modeling. Building the interactive dashboard gave me hands‑on experience in presenting results in a way that is both clear and engaging.

References
IBM Data Science Capstone (Coursera): Course Link (coursera.org)

SpaceX API Documentation: GitHub Repository


## Final Presentation
You can view the complete presentation here:  
[Final_Project_Presentation.pdf](presentation/Final_Project_Presentation.pdf)
