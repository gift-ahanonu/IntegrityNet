# 🛡IntegrityNet

**AI-Powered Scam and Fraud Detection Platform**

IntegrityNet is a web-based platform that empowers users to detect and report scams using state-of-the-art AI. Leveraging GPT-4 and multi-modal input analysis, the system provides real-time detection, reporting tools, and educational support to combat online fraud and misinformation.

---

##  Features

-  **Scam Detection** – Uses a fine-tuned GPT-4 model to classify text and image content as safe, suspicious, or malicious.
-  **Multimodal Analysis** – Accepts both text and image input for richer, more accurate predictions.
-  **User Reporting System** – Allows users to submit suspicious content and receive instant analysis.
-  **Rate Limiting & Security** – Implements IP-based rate limiting and secure input sanitization.
-  **Admin Dashboard** – View trends, flagged content, and user reports.
-  **Real-time Feedback** – Immediate classification results using modern frontend design.

---

## Screenshots

<img width="1898" height="806" alt="Screenshot 2025-04-30 053811" src="https://github.com/user-attachments/assets/df100b16-c0da-46e7-afbf-9956c4d56a03" />
<img width="1237" height="619" alt="image" src="https://github.com/user-attachments/assets/22beacdf-7048-4735-915d-32b18e0d6bb5" />
<img width="1919" height="824" alt="Screenshot 2025-04-28 135954" src="https://github.com/user-attachments/assets/cc5d91a3-d5ae-4024-be9e-8f05c94eea98" />
<img width="736" height="676" alt="image" src="https://github.com/user-attachments/assets/c90e2cb7-91a2-409a-9c41-ba865c60c206" />
<img width="886" height="382" alt="image" src="https://github.com/user-attachments/assets/6bc815b8-1e06-4be1-a93f-bfb8ab0d87f8" />



---

## Tech Stack

| Layer     | Technology          |
|-----------|---------------------|
| Frontend  | React + Vite        |
| Backend   | Flask (Python)      |
| AI Model  | GPT-4 via OpenAI API |
| Database  | PostgreSQL / SQLite |
| Others    | JWT Auth, Flask-CORS, RateLimiter |

---

##  Installation (Local)

```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/IntegrityNet.git
cd IntegrityNet

# Backend Setup
cd backend
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
pip install -r requirements.txt
python app.py

# Frontend Setup (optional if using React)
cd ../frontend
npm install
npm start
````

---

## 👩‍💻 Author

**Gift Ahanonu**
[LinkedIn](https://www.linkedin.com/in/giftahanonu) · [giftahanonu@outlook.com](mailto:giftahanonu@outlook.com)
