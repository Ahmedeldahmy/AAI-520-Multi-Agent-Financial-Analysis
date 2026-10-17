# AAI-520 Multi-Agent Financial Analysis System

**Group 2 | USD AAI-520 Final Team Project**

## Overview

A multi-agent financial research system built with LangGraph. Given a stock ticker, the system collects market and news data, analyzes the information with specialist agents, evaluates its own work, and produces a structured financial research report.

The project implements the three required workflows:

- Prompt Chaining
- Routing
- Evaluator-Optimizer

It also includes research planning, dynamic tool selection, self-reflection, and memory across runs.

## Team

| Member | Role |
| --- | --- |
| Ahmed Eldahmy | Data, APIs, Prompt Chaining |
| Brian Covington | Planning, Routing, Specialist Agents |
| Sai Gautham Bandi | Evaluator-Optimizer, Memory, Final Integration |

## System Flow

1. Retrieve stock and news data from Yahoo Finance
2. Preprocess and classify financial news
3. Extract key events, entities, sentiment, and financial figures
4. Create a research plan
5. Select and run financial tools
6. Analyze data using News, Earnings, and Market specialists
7. Build and self-review the research report
8. Evaluate and improve the report
9. Save lessons for future runs

## Project Structure

| Folder | Purpose |
| --- | --- |
| `notebooks/` | Development notebooks and final combined notebook |
| `data/` | Generated data and structured outputs |
| `outputs/` | Project outputs |
| `reports/` | Final submitted project report |
| `tools/` | Shared project tools |

## Tech Stack

- Python
- LangGraph
- LangChain
- OpenAI API
- Yahoo Finance / yfinance
- Pandas
- Pydantic
- Jupyter Notebook / Google Colab

## Final Notebook

`notebooks/AAI520_Final_Project_Ahmed_Brian_Sai_v2.ipynb`

## Security

API keys are not stored in this repository. The OpenAI API key is loaded from Colab Secrets or environment variables.

## Status

Final project completed and submitted.
