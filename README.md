## Run Locally (No Docker Required)

1. Clone repo:

git clone <repo_url>
cd ai-agent-langgraph-groq
Create virtual environment and install dependencies:


python -m venv venv
source venv/bin/activate   # Linux/macOS
venv\Scripts\activate      # Windows
pip install -r requirements.txt
cp .env.example .env