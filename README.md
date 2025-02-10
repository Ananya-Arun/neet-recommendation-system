# NEET Student Recommendation System
A Python-based student performance analysis and NEET rank prediction system.

## Overview
This project analyzes quiz performance data to provide personalized recommendations for NEET aspirants. It highlights weak areas, tracks improvement trends, and suggests strategies to enhance preparation. Additionally, it predicts a student's probable NEET rank based on historical quiz data.

## Features
- **Performance Analysis**: Tracks accuracy by topic and difficulty level.
- **Personalized Recommendations**: Suggests improvement strategies based on weak areas.
- **Student Persona Analysis**: Categorizes students based on their learning patterns.
- **NEET Rank Prediction**: Uses a logistic regression model to estimate the probable NEET rank.

## Dataset
- **Fixed_Quiz_Submission_Data.json**: Latest quiz submissions, including questions, topics, and responses.
- **Fixed_Current_Quiz_Data.json**: Current quiz data with question details and student answers.
- **Fixed_Historical_Quiz_Data.json**: Past 5 quiz performances, including scores and selected answers.

## Setup Instructions
### Prerequisites
- Python 3.7+
- Required libraries: Install using
  ```bash
  pip install pandas numpy matplotlib seaborn scikit-learn
  ```

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/neet-recommendation.git
   ```
2. Navigate to the project directory:
   ```bash
   cd neet-recommendation
   ```
3. Place `Fixed_Quiz_Submission_Data.json`, `Fixed_Current_Quiz_Data.json`, and `Fixed_Historical_Quiz_Data.json` in the project folder.
4. Run the main script:
   ```bash
   python main.py
   ```

## File Structure
```
neet-recommendation/
│── Fixed_Quiz_Submission_Data.json   # Latest quiz submissions
│── Fixed_Current_Quiz_Data.json   # Current quiz data
│── Fixed_Historical_Quiz_Data.json   # Past quiz data
│── neet-recommendation.ipynb  # Google Colab Notebook
│── README.md  # Project documentation
```

## Insights and Visualizations
- **Accuracy by Topic**: Bar chart displaying topic-wise performance.
- **Accuracy by Difficulty**: Insights into performance across different difficulty levels.
- **Personalized Recommendations**: List of suggested topics and improvement strategies.

## Demo Video
A 2-5 minute video demonstrating:
1. How the script analyzes quiz data.
2. Generated insights and recommendations.
3. NEET rank prediction process.

## Contribution
Feel free to fork the repository and submit pull requests for improvements.

## License
This project is licensed under the MIT License.


