Sudiksha Ale, Sudha Sura - Team Members


# Finance AI Agent

AI-Powered Finance Analysis Agent
Overview

The AI-Powered Finance Analysis Agent enables users to query financial data interactively using natural language. It processes transaction and budget data, offering insights into spending patterns, budget adherence, and more. The agent uses Azure OpenAI GPT-4 to interpret queries and generate responses.

Features
Natural Language Query Support:
Users can ask financial questions, such as “What is my total spending?” or “Am I exceeding my food budget?”
Integrated Financial Data Analysis:
Summarizes transaction and budget data for insightful responses.
Azure OpenAI Integration:
Leverages GPT-4 hosted on Azure for advanced query processing.
Interactive Console Application:
A command-line interface to engage with the system in real time.
Technology Stack
Backend: Python (Pandas, Azure OpenAI API)
How to Run
1. Clone the Repository

git clone https://github.com/Sudha3222/finance-analysis-agent.git  
cd finance-analysis-agent  
2. Install Python Dependencies

Make sure Python 3.7+ is installed, and then install the required libraries:

pip install openai pandas  
3. Configure Azure OpenAI API Credentials

Set up the azure_api_key and azure_endpoint variables in the code with your Azure OpenAI credentials.

4. Run the Finance Agent

Launch the interactive application with:

python finance_agent.py  
Workflow
Data Input:
Uses sample transaction and budget data in Pandas DataFrames.
Users can replace sample data with their own records.
LLM Query Handling:
Summarizes financial data context for GPT-4.
Sends user queries and data to the Azure OpenAI API.
Interactive Insights:
Users receive real-time answers and insights based on their queries.

Example Queries
Query:
"How much have I spent on Food?"
Response:
"You have spent $80 on Food so far, with $20 remaining in your budget."
Query:
"What is my total spending?"
Response:
"Your total spending across all categories is $250."
Query:
"Am I exceeding any budgets?"
Response:
"No, you are within your budget for all categories."

Key Features
Dynamic Query Resolution:
Handles real-time financial questions with high accuracy.
Customizable Data:
Users can input their own transaction and budget records.
Interactive Experience:
Command-line interface for seamless user interaction.

Future Enhancements
Add a graphical user interface (GUI) for better usability.
Implement memory for saving and retrieving user data.
Automate transaction import from bank APIs.
Add predictive analytics for expense forecasting.
Acknowledgments
Azure OpenAI API: Azure OpenAI Documentation
Pandas Library: Pandas Documentation
