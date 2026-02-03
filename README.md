# Autonomous Task Execution Agent

An execution-driven AI Agent that plans tasks, selects appropriate tools, and completes multi-step workflows automatically using reasoning and tool calling.

This project demonstrates real-world **Agentic AI behavior** using LangChain and OpenAI.

---

## Overview

This agent can:
- understand user tasks
- decide which tools to use
- execute steps autonomously
- combine multiple tools
- return final results without manual intervention

It simulates how production AI agents operate.

---

## Features

- Multi-step task planning
- Tool selection (Search, Calculator, File Reader)
- Autonomous reasoning
- LLM-based decision making
- Extendable tool architecture
- CLI-based interaction

---

## Tech Stack

- Python
- LangChain Agents
- OpenAI API
- Google/Serp Search API
- Custom tools framework

---

## Architecture

User Query → Agent → Tool Selection → Tool Execution → Result → Final Answer

The agent dynamically chooses tools based on the task.

---

## Tools Implemented

### Search Tool
Retrieves real-time information from the web.

### Calculator Tool
Handles mathematical computations.

### File Reader Tool
Reads local files for data processing.

You can easily add more tools (APIs, databases, workflows).

---

## Folder Structure
