Enterprise Customer Support Automation System
An intelligent, autonomous customer support resolution system powered by a multi-agent Retrieval-Augmented Generation (RAG) pipeline. This project focuses on delivering highly accurate, empathetic, and automated ticket resolution while adhering to production-grade DevOps practices.

🚀 Key Features
Agentic Orchestration: Powered by CrewAI, a team of specialized AI agents handles the entire lifecycle of a customer query.

Hybrid RAG Pipeline: Utilizes a FAISS-based knowledge base for high-precision, context-aware information retrieval.

Multi-Step Quality Assurance: Every generated response is autonomously critiqued and refined before delivery.

Modern API & UI: Scalable backend powered by FastAPI, paired with an intuitive Streamlit chat interface.

Enterprise DevOps: Fully containerized with Docker, featuring a robust CI/CD pipeline via GitHub Actions with automated validation and rollback strategies.

📸 System Previews
Frontend Interface
The Streamlit-based chat interface where users interact with the support system.
 (Replace this path with your actual image file)

Backend Architecture & Logs
The FastAPI backend processing agentic workflows and pipeline logs.
 (Replace this path with your actual image file)

🧠 Multi-Agent Workflow
The core logic of the system is driven by five specialized agents working in sequence:

Query Understanding Agent: Parses the initial customer ticket to identify the core issue and extract key entities.

Sentiment Analysis Agent: Evaluates the emotional tone of the user to adjust the empathy and urgency of the final response.

RAG Retrieval Agent: Queries the Hybrid FAISS knowledge base to pull relevant internal documentation and historical solutions.

Escalation Resolution Agent: Synthesizes the retrieved context and drafts a comprehensive, accurate response.

Quality Assurance Agent: Critiques the draft against support guidelines, ensuring formatting, tone, and factual accuracy before final delivery.

🛠️ Tech Stack
Frameworks: CrewAI, LangChain

Backend: FastAPI, Python 3.10+

Frontend: Streamlit

Vector Database: FAISS (Hybrid Search)

DevOps: Docker, GitHub Actions

⚙️ Local Setup & Installation
Prerequisites
Docker & Docker Compose installed on your machine.

API keys for your configured LLM provider.

Steps
Clone the repository:

Bash
git clone https://github.com/yourusername/enterprise-support-agent.git
cd enterprise-support-agent
Configure Environment Variables:
Create a .env file in the root directory and add your credentials:

Code snippet
GEMINI_API_KEY=your_api_key_here
Build and Run with Docker:

Bash
docker-compose up --build
Access the Application:

Frontend UI: http://localhost:8501

FastAPI Docs (Swagger): http://localhost:8000/docs

👨‍💻 Author
Shreesanyog Rath
