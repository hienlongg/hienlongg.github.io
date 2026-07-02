---
title: 'Trương Hiển Long - AI/ML & Full-Stack Portfolio'
lastUpdated: '2026-06-25'
---

# Trương Hiển Long

## AI/ML & Full-Stack Engineering

I am an IT student at Ho Chi Minh University of Science focused on AI/ML and full-stack engineering, with hands-on experience building agentic AI workflows, vector search systems, computer vision pipelines, real-time backends, and browser-based ML tools.

My strongest interests are building practical AI systems that connect model capabilities with reliable software architecture: orchestration, retrieval, streaming interfaces, evaluation loops, and developer-facing tools.

I care about turning complex AI concepts into usable products through clear system design, strong engineering fundamentals, and pragmatic implementation.


<!-- [Get PDF version](#){ .md-button .md-button--primary } -->

<!-- PDF Export Button -->
<!-- <div style="text-align: right; margin-bottom: 2rem;"> -->
<div>
  <!-- <button id="pdf-export-btn" class="md-button md-button--primary pdf-export-btn" onclick="window.print()"> -->
  <button id="pdf-export-btn" class="md-button md-button--primary" onclick="exportToPDF()">
  <!-- <button id="pdf-export-btn" class="md-button md-button--primary"> -->
    <span class="icon">📄</span>
    <span>Export PDF</span>
  </button>
</div>

---

## 📞 Contact Information

- **Phone:** [+84.944.679.025 (VN)](https://zalo.me/0944679025)
- **Email:** [hienlong106@gmail.com](mailto:hienlong106@gmail.com)
- **Facebook:** [https://www.facebook.com/truonghienlongg](https://www.facebook.com/truonghienlongg)
- **LinkedIn:** [https://www.linkedin.com/in/long-truong-0b0597243/](https://www.linkedin.com/in/long-truong-0b0597243/)

---

## 🛠️ Technical Skills

<table>
  <thead>
    <tr>
      <th><strong>Category</strong></th>
      <th><strong>Skills & Technologies</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Languages</strong></td>
      <td>Python, C++, JavaScript, TypeScript</td>
    </tr>
    <tr>
      <td><strong>AI Harness Engineering</strong></td>
      <td>Harnessing AI for Code Generation, Code Synthesis from Intent, AI-Driven Development, LLM-Controlled Programming, Multi-Model Code Orchestration, Semantic Intent to Code Translation, AI Agent Coordination</td>
    </tr>
    <tr>
      <td><strong>AI/ML Frameworks</strong></td>
      <td>LangChain, LangGraph, PyTorch, Scikit-learn, HuggingFace Transformers, Sentence Transformers</td>
    </tr>
    <tr>
      <td><strong>LLMs & NLP</strong></td>
      <td>OpenAI Agents SDK, Google Gemini, RAG, Prompt Engineering, Agent-to-Agent Communication, Semantic Intent Routing</td>
    </tr>
    <tr>
      <td><strong>Computer Vision</strong></td>
      <td>PyTorch, CLIP, ResNet, CRNN, Attention Mechanisms, CTC Loss, FAISS, Object Detection, OCR</td>
    </tr>
    <tr>
      <td><strong>Backend & APIs</strong></td>
      <td>Node.js, Express, FastAPI, Flask, REST APIs, WebSocket/Streaming, Authentication (bcrypt, TOTP, 2FA), Rate Limiting, CSRF Protection</td>
    </tr>
    <tr>
      <td><strong>Frontend</strong></td>
      <td>React 19, TypeScript, Vite, Tailwind CSS, Material-UI, MapLibre GL</td>
    </tr>
    <tr>
      <td><strong>Databases & Vector Search</strong></td>
      <td>MongoDB, PostgreSQL, Redis, ChromaDB, FAISS, Query Optimization, Caching</td>
    </tr>
    <tr>
      <td><strong>DevOps & ML</strong></td>
      <td>Docker, ZenML, Git/GitHub, CI/CD, Grafana, Tempo Tracing, Structured Logging</td>
    </tr>
    <tr>
      <td><strong>Data & Math</strong></td>
      <td>NumPy, Pandas, Linear Algebra, Calculus, Statistics, Signal Processing, Time-Series Analysis</td>
    </tr>
    <tr>
      <td><strong>Browser Automation</strong></td>
      <td>Playwright, Puppeteer, Web Research, Content Extraction, Session Management</td>
    </tr>
  </tbody>
</table>

---

## 🎓 Education

### University of Science, VNU-HCM

**B.S. in Information Technology** | _2024 - Present_ | **GPA: 3.28/4.0**

- Relevant Coursework: Data Structures & Algorithms, Object-Oriented Programming, Software Engineering, Database Systems, Linear Algebra, Calculus, Statistics, Artificial Intelligence, Machine Learning
- Academic focus: AI/ML systems, software engineering, and mathematical foundations for computing

---

## 🚀 Featured Projects

### TorchViz-3D

**AI/ML Visualization Engineer** | _June 2026 - Current_ | **[torchviz-3d](https://torchviz-3d.vercel.app/)**

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>Browser-based educational platform that converts PyTorch-style <code>nn.Module</code> code into interactive 3D neural-network architecture diagrams without a backend or full PyTorch runtime.</td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li><strong>In-Browser Model Tracing:</strong> Used Pyodide and a custom shape-only <code>torchstub</code> runtime to execute model definitions safely and derive layer shapes, parameter counts, hierarchy, and graph edges</li>
          <li><strong>Interactive 3D Visualization:</strong> Rendered nested modules, tensor dimensions, skip connections, concatenation paths, and animated operation effects with React Three Fiber and Three.js</li>
          <li><strong>Developer Tooling:</strong> Integrated a Monaco code editor, inline shape-error highlighting, synchronized layer inspection, architecture templates, and SVG/PNG export</li>
          <li><strong>Learning Experience:</strong> Built guided learning paths, review modes, model-flow demonstrations, and shape/value exercises for understanding neural-network operations</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Architecture & Quality</strong></td>
      <td>
        <ul>
          <li>Designed a Web Worker pipeline from source code to an intermediate graph representation, deterministic layout engine, and interactive 3D scene</li>
          <li>Implemented reusable support for architectures including LeNet-5, ResNet, Vision Transformer, AlexNet, VGG-16, MobileNetV2, and UNet</li>
          <li>Maintained automated tests for shape inference, graph edges, layout bounds, localization, exercises, and forward-pass behavior</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>React 18, TypeScript, Vite, Three.js, React Three Fiber, Pyodide, WebAssembly, Web Workers, Monaco Editor, Zustand, SVG</td>
    </tr>
  </tbody>
</table>

---

### Yetty - AI Content Creation Platform

**Full-Stack Developer** | _March 2026 - Current_ | **[icecone.ai](https://icecone.ai/)**

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>AI-driven content creation and scheduling platform for multi-modal content (text, image, video, music) with virtual influencer management, MCP tool integration, and agentic AI workflows.</td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li><strong>Multi-Module Platform:</strong> Built 5+ integrated modules (content scheduler, media management, AI creation suite, influencer discovery, browser agent) with 100+ modular API routes</li>
          <li><strong>Agentic AI System:</strong> Implemented OpenAI Agents SDK with agent-to-agent communication, semantic intent routing, and persistent state; integrated Playwright/Puppeteer for autonomous web research</li>
          <li><strong>Multi-AI Orchestration:</strong> Unified multiple AI providers (text, music, image/video generation) with provider-agnostic routing and error fallback</li>
          <li><strong>Real-Time Infrastructure:</strong> Built WebSocket + Socket.IO layers for LLM streaming, live analytics, and scheduled content publishing with job queues and CRON orchestration</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technical Impact</strong></td>
      <td>
        <ul>
          <li><strong>Security & Scale:</strong> Full security audit compliance (bcrypt, 2FA/TOTP, CSRF, DOMPurify XSS, Helmet); distributed rate limiting (Redis + MongoDB); production-grade session management</li>
          <li><strong>Observability:</strong> Grafana + Tempo distributed tracing, structured logging, real-time metrics, admin alerts</li>
          <li><strong>Performance:</strong> Redis caching, optimized multi-DB queries, media streaming with range requests, Vite code-splitting</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        <ul>
          <li><strong>Frontend:</strong> React 18, TypeScript, Vite, Tailwind CSS, Material-UI, Three.js, Remotion</li>
          <li><strong>Backend:</strong> Node.js, Express, Socket.IO, WebSocket, node-cron, FFmpeg, Sharp</li>
          <li><strong>AI/ML:</strong> OpenAI Agents SDK, Suno (music), Fal AI (image/video), Playwright, Puppeteer</li>
          <li><strong>Database & Cache:</strong> MongoDB, PostgreSQL, Redis, ChromaDB</li>
          <li><strong>DevOps:</strong> Docker, Render, GitHub CI, Grafana, Tempo tracing</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

---

### HousingSGN Cloud Hosting & WordPress Migration

  **Cloud & WordPress Migration Consultant** | _May 2026 - Current_ | **Customer Project**

  <table>
    <thead>
      <tr>
        <th><strong>Aspect</strong></th>
        <th><strong>Details</strong></th>
      </tr>
    </thead>
    <tbody>
      <tr>
        <td><strong>Project</strong></td>
        <td>Cloud migration planning and performance audit for a WordPress real estate portal, housingsgn.com.</td>
      </tr>
      <tr>
        <td><strong>Responsibilities</strong></td>
        <td>
          <ul>
            <li>Gather customer requirements, analyze current hosting limitations, and identify technical constraints affecting reliability and maintainability</li>
            <li>Compared Cloudways, Kinsta, WP Engine, VPS, cPanel, AWS, and GCP based on cost, setup complexity, scalability, support, and operational effort</li>
            <li>Planned deployment architecture for two WordPress applications: main site and Japanese subdomain</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td><strong>Migration Planning</strong></td>
        <td>
          <ul>
            <li>Prepared migration steps for WordPress files, MariaDB database import, DNS configuration, SSL setup, and production environment configuration</li>
            <li>Identified migration risks including large database import, hardcoded local URLs, premium plugin license reactivation, SSL configuration, and theme update safety</li>
            <li>Investigated slow listing pages and identified N+1 <code>get_post_meta()</code> calls across property cards and map pins</li>
            <li>Found expensive <code>wp_postmeta</code> sorting by <code>prop_featured</code>, duplicated <code>WP_Query</code> execution, and no persistent Redis/Memcached object cache</li>
          </ul>
        </td>
      </tr>
      <tr>
        <td><strong>Technologies Used</strong></td>
        <td>
          WordPress, PHP 8.4, MariaDB 10.11, Docker Compose, Cloudways, DigitalOcean, DNS, SSL, WP-CLI.
        </td>
      </tr>
    </tbody>
  </table>

---

### Vietnamese AI Travel Assistant

**Full-Stack AI Engineer** | _Oct 2025 - Dec 2025_ | **University Course Project**

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>Multi-modal tourism chatbot with RAG, LangGraph agentic workflows, CLIP image search, and full-stack Flask + React platform for Vietnamese travel recommendations.</td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li><strong>Multi-Modal AI:</strong> CLIP + ResNet image search with FAISS indexing (200K+ vectors) for visual tourism location identification from photos</li>
          <li><strong>Agentic RAG:</strong> LangGraph agents with tool calling (RAG retrieval + location extraction); ChromaDB with HuggingFace embeddings; Google Gemini LLM; Vietnamese NLP processing (5000+ locations)</li>
          <li><strong>Full-Stack:</strong> Flask REST backend + React frontend with MapLibre GL maps, bcrypt auth, real-time LLM streaming, MongoDB + PostgreSQL</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technical Impact</strong></td>
      <td>
        <ul>
          <li><strong>Performance:</strong> FAISS-accelerated image search with sub-second queries; optimized ChromaDB vector similarity search</li>
          <li><strong>Architecture:</strong> Modular design with clean separation: agents, RAG engine, vision module, database layer</li>
          <li><strong>Scalability:</strong> Persistent conversation checkpointing, concurrent user handling, real-time streaming</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        LangChain, LangGraph, CLIP, ResNet, FAISS, ChromaDB, Flask, React 19, PyTorch, MongoDB, PostgreSQL, Google Gemini, HuggingFace, Docker
      </td>
    </tr>
  </tbody>
</table>

---

### Mental Health RAG Chatbot

**AI/ML Engineer & Backend Developer** | _Oct 2025 - Dec 2025_ | **University Course Project**

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>Psychology-focused RAG system with DSM-5 knowledge base, diagnostic assessment agents, unified FastAPI + Chainlit interface, and MongoDB authentication.</td>
    </tr>
    <tr>
      <td><strong>Responsibilities</strong></td>
      <td>
        <ul>
          <li>Architected unified FastAPI + Chainlit application; designed LangGraph agents with custom tool calling for DSM-5 retrieval and diagnosis tracking</li>
          <li>Implemented modular RAG pipeline: PDF loaders, recursive text splitting, HuggingFace embeddings, ChromaDB vector store</li>
          <li>Built secure auth system with MongoDB user management, session-based auth, bcrypt, and conversation persistence</li>
          <li>Integrated Google Gemini LLM for context-aware psychology responses</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li><strong>Agent System:</strong> LangGraph agents with state management, tool execution (retrieve_context, update_diagnosis), and structured diagnostic tracking</li>
          <li><strong>Vector Search:</strong> ChromaDB with top-k similarity retrieval and source attribution for psychology knowledge base</li>
          <li><strong>Production Architecture:</strong> Scalable system with CORS, session management, error handling, and comprehensive testing</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        LangChain, LangGraph, FastAPI, Chainlit, ChromaDB, MongoDB, Google Gemini, HuggingFace, bcrypt, Pydantic, PyMongo
      </td>
    </tr>
  </tbody>
</table>

---

### ICPR 2026 License Plate Recognition Competition

**Computer Vision Researcher** | _Finished_ | **🏆 Ranked 23rd**

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Competition</strong></td>
      <td>Multi-frame license plate OCR from low-resolution video frames using CNNs, attention mechanisms, and CTC decoding. Achieved 23rd place by analyzing and extending the baseline CRNN pipeline.</td>
    </tr>
    <tr>
      <td><strong>Research Contributions</strong></td>
      <td>
        <ul>
          <li>Analyzed and extended multi-frame CRNN + attention baseline; experimented with modifications to improve recognition under degraded conditions</li>
          <li>Customized architecture: 7-layer CNN (3→64→128→256→512 channels) + AttentionFusion (temporal fusion across 5 frames) + 2-layer BiLSTM + CTC decoder (38 characters)</li>
          <li>Experimented with data augmentation (blur, noise, compression), training strategies, hyperparameter tuning, and CTC loss optimization</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technical Achievements</strong></td>
      <td>
        <ul>
          <li>Systematic architecture improvements and hyperparameter optimization yielded 23rd place ranking</li>
          <li>Applied deep learning theory (CNN feature extraction, temporal modeling with BiLSTM, attention mechanisms) to practical implementation</li>
          <li>Gained hands-on experience with multi-frame processing, batch operations, and sequence-to-sequence learning</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        PyTorch, Custom nn.Module architectures, CTC loss, BiLSTM, Attention mechanisms, CNN architectures, Data augmentation, Custom PyTorch Dataset
      </td>
    </tr>
  </tbody>
</table>

---

### Smart Construction - IoT Activity Monitoring

**MLOps Engineer & Data Scientist** | _2025_

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>Real-time Active/Idle classification from construction site IoT sensor data (accelerometer + gyroscope) using ZenML orchestration and robust signal processing.</td>
    </tr>
    <tr>
      <td><strong>Responsibilities</strong></td>
      <td>
        <ul>
          <li>Designed and implemented 7-step ZenML pipeline: data ingestion → normalization → denoising → resampling → feature windowing → classification → persistence</li>
          <li>Developed robust rule-based classifier using z-score normalization with MAD, hysteresis thresholding, and temporal debouncing (10s window)</li>
          <li>Engineered time-series utilities: norm calculation, resampling (1Hz), sliding window extraction, signal denoising; built statistical model training with percentile-based thresholds</li>
          <li>Implemented YAML-based configuration management and JSON model serialization</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li>Complete ML lifecycle under real-world constraints: data exploration, feature engineering, model iteration, evaluation</li>
          <li>Robust classifier resilient to sensor noise through median-based statistics and hysteresis state machine</li>
          <li>Modular ZenML architecture with configuration-driven execution and comprehensive testing</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        ZenML, Pandas, NumPy, Time-series processing, Signal processing (denoising, resampling, debouncing), MAD normalization, Dataclasses
      </td>
    </tr>
  </tbody>
</table>

---

### Tower Defense Game - Team 7

**Software Developer** | _June 2025 - August 2025_

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>Tower Defense game in C++ with OOP principles, CMake build system, and collaborative team development.</td>
    </tr>
    <tr>
      <td><strong>Responsibilities</strong></td>
      <td>
        <ul>
          <li>Designed and implemented game mechanics (tower placement, enemy pathfinding, combat systems)</li>
          <li>Applied OOP principles for modular, maintainable code architecture; configured CMake build system for cross-platform compatibility</li>
          <li>Managed Git/GitHub workflows with code reviews and collaborative development; debugged and optimized performance</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li>Successfully delivered complex game with 96.8% C++ codebase (117KB+)</li>
          <li>Advanced OOP and design patterns; Git workflow proficiency and team collaboration</li>
          <li>Game loops, entity management, collision detection, and cross-platform compatibility</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        C++ (advanced OOP), CMake, Git/GitHub, OOP design patterns, Game loops, Entity management
      </td>
    </tr>
  </tbody>
</table>

---

### Transformer Online Continual Learning

**Research Implementation** | _Self-directed_

<table>
  <thead>
    <tr>
      <th><strong>Aspect</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>Project</strong></td>
      <td>Online continual learning with Transformer using privileged in-context labels and reservoir experience replay on Split Fashion-MNIST; reproducible ablation study.</td>
    </tr>
    <tr>
      <td><strong>Key Achievements</strong></td>
      <td>
        <ul>
          <li>Implemented SOCLTransformer with privileged attention (labels in keys/values) and zero-diagonal causal masking to prevent self-peeking</li>
          <li>Built online training loop and 2×2 ablation (ICL and replay modes) with pre-update accuracy and task accuracy matrices</li>
          <li>Provided reproducible artifacts: Colab notebook, heatmaps, accuracy curves, run outputs (online_accuracy.csv, accuracy_matrix.npy)</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td><strong>Technologies Used</strong></td>
      <td>
        Python, PyTorch, torchvision, NumPy, Matplotlib, Seaborn, Colab
      </td>
    </tr>
  </tbody>
</table>

---

## 🏅 Certifications

<table>
  <thead>
    <tr>
      <th><strong>Certification</strong></th>
      <th><strong>Institution</strong></th>
      <th><strong>Year</strong></th>
      <th><strong>Details</strong></th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td><strong>AIO-2025 AI/ML Program</strong></td>
      <td>AI VIETNAM</td>
      <td>2025 - 2026</td>
      <td>12/12 modules completed; theory-focused ML curriculum with mathematical derivations and from-scratch implementations</td>
    </tr>
    <tr>
      <td><strong>IELTS</strong></td>
      <td>The British Council</td>
      <td>2024</td>
      <td>6.0</td>
    </tr>
    <tr>
      <td><strong>AWS Cloud Practitioner</strong></td>
      <td>Amazon Web Services</td>
      <td>2026</td>
      <td>Foundational cloud certification demonstrating understanding of AWS services, cloud concepts, and cloud value proposition</td>
    </tr>
  </tbody>
</table>

---
