# Wolfram Alpha CrewAi custom tool

## Description

This project has a custom tool for CrewAi that allows agents to query the Wolfram Alpha API. 
It is designed to enable agents to fetch and analyze data from Wolfram Alpha.
I have integrated it in a basic CrewAi project that includes a Researcher Agent and a Writer Agent.
The Researcher Agent queries Wolfram Alpha for information and the Writer Agent generates a report based on the data.

## Features

- Query Wolfram Alpha for information.
- Automated data analysis by a Researcher Agent.
- Report generation by a Writer Agent.

## Installation

To install the required dependencies, run:

```bash
pip install -r requirements.txt
```

## Configuration

To configure the tool, you need to set the following environment variables:

```env
OPENAI_API_KEY=your_openai_api_key
OPENAI_MODEL_NAME=your_openai_model_name
APP_ID=your_wolfram_alpha_app_id
```

## Usage

To use the tool, run:

```bash
python main_crew.py
```
