# Claude Code with Free NVIDIA API Proxy

A simple configuration guide to route Anthropic's Claude Code CLI requests through NVIDIA's hosted AI models using a free NVIDIA API key and LiteLLM proxy.

## Features
- **Free Tier Models**: Access powerful open weights models hosted on NVIDIA Build.
- **OpenAI Standard Compatibility**: Convert Claude Code API requests seamlessly via LiteLLM.
- **Easy Setup**: Minimal environment variable adjustments required.

---

## Quick Start

### 1. Prerequisites
- [Node.js](https://nodejs.org/) installed
- [Python 3.10+](https://python.org) installed
- An active [NVIDIA Build Account](https://build.nvidia.com) & API Key

### 2. Install LiteLLM Proxy
```bash
pip install litellm
