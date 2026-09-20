# AAI-520 Multi-Agent Financial Analysis System
**Group 2 | USD AAI-520 Final Team Project**

## Overview
An AI agent that researches stocks using LangGraph. Give it a ticker symbol 
and it pulls financial data, analyzes news, checks its own work, and produces 
an investment summary. Implements three required workflows: Prompt Chaining, 
Routing, and Evaluator-Optimizer.

## Team
| Member | Role |
|--------|------|
| Ahmed | Data, APIs & Prompt Chaining |
| Brian | Agent Planning, Routing & Specialist Agents |
| Sai | Evaluator-Optimizer, Memory & Final Assembly |

## Structure
| Folder | Purpose |
|--------|---------|
| notebooks/ | Working notebooks per member + final combined notebook |
| tools/ | Shared financial data and API functions |
| data/ | Sample data and test files |
| outputs/ | Final notebook exports |

## Tech Stack
- Python 3.10+, LangGraph, Jupyter Notebook
- yfinance, NewsAPI
- Optional: FRED, SEC EDGAR, Alpha Vantage

## Security
API keys are not stored in this repo. Use environment variables for all credentials.

## Submission
One combined notebook exported as PDF or HTML with this GitHub link included. 
Due end of Module 7.
