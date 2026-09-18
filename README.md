# AI-Productivity-Assistant
An AI-powered assistant that automates repetitive workplace tasks like resume writing, email drafting, and summarization using ChatGPT/Gemini. Built for the CAPACITI AI skills accelerator.
## Core Features

* **Email Generation:** Automatically drafts context-aware emails, replies, and follow-ups based on short user prompts.
* **Meeting Summarization:** Transcribes or processes meeting notes to extract action items, key decisions, and concise summaries.
* **Task Planning:** Intelligently schedules tasks, prioritizes daily to-do lists, and integrates with planning frameworks.
* **Research Assistance:** Scours documents or web data to synthesize summaries, find statistics, and answer deep-dive questions.
* **Chatbot Interaction:** A conversational interface allowing users to query data, trigger automations, and brainstorm in real-time.

## Key Expectations & Goals

* **Data Privacy:** Secure handling of user prompts and workplace data (no logging of sensitive credentials/API keys).
* **Reliability:** Low-latency responses for conversational chatbot elements and accurate parsing of meeting transcripts.
* **Extensibility:** A modular code structure making it simple to add new tools or switch LLM providers (e.g., OpenAI, Anthropic, or local models).

## Tech Stack & Prerequisites

* **Language:** Python 3.10+ / Node.js (Adjust based on your preference)
* **AI Framework:** OpenAI API / LangChain / Hugging Face
* **Environment Management:** Virtualenv / Conda

## Installation & Setup

1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd AI-Productive-Assistance
   ```

2. **Set up a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate # On Windows use: venv\Scripts\activate
   ```

3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure Environment Variables:**
   * Duplicate the `.env.example` file and rename it to `.env`.
   * Add your API keys securely inside the `.env` file:
     ```env
     OPENAI_API_KEY=your_secret_key_here
     ```

## Project Structure

```text
AI-Productive-Assistance/
├── src/
│ ├── agents/ # Chatbot logic and research assistants
│ ├── services/ # Email generation and text summarization engines
│ └── utils/ # Task planners and helper functions
├── tests/ # Unit and integration tests
├── .env.example # Example environment configuration template
├── .gitignore # Keeps API keys and node_modules/venv out of GitHub
├── README.md # Project documentation (You are here)
└── requirements.txt # Third-party dependencies
```
