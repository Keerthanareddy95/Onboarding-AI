# Onboarding-AI 🤖
This Streamlit application utilizes GEMINI to facilitate an interactive onboarding process for a company named Amber AI. Users are guided through a series of questions, and their responses are stored in real-time.

## About Amber AI
Amber AI is an AI-driven solution enhancing customer success for SMBs, automating workflows, and boosting net revenue retention through personalized interactions and integration with existing CRM systems. https://www.helloamber.ai/

## Features of the Onboarding Bot 🚀
- Interactive Onboarding Process: Engage users with a personalized sequence of questions and responses.
- Real-time Response Storage: Store user responses in a CSV file (onboarding_data.csv) for future reference.
- Streamlit Integration: Utilizes Streamlit for creating a user-friendly web interface.

## Installation 🫧
### 1. Clone the repository:
```bash
git clone <repo_url>
```
### 2. Install dependencies:
```bash
pip install -r requirements.txt
```
### 3. Set up your environment variables:
- Create a .env file in the project root
- Add your Google API key:
```bash
GOOGLE_API_KEY="your_google_api_key"
```
Replace "your_google_api_key" with your actual Google API key.

## Usage 💬
Run the Streamlit application:

```bash
streamlit run app.py
```
