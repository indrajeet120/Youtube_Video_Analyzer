# 🎥 AI YouTube Video Analyzer

An AI-powered YouTube Video Analyzer built with Streamlit, Agno, and Groq. This application analyzes YouTube videos and generates detailed summaries, timestamps, topic breakdowns, and key learning points automatically.

## 🚀 Features

* Analyze any public YouTube video using its URL
* Generate detailed video summaries
* Create meaningful timestamps for important sections
* Identify major topics and content structure
* Highlight key learning points
* AI-powered analysis using Groq LLM
* Clean and interactive Streamlit UI

## 🛠️ Tech Stack

* Python
* Streamlit
* Agno Framework
* Groq LLM (Qwen 3 32B)
* YouTube Tools
* Python Dotenv

## 📂 Project Structure

```text
youtube_video_analyzer/
│
├── ui.py
├── youtube_analyzer.py
├── requirements.txt
├── .env
└── README.md
```

## ⚙️ Installation

### 1. Clone the Repository

```bash
git clone https://github.com/indrajeet120/Youtube_Video_Analyzer.git
cd Youtube_Video_Analyzer
```

### 2. Create Virtual Environment

```bash
python -m venv venv
```

Activate the environment:

Windows:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

## 🔑 Environment Variables

Create a `.env` file in the project root:

```env
GROQ_API_KEY=your_groq_api_key
```

## ▶️ Run the Application

```bash
streamlit run ui.py
```

The application will start locally and open in your browser.

## 📸 How It Works

1. Enter a YouTube video URL.
2. Click **Analyze Video**.
3. The AI extracts video information and content.
4. A detailed report is generated including:

   * Video Overview
   * Topic Breakdown
   * Timestamps
   * Key Insights
   * Learning Points

## Example Video URL

```text
https://www.youtube.com/watch?v=VIDEO_ID
```

## 🌐 Deployment

This project can be deployed on:

* Streamlit Community Cloud
* Render
* Railway
* AWS
* Azure

For Streamlit Cloud, add your secret:

```toml
GROQ_API_KEY="your_groq_api_key"
```

under **App Settings → Secrets**.

## 👨‍💻 Author

**Indrajeet Yadav**

B.Tech (Electronics Engineering)

Dr. Ambedkar Institute of Technology for Handicapped, Kanpur

## 📜 License

This project is open-source and available under the MIT License.
