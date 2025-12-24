<div align="center">
<img src="https://capsule-render.vercel.app/api?type=waving&color=00468c&height=220&section=header&text=Gabriel%20Martins&fontSize=80&fontAlignY=35&desc=Senior%20Software%20Engineer%20|%20AI%20&%20Modernization&descAlignY=55&descAlign=50" alt="Gabriel Martins Banner" />
</div>
<div align="center">
🚀 Engineering Logic meets Generative AI
</div>

👨‍💻 About Me

I am a Senior Software Engineer (6+ years) specialized in critical mission systems for the Government sector. My background is built on solid Engineering principles (Java, Spring Boot, Oracle, Legacy Modernization).
Currently, I am pivoting my career towards AI Engineering, applying my architectural experience to build autonomous agents, RAG systems, and scalable AI solutions.

🔭 I’m currently building: MentorIA (An AI-Powered Productivity OS).

🌱 I’m currently learning: Advanced RAG patterns, LangChain, and Agentic Workflows.

💡 Superpower: Bridging the gap between robust legacy architectures and bleeding-edge AI innovation.

🧠 Featured Project: MentorIA (In Progress)

A "Waze for Life" — High-performance biological operating system.
Since my corporate work (Government/Banking) is under NDA/Private, MentorIA is my public playground for AI Engineering.

🏗 Architecture & Tech Stack:

Core: Python & TypeScript.

AI Engine: RAG (Retrieval-Augmented Generation) for personalized context + Autonomous Agents for active monitoring.

Orchestration: n8n workflows integrated with LLMs (Gemini/OpenAI).

Frontend: Next.js (React) for the visual dashboard.

Database: Supabase (PostgreSQL) + Vector Store concepts.

Development: Accelerated using Cursor and Windsurf (AI-First IDEs).

<div align="center">

%%{init: {'theme': 'base', 'themeVariables': { 'primaryColor': '#00468c', 'edgeLabelBackground':'#ffffff', 'tertiaryColor': '#f4f4f4'}}}%%
graph TD
    subgraph Client Side
        User((👤 User))
        UI[🖥️ Next.js Frontend\nReact Dashboard]
    end

    subgraph "Orchestration & Intelligence Core (The Brain)"
        n8n[⚙️ n8n Workflows\nAI Orchestrator]
        LLM[🧠 LLMs\nGemini / OpenAI]
        Agents[🤖 Autonomous Agents\nActive Monitoring]
    end

    subgraph "Memory & Knowledge Base"
        VectorDB[(📚 Supabase\nVector Store\nRAG Context)]
        RelationalDB[(🗄️ Supabase\nPostgreSQL\nStructured Data)]
    end

    %% Flows
    User <-->|Interacts| UI
    UI <-->|API Calls / Data| n8n

    %% RAG Flow
    n8n -->|1. Query Context| VectorDB
    VectorDB -.->|2. Relevant Chunks| n8n
    n8n -->|3. Prompt + Context| LLM
    LLM -.->|4. Generated Response| n8n

    %% Agent Flow
    Agents -->|Trigger Events| n8n
    Agents -.->|Monitor State| RelationalDB

    %% Data Persistence
    n8n <-->|Read/Write State| RelationalDB


Figure: MentorIA High-Level Architecture Flow

</div>

🛠 Tech Stack

Current Focus (AI & Automation)

<div style="display: flex; gap: 10px; margin-bottom: 20px;">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Python-3776AB%3Fstyle%3Dfor-the-badge%26logo%3Dpython%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/LangChain-1C3C3C%3Fstyle%3Dfor-the-badge%26logo%3Dchainlink%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/n8n-FF6584%3Fstyle%3Dfor-the-badge%26logo%3Dn8n%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/OpenAI-412991%3Fstyle%3Dfor-the-badge%26logo%3Dopenai%26logoColor%3Dwhite" />
</div>

Solid Engineering Background (6+ Years)

<div style="display: flex; gap: 10px; margin-bottom: 20px;">
<img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Spring_Boot-6DB33F%3Fstyle%3Dfor-the-badge%26logo%3Dspring-boot%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Oracle-F80000%3Fstyle%3Dfor-the-badge%26logo%3Doracle%26logoColor%3Dwhite" />
<img src="https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white" />
</div>

DevOps & Tools

<div style="display: flex; gap: 10px;">
<img src="https://www.google.com/search?q=https://img.shields.io/badge/Docker-2496ED%3Fstyle%3Dfor-the-badge%26logo%3Ddocker%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/GitLab_CI-FC6D26%3Fstyle%3Dfor-the-badge%26logo%3Dgitlab%26logoColor%3Dwhite" />
<img src="https://www.google.com/search?q=https://img.shields.io/badge/PostgreSQL-316192%3Fstyle%3Dfor-the-badge%26logo%3Dpostgresql%26logoColor%3Dwhite" />
</div>
