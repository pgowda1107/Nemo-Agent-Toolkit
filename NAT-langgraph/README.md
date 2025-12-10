# Bringing Your Own LangGraph Agent to NeMo Agent Toolkit

## Overview

This notebook demonstrates how to integrate an existing **LangGraph agent** with **NVIDIA's NeMo Agent Toolkit (NAT)**.

## What You'll Learn

- How to wrap LangGraph agents to work seamlessly with NAT
- Take advantage of NAT features without refactoring your existing code:
  - **MCP compatibility**
  - **Observability** (with Phoenix tracing)
  - **Optimization**
  - **Profiling**

## Prerequisites

- **Python**: 3.11, 3.12, or 3.13
- **Platform**: Linux, macOS, or Windows
- **API Keys**:
  - NVIDIA Build API key (or local NIM deployment)
  - Tavily API key (for web search tools)


This notebook is configured to work with a NVIDIA API Endpoints:
- **Model**: `meta-llama/llama-3.3-70b-instruct`


## Notebook Structure

1. **Setup** - Install dependencies and configure API keys
2. **Define a LangGraph Agent** - Create an example agent with tools
3. **Migration Steps** - Transform your agent into a NAT-compatible workflow
4. **Integration** - Run with full NAT observability and profiling

