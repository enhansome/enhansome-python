# Awesome Python with stars

An opinionated guide to the best Python frameworks, libraries, and tools.

**Visit the [website](https://awesome-python.com/) to search and filter projects more easily.**

## **Sponsors**

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
  * [trailofbits-skills](https://github.com/trailofbits/skills) ⭐ 7,311 | 🐛 49 | 🌐 Python | 📅 2026-09-28 - Security skills for vulnerability detection, auditing, and testing.
  * [sentry-skills](https://github.com/getsentry/skills) ⭐ 1,029 | 🐛 26 | 🌐 Python | 📅 2026-09-29 - Agent skills the Sentry team uses for code review, pull requests, and Django reviews.
  * [django-ai-plugins](https://github.com/vintasoftware/django-ai-plugins) ⭐ 149 | 🐛 0 | 🌐 Python | 📅 2026-07-23 - Django backend agent skills for Django, DRF, Celery, and Django-specific code review.
* Orchestration
  * [langchain](https://github.com/langchain-ai/langchain) ⭐ 147,332 | 🐛 593 | 🌐 Python | 📅 2026-09-30 - A framework for building agents and LLM-powered applications.
  * [crewai](https://github.com/crewAIInc/crewAI) ⭐ 59,240 | 🐛 513 | 🌐 Python | 📅 2026-09-30 - A framework for orchestrating role-playing autonomous AI agents for collaborative task solving.
  * [langgraph](https://github.com/langchain-ai/langgraph) ⭐ 42,530 | 🐛 836 | 🌐 Python | 📅 2026-09-30 - Low-level orchestration framework for building stateful, long-running LLM agents.
  * [pydantic-ai](https://github.com/pydantic/pydantic-ai) ⭐ 20,298 | 🐛 1,387 | 🌐 Python | 📅 2026-10-01 - A Python agent framework for building generative AI applications with structured schemas.
* Vendor Agent SDKs
  * [openai-agents](https://github.com/openai/openai-agents-python) ⭐ 29,789 | 🐛 9 | 🌐 Python | 📅 2026-09-30 - OpenAI's framework for building and managing AI agents.
  * [claude-agent-sdk](https://github.com/anthropics/claude-agent-sdk-python) ⭐ 8,196 | 🐛 515 | 🌐 Python | 📅 2026-09-30 - Anthropic's Python SDK for building AI agents on Claude Code's harness — custom tools, in-process MCP servers, hooks.
* Personal Assistants
  * [hermes-agent](https://github.com/nousresearch/hermes-agent) ⭐ 250,346 | 🐛 47,637 | 🌐 Python | 📅 2026-10-01 - An adaptive personal AI assistant that grows with you.
  * [AstrBot](https://github.com/AstrBotDevs/AstrBot) ⭐ 41,261 | 🐛 1,572 | 🌐 Python | 📅 2026-09-30 - A multi-platform AI assistant that connects LLMs to chat apps like Telegram, Slack, and QQ, extensible with Python plugins.
* Prompt Optimization
  * [dspy](https://github.com/stanfordnlp/dspy) ⭐ 38,438 | 🐛 752 | 🌐 Python | 📅 2026-09-30 - A framework for programming, not prompting, language models.
* Data Layer
  * [mem0](https://github.com/mem0ai/mem0) ⭐ 66,388 | 🐛 773 | 🌐 Python | 📅 2026-09-30 - An intelligent memory layer for AI agents enabling personalized interactions.
  * [llama-index](https://github.com/run-llama/llama_index) ⭐ 52,375 | 🐛 829 | 🌐 Python | 📅 2026-09-29 - A data framework for your LLM application.
  * [openviking](https://github.com/volcengine/OpenViking) ⭐ 39,056 | 🐛 710 | 🌐 Python | 📅 2026-09-30 - A context database for AI agents that unifies memory, resources, and skills.
  * [instructor](https://github.com/567-labs/instructor) ⭐ 13,963 | 🐛 128 | 🌐 Python | 📅 2026-09-30 - A library for extracting structured data from LLMs, powered by Pydantic.
  * [semantica](https://github.com/semantica-agi/semantica) ⭐ 13,578 | 🐛 124 | 🌐 Python | 📅 2026-09-30 - A graph-native context and knowledge layer for AI agents with reasoning, provenance, and governance.
* Pre-trained Models
  * [transformers](https://github.com/huggingface/transformers) ⭐ 166,872 | 🐛 2,369 | 🌐 Python | 📅 2026-09-30 - The model-definition framework for pretrained models in text, computer vision, audio, video, and multimodal tasks, for inference and training.
* LLM Inference and Serving
  * [vllm](https://github.com/vllm-project/vllm) ⭐ 93,008 | 🐛 8,411 | 🌐 Python | 📅 2026-10-01 - A high-throughput and memory-efficient inference and serving engine for LLMs.
  * [sglang](https://github.com/sgl-project/sglang) ⭐ 36,678 | 🐛 5,465 | 🌐 Python | 📅 2026-10-01 - A high-performance serving framework for large language models and multimodal models.
  * [mlx-lm](https://github.com/ml-explore/mlx-lm) ⭐ 7,186 | 🐛 229 | 🌐 Python | 📅 2026-09-30 - Run and fine-tune large language models on Apple Silicon with MLX.
* LLM Gateways
  * [LiteLLM](https://github.com/BerriAI/litellm) ⭐ 59,946 | 🐛 5,478 | 🌐 Python | 📅 2026-10-01 - Call 100+ LLMs using OpenAI format.
* Image and Video Generation
  * [diffusers](https://github.com/huggingface/diffusers) ⭐ 34,638 | 🐛 1,462 | 🌐 Python | 📅 2026-09-30 - A library that provides pre-trained diffusion models for generating and editing images, audio, and video.
* Fine-tuning
  * [unsloth](https://github.com/unslothai/unsloth) ⭐ 77,097 | 🐛 1,152 | 🌐 Python | 📅 2026-09-30 - A library for faster LLM fine-tuning and training with reduced memory usage.
  * [peft](https://github.com/huggingface/peft) ⭐ 21,742 | 🐛 95 | 🌐 Python | 📅 2026-09-30 - A library for parameter-efficient fine-tuning of large pretrained models.
  * [axolotl](https://github.com/axolotl-ai-cloud/axolotl) ⭐ 12,512 | 🐛 248 | 🌐 Python | 📅 2026-09-30 - A framework for fine-tuning and post-training large language models.
* Speech
  * [openai-whisper](https://github.com/openai/whisper) ⭐ 109,808 | 🐛 155 | 🌐 Python | 📅 2026-08-31 - A general-purpose automatic speech recognition model trained on 680k hours of multilingual and multitask supervised data.
  * [vibevoice](https://github.com/microsoft/VibeVoice) ⭐ 54,557 | 🐛 198 | 🌐 Python | 📅 2026-09-03 - A family of open-source voice AI models from Microsoft for text-to-speech and long-form speech recognition.
  * [funasr](https://github.com/modelscope/FunASR) ⭐ 20,560 | 🐛 38 | 🌐 Python | 📅 2026-09-30 - Industrial-grade speech recognition toolkit with speaker diarization and emotion detection.
  * [kittentts](https://github.com/KittenML/KittenTTS) ⭐ 15,495 | 🐛 121 | 🌐 Python | 📅 2026-08-19 - Lightweight ONNX text-to-speech library with small CPU-friendly models.
  * [gTTS](https://github.com/pndurette/gTTS) ⭐ 2,632 | 🐛 24 | 🌐 Python | 📅 2026-04-06 - Python library and CLI tool for converting text to speech using Google Translate TTS.

### Deep Learning

*Frameworks for Neural Networks and Deep Learning. Also see [awesome-deep-learning](https://github.com/ChristosChristofidis/awesome-deep-learning) ⭐ 28,994 | 🐛 88 | 📅 2025-05-26.*

* Frameworks
  * [tensorflow](https://github.com/tensorflow/tensorflow) ⭐ 200,645 | 🐛 3,223 | 🌐 C++ | 📅 2026-10-01 - The most popular Deep Learning framework created by Google.
  * [pytorch](https://github.com/pytorch/pytorch) ⭐ 103,569 | 🐛 17,559 | 🌐 Python | 📅 2026-10-01 - Tensors and Dynamic neural networks in Python with strong GPU acceleration.
  * [keras](https://github.com/keras-team/keras) ⭐ 64,342 | 🐛 257 | 🌐 Python | 📅 2026-09-30 - A high-level deep learning library with support for JAX, TensorFlow, and PyTorch backends.
  * [jax](https://github.com/jax-ml/jax) ⭐ 36,367 | 🐛 2,613 | 🌐 Python | 📅 2026-09-30 - A library for high-performance numerical computing with automatic differentiation and JIT compilation.
  * [pytorch-lightning](https://github.com/Lightning-AI/pytorch-lightning) ⭐ 31,371 | 🐛 1,086 | 🌐 Python | 📅 2026-09-21 - Deep learning framework to train, deploy, and ship AI products Lightning fast.
* Reinforcement Learning
  * [stable-baselines3](https://github.com/DLR-RM/stable-baselines3) ⭐ 13,862 | 🐛 89 | 🌐 Python | 📅 2026-09-09 - PyTorch implementations of Stable Baselines (deep) reinforcement learning algorithms.
  * [gymnasium](https://github.com/Farama-Foundation/Gymnasium) ⭐ 12,603 | 🐛 98 | 🌐 Python | 📅 2026-09-30 - A standard API for reinforcement learning environments with popular reference environments ([gym](https://github.com/openai/gym) ⚠️ Archived successor).

### Machine Learning

*Libraries for Machine Learning. Also see [awesome-machine-learning](https://github.com/josephmisiti/awesome-machine-learning#python) ⭐ 74,505 | 🐛 22 | 🌐 Python | 📅 2026-09-30.*

* General
  * [scikit-learn](https://github.com/scikit-learn/scikit-learn) ⭐ 67,435 | 🐛 2,157 | 🌐 Python | 📅 2026-09-30 - The most popular Python library for Machine Learning with extensive documentation and community support.
  * [pgmpy](https://github.com/pgmpy/pgmpy) ⭐ 3,344 | 🐛 637 | 🌐 Python | 📅 2026-09-30 - A Python library for causal and probabilistic reasoning with graphical models.
  * [feature-engine](https://github.com/feature-engine/feature_engine) ⭐ 2,283 | 🐛 109 | 🌐 Python | 📅 2026-09-19 - sklearn compatible API with the widest toolset for feature engineering and selection.
* Gradient Boosting
  * [xgboost](https://github.com/dmlc/xgboost) ⭐ 28,809 | 🐛 446 | 🌐 C++ | 📅 2026-09-30 - A scalable, portable, and distributed gradient boosting library.
  * [lightgbm](https://github.com/lightgbm-org/LightGBM) ⭐ 18,824 | 🐛 536 | 🌐 C++ | 📅 2026-09-29 - A fast, distributed, high performance gradient boosting framework.
  * [catboost](https://github.com/catboost/catboost) ⭐ 9,128 | 🐛 736 | 🌐 C++ | 📅 2026-09-30 - A fast, scalable, high performance gradient boosting on decision trees library.
* Time Series Forecasting
  * [timesfm](https://github.com/google-research/timesfm) ⭐ 34,015 | 🐛 264 | 🌐 Python | 📅 2026-09-29 - A pretrained foundation model from Google Research for time-series forecasting, with non-commercial default weights.

### Natural Language Processing

*Libraries for working with human languages.*

* General
  * [spacy](https://github.com/explosion/spaCy) ⭐ 33,931 | 🐛 247 | 🌐 Python | 📅 2026-09-30 - A library for industrial-strength natural language processing in Python and Cython.
  * [gensim](https://github.com/piskvorky/gensim) ⭐ 16,493 | 🐛 440 | 🌐 Python | 📅 2025-11-01 - Topic Modeling for Humans.
  * [nltk](https://github.com/nltk/nltk) ⭐ 14,731 | 🐛 258 | 🌐 Python | 📅 2026-09-30 - A leading platform for building Python programs to work with human language data.
  * [stanza](https://github.com/stanfordnlp/stanza) ⭐ 7,889 | 🐛 93 | 🌐 Python | 📅 2026-09-30 - The Stanford NLP Group's official Python library, supporting 60+ languages.
* Chinese
  * [jieba](https://github.com/fxsjy/jieba) ⭐ 35,175 | 🐛 700 | 🌐 Python | 📅 2024-08-21 - The most popular Chinese text segmentation library.
  * [pypinyin](https://github.com/mozillazg/python-pinyin) ⭐ 5,367 | 🐛 45 | 🌐 Python | 📅 2026-07-20 - Convert Chinese hanzi (漢字) to pinyin (拼音).
  * [pangu.py](https://github.com/vinta/pangu.py) ⭐ 280 | 🐛 0 | 🌐 Python | 📅 2026-09-26 - Paranoid text spacing.

### Computer Vision

*Libraries for image and video analysis, object detection, and OCR.*

* General
  * [ultralytics](https://github.com/ultralytics/ultralytics) ⭐ 62,134 | 🐛 68 | 🌐 Python | 📅 2026-09-30 - Ultralytics YOLO for object detection, segmentation, pose estimation, classification, and tracking.
  * [kornia](https://github.com/kornia/kornia/) ⭐ 11,390 | 🐛 250 | 🌐 Python | 📅 2026-10-01 - Open Source Differentiable Computer Vision Library for PyTorch.
  * [fiftyone](https://github.com/voxel51/fiftyone) ⭐ 11,135 | 🐛 711 | 🌐 TypeScript | 📅 2026-09-30 - The open-source tool for building high-quality datasets and computer vision models.
  * [opencv-python](https://github.com/opencv/opencv-python) ⭐ 5,413 | 🐛 201 | 🌐 Python | 📅 2026-09-04 - Open Source Computer Vision Library.
* OCR
  * [easyocr](https://github.com/JaidedAI/EasyOCR) ⭐ 30,044 | 🐛 532 | 🌐 Python | 📅 2025-12-05 - Ready-to-use OCR with 80+ languages supported.
  * [pytesseract](https://github.com/madmaze/pytesseract) ⭐ 6,394 | 🐛 21 | 🌐 Python | 📅 2026-09-28 - A wrapper for the [Tesseract OCR](https://github.com/tesseract-ocr) engine.

### Recommender Systems

*Libraries for building recommender systems.*

* [annoy](https://github.com/spotify/annoy) ⭐ 14,309 | 🐛 88 | 🌐 C++ | 📅 2025-10-29 - Approximate Nearest Neighbors in C++/Python optimized for memory usage.
* [scikit-surprise](https://github.com/NicolasHug/Surprise) ⭐ 6,819 | 🐛 80 | 🌐 Python | 📅 2026-05-30 - A scikit for building and analyzing recommender systems.
* [implicit](https://github.com/benfred/implicit) ⭐ 3,826 | 🐛 97 | 🌐 Python | 📅 2026-05-08 - A fast Python implementation of collaborative filtering for implicit datasets.

**Web Development**

### Web Frameworks

*Traditional full stack web frameworks. Also see [Web APIs](#web-apis).*

* Synchronous
  * [django](https://github.com/django/django) ⭐ 91,239 | 🐛 525 | 🌐 Python | 📅 2026-09-30 - A high-level web framework that encourages rapid development and clean, pragmatic design.
    * [awesome-django](https://github.com/wsvincent/awesome-django) ⭐ 11,266 | 🐛 4 | 🌐 Python | 📅 2026-09-16
  * [flask](https://github.com/pallets/flask) ⭐ 74,799 | 🐛 4 | 🌐 Python | 📅 2026-09-08 - A microframework for Python.
    * [awesome-flask](https://github.com/humiaozuzu/awesome-flask) ⭐ 12,783 | 🐛 7 | 📅 2026-08-17
  * [bottle](https://github.com/bottlepy/bottle) ⭐ 8,795 | 🐛 290 | 🌐 Python | 📅 2026-09-18 - A fast and simple micro-framework distributed as a single file with no dependencies.
  * [fasthtml](https://github.com/AnswerDotAI/fasthtml) ⭐ 7,047 | 🐛 67 | 🌐 Jupyter Notebook | 📅 2026-09-21 - The fastest way to create an HTML app.
  * [pyramid](https://github.com/Pylons/pyramid) ⭐ 4,100 | 🐛 90 | 🌐 Python | 📅 2026-08-04 - A small, fast, down-to-earth, open source Python web framework.
* Asynchronous
  * [reflex](https://github.com/reflex-dev/reflex) ⭐ 28,926 | 🐛 354 | 🌐 Python | 📅 2026-10-01 - A framework for building reactive, full-stack web applications entirely with Python.
  * [tornado](https://github.com/tornadoweb/tornado) ⭐ 22,178 | 🐛 246 | 🌐 Python | 📅 2026-09-30 - A web framework and asynchronous networking library.
  * [starlette](https://github.com/Kludex/starlette) ⭐ 12,643 | 🐛 59 | 🌐 Python | 📅 2026-09-29 - A lightweight ASGI framework and toolkit for building high-performance async services.
  * [litestar](https://github.com/litestar-org/litestar) ⭐ 8,487 | 🐛 351 | 🌐 Python | 📅 2026-09-30 - Production-ready, capable and extensible ASGI Web framework.

### Web APIs

*Libraries for building RESTful, GraphQL, and RPC APIs.*

* Django
  * [django-rest-framework](https://github.com/encode/django-rest-framework) ⭐ 30,196 | 🐛 49 | 🌐 Python | 📅 2026-09-30 - A powerful and flexible toolkit to build web APIs.
  * [django-ninja](https://github.com/vitalik/django-ninja) ⭐ 9,203 | 🐛 224 | 🌐 Python | 📅 2026-09-27 - Fast, Django REST framework based on type hints and Pydantic.
  * [django-modern-rest](https://github.com/wemake-services/django-modern-rest) ⭐ 1,479 | 🐛 28 | 🌐 Python | 📅 2026-09-30 - Modern REST with speed, types, async, `msgspec`, `pydantic` and other goodies!
  * [strawberry-django](https://github.com/strawberry-graphql/strawberry-django) ⭐ 505 | 🐛 94 | 🌐 Python | 📅 2026-09-30 - Strawberry GraphQL integration with Django.
* Flask
  * [apiflask](https://github.com/apiflask/apiflask) ⭐ 1,137 | 🐛 39 | 🌐 Python | 📅 2026-09-12 - A lightweight Python web API framework based on Flask, supporting marshmallow schemas and Pydantic models.
* Framework Agnostic
  * [fastapi](https://github.com/fastapi/fastapi) ⭐ 102,731 | 🐛 83 | 🌐 Python | 📅 2026-09-30 - A modern, fast, web framework for building APIs with standard Python type hints.
  * [strawberry](https://github.com/strawberry-graphql/strawberry) ⭐ 4,722 | 🐛 313 | 🌐 Python | 📅 2026-09-30 - A GraphQL library that leverages Python type annotations for schema definition.
  * [connexion](https://github.com/spec-first/connexion) ⭐ 4,614 | 🐛 190 | 🌐 Python | 📅 2026-09-07 - A spec-first framework that automatically handles requests based on your OpenAPI specification.
* RPC
  * [grpcio](https://github.com/grpc/grpc) ⭐ 45,358 | 🐛 1,362 | 🌐 C++ | 📅 2026-10-01 - HTTP/2-based RPC framework with Python bindings, built by Google.

### Web Servers

*ASGI and WSGI compatible web servers.*

* ASGI
  * [uvicorn](https://github.com/Kludex/uvicorn) ⭐ 11,000 | 🐛 109 | 🌐 Python | 📅 2026-09-27 - A lightning-fast ASGI server implementation.
  * [granian](https://github.com/emmett-framework/granian) ⭐ 5,680 | 🐛 43 | 🌐 Rust | 📅 2026-09-30 - A Rust HTTP server for Python applications built on top of Hyper and Tokio, supporting WSGI/ASGI/RSGI.
  * [hypercorn](https://github.com/pgjones/hypercorn) ⭐ 1,614 | 🐛 155 | 🌐 Python | 📅 2025-11-08 - An ASGI and WSGI Server based on Hyper libraries and inspired by Gunicorn.
* WSGI
  * [gunicorn](https://github.com/benoitc/gunicorn) ⭐ 10,688 | 🐛 122 | 🌐 Python | 📅 2026-09-06 - Pre-forked, ported from Ruby's Unicorn project.
  * [waitress](https://github.com/Pylons/waitress) ⭐ 1,600 | 🐛 29 | 🌐 Python | 📅 2026-09-27 - Multi-threaded, powers Pyramid.

### WebSocket

*Libraries for working with WebSocket.*

* [channels](https://github.com/django/channels) ⭐ 6,361 | 🐛 123 | 🌐 Python | 📅 2026-08-06 - Brings WebSocket, long-poll HTTP, and other async support to Django.
* [websockets](https://github.com/python-websockets/websockets) ⭐ 5,721 | 🐛 3 | 🌐 Python | 📅 2026-09-24 - A library for building WebSocket servers and clients with a focus on correctness and simplicity.
* [flask-socketio](https://github.com/miguelgrinberg/Flask-SocketIO) ⭐ 5,507 | 🐛 0 | 🌐 Python | 📅 2026-08-29 - Socket.IO integration for Flask applications.
* [autobahn-python](https://github.com/crossbario/autobahn-python) ⭐ 2,540 | 🐛 199 | 🌐 Python | 📅 2026-09-29 - WebSocket & WAMP for Python on Twisted and [asyncio](https://docs.python.org/3/library/asyncio.html).

### Template Engines

*Libraries for rendering text and HTML from templates.*

* [jinja](https://github.com/pallets/jinja) ⭐ 11,795 | 🐛 105 | 🌐 Python | 📅 2025-06-14 - A modern and designer friendly templating language.
* [mako](https://github.com/sqlalchemy/mako) ⭐ 459 | 🐛 58 | 🌐 Python | 📅 2026-09-22 - Hyperfast and lightweight templating for the Python platform.

### Web Asset Management

*Tools for managing, storing, compressing and minifying website assets.*

* [django-storages](https://github.com/jschneier/django-storages) ⭐ 2,960 | 🐛 186 | 🌐 Python | 📅 2026-08-02 - A collection of custom storage back ends for Django.
* [django-compressor](https://github.com/django-compressor/django-compressor) ⭐ 2,869 | 🐛 121 | 🌐 Python | 📅 2026-09-01 - Compresses linked and inline JavaScript or CSS into a single cached file.

### Authentication

*Libraries for implementing authentication schemes.*

* OAuth
  * [django-allauth](https://github.com/pennersr/django-allauth) ⭐ 10,379 | 🐛 2 | 🌐 Python | 📅 2026-09-30 - Authentication app for Django that "just works."
  * [authlib](https://github.com/authlib/authlib) ⭐ 5,429 | 🐛 145 | 🌐 Python | 📅 2026-08-31 - A comprehensive library for building OAuth, OpenID Connect, and JWT/JWS/JWE/JWK/JWA.
  * [django-oauth-toolkit](https://github.com/django-oauth/django-oauth-toolkit) ⭐ 3,341 | 🐛 57 | 🌐 Python | 📅 2026-09-02 - An OAuth 2.0 authorization server for Django.
  * [oauthlib](https://github.com/oauthlib/oauthlib) ⭐ 2,983 | 🐛 124 | 🌐 Python | 📅 2026-09-28 - A generic and thorough implementation of the OAuth request-signing logic.
* JWT
  * [pyjwt](https://github.com/jpadilla/pyjwt) ⭐ 5,709 | 🐛 49 | 🌐 Python | 📅 2026-09-29 - JSON Web Token implementation in Python.
* Permissions
  * [django-guardian](https://github.com/django-guardian/django-guardian) ⭐ 3,917 | 🐛 34 | 🌐 Python | 📅 2026-09-18 - Implementation of per-object permissions for Django.
  * [django-rules](https://github.com/dfunckt/django-rules) ⭐ 1,975 | 🐛 41 | 🌐 Python | 📅 2025-10-11 - A tiny but powerful app providing object-level permissions to Django, without requiring a database.

### Admin Panels

*Libraries for administrative interfaces.*

* [flask-admin](https://github.com/pallets-eco/flask-admin) ⭐ 6,067 | 🐛 132 | 🌐 Python | 📅 2026-09-21 - Simple and extensible administrative interface framework for Flask.
* [django-grappelli](https://github.com/sehmaschine/django-grappelli) ⭐ 3,947 | 🐛 3 | 🌐 HTML | 📅 2026-09-17 - A jazzy skin for the Django Admin-Interface.
* [django-unfold](https://github.com/unfoldadmin/django-unfold) ⭐ 3,704 | 🐛 22 | 🌐 Python | 📅 2026-09-30 - A modern Django admin theme for building dashboards, internal tools, and business applications.

### CMS

*Content Management Systems.*

* [wagtail](https://github.com/wagtail/wagtail) ⭐ 20,511 | 🐛 1,007 | 🌐 Python | 📅 2026-09-29 - A Django content management system.
* [django-cms](https://github.com/django-cms/django-cms) ⭐ 10,675 | 🐛 8 | 🌐 Python | 📅 2026-09-30 - The easy-to-use and developer-friendly enterprise CMS powered by Django.

### ERP

*Enterprise resource planning frameworks.*

* [odoo](https://github.com/odoo/odoo) ⭐ 54,759 | 🐛 10,702 | 🌐 Python | 📅 2026-10-01 - A suite of open source business apps: CRM, e-commerce, accounting, inventory, and thousands of community modules.

### Static Site Generators

*Static site generator is a software that takes some text + templates as input and produces HTML files on the output.*

* [pelican](https://github.com/getpelican/pelican) ⭐ 13,344 | 🐛 110 | 🌐 Python | 📅 2026-04-20 - Static site generator that supports Markdown and reST syntax.
* [nikola](https://github.com/getnikola/nikola) ⭐ 2,744 | 🐛 95 | 🌐 Python | 📅 2026-09-26 - A static website and blog generator.

**HTTP & Scraping**

### HTTP Clients

*Libraries for working with HTTP.*

* Clients
  * [requests](https://github.com/psf/requests) ⭐ 54,368 | 🐛 242 | 🌐 Python | 📅 2026-09-28 - HTTP Requests for Humans.
  * [aiohttp](https://github.com/aio-libs/aiohttp) ⭐ 16,567 | 🐛 233 | 🌐 Python | 📅 2026-09-30 - Asynchronous HTTP client/server framework for asyncio and Python.
  * [httpx](https://github.com/encode/httpx) ⭐ 15,524 | 🐛 139 | 🌐 Python | 📅 2026-03-29 - A next generation HTTP client for Python.
  * [urllib3](https://github.com/urllib3/urllib3) ⭐ 4,065 | 🐛 244 | 🌐 Python | 📅 2026-09-30 - An HTTP library with thread-safe connection pooling, file post, and more.
  * [httpx2](https://github.com/pydantic/httpx2) ⭐ 1,505 | 🐛 99 | 🌐 Python | 📅 2026-09-28 - HTTP/1.1 and HTTP/2 client with sync and async APIs, maintained by Pydantic ([httpx](https://github.com/encode/httpx) ⭐ 15,524 | 🐛 139 | 🌐 Python | 📅 2026-03-29 fork).
* URL Manipulation
  * [yarl](https://github.com/aio-libs/yarl) ⭐ 1,497 | 🐛 69 | 🌐 Python | 📅 2026-09-30 - Yet another URL library.

### Web Scraping

*Libraries to automate web scraping and extract web content.*

* Frameworks
  * [browser-use](https://github.com/browser-use/browser-use) ⭐ 116,845 | 🐛 534 | 🌐 Python | 📅 2026-09-30 - Make websites accessible for AI agents with easy browser automation.
  * [crawl4ai](https://github.com/unclecode/crawl4ai) ⭐ 84,581 | 🐛 220 | 🌐 Python | 📅 2026-09-25 - An open-source, LLM-friendly web crawler that provides lightning-fast, structured data extraction specifically designed for AI agents.
  * [scrapy](https://github.com/scrapy/scrapy) ⭐ 64,537 | 🐛 319 | 🌐 Python | 📅 2026-09-30 - A fast high-level screen scraping and web crawling framework.
  * [stagehand](https://github.com/browserbase/stagehand) ⭐ 25,496 | 🐛 374 | 🌐 TypeScript | 📅 2026-09-30 - A fast and token-efficient browser automation SDK to extract data and perform self-healing actions on web pages.
  * [jev-ultrafast](https://github.com/browser-use/jev-ultrafast) ⭐ 21,575 | 🐛 173 | 🌐 Python | 📅 2026-09-30 - A fast browser agent that picks actions from an indexed table of page elements, using a small LLM only to type text.
* Content Extraction
  * [trafilatura](https://github.com/adbar/trafilatura) ⭐ 6,894 | 🐛 58 | 🌐 Python | 📅 2026-09-30 - A tool for gathering text and metadata from the web, with built-in content filtering.
  * [feedparser](https://github.com/kurtmckee/feedparser) ⭐ 2,430 | 🐛 112 | 🌐 Python | 📅 2026-09-07 - Universal feed parser.
  * [html2text](https://github.com/Alir3z4/html2text) ⭐ 2,174 | 🐛 100 | 🌐 Python | 📅 2025-10-28 - Convert HTML to Markdown-formatted text.

### Email

*Libraries for sending email.*

* [yagmail](https://github.com/kootenpv/yagmail) ⭐ 2,735 | 🐛 111 | 🌐 Python | 📅 2026-05-26 - Yet another Gmail/SMTP client.

**Database & Storage**

### ORM

*Libraries that implement Object-Relational Mapping or data mapping techniques.*

* Relational Databases
  * [django.db.models](https://github.com/django/django) ⭐ 91,239 | 🐛 525 | 🌐 Python | 📅 2026-09-30 - (part of Django) The Django [ORM](https://docs.djangoproject.com/en/stable/topics/db/models/).
  * [sqlmodel](https://github.com/fastapi/sqlmodel) ⭐ 18,353 | 🐛 55 | 🌐 Python | 📅 2026-09-23 - SQLModel is based on Python type annotations, and powered by Pydantic and SQLAlchemy.
  * [sqlalchemy](https://github.com/sqlalchemy/sqlalchemy) ⭐ 12,192 | 🐛 208 | 🌐 Python | 📅 2026-09-30 - The Python SQL Toolkit and Object Relational Mapper.
    * [awesome-sqlalchemy](https://github.com/dahlia/awesome-sqlalchemy) ⭐ 3,062 | 🐛 11 | 🌐 Python | 📅 2026-06-08
  * [peewee](https://github.com/coleifer/peewee) ⭐ 11,996 | 🐛 0 | 🌐 Python | 📅 2026-09-30 - A small, expressive ORM.
* NoSQL Databases
  * [mongoengine](https://github.com/MongoEngine/mongoengine) ⭐ 4,350 | 🐛 318 | 🌐 Python | 📅 2026-09-06 - A Python Object-Document-Mapper for working with MongoDB.
  * [beanie](https://github.com/BeanieODM/beanie) ⭐ 2,702 | 🐛 74 | 🌐 Python | 📅 2026-09-28 - An asynchronous Python object-document mapper (ODM) for MongoDB.
  * [pynamodb](https://github.com/pynamodb/PynamoDB) ⭐ 2,646 | 🐛 321 | 🌐 Python | 📅 2026-05-29 - A Pythonic interface for [Amazon DynamoDB](https://aws.amazon.com/dynamodb/).

### Database Drivers

*Libraries for connecting and operating databases.*

* PostgreSQL - [awesome-postgres](https://github.com/dhamaniasad/awesome-postgres) ⭐ 12,107 | 🐛 82 | 📅 2026-08-31
  * [asyncpg](https://github.com/MagicStack/asyncpg) ⭐ 8,096 | 🐛 273 | 🌐 Python | 📅 2026-09-30 - A fast PostgreSQL Database Client Library for Python/asyncio.
  * [psycopg](https://github.com/psycopg/psycopg) ⭐ 2,503 | 🐛 62 | 🌐 Python | 📅 2026-09-30 - The most popular PostgreSQL adapter for Python.
* MySQL - [awesome-mysql](https://github.com/shlomi-noach/awesome-mysql) ⭐ 2,614 | 🐛 19 | 🌐 Python | 📅 2026-09-22
  * [pymysql](https://github.com/PyMySQL/PyMySQL) ⭐ 7,852 | 🐛 15 | 🌐 Python | 📅 2026-09-30 - A pure-Python MySQL and MariaDB client library, based on PEP 249.
  * [mysqlclient](https://github.com/PyMySQL/mysqlclient) ⭐ 2,536 | 🐛 4 | 🌐 Python | 📅 2026-09-25 - MySQL and MariaDB connector ([MySQLdb1](https://github.com/farcepest/MySQLdb1) ⭐ 664 | 🐛 88 | 🌐 Python | 📅 2020-10-26 fork).
* SQLite - [awesome-sqlite](https://github.com/planetopendata/awesome-sqlite) ⭐ 406 | 🐛 11 | 📅 2026-08-22
  * [sqlite-utils](https://github.com/simonw/sqlite-utils) ⭐ 2,175 | 🐛 137 | 🌐 Python | 📅 2026-09-22 - Python CLI utility and library for manipulating SQLite databases.
  * [sqlite3](https://docs.python.org/3/library/sqlite3.html) - (Python standard library) SQLite interface compliant with DB-API 2.0.
* ClickHouse
  * [clickhouse-driver](https://github.com/mymarilyn/clickhouse-driver) ⭐ 1,304 | 🐛 77 | 🌐 Python | 📅 2026-07-22 - Python driver with native interface for ClickHouse.
  * [clickhouse-connect](https://github.com/ClickHouse/clickhouse-connect) ⭐ 522 | 🐛 21 | 🌐 Python | 📅 2026-09-30 - The official ClickHouse client, with SQLAlchemy and Superset connectors.
* Other Relational Databases
  * [pyodbc](https://github.com/mkleehammer/pyodbc) ⭐ 3,085 | 🐛 61 | 🌐 C++ | 📅 2026-06-06 - An ODBC bridge for connecting to SQL Server and any other ODBC-accessible database.
  * [mssql-python](https://github.com/microsoft/mssql-python) ⭐ 476 | 🐛 74 | 🌐 Python | 📅 2026-09-30 - Official Microsoft driver for SQL Server and Azure SQL, built on ODBC for high performance.
  * [oracledb](https://github.com/oracle/python-oracledb) ⭐ 454 | 🐛 28 | 🌐 Python | 📅 2026-09-22 - The official Python driver for Oracle Database, successor to cx\_Oracle.
* NoSQL Databases
  * [redis](https://github.com/redis/redis-py) ⭐ 13,649 | 🐛 88 | 🌐 Python | 📅 2026-09-30 - The Python client for Redis.
  * [pymongo](https://github.com/mongodb/mongo-python-driver) ⭐ 4,357 | 🐛 16 | 🌐 Python | 📅 2026-09-30 - The official Python client for MongoDB.
  * [cassandra-driver](https://github.com/apache/cassandra-python-driver) ⭐ 1,428 | 🐛 17 | 🌐 Python | 📅 2026-07-21 - The Python Driver for Apache Cassandra.
  * [django-mongodb-backend](https://github.com/mongodb/django-mongodb-backend) ⭐ 228 | 🐛 9 | 🌐 Python | 📅 2026-09-29 - Official MongoDB database backend for Django.

### Database

*In-process databases usable directly from Python.*

* Analytical
  * [duckdb](https://github.com/duckdb/duckdb) ⭐ 41,836 | 🐛 952 | 🌐 C++ | 📅 2026-09-30 - An in-process SQL OLAP database management system; optimized for analytics and fast queries, similar to SQLite but for analytical workloads.
  * [chdb](https://github.com/chdb-io/chdb) ⭐ 2,909 | 🐛 43 | 🌐 Python | 📅 2026-09-28 - In-process OLAP SQL engine with the full ClickHouse dialect, zero-copy pandas/Arrow interop, and federation to remote ClickHouse clusters via `remoteSecure()`.
* Vector
  * [chromadb](https://github.com/chroma-core/chroma) ⭐ 29,416 | 🐛 901 | 🌐 Rust | 📅 2026-10-01 - An open-source embedding database for building AI applications with embeddings and semantic search.
  * [zvec](https://github.com/alibaba/zvec) ⭐ 16,030 | 🐛 65 | 🌐 C++ | 📅 2026-09-29 - A lightweight, in-process vector database that embeds directly into applications.
  * [lancedb](https://github.com/lancedb/lancedb) ⭐ 11,566 | 🐛 688 | 🌐 Rust | 📅 2026-09-30 - A developer-friendly embedded retrieval database for multimodal AI.
  * [pixeltable](https://github.com/pixeltable/pixeltable) ⭐ 1,631 | 🐛 30 | 🌐 Python | 📅 2026-09-30 - Declarative multimodal AI data engine for tables, computed columns, and embedding search.
* Key-Value & Document
  * [tinydb](https://github.com/msiemens/tinydb) ⭐ 7,573 | 🐛 14 | 🌐 Python | 📅 2026-09-18 - A tiny, document-oriented database.

### Caching

*Libraries for caching data.*

* [diskcache](https://github.com/grantjenks/python-diskcache) ⭐ 2,911 | 🐛 86 | 🌐 Python | 📅 2024-08-10 - SQLite and file backed cache backend, compatible with Django.
* [cachetools](https://github.com/tkem/cachetools) ⭐ 2,781 | 🐛 5 | 🌐 Python | 📅 2026-09-30 - Extensible memoizing collections and decorators.
* [django-cacheops](https://github.com/Suor/django-cacheops) ⭐ 2,271 | 🐛 23 | 🌐 Python | 📅 2026-04-15 - A slick ORM cache with automatic granular event-driven invalidation.
* [hishel](https://github.com/karpetrosyan/hishel) ⭐ 413 | 🐛 8 | 🌐 Python | 📅 2026-09-18 - RFC 9111 compliant HTTP caching for clients like httpx and requests and servers like FastAPI, with sync and async support.
* [dogpile.cache](https://github.com/sqlalchemy/dogpile.cache) ⭐ 299 | 🐛 49 | 🌐 Python | 📅 2026-08-11 - dogpile.cache is a next generation replacement for Beaker made by the same authors.

### Search

*Libraries and software for indexing and performing search queries on data.*

* [elasticsearch](https://github.com/elastic/elasticsearch-py) ⭐ 4,389 | 🐛 66 | 🌐 Python | 📅 2026-09-28 - The official low-level Python client for [Elasticsearch](https://www.elastic.co/elasticsearch).
* [django-haystack](https://github.com/django-haystack/django-haystack) ⭐ 3,730 | 🐛 582 | 🌐 Python | 📅 2026-09-16 - Modular search for Django.
* [meilisearch](https://github.com/meilisearch/meilisearch-python) ⭐ 603 | 🐛 21 | 🌐 Python | 📅 2026-08-28 - The official Python client for the [Meilisearch](https://www.meilisearch.com/) search engine.
* [opensearch-py](https://github.com/opensearch-project/opensearch-py) ⭐ 470 | 🐛 120 | 🌐 Python | 📅 2026-09-03 - The official low-level Python client for [OpenSearch](https://opensearch.org/).

### Serialization

*Libraries for serializing complex data types.*

* [orjson](https://github.com/ijl/orjson) ⭐ 8,241 | 🐛 0 | 🌐 Python | 📅 2026-09-29 - Fast, correct JSON library.
* [marshmallow](https://github.com/marshmallow-code/marshmallow) ⭐ 7,242 | 🐛 146 | 🌐 Python | 📅 2026-09-28 - A lightweight library for converting complex objects to and from simple Python datatypes.
* [msgspec](https://github.com/msgspec/msgspec) ⭐ 4,139 | 🐛 222 | 🌐 Python | 📅 2026-09-30 - A fast serialization and validation library with built-in support for JSON, MessagePack, YAML, and TOML.
* [msgpack](https://github.com/msgpack/msgpack-python) ⭐ 2,105 | 🐛 14 | 🌐 Python | 📅 2026-09-29 - MessagePack serializer implementation for Python.

**Data & Science**

### Data Analysis

*Libraries for data analysis.*

* [pandas](https://github.com/pandas-dev/pandas) ⭐ 49,883 | 🐛 2,472 | 🌐 Python | 📅 2026-09-30 - A library providing high-performance, easy-to-use data structures and data analysis tools.
* [polars](https://github.com/pola-rs/polars) ⭐ 39,898 | 🐛 2,936 | 🌐 Rust | 📅 2026-09-30 - A fast DataFrame library implemented in Rust with a Python API.
* [ibis-framework](https://github.com/ibis-project/ibis) ⭐ 6,670 | 🐛 545 | 🌐 Python | 📅 2026-09-30 - A portable Python dataframe library with a single API for 20+ backends.

### Data Ingestion / ETL

*Libraries for data extraction, transformation, and loading pipelines across multiple sources and destinations.*

* General
  * [pathway](https://github.com/pathwaycom/pathway) ⭐ 62,206 | 🐛 38 | 🌐 Python | 📅 2026-09-30 - Python ETL framework for stream processing, real-time analytics, LLM pipelines, and RAG.
  * [dlt](https://github.com/dlt-hub/dlt) ⭐ 5,914 | 🐛 460 | 🌐 Python | 📅 2026-09-30 - A Python library for building data pipelines with automatic schema inference, incremental loading, and support for multiple sources and destinations.
  * [awswrangler](https://github.com/aws/aws-sdk-pandas) ⭐ 4,120 | 🐛 53 | 🌐 Python | 📅 2026-09-28 - Pandas integration with AWS services like Athena, Glue, Redshift, S3, and DynamoDB.
* Financial Data
  * [openbb](https://github.com/OpenBB-finance/OpenBB) ⭐ 73,699 | 🐛 85 | 🌐 Python | 📅 2026-09-30 - A financial data platform for analysts, quants and AI agents.
  * [yfinance](https://github.com/ranaroussi/yfinance) ⭐ 25,409 | 🐛 108 | 🌐 Python | 📅 2026-09-30 - Easy Pythonic way to download market and financial data from Yahoo Finance.
  * [akshare](https://github.com/akfamily/akshare) ⭐ 22,801 | 🐛 0 | 🌐 Python | 📅 2026-09-30 - A financial data interface library, with data provided for academic research only.
  * [edgartools](https://github.com/dgunning/edgartools) ⭐ 2,756 | 🐛 27 | 🌐 Python | 📅 2026-09-30 - Library for downloading structured data from SEC EDGAR filings and XBRL financial statements.

### Data Validation

*Libraries for validating data. Used for forms in many cases.*

* [pydantic](https://github.com/pydantic/pydantic) ⭐ 28,909 | 🐛 582 | 🌐 Python | 📅 2026-10-01 - Data validation using Python type hints.
* [jsonschema](https://github.com/python-jsonschema/jsonschema) ⭐ 4,988 | 🐛 53 | 🌐 Python | 📅 2026-09-29 - An implementation of [JSON Schema](https://json-schema.org/) for Python.
* [pandera](https://github.com/unionai-oss/pandera) ⭐ 4,471 | 🐛 459 | 🌐 Python | 📅 2026-09-26 - A data validation library for dataframes, with support for pandas, polars, PySpark, and more.

### Data Visualization

*Libraries for visualizing data. Also see [awesome-javascript](https://github.com/sorrycc/awesome-javascript#data-visualization) ⭐ 35,032 | 🐛 26 | 📅 2026-09-08.*

* Plotting
  * [matplotlib](https://github.com/matplotlib/matplotlib) ⭐ 23,310 | 🐛 1,493 | 🌐 Python | 📅 2026-09-30 - A comprehensive library for creating static, animated, and interactive visualizations.
  * [bokeh](https://github.com/bokeh/bokeh) ⭐ 20,460 | 🐛 848 | 🌐 TypeScript | 📅 2026-09-30 - Interactive Web Plotting for Python.
  * [plotly](https://github.com/plotly/plotly.py) ⭐ 18,817 | 🐛 724 | 🌐 Python | 📅 2026-09-25 - Interactive graphing library for Python.
  * [seaborn](https://github.com/mwaskom/seaborn) ⭐ 14,052 | 🐛 239 | 🌐 Python | 📅 2026-07-06 - Statistical data visualization using Matplotlib.
  * [altair](https://github.com/vega/altair) ⭐ 10,487 | 🐛 153 | 🌐 Python | 📅 2026-09-28 - Declarative statistical visualization library for Python.
* Specialized
  * [graphify](https://github.com/Graphify-Labs/graphify) ⭐ 122,806 | 🐛 1,495 | 🌐 Python | 📅 2026-09-30 - Turn any folder of code, SQL schemas, docs, papers, images, or videos into a queryable knowledge graph.
  * [cartopy](https://github.com/SciTools/cartopy) ⭐ 1,620 | 🐛 323 | 🌐 Python | 📅 2026-09-28 - A cartographic python library with matplotlib support.
  * [pygraphviz](https://github.com/pygraphviz/pygraphviz/) ⭐ 848 | 🐛 26 | 🌐 Python | 📅 2026-09-28 - Python interface to [Graphviz](https://www.graphviz.org/).
* Dashboards and Apps
  * [streamlit](https://github.com/streamlit/streamlit) ⭐ 45,867 | 🐛 1,178 | 🌐 Python | 📅 2026-09-30 - A framework which lets you build dashboards, generate reports, or create chat apps in minutes.
  * [gradio](https://github.com/gradio-app/gradio) ⭐ 43,646 | 🐛 99 | 🌐 Python | 📅 2026-09-30 - Build and share machine learning apps, all in Python.

### Geolocation

*Libraries for geocoding addresses and working with latitudes and longitudes.*

* [geodjango](https://github.com/django/django) ⭐ 91,239 | 🐛 525 | 🌐 Python | 📅 2026-09-30 - (part of Django) A world-class [geographic web framework](https://docs.djangoproject.com/en/stable/ref/contrib/gis/).
* [geopandas](https://github.com/geopandas/geopandas) ⭐ 5,269 | 🐛 419 | 🌐 Python | 📅 2026-09-28 - Python tools for geographic data (GeoSeries/GeoDataFrame) built on pandas.
* [geopy](https://github.com/geopy/geopy) ⭐ 4,866 | 🐛 56 | 🌐 Python | 📅 2026-07-12 - Python Geocoding Toolbox.
* [geojson](https://github.com/jazzband/geojson) ⭐ 997 | 🐛 26 | 🌐 Python | 📅 2026-06-06 - Python bindings and utilities for GeoJSON.

### Science

*Libraries for scientific computing. Also see [Python-for-Scientists](https://github.com/TomNicholas/Python-for-Scientists) ⭐ 376 | 🐛 3 | 📅 2025-06-27.*

* Core
  * [numpy](https://github.com/numpy/numpy) ⭐ 32,887 | 🐛 2,255 | 🌐 Python | 📅 2026-09-30 - A fundamental package for scientific computing with Python.
  * [scipy](https://github.com/scipy/scipy) ⭐ 15,060 | 🐛 1,854 | 🌐 Python | 📅 2026-09-30 - Fundamental algorithms for scientific computing in Python.
  * [numba](https://github.com/numba/numba) ⭐ 11,169 | 🐛 1,815 | 🌐 Python | 📅 2026-09-30 - A NumPy-aware JIT compiler for Python, using LLVM.
* Symbolic Mathematics
  * [sympy](https://github.com/sympy/sympy) ⭐ 14,981 | 🐛 6,012 | 🌐 Python | 📅 2026-10-01 - A Python library for symbolic mathematics.
* Statistics
  * [statsmodels](https://github.com/statsmodels/statsmodels) ⭐ 11,666 | 🐛 2,845 | 🌐 Python | 📅 2026-09-30 - Statistical modeling and econometrics in Python.
* Biology and Chemistry
  * [biopython](https://github.com/biopython/biopython) ⭐ 5,217 | 🐛 626 | 🌐 Python | 📅 2026-09-30 - Biopython is a set of freely available tools for biological computation.
  * [rdkit](https://github.com/rdkit/rdkit) ⭐ 3,601 | 🐛 87 | 🌐 HTML | 📅 2026-09-30 - Cheminformatics and Machine Learning Software.
* Physics and Engineering
  * [astropy](https://github.com/astropy/astropy) ⭐ 5,321 | 🐛 1,419 | 🌐 Python | 📅 2026-09-30 - A community Python library for Astronomy.
  * [pint](https://github.com/hgrecco/pint) ⭐ 2,807 | 🐛 310 | 🌐 Python | 📅 2026-09-18 - Operate and manipulate physical quantities with units and dimensional analysis.
  * [obspy](https://github.com/obspy/obspy) ⭐ 1,336 | 🐛 318 | 🌐 Python | 📅 2026-09-29 - A Python toolbox for seismology.
* Simulation and Modeling
  * [pymc](https://github.com/pymc-devs/pymc) ⭐ 9,786 | 🐛 516 | 🌐 Python | 📅 2026-09-29 - Probabilistic programming and Bayesian modeling in Python.
  * [mesa](https://github.com/mesa/mesa) ⭐ 3,868 | 🐛 110 | 🌐 Python | 📅 2026-09-30 - An agent-based modeling framework for building, analyzing, and visualizing complex system simulations.
  * [simpy](https://gitlab.com/team-simpy/simpy) - A process-based discrete-event simulation framework.
* Graphs and Networks
  * [networkx](https://github.com/networkx/networkx) ⭐ 17,300 | 🐛 307 | 🌐 Python | 📅 2026-09-29 - A high-productivity software for complex networks.
* Computational Geometry
  * [shapely](https://github.com/shapely/shapely) ⭐ 4,516 | 🐛 229 | 🌐 Python | 📅 2026-09-29 - Manipulation and analysis of geometric objects in the Cartesian plane.
* Other
  * [manim](https://github.com/ManimCommunity/manim) ⭐ 41,166 | 🐛 500 | 🌐 Python | 📅 2026-09-29 - An animation engine for explanatory math videos.
  * [colour-science](https://github.com/colour-science/colour) ⭐ 2,658 | 🐛 94 | 🌐 Python | 📅 2026-09-28 - Implementing a comprehensive number of colour theory transformations and algorithms.

### Quantum Computing

*Libraries for quantum computing.*

* [qiskit](https://github.com/Qiskit/qiskit) ⭐ 7,848 | 🐛 1,060 | 🌐 Python | 📅 2026-10-01 - An IBM-backed quantum SDK for building, simulating, and running circuits on real quantum hardware.
* [cirq](https://github.com/quantumlib/Cirq) ⭐ 5,075 | 🐛 124 | 🌐 Python | 📅 2026-09-30 - A Google-developed framework focused on hardware-aware quantum circuit design for NISQ devices.
* [pennylane](https://github.com/PennyLaneAI/pennylane) ⭐ 3,480 | 🐛 454 | 🌐 Python | 📅 2026-09-30 - A cross-platform library for quantum computing, quantum machine learning, and quantum chemistry.
* [qutip](https://github.com/qutip/qutip) ⭐ 2,078 | 🐛 119 | 🌐 Python | 📅 2026-09-29 - Quantum Toolbox in Python.

**Developer Tools**

### Algorithms and Design Patterns

*Python implementation of data structures, algorithms and design patterns. Also see [awesome-algorithms](https://github.com/tayllan/awesome-algorithms) ⭐ 25,598 | 🐛 0 | 📅 2026-09-22.*

* Algorithms
  * [thealgorithms](https://github.com/TheAlgorithms/Python) ⭐ 225,167 | 🐛 80 | 🌐 Python | 📅 2026-09-30 - All Algorithms implemented in Python.
  * [algorithms](https://github.com/keon/algorithms) ⭐ 25,558 | 🐛 14 | 🌐 Python | 📅 2026-09-25 - Minimal examples of data structures and algorithms.
  * [sortedcontainers](https://github.com/grantjenks/python-sortedcontainers) ⭐ 3,981 | 🐛 41 | 🌐 Python | 📅 2024-03-08 - Fast and pure-Python implementation of sorted collections.
* Design Patterns
  * [python-patterns](https://github.com/faif/python-patterns) ⭐ 43,020 | 🐛 12 | 🌐 Python | 📅 2026-09-24 - A collection of design patterns in Python.
  * [transitions](https://github.com/pytransitions/transitions) ⭐ 6,595 | 🐛 23 | 🌐 Python | 📅 2025-09-11 - A lightweight, object-oriented finite state machine implementation.
  * [python-statemachine](https://github.com/fgmacedo/python-statemachine) ⭐ 1,318 | 🐛 20 | 🌐 Python | 📅 2026-09-14 - Expressive statecharts and finite state machines with a declarative API, in sync and async codebases.

### Interactive Interpreter

*Interactive Python interpreters (REPL).*

* [marimo](https://github.com/marimo-team/marimo) ⭐ 22,958 | 🐛 604 | 🌐 Python | 📅 2026-09-30 - Transform data and train models, feels like a next-gen notebook, stored as Git-friendly Python.
* [ipython](https://github.com/ipython/ipython) ⭐ 16,787 | 🐛 1,301 | 🌐 Python | 📅 2026-09-14 - A powerful interactive Python shell, and the kernel behind Jupyter notebooks.
* [jupyter](https://github.com/jupyter/notebook) ⭐ 13,407 | 🐛 1,888 | 🌐 Jupyter Notebook | 📅 2026-09-28 - A web-based notebook environment for interactive computing.
  * [awesome-jupyter](https://github.com/markusschanta/awesome-jupyter) ⭐ 4,678 | 🐛 8 | 📅 2026-09-30
* [ptpython](https://github.com/prompt-toolkit/ptpython) ⭐ 5,457 | 🐛 265 | 🌐 Python | 📅 2025-11-21 - Advanced Python REPL built on top of the [python-prompt-toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,592 | 🐛 732 | 🌐 Python | 📅 2026-07-26.

### Code Analysis

*Tools of static analysis, linters and code quality checkers. Also see [awesome-static-analysis](https://github.com/analysis-tools-dev/static-analysis) ⭐ 14,815 | 🐛 1 | 🌐 Rust | 📅 2026-09-21.*

* Type Checkers - [awesome-python-typing](https://github.com/typeddjango/awesome-python-typing) ⭐ 1,987 | 🐛 6 | 📅 2026-09-23
  * [mypy](https://github.com/python/mypy) ⭐ 20,652 | 🐛 3,236 | 🌐 Python | 📅 2026-09-30 - A static type checker for Python.
  * [ty](https://github.com/astral-sh/ty) ⭐ 19,780 | 🐛 909 | 🌐 Python | 📅 2026-09-30 - An extremely fast Python type checker and language server.
  * [pyright](https://github.com/microsoft/pyright) ⭐ 15,669 | 🐛 322 | 🌐 Python | 📅 2026-09-29 - Full-featured static type checker for Python from Microsoft, the engine behind Pylance.
  * [pyrefly](https://github.com/facebook/pyrefly) ⭐ 7,035 | 🐛 693 | 🌐 Rust | 📅 2026-09-30 - A fast type checker and language server for Python.
* Code Analysis
  * [repowise](https://github.com/repowise-dev/repowise) ⭐ 7,114 | 🐛 235 | 🌐 Python | 📅 2026-09-30 - Codebase intelligence that indexes repos into dependency graphs, git history, and auto-generated docs with dead code detection.
  * [vulture](https://github.com/jendrikseipp/vulture) ⭐ 4,829 | 🐛 71 | 🌐 Python | 📅 2026-09-25 - A tool for finding and analyzing dead Python code.
  * [prospector](https://github.com/prospector-dev/prospector) ⭐ 2,083 | 🐛 32 | 🌐 Python | 📅 2026-09-28 - A tool to analyze Python code.
  * [import-linter](https://github.com/seddonym/import-linter) ⭐ 1,199 | 🐛 74 | 🌐 Python | 📅 2026-09-16 - A linter that enforces architectural constraints on imports between Python modules.
  * [complexipy](https://github.com/rohaquinlop/complexipy) ⭐ 869 | 🐛 12 | 🌐 Rust | 📅 2026-09-27 - Cognitive complexity analysis for Python code, written in Rust.
* Git Hooks
  * [pre-commit](https://github.com/pre-commit/pre-commit) ⭐ 15,603 | 🐛 25 | 🌐 Python | 📅 2026-09-29 - A framework for managing and maintaining multi-language pre-commit hooks.
* Linters and Formatters
  * [ruff](https://github.com/astral-sh/ruff) ⭐ 49,859 | 🐛 2,192 | 🌐 Rust | 📅 2026-09-30 - An extremely fast Python linter and code formatter.
  * [black](https://github.com/psf/black) ⭐ 41,857 | 🐛 300 | 🌐 Python | 📅 2026-09-30 - The uncompromising Python code formatter.
  * [bandit](https://github.com/PyCQA/bandit) ⭐ 8,289 | 🐛 259 | 🌐 Python | 📅 2026-09-21 - A tool designed to find common security issues in Python code.
  * [isort](https://github.com/PyCQA/isort) ⭐ 6,959 | 🐛 93 | 🌐 Python | 📅 2026-09-28 - A Python utility / library to sort imports.
  * [pylint](https://github.com/pylint-dev/pylint) ⭐ 5,727 | 🐛 1,025 | 🌐 Python | 📅 2026-09-30 - A fully customizable source code analyzer.
  * [flake8](https://github.com/PyCQA/flake8) ⭐ 3,826 | 🐛 23 | 🌐 Python | 📅 2026-09-29 - A wrapper around `pycodestyle`, `pyflakes` and McCabe.
    * [awesome-flake8-extensions](https://github.com/DmytroLitvinov/awesome-flake8-extensions) ⭐ 1,282 | 🐛 1 | 📅 2026-07-21
* Refactoring
  * [rope](https://github.com/python-rope/rope) ⭐ 2,238 | 🐛 155 | 🌐 Python | 📅 2026-09-28 - Rope is a python refactoring library.
* Type Annotations Generators
  * [monkeytype](https://github.com/Instagram/MonkeyType) ⭐ 5,005 | 🐛 78 | 🌐 Python | 📅 2026-02-11 - A system for Python that generates static type annotations by collecting runtime types.

### Testing

*Libraries for testing codebases and generating test data. Also see [awesome-python-testing](https://github.com/cleder/awesome-python-testing) ⭐ 312 | 🐛 3 | 📅 2026-09-29.*

* Frameworks
  * [pytest](https://github.com/pytest-dev/pytest) ⭐ 14,556 | 🐛 843 | 🌐 Python | 📅 2026-09-29 - A mature full-featured Python testing tool.
    * [awesome-pytest](https://github.com/augustogoulart/awesome-pytest) ⭐ 575 | 🐛 5 | 📅 2026-06-24
  * [robotframework](https://github.com/robotframework/robotframework) ⭐ 11,922 | 🐛 308 | 🌐 Python | 📅 2026-09-30 - A generic test automation framework.
  * [hypothesis](https://github.com/HypothesisWorks/hypothesis) ⭐ 9,032 | 🐛 53 | 🌐 Python | 📅 2026-09-28 - Hypothesis is an advanced Quickcheck style property based testing library.
* Test Runners
  * [tox](https://github.com/tox-dev/tox) ⭐ 3,942 | 🐛 3 | 🌐 Python | 📅 2026-09-29 - Auto builds and tests distributions in multiple Python versions.
  * [nox](https://github.com/wntrblm/nox) ⭐ 1,561 | 🐛 73 | 🌐 Python | 📅 2026-09-29 - Flexible test automation for Python.
* Browser Automation
  * [selenium](https://github.com/SeleniumHQ/selenium) ⭐ 34,525 | 🐛 198 | 🌐 Java | 📅 2026-09-30 - Python bindings for [Selenium](https://selenium.dev/) [WebDriver](https://selenium.dev/documentation/webdriver/).
  * [playwright-python](https://github.com/microsoft/playwright-python) ⭐ 15,021 | 🐛 20 | 🌐 Python | 📅 2026-09-24 - Python version of the Playwright testing and automation library.
  * [seleniumbase](https://github.com/seleniumbase/SeleniumBase) ⭐ 13,048 | 🐛 14 | 🌐 Python | 📅 2026-09-30 - Python framework for web automation & testing, with stealth options.
* Load Testing
  * [locust](https://github.com/locustio/locust) ⭐ 28,190 | 🐛 5 | 🌐 Python | 📅 2026-09-26 - Scalable user load testing tool written in Python.
* API Testing
  * [schemathesis](https://github.com/schemathesis/schemathesis) ⭐ 3,643 | 🐛 13 | 🌐 Python | 📅 2026-09-30 - A tool for automatic property-based testing of web APIs from OpenAPI or GraphQL schemas.
* Mock
  * [freezegun](https://github.com/spulec/freezegun) ⭐ 4,528 | 🐛 171 | 🌐 Python | 📅 2025-08-19 - Travel through time by mocking the datetime module.
  * [responses](https://github.com/getsentry/responses) ⭐ 4,343 | 🐛 44 | 🌐 Python | 📅 2026-09-24 - A utility library for mocking out the requests Python library.
  * [vcrpy](https://github.com/kevin1024/vcrpy) ⭐ 3,017 | 🐛 176 | 🌐 Python | 📅 2026-09-15 - Record and replay HTTP interactions on your tests.
  * [respx](https://github.com/lundberg/respx) ⭐ 836 | 🐛 29 | 🌐 Python | 📅 2026-07-21 - Mock HTTPX with awesome request patterns and response side effects.
  * [mock](https://docs.python.org/3/library/unittest.mock.html) - (Python standard library) A mocking and patching library.
* Object Factories
  * [factory\_boy](https://github.com/FactoryBoy/factory_boy) ⭐ 3,811 | 🐛 209 | 🌐 Python | 📅 2026-01-01 - A test fixtures replacement for Python.
  * [polyfactory](https://github.com/litestar-org/polyfactory) ⭐ 1,511 | 🐛 75 | 🌐 Python | 📅 2026-09-28 - A mock data generation library based on type hints (continuation of `pydantic-factories`).
* Code Coverage
  * [coverage](https://github.com/coveragepy/coveragepy) ⭐ 3,410 | 🐛 322 | 🌐 Python | 📅 2026-09-27 - Code coverage measurement.
* Fake Data
  * [faker](https://github.com/joke2k/faker) ⭐ 19,423 | 🐛 41 | 🌐 Python | 📅 2026-09-29 - A Python package that generates fake data.
  * [mimesis](https://github.com/lk-geimfari/mimesis) ⭐ 4,841 | 🐛 15 | 🌐 Python | 📅 2026-09-29 - A Python library for generating fake but realistic data in multiple languages and locales.

### Debugging Tools

*Libraries for debugging code.*

* pdb-like Debugger
  * [pudb](https://github.com/inducer/pudb) ⭐ 3,247 | 🐛 164 | 🌐 Python | 📅 2026-09-20 - A full-screen, console-based Python debugger.
  * [ipdb](https://github.com/gotcha/ipdb) ⭐ 1,975 | 🐛 81 | 🌐 Python | 📅 2026-02-27 - IPython-enabled [pdb](https://docs.python.org/3/library/pdb.html).
* Tracing
  * [hunter](https://github.com/ionelmc/python-hunter) ⭐ 872 | 🐛 49 | 🌐 Python | 📅 2025-08-22 - A flexible code tracing toolkit.
* Profiler
  * [py-spy](https://github.com/benfred/py-spy) ⭐ 15,525 | 🐛 244 | 🌐 Rust | 📅 2026-08-14 - A sampling profiler for Python programs. Written in Rust.
  * [memray](https://github.com/bloomberg/memray) ⭐ 15,243 | 🐛 45 | 🌐 Python | 📅 2026-09-28 - A memory profiler that tracks allocations in Python code, native extensions, and the interpreter itself.
  * [scalene](https://github.com/plasma-umass/scalene) ⭐ 13,521 | 🐛 155 | 🌐 Python | 📅 2026-09-27 - A high-performance, high-precision CPU, GPU, and memory profiler for Python.
  * [pyinstrument](https://github.com/joerick/pyinstrument) ⭐ 8,014 | 🐛 31 | 🌐 Python | 📅 2026-09-01 - A statistical wall-clock profiler with low overhead and readable call-tree output.
* Others
  * [icecream](https://github.com/gruns/icecream) ⭐ 10,113 | 🐛 72 | 🌐 Python | 📅 2026-08-21 - Inspect variables, expressions, and program execution with a single, simple function call.
  * [django-debug-toolbar](https://github.com/django-commons/django-debug-toolbar) ⭐ 8,380 | 🐛 86 | 🌐 Python | 📅 2026-09-28 - Display various debug information for Django.
  * [flask-debugtoolbar](https://github.com/pallets-eco/flask-debugtoolbar) ⭐ 978 | 🐛 39 | 🌐 JavaScript | 📅 2026-09-29 - A port of the django-debug-toolbar to flask.

### Build Tools

*Task runners and software build tools. If you're looking for Python packaging/build tools, see [Package Management](#package-management).*

* [invoke](https://github.com/pyinvoke/invoke) ⭐ 4,780 | 🐛 467 | 🌐 Python | 📅 2026-04-07 - A tool for managing shell-oriented subprocesses and organizing executable Python code into CLI-invokable tasks.
* [scons](https://github.com/SCons/scons) ⭐ 2,427 | 🐛 659 | 🌐 Python | 📅 2026-09-23 - A software construction tool.
* [doit](https://github.com/pydoit/doit) ⭐ 2,087 | 🐛 99 | 🌐 Python | 📅 2026-09-21 - A task runner and build tool.

### Documentation

*Libraries for generating project documentation.*

* [diagrams](https://github.com/mingrammer/diagrams) ⭐ 42,656 | 🐛 395 | 🌐 Python | 📅 2026-09-22 - Diagram as Code.
* [mkdocs-material](https://github.com/squidfunk/mkdocs-material) ⭐ 27,524 | 🐛 1 | 🌐 Python | 📅 2026-09-15 - A documentation framework and Material Design theme built on MkDocs.
* [sphinx](https://github.com/sphinx-doc/sphinx/) ⭐ 8,045 | 🐛 1,464 | 🌐 Python | 📅 2026-09-21 - Python Documentation generator.
  * [awesome-sphinxdoc](https://github.com/ygzgxyz/awesome-sphinxdoc) ⭐ 978 | 🐛 8 | 🌐 HTML | 📅 2025-10-07
* [zensical](https://github.com/zensical/zensical) ⭐ 5,806 | 🐛 1 | 🌐 Rust | 📅 2026-09-30 - A modern static site generator for technical documentation.
* [pdoc](https://github.com/mitmproxy/pdoc) ⭐ 2,513 | 🐛 74 | 🌐 Python | 📅 2026-07-01 - Auto-generates API documentation for Python projects.

**DevOps**

### DevOps Tools

*Software and libraries for DevOps.*

* Cloud Providers
  * [awscli](https://github.com/aws/aws-cli) ⭐ 17,282 | 🐛 748 | 🌐 Python | 📅 2026-09-30 - Universal Command Line Interface for Amazon Web Services.
  * [boto3](https://github.com/boto/boto3) ⭐ 9,911 | 🐛 200 | 🌐 Python | 📅 2026-09-30 - Python interface to Amazon Web Services.
  * [azure-sdk-for-python](https://github.com/Azure/azure-sdk-for-python) ⭐ 5,612 | 🐛 1,110 | 🌐 Python | 📅 2026-10-01 - Microsoft Azure SDK for Python, published as per-service packages.
  * [google-cloud-python](https://github.com/googleapis/google-cloud-python) ⭐ 5,391 | 🐛 582 | 🌐 Python | 📅 2026-10-01 - Google Cloud client libraries for Python, published as per-service packages.
* Configuration Management
  * [ansible](https://github.com/ansible/ansible) ⭐ 70,820 | 🐛 863 | 🌐 Python | 📅 2026-09-30 - A radically simple IT automation platform.
  * [salt](https://github.com/saltstack/salt) ⭐ 15,686 | 🐛 1,896 | 🌐 Python | 📅 2026-09-30 - Infrastructure automation and management system.
  * [pyinfra](https://github.com/pyinfra-dev/pyinfra) ⭐ 6,020 | 🐛 163 | 🌐 Python | 📅 2026-09-22 - Turns Python code into shell commands and runs them on your servers.
  * [cloud-init](https://github.com/canonical/cloud-init) ⭐ 3,826 | 🐛 614 | 🌐 Python | 📅 2026-09-29 - A multi-distribution package that handles early initialization of a cloud instance.
* Deployment
  * [fabric](https://github.com/fabric/fabric) ⭐ 15,510 | 🐛 509 | 🌐 Python | 📅 2026-04-10 - A simple, Pythonic tool for remote execution and deployment.
  * [chalice](https://github.com/aws/chalice) ⭐ 11,054 | 🐛 501 | 🌐 Python | 📅 2026-09-11 - A Python serverless microframework for AWS.
* Monitoring and Processes
  * [psutil](https://github.com/giampaolo/psutil) ⭐ 11,286 | 🐛 267 | 🌐 Python | 📅 2026-09-14 - A cross-platform process and system utilities module.
  * [supervisor](https://github.com/Supervisor/supervisor) ⭐ 9,124 | 🐛 183 | 🌐 Python | 📅 2025-12-21 - Supervisor process control system for UNIX.
  * [sh](https://github.com/amoffat/sh) ⭐ 7,245 | 🐛 2 | 🌐 Python | 📅 2026-07-25 - A full-fledged subprocess replacement for Python.
  * [flower](https://github.com/mher/flower) ⭐ 7,242 | 🐛 37 | 🌐 Python | 📅 2026-09-22 - A real-time monitor and web admin for Celery task queues.
  * [sentry-sdk](https://github.com/getsentry/sentry-python) ⭐ 2,208 | 🐛 389 | 🌐 Python | 📅 2026-09-30 - Sentry SDK for Python.
* Other
  * [borgbackup](https://github.com/borgbackup/borg) ⭐ 13,793 | 🐛 209 | 🌐 Python | 📅 2026-09-29 - A deduplicating archiver with compression and encryption.
  * [chaostoolkit](https://github.com/chaostoolkit/chaostoolkit) ⭐ 2,031 | 🐛 3 | 🌐 Python | 📅 2026-09-28 - A Chaos Engineering toolkit & Orchestration for Developers.

### Distributed Computing

*Frameworks and libraries for Distributed Computing.*

* [pyspark](https://github.com/apache/spark) ⭐ 44,093 | 🐛 597 | 🌐 Scala | 📅 2026-09-30 - [Apache Spark](https://spark.apache.org/) Python API.
* [ray](https://github.com/ray-project/ray/) ⭐ 43,955 | 🐛 3,543 | 🌐 Python | 📅 2026-10-01 - A unified framework for scaling AI and Python applications.
* [dask](https://github.com/dask/dask) ⭐ 13,927 | 🐛 1,345 | 🌐 Python | 📅 2026-09-29 - A flexible parallel computing library for analytic computing.
* [joblib](https://github.com/joblib/joblib) ⭐ 4,399 | 🐛 433 | 🌐 Python | 📅 2026-09-30 - Parallel computing and disk-based caching for Python functions.
* [mpi4py](https://github.com/mpi4py/mpi4py) ⭐ 926 | 🐛 5 | 🌐 Python | 📅 2026-09-29 - Python bindings for MPI.

### Task Queues

*Libraries for working with task queues.*

* [celery](https://github.com/celery/celery) ⭐ 28,928 | 🐛 722 | 🌐 Python | 📅 2026-09-30 - An asynchronous task queue/job queue based on distributed message passing.
* [rq](https://github.com/rq/rq) ⭐ 10,696 | 🐛 258 | 🌐 Python | 📅 2026-09-30 - Simple job queues for Python.
* [huey](https://github.com/coleifer/huey) ⭐ 6,041 | 🐛 0 | 🌐 Python | 📅 2026-09-15 - A little task queue with multi-process, multi-thread, or greenlet workers.
* [dramatiq](https://github.com/Bogdanp/dramatiq) ⭐ 5,318 | 🐛 66 | 🌐 Python | 📅 2026-09-14 - A fast and reliable background task processing library for Python 3.
* [taskiq](https://github.com/taskiq-python/taskiq) ⭐ 2,345 | 🐛 118 | 🌐 Python | 📅 2026-09-26 - Distributed task queue with native asyncio support and pluggable brokers.

### Messaging

*Libraries for working with message brokers and event streaming.*

* [faststream](https://github.com/ag2ai/faststream) ⭐ 5,357 | 🐛 94 | 🌐 Python | 📅 2026-09-30 - A framework for building asynchronous services over Apache Kafka, RabbitMQ, NATS, MQTT and Redis.
* [pika](https://github.com/pika/pika) ⭐ 3,888 | 🐛 27 | 🌐 Python | 📅 2026-09-22 - Pure-Python RabbitMQ/AMQP 0-9-1 client library.
* [paho-mqtt](https://github.com/eclipse-paho/paho.mqtt.python) ⭐ 2,425 | 🐛 129 | 🌐 Python | 📅 2026-09-21 - The Eclipse Paho MQTT client for Python.
* [confluent-kafka](https://github.com/confluentinc/confluent-kafka-python) ⭐ 515 | 🐛 217 | 🌐 Python | 📅 2026-09-30 - Confluent's Python client for Apache Kafka, built on librdkafka.

### Job Schedulers

*Libraries for scheduling jobs.*

* Task Scheduling
  * [schedule](https://github.com/dbader/schedule) ⭐ 12,275 | 🐛 182 | 🌐 Python | 📅 2024-05-25 - Python job scheduling for humans.
  * [apscheduler](https://github.com/agronholm/apscheduler) ⭐ 7,643 | 🐛 59 | 🌐 Python | 📅 2026-09-26 - A light but powerful in-process task scheduler that lets you schedule functions.
* Workflow Orchestration
  * [apache-airflow](https://github.com/apache/airflow) ⭐ 47,014 | 🐛 1,958 | 🌐 Python | 📅 2026-09-30 - Airflow is a platform to programmatically author, schedule and monitor workflows.
  * [prefect](https://github.com/PrefectHQ/prefect) ⭐ 23,958 | 🐛 860 | 🌐 Python | 📅 2026-09-30 - A modern workflow orchestration framework that makes it easy to build, schedule and monitor robust data pipelines.
  * [dagster](https://github.com/dagster-io/dagster) ⭐ 16,225 | 🐛 2,577 | 🌐 Python | 📅 2026-09-30 - An orchestration platform for the development, production, and observation of data assets.

### Logging

*Libraries for generating and working with logs.*

* [loguru](https://github.com/Delgan/loguru) ⭐ 24,138 | 🐛 259 | 🌐 Python | 📅 2026-09-28 - Library which aims to bring enjoyable logging in Python.
* [structlog](https://github.com/hynek/structlog) ⭐ 4,968 | 🐛 39 | 🌐 Python | 📅 2026-09-05 - Structured logging made easy.
* [logfire](https://github.com/pydantic/logfire) ⭐ 4,498 | 🐛 215 | 🌐 Python | 📅 2026-09-30 - The observability platform for Python, from the makers of Pydantic.
* [logging](https://docs.python.org/3/library/logging.html) - (Python standard library) Logging facility for Python.

### Network Virtualization

*Tools and libraries for Virtual Networking and SDN (Software Defined Networking).*

* [scapy](https://github.com/secdev/scapy) ⭐ 12,577 | 🐛 140 | 🌐 Python | 📅 2026-09-30 - A brilliant packet manipulation library.
* [napalm](https://github.com/napalm-automation/napalm) ⭐ 2,507 | 🐛 175 | 🌐 Python | 📅 2026-08-12 - Cross-vendor API to manipulate network devices.

**CLI & GUI**

### CLI Development

*Libraries for building command-line applications.*

* CLI Development
  * [fire](https://github.com/google/python-fire) ⭐ 28,226 | 🐛 198 | 🌐 Python | 📅 2026-07-01 - A library for creating command line interfaces from absolutely any Python object.
  * [typer](https://github.com/fastapi/typer) ⭐ 20,045 | 🐛 48 | 🌐 Python | 📅 2026-09-19 - Modern CLI framework that uses Python type hints. Built on Click.
  * [click](https://github.com/pallets/click/) ⭐ 17,780 | 🐛 86 | 🌐 Python | 📅 2026-09-23 - A package for creating beautiful command line interfaces in a composable way.
  * [prompt\_toolkit](https://github.com/prompt-toolkit/python-prompt-toolkit) ⭐ 10,592 | 🐛 732 | 🌐 Python | 📅 2026-07-26 - A library for building powerful interactive command lines.
  * [argparse](https://docs.python.org/3/library/argparse.html) - (Python standard library) Command-line option and argument parsing.
* Terminal Rendering
  * [rich](https://github.com/Textualize/rich) ⭐ 57,457 | 🐛 380 | 🌐 Python | 📅 2026-06-23 - Python library for rich text and beautiful formatting in the terminal. Also provides a great `RichHandler` log handler.
  * [tqdm](https://github.com/tqdm/tqdm) ⭐ 31,351 | 🐛 636 | 🌐 Python | 📅 2026-09-20 - Fast, extensible progress bar for loops and CLI.
  * [alive-progress](https://github.com/rsalmei/alive-progress) ⭐ 6,311 | 🐛 22 | 🌐 Python | 📅 2026-05-24 - A new kind of Progress Bar, with real-time throughput, eta and very cool animations.
  * [colorama](https://github.com/tartley/colorama) ⭐ 3,795 | 🐛 144 | 🌐 Python | 📅 2026-05-13 - Cross-platform colored terminal text.
* TUI Frameworks
  * [textual](https://github.com/Textualize/textual) ⭐ 37,374 | 🐛 360 | 🌐 Python | 📅 2026-07-11 - A framework for building interactive user interfaces that run in the terminal and the browser.
  * [asciimatics](https://github.com/peterbrittain/asciimatics) ⭐ 4,303 | 🐛 17 | 🌐 Python | 📅 2026-07-04 - A package to create full-screen text UIs (from interactive forms to ASCII animations).
  * [urwid](https://github.com/urwid/urwid) ⭐ 3,020 | 🐛 113 | 🌐 Python | 📅 2026-09-30 - A library for creating terminal GUI applications with strong support for widgets, events, rich colors, etc.

### CLI Tools

*Useful CLI-based tools.*

* Database CLIs
  * [pgcli](https://github.com/dbcli/pgcli) ⭐ 13,410 | 🐛 49 | 🌐 Python | 📅 2026-09-20 - PostgreSQL CLI with autocompletion and syntax highlighting.
  * [mycli](https://github.com/dbcli/mycli) ⭐ 11,979 | 🐛 0 | 🌐 Python | 📅 2026-09-30 - MySQL CLI with autocompletion and syntax highlighting.
  * [litecli](https://github.com/dbcli/litecli) ⭐ 3,309 | 🐛 43 | 🌐 Python | 📅 2026-06-18 - SQLite CLI with autocompletion and syntax highlighting.
  * [iredis](https://github.com/laixintao/iredis) ⭐ 2,760 | 🐛 49 | 🌐 Python | 📅 2026-09-21 - Redis CLI with autocompletion and syntax highlighting.
* Downloaders
  * [yt-dlp](https://github.com/yt-dlp/yt-dlp) ⭐ 194,588 | 🐛 2,671 | 🌐 Python | 📅 2026-09-27 - A command-line program to download videos from YouTube and other video sites, a fork of youtube-dl.
* HTTP Clients
  * [httpie](https://github.com/httpie/cli) ⭐ 38,601 | 🐛 342 | 🌐 Python | 📅 2024-12-17 - A command line HTTP client, a user-friendly cURL replacement.
* Project Scaffolding
  * [cookiecutter](https://github.com/cookiecutter/cookiecutter) ⭐ 25,121 | 🐛 319 | 🌐 Python | 📅 2026-04-01 - A command-line utility that creates projects from cookiecutters (project templates).
  * [copier](https://github.com/copier-org/copier) ⭐ 3,605 | 🐛 140 | 🌐 Python | 📅 2026-09-30 - A library and command-line utility for rendering project templates.
* Shells
  * [xonsh](https://github.com/xonsh/xonsh/) ⭐ 9,657 | 🐛 75 | 🌐 Python | 📅 2026-09-29 - A Python-powered shell. Full-featured and cross-platform.
* Terminal Workflow
  * [tmuxp](https://github.com/tmux-python/tmuxp) ⭐ 4,588 | 🐛 138 | 🌐 Python | 📅 2026-09-28 - A [tmux](https://github.com/tmux/tmux) ⭐ 49,596 | 🐛 42 | 🌐 C | 📅 2026-09-30 session manager.

### GUI Development

*Libraries for working with graphical user interface applications.*

* Desktop
  * [kivy](https://github.com/kivy/kivy) ⭐ 19,030 | 🐛 848 | 🌐 Python | 📅 2026-09-24 - An open-source framework for cross-platform GUI apps on desktop, mobile, and embedded platforms.
  * [dearpygui](https://github.com/hoffstadt/DearPyGui) ⭐ 15,639 | 🐛 328 | 🌐 C++ | 📅 2026-05-13 - A simple GPU-accelerated Python GUI framework.
  * [toga](https://github.com/beeware/toga) ⭐ 5,415 | 🐛 313 | 🌐 Python | 📅 2026-09-29 - A Python native, OS native GUI toolkit.
  * [wxPython](https://github.com/wxWidgets/Phoenix) ⭐ 2,627 | 🐛 611 | 🌐 Python | 📅 2026-09-30 - A cross-platform GUI toolkit that wraps the wxWidgets C++ library.
  * [pygobject](https://github.com/GNOME/pygobject) ⭐ 159 | 🐛 0 | 🌐 Python | 📅 2026-09-28 - Python Bindings for GLib/GObject/GIO/GTK.
* Qt
  * [PySide6](https://github.com/pyside/pyside-setup) ⭐ 134 | 🐛 0 | 🌐 C++ | 📅 2026-09-30 - Qt for Python offers the official Python bindings for [Qt](https://www.qt.io/), largely API-compatible with PyQt6 but with different licensing.
  * [PyQt6](https://www.riverbankcomputing.com/static/Docs/PyQt6/) - Python bindings for the [Qt](https://www.qt.io/) cross-platform application and UI framework.
* Tkinter
  * [customtkinter](https://github.com/tomschimansky/customtkinter) ⭐ 13,580 | 🐛 317 | 🌐 Python | 📅 2026-06-24 - A modern and customizable python UI-library based on Tkinter.
  * [tkdesigner](https://github.com/ParthJadhav/Tkinter-Designer) ⭐ 10,265 | 🐛 5 | 🌐 Python | 📅 2026-09-05 - Generates Tkinter interfaces from Figma designs using the Figma API.
  * [tkinter](https://docs.python.org/3/library/tkinter.html) - (Python standard library) The standard Python interface to the Tcl/Tk GUI toolkit.
* Web-based
  * [flet](https://github.com/flet-dev/flet) ⭐ 17,205 | 🐛 313 | 🌐 Python | 📅 2026-09-30 - Cross-platform GUI framework for building modern apps in pure Python.
  * [nicegui](https://github.com/zauberzeug/nicegui) ⭐ 16,257 | 🐛 66 | 🌐 Python | 📅 2026-09-29 - An easy-to-use, Python-based UI framework, which shows up in your web browser.
  * [pywebview](https://github.com/r0x0r/pywebview/) ⭐ 6,072 | 🐛 17 | 🌐 Python | 📅 2026-09-28 - A lightweight cross-platform native wrapper around a webview component.
* Wrappers
  * [gooey](https://github.com/chriskiehl/Gooey) ⭐ 21,911 | 🐛 180 | 🌐 Python | 📅 2026-09-12 - Turn command line programs into a full GUI application with one line.

**Text & Documents**

### Text Processing

*Libraries for parsing and manipulating plain texts.*

* Encoding and Unicode
  * [ftfy](https://github.com/rspeer/python-ftfy) ⭐ 4,067 | 🐛 26 | 🌐 Python | 📅 2024-10-30 - Makes Unicode text less broken and more consistent automagically.
  * [chardet](https://github.com/chardet/chardet) ⭐ 2,674 | 🐛 0 | 🌐 Python | 📅 2026-08-30 - Python character encoding detector.
  * [charset-normalizer](https://github.com/jawah/charset_normalizer) ⭐ 797 | 🐛 0 | 🌐 Python | 📅 2026-09-29 - Universal character encoding detector, and a dependency of requests.
* Fuzzy Matching
  * [rapidfuzz](https://github.com/rapidfuzz/RapidFuzz) ⭐ 4,149 | 🐛 33 | 🌐 Python | 📅 2026-09-28 - Rapid fuzzy string matching using various string metrics, with a C++ core.
* General
  * [pyfiglet](https://github.com/pwaller/pyfiglet) ⭐ 1,585 | 🐛 2 | 🌐 Python | 📅 2026-08-02 - An implementation of figlet written in Python.
  * [difflib](https://docs.python.org/3/library/difflib.html) - (Python standard library) Helpers for computing deltas.
* Internationalization
  * [babel](https://github.com/python-babel/babel) ⭐ 1,468 | 🐛 247 | 🌐 Python | 📅 2026-09-22 - An internationalization library for Python.
* Parser
  * [sqlparse](https://github.com/andialbrecht/sqlparse) ⭐ 4,021 | 🐛 304 | 🌐 Python | 📅 2026-08-13 - A non-validating SQL parser.
  * [phonenumbers](https://github.com/daviddrysdale/python-phonenumbers) ⭐ 3,774 | 🐛 11 | 🌐 Python | 📅 2026-09-24 - Parsing, formatting, storing and validating international phone numbers.
  * [pyparsing](https://github.com/pyparsing/pyparsing) ⭐ 2,493 | 🐛 47 | 🌐 Python | 📅 2026-09-20 - A Python library for creating PEG parsers.
  * [pygments](https://github.com/pygments/pygments) ⭐ 2,211 | 🐛 678 | 🌐 Python | 📅 2026-09-27 - A generic syntax highlighter.
  * [parsy](https://github.com/python-parsy/parsy) ⭐ 452 | 🐛 18 | 🌐 Python | 📅 2026-06-22 - Easy, generic parser combinator library for creating parsers.
* Transliteration and Slugs
  * [python-slugify](https://github.com/un33k/python-slugify) ⭐ 1,625 | 🐛 0 | 🌐 Python | 📅 2026-09-27 - A Python slugify library that translates unicode to ASCII.
  * [unidecode](https://github.com/avian2/unidecode) ⭐ 611 | 🐛 24 | 🌐 Python | 📅 2026-01-05 - ASCII transliterations of Unicode text.
* Unique identifiers
  * [shortuuid](https://github.com/skorokithakis/shortuuid) ⭐ 2,198 | 🐛 0 | 🌐 Python | 📅 2026-06-20 - A generator library for concise, unambiguous and URL-safe UUIDs.
  * [sqids](https://github.com/sqids/sqids-python) ⭐ 524 | 🐛 1 | 🌐 Python | 📅 2025-10-01 - A library for generating short unique IDs from numbers.

### HTML Manipulation

*Libraries for working with HTML and XML.*

* [xmltodict](https://github.com/martinblech/xmltodict) ⭐ 5,756 | 🐛 7 | 🌐 Python | 📅 2026-08-19 - Working with XML feel like you are working with JSON.
* [lxml](https://github.com/lxml/lxml) ⭐ 3,063 | 🐛 13 | 🌐 Python | 📅 2026-09-26 - A very fast, easy-to-use and versatile library for handling HTML and XML.
* [justhtml](https://github.com/EmilStenstrom/justhtml/) ⭐ 1,157 | 🐛 0 | 🌐 Python | 📅 2026-09-30 - A pure Python HTML5 parser that sanitizes untrusted HTML by default.
* [markupsafe](https://github.com/pallets/markupsafe) ⭐ 697 | 🐛 16 | 🌐 Python | 📅 2025-09-27 - Safely adds untrusted strings to HTML/XML markup.
* [beautifulsoup4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - Providing Pythonic idioms for iterating, searching, and modifying HTML or XML.

### File Format Processing

*Libraries for parsing and manipulating specific file formats.*

* General
  * [tablib](https://github.com/jazzband/tablib) ⭐ 4,757 | 🐛 60 | 🌐 Python | 📅 2026-09-11 - A module for Tabular Datasets in XLS, CSV, JSON, YAML.
  * [pyelftools](https://github.com/eliben/pyelftools) ⭐ 2,281 | 🐛 56 | 🌐 Python | 📅 2026-09-29 - Parsing and analyzing ELF files and DWARF debugging information.
* File Conversion
  * [markitdown](https://github.com/microsoft/markitdown) ⭐ 187,780 | 🐛 634 | 🌐 Python | 📅 2026-09-30 - Python tool for converting files and office documents to Markdown.
  * [docling](https://github.com/docling-project/docling) ⭐ 68,236 | 🐛 951 | 🌐 Python | 📅 2026-09-30 - Library for converting documents into structured data.
* Excel
  * [xlsxwriter](https://github.com/jmcnamara/XlsxWriter) ⭐ 3,977 | 🐛 32 | 🌐 Python | 📅 2026-08-04 - A Python module for creating Excel .xlsx files.
  * [openpyxl](https://openpyxl.readthedocs.io/en/stable/) - A library for reading and writing Excel 2010 xlsx/xlsm/xltx/xltm files.
* Word
  * [python-docx](https://github.com/python-openxml/python-docx) ⭐ 5,731 | 🐛 533 | 🌐 Python | 📅 2026-08-01 - Creates, reads, and updates Microsoft Word (.docx) files.
* PowerPoint
  * [python-pptx](https://github.com/scanny/python-pptx) ⭐ 3,548 | 🐛 540 | 🌐 Python | 📅 2024-08-07 - Python library for creating and updating PowerPoint (.pptx) files.
* PDF
  * [pypdf](https://github.com/py-pdf/pypdf) ⭐ 10,241 | 🐛 137 | 🌐 Python | 📅 2026-09-30 - A library capable of splitting, merging, cropping, and transforming PDF pages.
  * [pdfminer.six](https://github.com/pdfminer/pdfminer.six) ⭐ 7,032 | 🐛 234 | 🌐 Python | 📅 2026-03-13 - A community-maintained fork of PDFMiner for extracting information from PDF documents.
  * [reportlab](https://www.reportlab.com/opensource/) - Allowing Rapid creation of rich PDF documents.
* HTML-to-PDF
  * [weasyprint](https://github.com/Kozea/WeasyPrint) ⭐ 9,651 | 🐛 149 | 🌐 Python | 📅 2026-09-30 - A visual rendering engine for HTML and CSS that can export to PDF.
* Markdown
  * [markdown](https://github.com/Python-Markdown/markdown) ⭐ 4,254 | 🐛 22 | 🌐 Python | 📅 2026-09-30 - A Python implementation of John Gruber’s Markdown.
  * [mistune](https://github.com/lepture/mistune) ⭐ 3,075 | 🐛 31 | 🌐 Python | 📅 2026-08-21 - A fast yet powerful Python Markdown parser with renderers and plugins.
  * [markdown-it-py](https://github.com/executablebooks/markdown-it-py) ⭐ 1,369 | 🐛 28 | 🌐 Python | 📅 2026-09-28 - Markdown parser with 100% CommonMark support, extensions, and syntax plugins.
* Data Formats
  * [pyyaml](https://github.com/yaml/pyyaml) ⭐ 2,950 | 🐛 369 | 🌐 Python | 📅 2026-06-17 - A full-featured YAML framework for Python.
  * [tomllib](https://docs.python.org/3/library/tomllib.html) - (Python standard library) Parse TOML files.

### File Manipulation

*Libraries for file manipulation.*

* [watchdog](https://github.com/gorakhargosh/watchdog) ⭐ 7,417 | 🐛 266 | 🌐 Python | 📅 2026-09-22 - API and shell utilities to monitor file system events.
* [python-magic](https://github.com/ahupp/python-magic) ⭐ 2,919 | 🐛 26 | 🌐 Python | 📅 2026-09-22 - A Python interface to the libmagic file type identification library.
* [watchfiles](https://github.com/samuelcolvin/watchfiles) ⭐ 2,542 | 🐛 48 | 🌐 Python | 📅 2026-09-21 - Simple, modern and fast file watching and code reload in python.
* [mimetypes](https://docs.python.org/3/library/mimetypes.html) - (Python standard library) Map filenames to MIME types.
* [pathlib](https://docs.python.org/3/library/pathlib.html) - (Python standard library) A cross-platform, object-oriented path library.

**Media**

### Image Processing

*Libraries for manipulating images.*

* Barcodes and QR Codes
  * [qrcode](https://github.com/lincolnloop/python-qrcode) ⭐ 4,947 | 🐛 58 | 🌐 Python | 📅 2026-03-25 - A pure Python QR Code generator.
  * [python-barcode](https://github.com/WhyNotHugo/python-barcode) ⭐ 656 | 🐛 58 | 🌐 Python | 📅 2026-07-27 - Create barcodes in Python with no extra dependencies.
* General
  * [rembg](https://github.com/danielgatis/rembg) ⭐ 24,934 | 🐛 1 | 🌐 Python | 📅 2026-09-20 - A tool to remove image backgrounds.
  * [pillow](https://github.com/python-pillow/Pillow) ⭐ 13,863 | 🐛 146 | 🌐 Python | 📅 2026-09-30 - Pillow is the friendly [PIL](https://pillow.readthedocs.io/en/stable/about.html) fork.
  * [scikit-image](https://github.com/scikit-image/scikit-image) ⭐ 6,600 | 🐛 952 | 🌐 Python | 📅 2026-09-24 - A Python library for (scientific) image processing.
  * [wand](https://github.com/emcconville/wand) ⭐ 1,479 | 🐛 29 | 🌐 Python | 📅 2026-08-06 - Python bindings for [MagickWand](https://imagemagick.org/magick-wand/), C API for ImageMagick.
  * [pyvips](https://github.com/libvips/pyvips) ⭐ 812 | 🐛 2 | 🌐 Python | 📅 2026-08-30 - A binding for libvips, a fast image processing library with low memory needs.
* Image Serving
  * [thumbor](https://github.com/thumbor/thumbor) ⭐ 10,520 | 🐛 28 | 🌐 Python | 📅 2026-10-01 - A smart imaging service. It enables on-demand crop, re-sizing and flipping of images.

### Audio & Video Processing

*Libraries for manipulating audio, video, and their metadata.*

* Audio
  * [pydub](https://github.com/jiaaro/pydub) ⭐ 9,802 | 🐛 423 | 🌐 Python | 📅 2026-03-19 - Manipulate audio with a simple and easy high level interface.
  * [librosa](https://github.com/librosa/librosa) ⭐ 8,639 | 🐛 51 | 🌐 Python | 📅 2026-09-29 - Python library for audio and music analysis.
* Video
  * [moviepy](https://github.com/Zulko/moviepy) ⭐ 14,937 | 🐛 87 | 🌐 Python | 📅 2026-08-26 - A module for script-based movie editing with many formats, including animated GIFs.
  * [vidgear](https://github.com/abhiTronix/vidgear) ⭐ 3,725 | 🐛 1 | 🌐 Python | 📅 2026-05-18 - A high-performance, cross-platform, multi-threaded video processing framework.
* Metadata
  * [beets](https://github.com/beetbox/beets) ⭐ 15,730 | 🐛 704 | 🌐 Python | 📅 2026-09-30 - A music library manager and [MusicBrainz](https://musicbrainz.org/) tagger.
  * [mutagen](https://github.com/quodlibet/mutagen) ⭐ 1,964 | 🐛 125 | 🌐 Python | 📅 2026-08-20 - A Python module to handle audio metadata.
  * [tinytag](https://github.com/tinytag/tinytag) ⭐ 843 | 🐛 5 | 🌐 Python | 📅 2026-09-15 - A library for reading audio file metadata of MP3, MP4, WAV, OGG, FLAC, WMA, and AIFF files.

### Game Development

*Awesome game development libraries.*

* 3D Engines
  * [panda3d](https://github.com/panda3d/panda3d) ⭐ 5,233 | 🐛 371 | 🌐 C++ | 📅 2026-07-28 - 3D game engine developed jointly by Disney and contributors from around the world.
* Game Frameworks
  * [pygame](https://github.com/pygame/pygame) ⭐ 8,951 | 🐛 797 | 🌐 C | 📅 2025-11-01 - Pygame is a set of Python modules designed for writing games.
  * [pyglet](https://github.com/pyglet/pyglet) ⭐ 2,217 | 🐛 34 | 🌐 Python | 📅 2026-09-28 - A cross-platform windowing and multimedia library for Python.
  * [arcade](https://github.com/pythonarcade/arcade) ⭐ 2,084 | 🐛 102 | 🌐 Python | 📅 2026-09-30 - Arcade is a modern Python framework for crafting games with compelling graphics and sound.
  * [pygame-ce](https://github.com/pygame-community/pygame-ce) ⭐ 1,670 | 🐛 442 | 🌐 C | 📅 2026-09-26 - An actively developed drop-in replacement with new features and performance improvements ([pygame](https://github.com/pygame/pygame) ⭐ 8,951 | 🐛 797 | 🌐 C | 📅 2025-11-01 fork).
* Visual Novels
  * [renpy](https://github.com/renpy/renpy) ⭐ 6,876 | 🐛 304 | 🌐 Ren'Py | 📅 2026-09-30 - A Visual Novel engine.

**Python Language**

### Implementations

*Implementations of Python.*

* [cpython](https://github.com/python/cpython) ⭐ 77,372 | 🐛 9,749 | 🌐 Python | 📅 2026-09-30 - Default, most widely used implementation of the Python programming language written in C.
* [micropython](https://github.com/micropython/micropython) ⭐ 22,104 | 🐛 1,525 | 🌐 C | 📅 2026-09-30 - A lean and efficient Python implementation for microcontrollers and constrained systems.
* [pyodide](https://github.com/pyodide/pyodide) ⭐ 14,869 | 🐛 396 | 🌐 Python | 📅 2026-09-23 - Python distribution for the browser and Node.js based on WebAssembly.
* [Cython](https://github.com/cython/cython) ⭐ 10,853 | 🐛 1,532 | 🌐 Cython | 📅 2026-09-27 - Optimizing Static Compiler for Python.
* [pypy](https://github.com/pypy/pypy) ⭐ 1,804 | 🐛 715 | 🌐 Python | 📅 2026-09-30 - A very fast and compliant implementation of the Python language.

### Built-in Classes Enhancement

*Libraries for enhancing Python built-in classes.*

* [attrs](https://github.com/python-attrs/attrs) ⭐ 5,850 | 🐛 164 | 🌐 Python | 📅 2026-09-01 - Replacement for `__init__`, `__eq__`, `__repr__`, etc. boilerplate in class definitions.
* [python-box](https://github.com/cdgriffith/Box) ⭐ 2,834 | 🐛 53 | 🌐 Python | 📅 2026-02-21 - Python dictionaries with advanced dot notation access.
* [bidict](https://github.com/jab/bidict) ⭐ 1,587 | 🐛 3 | 🌐 Python | 📅 2026-09-28 - Efficient, Pythonic bidirectional map data structures and related functionality.
* [uuid-utils](https://github.com/aminalaee/uuid-utils) ⭐ 374 | 🐛 1 | 🌐 Python | 📅 2026-09-08 - A fast, Rust-backed drop-in replacement for Python's built-in `uuid` module, supporting RFC 9562 (UUIDv6, UUIDv7, and UUIDv8).

### Functional Programming

*Functional Programming with Python.*

* [toolz](https://github.com/pytoolz/toolz) ⭐ 5,156 | 🐛 135 | 🌐 Python | 📅 2026-09-18 - A collection of functional utilities for iterators, functions, and dictionaries. Also available as [cytoolz](https://github.com/pytoolz/cytoolz/) ⭐ 1,113 | 🐛 34 | 🌐 Python | 📅 2026-09-18 for Cython-accelerated performance.
* [returns](https://github.com/dry-python/returns) ⭐ 4,368 | 🐛 81 | 🌐 Python | 📅 2026-09-30 - A set of type-safe monads, transformers, and composition utilities.
* [more-itertools](https://github.com/more-itertools/more-itertools) ⭐ 4,096 | 🐛 8 | 🌐 Python | 📅 2026-09-29 - More routines for operating on iterables, beyond `itertools`.
* [funcy](https://github.com/Suor/funcy) ⭐ 3,509 | 🐛 7 | 🌐 Python | 📅 2026-09-27 - A fancy and practical functional tools.
* [functools](https://docs.python.org/3/library/functools.html) - (Python standard library) Higher-order functions and operations on callable objects.

### Asynchronous Programming

*Libraries for asynchronous, concurrent and parallel execution. Also see [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) ⭐ 5,134 | 🐛 20 | 📅 2025-12-01.*

* Async I/O
  * [uvloop](https://github.com/MagicStack/uvloop) ⭐ 11,910 | 🐛 163 | 🌐 Cython | 📅 2026-09-30 - Ultra fast asyncio event loop.
  * [trio](https://github.com/python-trio/trio) ⭐ 7,342 | 🐛 330 | 🌐 Python | 📅 2026-09-30 - A friendly library for async concurrency and I/O.
  * [gevent](https://github.com/gevent/gevent) ⭐ 6,449 | 🐛 132 | 🌐 Python | 📅 2026-09-16 - A coroutine-based Python networking library that uses [greenlet](https://github.com/python-greenlet/greenlet) ⭐ 1,852 | 🐛 22 | 🌐 C++ | 📅 2026-09-14.
  * [Twisted](https://github.com/twisted/twisted) ⭐ 5,992 | 🐛 2,832 | 🌐 Python | 📅 2026-09-28 - An event-driven networking engine.
  * [anyio](https://github.com/agronholm/anyio) ⭐ 2,550 | 🐛 130 | 🌐 Python | 📅 2026-09-29 - A high-level async concurrency and networking framework that works on top of asyncio or trio.
  * [asyncio](https://docs.python.org/3/library/asyncio.html) - (Python standard library) Asynchronous I/O, event loop, coroutines and tasks.
    * [awesome-asyncio](https://github.com/timofurrer/awesome-asyncio) ⭐ 5,134 | 🐛 20 | 📅 2025-12-01
* Parallelism
  * [concurrent.futures](https://docs.python.org/3/library/concurrent.futures.html) - (Python standard library) A high-level interface for asynchronously executing callables.
  * [multiprocessing](https://docs.python.org/3/library/multiprocessing.html) - (Python standard library) Process-based parallelism.

### Date and Time

*Libraries for working with dates and times.*

* [pendulum](https://github.com/python-pendulum/pendulum) ⭐ 6,676 | 🐛 257 | 🌐 Python | 📅 2026-09-29 - Python datetimes made easy.
* [dateparser](https://github.com/scrapinghub/dateparser) ⭐ 2,861 | 🐛 287 | 🌐 Python | 📅 2026-09-30 - A Python parser for human-readable dates in over 200 language locales.
* [python-dateutil](https://github.com/dateutil/dateutil) ⭐ 2,637 | 🐛 498 | 🌐 Python | 📅 2026-09-26 - Extensions to the standard Python [datetime](https://docs.python.org/3/library/datetime.html) module.
* [whenever](https://github.com/ariebovenberg/whenever) ⭐ 2,404 | 🐛 10 | 🌐 Python | 📅 2026-09-30 - A modern datetime library, type-safe and DST-safe, in Rust or pure Python.
* [zoneinfo](https://docs.python.org/3/library/zoneinfo.html) - (Python standard library) IANA time zone support. Brings the [tz database](https://en.wikipedia.org/wiki/Tz_database) into Python.

**Python Toolchain**

### Environment Management

*Libraries for Python version and virtual environment management.*

* [uv](https://github.com/astral-sh/uv) ⭐ 90,321 | 🐛 2,941 | 🌐 Rust | 📅 2026-10-01 - An extremely fast Python version, package and project manager, written in Rust.
* [pyenv](https://github.com/pyenv/pyenv) ⭐ 45,119 | 🐛 54 | 🌐 Shell | 📅 2026-09-30 - Simple Python version management.
* [virtualenv](https://github.com/pypa/virtualenv) ⭐ 5,050 | 🐛 0 | 🌐 Python | 📅 2026-09-30 - A tool to create isolated Python environments.

### Package Management

*Libraries for package and dependency management.*

* Package Managers
  * [uv](https://github.com/astral-sh/uv) ⭐ 90,321 | 🐛 2,941 | 🌐 Rust | 📅 2026-10-01 - An extremely fast Python version, package and project manager, written in Rust.
  * [poetry](https://github.com/python-poetry/poetry) ⭐ 34,306 | 🐛 581 | 🌐 Python | 📅 2026-09-28 - Python dependency management and packaging made easy.
  * [pipx](https://github.com/pypa/pipx) ⭐ 12,976 | 🐛 0 | 🌐 Python | 📅 2026-09-29 - Install and Run Python Applications in Isolated Environments. Like `npx` in Node.js.
  * [pip](https://github.com/pypa/pip) ⭐ 10,290 | 🐛 954 | 🌐 Python | 📅 2026-09-23 - The package installer for Python.
  * [conda](https://github.com/conda/conda/) ⭐ 7,522 | 🐛 653 | 🌐 Python | 📅 2026-09-30 - Cross-platform, Python-agnostic binary package manager.
  * [hatch](https://github.com/pypa/hatch) ⭐ 7,242 | 🐛 445 | 🌐 Python | 📅 2026-09-20 - Modern, extensible Python project manager for environments, builds, and publishing.
* Build Backends
  * [uv-build](https://github.com/astral-sh/uv) ⭐ 90,321 | 🐛 2,941 | 🌐 Rust | 📅 2026-10-01 - uv's fast, minimal build backend for pure-Python projects.
  * [hatchling](https://github.com/pypa/hatch) ⭐ 7,242 | 🐛 445 | 🌐 Python | 📅 2026-09-20 - Modern, extensible build backend from the hatch project.
  * [setuptools](https://github.com/pypa/setuptools) ⭐ 2,865 | 🐛 701 | 🌐 Python | 📅 2026-09-10 - The historical and still most widely used pyproject build backend.

### Package Repositories

*Local PyPI repository servers, proxies, and mirrors.*

* [warehouse](https://github.com/pypi/warehouse) ⭐ 4,162 | 🐛 578 | 🌐 Python | 📅 2026-09-30 - The software that powers PyPI.
* [devpi](https://github.com/devpi/devpi) ⭐ 1,228 | 🐛 97 | 🌐 Python | 📅 2026-09-28 - PyPI server and packaging/testing/release tool.
* [bandersnatch](https://github.com/pypa/bandersnatch/) ⭐ 552 | 🐛 30 | 🌐 Python | 📅 2026-09-28 - PyPI mirroring tool provided by Python Packaging Authority (PyPA).

### Distribution

*Libraries to create packaged executables for release distribution.*

* Executables
  * [Nuitka](https://github.com/Nuitka/Nuitka) ⭐ 15,175 | 🐛 226 | 🌐 Python | 📅 2026-09-30 - Compiles Python programs into high-performance standalone executables (cross-platform).
  * [pyinstaller](https://github.com/pyinstaller/pyinstaller) ⭐ 13,116 | 🐛 289 | 🌐 Python | 📅 2026-09-28 - Converts Python programs into stand-alone executables (cross-platform).
  * [shiv](https://github.com/linkedin/shiv) ⭐ 1,947 | 🐛 65 | 🌐 Python | 📅 2026-05-22 - A command line utility for building fully self-contained zipapps (PEP 441), but with all their dependencies included.
  * [cx-Freeze](https://github.com/marcelotduarte/cx_Freeze) ⭐ 1,561 | 🐛 43 | 🌐 Python | 📅 2026-09-29 - Converts Python scripts into standalone executables and installers for Windows, macOS, and Linux.
* Obfuscation
  * [pyarmor](https://github.com/dashingsoft/pyarmor) ⭐ 5,204 | 🐛 15 | 🌐 Python | 📅 2026-09-19 - A tool used to obfuscate python scripts, bind obfuscated scripts to fixed machine or expire obfuscated scripts.

### Configuration Files

*Libraries for storing and parsing configuration options.*

* [hydra-core](https://github.com/facebookresearch/hydra) ⭐ 10,681 | 🐛 66 | 🌐 Python | 📅 2026-09-30 - Hydra is a framework for elegantly configuring complex applications.
* [python-dotenv](https://github.com/theskumar/python-dotenv) ⭐ 8,886 | 🐛 122 | 🌐 Python | 📅 2026-09-30 - Reads key-value pairs from a `.env` file and sets them as environment variables.
* [dynaconf](https://github.com/dynaconf/dynaconf) ⭐ 4,333 | 🐛 170 | 🌐 Python | 📅 2026-09-01 - Dynaconf is a configuration manager with plugins for Django and Flask.
* [pydantic-settings](https://github.com/pydantic/pydantic-settings) ⭐ 1,467 | 🐛 41 | 🌐 Python | 📅 2026-09-28 - Settings management using Pydantic models with validation, loading from environment variables and secrets files.
* [configparser](https://docs.python.org/3/library/configparser.html) - (Python standard library) INI file parser.

**Security**

### Cryptography

*Libraries for cryptographic primitives and secure protocols.*

* [paramiko](https://github.com/paramiko/paramiko) ⭐ 9,870 | 🐛 1,199 | 🌐 Python | 📅 2026-08-29 - The leading native Python SSHv2 protocol library.
* [cryptography](https://github.com/pyca/cryptography) ⭐ 7,792 | 🐛 34 | 🌐 Python | 📅 2026-09-30 - A package designed to expose cryptographic primitives and recipes to Python developers.
* [itsdangerous](https://github.com/pallets/itsdangerous) ⭐ 3,137 | 🐛 5 | 🌐 Python | 📅 2025-06-14 - Safely pass trusted data to untrusted environments and back.
* [pynacl](https://github.com/pyca/pynacl) ⭐ 1,206 | 🐛 63 | 🌐 C | 📅 2026-09-28 - Python binding to libsodium, a fork of the Networking and Cryptography (NaCl) library.

### Penetration Testing

*Frameworks and tools for penetration testing.*

* [sherlock-project](https://github.com/sherlock-project/sherlock) ⭐ 93,081 | 🐛 355 | 🌐 Python | 📅 2026-09-30 - Hunt down social media accounts by username across social networks.
* [mitmproxy](https://github.com/mitmproxy/mitmproxy) ⭐ 45,208 | 🐛 498 | 🌐 Python | 📅 2026-09-30 - An interactive TLS-capable intercepting HTTP proxy for penetration testers and software developers.
* [sqlmap](https://github.com/sqlmapproject/sqlmap) ⭐ 38,563 | 🐛 32 | 🌐 Python | 📅 2026-09-28 - Automatic SQL injection and database takeover tool.
* [social-engineer-toolkit](https://github.com/trustedsec/social-engineer-toolkit) ⭐ 15,346 | 🐛 14 | 🌐 Python | 📅 2026-06-04 - A toolkit for social engineering.

### Supply Chain Security

*Tools for auditing dependencies against known vulnerabilities.*

* [uv-audit](https://github.com/astral-sh/uv) ⭐ 90,321 | 🐛 2,941 | 🌐 Rust | 📅 2026-10-01 - (part of uv) uv's [dependency vulnerability scanning](https://docs.astral.sh/uv/reference/cli/#uv-audit) backed by OSV.
* [pip-audit](https://github.com/pypa/pip-audit) ⭐ 1,375 | 🐛 61 | 🌐 Python | 📅 2026-09-26 - Audits Python environments and dependency trees for known vulnerabilities, using the Python Packaging Advisory Database or OSV.

### Web Security

*Libraries for application-layer web security.*

* [secure](https://github.com/TypeError/secure) ⭐ 1,072 | 🐛 9 | 🌐 Python | 📅 2026-09-01 - HTTP security headers for Python web applications with ASGI and WSGI middleware.

**Other**

### Hardware

*Libraries for programming with hardware.*

* [bleak](https://github.com/hbldh/bleak) ⭐ 2,531 | 🐛 117 | 🌐 Python | 📅 2026-09-30 - A cross platform Bluetooth Low Energy Client for Python using asyncio.
* [pynput](https://github.com/moses-palmer/pynput) ⭐ 2,171 | 🐛 203 | 🌐 Python | 📅 2026-05-12 - A library to control and monitor input devices.
* [jumpstarter](https://github.com/jumpstarter-dev/jumpstarter) ⭐ 223 | 🐛 108 | 🌐 Python | 📅 2026-09-30 - A hardware-in-the-loop testing framework with a Python client library for automated testing on real and virtual hardware.

### Microsoft Windows

*Python programming on Microsoft Windows.*

* [pyenv-win](https://github.com/pyenv-win/pyenv-win) ⭐ 7,406 | 🐛 169 | 🌐 VBScript | 📅 2026-09-25 - A Python version manager for Windows ([rbenv-win](https://github.com/nak1114/rbenv-win) ⭐ 105 | 🐛 16 | 🌐 VBScript | 📅 2022-09-18 fork).
* [pywin32](https://github.com/mhammond/pywin32) ⭐ 5,614 | 🐛 397 | 🌐 C++ | 📅 2026-09-08 - Python Extensions for Windows.
* [pythonnet](https://github.com/pythonnet/pythonnet) ⭐ 5,516 | 🐛 158 | 🌐 C# | 📅 2026-09-29 - Python Integration with the .NET Common Language Runtime (CLR).
* [winpython](https://github.com/winpython/winpython) ⭐ 2,285 | 🐛 78 | 🌐 Python | 📅 2026-09-27 - Portable Python distribution for Windows.

### Miscellaneous

*Useful libraries or tools that don't fit in the categories above.*

* [boltons](https://github.com/mahmoud/boltons) ⭐ 6,931 | 🐛 99 | 🌐 Python | 📅 2026-09-23 - A set of pure-Python utilities.
* [blinker](https://github.com/pallets-eco/blinker) ⭐ 2,094 | 🐛 0 | 🌐 Python | 📅 2025-11-19 - A fast Python in-process signal/event dispatching system.

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

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/vinta/awesome-python/blob/master/CONTRIBUTING.md) ⭐ 324,348 | 🐛 20 | 🌐 Python | 📅 2026-09-29 first.

***

If you have any question about this opinionated list, do not hesitate to contact [@vinta](https://x.com/vinta) on X (Twitter).

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-10-01._
