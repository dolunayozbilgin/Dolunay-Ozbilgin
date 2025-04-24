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


##  Sources

###  Go/No-Go Test
- **Purpose**: Assesses response inhibition and impulse control.
- **Scientific Reference**:  
  [A Formal Cognitive Model of the Go/No-Go Discrimination Task](https://pmc.ncbi.nlm.nih.gov/articles/PMC2752340/)
- **Online Tool**:  
  [PsyToolkit - Go/No-Go Task](https://www.psytoolkit.org/experiment-library/go-no-go.html)

---

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



- **Data Recording Strategy:**
  - Information will be logged immediately after each session to ensure accuracy.
  - Data will be systematically organized in Google Sheets or Excel.
  - Confounding variables, such as fatigue and distractions, will be noted for better analysis.

#### **Data Preparation and Analysis**
- At the end of the data collection period:
  - Data will be reviewed for completeness and consistency.
  - I try to understand that Is there a certain correlation between my chess habits and my cognitive results, and is there a certain difference between my initial and final test in these 30 days that I measured myself because I played chess regularly.
- **Exploratory Data Analysis (EDA):**
  - Trends in chess performance and cognitive test scores will be identified using statistical methods and visualizations.
- **Statistical Analysis:**
  - Correlation tests will be conducted to examine the impact of chess engagement on reaction time and problem-solving skills.Main focus is I try to compare the test results that I get after chess session and no-chess session.Additionally, trends in chess performance and cognitive test scores will be analyzed using simple statistics and visual tools.
- **Regression Analysis:**
  - Linear regression models will be applied to investigate potential relationships between chess-playing time and cognitive improvements.


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



##  **Visualization Techniques**

### **Univariate Analysis**
- **Histogram for Play Time (min)**  
  To explore the distribution of chess session durations.
- **Histogram for Accuracy (%)**  
  To understand the spread and consistency of chess performance.
- **Histogram for Stroop Score (Before & After)**  
  To evaluate attention and interference control levels individually.
- **Count Plot for Game Type**  
  To visualize frequency of Blitz, Rapid, and Classical games.

---

### **Bivariate Analysis**
- **Boxplots for Cognitive Test Scores (Before vs After)**  
  Used to compare memory (Digit Span), attention (Stroop), and reaction time changes across sessions.
- **Scatter Plots**  
  - *Play Time vs Cognitive Improvements (Stroop/Reaction Time)*  
  - *Accuracy vs Digit Span Delta*  
  To examine potential correlations between chess performance and cognitive gain.

---

### **Multivariate Analysis**
- **Grouped Bar Plots**  
  Compare chess vs non-chess days across cognitive outcomes.
- **Correlation Heatmap**  
  To explore relationships between chess metrics (duration, accuracy, blunders) and cognitive metrics (test deltas).
- **Line Charts (Timeline)**  
  To track day-by-day progress of chess performance and mental sharpness.

---

##  **Machine Learning Models** *(optional extension)*
> For predicting cognitive performance based on gameplay features:
- **Linear Regression**
- **Decision Tree Regressor**
- **Random Forest Regressor**

  
