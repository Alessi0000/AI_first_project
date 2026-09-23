# AI_first_project
AI-powered sales data analysis tool built with Python, pandas and the Gemini API. Processes sales data, generates statistics and business insights, and supports interactive follow-up questions.


# AI Data Analyst

A lightweight Python project that combines data analysis with generative AI.

The application uses **pandas** to process and summarize sales data, then sends the resulting statistics to the **Gemini API** to generate business insights, identify relevant patterns, and provide recommendations.

It also includes an interactive mode that allows the user to ask follow-up questions about the analyzed data.

---

## Features

- Generates a sample sales dataset
- Loads and processes CSV data using pandas
- Calculates revenue for each transaction
- Generates descriptive statistics
- Aggregates revenue by product
- Aggregates revenue by month
- Sends structured data summaries to Gemini
- Generates AI-powered business insights
- Supports interactive follow-up questions
- Maintains conversation context during the interactive session

---

## Tech Stack

- Python
- pandas
- Google GenAI SDK
- Gemini API

---

## How It Works

The application follows this workflow:

```text
Sales Data
    ↓
pandas Data Processing
    ↓
Statistics and Aggregations
    ↓
Prompt Construction
    ↓
Gemini API
    ↓
AI-Generated Business Insights
    ↓
Interactive Follow-up Questions

## Current Limitations

This project is intentionally simple and was built as a learning project.

Current limitations:

- Uses a generated sample dataset
- Command-line interface only
- Limited error handling and data validation
