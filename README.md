# 🛡️ SourceShield - AI News Analysis Tool

**Detect bias, analyze sentiment, and classify facts vs opinions in news articles using advanced AI**

<img width="1919" height="888" alt="Screenshot 2025-08-22 172358" src="https://github.com/user-attachments/assets/6dbb4a94-eb28-4980-bd78-7cee2924a61b" />
<img width="1909" height="898" alt="Screenshot 2025-08-22 172442" src="https://github.com/user-attachments/assets/f3b2af98-0fb0-4901-90f7-167b116acf15" />



---

## 🎯 What it Does

SourceShield analyzes news articles and provides:
- **✅ Fact vs Opinion Classification** - Distinguishes factual statements from opinions
- **⚖️ Bias Detection** - Identifies political and emotional bias
- **📊 Sentiment Analysis** - Determines positive/negative tone
- **🤖 AI Insights** - Advanced analysis using OpenAI GPT
- **📈 Multi-source Comparison** - Compare different news outlets

---

## 📱 Screenshots

### Dashboard Overview
![Dashboard](<img width="1919" height="897" alt="Screenshot 2025-08-22 172448" src="https://github.com/user-attachments/assets/e0258625-2d39-4938-a4a5-bf29548beff9" />
)
*Main analysis interface with 4 comprehensive tabs*

### Analysis Results
![Results](<img width="1907" height="892" alt="Screenshot 2025-08-22 172455" src="https://github.com/user-attachments/assets/ae763db4-b931-4a8e-8aed-f360e0a9a0d2" />
)
*Detailed breakdown of fact vs opinion classification*

### Bias Detection
![Bias](<img width="1919" height="912" alt="Screenshot 2025-08-22 172506" src="https://github.com/user-attachments/assets/052b8408-ac5c-4725-99b9-fa3e083a8de6" />
)
![Bias](<img width="1913" height="874" alt="Screenshot 2025-08-22 172513" src="https://github.com/user-attachments/assets/e77e39f7-2ddc-4c05-b915-dbd34fbb0742" />
 )
 ![Bias](<img width="1919" height="902" alt="Screenshot 2025-08-22 172520" src="https://github.com/user-attachments/assets/8fcc02db-aab7-481e-b652-0dd88a082d71" />)
 ![Bias](<img width="1915" height="891" alt="Screenshot 2025-08-22 172542" src="https://github.com/user-attachments/assets/c7f37e5e-fa30-4da6-95e4-3f4d836c4f47" />



)
*Political and emotional bias visualization*

### AI Analysis
![AI Analysis](<img width="1916" height="905" alt="Screenshot 2025-08-22 172535" src="https://github.com/user-attachments/assets/3c8bf5f7-ccda-49d0-b810-eb95c96a7849" />
)
*Advanced insights from OpenAI GPT*

---

##  Quick Demo

**Input Article:**
> "The GDP grew by 7.2% according to RBI data. This is amazing news for investors!"

**SourceShield Analysis:**
- **Fact vs Opinion:** 50% Factual, 50% Opinion
- **Sentiment:** Positive (78% confidence)
- **Political Bias:** Neutral
- **Emotional Bias:** Moderately Emotional
- **AI Insight:** *"Factual economic data with positive editorial framing"*

---

## ⚡ Installation & Setup

### Prerequisites
- Python 3.8+
- MongoDB (local or cloud)
- OpenAI API key (optional)

### 1. Clone Repository
```bash
git clone https://github.com/yourusername/sourceshield.git
cd sourceshield
```

### 2. Install Dependencies
```bash
# Create virtual environment
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# Install packages
pip install -r requirements.txt

# Download NLTK data
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords'); nltk.download('wordnet')"
```

### 3. Configure Environment
Create `.env` file:
```env
OPENAI_API_KEY=sk-proj-your-api-key-here
MONGODB_URI=mongodb://localhost:27017/
```

### 4. Run Application
```bash
streamlit run app/main.py
```

**Open:** http://localhost:8501

---

## 🔧 Tech Stack

| Component | Technology |
|-----------|------------|
| **Frontend** | Streamlit |
| **AI Analysis** | OpenAI GPT-3.5 |
| **NLP Models** | HuggingFace Transformers |
| **Database** | MongoDB |
| **Web Scraping** | Newspaper3k |
| **Similarity** | Sentence Transformers |

---

## 🎮 How to Use

### Option 1: URL Analysis
1. Paste news article URL
2. Click "Analyze Article"
3. View results in 4 tabs

### Option 2: Direct Text
1. Copy-paste article content
2. Click "Analyze Text"
3. Get comprehensive analysis

### Option 3: Multi-Source Comparison
1. Add multiple news sources
2. Compare bias and perspectives
3. Identify factual consistency

---

## 📊 Features

- **🔍 Content Extraction** - Automatic article parsing
- **📈 Real-time Analysis** - Results in under 20 seconds
- **💾 Historical Storage** - MongoDB for trend tracking
- **📱 Interactive Dashboard** - Beautiful Streamlit interface
- **🤖 AI-Powered** - Advanced GPT-based insights
- **⚡ Parallel Processing** - Multiple analysis methods simultaneously

---

## 🚨 Quick Troubleshooting

### Common Issues:
```bash
# MongoDB not running
sudo systemctl start mongod

# Missing dependencies
pip install lxml_html_clean

# OpenAI API issues
# Check your API key in .env file
```

### Social Media URLs:
- Twitter/X URLs don't work directly
- **Solution:** Copy tweet text and use "Direct Text" option

---

## 📈 Example Output

```
Analysis Results:
├── Fact Percentage: 65%
├── Opinion Percentage: 35%
├── Sentiment: Positive (0.82)
├── Political Bias: Neutral (0.71)
├── Emotional Bias: Moderate
└── AI Analysis: "Balanced reporting with slight positive framing"
```

---

## 🎯 Use Cases

- **📰 Journalists** - Source credibility verification
- **🎓 Students** - Media literacy education
- **🔬 Researchers** - Content analysis studies
- **👥 General Public** - News fact-checking

---

## 🤝 Contributing

1. Fork the repository
2. Create feature branch: `git checkout -b feature-name`
3. Make your changes
4. Submit pull request

---

## 📄 License

MIT License - feel free to use for educational and commercial purposes.

---

<div align="center">

**⭐ Star this repo if you find it useful!**

[📖 Full Documentation](docs/) • [🐛 Report Issues](issues/) • [💬 Discussions](discussions/)

</div>
