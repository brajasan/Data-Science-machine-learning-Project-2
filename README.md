# Indeed Data Science Jobs Market Analysis (2024)

## Project Overview
This project involves web scraping and exploratory data analysis (EDA) of job listings from the Indeed.com website. The focus is on analyzing the job market for data scientists across 130 companies in the USA as of October 2024. The goal is to extract insights regarding job trends, required skills, and technologies in demand.

## Table of Contents
- [Introduction](#introduction)
- [Tools & Modules Used](#tools--modules-used)
- [Data Collection](#data-collection)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Conclusion](#conclusion)
- [How to Run the Project](#how-to-run-the-project)

## Introduction
The job market for data scientists is rapidly evolving, and this project aims to provide a comprehensive analysis of current trends. By scraping job listings from Indeed, we can gather valuable data on job titles, companies, locations, and required skills.

## Tools & Modules Used
- **Python 3**
- **Jupyter Notebook**
- **Selenium**: For web scraping
- **Pandas**: For data manipulation and analysis
- **NumPy**: For numerical operations
- **Matplotlib**: For data visualization
- **Seaborn**: For statistical data visualization
- **Plotly**: For interactive visualizations
- **WordCloud**: For generating word clouds
- **IPython**: For displaying outputs in Jupyter

## Data Collection
Data is collected using Selenium to automate the web scraping process. The script navigates through job listings on Indeed, extracts relevant information, and stores it in a structured format.

## Exploratory Data Analysis
The EDA phase involves analyzing the collected data to uncover insights such as:
- The most common job titles and companies hiring data scientists
- Required skills and technologies
- Trends in job locations and remote work opportunities

Visualizations are created to represent the findings effectively.

## Conclusion
The analysis reveals that the job market for data science remains strong, with a significant demand for skills in Python, SQL, and machine learning technologies. The project highlights the importance of continuous learning and adaptation in this dynamic field.

## How to Run the Project
1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install required packages**:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook**:
   ```bash
   jupyter notebook indeed-eda-data-scientist.ipynb
   ```

4. **Follow the instructions in the notebook to execute the scraping and analysis.**

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
