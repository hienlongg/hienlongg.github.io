---
title: 'Trương Hiển Long - Software Engineer CV'
variant: 'Full-Stack & Backend Engineering Focused'
lastUpdated: '2026-01-15'
---

# Trương Hiển Long

## Full-Stack Software Engineer | Backend & AI Integration Specialist

Full-stack software engineer with expertise in building complex backend systems, REST APIs, and AI-integrated applications through comprehensive academic projects and real-world experience. Proficient in Python (FastAPI, Flask), TypeScript/React, and database architecture (MongoDB, PostgreSQL). Strong foundation in algorithms, data structures, and system design with proven ability to deliver scalable, well-architected solutions from concept to implementation.

---

## 📞 Contact Information

- **Phone:** [+84.944.679.025 (VN)](https://zalo.me/0944679025)
- **Email:** [hienlong106@gmail.com](mailto:hienlong106@gmail.com)
- **LinkedIn:** [https://www.linkedin.com/in/long-truong-0b0597243/](https://www.linkedin.com/in/long-truong-0b0597243/)
- **GitHub:** Portfolio available upon request

---

## 🎯 Core Competencies

**Backend Development**
- Python (FastAPI, Flask), REST API Design
- Database Architecture (MongoDB, PostgreSQL)
- Authentication/Authorization (bcrypt, session management)
- Microservices, WebSocket/Streaming

**Frontend Development**
- React 19, TypeScript, Modern JavaScript
- Material-UI, Tailwind CSS, Responsive Design
- State Management, API Integration

**Software Engineering**
- C++ (Advanced), OOP, Design Patterns
- Algorithms & Data Structures
- Git/GitHub, Code Review, Testing

**Cloud & DevOps**
- Docker, CI/CD
- MLOps (ZenML), Pipeline Orchestration
- Environment Configuration, Deployment

---

## 💼 Software Engineering Experience

### VoyAIage - Vietnamese AI Travel Assistant
**Full-Stack Engineer** | _Current - 2025_ | **University Course Project**

**Full-Stack Tourism Platform (Academic Project)**

Architected and developed complete tourism platform as university course project with Flask REST API backend, React 19 frontend, and multi-database architecture serving AI-powered travel recommendations.

**Backend Engineering:**
- **API Architecture:** Built comprehensive Flask REST API with 15+ endpoints: authentication (login/register/logout), chat streaming, travel logs CRUD, social posts, file upload
- **Database Design:** Architected multi-database system: MongoDB (user sessions, app data), PostgreSQL (conversation memory with LangGraph checkpointing), ChromaDB (vector store)
- **Authentication & Security:** Implemented bcrypt password hashing, session-based auth with Flask-Session, CORS middleware for cross-origin requests
- **File Management:** Built upload system for images with validation, storage, and URL resolution for user-generated content
- **API Integration:** Integrated Google Gemini LLM with streaming responses, custom embedding API client, external map services

**Frontend Engineering:**
- **Modern Stack:** Built responsive React 19 application with TypeScript, Vite build tool, Material-UI components, Tailwind CSS v4 styling
- **Architecture:** Clean separation with AuthProvider context, React Router v6 routing, Axios HTTP client, reusable component library
- **Features:** Real-time chat with streaming AI responses, interactive MapLibre GL maps, markdown rendering (react-markdown + remark-gfm), location autocomplete
- **UI/UX:** Responsive design across devices, beautiful interface with lucide-react icons, modal dialogs, form validation, loading states

**System Architecture:**
- **Scalability:** Designed modular backend with separation: routes, models, middlewares, utils; frontend with providers, pages, components structure
- **Performance:** Optimized database queries, implemented FAISS for sub-second image search, ChromaDB for fast semantic retrieval
- **Code Quality:** ESLint configuration, TypeScript strict mode, error handling middleware, logging, input validation

**Technical Stack:** Flask, FastAPI, React 19, TypeScript, MongoDB, PostgreSQL, ChromaDB, Docker, Git

---

### Mental Health RAG Chatbot
**Backend Engineer & Full-Stack Developer** | _Current - 2025_ | **University Course Project**

**Unified FastAPI + Chainlit Application (Academic Project)**

Developed backend system as university course project combining high-performance REST API (FastAPI) with interactive chat interface (Chainlit) for psychology chatbot.

**Backend Architecture:**
- **Unified Application:** Architected FastAPI app with Chainlit mounted at /rag route, combining RESTful endpoints with WebSocket chat interface
- **Middleware Stack:** Implemented CORS for cross-origin requests, SessionMiddleware for session management, centralized error handling
- **Authentication System:** Built MongoDB-based user management: registration, login with password validation, bcrypt hashing, conversation history storage
- **API Endpoints:** Developed routes for health checks (/health), document management (/documents/*), authentication (/auth/*), with proper error responses
- **Database Integration:** Designed MongoDB schema with UserModel, ConversationModel, MessageModel; implemented CRUD operations with PyMongo

**System Design:**
- **Modular Architecture:** Separated concerns: routes (health, documents), utils (error_handler), backend (database, storage), rag (pipeline, agents)
- **Configuration Management:** Environment-based config with .env files, logging setup, database connection pooling
- **Error Handling:** Centralized error handling with HTTP exceptions, status codes, proper JSON error responses
- **Testing:** Built test suite with unit tests, integration tests, manual verification scripts

**Technical Stack:** FastAPI, Chainlit, PyMongo, MongoDB, Starlette Middleware, Python 3.9+, LangChain (AI integration)

---

### Travel Platform Frontend (VoyAIage Client)
**Frontend Engineer** | _Current - 2025_

**Modern React 19 SPA with TypeScript**

Built responsive, feature-rich frontend for tourism platform with modern UI framework and best practices.

**Frontend Development:**
- **Component Architecture:** Organized 30+ reusable components: Auth (Login/Register), ChatbotPage (ChatWindow, InputBar, MapView), Common (Sidebar, LocationAutocomplete), CreatePage, LandingPage sections
- **Page Structure:** Implemented 10+ pages with React Router v6: Landing, Chat, CreatePage, Dashboard, Inspiration feed, SavedPosts, TravelLog, PostDetail
- **State Management:** Built AuthProvider context for global auth state, session persistence, protected routes
- **API Integration:** Created API client utilities (postApi, saveApi) with Axios, error handling, request/response interceptors

**UI/UX Engineering:**
- **Responsive Design:** Mobile-first approach with Tailwind CSS v4, breakpoints for all device sizes
- **Modern UI:** Material-UI components (buttons, forms, cards, dialogs), custom styling with Emotion CSS-in-JS
- **Interactive Maps:** Integrated MapLibre GL for location visualization, custom markers, popups, navigation controls
- **Rich Content:** Markdown rendering for travel posts (react-markdown), syntax highlighting, GFM support

**Development Practices:**
- **Type Safety:** TypeScript with strict mode, custom type definitions (location.ts, post.ts)
- **Build Optimization:** Vite for fast HMR, code splitting, optimized production builds
- **Code Quality:** ESLint with TypeScript rules, consistent formatting, component documentation
- **Version Control:** Git workflow with feature branches, meaningful commits, code review

**Technical Stack:** React 19, TypeScript, Vite, Material-UI, Tailwind CSS v4, MapLibre GL, Axios, React Router v6

---

### Tower Defense Game Project - Team 7
**C++ Software Developer** | _June 2025 - August 2025_

**Object-Oriented Game Development**

Collaborated in team to develop tower defense game using C++ with advanced OOP principles, demonstrating strong C++ programming and software engineering skills.

**Software Development:**
- **C++ Programming:** Developed game using advanced C++ (96.8% of 117KB+ codebase), object-oriented design, class hierarchies, polymorphism
- **Game Architecture:** Implemented game mechanics, entity management, collision detection, game state machine, render loop
- **Build System:** Configured CMake build system (3.7% of project), cross-platform compatibility, dependency management
- **Team Collaboration:** Used Git for version control, code reviews, merging team contributions, conflict resolution
- **Code Quality:** Wrote clean, maintainable code with proper documentation, naming conventions, design patterns

**Technical Stack:** C++, CMake, Git, Visual Studio/Code::Blocks, Object-Oriented Programming

---

### Smart Construction - IoT Activity Monitoring
**Software Engineer & MLOps** | _2025_ | **Confidential Industry Project**

**Real-World ML Pipeline (Confidential)**

Built production-like machine learning pipeline for confidential real-world sensor data processing and activity classification, experiencing complete ML project lifecycle under industry constraints.

**Software Engineering:**
- **Pipeline Architecture:** Designed 7-step ZenML pipeline with modular step architecture, clean interfaces, dependency injection
- **Code Organization:** Structured project: core (interfaces, utils), predictors (rule_based), zen_pipelines (steps, pipeline), configs (YAML), tests
- **Data Engineering:** Built time-series processing utilities: norm calculation, resampling, sliding window extraction, denoising
- **Configuration:** YAML-based configuration management, JSON model serialization/deserialization, environment variables
- **Testing:** Implemented unit tests for contract validation, edge case handling, integration testing

**Technical Stack:** Python, ZenML, Pandas, NumPy, Dataclasses, YAML, Git

---

### ICPR 2026 License Plate Recognition Competition
**Software Engineer & Researcher** | _2025_

**Applied Deep Learning Research**

Participated in computer vision competition by studying and modifying a multi-frame OCR baseline pipeline, applying deep learning theory to improve license plate recognition from degraded video frames.

**Software Engineering & Research:**
- **Baseline Analysis & Extension:** Studied provided multi-frame CRNN + attention architecture, experimented with component modifications and training strategies
- **PyTorch Implementation:** Worked with custom nn.Module architectures, training loops, data augmentation pipelines, understanding deep learning software patterns
- **Applied Theory:** Translated knowledge of CNNs, BiLSTM, attention mechanisms, and CTC loss into practical implementation and experimentation
- **Research Mindset:** Approached competition as learning opportunity—analyzed baseline architecture, understood design decisions, iteratively tested improvements
- **Code Organization:** Built modular training pipeline with dataset classes, transform compositions, evaluation metrics

**Technical Stack:** Python, PyTorch, NumPy, Image Processing, Git

---

### AIO-2025 Learning & Academic Projects
**Computer Science Student** | _2025 - Current_

**Algorithm Implementation & Fundamentals**

Completed intensive coursework and projects demonstrating strong programming fundamentals, mathematical understanding, and algorithm implementation skills.

**Key Projects:**
- **ML Algorithms from Scratch:** Implemented K-Means, KNN, Decision Trees, Linear/Logistic Regression without high-level libraries, demonstrating algorithmic thinking and mathematical foundations
- **Neural Networks:** Built MLP, CNN, RNN/LSTM/GRU, Transformers from first principles using PyTorch, understanding architecture design
- **Mathematical Rigor:** Derived and implemented gradient descent, backpropagation, vectorization techniques with NumPy
- **Data Structures & Algorithms:** Coursework in advanced data structures, algorithm analysis, complexity theory, optimization
- **Object-Oriented Programming:** C++ projects with design patterns, inheritance, polymorphism, template programming

**Technical Stack:** Python, C++, NumPy, Pandas, PyTorch, Git

---

## 🎓 Education

### Ho Chi Minh University of Science
**Computer Science Student** | _Current_ | **GPA: 3.63/4.0**

**Key Coursework:**
- Software Engineering, Object-Oriented Programming (C++)
- Data Structures & Algorithms, Algorithm Design & Analysis
- Database Systems, Operating Systems
- Machine Learning, Artificial Intelligence (1-year specialization)
- Web Development, Computer Networks

**Academic Excellence:**
- Strong foundation in computer science fundamentals
- Active participation in programming challenges
- Team project experience with version control

---

## 🏆 Certificates

| Certificate | Institution | Year | Score |
|-------------|-------------|------|-------|
| **Sophomore of Information Technology** | University of Science - VNUHCM | 2025 | GPA: 3.63/4.0 |
| **IELTS** | The British Council | 2024 | 6.0 (L:6, R:7.5, W:6.5, S:4.5) |

---

## 🛠️ Technical Skills

**Programming Languages**
- **Python** (Advanced) - 3+ years, production systems
- **C++** (Advanced) - OOP, STL, algorithms
- **TypeScript/JavaScript** (Intermediate) - React, Node.js
- **C** (Intermediate)

**Backend Development**
- **Frameworks:** FastAPI, Flask, REST API design
- **Databases:** MongoDB, PostgreSQL, database design
- **Authentication:** bcrypt, session management, JWT
- **Tools:** Docker, Git/GitHub, Postman

**Frontend Development**
- **React 19** - Hooks, Context API, Router
- **TypeScript** - Strict mode, type safety
- **UI Frameworks:** Material-UI, Tailwind CSS v4
- **Build Tools:** Vite, Webpack, npm/yarn

**Software Engineering**
- **OOP & Design Patterns** - SOLID principles
- **Data Structures & Algorithms** - Advanced
- **Version Control** - Git, GitHub, collaboration
- **Testing** - Unit tests, integration tests
- **Code Quality** - ESLint, code review, documentation

**DevOps & Cloud**
- **Containerization:** Docker, Docker Compose
- **CI/CD:** GitHub Actions, deployment pipelines
- **MLOps:** ZenML, pipeline orchestration
- **Configuration:** Environment management, YAML

**Additional Skills**
- **Web Technologies:** RESTful APIs, WebSocket, CORS
- **Data Processing:** Pandas, NumPy
- **AI Integration:** LangChain, LLM APIs (bonus)

---

## 🎯 What I Bring

✅ **Full-Stack Capability** - Built complete applications: React frontend, Python backend, multi-database architecture, deployment

✅ **Strong Backend Skills** - REST API design, database architecture, authentication, scalable system design

✅ **Modern Frontend** - React 19, TypeScript, responsive design, state management, modern UI frameworks

✅ **Software Engineering** - Clean code, design patterns, testing, version control, team collaboration

✅ **Problem Solving** - Strong algorithmic thinking from C++ and CS fundamentals, compete in challenges

✅ **Fast Learner** - Quickly mastered React 19, FastAPI, TypeScript, cloud services through hands-on projects

✅ **Team Player** - Experience collaborating on team projects with Git, code reviews, communication

✅ **AI Integration** - Unique ability to integrate AI/ML capabilities into traditional software systems
