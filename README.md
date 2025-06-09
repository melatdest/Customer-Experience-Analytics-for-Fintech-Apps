
---

## ✅ Tasks Summary

### ✅ Task 1: Scraping and Preprocessing
- Scrape 400+ reviews per bank using `google-play-scraper`.
- Clean text, normalize dates, remove duplicates.
- Store as a CSV with columns: `review`, `rating`, `date`, `bank`, `source`.

### ✅ Task 2: Sentiment & Theme Analysis
- Use `distilbert-base-uncased-finetuned-sst-2-english`, VADER, or TextBlob.
- Identify themes using TF-IDF, spaCy, or topic modeling.
- Group keywords into 3–5 themes per bank.

### ✅ Task 3: Store in Oracle DB
- Create `bank_reviews` DB and insert processed reviews.
- Design schema with `banks` and `reviews` tables.

### ✅ Task 4: Insights & Visualization
- Derive 2+ satisfaction drivers and pain points.
- Create 3–5 visualizations (e.g., sentiment trends, word clouds).
- Summarize findings in a final PDF report.

---

## 🛠️ Installation

```bash
# Clone the repo
git clone https://github.com/melatdest/Customer-Experience-Analytics-for-Fintech-Apps.git
cd Customer-Experience-Analytics-for-Fintech-Apps

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies
pip install -r requirements.txt
