# Awesome Python with stars

An opinionated guide to the best Python frameworks, libraries, and tools.

**Visit the [website](https://awesome-python.com/) to search and filter projects more easily.**

## **Sponsors**

* [iPulse AI](https://ipulseai.com) - Open Agentic Investment Research Platform. Inspect deep multi-agent market forecasts and stock picks.

> The **#10 most-starred repo on GitHub**. Put your product in front of Python developers. [Become a sponsor](SPONSORSHIP.md).

## Categories

**AI & ML**

* [AI and Agents](#ai-and-agents)
* [Deep Learning](#deep-learning)
* [Machine Learning](#machine-learning)
* [Natural Language Processing](#natural-language-processing)
* [Computer Vision](#computer-vision)
* [Recommender Systems](#recommender-systems)

**Web Development**

* [Web Frameworks](#web-frameworks)
* [Web APIs](#web-apis)
* [Web Servers](#web-servers)
* [WebSocket](#websocket)
* [Template Engines](#template-engines)
* [Web Asset Management](#web-asset-management)
* [Authentication](#authentication)
* [Admin Panels](#admin-panels)
* [CMS](#cms)
* [ERP](#erp)
* [Static Site Generators](#static-site-generators)

**HTTP & Scraping**

* [HTTP Clients](#http-clients)
* [Web Scraping](#web-scraping)
* [Email](#email)

**Database & Storage**

* [ORM](#orm)
* [Database Drivers](#database-drivers)
* [Database](#database)
* [Caching](#caching)
* [Search](#search)
* [Serialization](#serialization)

**Data & Science**

* [Data Analysis](#data-analysis)
* [Data Ingestion / ETL](#data-ingestion--etl)
* [Data Validation](#data-validation)
* [Data Visualization](#data-visualization)
* [Geolocation](#geolocation)
* [Science](#science)
* [Quantum Computing](#quantum-computing)

**Developer Tools**

* [Algorithms and Design Patterns](#algorithms-and-design-patterns)
* [Interactive Interpreter](#interactive-interpreter)
* [Code Analysis](#code-analysis)
* [Testing](#testing)
* [Debugging Tools](#debugging-tools)
* [Build Tools](#build-tools)
* [Documentation](#documentation)

**DevOps**

* [DevOps Tools](#devops-tools)
* [Distributed Computing](#distributed-computing)
* [Task Queues](#task-queues)
* [Messaging](#messaging)
* [Job Schedulers](#job-schedulers)
* [Logging](#logging)
* [Network Virtualization](#network-virtualization)

**CLI & GUI**

* [CLI Development](#cli-development)
* [CLI Tools](#cli-tools)
* [GUI Development](#gui-development)

**Text & Documents**

* [Text Processing](#text-processing)
* [HTML Manipulation](#html-manipulation)
* [File Format Processing](#file-format-processing)
* [File Manipulation](#file-manipulation)

**Media**

* [Image Processing](#image-processing)
* [Audio & Video Processing](#audio--video-processing)
* [Game Development](#game-development)

**Python Language**

* [Implementations](#implementations)
* [Built-in Classes Enhancement](#built-in-classes-enhancement)
* [Functional Programming](#functional-programming)
* [Asynchronous Programming](#asynchronous-programming)
* [Date and Time](#date-and-time)

**Python Toolchain**

* [Environment Management](#environment-management)
* [Package Management](#package-management)
* [Package Repositories](#package-repositories)
* [Distribution](#distribution)
* [Configuration Files](#configuration-files)

**Security**

* [Cryptography](#cryptography)
* [Penetration Testing](#penetration-testing)
* [Supply Chain Security](#supply-chain-security)
* [Web Security](#web-security)

**Other**

* [Hardware](#hardware)
* [Microsoft Windows](#microsoft-windows)
* [Miscellaneous](#miscellaneous)

## Projects

**AI & ML**

### AI and Agents

*Libraries for building AI applications, LLM integrations, and autonomous agents.*

* Agent Skills
  * [scientific-agent-skills](https://github.com/K-Dense-AI/scientific-agent-skills) ⭐ 50,422 | 🐛 39 | 🌐 Python | 📅 2026-10-15 - Agent skills for scientific research and analysis with Python libraries like scikit-learn, polars, and biopython.
  * [wshobson-agents](https://github.com/wshobson/agents) ⭐ 40,859 | 🐛 0 | 🌐 Python | 📅 2026-10-15 - Plugins, agents, and skills for AI coding tools, including Python skills for testing, async, packaging, and uv.
  * [trailofbits-skills](https://github.com/trailofbits/skills) ⭐ 7,573 | 🐛 46 | 🌐 Python | 📅 2026-10-15 - Security skills for vulnerability detection, auditing, and testing.
  * [sentry-skills](https://github.com/getsentry/skills) ⭐ 1,059 | 🐛 28 | 🌐 Python | 📅 2026-10-15 - Agent skills the Sentry team uses for code review, pull requests, and Django reviews.
  * [django-ai-plugins](https://github.com/vintasoftware/django-ai-plugins) ⭐ 157 | 🐛 0 | 🌐 Python | 📅 2026-07-23 - Django backend agent skills for Django, DRF, Celery, and Django-specific code review.
* Orchestration
  * [langchain](https://github.com/langchain-ai/langchain) ⭐ 147,886 | 🐛 650 | 🌐 Python | 📅 2026-10-15 - A framework for building agents and LLM-powered applications.
  * [crewai](https://github.com/crewAIInc/crewAI) ⭐ 59,743 | 🐛 721 | 🌐 Python | 📅 2026-10-15 - A framework for orchestrating role-playing autonomous AI agents for collaborative task solving.
  * [langgraph](https://github.com/langchain-ai/langgraph) ⭐ 43,323 | 🐛 810 | 🌐 Python | 📅 2026-10-15 - Low-level orchestration framework for building stateful, long-running LLM agents.
  * [pydantic-ai](https://github.com/pydantic/pydantic-ai) ⭐ 20,644 | 🐛 1,453 | 🌐 Python | 📅 2026-10-15 - A Python agent framework for building generative AI applications with structured schemas.
* Vendor Agent SDKs
  * [openai-agents](https://github.com/openai/openai-agents-python) ⭐ 30,058 | 🐛 7 | 🌐 Python | 📅 2026-10-15 - OpenAI's framework for building and managing AI agents.
  * [google-adk](https://github.com/google/adk-python) ⭐ 21,864 | 🐛 354 | 🌐 Python | 📅 2026-10-15 - Google's code-first toolkit for building, evaluating, and deploying AI agents.
  * [claude-agent-sdk](https://github.com/anthropics/claude-agent-sdk-python) ⭐ 8,288 | 🐛 553 | 🌐 Python | 📅 2026-10-15 - Anthropic's Python SDK for building AI agents on Claude Code's harness — custom tools, in-process MCP servers, hooks.
* Model Context Protocol
  * [fastmcp](https://github.com/PrefectHQ/fastmcp) ⭐ 28,089 | 🐛 516 | 🌐 Python | 📅 2026-10-15 - A high-level, Pythonic framework for building MCP servers and clients.
  * [mcp](https://github.com/modelcontextprotocol/python-sdk) ⭐ 24,590 | 🐛 359 | 🌐 Python | 📅 2026-10-13 - The official Python SDK for building Model Context Protocol servers and clients.
* Personal Assistants
  * [hermes-agent](https://github.com/NousResearch/hermes-agent) ⭐ 254,113 | 🐛 49,343 | 🌐 Python | 📅 2026-10-15 - An adaptive personal AI assistant that grows with you.
  * [AstrBot](https://github.com/AstrBotDevs/AstrBot) ⭐ 41,952 | 🐛 943 | 🌐 Python | 📅 2026-10-15 - A multi-platform AI assistant that connects LLMs to chat apps like Telegram, Slack, and QQ, extensible with Python plugins.
* Prompt Optimization
  * [dspy](https://github.com/stanfordnlp/dspy) ⭐ 38,653 | 🐛 802 | 🌐 Python | 📅 2026-10-15 - A framework for programming, not prompting, language models.
* Data Layer
  * [mem0](https://github.com/mem0ai/mem0) ⭐ 67,239 | 🐛 837 | 🌐 Python | 📅 2026-10-14 - An intelligent memory layer for AI agents enabling personalized interactions.
  * [llama-index](https://github.com/run-llama/llama_index) ⭐ 52,513 | 🐛 939 | 🌐 Python | 📅 2026-10-14 - A toolkit for building RAG pipelines and agents over your data.
  * [openviking](https://github.com/volcengine/OpenViking) ⭐ 40,013 | 🐛 928 | 🌐 Python | 📅 2026-10-15 - A context database for AI agents that unifies memory, resources, and skills.
  * [semantica](https://github.com/semantica-agi/semantica) ⭐ 14,058 | 🐛 113 | 🌐 Python | 📅 2026-10-15 - A graph-native context and knowledge layer for AI agents with reasoning, provenance, and governance.
  * [instructor](https://github.com/567-labs/instructor) ⭐ 14,020 | 🐛 195 | 🌐 Python | 📅 2026-10-14 - A library for extracting structured data from LLMs, powered by Pydantic.
* Pre-trained Models
  * [transformers](https://github.com/huggingface/transformers) ⭐ 167,731 | 🐛 2,318 | 🌐 Python | 📅 2026-10-15 - The model-definition framework for pretrained models in text, computer vision, audio, video, and multimodal tasks, for inference and training.
  * [sentence-transformers](https://github.com/huggingface/sentence-transformers) ⭐ 19,178 | 🐛 1,306 | 🌐 Python | 📅 2026-10-15 - Compute embeddings, run retrieval, and rerank results with pretrained and fine-tuned models.
* LLM Inference and Serving
  * [vllm](https://github.com/vllm-project/vllm) ⭐ 93,869 | 🐛 8,927 | 🌐 Python | 📅 2026-10-15 - A high-throughput and memory-efficient inference and serving engine for LLMs.
  * [sglang](https://github.com/sgl-project/sglang) ⭐ 37,179 | 🐛 5,850 | 🌐 Python | 📅 2026-10-15 - A high-performance serving framework for large language models and multimodal models.
  * [mlx-lm](https://github.com/ml-explore/mlx-lm) ⭐ 7,331 | 🐛 238 | 🌐 Python | 📅 2026-10-15 - Run and fine-tune large language models on Apple Silicon with MLX.
* LLM Gateways
  * [litellm](https://github.com/BerriAI/litellm) ⭐ 61,334 | 🐛 5,506 | 🌐 Python | 📅 2026-10-15 - Call 100+ LLMs using OpenAI format.
* Image and Video Generation
  * [diffusers](https://github.com/huggingface/diffusers) ⭐ 34,728 | 🐛 1,493 | 🌐 Python | 📅 2026-10-15 - A library that provides pre-trained diffusion models for generating and editing images, audio, and video.
* Fine-tuning
  * [unsloth](https://github.com/unslothai/unsloth) ⭐ 78,077 | 🐛 348 | 🌐 Python | 📅 2026-10-15 - Faster, lower-memory LLM fine-tuning, as a Python library or a desktop app.
  * [peft](https://github.com/huggingface/peft) ⭐ 21,791 | 🐛 129 | 🌐 Python | 📅 2026-10-15 - A library for parameter-efficient fine-tuning of large pretrained models.
  * [trl](https://github.com/huggingface/trl) ⭐ 19,521 | 🐛 269 | 🌐 Python | 📅 2026-10-15 - A library for post-training transformer language models with SFT, DPO, GRPO, and other trainers.
  * [axolotl](https://github.com/axolotl-ai-cloud/axolotl) ⭐ 12,574 | 🐛 257 | 🌐 Python | 📅 2026-10-15 - A framework for fine-tuning and post-training large language models.
* Speech
  * [openai-whisper](https://github.com/openai/whisper) ⭐ 110,587 | 🐛 172 | 🌐 Python | 📅 2026-08-31 - A general-purpose automatic speech recognition model trained on 680k hours of multilingual and multitask supervised data.
  * [faster-whisper](https://github.com/SYSTRAN/faster-whisper) ⭐ 25,879 | 🐛 24 | 🌐 Python | 📅 2026-10-15 - A Whisper reimplementation on CTranslate2, up to 4 times faster than openai-whisper with less memory.
  * [funasr](https://github.com/modelscope/FunASR) ⭐ 20,705 | 🐛 45 | 🌐 Python | 📅 2026-10-13 - Industrial-grade speech recognition toolkit with speaker diarization and emotion detection.
  * [gTTS](https://github.com/pndurette/gTTS) ⭐ 2,636 | 🐛 24 | 🌐 Python | 📅 2026-04-06 - Python library and CLI tool for converting text to speech using Google Translate TTS.

### Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 29,053 | 🐛 90 | 📅 2025-05-26.*

* Frameworks
  * [tensorflow](https://github.com/tensorflow/tensorflow) ⭐ 200,984 | 🐛 3,403 | 🌐 C++ | 📅 2026-10-15 - An end-to-end machine learning platform from Google.
  * [pytorch](https://github.com/pytorch/pytorch) ⭐ 104,706 | 🐛 17,664 | 🌐 Python | 📅 2026-10-15 - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
  * [keras](https://github.com/keras-team/keras) ⭐ 64,375 | 🐛 235 | 🌐 Python | 📅 2026-10-15 - A high-level deep learning library with support for JAX, TensorFlow, and PyTorch backends.
  * [jax](https://github.com/jax-ml/jax) ⭐ 36,446 | 🐛 2,554 | 🌐 Python | 📅 2026-10-15 - A library for high-performance numerical computing with automatic differentiation and JIT compilation.
  * [pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) ⭐ 31,410 | 🐛 1,123 | 🌐 Python | 📅 2026-10-12 - Deep learning framework to train, deploy, and ship AI products Lightning fast.
* Reinforcement Learning
  * [stable-baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐ 13,899 | 🐛 90 | 🌐 Python | 📅 2026-10-13 - PyTorch implementations of Stable Baselines (deep) reinforcement learning algorithms.
  * [gymnasium](https://github.com/Farama-Foundation/Gymnasium) ⭐ 12,683 | 🐛 108 | 🌐 Python | 📅 2026-10-14 - A standard API for reinforcement learning environments with popular reference environments ([gym](https://github.com/openai/gym) ⚠️ Archived successor).

### Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python) ⭐ 74,590 | 🐛 25 | 🌐 Python | 📅 2026-10-13.*

* General
  * [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐ 67,624 | 🐛 2,155 | 🌐 Python | 📅 2026-10-14 - The most popular Python library for Machine Learning with extensive documentation and community support.
  * [pgmpy](https://github.com/pgmpy/pgmpy) ⭐ 3,358 | 🐛 663 | 🌐 Python | 📅 2026-10-12 - A Python library for causal and probabilistic reasoning with graphical models.
  * [feature-engine](https://github.com/feature-engine/feature_engine) ⭐ 2,291 | 🐛 120 | 🌐 Python | 📅 2026-09-19 - sklearn compatible API with the widest toolset for feature engineering and selection.
* Gradient Boosting
  * [xgboost](https://github.com/dmlc/xgboost) ⭐ 28,879 | 🐛 452 | 🌐 C++ | 📅 2026-10-15 - A scalable, portable, and distributed gradient boosting library.
  * [lightgbm](https://github.com/lightgbm-org/LightGBM) ⭐ 18,884 | 🐛 538 | 🌐 C++ | 📅 2026-10-15 - A fast, distributed, high performance gradient boosting framework.
  * [catboost](https://github.com/catboost/catboost) ⭐ 9,141 | 🐛 739 | 🌐 C++ | 📅 2026-10-15 - A fast, scalable, high performance gradient boosting on decision trees library.
* Time Series Forecasting
  * [timesfm](https://github.com/google-research/timesfm) ⭐ 34,522 | 🐛 267 | 🌐 Python | 📅 2026-09-29 - A pretrained foundation model from Google Research for time-series forecasting, with non-commercial default weights.
  * [prophet](https://github.com/facebook/prophet) ⭐ 20,438 | 🐛 452 | 🌐 Python | 📅 2026-10-13 - A tool for producing forecasts for time series with multiple seasonality and trend changes.
  * [sktime](https://github.com/sktime/sktime) ⭐ 10,069 | 🐛 2,639 | 🌐 Python | 📅 2026-10-14 - A unified scikit-learn-style framework for forecasting and other time-series learning tasks.
  * [statsforecast](https://github.com/Nixtla/statsforecast) ⭐ 4,932 | 🐛 170 | 🌐 Python | 📅 2026-10-14 - Fast statistical forecasting models such as ARIMA, ETS, and Theta, compiled with numba.

### Natural Language Processing

*Libraries for working with human languages.*

* General
  * [spacy](https://github.com/explosion/spaCy) ⭐ 33,967 | 🐛 251 | 🌐 Python | 📅 2026-10-12 - A library for industrial-strength natural language processing in Python and Cython.
  * [gensim](https://github.com/piskvorky/gensim) ⭐ 16,506 | 🐛 440 | 🌐 Python | 📅 2025-11-01 - Topic Modeling for Humans.
  * [nltk](https://github.com/nltk/nltk) ⭐ 14,738 | 🐛 220 | 🌐 Python | 📅 2026-10-15 - A leading platform for building Python programs to work with human language data.
  * [stanza](https://github.com/stanfordnlp/stanza) ⭐ 7,903 | 🐛 94 | 🌐 Python | 📅 2026-10-15 - The Stanford NLP Group's official Python library, supporting 60+ languages.
* Chinese
  * [jieba](https://github.com/fxsjy/jieba) ⭐ 35,197 | 🐛 703 | 🌐 Python | 📅 2024-08-21 - The most popular Chinese text segmentation library.
  * [pypinyin](https://github.com/mozillazg/python-pinyin) ⭐ 5,375 | 🐛 49 | 🌐 Python | 📅 2026-07-20 - Convert Chinese hanzi (漢字) to pinyin (拼音).
  * [pangu.py](https://github.com/vinta/pangu.py) ⭐ 281 | 🐛 0 | 🌐 Python | 📅 2026-10-11 - Paranoid text spacing.

### Computer Vision

*Libraries for image and video analysis, object detection, and OCR.*

* General
  * [ultralytics](https://github.com/ultralytics/ultralytics) ⭐ 62,537 | 🐛 89 | 🌐 Python | 📅 2026-10-15 - Ultralytics YOLO for object detection, segmentation, pose estimation, classification, and tracking.
  * [kornia](https://github.com/kornia/kornia) ⭐ 11,431 | 🐛 146 | 🌐 Python | 📅 2026-10-15 - Open Source Differentiable Computer Vision Library for PyTorch.
  * [fiftyone](https://github.com/voxel51/fiftyone) ⭐ 11,190 | 🐛 720 | 🌐 TypeScript | 📅 2026-10-15 - The open-source tool for building high-quality datasets and computer vision models.
  * [opencv-python](https://github.com/opencv/opencv-python) ⭐ 5,428 | 🐛 203 | 🌐 Python | 📅 2026-09-04 - Open Source Computer Vision Library.
* OCR
  * [paddleocr](https://github.com/PaddlePaddle/PaddleOCR) ⭐ 91,183 | 🐛 246 | 🌐 Python | 📅 2026-09-16 - Multilingual OCR and document parsing toolkit based on PaddlePaddle.
  * [easyocr](https://github.com/JaidedAI/EasyOCR) ⭐ 30,074 | 🐛 533 | 🌐 Python | 📅 2025-12-05 - Ready-to-use OCR with 80+ languages supported.
  * [pytesseract](https://github.com/madmaze/pytesseract) ⭐ 6,395 | 🐛 21 | 🌐 Python | 📅 2026-10-12 - A wrapper for the [Tesseract OCR](https://github.com/tesseract-ocr/tesseract) ⭐ 77,018 | 🐛 501 | 🌐 C++ | 📅 2026-10-10 engine.

### Recommender Systems

*Libraries for building recommender systems.*

* [annoy](https://github.com/spotify/annoy) ⭐ 14,318 | 🐛 90 | 🌐 C++ | 📅 2025-10-29 - Approximate Nearest Neighbors in C++/Python optimized for memory usage.
* [scikit-surprise](https://github.com/NicolasHug/Surprise) ⭐ 6,820 | 🐛 80 | 🌐 Python | 📅 2026-05-30 - A scikit for building and analyzing recommender systems.
* [implicit](https://github.com/benfred/implicit) ⭐ 3,831 | 🐛 97 | 🌐 Python | 📅 2026-05-08 - A fast Python implementation of collaborative filtering for implicit datasets.

**Web Development**

### Web Frameworks

*Traditional full stack web frameworks. Also see [Web APIs](#web-apis).*

* Synchronous
  * [django](https://github.com/django/django) ⭐ 91,331 | 🐛 539 | 🌐 Python | 📅 2026-10-15 - A high-level web framework that encourages rapid development and clean, pragmatic design.
    * [awesome-django](https://github.com/wsvincent/awesome-django) ⭐ 11,278 | 🐛 7 | 🌐 Python | 📅 2026-10-06
  * [flask](https://github.com/pallets/flask) ⭐ 74,909 | 🐛 4 | 🌐 Python | 📅 2026-10-07 - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask) ⭐ 12,785 | 🐛 9 | 📅 2026-08-17
  * [bottle](https://github.com/bottlepy/bottle) ⭐ 8,796 | 🐛 289 | 🌐 Python | 📅 2026-10-10 - A fast and simple micro-framework distributed as a single file with no dependencies.
  * [fasthtml](https://github.com/AnswerDotAI/fasthtml) ⭐ 7,058 | 🐛 70 | 🌐 Jupyter Notebook | 📅 2026-10-09 - The fastest way to create an HTML app.
  * [pyramid](https://github.com/Pylons/pyramid) ⭐ 4,103 | 🐛 91 | 🌐 Python | 📅 2026-08-04 - A small, fast, down-to-earth, open source Python web framework.
* Asynchronous
  * [reflex](https://github.com/reflex-dev/reflex) ⭐ 28,952 | 🐛 359 | 🌐 Python | 📅 2026-10-15 - A framework for building reactive, full-stack web applications entirely with Python.
  * [tornado](https://github.com/tornadoweb/tornado) ⭐ 22,165 | 🐛 227 | 🌐 Python | 📅 2026-10-15 - A web framework and asynchronous networking library.
  * [starlette](https://github.com/Kludex/starlette) ⭐ 12,665 | 🐛 56 | 🌐 Python | 📅 2026-10-13 - A lightweight ASGI framework and toolkit for building high-performance async services.
  * [litestar](https://github.com/litestar-org/litestar) ⭐ 8,515 | 🐛 361 | 🌐 Python | 📅 2026-10-13 - Production-ready, capable and extensible ASGI Web framework.

### Web APIs

*Libraries for building RESTful, GraphQL, and RPC APIs.*

* Django
  * [django-rest-framework](https://github.com/encode/django-rest-framework) ⭐ 30,209 | 🐛 57 | 🌐 Python | 📅 2026-10-14 - A powerful and flexible toolkit to build web APIs.
  * [django-ninja](https://github.com/vitalik/django-ninja) ⭐ 9,212 | 🐛 225 | 🌐 Python | 📅 2026-10-13 - Fast, Django REST framework based on type hints and Pydantic.
  * [django-modern-rest](https://github.com/wemake-services/django-modern-rest) ⭐ 1,507 | 🐛 52 | 🌐 Python | 📅 2026-10-15 - Modern REST with speed, types, async, `msgspec`, `pydantic` and other goodies.
  * [strawberry-django](https://github.com/strawberry-graphql/strawberry-django) ⭐ 505 | 🐛 95 | 🌐 Python | 📅 2026-10-13 - Strawberry GraphQL integration with Django.
* Flask
  * [flask-restx](https://github.com/python-restx/flask-restx) ⭐ 2,233 | 🐛 322 | 🌐 Python | 📅 2026-04-14 - Fully featured framework for fast, easy and documented API development with Flask.
  * [apiflask](https://github.com/apiflask/apiflask) ⭐ 1,139 | 🐛 41 | 🌐 Python | 📅 2026-09-12 - A lightweight Python web API framework based on Flask, supporting marshmallow schemas and Pydantic models.
  * [flask-smorest](https://github.com/marshmallow-code/flask-smorest) ⭐ 717 | 🐛 59 | 🌐 Python | 📅 2026-10-13 - A Flask/Marshmallow-based REST API framework with automatic OpenAPI documentation.
* Framework Agnostic
  * [fastapi](https://github.com/fastapi/fastapi) ⭐ 103,116 | 🐛 81 | 🌐 Python | 📅 2026-10-15 - A modern, fast, web framework for building APIs with standard Python type hints.
  * [strawberry](https://github.com/strawberry-graphql/strawberry) ⭐ 4,722 | 🐛 319 | 🌐 Python | 📅 2026-10-14 - A GraphQL library that leverages Python type annotations for schema definition.
  * [connexion](https://github.com/spec-first/connexion) ⭐ 4,614 | 🐛 192 | 🌐 Python | 📅 2026-10-05 - A spec-first framework that automatically handles requests based on your OpenAPI specification.
* RPC
  * [grpcio](https://github.com/grpc/grpc) ⭐ 45,379 | 🐛 1,354 | 🌐 C++ | 📅 2026-10-15 - HTTP/2-based RPC framework with Python bindings, built by Google.

### Web Servers

*ASGI and WSGI compatible web servers.*

* ASGI
  * [uvicorn](https://github.com/Kludex/uvicorn) ⭐ 11,015 | 🐛 104 | 🌐 Python | 📅 2026-10-11 - A lightning-fast ASGI server implementation.
  * [granian](https://github.com/emmett-framework/granian) ⭐ 5,702 | 🐛 55 | 🌐 Rust | 📅 2026-10-07 - A Rust HTTP server for Python applications built on top of Hyper and Tokio, supporting WSGI/ASGI/RSGI.
  * [hypercorn](https://github.com/pgjones/hypercorn) ⭐ 1,619 | 🐛 160 | 🌐 Python | 📅 2025-11-08 - An ASGI and WSGI Server based on Hyper libraries and inspired by Gunicorn.
* WSGI
  * [gunicorn](https://github.com/benoitc/gunicorn) ⭐ 10,701 | 🐛 127 | 🌐 Python | 📅 2026-09-06 - A pre-fork WSGI server with a native ASGI worker, ported from Ruby's Unicorn project.
  * [waitress](https://github.com/Pylons/waitress) ⭐ 1,602 | 🐛 30 | 🌐 Python | 📅 2026-09-27 - Multi-threaded, powers Pyramid.

### WebSocket

*Libraries for working with WebSocket.*

* [channels](https://github.com/django/channels) ⭐ 6,363 | 🐛 123 | 🌐 Python | 📅 2026-08-06 - Brings WebSocket, long-poll HTTP, and other async support to Django.
* [websockets](https://github.com/python-websockets/websockets) ⭐ 5,733 | 🐛 1 | 🌐 Python | 📅 2026-10-15 - A library for building WebSocket servers and clients with a focus on correctness and simplicity.
* [flask-socketio](https://github.com/miguelgrinberg/Flask-SocketIO) ⭐ 5,506 | 🐛 0 | 🌐 Python | 📅 2026-10-08 - Socket.IO integration for Flask applications.
* [autobahn-python](https://github.com/crossbario/autobahn-python) ⭐ 2,540 | 🐛 198 | 🌐 Python | 📅 2026-10-14 - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).

### Template Engines

*Libraries for rendering text and HTML from templates.*

* [jinja](https://github.com/pallets/jinja) ⭐ 11,793 | 🐛 105 | 🌐 Python | 📅 2025-06-14 - A modern and designer friendly templating language.
* [mako](https://github.com/sqlalchemy/mako) ⭐ 461 | 🐛 58 | 🌐 Python | 📅 2026-09-22 - Hyperfast and lightweight templating for the Python platform.

### Web Asset Management

*Tools for managing, storing, compressing and minifying website assets.*

* [django-storages](https://github.com/jschneier/django-storages) ⭐ 2,962 | 🐛 190 | 🌐 Python | 📅 2026-08-02 - A collection of custom storage back ends for Django.
* [django-compressor](https://github.com/django-compressor/django-compressor) ⭐ 2,870 | 🐛 122 | 🌐 Python | 📅 2026-10-06 - Compresses linked and inline JavaScript or CSS into a single cached file.
* [whitenoise](https://github.com/evansd/whitenoise) ⭐ 2,763 | 🐛 40 | 🌐 Python | 📅 2026-10-04 - Radically simplified static file serving for WSGI applications, with compression and caching headers.

### Authentication

*Libraries for implementing authentication schemes.*

* OAuth
  * [django-allauth](https://github.com/pennersr/django-allauth) ⭐ 10,381 | 🐛 2 | 🌐 Python | 📅 2026-10-01 - Authentication app for Django that "just works."
  * [authlib](https://github.com/authlib/authlib) ⭐ 5,433 | 🐛 152 | 🌐 Python | 📅 2026-10-15 - A comprehensive library for building OAuth, OpenID Connect, and JWT/JWS/JWE/JWK/JWA.
  * [django-oauth-toolkit](https://github.com/django-oauth/django-oauth-toolkit) ⭐ 3,343 | 🐛 48 | 🌐 Python | 📅 2026-10-10 - An OAuth 2.0 authorization server for Django.
  * [oauthlib](https://github.com/oauthlib/oauthlib) ⭐ 2,985 | 🐛 129 | 🌐 Python | 📅 2026-10-06 - A generic and thorough implementation of the OAuth request-signing logic.
* JWT
  * [pyjwt](https://github.com/jpadilla/pyjwt) ⭐ 5,718 | 🐛 59 | 🌐 Python | 📅 2026-10-14 - JSON Web Token implementation in Python.
* Permissions
  * [django-guardian](https://github.com/django-guardian/django-guardian) ⭐ 3,921 | 🐛 30 | 🌐 Python | 📅 2026-10-13 - Implementation of per-object permissions for Django.
  * [django-rules](https://github.com/dfunckt/django-rules) ⭐ 1,976 | 🐛 41 | 🌐 Python | 📅 2025-10-11 - A tiny but powerful app providing object-level permissions to Django, without requiring a database.

### Admin Panels

*Libraries for administrative interfaces.*

* [flask-admin](https://github.com/pallets-eco/flask-admin) ⭐ 6,068 | 🐛 135 | 🌐 Python | 📅 2026-10-13 - Simple and extensible administrative interface framework for Flask.
* [django-grappelli](https://github.com/sehmaschine/django-grappelli) ⭐ 3,947 | 🐛 4 | 🌐 HTML | 📅 2026-09-17 - A jazzy skin for the Django Admin-Interface.
* [django-unfold](https://github.com/unfoldadmin/django-unfold) ⭐ 3,722 | 🐛 4 | 🌐 Python | 📅 2026-10-13 - A modern Django admin theme for building dashboards, internal tools, and business applications.
* [sqladmin](https://github.com/smithyhq/sqladmin) ⭐ 2,845 | 🐛 56 | 🌐 Python | 📅 2026-10-01 - An admin interface for SQLAlchemy models in FastAPI and Starlette.

### CMS

*Content Management Systems.*

* [wagtail](https://github.com/wagtail/wagtail) ⭐ 20,573 | 🐛 1,021 | 🌐 Python | 📅 2026-10-15 - A Django content management system.
* [django-cms](https://github.com/django-cms/django-cms) ⭐ 10,675 | 🐛 11 | 🌐 Python | 📅 2026-10-15 - The easy-to-use and developer-friendly enterprise CMS powered by Django.

### ERP

*Enterprise resource planning frameworks.*

* [odoo](https://github.com/odoo/odoo) ⭐ 55,070 | 🐛 10,996 | 🌐 Python | 📅 2026-10-15 - A suite of open source business apps: CRM, e-commerce, accounting, inventory, and thousands of community modules.

### Static Site Generators

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [pelican](https://github.com/getpelican/pelican) ⭐ 13,355 | 🐛 103 | 🌐 Python | 📅 2026-10-13 - Static site generator that supports Markdown and reST syntax.
* [nikola](https://github.com/getnikola/nikola) ⭐ 2,750 | 🐛 95 | 🌐 Python | 📅 2026-09-26 - A static website and blog generator.

**HTTP & Scraping**

### HTTP Clients

*Libraries for working with HTTP.*

* General
  * [requests](https://github.com/psf/requests) ⭐ 54,460 | 🐛 244 | 🌐 Python | 📅 2026-09-28 - HTTP Requests for Humans.
  * [aiohttp](https://github.com/aio-libs/aiohttp) ⭐ 16,574 | 🐛 233 | 🌐 Python | 📅 2026-10-15 - Asynchronous HTTP client/server framework for asyncio and Python.
  * [httpx](https://github.com/encode/httpx) ⭐ 15,602 | 🐛 140 | 🌐 Python | 📅 2026-10-02 - A next generation HTTP client for Python.
  * [urllib3](https://github.com/urllib3/urllib3) ⭐ 4,071 | 🐛 250 | 🌐 Python | 📅 2026-10-14 - An HTTP library with thread-safe connection pooling, file post, and more.
  * [httpx2](https://github.com/pydantic/httpx2) ⭐ 1,550 | 🐛 109 | 🌐 Python | 📅 2026-10-12 - HTTP/1.1 and HTTP/2 client with sync and async APIs, maintained by Pydantic ([httpx](https://github.com/encode/httpx) ⭐ 15,602 | 🐛 140 | 🌐 Python | 📅 2026-10-02 fork).
* URL Manipulation
  * [yarl](https://github.com/aio-libs/yarl) ⭐ 1,499 | 🐛 69 | 🌐 Python | 📅 2026-10-15 - Yet another URL library.

### Web Scraping

*Libraries to automate web scraping and extract web content.*

* Frameworks
  * [browser-use](https://github.com/browser-use/browser-use) ⭐ 118,096 | 🐛 554 | 🌐 Python | 📅 2026-10-15 - Make websites accessible for AI agents with easy browser automation.
  * [crawl4ai](https://github.com/unclecode/crawl4ai) ⭐ 85,622 | 🐛 237 | 🌐 Python | 📅 2026-10-15 - An open-source, LLM-friendly web crawler that provides lightning-fast, structured data extraction specifically designed for AI agents.
  * [scrapy](https://github.com/scrapy/scrapy) ⭐ 64,836 | 🐛 232 | 🌐 Python | 📅 2026-10-15 - A fast high-level web crawling and scraping framework.
  * [stagehand](https://github.com/browserbase/stagehand) ⭐ 25,688 | 🐛 387 | 🌐 TypeScript | 📅 2026-10-15 - A fast and token-efficient browser automation SDK to extract data and perform self-healing actions on web pages.
  * [jev-ultrafast](https://github.com/browser-use/jev-ultrafast) ⭐ 23,007 | 🐛 201 | 🌐 Python | 📅 2026-09-30 - A fast browser agent that picks actions from an indexed table of page elements through TypeSafe's hosted Jev API, using a small LLM only to type text.
* Content Extraction
  * [trafilatura](https://github.com/adbar/trafilatura) ⭐ 6,972 | 🐛 85 | 🌐 Python | 📅 2026-10-06 - A tool for gathering text and metadata from the web, with built-in content filtering.
  * [feedparser](https://github.com/kurtmckee/feedparser) ⭐ 2,444 | 🐛 119 | 🌐 Python | 📅 2026-10-06 - Universal feed parser.
  * [markdownify](https://github.com/matthewwithanm/python-markdownify) ⭐ 2,254 | 🐛 58 | 🌐 Python | 📅 2026-06-30 - Convert HTML to Markdown, with customizable tag handling.

### Email

*Libraries for sending email.*

* [yagmail](https://github.com/kootenpv/yagmail) ⭐ 2,738 | 🐛 111 | 🌐 Python | 📅 2026-05-26 - Yet another Gmail/SMTP client.
* [django-anymail](https://github.com/anymail/django-anymail) ⭐ 1,911 | 🐛 14 | 🌐 Python | 📅 2026-09-23 - Django email backends and webhooks for transactional email services such as Amazon SES, Brevo, Mailgun, Postmark, and Resend.
* [aiosmtplib](https://github.com/cole/aiosmtplib) ⭐ 434 | 🐛 9 | 🌐 Python | 📅 2026-10-06 - An asyncio SMTP client.

**Database & Storage**

### ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
  * [django.db.models](https://github.com/django/django) ⭐ 91,331 | 🐛 539 | 🌐 Python | 📅 2026-10-15 - (part of Django) The Django [ORM](https://docs.djangoproject.com/en/stable/topics/db/models/).
  * [sqlmodel](https://github.com/fastapi/sqlmodel) ⭐ 18,401 | 🐛 53 | 🌐 Python | 📅 2026-10-15 - SQLModel is based on Python type annotations, and powered by Pydantic and SQLAlchemy.
  * [sqlalchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,245 | 🐛 214 | 🌐 Python | 📅 2026-10-15 - The Python SQL Toolkit and Object Relational Mapper.
    * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) ⭐ 3,066 | 🐛 11 | 🌐 Python | 📅 2026-06-08
  * [peewee](https://github.com/coleifer/peewee) ⭐ 11,994 | 🐛 0 | 🌐 Python | 📅 2026-10-07 - A small, expressive ORM.
* NoSQL Databases
  * [mongoengine](https://github.com/MongoEngine/mongoengine) ⭐ 4,350 | 🐛 319 | 🌐 Python | 📅 2026-09-06 - A Python Object-Document-Mapper for working with MongoDB.
  * [beanie](https://github.com/BeanieODM/beanie) ⭐ 2,706 | 🐛 69 | 🌐 Python | 📅 2026-10-12 - An asynchronous Python object-document mapper (ODM) for MongoDB.
  * [pynamodb](https://github.com/pynamodb/PynamoDB) ⭐ 2,647 | 🐛 321 | 🌐 Python | 📅 2026-05-29 - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).
  * [django-mongodb-backend](https://github.com/mongodb/django-mongodb-backend) ⭐ 228 | 🐛 11 | 🌐 Python | 📅 2026-10-09 - Official MongoDB database backend for Django.

### Database Drivers

*Libraries for connecting and operating databases.*

* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres) ⭐ 12,115 | 🐛 100 | 📅 2026-08-31
  * [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 8,107 | 🐛 278 | 🌐 Python | 📅 2026-10-08 - A fast PostgreSQL Database Client Library for Python/asyncio.
  * [psycopg](https://github.com/psycopg/psycopg) ⭐ 2,510 | 🐛 64 | 🌐 Python | 📅 2026-10-12 - A PostgreSQL adapter for Python, the successor to psycopg2.
* MySQL - [awesome-mysql](https://github.com/shlomi-noach/awesome-mysql) ⭐ 2,617 | 🐛 25 | 🌐 Python | 📅 2026-10-08
  * [pymysql](https://github.com/PyMySQL/PyMySQL) ⭐ 7,853 | 🐛 20 | 🌐 Python | 📅 2026-10-14 - A pure-Python MySQL and MariaDB client library, based on PEP 249.
  * [mysqlclient](https://github.com/PyMySQL/mysqlclient) ⭐ 2,538 | 🐛 5 | 🌐 Python | 📅 2026-10-13 - MySQL and MariaDB connector ([MySQLdb1](https://github.com/farcepest/MySQLdb1) ⭐ 664 | 🐛 88 | 🌐 Python | 📅 2020-10-26 fork).
* SQLite - [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite) ⭐ 407 | 🐛 19 | 📅 2026-08-22
  * [sqlite-utils](https://github.com/simonw/sqlite-utils) ⭐ 2,179 | 🐛 149 | 🌐 Python | 📅 2026-10-11 - Python CLI utility and library for manipulating SQLite databases.
  * [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python standard library) SQLite interface compliant with DB-API 2.0.
* ClickHouse
  * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) ⭐ 1,307 | 🐛 77 | 🌐 Python | 📅 2026-07-22 - Python driver with native interface for ClickHouse.
  * [clickhouse-connect](https://github.com/ClickHouse/clickhouse-connect) ⭐ 531 | 🐛 19 | 🌐 Python | 📅 2026-10-15 - The official ClickHouse client, with SQLAlchemy and Superset connectors.
* Other Relational Databases
  * [pyodbc](https://github.com/mkleehammer/pyodbc) ⭐ 3,090 | 🐛 65 | 🌐 C++ | 📅 2026-10-03 - An ODBC bridge for connecting to SQL Server and any other ODBC-accessible database.
  * [mssql-python](https://github.com/microsoft/mssql-python) ⭐ 480 | 🐛 73 | 🌐 Python | 📅 2026-10-14 - Official Microsoft driver for SQL Server and Azure SQL, built on ODBC for high performance.
  * [oracledb](https://github.com/oracle/python-oracledb) ⭐ 455 | 🐛 32 | 🌐 Python | 📅 2026-10-07 - The official Python driver for Oracle Database, successor to cx\_Oracle.
* NoSQL Databases
  * [redis](https://github.com/redis/redis-py) ⭐ 13,650 | 🐛 83 | 🌐 Python | 📅 2026-10-15 - The Python client for Redis.
  * [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,358 | 🐛 17 | 🌐 Python | 📅 2026-10-15 - The official Python client for MongoDB.
  * [cassandra-driver](https://github.com/apache/cassandra-python-driver) ⭐ 1,430 | 🐛 18 | 🌐 Python | 📅 2026-07-21 - The Python Driver for Apache Cassandra.

### Database

*In-process databases usable directly from Python.*

* Analytical
  * [duckdb](https://github.com/duckdb/duckdb) ⭐ 42,186 | 🐛 961 | 🌐 C++ | 📅 2026-10-15 - An in-process SQL OLAP database management system; optimized for analytics and fast queries, similar to SQLite but for analytical workloads.
  * [chdb](https://github.com/chdb-io/chdb) ⭐ 2,917 | 🐛 46 | 🌐 Python | 📅 2026-10-13 - In-process OLAP SQL engine with the full ClickHouse dialect, zero-copy pandas/Arrow interop, and federation to remote ClickHouse clusters via `remoteSecure()`.
* Vector
  * [chromadb](https://github.com/chroma-core/chroma) ⭐ 29,512 | 🐛 946 | 🌐 Rust | 📅 2026-10-15 - An open-source embedding database for building AI applications with embeddings and semantic search.
  * [zvec](https://github.com/alibaba/zvec) ⭐ 16,114 | 🐛 86 | 🌐 C++ | 📅 2026-10-14 - A lightweight, in-process vector database that embeds directly into applications.
  * [lancedb](https://github.com/lancedb/lancedb) ⭐ 11,681 | 🐛 734 | 🌐 Rust | 📅 2026-10-15 - A developer-friendly embedded retrieval database for multimodal AI.
* Key-Value & Document
  * [tinydb](https://github.com/msiemens/tinydb) ⭐ 7,572 | 🐛 6 | 🌐 Python | 📅 2026-10-15 - A tiny, document-oriented database.

### Caching

*Libraries for caching data.*

* [diskcache](https://github.com/grantjenks/python-diskcache) ⭐ 2,915 | 🐛 88 | 🌐 Python | 📅 2024-08-10 - SQLite and file backed cache backend, compatible with Django.
* [cachetools](https://github.com/tkem/cachetools) ⭐ 2,787 | 🐛 3 | 🌐 Python | 📅 2026-10-15 - Extensible memoizing collections and decorators.
* [django-cacheops](https://github.com/Suor/django-cacheops) ⭐ 2,271 | 🐛 23 | 🌐 Python | 📅 2026-04-15 - A slick ORM cache with automatic granular event-driven invalidation.
* [hishel](https://github.com/karpetrosyan/hishel) ⭐ 413 | 🐛 14 | 🌐 Python | 📅 2026-10-05 - RFC 9111 compliant HTTP caching for clients like httpx and requests and servers like FastAPI, with sync and async support.
* [dogpile.cache](https://github.com/sqlalchemy/dogpile.cache) ⭐ 299 | 🐛 49 | 🌐 Python | 📅 2026-08-11 - dogpile.cache is a next generation replacement for Beaker made by the same authors.

### Search

*Libraries and software for indexing and performing search queries on data.*

* [elasticsearch](https://github.com/elastic/elasticsearch-py) ⭐ 4,392 | 🐛 66 | 🌐 Python | 📅 2026-10-12 - The official low-level Python client for [Elasticsearch](https://www.elastic.co/elasticsearch).
* [django-haystack](https://github.com/django-haystack/django-haystack) ⭐ 3,724 | 🐛 584 | 🌐 Python | 📅 2026-10-14 - Modular search for Django.
* [meilisearch](https://github.com/meilisearch/meilisearch-python) ⭐ 606 | 🐛 17 | 🌐 Python | 📅 2026-10-14 - The official Python client for the [Meilisearch](https://www.meilisearch.com/) search engine.
* [opensearch-py](https://github.com/opensearch-project/opensearch-py) ⭐ 472 | 🐛 124 | 🌐 Python | 📅 2026-09-03 - The official low-level Python client for [OpenSearch](https://opensearch.org/).

### Serialization

*Libraries for serializing complex data types.*

* [orjson](https://github.com/ijl/orjson) ⭐ 8,255 | 🐛 0 | 🌐 Python | 📅 2026-10-07 - Fast, correct JSON library.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) ⭐ 7,249 | 🐛 154 | 🌐 Python | 📅 2026-10-06 - A lightweight library for converting complex objects to and from simple Python datatypes.
* [msgspec](https://github.com/msgspec/msgspec) ⭐ 4,168 | 🐛 240 | 🌐 Python | 📅 2026-10-15 - A fast serialization and validation library with built-in support for JSON, MessagePack, YAML, and TOML.
* [msgpack](https://github.com/msgpack/msgpack-python) ⭐ 2,107 | 🐛 12 | 🌐 Python | 📅 2026-10-14 - MessagePack serializer implementation for Python.

**Data & Science**

### Data Analysis

*Libraries for data analysis.*

* [pandas](https://github.com/pandas-dev/pandas) ⭐ 50,055 | 🐛 2,224 | 🌐 Python | 📅 2026-10-15 - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [polars](https://github.com/pola-rs/polars) ⭐ 40,093 | 🐛 2,971 | 🌐 Rust | 📅 2026-10-15 - A fast DataFrame library implemented in Rust with a Python API.
* [ibis-framework](https://github.com/ibis-project/ibis) ⭐ 6,675 | 🐛 538 | 🌐 Python | 📅 2026-10-15 - A portable Python dataframe library with a single API for 20+ backends.

### Data Ingestion / ETL

*Libraries for data extraction, transformation, and loading pipelines across multiple sources and destinations.*

* General
  * [dlt](https://github.com/dlt-hub/dlt) ⭐ 5,969 | 🐛 453 | 🌐 Python | 📅 2026-10-15 - A Python library for building data pipelines with automatic schema inference, incremental loading, and support for multiple sources and destinations.
  * [awswrangler](https://github.com/aws/aws-sdk-pandas) ⭐ 4,122 | 🐛 45 | 🌐 Python | 📅 2026-10-15 - Pandas integration with AWS services like Athena, Glue, Redshift, S3, and DynamoDB.
* Financial Data
  * [openbb](https://github.com/openbq-org/OpenBB) ⭐ 74,271 | 🐛 101 | 🌐 Python | 📅 2026-10-15 - A financial data platform for analysts, quants and AI agents.
  * [yfinance](https://github.com/ranaroussi/yfinance) ⭐ 25,531 | 🐛 110 | 🌐 Python | 📅 2026-10-12 - Easy Pythonic way to download market and financial data from Yahoo Finance.
  * [akshare](https://github.com/akfamily/akshare) ⭐ 22,942 | 🐛 3 | 🌐 Python | 📅 2026-10-14 - A financial data interface library, with data provided for academic research only.
  * [edgartools](https://github.com/dgunning/edgartools) ⭐ 2,793 | 🐛 43 | 🌐 Python | 📅 2026-10-15 - Library for downloading structured data from SEC EDGAR filings and XBRL financial statements.

### Data Validation

*Libraries for validating data.*

* [pydantic](https://github.com/pydantic/pydantic) ⭐ 29,050 | 🐛 586 | 🌐 Python | 📅 2026-10-15 - Data validation using Python type hints.
* [great-expectations](https://github.com/fivetran/great_expectations) ⭐ 11,874 | 🐛 52 | 🌐 Python | 📅 2026-10-14 - A data quality framework for validating, documenting, and profiling data with declarative expectations.
* [jsonschema](https://github.com/python-jsonschema/jsonschema) ⭐ 4,989 | 🐛 56 | 🌐 Python | 📅 2026-10-12 - An implementation of [JSON Schema](https://json-schema.org/) for Python.
* [pandera](https://github.com/unionai-oss/pandera) ⭐ 4,482 | 🐛 460 | 🌐 Python | 📅 2026-10-15 - A data validation library for dataframes, with support for pandas, polars, PySpark, and more.

### Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization) ⭐ 35,026 | 🐛 27 | 📅 2026-10-14.*

* Plotting
  * [matplotlib](https://github.com/matplotlib/matplotlib) ⭐ 23,373 | 🐛 1,490 | 🌐 Python | 📅 2026-10-15 - A comprehensive library for creating static, animated, and interactive visualizations.
  * [bokeh](https://github.com/bokeh/bokeh) ⭐ 20,457 | 🐛 805 | 🌐 TypeScript | 📅 2026-10-15 - Interactive Web Plotting for Python.
  * [plotly](https://github.com/plotly/plotly.py) ⭐ 18,843 | 🐛 728 | 🌐 Python | 📅 2026-10-15 - Interactive graphing library for Python.
  * [seaborn](https://github.com/mwaskom/seaborn) ⭐ 14,074 | 🐛 253 | 🌐 Python | 📅 2026-10-08 - Statistical data visualization using Matplotlib.
  * [altair](https://github.com/vega/altair) ⭐ 10,500 | 🐛 163 | 🌐 Python | 📅 2026-10-14 - Declarative statistical visualization library for Python.
* Specialized
  * [graphify](https://github.com/Graphify-Labs/graphify) ⭐ 126,896 | 🐛 1,517 | 🌐 Python | 📅 2026-10-14 - Turn any folder of code, SQL schemas, docs, papers, images, or videos into a queryable knowledge graph.
  * [graphviz](https://github.com/xflr6/graphviz) ⭐ 1,814 | 🐛 10 | 🌐 Python | 📅 2026-07-11 - Simple Python interface for creating and rendering Graphviz graphs.
  * [cartopy](https://github.com/SciTools/cartopy) ⭐ 1,622 | 🐛 323 | 🌐 Python | 📅 2026-10-14 - A cartographic python library with matplotlib support.
* Dashboards and Apps
  * [streamlit](https://github.com/streamlit/streamlit) ⭐ 46,003 | 🐛 1,180 | 🌐 Python | 📅 2026-10-15 - A framework which lets you build dashboards, generate reports, or create chat apps in minutes.
  * [gradio](https://github.com/gradio-app/gradio) ⭐ 43,773 | 🐛 107 | 🌐 Python | 📅 2026-10-15 - Build and share machine learning apps, all in Python.
  * [dash](https://github.com/plotly/dash) ⭐ 24,453 | 🐛 433 | 🌐 Python | 📅 2026-10-15 - A framework for building data apps and dashboards in pure Python, built on Plotly.

### Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [geodjango](https://github.com/django/django) ⭐ 91,331 | 🐛 539 | 🌐 Python | 📅 2026-10-15 - (part of Django) A world-class [geographic web framework](https://docs.djangoproject.com/en/stable/ref/contrib/gis/).
* [geopandas](https://github.com/geopandas/geopandas) ⭐ 5,276 | 🐛 430 | 🌐 Python | 📅 2026-10-12 - Python tools for geographic data (GeoSeries/GeoDataFrame) built on pandas.
* [geopy](https://github.com/geopy/geopy) ⭐ 4,869 | 🐛 59 | 🌐 Python | 📅 2026-07-12 - Python Geocoding Toolbox.
* [geojson](https://github.com/jazzband/geojson) ⭐ 998 | 🐛 29 | 🌐 Python | 📅 2026-10-05 - Python bindings and utilities for GeoJSON.

### Science

*Libraries for scientific computing. Also see [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists) ⭐ 378 | 🐛 3 | 📅 2025-06-27.*

* Core
  * [numpy](https://github.com/numpy/numpy) ⭐ 33,018 | 🐛 2,241 | 🌐 Python | 📅 2026-10-15 - A fundamental package for scientific computing with Python.
  * [scipy](https://github.com/scipy/scipy) ⭐ 15,114 | 🐛 1,873 | 🌐 Python | 📅 2026-10-15 - Fundamental algorithms for scientific computing in Python.
  * [numba](https://github.com/numba/numba) ⭐ 11,179 | 🐛 1,823 | 🌐 Python | 📅 2026-10-15 - A NumPy-aware JIT compiler for Python, using LLVM.
* Symbolic Mathematics
  * [sympy](https://github.com/sympy/sympy) ⭐ 15,016 | 🐛 6,028 | 🌐 Python | 📅 2026-10-15 - A Python library for symbolic mathematics.
* Statistics
  * [statsmodels](https://github.com/statsmodels/statsmodels) ⭐ 11,686 | 🐛 2,810 | 🌐 Python | 📅 2026-10-15 - Statistical modeling and econometrics in Python.
* Biology and Chemistry
  * [biopython](https://github.com/biopython/biopython) ⭐ 5,233 | 🐛 634 | 🌐 Python | 📅 2026-10-11 - Biopython is a set of freely available tools for biological computation.
  * [rdkit](https://github.com/rdkit/rdkit) ⭐ 3,625 | 🐛 92 | 🌐 HTML | 📅 2026-10-15 - Cheminformatics and Machine Learning Software.
* Physics and Engineering
  * [astropy](https://github.com/astropy/astropy) ⭐ 5,345 | 🐛 1,406 | 🌐 Python | 📅 2026-10-15 - A community Python library for Astronomy.
  * [pint](https://github.com/hgrecco/pint) ⭐ 2,814 | 🐛 212 | 🌐 Python | 📅 2026-10-13 - Operate and manipulate physical quantities with units and dimensional analysis.
  * [obspy](https://github.com/obspy/obspy) ⭐ 1,340 | 🐛 322 | 🌐 Python | 📅 2026-10-14 - A Python toolbox for seismology.
* Simulation and Modeling
  * [pymc](https://github.com/pymc-devs/pymc) ⭐ 9,809 | 🐛 521 | 🌐 Python | 📅 2026-10-13 - Probabilistic programming and Bayesian modeling in Python.
  * [mesa](https://github.com/mesa/mesa) ⭐ 3,890 | 🐛 136 | 🌐 Python | 📅 2026-10-10 - An agent-based modeling framework for building, analyzing, and visualizing complex system simulations.
  * [simpy](https://gitlab.com/team-simpy/simpy) - A process-based discrete-event simulation framework.
* Graphs and Networks
  * [networkx](https://github.com/networkx/networkx) ⭐ 17,329 | 🐛 321 | 🌐 Python | 📅 2026-10-06 - A high-productivity software for complex networks.
* Computational Geometry
  * [shapely](https://github.com/shapely/shapely) ⭐ 4,526 | 🐛 223 | 🌐 Python | 📅 2026-10-14 - Manipulation and analysis of geometric objects in the Cartesian plane.
* Other
  * [manim](https://github.com/ManimCommunity/manim) ⭐ 41,569 | 🐛 497 | 🌐 Python | 📅 2026-10-12 - An animation engine for explanatory math videos.
  * [colour-science](https://github.com/colour-science/colour) ⭐ 2,665 | 🐛 95 | 🌐 Python | 📅 2026-10-12 - Implementing a comprehensive number of colour theory transformations and algorithms.

### Quantum Computing

*Libraries for quantum computing.*

* [qiskit](https://github.com/Qiskit/qiskit) ⭐ 7,892 | 🐛 1,023 | 🌐 Python | 📅 2026-10-15 - An IBM-backed quantum SDK for building, simulating, and running circuits on real quantum hardware.
* [cirq](https://github.com/quantumlib/Cirq) ⭐ 5,081 | 🐛 134 | 🌐 Python | 📅 2026-10-15 - A Google-developed framework focused on hardware-aware quantum circuit design for NISQ devices.
* [pennylane](https://github.com/PennyLaneAI/pennylane) ⭐ 3,499 | 🐛 465 | 🌐 Python | 📅 2026-10-15 - A cross-platform library for quantum computing, quantum machine learning, and quantum chemistry.
* [qutip](https://github.com/qutip/qutip) ⭐ 2,086 | 🐛 121 | 🌐 Python | 📅 2026-10-15 - Quantum Toolbox in Python.

**Developer Tools**

### Algorithms and Design Patterns

*Python implementation of data structures, algorithms and design patterns. Also see [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) ⭐ 25,617 | 🐛 0 | 📅 2026-10-13.*

* Algorithms
  * [thealgorithms](https://github.com/TheAlgorithms/Python) ⭐ 225,284 | 🐛 26 | 🌐 Python | 📅 2026-10-14 - All Algorithms implemented in Python.
  * [algorithms](https://github.com/keon/algorithms) ⭐ 25,564 | 🐛 18 | 🌐 Python | 📅 2026-09-25 - Minimal examples of data structures and algorithms.
  * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) ⭐ 3,983 | 🐛 44 | 🌐 Python | 📅 2024-03-08 - Fast and pure-Python implementation of sorted collections.
* Design Patterns
  * [python-patterns](https://github.com/faif/python-patterns) ⭐ 43,045 | 🐛 15 | 🌐 Python | 📅 2026-10-15 - A collection of design patterns and idioms in Python.
  * [python-statemachine](https://github.com/fgmacedo/python-statemachine) ⭐ 1,322 | 🐛 44 | 🌐 Python | 📅 2026-10-15 - Expressive statecharts and finite state machines with a declarative API, in sync and async codebases.

### Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [marimo](https://github.com/marimo-team/marimo) ⭐ 23,196 | 🐛 624 | 🌐 Python | 📅 2026-10-15 - A reactive notebook for Python, stored as pure Python and runnable as a script or app.
* [ipython](https://github.com/ipython/ipython) ⭐ 16,791 | 🐛 1,322 | 🌐 Python | 📅 2026-10-09 - A powerful interactive Python shell, and the kernel behind Jupyter notebooks.
* [notebook](https://github.com/jupyter/notebook) ⭐ 13,441 | 🐛 1,892 | 🌐 Jupyter Notebook | 📅 2026-10-15 - A web-based notebook environment for interactive computing.
  * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter) ⭐ 4,676 | 🐛 7 | 📅 2026-10-15
* [ptpython](https://github.com/prompt-toolkit/ptpython) ⭐ 5,457 | 🐛 266 | 🌐 Python | 📅 2025-11-21 - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,595 | 🐛 762 | 🌐 Python | 📅 2026-07-26.

### Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis](https://github.com/analysis-tools-dev/static-analysis) ⭐ 14,836 | 🐛 3 | 🌐 Rust | 📅 2026-10-15.*

* Type Checkers - [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) ⭐ 1,988 | 🐛 7 | 📅 2026-09-23
  * [mypy](https://github.com/python/mypy) ⭐ 20,683 | 🐛 3,239 | 🌐 Python | 📅 2026-10-15 - A static type checker for Python.
  * [ty](https://github.com/astral-sh/ty) ⭐ 19,871 | 🐛 940 | 🌐 Python | 📅 2026-10-15 - An extremely fast Python type checker and language server.
  * [pyright](https://github.com/microsoft/pyright) ⭐ 15,681 | 🐛 348 | 🌐 Python | 📅 2026-10-15 - Full-featured static type checker for Python from Microsoft, the engine behind Pylance.
  * [pyrefly](https://github.com/facebook/pyrefly) ⭐ 7,095 | 🐛 708 | 🌐 Rust | 📅 2026-10-15 - A fast type checker and language server for Python.
* General
  * [vulture](https://github.com/jendrikseipp/vulture) ⭐ 4,848 | 🐛 75 | 🌐 Python | 📅 2026-10-12 - A tool for finding and analyzing dead Python code.
  * [prospector](https://github.com/prospector-dev/prospector) ⭐ 2,083 | 🐛 32 | 🌐 Python | 📅 2026-10-12 - A tool to analyze Python code.
  * [import-linter](https://github.com/seddonym/import-linter) ⭐ 1,223 | 🐛 73 | 🌐 Python | 📅 2026-10-13 - A linter that enforces architectural constraints on imports between Python modules.
  * [complexipy](https://github.com/rohaquinlop/complexipy) ⭐ 885 | 🐛 10 | 🌐 Rust | 📅 2026-10-15 - Cognitive complexity analysis for Python code, written in Rust.
* Git Hooks
  * [pre-commit](https://github.com/pre-commit/pre-commit) ⭐ 15,636 | 🐛 25 | 🌐 Python | 📅 2026-10-13 - A framework for managing and maintaining multi-language pre-commit hooks.
* Linters and Formatters
  * [ruff](https://github.com/astral-sh/ruff) ⭐ 50,104 | 🐛 2,229 | 🌐 Rust | 📅 2026-10-15 - An extremely fast Python linter and code formatter.
  * [black](https://github.com/psf/black) ⭐ 41,930 | 🐛 284 | 🌐 Python | 📅 2026-10-12 - The uncompromising Python code formatter.
  * [bandit](https://github.com/PyCQA/bandit) ⭐ 8,313 | 🐛 262 | 🌐 Python | 📅 2026-10-12 - A tool designed to find common security issues in Python code.
  * [isort](https://github.com/PyCQA/isort) ⭐ 6,963 | 🐛 89 | 🌐 Python | 📅 2026-10-15 - A Python utility / library to sort imports.
  * [pylint](https://github.com/pylint-dev/pylint) ⭐ 5,739 | 🐛 1,011 | 🌐 Python | 📅 2026-10-15 - A fully customizable source code analyzer.
  * [flake8](https://github.com/PyCQA/flake8) ⭐ 3,829 | 🐛 24 | 🌐 Python | 📅 2026-10-13 - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
    * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) ⭐ 1,283 | 🐛 1 | 📅 2026-07-21
* Refactoring
  * [rope](https://github.com/python-rope/rope) ⭐ 2,242 | 🐛 166 | 🌐 Python | 📅 2026-10-08 - Rope is a python refactoring library.

### Testing

*Libraries for testing codebases and generating test data. Also see [awesome-python-testing](https://github.com/cleder/awesome-python-testing) ⭐ 315 | 🐛 2 | 📅 2026-10-13.*

* Frameworks
  * [pytest](https://github.com/pytest-dev/pytest) ⭐ 14,600 | 🐛 859 | 🌐 Python | 📅 2026-10-13 - A mature full-featured Python testing tool.
    * [awesome-pytest](https://github.com/augustogoulart/awesome-pytest) ⭐ 576 | 🐛 5 | 📅 2026-06-24
  * [robotframework](https://github.com/robotframework/robotframework) ⭐ 11,943 | 🐛 314 | 🌐 Python | 📅 2026-10-06 - A generic test automation framework.
  * [hypothesis](https://github.com/HypothesisWorks/hypothesis) ⭐ 9,085 | 🐛 43 | 🌐 Python | 📅 2026-10-15 - Hypothesis is an advanced Quickcheck style property based testing library.
* Test Runners
  * [tox](https://github.com/tox-dev/tox) ⭐ 3,958 | 🐛 0 | 🌐 Python | 📅 2026-10-15 - Auto builds and tests distributions in multiple Python versions.
  * [nox](https://github.com/wntrblm/nox) ⭐ 1,561 | 🐛 77 | 🌐 Python | 📅 2026-10-13 - Flexible test automation for Python.
* Browser Automation
  * [selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,552 | 🐛 193 | 🌐 Java | 📅 2026-10-15 - Python bindings for [Selenium](https://selenium.dev/) [WebDriver](https://selenium.dev/documentation/webdriver/).
  * [playwright-python](https://github.com/microsoft/playwright-python) ⭐ 15,044 | 🐛 1 | 🌐 Python | 📅 2026-10-15 - Python version of the Playwright testing and automation library.
  * [seleniumbase](https://github.com/seleniumbase/SeleniumBase) ⭐ 13,075 | 🐛 10 | 🌐 Python | 📅 2026-10-13 - Python framework for web automation & testing, with stealth options.
* Load Testing
  * [locust](https://github.com/locustio/locust) ⭐ 28,212 | 🐛 6 | 🌐 Python | 📅 2026-10-15 - Scalable user load testing tool written in Python.
* API Testing
  * [schemathesis](https://github.com/schemathesis/schemathesis) ⭐ 3,668 | 🐛 23 | 🌐 Python | 📅 2026-10-15 - A tool for automatic property-based testing of web APIs from OpenAPI or GraphQL schemas.
* Mock
  * [responses](https://github.com/getsentry/responses) ⭐ 4,342 | 🐛 52 | 🌐 Python | 📅 2026-10-06 - A utility library for mocking out the requests Python library.
  * [vcrpy](https://github.com/kevin1024/vcrpy) ⭐ 3,021 | 🐛 182 | 🌐 Python | 📅 2026-10-13 - Record and replay HTTP interactions on your tests.
  * [time-machine](https://github.com/adamchainz/time-machine) ⭐ 1,013 | 🐛 9 | 🌐 Python | 📅 2026-10-05 - Travel through time in your tests by mocking the current time at the C level.
  * [respx](https://github.com/lundberg/respx) ⭐ 841 | 🐛 33 | 🌐 Python | 📅 2026-07-21 - Mock HTTPX with awesome request patterns and response side effects.
  * [unittest.mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
* Object Factories
  * [factory-boy](https://github.com/FactoryBoy/factory_boy) ⭐ 3,811 | 🐛 209 | 🌐 Python | 📅 2026-01-01 - A test fixtures replacement for Python.
  * [polyfactory](https://github.com/litestar-org/polyfactory) ⭐ 1,515 | 🐛 82 | 🌐 Python | 📅 2026-10-11 - A mock data generation library based on type hints (continuation of `pydantic-factories`).
* Code Coverage
  * [coverage](https://github.com/coveragepy/coveragepy) ⭐ 3,420 | 🐛 322 | 🌐 Python | 📅 2026-10-15 - Code coverage measurement.
* Fake Data
  * [faker](https://github.com/joke2k/faker) ⭐ 19,447 | 🐛 45 | 🌐 Python | 📅 2026-10-09 - A Python package that generates fake data.
  * [mimesis](https://github.com/lk-geimfari/mimesis) ⭐ 4,848 | 🐛 17 | 🌐 Python | 📅 2026-10-06 - A Python library for generating fake but realistic data in multiple languages and locales.

### Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
  * [pudb](https://github.com/inducer/pudb) ⭐ 3,250 | 🐛 164 | 🌐 Python | 📅 2026-10-14 - A full-screen, console-based Python debugger.
  * [ipdb](https://github.com/gotcha/ipdb) ⭐ 1,975 | 🐛 81 | 🌐 Python | 📅 2026-02-27 - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
* Tracing
  * [viztracer](https://github.com/gaogaotiantian/viztracer) ⭐ 7,754 | 🐛 33 | 🌐 Python | 📅 2026-09-26 - A low-overhead tool that traces and visualizes Python code execution.
* Profiler
  * [py-spy](https://github.com/benfred/py-spy) ⭐ 15,573 | 🐛 234 | 🌐 Rust | 📅 2026-10-15 - A sampling profiler for Python programs. Written in Rust.
  * [memray](https://github.com/bloomberg/memray) ⭐ 15,382 | 🐛 44 | 🌐 Python | 📅 2026-10-14 - A memory profiler that tracks allocations in Python code, native extensions, and the interpreter itself.
  * [scalene](https://github.com/plasma-umass/scalene) ⭐ 13,526 | 🐛 154 | 🌐 Python | 📅 2026-10-01 - A high-performance, high-precision CPU, GPU, and memory profiler for Python.
  * [pyinstrument](https://github.com/joerick/pyinstrument) ⭐ 8,016 | 🐛 32 | 🌐 Python | 📅 2026-10-12 - A statistical wall-clock profiler with low overhead and readable call-tree output.
* Others
  * [icecream](https://github.com/gruns/icecream) ⭐ 10,109 | 🐛 77 | 🌐 Python | 📅 2026-08-21 - Inspect variables, expressions, and program execution with a single, simple function call.
  * [django-debug-toolbar](https://github.com/django-commons/django-debug-toolbar) ⭐ 8,379 | 🐛 84 | 🌐 Python | 📅 2026-10-15 - Display various debug information for Django.
  * [flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar) ⭐ 978 | 🐛 39 | 🌐 JavaScript | 📅 2026-10-05 - A port of the django-debug-toolbar to flask.

### Build Tools

*Task runners and software build tools. If you're looking for Python packaging/build tools, see [Package Management](#package-management).*

* [invoke](https://github.com/pyinvoke/invoke) ⭐ 4,780 | 🐛 468 | 🌐 Python | 📅 2026-04-07 - A tool for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
* [scons](https://github.com/SCons/scons) ⭐ 2,435 | 🐛 655 | 🌐 Python | 📅 2026-10-15 - A software construction tool.
* [doit](https://github.com/pydoit/doit) ⭐ 2,094 | 🐛 101 | 🌐 Python | 📅 2026-09-21 - A task runner and build tool.
* [poethepoet](https://github.com/nat-n/poethepoet) ⭐ 2,090 | 🐛 12 | 🌐 Python | 📅 2026-10-15 - A task runner that defines tasks in pyproject.toml and works with poetry or uv.

### Documentation

*Libraries for generating project documentation.*

* [diagrams](https://github.com/mingrammer/diagrams) ⭐ 42,727 | 🐛 396 | 🌐 Python | 📅 2026-10-15 - Diagram as Code.
* [mkdocs-material](https://github.com/squidfunk/mkdocs-material) ⭐ 27,576 | 🐛 1 | 🌐 Python | 📅 2026-10-14 - A documentation framework and Material Design theme built on MkDocs.
* [sphinx](https://github.com/sphinx-doc/sphinx) ⭐ 8,061 | 🐛 1,474 | 🌐 Python | 📅 2026-10-12 - Python Documentation generator.
  * [awesome-sphinxdoc](https://github.com/ygzgxyz/awesome-sphinxdoc) ⭐ 979 | 🐛 9 | 🌐 HTML | 📅 2025-10-07
* [zensical](https://github.com/zensical/zensical) ⭐ 5,916 | 🐛 5 | 🌐 Rust | 📅 2026-10-15 - A modern static site generator for technical documentation.
* [pdoc](https://github.com/mitmproxy/pdoc) ⭐ 2,518 | 🐛 74 | 🌐 Python | 📅 2026-07-01 - Auto-generates API documentation for Python projects.

**DevOps**

### DevOps Tools

*Software and libraries for DevOps.*

* Cloud Providers
  * [awscli](https://github.com/aws/aws-cli) ⭐ 17,306 | 🐛 768 | 🌐 Python | 📅 2026-10-15 - Universal Command Line Interface for Amazon Web Services; the PyPI package is v1, in maintenance mode, while v2 ships as AWS's bundled installer.
  * [boto3](https://github.com/boto/boto3) ⭐ 9,909 | 🐛 189 | 🌐 Python | 📅 2026-10-15 - Python interface to Amazon Web Services.
  * [azure-sdk-for-python](https://github.com/Azure/azure-sdk-for-python) ⭐ 5,621 | 🐛 1,176 | 🌐 Python | 📅 2026-10-15 - Microsoft Azure SDK for Python, published as per-service packages.
  * [google-cloud-python](https://github.com/googleapis/google-cloud-python) ⭐ 5,408 | 🐛 610 | 🌐 Python | 📅 2026-10-15 - Google Cloud client libraries for Python, published as per-service packages.
* Configuration Management
  * [ansible](https://github.com/ansible/ansible) ⭐ 70,983 | 🐛 856 | 🌐 Python | 📅 2026-10-15 - A radically simple IT automation platform.
  * [salt](https://github.com/saltstack/salt) ⭐ 15,715 | 🐛 1,704 | 🌐 Python | 📅 2026-10-15 - Infrastructure automation and management system.
  * [pyinfra](https://github.com/pyinfra-dev/pyinfra) ⭐ 6,035 | 🐛 160 | 🌐 Python | 📅 2026-10-15 - Turns Python code into shell commands and runs them on your servers.
  * [cloud-init](https://github.com/canonical/cloud-init) ⭐ 3,834 | 🐛 607 | 🌐 Python | 📅 2026-10-15 - A multi-distribution package that handles early initialization of a cloud instance.
* Deployment
  * [fabric](https://github.com/fabric/fabric) ⭐ 15,516 | 🐛 506 | 🌐 Python | 📅 2026-04-10 - A simple, Pythonic tool for remote execution and deployment.
  * [chalice](https://github.com/aws/chalice) ⭐ 11,056 | 🐛 496 | 🌐 Python | 📅 2026-10-15 - A Python serverless microframework for AWS.
* Monitoring and Processes
  * [psutil](https://github.com/giampaolo/psutil) ⭐ 11,295 | 🐛 283 | 🌐 Python | 📅 2026-10-15 - A cross-platform process and system utilities module.
  * [supervisor](https://github.com/Supervisor/supervisor) ⭐ 9,142 | 🐛 184 | 🌐 Python | 📅 2025-12-21 - Supervisor process control system for UNIX.
  * [sh](https://github.com/amoffat/sh) ⭐ 7,246 | 🐛 7 | 🌐 Python | 📅 2026-07-25 - A full-fledged subprocess replacement for Python.
  * [flower](https://github.com/mher/flower) ⭐ 7,238 | 🐛 37 | 🌐 Python | 📅 2026-09-22 - A real-time monitor and web admin for Celery task queues.
  * [sentry-sdk](https://github.com/getsentry/sentry-python) ⭐ 2,215 | 🐛 369 | 🌐 Python | 📅 2026-10-15 - Sentry SDK for Python.
* Other
  * [borgbackup](https://github.com/borgbackup/borg) ⭐ 13,844 | 🐛 182 | 🌐 Python | 📅 2026-10-14 - A deduplicating archiver with compression and encryption.

### Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* [pyspark](https://github.com/apache/spark) ⭐ 44,215 | 🐛 687 | 🌐 Scala | 📅 2026-10-15 - [Apache Spark](https://spark.apache.org/) Python API.
* [ray](https://github.com/ray-project/ray) ⭐ 44,036 | 🐛 3,597 | 🌐 Python | 📅 2026-10-15 - A unified framework for scaling AI and Python applications.
* [dask](https://github.com/dask/dask) ⭐ 13,935 | 🐛 1,368 | 🌐 Python | 📅 2026-09-29 - A flexible parallel computing library for analytic computing.
* [joblib](https://github.com/joblib/joblib) ⭐ 4,406 | 🐛 442 | 🌐 Python | 📅 2026-10-15 - Parallel computing and disk-based caching for Python functions.
* [mpi4py](https://github.com/mpi4py/mpi4py) ⭐ 928 | 🐛 6 | 🌐 Python | 📅 2026-10-15 - Python bindings for MPI.

### Task Queues

*Libraries for working with task queues.*

* [celery](https://github.com/celery/celery) ⭐ 28,989 | 🐛 718 | 🌐 Python | 📅 2026-10-15 - An asynchronous task queue/job queue based on distributed message passing.
* [rq](https://github.com/rq/rq) ⭐ 10,694 | 🐛 262 | 🌐 Python | 📅 2026-10-14 - Simple job queues for Python.
* [huey](https://github.com/coleifer/huey) ⭐ 6,049 | 🐛 0 | 🌐 Python | 📅 2026-10-13 - A little task queue with multi-process, multi-thread, or greenlet workers.
* [dramatiq](https://github.com/Bogdanp/dramatiq) ⭐ 5,329 | 🐛 65 | 🌐 Python | 📅 2026-10-15 - A fast and reliable background task processing library for Python 3.
* [taskiq](https://github.com/taskiq-python/taskiq) ⭐ 2,356 | 🐛 123 | 🌐 Python | 📅 2026-10-12 - Distributed task queue with native asyncio support and pluggable brokers.

### Messaging

*Libraries for working with message brokers and event streaming.*

* [faststream](https://github.com/ag2ai/faststream) ⭐ 5,372 | 🐛 91 | 🌐 Python | 📅 2026-10-13 - A framework for building asynchronous services over Apache Kafka, RabbitMQ, NATS, MQTT and Redis.
* [pika](https://github.com/pika/pika) ⭐ 3,886 | 🐛 35 | 🌐 Python | 📅 2026-10-15 - Pure-Python RabbitMQ/AMQP 0-9-1 client library.
* [paho-mqtt](https://github.com/eclipse-paho/paho.mqtt.python) ⭐ 2,430 | 🐛 129 | 🌐 Python | 📅 2026-10-12 - The Eclipse Paho MQTT client for Python.
* [confluent-kafka](https://github.com/confluentinc/confluent-kafka-python) ⭐ 520 | 🐛 225 | 🌐 Python | 📅 2026-10-14 - Confluent's Python client for Apache Kafka, built on librdkafka.

### Job Schedulers

*Libraries for scheduling jobs.*

* Task Scheduling
  * [schedule](https://github.com/dbader/schedule) ⭐ 12,270 | 🐛 188 | 🌐 Python | 📅 2024-05-25 - Python job scheduling for humans.
  * [apscheduler](https://github.com/agronholm/apscheduler) ⭐ 7,656 | 🐛 64 | 🌐 Python | 📅 2026-10-12 - A light but powerful in-process task scheduler that lets you schedule functions.
* Workflow Orchestration
  * [apache-airflow](https://github.com/apache/airflow) ⭐ 47,186 | 🐛 1,891 | 🌐 Python | 📅 2026-10-15 - Airflow is a platform to programmatically author, schedule and monitor workflows.
  * [prefect](https://github.com/PrefectHQ/prefect) ⭐ 24,025 | 🐛 906 | 🌐 Python | 📅 2026-10-15 - A modern workflow orchestration framework that makes it easy to build, schedule and monitor robust data pipelines.
  * [dagster](https://github.com/dagster-io/dagster) ⭐ 16,282 | 🐛 2,589 | 🌐 Python | 📅 2026-10-12 - An orchestration platform for the development, production, and observation of data assets.
  * [temporalio](https://github.com/temporalio/sdk-python) ⭐ 1,223 | 🐛 71 | 🌐 Python | 📅 2026-10-15 - Temporal SDK for durable, fault-tolerant workflows that survive crashes and retries.

### Logging

*Libraries for generating and working with logs.*

* [loguru](https://github.com/Delgan/loguru) ⭐ 24,148 | 🐛 259 | 🌐 Python | 📅 2026-10-11 - Library which aims to bring enjoyable logging in Python.
* [structlog](https://github.com/hynek/structlog) ⭐ 4,975 | 🐛 39 | 🌐 Python | 📅 2026-10-05 - Structured logging made easy.
* [logfire](https://github.com/pydantic/logfire) ⭐ 4,512 | 🐛 216 | 🌐 Python | 📅 2026-10-15 - The observability platform for Python, from the makers of Pydantic.
* [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.

### Network Virtualization

*Tools and libraries for packet manipulation and network device automation.*

* [scapy](https://github.com/secdev/scapy) ⭐ 12,608 | 🐛 146 | 🌐 Python | 📅 2026-10-11 - A brilliant packet manipulation library.
* [netmiko](https://github.com/ktbyers/netmiko) ⭐ 4,307 | 🐛 69 | 🌐 Python | 📅 2026-10-09 - Multi-vendor library to simplify CLI connections to network devices.
* [napalm](https://github.com/napalm-automation/napalm) ⭐ 2,513 | 🐛 175 | 🌐 Python | 📅 2026-08-12 - Cross-vendor API to manipulate network devices.

**CLI & GUI**

### CLI Development

*Libraries for building command-line applications.*

* General
  * [typer](https://github.com/fastapi/typer) ⭐ 20,110 | 🐛 47 | 🌐 Python | 📅 2026-10-15 - Modern CLI framework that uses Python type hints. Built on Click.
  * [click](https://github.com/pallets/click) ⭐ 17,789 | 🐛 85 | 🌐 Python | 📅 2026-10-06 - A package for creating beautiful command line interfaces in a composable way.
  * [prompt\_toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,595 | 🐛 762 | 🌐 Python | 📅 2026-07-26 - A library for building powerful interactive command lines.
  * [cyclopts](https://github.com/BrianPugh/cyclopts) ⭐ 1,278 | 🐛 20 | 🌐 Python | 📅 2026-10-14 - Build CLIs from type-hinted functions, with docstring-based help.
  * [argparse](https://docs.python.org/3/library/argparse.html) - (Python standard library) Command-line option and argument parsing.
* Terminal Rendering
  * [rich](https://github.com/Textualize/rich) ⭐ 57,546 | 🐛 384 | 🌐 Python | 📅 2026-06-23 - Python library for rich text and beautiful formatting in the terminal. Also provides a great `RichHandler` log handler.
  * [tqdm](https://github.com/tqdm/tqdm) ⭐ 31,356 | 🐛 657 | 🌐 Python | 📅 2026-10-05 - Fast, extensible progress bar for loops and CLI.
  * [alive-progress](https://github.com/rsalmei/alive-progress) ⭐ 6,317 | 🐛 25 | 🌐 Python | 📅 2026-05-24 - A new kind of Progress Bar, with real-time throughput, eta and very cool animations.
  * [colorama](https://github.com/tartley/colorama) ⭐ 3,798 | 🐛 149 | 🌐 Python | 📅 2026-05-13 - Cross-platform colored terminal text.
* TUI Frameworks
  * [textual](https://github.com/Textualize/textual) ⭐ 37,465 | 🐛 368 | 🌐 Python | 📅 2026-10-09 - A framework for building interactive user interfaces that run in the terminal and the browser.
  * [asciimatics](https://github.com/peterbrittain/asciimatics) ⭐ 4,307 | 🐛 18 | 🌐 Python | 📅 2026-07-04 - A package to create full-screen text UIs (from interactive forms to ASCII animations).
  * [urwid](https://github.com/urwid/urwid) ⭐ 3,024 | 🐛 112 | 🌐 Python | 📅 2026-10-15 - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.

### CLI Tools

*Useful CLI-based tools.*

* Database CLIs
  * [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,418 | 🐛 48 | 🌐 Python | 📅 2026-10-15 - PostgreSQL CLI with autocompletion and syntax highlighting.
  * [mycli](https://github.com/dbcli/mycli) ⭐ 11,982 | 🐛 0 | 🌐 Python | 📅 2026-10-15 - MySQL CLI with autocompletion and syntax highlighting.
  * [litecli](https://github.com/dbcli/litecli) ⭐ 3,317 | 🐛 44 | 🌐 Python | 📅 2026-06-18 - SQLite CLI with autocompletion and syntax highlighting.
  * [iredis](https://github.com/laixintao/iredis) ⭐ 2,762 | 🐛 49 | 🌐 Python | 📅 2026-09-21 - Redis CLI with autocompletion and syntax highlighting.
* Downloaders
  * [yt-dlp](https://github.com/yt-dlp/yt-dlp) ⭐ 198,120 | 🐛 2,702 | 🌐 Python | 📅 2026-10-10 - A command-line program to download videos from YouTube and other video sites, a fork of youtube-dl.
* HTTP Clients
  * [httpie](https://github.com/httpie/cli) ⭐ 38,643 | 🐛 349 | 🌐 Python | 📅 2024-12-17 - A command line HTTP client, a user-friendly cURL replacement.
* Project Scaffolding
  * [cookiecutter](https://github.com/cookiecutter/cookiecutter) ⭐ 25,147 | 🐛 329 | 🌐 Python | 📅 2026-04-01 - A command-line utility that creates projects from cookiecutters (project templates).
  * [copier](https://github.com/copier-org/copier) ⭐ 3,637 | 🐛 149 | 🌐 Python | 📅 2026-10-13 - A library and command-line utility for rendering project templates.
* Shells
  * [xonsh](https://github.com/xonsh/xonsh) ⭐ 9,669 | 🐛 79 | 🌐 Python | 📅 2026-10-14 - A Python-powered shell. Full-featured and cross-platform.
* Terminal Workflow
  * [tmuxp](https://github.com/tmux-python/tmuxp) ⭐ 4,589 | 🐛 140 | 🌐 Python | 📅 2026-10-03 - A [tmux](https://github.com/tmux/tmux) ⭐ 49,851 | 🐛 33 | 🌐 C | 📅 2026-10-15 session manager.

### GUI Development

*Libraries for working with graphical user interface applications.*

* Desktop
  * [Kivy](https://github.com/kivy/kivy) ⭐ 19,032 | 🐛 875 | 🌐 Python | 📅 2026-10-15 - An open-source framework for cross-platform GUI apps on desktop, mobile, and embedded platforms.
  * [dearpygui](https://github.com/hoffstadt/DearPyGui) ⭐ 15,646 | 🐛 330 | 🌐 C++ | 📅 2026-05-13 - A simple GPU-accelerated Python GUI framework.
  * [toga](https://github.com/beeware/toga) ⭐ 5,420 | 🐛 307 | 🌐 Python | 📅 2026-10-14 - A Python native, OS native GUI toolkit.
  * [wxPython](https://github.com/wxWidgets/Phoenix) ⭐ 2,630 | 🐛 605 | 🌐 Python | 📅 2026-10-14 - A cross-platform GUI toolkit that wraps the wxWidgets C++ library.
  * [PyGObject](https://github.com/GNOME/pygobject) ⭐ 159 | 🐛 0 | 🌐 Python | 📅 2026-10-13 - Python Bindings for GLib/GObject/GIO/GTK.
* Qt
  * [PySide6](https://github.com/pyside/pyside-setup) ⭐ 134 | 🐛 0 | 🌐 C++ | 📅 2026-10-15 - Qt for Python offers the official Python bindings for [Qt](https://www.qt.io/), largely API-compatible with PyQt6 but with different licensing.
  * [PyQt6](https://www.riverbankcomputing.com/static/Docs/PyQt6/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
* Tkinter
  * [customtkinter](https://github.com/tomschimansky/customtkinter) ⭐ 13,589 | 🐛 318 | 🌐 Python | 📅 2026-06-24 - A modern and customizable python UI-library based on Tkinter.
  * [tkinter](https://docs.python.org/3/library/tkinter.html) - (Python standard library) The standard Python interface to the Tcl/Tk GUI toolkit.
* Web-based
  * [flet](https://github.com/flet-dev/flet) ⭐ 17,371 | 🐛 267 | 🌐 Python | 📅 2026-10-15 - Cross-platform GUI framework for building modern apps in pure Python.
  * [nicegui](https://github.com/zauberzeug/nicegui) ⭐ 16,294 | 🐛 63 | 🌐 Python | 📅 2026-10-15 - An easy-to-use, Python-based UI framework, which shows up in your web browser.
  * [pywebview](https://github.com/r0x0r/pywebview) ⭐ 6,117 | 🐛 24 | 🌐 Python | 📅 2026-10-15 - A lightweight cross-platform native wrapper around a webview component.

**Text & Documents**

### Text Processing

*Libraries for parsing and manipulating plain texts.*

* Encoding and Unicode
  * [ftfy](https://github.com/rspeer/python-ftfy) ⭐ 4,068 | 🐛 26 | 🌐 Python | 📅 2024-10-30 - Makes Unicode text less broken and more consistent automagically.
  * [chardet](https://github.com/chardet/chardet) ⭐ 2,676 | 🐛 1 | 🌐 Python | 📅 2026-10-15 - Python character encoding detector.
  * [charset-normalizer](https://github.com/jawah/charset_normalizer) ⭐ 803 | 🐛 2 | 🌐 Python | 📅 2026-10-13 - Universal character encoding detector, and a dependency of requests.
* Fuzzy Matching
  * [rapidfuzz](https://github.com/rapidfuzz/RapidFuzz) ⭐ 4,167 | 🐛 34 | 🌐 Python | 📅 2026-10-12 - Rapid fuzzy string matching using various string metrics, with a C++ core.
* General
  * [pyfiglet](https://github.com/pwaller/pyfiglet) ⭐ 1,589 | 🐛 3 | 🌐 Python | 📅 2026-08-02 - An implementation of figlet written in Python.
  * [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
* Internationalization
  * [babel](https://github.com/python-babel/babel) ⭐ 1,472 | 🐛 277 | 🌐 Python | 📅 2026-09-22 - An internationalization library for Python.
* Parser
  * [sqlparse](https://github.com/andialbrecht/sqlparse) ⭐ 4,022 | 🐛 325 | 🌐 Python | 📅 2026-08-13 - A non-validating SQL parser.
  * [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,774 | 🐛 11 | 🌐 Python | 📅 2026-10-08 - Parsing, formatting, storing and validating international phone numbers.
  * [pyparsing](https://github.com/pyparsing/pyparsing) ⭐ 2,494 | 🐛 65 | 🌐 Python | 📅 2026-09-20 - A Python library for creating PEG parsers.
  * [pygments](https://github.com/pygments/pygments) ⭐ 2,214 | 🐛 742 | 🌐 Python | 📅 2026-09-27 - A generic syntax highlighter.
  * [parsy](https://github.com/python-parsy/parsy) ⭐ 453 | 🐛 18 | 🌐 Python | 📅 2026-10-07 - Easy, generic parser combinator library for creating parsers.
* Transliteration and Slugs
  * [python-slugify](https://github.com/un33k/python-slugify) ⭐ 1,625 | 🐛 0 | 🌐 Python | 📅 2026-10-11 - A Python slugify library that translates unicode to ASCII.
  * [unidecode](https://github.com/avian2/unidecode) ⭐ 611 | 🐛 24 | 🌐 Python | 📅 2026-01-05 - ASCII transliterations of Unicode text.
* Unique identifiers
  * [shortuuid](https://github.com/skorokithakis/shortuuid) ⭐ 2,197 | 🐛 0 | 🌐 Python | 📅 2026-10-11 - A generator library for concise, unambiguous and URL-safe UUIDs.

### HTML Manipulation

*Libraries for working with HTML and XML.*

* [xmltodict](https://github.com/martinblech/xmltodict) ⭐ 5,761 | 🐛 12 | 🌐 Python | 📅 2026-08-19 - Working with XML feel like you are working with JSON.
* [lxml](https://github.com/lxml/lxml) ⭐ 3,066 | 🐛 17 | 🌐 Python | 📅 2026-10-11 - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [justhtml](https://github.com/EmilStenstrom/justhtml) ⭐ 1,159 | 🐛 1 | 🌐 Python | 📅 2026-10-12 - A pure Python HTML5 parser that sanitizes untrusted HTML by default.
* [markupsafe](https://github.com/pallets/markupsafe) ⭐ 698 | 🐛 6 | 🌐 Python | 📅 2026-10-03 - Safely adds untrusted strings to HTML/XML markup.
* [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.

### File Format Processing

*Libraries for parsing and manipulating specific file formats.*

* General
  * [tablib](https://github.com/jazzband/tablib) ⭐ 4,758 | 🐛 69 | 🌐 Python | 📅 2026-10-06 - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
  * [pyelftools](https://github.com/eliben/pyelftools) ⭐ 2,285 | 🐛 53 | 🌐 Python | 📅 2026-10-08 - Parsing and analyzing ELF files and DWARF debugging information.
* File Conversion
  * [markitdown](https://github.com/microsoft/markitdown) ⭐ 190,424 | 🐛 735 | 🌐 Python | 📅 2026-10-04 - Python tool for converting files and office documents to Markdown.
  * [docling](https://github.com/docling-project/docling) ⭐ 68,943 | 🐛 889 | 🌐 Python | 📅 2026-10-15 - Library for converting documents into structured data.
* Excel
  * [xlsxwriter](https://github.com/jmcnamara/XlsxWriter) ⭐ 3,982 | 🐛 38 | 🌐 Python | 📅 2026-08-04 - A Python module for creating Excel .xlsx files.
  * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
* Word
  * [python-docx](https://github.com/python-openxml/python-docx) ⭐ 5,742 | 🐛 539 | 🌐 Python | 📅 2026-08-01 - Creates, reads, and updates Microsoft Word (.docx) files.
* PowerPoint
  * [python-pptx](https://github.com/scanny/python-pptx) ⭐ 3,556 | 🐛 541 | 🌐 Python | 📅 2024-08-07 - Python library for creating and updating PowerPoint (.pptx) files.
* PDF
  * [pymupdf](https://github.com/pymupdf/PyMuPDF) ⭐ 10,910 | 🐛 77 | 🌐 Python | 📅 2026-10-15 - A fast library for extracting, rendering, and editing PDF and other document formats, built on MuPDF.
  * [pypdf](https://github.com/py-pdf/pypdf) ⭐ 10,259 | 🐛 136 | 🌐 Python | 📅 2026-10-14 - A library capable of splitting, merging, cropping, and transforming PDF pages.
  * [pdfminer.six](https://github.com/pdfminer/pdfminer.six) ⭐ 7,038 | 🐛 245 | 🌐 Python | 📅 2026-03-13 - A community-maintained fork of PDFMiner for extracting information from PDF documents.
  * [reportlab](https://docs.reportlab.com/) - An open-source library for generating PDFs and graphics.
* HTML-to-PDF
  * [weasyprint](https://github.com/Kozea/WeasyPrint) ⭐ 9,684 | 🐛 154 | 🌐 Python | 📅 2026-10-15 - A visual rendering engine for HTML and CSS that can export to PDF.
* Markdown
  * [markdown](https://github.com/Python-Markdown/markdown) ⭐ 4,251 | 🐛 21 | 🌐 Python | 📅 2026-10-13 - A Python implementation of John Gruber’s Markdown.
  * [mistune](https://github.com/lepture/mistune) ⭐ 3,078 | 🐛 31 | 🌐 Python | 📅 2026-10-14 - A fast yet powerful Python Markdown parser with renderers and plugins.
  * [markdown-it-py](https://github.com/executablebooks/markdown-it-py) ⭐ 1,377 | 🐛 34 | 🌐 Python | 📅 2026-10-12 - Markdown parser with 100% CommonMark support, extensions, and syntax plugins.
* Data Formats
  * [pyyaml](https://github.com/yaml/pyyaml) ⭐ 2,956 | 🐛 377 | 🌐 Python | 📅 2026-10-07 - A full-featured YAML framework for Python.
  * [tomllib](https://docs.python.org/3/library/tomllib.html) - (Python standard library) Parse TOML files.

### File Manipulation

*Libraries for file manipulation.*

* [watchdog](https://github.com/gorakhargosh/watchdog) ⭐ 7,423 | 🐛 257 | 🌐 Python | 📅 2026-10-15 - API and shell utilities to monitor file system events.
* [python-magic](https://github.com/ahupp/python-magic) ⭐ 2,924 | 🐛 26 | 🌐 Python | 📅 2026-10-14 - A Python interface to the libmagic file type identification library.
* [watchfiles](https://github.com/samuelcolvin/watchfiles) ⭐ 2,549 | 🐛 50 | 🌐 Python | 📅 2026-09-21 - Simple, modern and fast file watching and code reload in python.
* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) A cross-platform, object-oriented path library.

**Media**

### Image Processing

*Libraries for manipulating images.*

* Barcodes and QR Codes
  * [qrcode](https://github.com/lincolnloop/python-qrcode) ⭐ 4,949 | 🐛 59 | 🌐 Python | 📅 2026-03-25 - A pure Python QR Code generator.
  * [python-barcode](https://github.com/WhyNotHugo/python-barcode) ⭐ 658 | 🐛 58 | 🌐 Python | 📅 2026-10-09 - Create barcodes in Python with no extra dependencies.
* General
  * [rembg](https://github.com/danielgatis/rembg) ⭐ 25,092 | 🐛 2 | 🌐 Python | 📅 2026-10-10 - A tool to remove image backgrounds.
  * [pillow](https://github.com/python-pillow/Pillow) ⭐ 13,899 | 🐛 126 | 🌐 Python | 📅 2026-10-15 - Pillow is the friendly [PIL](https://pillow.readthedocs.io/en/stable/about.html) fork.
  * [scikit-image](https://github.com/scikit-image/scikit-image) ⭐ 6,612 | 🐛 955 | 🌐 Python | 📅 2026-10-09 - A Python library for (scientific) image processing.
  * [wand](https://github.com/emcconville/wand) ⭐ 1,481 | 🐛 29 | 🌐 Python | 📅 2026-08-06 - Python bindings for [MagickWand](https://imagemagick.org/magick-wand/), C API for ImageMagick.
  * [pyvips](https://github.com/libvips/pyvips) ⭐ 813 | 🐛 2 | 🌐 Python | 📅 2026-08-30 - A binding for libvips, a fast image processing library with low memory needs.
* Image Serving
  * [thumbor](https://github.com/thumbor/thumbor) ⭐ 10,525 | 🐛 6 | 🌐 Python | 📅 2026-10-11 - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.

### Audio & Video Processing

*Libraries for manipulating audio, video, and their metadata.*

* Audio
  * [pydub](https://github.com/jiaaro/pydub) ⭐ 9,800 | 🐛 429 | 🌐 Python | 📅 2026-03-19 - Manipulate audio with a simple and easy high level interface.
  * [librosa](https://github.com/librosa/librosa) ⭐ 8,682 | 🐛 51 | 🌐 Python | 📅 2026-10-06 - Python library for audio and music analysis.
  * [soundfile](https://github.com/bastibe/python-soundfile) ⭐ 865 | 🐛 138 | 🌐 Python | 📅 2026-10-15 - An audio library for reading and writing sound files, based on libsndfile, CFFI, and NumPy.
* Video
  * [moviepy](https://github.com/Zulko/moviepy) ⭐ 14,989 | 🐛 91 | 🌐 Python | 📅 2026-08-26 - A module for script-based movie editing with many formats, including animated GIFs.
  * [av](https://github.com/PyAV-Org/PyAV) ⭐ 3,309 | 🐛 10 | 🌐 Python | 📅 2026-10-14 - Pythonic bindings for FFmpeg's libraries.
* Metadata
  * [beets](https://github.com/beetbox/beets) ⭐ 15,795 | 🐛 693 | 🌐 Python | 📅 2026-10-15 - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
  * [mutagen](https://github.com/quodlibet/mutagen) ⭐ 1,970 | 🐛 130 | 🌐 Python | 📅 2026-08-20 - A Python module to handle audio metadata.
  * [tinytag](https://github.com/tinytag/tinytag) ⭐ 841 | 🐛 5 | 🌐 Python | 📅 2026-10-14 - A library for reading audio file metadata of MP3, MP4, WAV, OGG, FLAC, WMA, and AIFF files.

### Game Development

*Awesome game development libraries.*

* 3D Engines
  * [panda3d](https://github.com/panda3d/panda3d) ⭐ 5,252 | 🐛 375 | 🌐 C++ | 📅 2026-07-28 - 3D game engine developed jointly by Disney and contributors from around the world.
* Game Frameworks
  * [pygame](https://github.com/pygame/pygame) ⭐ 8,974 | 🐛 801 | 🌐 C | 📅 2025-11-01 - Pygame is a set of Python modules designed for writing games.
  * [pyglet](https://github.com/pyglet/pyglet) ⭐ 2,225 | 🐛 33 | 🌐 Python | 📅 2026-10-13 - A cross-platform windowing and multimedia library for Python.
  * [arcade](https://github.com/pythonarcade/arcade) ⭐ 2,092 | 🐛 40 | 🌐 Python | 📅 2026-10-09 - An easy-to-use library for creating 2D arcade games.
  * [pygame-ce](https://github.com/pygame-community/pygame-ce) ⭐ 1,692 | 🐛 445 | 🌐 C | 📅 2026-10-14 - An actively developed drop-in replacement with new features and performance improvements ([pygame](https://github.com/pygame/pygame) ⭐ 8,974 | 🐛 801 | 🌐 C | 📅 2025-11-01 fork).
* Visual Novels
  * [renpy](https://github.com/renpy/renpy) ⭐ 6,917 | 🐛 308 | 🌐 Ren'Py | 📅 2026-10-15 - A Visual Novel engine.

**Python Language**

### Implementations

*Implementations of Python.*

* [cpython](https://github.com/python/cpython) ⭐ 77,566 | 🐛 9,786 | 🌐 Python | 📅 2026-10-15 - Default, most widely used implementation of the Python programming language written in C.
* [micropython](https://github.com/micropython/micropython) ⭐ 22,130 | 🐛 1,532 | 🌐 C | 📅 2026-10-15 - A lean and efficient Python implementation for microcontrollers and constrained systems.
* [pyodide](https://github.com/pyodide/pyodide) ⭐ 14,890 | 🐛 404 | 🌐 Python | 📅 2026-10-15 - Python distribution for the browser and Node.js based on WebAssembly.
* [Cython](https://github.com/cython/cython) ⭐ 10,869 | 🐛 1,542 | 🌐 Cython | 📅 2026-10-15 - Optimizing Static Compiler for Python.
* [pypy](https://github.com/pypy/pypy) ⭐ 1,814 | 🐛 712 | 🌐 Python | 📅 2026-10-15 - A very fast and compliant implementation of the Python language.

### Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [attrs](https://github.com/python-attrs/attrs) ⭐ 5,852 | 🐛 168 | 🌐 Python | 📅 2026-10-13 - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions.
* [python-box](https://github.com/cdgriffith/Box) ⭐ 2,838 | 🐛 60 | 🌐 Python | 📅 2026-02-21 - Python dictionaries with advanced dot notation access.
* [bidict](https://github.com/jab/bidict) ⭐ 1,587 | 🐛 2 | 🌐 Python | 📅 2026-10-05 - Efficient, Pythonic bidirectional map data structures and related functionality.
* [uuid-utils](https://github.com/aminalaee/uuid-utils) ⭐ 374 | 🐛 1 | 🌐 Python | 📅 2026-10-13 - A fast, Rust-backed drop-in replacement for Python's built-in `uuid` module.

### Functional Programming

*Functional Programming with Python.*

* [toolz](https://github.com/pytoolz/toolz) ⭐ 5,159 | 🐛 143 | 🌐 Python | 📅 2026-10-07 - A collection of functional utilities for iterators, functions, and dictionaries. Also available as [cytoolz](https://github.com/pytoolz/cytoolz) ⭐ 1,115 | 🐛 33 | 🌐 Python | 📅 2026-10-08 for Cython-accelerated performance.
* [returns](https://github.com/dry-python/returns) ⭐ 4,381 | 🐛 82 | 🌐 Python | 📅 2026-10-13 - A set of type-safe monads, transformers, and composition utilities.
* [more-itertools](https://github.com/more-itertools/more-itertools) ⭐ 4,101 | 🐛 17 | 🌐 Python | 📅 2026-10-14 - More routines for operating on iterables, beyond `itertools`.
* [funcy](https://github.com/Suor/funcy) ⭐ 3,509 | 🐛 15 | 🌐 Python | 📅 2026-10-13 - A fancy and practical functional tools.
* [functools](https://docs.python.org/3/library/functools.html) - (Python standard library) Higher-order functions and operations on callable objects.

### Asynchronous Programming

*Libraries for asynchronous, concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) ⭐ 5,135 | 🐛 23 | 📅 2025-12-01.*

* Async I/O
  * [uvloop](https://github.com/MagicStack/uvloop) ⭐ 11,911 | 🐛 169 | 🌐 Cython | 📅 2026-10-06 - Ultra fast asyncio event loop.
  * [trio](https://github.com/python-trio/trio) ⭐ 7,346 | 🐛 334 | 🌐 Python | 📅 2026-10-13 - A friendly library for async concurrency and I/O.
  * [gevent](https://github.com/gevent/gevent) ⭐ 6,444 | 🐛 134 | 🌐 Python | 📅 2026-09-16 - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet) ⭐ 1,852 | 🐛 25 | 🌐 C++ | 📅 2026-10-01.
  * [Twisted](https://github.com/twisted/twisted) ⭐ 5,996 | 🐛 2,829 | 🌐 Python | 📅 2026-10-12 - An event-driven networking engine.
  * [anyio](https://github.com/agronholm/anyio) ⭐ 2,557 | 🐛 133 | 🌐 Python | 📅 2026-10-15 - A high-level async concurrency and networking framework that works on top of asyncio or trio.
  * [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    * [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) ⭐ 5,135 | 🐛 23 | 📅 2025-12-01
* Parallelism
  * [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
  * [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.

### Date and Time

*Libraries for working with dates and times.*

* [pendulum](https://github.com/python-pendulum/pendulum) ⭐ 6,677 | 🐛 275 | 🌐 Python | 📅 2026-10-12 - Python datetimes made easy.
* [dateparser](https://github.com/scrapinghub/dateparser) ⭐ 2,861 | 🐛 299 | 🌐 Python | 📅 2026-10-12 - A Python parser for human-readable dates in over 200 language locales.
* [python-dateutil](https://github.com/dateutil/dateutil) ⭐ 2,638 | 🐛 513 | 🌐 Python | 📅 2026-09-26 - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
* [whenever](https://github.com/ariebovenberg/whenever) ⭐ 2,410 | 🐛 5 | 🌐 Python | 📅 2026-10-15 - A modern datetime library, type-safe and DST-safe, in Rust or pure Python.
* [zoneinfo](https://docs.python.org/3/library/zoneinfo.html) - (Python standard library) IANA time zone support. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.

**Python Toolchain**

### Environment Management

*Libraries for Python version and virtual environment management.*

* [uv](https://github.com/astral-sh/uv) ⭐ 90,799 | 🐛 3,005 | 🌐 Rust | 📅 2026-10-15 - An extremely fast Python version, package and project manager, written in Rust.
* [pyenv](https://github.com/pyenv/pyenv) ⭐ 45,141 | 🐛 49 | 🌐 Shell | 📅 2026-10-14 - Simple Python version management.
* [virtualenv](https://github.com/pypa/virtualenv) ⭐ 5,054 | 🐛 1 | 🌐 Python | 📅 2026-10-14 - A tool to create isolated Python environments.

### Package Management

*Libraries for package and dependency management.*

* Package Managers
  * [uv](https://github.com/astral-sh/uv) ⭐ 90,799 | 🐛 3,005 | 🌐 Rust | 📅 2026-10-15 - An extremely fast Python version, package and project manager, written in Rust.
  * [poetry](https://github.com/python-poetry/poetry) ⭐ 34,307 | 🐛 595 | 🌐 Python | 📅 2026-10-12 - Python dependency management and packaging made easy.
  * [pipx](https://github.com/pypa/pipx) ⭐ 12,977 | 🐛 3 | 🌐 Python | 📅 2026-10-15 - Install and Run Python Applications in Isolated Environments. Like `npx` in Node.js.
  * [pip](https://github.com/pypa/pip) ⭐ 10,293 | 🐛 971 | 🌐 Python | 📅 2026-10-14 - The package installer for Python.
  * [conda](https://github.com/conda/conda) ⭐ 7,532 | 🐛 656 | 🌐 Python | 📅 2026-10-15 - Cross-platform, Python-agnostic binary package manager.
  * [hatch](https://github.com/pypa/hatch) ⭐ 7,244 | 🐛 450 | 🌐 Python | 📅 2026-10-13 - Modern, extensible Python project manager for environments, builds, and publishing.
* Build Backends
  * [uv-build](https://github.com/astral-sh/uv) ⭐ 90,799 | 🐛 3,005 | 🌐 Rust | 📅 2026-10-15 - uv's fast, minimal build backend for pure-Python projects.
  * [hatchling](https://github.com/pypa/hatch) ⭐ 7,244 | 🐛 450 | 🌐 Python | 📅 2026-10-13 - Modern, extensible build backend from the hatch project.
  * [setuptools](https://github.com/pypa/setuptools) ⭐ 2,867 | 🐛 706 | 🌐 Python | 📅 2026-09-10 - The historical and still most widely used pyproject build backend.
  * [poetry-core](https://github.com/python-poetry/poetry-core) ⭐ 481 | 🐛 28 | 🌐 Python | 📅 2026-10-12 - Poetry's PEP 517 build backend, usable without Poetry itself.

### Package Repositories

*Local PyPI repository servers, proxies, and mirrors.*

* [pypiserver](https://github.com/pypiserver/pypiserver) ⭐ 2,071 | 🐛 102 | 🌐 Python | 📅 2026-10-05 - A minimal PyPI server for uploading and installing packages with pip.
* [devpi](https://github.com/devpi/devpi) ⭐ 1,238 | 🐛 96 | 🌐 Python | 📅 2026-10-12 - PyPI server and packaging/testing/release tool.
* [bandersnatch](https://github.com/pypa/bandersnatch) ⭐ 554 | 🐛 20 | 🌐 Python | 📅 2026-10-14 - PyPI mirroring tool provided by Python Packaging Authority (PyPA).

### Distribution

*Libraries to create packaged executables for release distribution.*

* Executables
  * [Nuitka](https://github.com/Nuitka/Nuitka) ⭐ 15,185 | 🐛 179 | 🌐 Python | 📅 2026-10-15 - Compiles Python programs into high-performance standalone executables (cross-platform).
  * [pyinstaller](https://github.com/pyinstaller/pyinstaller) ⭐ 13,122 | 🐛 292 | 🌐 Python | 📅 2026-10-14 - Converts Python programs into stand-alone executables (cross-platform).
  * [pex](https://github.com/pex-tool/pex) ⭐ 4,230 | 🐛 57 | 🌐 Python | 📅 2026-10-09 - A tool for building self-contained Python executable environments (PEP 441 zipapps).
  * [cx-Freeze](https://github.com/marcelotduarte/cx_Freeze) ⭐ 1,563 | 🐛 44 | 🌐 Python | 📅 2026-10-15 - Converts Python scripts into standalone executables and installers for Windows, macOS, and Linux.
* Obfuscation
  * [pyarmor](https://github.com/dashingsoft/pyarmor) ⭐ 5,214 | 🐛 14 | 🌐 Python | 📅 2026-10-05 - A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.

### Configuration Files

*Libraries for storing and parsing configuration options.*

* [hydra-core](https://github.com/hydra-ecosystem/hydra) ⭐ 10,705 | 🐛 44 | 🌐 Python | 📅 2026-10-15 - Hydra is a framework for elegantly configuring complex applications.
* [python-dotenv](https://github.com/theskumar/python-dotenv) ⭐ 8,900 | 🐛 130 | 🌐 Python | 📅 2026-10-01 - Reads key-value pairs from a `.env` file and sets them as environment variables.
* [dynaconf](https://github.com/dynaconf/dynaconf) ⭐ 4,333 | 🐛 169 | 🌐 Python | 📅 2026-10-01 - Dynaconf is a configuration manager with plugins for Django and Flask.
* [pydantic-settings](https://github.com/pydantic/pydantic-settings) ⭐ 1,479 | 🐛 43 | 🌐 Python | 📅 2026-10-15 - Settings management using Pydantic models with validation, loading from environment variables and secrets files.
* [configparser](https://docs.python.org/3/library/configparser.html) - (Python standard library) INI file parser.

**Security**

### Cryptography

*Libraries for cryptographic primitives and secure protocols.*

* [paramiko](https://github.com/paramiko/paramiko) ⭐ 9,877 | 🐛 1,202 | 🌐 Python | 📅 2026-10-10 - The leading native Python SSHv2 protocol library.
* [cryptography](https://github.com/pyca/cryptography) ⭐ 7,804 | 🐛 45 | 🌐 Python | 📅 2026-10-15 - A package designed to expose cryptographic primitives and recipes to Python developers.
* [itsdangerous](https://github.com/pallets/itsdangerous) ⭐ 3,140 | 🐛 4 | 🌐 Python | 📅 2025-06-14 - Safely pass trusted data to untrusted environments and back.
* [pynacl](https://github.com/pyca/pynacl) ⭐ 1,210 | 🐛 65 | 🌐 C | 📅 2026-10-13 - Python binding to libsodium, a fork of the Networking and Cryptography (NaCl) library.

### Penetration Testing

*Frameworks and tools for penetration testing.*

* [sherlock-project](https://github.com/sherlock-project/sherlock) ⭐ 94,213 | 🐛 350 | 🌐 Python | 📅 2026-10-15 - Hunt down social media accounts by username across social networks.
* [mitmproxy](https://github.com/mitmproxy/mitmproxy) ⭐ 45,649 | 🐛 495 | 🌐 Python | 📅 2026-10-13 - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,704 | 🐛 31 | 🌐 Python | 📅 2026-10-11 - Automatic SQL injection and database takeover tool.
* [impacket](https://github.com/fortra/impacket) ⭐ 16,171 | 🐛 320 | 🌐 Python | 📅 2026-10-15 - A collection of Python classes for working with network protocols, widely used for Windows and Active Directory testing.
* [pwntools](https://github.com/Gallopsled/pwntools) ⭐ 13,768 | 🐛 126 | 🌐 Python | 📅 2026-09-03 - A CTF framework and exploit development library.

### Supply Chain Security

*Tools for auditing dependencies against known vulnerabilities.*

* [uv-audit](https://github.com/astral-sh/uv) ⭐ 90,799 | 🐛 3,005 | 🌐 Rust | 📅 2026-10-15 - (part of uv) uv's [dependency vulnerability scanning](https://docs.astral.sh/uv/reference/cli/#uv-audit) backed by OSV.
* [pip-audit](https://github.com/pypa/pip-audit) ⭐ 1,381 | 🐛 63 | 🌐 Python | 📅 2026-10-15 - Audits Python environments and dependency trees for known vulnerabilities, using the Python Packaging Advisory Database or OSV.

### Web Security

*Libraries for application-layer web security.*

* [secure](https://github.com/TypeError/secure) ⭐ 1,072 | 🐛 9 | 🌐 Python | 📅 2026-09-01 - HTTP security headers for Python web applications with ASGI and WSGI middleware.
* [nh3](https://github.com/messense/nh3) ⭐ 399 | 🐛 8 | 🌐 Rust | 📅 2026-10-14 - Python binding to the ammonia HTML sanitizer, a fast replacement for bleach.

**Other**

### Hardware

*Libraries for programming with hardware.*

* [pyserial](https://github.com/pyserial/pyserial) ⭐ 3,579 | 🐛 349 | 🌐 Python | 📅 2026-05-19 - Python serial port access library for Windows, macOS, Linux, and BSD.
* [bleak](https://github.com/hbldh/bleak) ⭐ 2,550 | 🐛 116 | 🌐 Python | 📅 2026-10-05 - A cross platform Bluetooth Low Energy Client for Python using asyncio.
* [pynput](https://github.com/moses-palmer/pynput) ⭐ 2,173 | 🐛 203 | 🌐 Python | 📅 2026-05-12 - A library to control and monitor input devices.
* [jumpstarter](https://github.com/jumpstarter-dev/jumpstarter) ⭐ 226 | 🐛 73 | 🌐 Python | 📅 2026-10-15 - A hardware-in-the-loop testing framework with a Python client library for automated testing on real and virtual hardware.

### Microsoft Windows

*Python programming on Microsoft Windows.*

* [pyenv-win](https://github.com/pyenv-win/pyenv-win) ⭐ 7,415 | 🐛 169 | 🌐 VBScript | 📅 2026-10-15 - A Python version manager for Windows ([rbenv-win](https://github.com/nak1114/rbenv-win) ⭐ 105 | 🐛 16 | 🌐 VBScript | 📅 2022-09-18 fork).
* [pywin32](https://github.com/mhammond/pywin32) ⭐ 5,623 | 🐛 391 | 🌐 C++ | 📅 2026-10-07 - Python Extensions for Windows.
* [pythonnet](https://github.com/pythonnet/pythonnet) ⭐ 5,526 | 🐛 158 | 🌐 C# | 📅 2026-10-08 - Python Integration with the .NET Common Language Runtime (CLR).
* [winpython](https://github.com/winpython/winpython) ⭐ 2,288 | 🐛 79 | 🌐 Python | 📅 2026-10-11 - Portable Python distribution for Windows.

### Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [boltons](https://github.com/mahmoud/boltons) ⭐ 6,938 | 🐛 157 | 🌐 Python | 📅 2026-09-23 - A set of pure-Python utilities.
* [blinker](https://github.com/pallets-eco/blinker) ⭐ 2,103 | 🐛 0 | 🌐 Python | 📅 2025-11-19 - A fast Python in-process signal/event dispatching system.

## Resources

Where to discover learning resources or new Python libraries.

### Newsletters

* [Awesome Python Newsletter](https://python.libhunt.com/newsletter)
* [Pycoder's Weekly](https://pycoders.com/)
* [Python Tricks](https://realpython.com/python-tricks/)
* [Python Weekly](https://www.pythonweekly.com/)

### Podcasts

* [Django Chat](https://djangochat.com/)
* [PyPodcats](https://pypodcats.live)
* [Python Bytes](https://pythonbytes.fm)
* [Talk Python To Me](https://talkpython.fm/)
* [The Real Python Podcast](https://realpython.com/podcasts/rpp/)

### Websites

* [Python Developer Tooling Handbook](https://pydevtools.com/) - Comprehensive guide to modern Python developer tools covering package management, linting, type checking, testing, and more.

## Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) first.

***

If you have any question about this opinionated list, do not hesitate to contact [@vinta](https://x.com/vinta) on X (Twitter).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-15._
