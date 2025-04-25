# Dolunay Özbilgin DSA 210 
# Chess Habits & Cognitive Impact

## **Project Idea**
In this project, I will analyze how chess-playing habits influence cognitive abilities such as reaction time, problem-solving, and decision-making speed. My goal is to understand the relationship between chess engagement and mental performance by collecting and analyzing chess gameplay data and cognitive test results.

I decided to work on this topic, because chess is playing a huge role in my daily life.And, there are so many discussions about whether chess is beneficial for mental and cognitive development of young people.So, I want to make this ongoing debates clear at least for myself, while I am doing my hobby everday.Now, I will mention the keypoints of my work.

## **Description of Dataset**
- **Total duration of each chess session**: I will manually record my chess playing time for each session.

- **Game Performance Metrics**: I will track my rating, accuracy, number of blunders, and mistakes from Chess.com or Lichess(These are the platforms that I use for playing chess.).

- **Cognitive Performance**: I will assess reaction time, memory, and focus levels using cognitive tests that are memory tests such as Digit Span Test, Attention and Focus Tests such as Stroop Test,lastly Processing Speed and Reaction Time tests such as Go/No-Go Test.These test are available free in several websites like Human Benchmark in internet, so it is easy to access and make them.(These tests would be changed if I can found better tests for this purposes.).

- **Game Type**: The chess format played (Blitz, Rapid, Classical) will be recorded to analyze its impact on cognitive performance.

- **Date of Play**: I generally play everyday chess, because I love to play it:) but, in this proccess, somedays I will not play chess, and then I make the cognitive tests for comparing the results. Each session will be recorded and the datas I obtained will be used in folowing phases.

