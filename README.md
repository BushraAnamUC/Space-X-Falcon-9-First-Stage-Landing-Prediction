# Space Falcon 9 First Stage Landing Prediction

## Project Overview
The commercial space age is here, and companies are making space travel more affordable and accessible. SpaceX’s innovative reuse of rocket stages has significantly reduced launch costs, making it a leader in the industry. This project, titled **"Space Falcon 9 First Stage Landing Prediction"**, focuses on building a predictive model to determine whether the first stage of SpaceX’s Falcon 9 rocket will successfully land. This can help estimate the cost of a launch, which is critical for new competitors like Space Y to remain competitive in the market.

The project involves gathering and analysing SpaceX launch data, building machine learning models, and creating dashboards to visualise insights. The goal is to support Space Y in decision-making processes and optimise their business strategies.

---

## Objectives
1. Collect and preprocess SpaceX Falcon 9 launch data using APIs and web scraping.
2. Perform exploratory data analysis (EDA) to understand key features affecting first-stage landing outcomes.
3. Build machine learning models to predict whether the first stage will successfully land.
4. Create interactive dashboards for visualizing launch data and predictions.
5. Develop a comprehensive report and presentation to communicate findings.

---

## Advanced Data Science Skills Used
- **Data Collection:**
  - Consuming REST APIs with Python libraries (e.g., `requests`).
  - Web scraping using `BeautifulSoup`.
- **Data Wrangling and Cleaning:**
  - Handling JSON data.
  - Dealing with null values (e.g., calculating mean, one-hot encoding).
  - Filtering data for relevant rockets (e.g., Falcon 9 only).
- **Exploratory Data Analysis (EDA):**
  - Creating scatter plots, bar charts, and summary statistics using `Pandas`, `Matplotlib`, and `Seaborn`.
  - Writing and executing SQL queries to analyse datasets.
- **Machine Learning:**
  - Classification models using `Scikit-learn`.
  - Hyperparameter tuning with grid search.
  - Train-test splitting and model evaluation.
- **Data Visualization:**
  - Building interactive dashboards with `Plotly Dash`.
  - Generating interactive maps with `Folium`.
  - Visualising distances and clusters.
- **Reporting and Presentation:**
  - Creating reports and PowerPoint presentations summarising the findings.

---

## Project Directory Structure
```plaintext
Space-Falcon9-Landing-Prediction/
|— data/
|   |— raw_data.json               # Raw data collected from the API.
|   |— processed_data_1.csv          # Cleaned and preprocessed dataset.
|   |— processed_data_2.csv          # Cleaned and preprocessed dataset.
|— notebooks/
|   |— data_collection_api.ipynb   # Notebook for API
|   |— data_collection_webscraping.ipynb   # Notebook for web scraping.
|   |— data_wrangling.ipynb     # Data cleaning and preprocessing.
|   |— eda.ipynb                # Exploratory data analysis.
|   |— ml_models.ipynb          # Training machine learning models.
|— dashboard/
|   |— spacex_dash_app.py                # Plotly Dash interactive dashboard.
|— reports/
|   |— report.pdf                 # Final project report.
|   |— presentation.pptx          # PowerPoint presentation.
|— requirements.txt              # Required Python packages.
|— README.md                     # Project README file.

```

---

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Space-Falcon9-Landing-Prediction.git
   cd Space-Falcon9-Landing-Prediction
   ```

2. Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```

3. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks:
   ```bash
   jupyter notebook
   ```

5. To start the dashboard:
   ```bash
   python dashboard/dashboard.py
   ```

---

## Requirements
The project uses the following Python libraries:
```plaintext
beautifulsoup4
folium
matplotlib
numpy
pandas
plotly
requests
scikit-learn
seaborn
sqlalchemy
dash
```
All dependencies are listed in `requirements.txt`. Install them with:
```bash
pip install -r requirements.txt
```

---

## Findings
- **EDA Insights:**
  - Certain features such as payload mass, orbit type, and launch site significantly impact first-stage landing success.
  - The presence of null values in critical columns required imputation for accurate modeling.
- **Machine Learning Model:**
  - The best-performing model achieved an accuracy of ~90% in predicting first-stage landing success.
  - Hyperparameter tuning improved the model’s precision and recall.
- **Interactive Dashboard:**
  - The dashboard provides insights into historical launch records, success rates, and payload trends.
  - Interactive maps allow users to analyse launch site proximities and patterns.

---

## How to Contribute
Contributions are welcome! Feel free to submit a pull request or open an issue for bugs and feature requests.

---


