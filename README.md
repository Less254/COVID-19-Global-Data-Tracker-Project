# COVID-19-Global-Data-Tracker-Project 

COVID-19 Global Data Tracker
Description
This project provides a comprehensive analysis of COVID-19 data across the globe, visualizing trends, patterns, and impacts of the pandemic through interactive Jupyter notebooks. The tracker presents critical insights about infection rates, mortality, recovery trends, and geographical distribution of cases.
Objectives

Track and visualize the global spread of COVID-19 over time
Analyze country-specific COVID-19 metrics and comparative analysis
Identify patterns in case growth, mortality rates, and recovery rates
Create interactive visualizations for better understanding of pandemic data
Provide insights that could inform public health decision-making

Tools and Libraries Used

Python 3.x - Core programming language
Pandas - Data manipulation and analysis
NumPy - Numerical operations and array handling
Matplotlib - Static data visualization
Seaborn - Enhanced statistical visualizations
Plotly - Interactive visualizations
Folium - Interactive map visualizations
Jupyter Notebook - Interactive development environment
requests - API calls to retrieve updated COVID-19 data
datetime - Time series analysis and date formatting

Data Sources

Johns Hopkins University CSSE COVID-19 Dataset
Our World in Data COVID-19 Dataset
World Health Organization (WHO) COVID-19 Dashboard
National health departments' open data

How to Run the Project
Prerequisites

Python 3.6 or higher
Jupyter Notebook or JupyterLab

Installation

Clone this repository:
git clone https://github.com/yourusername/covid19-global-tracker.git
cd covid19-global-tracker

Create a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

Install required packages:
pip install -r requirements.txt


Running the Notebooks

Start Jupyter Notebook:
jupyter notebook

Open the main analysis notebook:
covid19_analysis.ipynb

Run the cells sequentially to reproduce the analysis

Project Structure
covid19-global-tracker/
├── data/                    # Raw and processed data files
├── notebooks/               # Jupyter notebooks
│   ├── covid19_analysis.ipynb    # Main analysis notebook
│   ├── data_preparation.ipynb    # Data cleaning and preprocessing
│   └── visualizations.ipynb      # Dedicated visualization notebook
├── src/                     # Python modules
│   ├── data_loader.py       # Functions to load and update data
│   ├── visualizations.py    # Visualization functions
│   └── utils.py             # Utility functions
├── requirements.txt         # Project dependencies
└── README.md                # Project documentation
Key Insights and Reflections
Pandemic Patterns

Identified distinct waves of infection across different regions
Documented correlation between policy implementation and case reduction
Analyzed vaccination rollout impact on mortality rates

Technical Challenges

Managing and cleaning inconsistent data reporting from different countries
Creating scalable visualizations that work with varying data densities
Balancing comprehensive analysis with performance considerations

Future Improvements

Implement automated data updates from public health APIs
Add predictive modeling for trend forecasting
Develop a web dashboard for non-technical users
Include demographic analysis of vulnerable populations
