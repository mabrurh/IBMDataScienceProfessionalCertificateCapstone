# IBMDataScienceProfessionalCertificateCapstone
# SpaceX Data Analysis and Visualization

## Description
This repository contains various Jupyter Notebooks and a Dash application focused on the analysis and visualization of SpaceX launch data. The files cover different aspects including data collection, data wrangling, exploratory data analysis (EDA), machine learning predictions, and creating interactive dashboards.

## Contents

### 1. Exploratory Data Analysis and Visualization
**File:** `edadataviz.ipynb`
- Conducting Exploratory Data Analysis (EDA) and creating visualizations using Python libraries.
- **Dependencies:** pandas, numpy, matplotlib, seaborn

### 2. SQL and Exploratory Data Analysis with SQLite
**File:** `jupyter-labs-eda-sql-coursera_sqllite.ipynb`
- Learning SQL and performing EDA using SQLite.
- **Dependencies:** sqlite3, pandas, matplotlib

### 3. SpaceX Data Collection via API
**File:** `jupyter-labs-spacex-data-collection-api.ipynb`
- Collecting data from the SpaceX API and performing preliminary data analysis.
- **Dependencies:** requests, pandas

### 4. Web Scraping with Python
**File:** `jupyter-labs-webscraping.ipynb`
- Introduction to web scraping using Python.
- **Dependencies:** requests, beautifulsoup4, pandas

### 5. Analysis of Launch Site Locations
**File:** `lab_jupyter_launch_site_location.ipynb`
- Geospatial analysis of SpaceX launch sites and their impact on launch success.
- **Dependencies:** pandas, matplotlib, geopandas

### 6. SpaceX Data Wrangling
**File:** `labs-jupyter-spacex-Data wrangling.ipynb`
- Data wrangling techniques applied to SpaceX launch data.
- **Dependencies:** pandas, numpy

### 7. SpaceX Launch Records Dashboard
**File:** `spacex_dash_app.py`
- Dash web application to visualize SpaceX launch records with interactive elements.
- **Dependencies:** pandas, dash, dash_html_components, dash_core_components, plotly

### 8. SpaceX Machine Learning Prediction
**File:** `SpaceX_Machine Learning Prediction_Part_5.ipynb`
- Applying machine learning techniques to predict SpaceX launch outcomes.
- **Dependencies:** pandas, numpy, scikit-learn

## Setup and Usage

### Jupyter Notebooks
1. Ensure you have Jupyter Notebook installed. If not, you can install it via Anaconda or pip:
   ```sh
   pip install jupyter
2. Install the necessary dependencies for each notebook using pip:

    ```sh
    pip install pandas numpy matplotlib seaborn sqlite3 requests beautifulsoup4 geopandas scikit-learn
    ```

3. Open the desired notebook:

    ```sh
    jupyter notebook <notebook-name>.ipynb
    ```

    Run the cells sequentially to execute the code.

### Dash Application

1. Ensure you have the required libraries installed:

    ```sh
    pip install pandas dash plotly
    ```

2. Run the Dash application:

    ```sh
    python spacex_dash_app.py
    ```

3. Open your web browser and navigate to the local server address provided in the terminal to interact with the dashboard.

## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue if you have any suggestions or find any bugs.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

Special thanks to the data providers and the community for their support and resources.
