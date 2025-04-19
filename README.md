
# 🧠 StackMate Ultra

StackMate Ultra is an AI-powered IT assistant designed to help helpdesk and MSP technicians troubleshoot issues faster and smarter.

This tool includes:

- 🔍 AI-powered ticket analysis with root cause, fix, user message, and internal notes
- 🧠 Context-aware recommendations (OS, domain joined, AV, etc.)
- 💻 PowerShell/CMD script generation
- 🔄 Alternate script suggestions
- 📚 Custom KB & internal script library (editable and downloadable)
- 🧾 Step-by-step troubleshooting instructions
- 📄 Export to TXT or download `.ps1` scripts

---

## 📦 Features

### 1. **Analyze Support Issues**
Feed in vague or detailed issue reports and get:
- Root cause explanation
- Fix + detailed script
- Alternate solutions
- Internal and user-friendly messaging

### 2. **Custom KB & Script Management**
- Save and organize internal how-tos, scripts, or notes
- Easily download saved scripts as `.ps1`
- Persisted via CSV locally (future upgrade: database or shared repo)

---

## 🚀 Getting Started

### 1. Clone the repo or download this ZIP

### 2. Set up your environment:

```bash
cd stackmate-ultra-github-version
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
```

### 3. Add your API key:
Create a `.env` file at the root with this line:

```env
OPENROUTER_API_KEY=your-openrouter-key-here
```

### 4. Launch the app:

```bash
streamlit run main.py
```

---

## 🧠 Powered By
- OpenRouter + LLaMA3
- Streamlit
- Python + dotenv + pandas

---

## 🛠 Future Ideas
- GitHub-based syncing for scripts
- KB categories or tags
- Slack/Teams integration
- Endpoint-side agent

---

Built by [Alexandra Mckinnon](https://github.com/alexandrafaith2)
