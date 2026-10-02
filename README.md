# AI Agent with Calculator and Weather Tools

A simple AI agent built using Python and the Groq API. The agent can understand
user questions, decide whether a tool is required, use the appropriate tool,
observe the result, and provide a final response.

## Project Overview

This project demonstrates the basic working of an AI agent using an LLM and
external tools.

The agent can:

- Answer general questions using the LLM.
- Perform mathematical calculations using a Calculator Tool.
- Provide demo weather information using a Weather Tool.
- Select the appropriate tool based on the user's request.
- Process tool results and generate a final response.

## Agent Workflow

The agent follows the basic loop:

**THINK → ACT → OBSERVE → REPEAT**

1. **THINK** – Understand the user's request and decide what to do.
2. **ACT** – Select and use the appropriate tool.
3. **OBSERVE** – Receive the result from the tool.
4. **REPEAT** – Continue until the task is completed.

## Tools Used

- Python
- Google Colab
- Groq API
- OpenAI GPT-OSS-20B model
- Function/Tool Calling
- Calculator Tool
- Weather Tool

## Features

### Calculator Tool

The calculator tool performs mathematical calculations requested by the user.

Example:

```text
User: Calculate 125 * 8 + 50

ACT → Calculator
OBSERVE → 1050

Final Answer: 125 × 8 + 50 = 1050
