# Simple Sentiment Analyzer Website

This is a simple web app that takes a product review and instantly classifies it as Positive, Negative, or Neutral using a pre-trained Transformer model.

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/sentiment-analyzer.git
    cd sentiment-analyzer
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Run the server:
    ```bash
    uvicorn app.main:app --reload
    ```

4. Visit `http://127.0.0.1:8000/` in your browser.

---

> **Deploy on Render/Heroku/Vercel** by connecting your GitHub repo and setting up Python + `uvicorn` as server command.

---
