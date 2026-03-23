# Emergency AI Triage

This project explores the application of AI to support initial patient assessment in emergency scenarios. It serves as a prototype for a clinical decision support tool, aiming to demonstrate how AI can help structure and prioritize information during critical first-contact evaluations.

## Key Features
*   AI-powered symptom analysis and initial acuity scoring.
*   Structured data capture for presenting complaints and vital signs.
*   Generates a summary report for handoff to medical professionals.
*   Designed for rapid, intuitive use in high-pressure environments.

## Tech Stack
*   Python
*   FastAPI
*   OpenAI API (or similar LLM service)
*   Pydantic

## Getting Started
1.  Clone the repository: `git clone https://github.com/zoreanuj/emergency-ai-triage.git`
2.  Install dependencies: `pip install -r requirements.txt`
3.  Set your API key: `export OPENAI_API_KEY='your-key'`
4.  Run the server: `uvicorn main:app --reload`