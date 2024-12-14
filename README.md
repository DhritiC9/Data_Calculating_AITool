# Data_Calculating_AITool
Data Analysis and AI-Driven Excel Processing Tool:

This repository contains a Python-based project that integrates LangChain, Pandas, and an LLM API (ChatGroq) to analyze Excel datasets and perform column-wise computations dynamically based on natural language user prompts.

Key Features:

	1.	Natural Language Processing: Accepts user prompts to specify tasks, e.g., “Calculate the age and the sum of columns A and B.”
	2.	Custom Tool Integration: Implements a calculate function for arithmetic operations like sum, multiplication, division, subtraction, and mean.
	3.	Age Computation: Dynamically calculates “age” from a DOB column.
	4.	AI and Automation: Uses ChatGroq for intelligently parsing and delegating tasks to tools.

Technologies Used:

	•	LangChain: For tool integration and seamless LLM interactions.
	•	Pandas: To handle Excel data manipulation.
	•	Python: For scripting and tool development.
	•	ChatGroq LLM API: To understand and execute user instructions.

Example Use Case:

Given an Excel sheet with columns A, B, and DOB, you can prompt:
“Calculate the age, and then find the sum, multiplication, and average of A, B, and age. Also, compute the division and subtraction of A and B.”
The system outputs the original data along with the new calculated columns.

Future Enhancements:

	•	Dynamic file upload support.
	•	Improved error handling for invalid column names.
	•	Extended operations (e.g., correlation, variance).
