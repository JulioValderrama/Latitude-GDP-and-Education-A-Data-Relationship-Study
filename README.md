# Latitude-GDP-and-Education-A-Data-Relationship-Study
This repository explores the relationship between geographic latitude, GDP per capita, and tertiary education enrollment across countries. It includes data analysis, visualizations, and regression models to uncover how geography impacts economic performance and education levels.
Latitude-GDP-Education Analysis
This project analyzes the relationship between geographic latitude, GDP per capita, and tertiary education enrollment across various countries. The goal is to uncover how proximity to the equator influences both economic performance and education levels globally.

Project Structure
markdown
Copy code
- data/
  - `Countries Position.csv`: Geographic information including latitude for each country.
  - `GDP per Capita.csv`: GDP data for countries from 2014 to 2023.
  - `Global Education.csv`: Tertiary education enrollment data.
  - `Population per Country.csv`: Population data for countries.
- `Analysis GDP and Education to Distance from Equator.ipynb`: Jupyter notebook containing the full analysis.
- `README.md`: Documentation for the project.
Installation and Setup
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/yourusername/Latitude-GDP-Education-Analysis.git
Navigate into the project folder:

bash
Copy code
cd Latitude-GDP-Education-Analysis
Install the necessary dependencies:

bash
Copy code
pip install pandas matplotlib seaborn
Open the Jupyter notebook:

bash
Copy code
jupyter notebook
Open the .ipynb file and run the analysis.

Datasets
Countries Position.csv: Contains geographical coordinates (latitude and longitude) for each country.
GDP per Capita.csv: Provides GDP per capita data for countries from 2014 to 2023.
Global Education.csv: Data on tertiary education enrollment for different countries.
Population per Country.csv: Population data for various countries.
Analysis Overview
The analysis explores the relationship between geographic latitude, GDP, and tertiary education enrollment. Key insights include:

Regression analysis shows how countries farther from the equator tend to have higher GDP and better education outcomes.
Box plots and scatter plots highlight the trends in the data.
Results and Visualizations
Key insights:

Countries farther from the equator tend to have higher GDP per capita.
Higher education enrollment rates are also associated with countries farther from the equator.
License
This project is licensed under the MIT License.
