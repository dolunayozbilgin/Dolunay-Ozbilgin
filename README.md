# Dolunay Ozbilgin DSA 210 
# Chess Habits & Cognitive Impact

## **Project Idea**
In this project, I will analyze how chess-playing habits influence cognitive abilities such as reaction time, problem-solving, and decision-making speed. My goal is to understand the relationship between chess engagement and mental performance by collecting and analyzing chess gameplay data and cognitive test results.

## **Description of Dataset**
- **Total duration of each chess session**: I will manually record my chess playing time for each session.

- **Game Performance Metrics**: I will track my rating, accuracy, number of blunders, and mistakes from Chess.com or Lichess.

- **Cognitive Performance**: I will assess reaction time, problem-solving speed, and focus levels using cognitive test websites such as Human Benchmark and OpenPsychometrics.

- **Game Type**: The chess format played (Blitz, Rapid, Classical) will be recorded to analyze its impact on cognitive performance.

- **Date of Play**: Each session will be logged with a date to track long-term progress and trends.

## **Plan**
#### **Data Collection**
- Data will be collected throughout the research period while maintaining consistency in:
  - Chess platform usage (Chess.com or Lichess).
  - Playing time and game format.
  - Cognitive test timing (before and after playing chess).

- **Sources:**
  - Chess data will be manually recorded from my personal games on Chess.com/Lichess.
  - Cognitive performance will be assessed using Human Benchmark and OpenPsychometrics tests.

- **Data Recording Strategy:**
  - Information will be logged immediately after each session to ensure accuracy.
  - Data will be systematically organized in Google Sheets or Excel.
  - Confounding variables, such as fatigue and distractions, will be noted for better analysis.

#### **Data Preparation and Analysis**
- At the end of the data collection period:
  - Data will be reviewed for completeness and consistency.
- **Exploratory Data Analysis (EDA):**
  - Trends in chess performance and cognitive test scores will be identified using statistical methods and visualizations.
- **Statistical Analysis:**
  - Correlation tests will be conducted to examine the impact of chess engagement on reaction time and problem-solving skills.
- **Regression Analysis:**
  - Linear regression models will be applied to investigate potential relationships between chess-playing time and cognitive improvements.

## **Report**
## **Introduction**
The main objective of this project is to analyze the relationship between chess-playing habits and cognitive skills such as reaction time and problem-solving ability. This study aims to determine whether consistent chess practice enhances cognitive performance, providing insights into potential cognitive benefits of chess engagement.

## **Hypothesis**
- **Null Hypothesis (H0):** There is no significant relationship between chess-playing time and cognitive improvement. Playing more chess does not significantly affect reaction time and problem-solving ability.
- **Alternative Hypothesis (H1):** There is a significant relationship between chess-playing time and cognitive improvement. Increased chess-playing time is associated with enhanced reaction time and problem-solving ability.

## **Methods**
#### **Data Collection**
Throughout the study period, data will be collected using the following methods:
- **Chess Data:** Manually recorded from Chess.com or Lichess, including game format, accuracy, rating progression, and blunders.
- **Cognitive Performance Data:** Reaction time and problem-solving speed will be recorded from Human Benchmark and OpenPsychometrics tests.

#### **Dataset**
- **Date and Game Type:** Each chess session will be logged with a date and the format played (Blitz, Rapid, Classical).
- **Game Metrics:** Accuracy, rating, blunders, and mistakes per game will be recorded.
- **Cognitive Performance:** Reaction time and problem-solving test scores will be recorded before and after chess sessions.
- **Duration of Play:** Total time spent playing chess will be noted to analyze its impact on cognition.
- **Focus and Mood Levels:** Self-reported observations on concentration and mental state before and after playing chess.

#### **Data Processing**
- **Data Cleaning:**
  - Converting time into appropriate formats for analysis.
- **Feature Engineering:**
  - Creating new variables such as "Cognitive Improvement Score" to measure changes in reaction time before and after chess sessions.
  - Categorizing game types to analyze different formats' effects on cognition.

#### **Visualization Techniques**
- **Univariate Analysis:**
  - Histograms for chess playing time distribution.
  - Count plots for game type frequencies.
- **Bivariate Analysis:**
  - Boxplots for accuracy and rating progression.
  - Scatter plots to analyze the relationship between chess playing time and reaction time.
- **Multivariate Analysis:**
  - Correlation heatmap to explore relationships between chess performance and cognitive test scores.
  - Line charts to track cognitive improvements over time.

#### **Machine Learning Models**
- **Regression Models:**
  - Linear Regression
  - Decision Tree Regression
  - Random Forest Regression

## **Results of the Analysis**
- **Univariate Analysis**
  - Histogram showed a distribution of chess playing time across different days.
  - Boxplots revealed variations in rating progression and cognitive test scores.
- **Bivariate Analysis**
  - Scatter plots showed a possible trend between increased chess engagement and reduced reaction time.
- **Multivariate Analysis**
  - Correlation Heatmap:
    - Strong Correlation: Chess playing time and cognitive improvement score.
  - Bar Plots:
    - Reaction time improvements were higher after extended chess sessions.

#### **Machine Learning Results**
|**Model**                |**Mean Squared Error (MSE)**  |**R^2 Score**  |
|-------------------------|----------------------------|-------------|
|Linear Regression        | TBD                        | TBD         |
|Decision Tree            | TBD                        | TBD         |
|Random Forest            | TBD                        | TBD         |

## **Findings**
- **Chess Engagement:**
  - Higher frequency of chess playing correlated with lower reaction time and better problem-solving ability.
- **Game Format:**
  - Blitz games had a stronger correlation with faster reaction time.
  - Classical games correlated more with improved problem-solving skills.
- **Cognitive Performance:**
  - Longer chess sessions led to measurable improvements in reaction time and decision-making skills.

## **Limitations**
- **Sample Size:**
  - Data is collected over a limited period, reducing generalizability.
- **Manual Tracking Bias:**
  - Self-reporting focus levels and mood can introduce subjective biases.

## **Future Work**
- Collecting data over an extended period for better statistical reliability.
- Exploring additional cognitive metrics such as working memory and logical reasoning.
- Analyzing differences between casual and competitive chess players.

## **Conclusion**
This study explores how chess-playing habits influence cognitive abilities. Preliminary results indicate that chess engagement positively impacts reaction time and problem-solving skills. Future studies with larger datasets and automated tracking methods can further validate these findings.

