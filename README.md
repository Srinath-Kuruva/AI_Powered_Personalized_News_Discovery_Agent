# AI_Powered_Personalized_News_Discovery_Agent

## Copyright and Licensing
© [2026] [Srinath Kuruva]. All rights reserved.

This project is provided for demonstration purposes only and is not intended for commercial use, modification, or redistribution without explicit written consent from the author. All intellectual property rights remain with the author

## Prerequisites
* googlecolab
* Jupyter

## Overview
In the fast-moving digital landscape, staying informed without being overwhelmed is a challenge. NewsFindr is an autonomous AI agent designed to act as a personal research assistant. By mapping user interest profiles to live web data, the agent discovers, filters, and summarizes the most relevant news stories in real-time, providing a highly personalized news consumption experience.

## Objective
The goal of this project was to create a search-connected AI agent that:

Connects to the live web to find information beyond its training data.

Understands and acts upon unique user interest profiles.

Automates the process of query formulation, web scraping, and summarization.

Provides high-quality, synthesized news reports to save time and improve productivity.

## Technical Stack
LLM Engine: OpenAI gpt-4o-mini

Orchestration Framework: LangChain (Agents & Tools)

Search Infrastructure: Tavily API (Optimized for AI search)

Language: Python

Environment: Jupyter Notebook / Google Colab

## System Architecture & Workflow
1. Interest Mapping
The system maintains a database of user IDs and their corresponding interests (e.g., "Quantum Computing," "European Market Trends"). When a user initiates a request, the agent retrieves these interests as the foundation for the search.

2. Agentic Search & Query Expansion
Using Agentic Reasoning, the model does not just search for keywords; it "thinks" about the user's intent. It expands simple topics into detailed search queries to ensure it captures the most recent and impactful news from multiple perspectives.

3. Live Web Retrieval
The agent utilizes the Tavily tool to browse the web. It analyzes multiple sources simultaneously to find consistent and credible information, mimicking the workflow of a professional researcher.

4. Synthesis and Summarization
Finally, the agent distills the retrieved information into a clean, structured summary. This ensures the user gets the "big picture" without having to read through dozens of individual articles.

## Key Outcomes
Real-time Accuracy: Unlike standard LLMs, this agent provides information on current events happening today.

Hyper-Personalization: The discovery process is entirely driven by specific user personas.

Operational Efficiency: Automated the end-to-end research workflow from query to final report.

## Setup and Usage
Open MLS_AI_Powered_Personalized_News_Discovery_Agent.ipynb in Jupyter or Google Colab.

Install dependencies:

Bash

pip install langchain openai tavily-python pandas
Configure your OpenAI API Key and Tavily API Key.

Run the notebook to initialize the search agent and generate your personalized news feed.
