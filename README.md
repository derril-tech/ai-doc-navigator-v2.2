# 🧭 AI DocNavigator
**with LangGraph & OpenAI**

> **Navigate any GitHub repository like a graph. Ask questions, get intelligent answers with precise citations, and explore codebases with AI-powered insights—all in real-time.** ⚡

---

## ✨ Features

### 🎯 **Core Functionality**
- 🔍 **Intelligent Repository Discovery** - Automatically analyze and map repository structure
- 🤖 **AI-Powered Q&A** - Ask natural language questions and get precise answers with citations
- 📊 **Real-Time Streaming** - Watch AI responses stream token-by-token for instant feedback
- 🗺️ **Interactive Code Graph** - Visualize file relationships and dependencies
- 📝 **Precise Citations** - Every answer includes exact file paths and line numbers
- 🔄 **Conversation Memory** - Maintain context across multiple questions per repository

### 🎨 **Beautiful UI/UX**
- ✨ **Modern 2025 Design** - Glassmorphism effects, smooth animations, video backgrounds
- 🌙 **Dark Mode** - Full theme support with seamless transitions
- 📱 **Fully Responsive** - Optimized for desktop, tablet, and mobile devices
- ♿ **Accessible** - WCAG AA compliant with proper touch targets (44x44px minimum)
- 🎯 **Intuitive Interface** - Clean, user-friendly design with state-driven transitions
- 🎬 **Smooth Animations** - Micro-interactions and elegant state changes

### 🚀 **Advanced Features**
- 🎚️ **Customizable Analysis Styles** - Balanced, Technical, Beginner-Friendly, Architecture, Debugging
- 📝 **Custom Prompts** - Guide the AI with specific instructions for tailored responses
- 🔐 **Private Repository Support** - Analyze private repos with GitHub token authentication
- 📊 **Code Complexity Analysis** - Identify hotspots, metrics, and improvement suggestions
- 🔄 **Repository Comparison** - Side-by-side analysis of two repositories
- 📈 **Live Pipeline Tracking** - Real-time visualization of analysis stages
- 💾 **Persistent History** - All conversations saved locally with 7-day retention
- 🔗 **Shareable Links** - Generate permalinks to share specific analyses

### 🏗️ **Enterprise Features**
- 👥 **Team Collaboration** - Share workspaces with unique IDs
- 📤 **Export & Import** - Export conversations as Markdown, import workspace states
- 🎨 **Dependency Visualization** - Interactive D3.js force-directed graph of file dependencies
- 📊 **Complexity Metrics** - File-by-file complexity scores and recommendations
- 🔍 **Interactive Code Explorer** - Expandable code citations with syntax highlighting

---

## 🏗️ Tech Stack

### **Backend** 🐍
- **FastAPI** - Modern, high-performance Python web framework
- **LangGraph** - Sophisticated AI agent orchestration framework
- **OpenAI API** - GPT-4.1-mini for intelligent code analysis
- **Python 3.11+** - Latest features and performance optimizations
- **httpx** - Async HTTP client for GitHub API integration

### **Frontend** ⚛️
- **Next.js 15** - React 19.2 with App Router and Server Components
- **React 19.2** - Latest React features with concurrent rendering
- **TypeScript** - Full type safety across the application
- **Tailwind CSS** - Utility-first styling with custom design system
- **shadcn/ui** - Beautiful, accessible component library
- **D3.js** - Interactive data visualizations and graph rendering
- **Lucide Icons** - Modern, consistent icon set

### **AI & Orchestration** 🤖
- **LangGraph** - Multi-agent workflow orchestration
- **OpenAI GPT-4.1-mini** - Cost-effective, fast AI responses
- **Streaming API** - Real-time token streaming via Server-Sent Events
- **Custom Prompt Engineering** - Fine-tuned prompts for optimal results

### **Database & Cache** 💾
- **Supabase** - PostgreSQL with real-time capabilities
- **Upstash Redis** - Serverless caching and rate limiting
- **LocalStorage** - Client-side conversation persistence

### **External APIs** 🔌
- **GitHub REST API** - Repository discovery and file content fetching
- **OpenAI API** - LLM-powered code analysis and summarization

### **Deployment** 🚀
- **Vercel** - Frontend deployment with edge functions
- **Railway** - Backend API deployment with auto-scaling
- **Environment-based Configuration** - Flexible deployment options

