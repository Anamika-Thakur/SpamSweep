# SpamSweep
Multi-Domain Threat Detection using Machine Learning. 
It intelligently scans and classifies:

📧 Emails to detect phishing or fraudulent content

💬 SMS messages to identify spam or scam attempts

🔗 URLs to detect malware, phishing pages, defacements, and other malicious threats

The goal is to safeguard users from social engineering attacks, fake websites, and unsolicited messages by providing instant and accurate predictions based on pre-trained ML models.

With its clean UI and modular backend, SpamSweep brings real-time threat assessment right to your browser - no bluff.


## 🔍 Features

- 📧 Classifies **emails** as spam or legitimate
- 💬 Detects **SMS** spam and promotional abuse
- 🔗 Identifies **malicious URLs** such as phishing, defacement, or malware
- 🎯 Clean UI with quick results
- 🧠 Pre-trained ML models using Logistic Regression, Multinomial Naive Bayes, and XGBoost

---

##  Tech Stack

| Layer       | Technology Used        |
|-------------|------------------------|
| **Frontend** | HTML5, CSS3 (vanilla) |
| **Backend**  | Python, Flask         |
| **ML Models**| scikit-learn, XGBoost |
| **Persistence** | Pickle `.pkl` files |
| **Deployment** | Render.com          |

---



##  Deployment on Render

You can deploy this app for free using [Render](https://render.com):

1. **Push to GitHub**: Upload your complete `SpamSweep` folder to a public/private repo.
2. **Create a Web Service** on Render:
   - Runtime: Python 3
   - Start Command:  
     ```
     gunicorn app:app
     ```
3. **Add your build files**:
   - `requirements.txt` (see below)
   - Flask and all `.pkl` model files
4. **Wait for deployment** and access your hosted site.

---


Make sure you have all the requiremnets. Install locally with:

```bash
pip install -r requirements.txt
```

