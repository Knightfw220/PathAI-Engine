# PathAI Engine

PathAI Engine is a behavioral analytics framework designed to analyze student engagement patterns in online learning environments. Using interaction data from digital learning platforms, the project generates dynamic behavioral scores that help identify engagement trends, evaluate learning consistency, and detect students who may require early academic intervention.

The project is built using the **OULAD (Open University Learning Analytics Dataset)** and focuses on transforming raw student activity logs into meaningful behavioral insights.

---

## Objective

Online learning platforms generate large volumes of interaction data, but deriving actionable insights from this data remains a challenge.

This project aims to:

- Analyze weekly student engagement patterns  
- Measure learning consistency over time  
- Evaluate participation across multiple learning resources  
- Track assessment performance  
- Generate a unified behavioral score for engagement analysis  

---

## Key Features

### Weekly Engagement Analysis
Tracks overall student interaction with the platform through:

- Total clicks per week  
- Number of active learning days  

---

### Activity Diversity Measurement
Evaluates how students interact with different types of learning resources such as:

- Forums  
- Course materials  
- Quizzes  
- Learning resources  

---

### Assessment Performance Tracking
Monitors student assessment scores to incorporate academic performance into engagement analysis.

---

### Consistency Analysis
Measures how regularly students interact with the platform across different days.

---

### Dynamic Behavioral Scoring
Combines multiple engagement metrics into a single behavioral score.

```python
Behavioral Score =
0.35 × Weekly Clicks +
0.25 × Active Days +
0.20 × Activity Diversity +
0.20 × Assessment Performance
```
### Dataset

This project uses the OULAD (Open University Learning Analytics Dataset). 
Dataset source: https://raw.githubusercontent.com/vjcalling/OULAD-data-analysis-EDA-/master/data/raw/
