# Understanding-the-Use-of-Artificial-Intelligence-by-Students
''Analysing how students use Artificial Intelligence in their academic work. The project explores AI adoption patterns across education levels, session durations, satisfaction ratings, and task types—providing data-driven insights into the role of AI in modern learning environments."

****OVERVIEW****

This project analyses how students across various academic levels and disciplines engage with Artificial Intelligence (AI) tools to complete academic tasks. Using a detailed dataset and Power BI dashboard, I uncover insights into task types, usage patterns, satisfaction ratings, and factors that influence repeated use of AI. The aim is to evaluate the impact and effectiveness of AI-assisted learning from a user behaviour perspective.

The dataset used in this project was sourced from Kaggle.
[download here](https://www.kaggle.com/datasets/ayeshasal89/ai-assistant-usage-in-student-life-synthetic)

****Project Objective****

The main objective is to answer:

"How do students engage with AI tools for academic support, and what factors influence their satisfaction and continued use?"
From this central question, I further explore:

•	Which types of tasks are most supported by AI?

•	What disciplines and student levels rely on AI the most?

•	How effective is AI assistance in helping students complete their academic tasks?

•	What is the relationship between session behaviour (duration, prompts) and satisfaction?

📊 **Dataset Summary**

The dataset consists of two sheets: the first sheet which is the original dataset contains 10 columns and 10,000 of rows. 

The second sheet contains basic statistical analysis using the pivot table.

Sheet 1: Session-Level Data
Each row represents an individual AI usage session and contains:

•	Student Level (e.g.,High school, Undergraduate, Graduate).

•	Discipline (e.g., Biology, Business, Engineering, history, Maths, Computer science, Psychology).

•	Task Type (e.g., Writing, Studying, Coding, Homework help, Research, Brainstorming).

•	Session Details (Date, Length, Total Prompts).

•	AI Assistance Level (scale of 1–5).

•	Final Outcome (e.g., Assignment Completed, Gave Up, Idea drafted, Confused).

•	Satisfaction Rating (1–5).

•	Used Again (True/False — did the student return?).

Sheet 2: Summary Pivot Table

Aggregated data showing how many students used AI again versus not.

	Basic Descriptive Analysis	
Total Session Length in Minutes 		198464.67

Average  Session Length in Minutes		19.846467

Maximum  Session Length in Minutes		110.81

Minimum  Session Length in Minutes		0.03

Range of  Session Length in Minutes		110.78

AI ADOPTION IN ACADEMIC WORKFLOW DASHBOARD
<img width="1214" height="683" alt="Screenshot 2025-08-08 112626" src="https://github.com/user-attachments/assets/8c94cf6b-3c10-4053-a0e0-4e01420923d6" />



📈 **Power BI Dashboard Highlights**

The interactive dashboard visualizes and summarizes key metrics:

✅ Key KPIs:

•	Average Satisfaction Rating: 3.42

•	Average Time Spent per Session: 19.85 minutes

•	Total Prompts Across All Sessions: 56,000

•	Repeat Usage: 70.64% of students returned to use AI again

📊 Visual Insights:

•	Most Common Task: Writing is by far the most supported task type by AI.

•	Student Level Usage: Undergraduates are the primary users across most task types.

•	AI Assistance Effectiveness: Higher assistance levels correlate with completed assignments, while lower levels link with confusion or abandonment.

•	Session Trends: A spike in session durations is observed between April and July 2024, with a slight decline after.

•	Discipline-wise Satisfaction:

o	Students in History and Biology reported the most satisfaction at the 5-star level.

o	Business students showed a more balanced distribution across satisfaction levels.

•	Repeat Use Behaviour:

o	70.64% of users reused the AI tools after their first session, indicating high perceived value.

                                                        **SUMMARY, FINDINGS AND RECOMMENDATIONS**


📌 **Key Findings**

1.	Writing is the Dominant Task Type: 
Students overwhelmingly use AI for writing, suggesting it is the most easily supported academic activity via AI tools.

2.	High Repeat Usage Indicates Trust:
The fact that over 70% of students returned to use AI again points to satisfaction and value in the AI experience.

3.	AI Support Drives Task Completion:
Most of the "Assignment Completed" outcomes had higher AI assistance levels, reinforcing that more comprehensive AI support improves academic outcomes.

4.	Satisfaction Varies by Discipline:
Disciplines like History and Psychology tend to report higher satisfaction levels, possibly due to the nature of their tasks being well-suited to AI assistance.

5.	Session Behaviour Influences Satisfaction:
Students who spent longer time or issued more prompts generally had better outcomes and higher ratings.


💡 **Future Recommendations**

•	Tailor AI Tools to Disciplines: Further refine AI tools to better support specific fields like engineering or science, where satisfaction is more varied.

•	AI Assistance Personalization: Introduce adaptive assistance levels based on user history and task complexity.

•	Track Learning Outcomes: Integrate academic performance data to assess the actual learning benefit of AI usage beyond task completion.


🛠 **TOOLS USED**

•	Microsoft Excel – Data cleaning and pivot table generation

•	Power BI – Data visualization and dashboard creation

•	Python (Pandas) – (Optional) Data inspection and preparation

🧠 **CONCLUSION**
This project highlights how students use AI in their academic workflow and the impact it has on task success and satisfaction. With growing reliance on digital tools in education, understanding these patterns can help educators, developers, and institutions better integrate AI into learning environments.

	 