---

## 📸 Key Highlights

### 🎮 **Interactive Playground**
Experience real-time AI analysis with streaming responses, live pipeline tracking, and interactive code exploration. Ask questions like *"Where is authentication handled?"* or *"How does the caching system work?"* and get comprehensive answers with precise citations.

### 📊 **Visual Code Analysis**
Explore repositories through interactive visualizations:
- **Dependency Graph** - See how files connect and depend on each other
- **Complexity Heatmap** - Identify code hotspots and technical debt
- **File Explorer** - Navigate code with expandable citations

### 🎨 **Modern React Architecture**
Built with cutting-edge React 19.2 features:
- **Server Components** - Optimal performance with server-side rendering
- **Streaming UI** - Real-time updates without page reloads
- **State-Driven Transitions** - Smooth, elegant state changes
- **Single-Page Experience** - No routing complexity, just component transitions

### 🤖 **Sophisticated AI Orchestration**
Powered by LangGraph for intelligent multi-step workflows:
- **Repository Discovery** - Automatically map repository structure
- **File Selection** - Intelligently identify relevant files
- **Code Chunking** - Smart context management for optimal AI responses
- **Answer Generation** - Context-aware responses with citations

---

## 📖 User Guide

### 🎮 Using the Playground

1. **Enter Repository**
   - Type `owner/repo` (e.g., `openai/openai-cookbook`)
   - Or use suggested popular repositories
   - Private repos require GitHub token

2. **Ask Questions**
   - Natural language questions work best
   - Examples:
     - *"Where is authentication handled?"*
     - *"How does the caching system work?"*
     - *"What's the main entry point?"*
     - *"Explain the architecture"*

3. **Customize Analysis** (Optional)
   - Choose analysis style: Balanced, Technical, Beginner, Architecture, or Debugging
   - Add custom instructions for tailored responses
   - Enable/disable streaming for different experiences

4. **Explore Results**
   - View AI-generated answers with citations
   - Click citations to see code snippets
   - Copy code or navigate to GitHub
   - Export conversation as Markdown

5. **Advanced Features**
   - **Compare Repositories** - Side-by-side analysis
   - **Complexity Analysis** - View code complexity metrics
   - **Dependency Graph** - Visualize file relationships
   - **Team Sharing** - Share workspaces with colleagues

### 📊 Using the Dashboard

1. **View History**
   - See all previous conversations
   - Filter by repository
   - View relative timestamps

2. **Manage Conversations**
   - Delete individual conversations
   - Clear all history
   - Export important analyses

3. **Quick Actions**
   - Share conversations via permalink
   - Export as Markdown
   - Resume previous analyses

---

## 🚀 Getting Started

### Prerequisites

- **Node.js 20+** and pnpm (or npm/yarn)
- **Python 3.11+**
- **Supabase** account and project
- **Upstash Redis** account
- **GitHub Personal Access Token** (for private repos)
- **OpenAI API key**

---

## 🎨 Customization

### Analysis Styles

Choose from five analysis styles to match your needs:

- **Balanced** - Clear, accessible, well-structured (default)
- **Technical** - Deep technical analysis for experienced developers
- **Beginner** - Simple, educational, step-by-step explanations
- **Architecture** - High-level system design and patterns
- **Debugging** - Issue identification and problem-solving

### Theme Options

- ☀️ **Light Mode** - Clean, bright interface
- 🌙 **Dark Mode** - Easy on the eyes
- 🖥️ **System** - Follows OS preference



## 🔒 Security

- **API Keys**: Never exposed to frontend
- **GitHub Tokens**: Securely stored and transmitted
- **CORS**: Configured for production domains
- **Rate Limiting**: Redis-based rate limiting
- **Input Validation**: Pydantic models for type safety

---

## 👨‍💻 Creator

**Created by Derril Filemon**

---

## 🙏 Acknowledgments

- **OpenAI** - For GPT-4.1-mini API and LangChain integration
- **LangGraph** - For sophisticated AI agent orchestration
- **Supabase** - For PostgreSQL database and real-time capabilities
- **Upstash** - For serverless Redis caching
- **Railway** - For seamless backend deployment
- **Vercel** - For Next.js deployment and edge functions
- **shadcn/ui** - For beautiful, accessible components
- **GitHub** - For repository API access

---



<div align="center">



Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
