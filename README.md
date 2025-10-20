# AbstractAI

**Intelligent AI Model Selection and Management**

AbstractAI is an intelligent AI framework that automatically selects the optimal model for each task, built on top of [AbstractCore](https://github.com/lpalbou/abstractcore).

## Overview

AbstractAI extends AbstractCore's unified LLM interface with intelligent model selection capabilities. It automatically determines which model to use based on:

- **Task complexity** - Simple queries vs. complex reasoning
- **Input type** - Text, images, documents, or multimodal content  
- **Performance requirements** - Speed vs. accuracy trade-offs
- **Cost optimization** - Balancing quality with budget constraints
- **Context awareness** - Understanding the broader application needs

## Key Features

- **Automatic Model Selection** - AI-driven decision making for optimal model choice
- **All AbstractCore Capabilities** - Inherits unified interface, multimodal support, tool calling, embeddings, and more
- **Intelligent Routing** - Routes tasks to the most appropriate model automatically
- **Performance Optimization** - Balances speed, quality, and cost automatically
- **Context-Aware Decisions** - Learns from usage patterns to improve selections

## Installation

```bash
pip install abstractai
```

## Quick Start

```python
from abstractai import create_smart_llm

# AI automatically selects the best model for your task
llm = create_smart_llm()

# Simple text generation - might use a fast, cost-effective model
response = llm.generate("What is the capital of France?")

# Complex reasoning - automatically switches to a more capable model  
response = llm.generate("Analyze the economic implications of climate change policies")

# Image analysis - automatically selects a vision-capable model
response = llm.generate("Describe this image", media=["photo.jpg"])
```

## Status

🚧 **Currently in Development** 🚧

This is a placeholder package for PyPI publication. AbstractAI is under active development and will be released soon.

## Based on AbstractCore

AbstractAI builds upon the robust foundation of [AbstractCore](https://github.com/lpalbou/abstractcore), inheriting:

- Unified interface for all LLM providers
- Multimodal support (text, images, documents)
- Tool calling capabilities
- Embeddings and RAG functionality
- Production-ready error handling
- Local and cloud model support

## Roadmap

- [ ] Intelligent model selection algorithms
- [ ] Performance benchmarking and optimization
- [ ] Cost-aware routing
- [ ] Context learning and adaptation
- [ ] Advanced caching strategies
- [ ] Real-time model performance monitoring

## Contributing

Contributions are welcome! This project is in early development.

## Contact

**Maintainer:** Laurent-Philippe Albou  
📧 Email: contact@abstractcore.ai

---

**AbstractAI** - Intelligent AI model selection, built on AbstractCore's solid foundation.
