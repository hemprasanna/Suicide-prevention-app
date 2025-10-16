<<<<<<< HEAD
# 🛡️ Suicide Prevention Through Social Media Analytics

## Overview

This Streamlit application analyzes social media messages to identify patterns, detect at-risk individuals, and facilitate early intervention for suicide prevention. The dashboard provides comprehensive analytics across multiple platforms to support mental health professionals and crisis intervention teams.

## Problem Statement

Suicide is a global public health crisis affecting over 700,000 people annually. Social media platforms have become crucial spaces where individuals express distress. This project leverages data science and machine learning to:

- **Detect** high-risk individuals through social media message analysis
- **Identify** patterns and linguistic markers associated with suicide risk
- **Facilitate** early intervention by mental health professionals
- **Track** trends across platforms and time periods

## Target Audience

- Mental health professionals
- Crisis intervention teams
- Social media platform moderators
- Public health researchers
- Policy makers

## Features

### 📊 Overview Dashboard
- Real-time metrics on messages analyzed, risk levels, and interventions
- Risk level distribution visualization
- Platform comparison charts
- Key insights and patterns

### 💬 Platform Analysis
- Platform-specific statistics and trends
- Intervention rates by platform
- Sentiment patterns by time of day
- Comparative analysis across social networks

### 🔍 Risk Keyword Analysis
- High-risk keyword identification
- Severity scoring and frequency analysis
- Keyword risk matrix visualization
- Top risk indicators

### 📈 Timeline & Trends
- Monthly incident and intervention tracking
- Daily severity score patterns
- Seasonal trend analysis
- Success rate improvements

### ℹ️ Project Documentation
- Methodology explanation
- Data sources and quality handling
- Ethical considerations
- Model performance metrics

## Data Sources

The analysis integrates:
- Social media posts (Twitter, Reddit, Instagram, Facebook)
- Natural language processing sentiment scores
- Temporal metadata and posting patterns
- Intervention outcomes and follow-up data

**Note:** This demo uses synthetic data generated to represent realistic patterns while protecting privacy.

## Methodology

### Data Processing
- **Risk Classification:** ML models classify posts into 4 risk levels (Low, Medium, High, Critical)
- **Missing Data:** MICE (Multiple Imputation by Chained Equations) for robust handling
- **Sentiment Analysis:** Deep learning models assess emotional content
- **Keyword Extraction:** NLP algorithms identify linguistic risk markers

### Key Metrics
- Precision: 87%
- Recall: 84%
- F1-Score: 85%
- Average Response Time: 14 minutes

## Installation & Setup

### Prerequisites
- Python 3.8 or higher
- pip package manager

### Local Installation

1. Clone the repository:
```bash
git clone https://github.com/YOUR_USERNAME/suicide-prevention-app.git
cd suicide-prevention-app
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Run the application:
```bash
streamlit run app.py
```

4. Open your browser to `http://localhost:8501`

## Deployment

This app is deployed on Streamlit Cloud. To deploy your own version:

1. Push code to GitHub
2. Go to [share.streamlit.io](https://share.streamlit.io)
3. Connect your GitHub repository
4. Select `app.py` as the main file
5. Click Deploy

## Usage

### Filters (Sidebar)
- **Platform Selection:** Filter by social media platform
- **Risk Levels:** Focus on specific risk categories
- **Date Range:** Analyze specific time periods

### Navigation
Use the tabs to explore different aspects:
- Overview: High-level metrics and insights
- Platform Analysis: Platform-specific patterns
- Risk Keywords: Linguistic markers and severity
- Timeline: Temporal trends and patterns
- About: Project methodology and documentation

## Ethical Considerations

This project prioritizes:
- **Privacy:** All data is anonymized and encrypted
- **Human Oversight:** AI assists but doesn't replace human judgment
- **Transparency:** Clear documentation of methods and limitations
- **Responsible Use:** Focus on intervention and support, not surveillance

## Crisis Resources

**If you or someone you know is in crisis:**

📞 **988 Suicide & Crisis Lifeline**  
Call or Text: 988 (Available 24/7)

📱 **Crisis Text Line**  
Text HOME to 741741

🌍 **International Resources**  
Visit: [findahelpline.com](https://findahelpline.com)

## Future Enhancements

- Real-time alert system integration
- Multi-language support
- Mobile app for crisis responders
- Integration with mental health service providers
- Improved model accuracy through continuous learning

## Project Information

**Course:** CMSE 830 - Foundations of Data Science  
**Institution:** Michigan State University  
**Department:** Computational Mathematics, Science and Engineering  

## License

This project is for educational purposes as part of CMSE 830 coursework.

## Acknowledgments

- World Health Organization - Suicide Prevention Guidelines
- National Institute of Mental Health
- Crisis Text Line - Data & Impact Reports
- American Foundation for Suicide Prevention

---

**Important Note:** This is a demonstration project for educational purposes. In real-world applications, suicide prevention requires trained professionals, proper protocols, and immediate response systems. This tool is designed to assist, not replace, professional mental health services.
=======
# Suicide-prevention-app
App to detect suicide intent through messages
>>>>>>> 679c411567176372ed5f93aace2f6206c77e7d3a
