# ReadME
# Intel_Products_Sentiment_Analysis
Intel Unnati Industrial Training Program 2024. Problem Statement : Intel Products Sentiment Analysis from Online Reviews

Project Overview:
This repository contains Python code for performing sentiment analysis on Intel desktop processor reviews. The analysis was conducted using Visual Studio Code and involves data scraping, cleaning, transformation, sentiment analysis, text summarization, and clustering to extract key insights and generate recommendations.

Key Features:
* Data scraping and cleaning
* Text preprocessing and transformation
* Sentiment analysis
* Text summarization
* Clustering
* Insight generation and recommendation

Dependencies:
* Python libraries required for data manipulation, analysis, and visualization (e.g., pandas, NumPy, Scikit-learn, NLTK, Transformers).

Usage:
1. Clone the repository.
2. Install required dependencies referring to requirements.txt
3. Open the project in Visual Studio Code.
4. Run the Python scripts in the appropriate order to perform data analysis and generate insights.
5. Explore the generated output files for results.

Structure
* data: Contains raw and processed data files. (raw files in Webscraping folder and preprocessed files in EDA_and_ML\Preprocessed_datset)
* scripts: Python scripts for scraping, data processing and analysis:
  - WebScraping file at WebScraping\Scrapper
  - Data Cleaning and Pre processing at EDA_and_ML\remove_duplicate.py and     
    EDA_and_ML\review_analysis.py
  - Machine learning model and Summary generation at 
    EDA_and_ML\cluster_analysis.py and EDA_and_ML\batchwise_summarize.py
* outputs: Stores generated output files at Summary_of_Sentiment_Analysis

Additional Notes: Refer to command_cheatsheet while running scrapper
