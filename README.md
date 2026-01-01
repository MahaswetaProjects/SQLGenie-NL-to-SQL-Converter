# SQLGenie-Natural Language-to-SQL-Converter


## Overview
SQLGenie is a lightweight NLP-powered tool that translates natural language queries into executable SQL statements. Designed for data analysts and non-technical users, it simplifies database interaction and accelerates business intelligence workflows.

## Features
- Converts plain English queries into accurate SQL syntax  
- Built with a Gradio UI for real-time interaction  
- Supports SELECT, WHERE, GROUP BY, and basic JOIN operations  
- Ideal for educational use, BI automation, and internal dashboards

## Tech Stack
- **Languages & Libraries:** Python, Pandas, Scikit-learn, Regex  
- **NLP:** Custom rule-based parsing with keyword mapping  
- **Interface:** Gradio for interactive query input and SQL output  
- **Deployment:** Local runtime or hosted via Hugging Face Spaces

## How It Works
1. User enters a natural language query (e.g., "Show total sales by region for 2023")  
2. SQLGenie parses the input and maps it to SQL syntax  
3. The generated SQL query is displayed instantly for review or execution

## Sample Input & Output
**Input:** "List customer names who ordered more than 5 items"  
**Output:** `SELECT CustomerName FROM Orders WHERE Quantity > 5;`

## Results
- Reduced manual query writing time by **~40%** in test cases  
- Improved accessibility for non-SQL users in data exploration tasks

## Future Enhancements
- Add support for complex JOINs and subqueries  
- Integrate with live databases for direct query execution  
- Expand NLP capabilities using transformer-based models


## Acknowledgements
Built as part of a data accessibility initiative to bridge the gap between natural language and structured query logic.
