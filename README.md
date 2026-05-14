# 📱 Social Media Post Analyzer using Generative AI

## 📌 Project Overview

The Social Media Post Analyzer is a Generative AI application that analyzes social media content and classifies it into structured categories such as:

* Tone
* Intent
* Communication Style
* Summary

The application uses Large Language Models (LLMs), Prompt Engineering, and Pydantic Output Parsing to generate accurate and structured responses from social media text inputs.

---

# 🚀 Features

✅ Analyze social media posts in real time
✅ Detect post tone automatically
✅ Identify communication intent
✅ Classify communication style
✅ Generate concise summaries
✅ Structured JSON output
✅ Interactive Streamlit UI
✅ Download analysis results as JSON
✅ Public deployment support

---

# 🛠 Technologies Used

* Python
* Streamlit
* LangChain
* Pydantic
* Groq / Google Gemini API
* Git
* GitHub

---

# 📂 Project Structure

```bash
social-media-post-analyzer/
│
├── app.py
├── main.py
├── model.py
├── parser.py
├── prompt.py
├── requirements.txt
├── README.md
├── .env
```

---

# ⚙️ Installation

## 1️⃣ Clone Repository

```bash
git clone https://github.com/yourusername/social-media-post-analyzer.git
```

## 2️⃣ Navigate to Project Folder

```bash
cd social-media-post-analyzer
```

## 3️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

---

# 🔑 Environment Variables

Create a `.env` file and add your API key.

For Groq:

```env
GROQ_API_KEY=your_api_key
```

For Gemini:

```env
GOOGLE_API_KEY=your_api_key
```

---

# ▶️ Run Application

```bash
python -m streamlit run app.py
```

---

# 📊 Example Input

```text
We are excited to launch our new AI-powered learning platform next week. Stay tuned for more updates!
```

---

# 📤 Example Output

```json
{
  "tone": "Positive",
  "intent": "Promotion",
  "communication_style": "Announcement",
  "summary": "The post announces an upcoming product launch in an enthusiastic and promotional tone."
}
```

---

# 🧠 Workflow

```text
User Input
    ↓
Prompt Template
    ↓
LLM Processing
    ↓
Pydantic Output Parsing
    ↓
Structured Response
    ↓
Streamlit Visualization
```

---

# 🌍 Deployment

The application can be deployed using:

* Streamlit Cloud
* Hugging Face Spaces
* Render
* Railway

---

# ⚠️ Challenges Faced

* Prompt formatting errors
* JSON parsing issues
* Deployment dependency conflicts
* API security handling
* Model deprecation updates

---

# 🔮 Future Improvements

* Multi-language support
* Emotion intensity analysis
* Social media API integration
* Advanced analytics dashboard
* Real-time monitoring
* PDF report generation

---

# 👩‍💻 Developed By

Nagaladoddi Mounika
