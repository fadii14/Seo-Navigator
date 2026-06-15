==============================================================================
AI SEO NAVIGATOR - SETUP & RUN INSTRUCTIONS
==============================================================================

This project uses a Hybrid Architecture:
1. Backend: Python (FastAPI + Machine Learning)
2. Frontend: React (Modern UI)
3. AI Brain: Ollama (Llama 3.2)

------------------------------------------------------------------------------
PHASE 1: PREREQUISITES
------------------------------------------------------------------------------
Before starting, ensure the target laptop has these 3 things installed:
1. Python (v3.9 or higher)
2. Node.js (Latest LTS version)
3. Ollama (For the AI Consultant)

------------------------------------------------------------------------------
PHASE 2: FIRST-TIME INSTALLATION
------------------------------------------------------------------------------
(Do this only ONCE when you copy the project to a new laptop)

STEP 1: Install Python Libraries
   > Open Terminal/Command Prompt in this main folder.
   > Run the following command:
     pip install fastapi uvicorn pandas numpy scikit-learn ollama requests flask-cors
     OR pip install -r requirements.txt

STEP 2: Install React Dependencies
   > In the terminal, go inside the frontend folder:
     cd seo-frontend
   > Run this command to restore the modules:
     npm install
   > Wait for it to finish, then go back to the main folder:
     cd ..

STEP 3: Download the AI Model
   > Open a terminal and run:
     ollama pull llama3.2

------------------------------------------------------------------------------
PHASE 3: HOW TO RUN (DAILY USAGE)
------------------------------------------------------------------------------
Once installed, you can launch the entire system with one click.

1. Open Terminal in the main project folder.
2. Run the launcher script:
   python launcher.py

   * This will automatically start the Backend API.
   * This will automatically start the React Frontend.
   * Your browser will open the App automatically.

------------------------------------------------------------------------------
TROUBLESHOOTING
------------------------------------------------------------------------------
1. "Ollama connection failed":
   Make sure the Ollama app is actually running in the background (check taskbar).

2. "npm is not recognized":
   Node.js is not installed on the laptop. Install it from nodejs.org.

3. "pip is not recognized":
   Python is not added to the system PATH. Reinstall Python and check "Add to PATH".

==============================================================================
Developed by: Muhammad Fawwad Siddiqui
==============================================================================
