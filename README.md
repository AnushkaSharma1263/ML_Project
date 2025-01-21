# ML_Project
Student Performance Analysis Tool

This repository contains a Python-based tool for analyzing student performance on quizzes, identifying weak areas, and generating actionable recommendations. The tool processes historical and current quiz data in JSON format to provide insights into topics, difficulty levels, and overall performance.

Features

Analyze student performance by topics and difficulty levels.

Identify weak areas and trends in quiz performance.

Generate actionable recommendations for improvement.

Flexible JSON-based input for quiz data.


Requirements

Ensure you have Python 3.x installed along with the following libraries:

pandas

json


You can install required libraries with:

pip install pandas

Usage

1. Prepare Your Data
Ensure you have the following files:

current_quiz_file.json: Contains the current quiz data.

historical_quiz_file.json: Contains the historical quiz data.


The JSON format for historical_quiz_file.json should be structured like this:


2. Run the Tool
Execute the script from the terminal:

python analysis_tool.py


3. View Insights and Recommendations
The script will output:

Insights: Weak areas and trends in performance.

Recommendations: Suggestions to improve performance in specific topics or difficulty levels.


Error Handling

The tool includes basic error handling to:

Manage missing or invalid JSON files.

Handle empty data gracefully.



Contributing

Contributions are welcome! Feel free to fork this repository, make improvements, and submit a pull request.


