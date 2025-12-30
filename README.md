# Task 5: Auto Tagging Support Tickets Using LLM

## Objective
Build an intelligent support ticket classification system using Large Language Models (LLMs) with prompt engineering, comparing zero-shot vs few-shot learning approaches.

## Dataset
**Synthetic Support Tickets** (20 samples for demonstration)

**Categories**:
- Billing (payment issues, refunds, charges)
- Technical (bugs, crashes, errors)
- Account (login, password, settings)
- Shipping (delivery, tracking, damaged items)
- Feature Request (new features, integrations)
- Inquiry (general questions, information)
- Security (suspicious activity, 2FA)
- Urgent (immediate attention needed)



## 🛠️ Technologies Used

| Technology | Purpose | Free Tier |
|------------|---------|-----------|
| **Python 3.8+** | Programming | ✅ |
| **pandas/numpy** | Data processing | ✅ |
| **Google Gemini** | LLM API (recommended) | ✅ 60 req/min |



## 🚀 How to Run

### Prerequisites
```bash
# Base packages
pip install pandas numpy scikit-learn


pip install google-generativeai  # For Gemini

```



## Output Files
- `results.csv` - All predictions
- `metrics.json` - Performance metrics