Prototype Agent — Google ADK Workspace Assistant
A smart AI-powered workspace assistant built with Google Agent Development Kit (ADK), capable of managing tasks, saving notes, and answering general knowledge questions.

Features
✅ Add and manage tasks
📝 Save detailed notes
✔️ Mark tasks as complete
💬 Answer general knowledge questions
☁️ Powered by Gemini AI via Google ADK
🗄️ Data stored in Google Cloud Datastore


🗂️ Project Structure
prototype_agent/
├── agent.py           # Main agent logic, tools, and FastAPI server
├── requirements.txt   # Python dependencies
├── __init__.py        # Package init
├── .env               # Environment variables (not committed)
└── .gitignore         # Git ignore rules

Setup & Installation
1. Clone the repository
    git clone https://github.com/jagadeeshnalluri99/prototype-agent.git
    cd prototype-agent
2. Create a virtual environment
   python -m venv .venv
   source .venv/bin/activate  
3. Install dependencies
   pip install -r requirements.txt

Google Cloud Requirements:
Google Cloud Project with billing enabled
Firestore (Datastore mode) database named genaistore
Service Account with Cloud Datastore User role
Vertex AI API enabled

Dependencies:
google-adk==1.14.0
langchain-community==0.3.27
wikipedia==1.4.0
google-cloud-datastore
google-cloud-logging
fastapi
uvicorn
python-dotenv
mcp
