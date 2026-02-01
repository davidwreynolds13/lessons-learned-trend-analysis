Lessons Learned Trend Analysis

OVERVIEW: This project demonstrates a data analytics workflow applied to a lessons-learned use case. Using synthetically generated records, the analysis identifies recurring trends, severity patterns, and areas for operational improvement. The goal is to show how structured data analysis can support decision-making, process improvement, and leadership recommendations. 
This project reflects real-world analytical approaches commonly used in operations, training evaluation, and performance improvement environments.
  
Tools Used: Python, pandas, NumPy, matplotlib, Google Colab

The dataset simulates lessons-learned records with the following fields:
             
  • Date of observation

  • Operational category (e.g., Training, Equipment, Logistics)

  • Severity level (1–5)

  • Unit type

  • Status (Open / Closed)

Data Note:
All data used in this project is synthetically generated for demonstration purposes. No real, sensitive, or classified information is included.

The analysis follows a structured, reproducible workflow:

 • Data generation and validation

 • Data cleaning and preprocessing

 • Exploratory data analysis (EDA)

 • Trend analysis by category and time

 • Severity and status distribution analysis

 • Visualization of key findings

Certain operational categories appear more frequently in lessons-learned records, indicating recurring problem areas

Higher-severity issues tend to cluster around specific categories and unit types

A majority of records transition to a closed status, but higher-severity issues remain open longer on average

(Exact results will vary based on synthetic data generation parameters.)

The notebook produces visualizations such as:

 • Frequency of lessons-learned by category

 • Severity distribution

 • Time-based trends

 • Status comparisons

These visualizations are designed to support executive-level briefings and data-driven recommendations.

HOW TO RUN:

    Clone the repository or download the notebook

    Open eda_lessons_learned.ipynb in Jupyter Notebook or Google Colab

    Run cells sequentially from top to bottom

Required libraries:

    pip install pandas numpy matplotlib

This project is representative of analytics tasks found in:

 • Operations analysis

 • Lessons-learned programs

 • Performance improvement initiatives
 
 • Training and evaluation environments

It demonstrates the ability to translate structured data into actionable insights for stakeholders.

DISCLAIMER: This project is for educational and portfolio purposes only. All data is fictional and intended solely to demonstrate analytical techniques and methodology.
