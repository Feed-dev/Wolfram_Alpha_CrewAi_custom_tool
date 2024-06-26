# Wolfram Alpha CrewAi custom tool

## Description

This project provides a custom tool for CrewAi that allows agents to query the Wolfram Alpha API. 
It is designed to enable agents to fetch and analyze data from the Wolfram Alpha api.
It includes an example of a basic Crew that includes a Researcher Agent and a Writer Agent.
The Researcher Agent queries Wolfram Alpha for information and the Writer Agent generates a report based on the data.

## Features

- Query Wolfram Alpha for information.
- Automated data analysis by a Researcher Agent. (example crew)
- Report generation by a Writer Agent. (example crew)

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
Get a Wolfram Alpha App ID by signing up at https://developer.wolframalpha.com/access

## Usage

To see the example, run:

```bash
python main_crew.py
```

Or do a quick tool test:

```bash
python quick_tool_test.py
```

To use the tool in your own project, you can import the `WolframAlphaTool` class:

```python
from wolfram_alpha_CrewAi_tool import WolframAlphaTool

# Initialize the tool
wolfram_tool = WolframAlphaTool()
```