## **Plan**
#### **Data Collection**
- Data will be collected throughout the research period while maintaining consistency in:
  - Chess platform usage (Chess.com or Lichess).
  - Playing time and game format.
  - Cognitive tests results.(Before and after playing chess and after the day I played chess and after the day that I don't play chess.


## Cognitive Tests and Measured Skills

### Reaction Time Test
- **Measures:**
  - Decision-making speed
  - Reflex response time
  - Attention and alertness
- **Description:**  
  Assesses how quickly and accurately a person can respond to a stimulus. It reflects cognitive speed and focused attention.

### Stroop Test
- **Measures:**
  - Attention control
  - Cognitive flexibility
  - Interference management
- **Description:**  
  Evaluates the ability to maintain focus and respond correctly when presented with conflicting information. It tests mental control and switching abilities.

### Digit Span Test
- **Measures:**
  - Working memory
  - Short-term memory capacity
  - Information processing and management
- **Description:**  
  Measures the ability to temporarily hold and manipulate sequences of numbers. It reflects the brain’s memory load handling ability.

### Verbal Memory Test
- **Measures:**
  - Verbal memory
  - Learning and information retention
  - Recall ability
- **Description:**  
  Assesses how well a person can learn, store, and later recall verbal information such as words or phrases.




##  Sources

###  Digit Span Test
- **Purpose**: Measures short-term and working memory.
- **Scientific Reference**:  
  [Digit Span - ScienceDirect Topics](https://www.sciencedirect.com/topics/psychology/digit-span)
- **Online Tool**:  
  [Cambridge Cognition - Digit Span (DGS)](https://cambridgecognition.com/digit-span-dgs/)

---

###  Stroop Test
- **Purpose**: Measures attention, cognitive flexibility, and processing speed.
- **Scientific Reference**:  
  [The Stroop Color and Word Test - PMC](https://pmc.ncbi.nlm.nih.gov/articles/PMC5388755/)
- **Online Tool**:  
  [PsyToolkit - Stroop Task](https://www.psytoolkit.org/experiment-library/stroop.html)

---

###  Verbal Memory Test
- **Purpose**: Evaluates the ability to encode, retain, and recall verbal information.
- **Scientific Reference**:  
  [Verbal Memory Test - ScienceDirect Topics](https://www.sciencedirect.com/topics/nursing-and-health-professions/verbal-memory-test)
- **Online Tool**:  
  [Pearson Clinical - Verbal Memory](https://pearsonclinical.in/solution_category/clinical-psychology/memory/visual-verbal/)



###  Chess Data Consistency

- **Purpose**: Ensures that the measurement of chess performance (e.g., accuracy, rating, play time) remains standardized throughout the research period.

- **Methodological Standard**: 
Data was collected under controlled conditions using either **Chess.com** or **Lichess.org**, two widely recognized chess platforms. These platforms provide consistent, reliable, and detailed game statistics including:
- Game duration
- Accuracy and evaluation metrics
- Number of blunders and mistakes
- Game format (e.g., Blitz, Rapid)

- **Platform References**:
- [Chess.com – Stats, Accuracy, and Game Reports](https://www.chess.com/stats)
- [Lichess.org – Advanced Chess Insights and Export Tools](https://lichess.org/@/username/perf)



## **Methodology: Data Collection & Analysis**

### Consistency & Bias Minimization

To ensure data quality and minimize bias in the analysis of the relationship between chess playing and cognitive performance:

-  All data (chess sessions and cognitive tests) is recorded **immediately after each session** to maintain accuracy and reduce memory bias.
-  Information is **systematically organized** by date and test type (Reaction time Test, Verbal Memory, Digit Span, Stroop).

---

###  Data Preparation & Analysis

At the end of the data collection period, the following steps will be taken:

####  Data Review
- All entries will be checked for **completeness**, **consistency**, and **logical coherence** (e.g., reaction times not being too low or high).
- Duplicate, missing, or corrupted entries will be corrected or removed.

####  Exploratory Data Analysis (EDA)
- Trends will be explored using:
  - Descriptive statistics (mean, median, std deviation)
  - Time series and session-based visualizations
  - Correlation heatmaps to assess relationships between chess activity and test results

####  Regression Analysis
- Statistical modeling will be used to explore:
  - The impact of chess session variables (e.g., play time, mistakes, rating) on cognitive test outcomes
  - Differences in **before vs. after** performance for each cognitive test
  - Longitudinal patterns in cognitive performance over time



## **Introduction**
The main objective of this project is to analyze the relationship between chess-playing habits and cognitive skills such as reaction time,focus and memory. This study aims to determine whether consistent chess practice enhances cognitive performance, providing insights into potential cognitive benefits of chess engagement.

## **Hypothesis**
- **Null Hypothesis (H0):** There is no significant relationship between chess-playing time and cognitive improvement. Playing more chess does not significantly affect our cognitive capacity.
- **Alternative Hypothesis (H1):** There is a significant relationship between chess-playing time and cognitive improvement. Increased chess-playing time is associated with better test results.

## **Methods**
#### **Data Collection**
Throughout the study period, data will be collected using the following methods:
- **Chess Data:** Manually recorded from Chess.com or Lichess, including game format, accuracy, rating progression, and blunders.
- **Cognitive Performance Data:** Memory tests scores ,Digit Span Test scores and Processing Speed and Reaction Time tests scores will be recorded from Human Benchmark etc.

#### **Dataset**
- **Date and Game Type:** Each chess session will be logged with a date and the format played (Blitz, Rapid, Classical).
- **Game Metrics:** Accuracy, rating, blunders, and mistakes per game will be recorded.
- **Cognitive Performance:** Memory tests scores ,Digit Span Test scores and Processing Speed and Reaction Time tests scores will be recorded before and after chess sessions and at the end of the days that I play chess and I don't play chess.
- **Duration of Play:** Total time spent playing chess will be noted to analyze its impact on cognition.

## **Data Processing**
- **Data Cleaning:**
Converted date and time into appropriate formats.
There is no outliers, because the test results are not extreme with eachother.I don't need to apply any method for deleting outliers.

##  **Visualization Techniques**


### Univariate Analysis
- **Histograms for Cognitive Test Scores (Before & After)**  
  Used to assess the distribution and central tendency of individual tests like Stroop, Digit Span, Reaction Time, and Verbal Memory.
- **Bar Plot for Chess Activity Frequency**  
  To visualize the number of days chess was played versus not played.

### Bivariate Analysis
- **Boxplots (Before vs After)**  
  Applied to each cognitive test (Stroop, Reaction, Digit Span, Verbal Memory) to compare performance change within individuals.
- **Scatter Plots (After Score vs Improvement)**  
  To assess whether higher post-test scores correspond to greater or lesser improvements and if this pattern differs by chess activity.

### Multivariate Analysis
- **Grouped Scatter Plots with Hue = Chess Played?**  
  To show differences in cognitive improvements based on whether chess was played on that day (Yes/No).
- **Correlation Heatmap**  
  To examine relationships between chess activity and different test improvement metrics.
- **Line Plot for Daily Reaction Time or Stroop Trends**  
  Used to track changes in cognitive measures over time.


---

##  **Machine Learning Models** *(optional extension not used in this proejct)*
> For predicting cognitive performance based on gameplay features:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

  
# Hypothesis Testing Summary for Chess and Cognitive Performance Project

## Objective
This project investigates whether playing chess has a significant impact on cognitive performance improvements across multiple domains:

- Reaction Time
- Stroop Test
- Digit Span Test
- Verbal Memory Test

## Hypotheses

### Paired t-test (Before vs After Scores)

- **Null Hypothesis (H₀):** There is no significant difference between Before and After scores in cognitive tests.
- **Alternative Hypothesis (H₁):** There is a significant improvement in After scores compared to Before scores.

### Linear Regression (Chess Played vs Improvement)

- **Null Hypothesis (H₀):** Chess playing has no significant effect on cognitive improvement.
- **Alternative Hypothesis (H₁):** Chess playing has a significant positive effect on cognitive improvement.

## Methods Used

### 1. Paired t-test
- Tests whether the mean difference between paired observations (Before and After scores) is statistically significant.
- Applied separately to each cognitive test (Reaction Time, Stroop, Digit Span, Verbal Memory).
- Significance level: **0.05**

### 2. Linear Regression
- Models cognitive improvement as a function of whether chess was played or not.
- Dependent variable: Improvement (After - Before)
- Independent variable: Chess Played (Yes = 1, No = 0)
- Significance level: **0.05**

## Decision Rule

For each test:
- If **p-value < 0.05**, we reject H₀ and conclude that there is statistically significant evidence.
- If **p-value ≥ 0.05**, we fail to reject H₀ and conclude that there is no statistically significant evidence.

## Summary

| Test                         | Method              | p-value  | H₀ Rejected? | Conclusion                                              |
|:------------------------------|:--------------------|:--------|:---------------|:--------------------------------------------------------|
| Reaction Time Improvement    | Paired t-test        | 0.00014  | Yes           | Chess significantly improves reaction time.             |
| Digit Span Improvement       | Paired t-test        | 0.0132   | Yes           | Chess significantly improves digit span memory.         |
| Stroop Test Improvement      | Paired t-test        | 0.000017 | Yes           | Chess significantly improves Stroop test scores.        |
| Verbal Memory Improvement    | Paired t-test        | 0.0102   | Yes           | Chess significantly improves verbal memory.             |
| Reaction Time Regression     | Linear Regression    | 0.1308   | No            | Chess does not significantly predict reaction improvement. |
| Digit Span Regression        | Linear Regression    | 0.0151   | Yes           | Chess significantly predicts digit span improvement.    |
| Stroop Test Regression       | Linear Regression    | 0.2927   | No            | Chess does not significantly predict Stroop improvement. |
| Verbal Memory Regression     | Linear Regression    | NaN      | No            | Regression could not be performed (missing variation).  |

> Note: Verbal Memory regression could not be fully performed due to insufficient variation in the Chess Played variable.

## Final Conclusion

The results show that chess playing clearly helps improve cognitive performance in Reaction Time, Digit Span, Stroop, and Verbal Memory, based on paired t-tests. Linear regression also shows that chess playing has a significant positive effect on Digit Span scores. However, for the other tests, chess playing was not found to be a strong, independent factor for 30 days period.

In short, chess seems to boost different cognitive skills on the same day it is played. But when we look over a longer period of 30 days, the only clear long-term improvement is seen in working memory (Digit Span Test). This suggests that chess may provide short-term mental benefits across many skills, but its longer-term effects can not be understand by this limited dataset.

Also, test scores on days without chess were generally lower than the "after" scores on chess-playing days. This supports the idea that chess playing helps with short-term cognitive improvement.

It is important to note that if we had a longer dataset (for example, over six months or a year), we might have different results than we had. Past scientific studies already show that chess has positive long-term effects on thinking skills. However, with the current short-term data, we can only prove the instant impact on cognitive skills.
