# ✈️ AI Travel Agent

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python)
![ADK](https://img.shields.io/badge/Built%20With-Google%20ADK-orange?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Active-success?style=for-the-badge)

## 📖 Overview
**Travel_Agent** is an intelligent, autonomous agent designed to assist users in planning travel itineraries. Built using **Google's Agent Development Kit (ADK)**, this project demonstrates how to orchestrate GenAI workflows to solve multi-step reasoning tasks.

The agent takes natural language queries (e.g., *"Plan a 3-day trip to Paris on a budget"*) and generates structured travel plans, demonstrating the power of agentic workflows in real-world scenarios.

## ✨ Key Features
* **Agentic Workflow:** Utilizes the ADK framework to structure reasoning loops and decision-making processes.
* **Natural Language Processing:** Understands complex travel constraints like budget, dietary restrictions, and time preferences.
* **Modular Design:** Clean separation of agent logic (`agent.py`) making it easy to extend with new tools.
* **Python-Native:** Fully implemented in Python for easy integration and deployment.

## 🛠️ Tech Stack
* **Language:** Python
* **Framework:** [Google Agent Development Kit (ADK)](https://github.com/google/generative-ai-python)
* **Model:** Gemini Pro (via Google GenAI SDK)

## 🚀 Getting Started

### Prerequisites
Before running the agent, ensure you have the following:
1.  Python 3.10 or higher installed.
2.  A Google Cloud Project (if using Vertex AI) or a valid API Key for Gemini.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Dhineshkumar272005/Travel_Agent.git](https://github.com/Dhineshkumar272005/Travel_Agent.git)
    cd Travel_Agent
    ```

2.  **Create a virtual environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3.  **Install dependencies:**
    *(Note: Ensure you have the ADK and GenAI libraries installed)*
    ```bash
    pip install google-generativeai
    # Add other requirements here if you have a requirements.txt
    ```

4.  **Set up Environment Variables:**
    Create a `.env` file in the root directory and add your API keys:
    ```env
    GOOGLE_API_KEY=your_api_key_here
    ```

### 🏃‍♂️ Usage

To start the agent, simply run the main script:

```bash
python agent.py
