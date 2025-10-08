Finsecure AI – An AI Powered Loan Approval Bot
🚀 Prototype submission for the OpenAI x NxtWave Buildathon > Developed by: Team BitSquad VIT

📌 Problem Statement
In the BFSI (Banking, Financial Services, and Insurance) sector, the loan approval process is often time-consuming, error-prone, and vulnerable to fraud. This is because most document verification is still performed manually by loan officers.

Documents such as Aadhaar, PAN, salary slips, and bank statements need to be meticulously verified for authenticity and eligibility. These manual checks not only delay the entire process but also negatively impact transparency and the overall customer experience.

💡 Our Solution
We have built Finsecure AI, an AI-powered loan approval assistant designed to automate and secure the entire workflow. Our system:

🤖 Uses OCR (Optical Character Recognition) to instantly extract data from applicant documents.

🔍 Validates KYC documents in real-time against the bank's master database to detect fraud and ensure authenticity.

⚡️ Applies an AI-driven financial model to approve or reject applications in seconds, not days.

📝 Maintains a secure audit trail by logging all applications, ensuring transparency and explainability of decisions.

🧩 Is built to be scalable, allowing for easy integration with production banking systems and more powerful OCR APIs.

Note on the Prototype: For this hackathon, we have focused on Aadhaar and PAN verification using the Tesseract OCR engine. The final, production-ready product is designed to integrate with robust tools like Google Cloud Vision API, Microsoft Azure AI Vision, or AWS Textract to support a full range of financial documents (salary slips, bank statements, etc.) with the highest accuracy.

⚙️ Technology Stack
Backend: Python, FastAPI, Tesseract OCR, MySQL

Frontend: JavaScript, React, Vite

Database: MySQL 8.0+

✅ Prerequisites
Before running this project locally, make sure you have the following installed on your system:

Python (version 3.9 or higher)

MySQL Server (version 8.0 or higher)

Node.js (version 18 or higher) and npm

Tesseract OCR Engine (must be installed and added to your system's PATH)

Git

🎥 Demo Video
You can watch a detailed video and photos demonstration of our project here:
https://drive.google.com/drive/folders/1SP8j-EhHSe437e6djbYTF__OtZB-gC4p

🚀 How to Run Locally
Follow these instructions to set up and run the project on your machine.

1. Clone the Repository
git clone <your-repository-url>
cd <your-repository-folder>

2. Configure the Backend
Navigate to the backend directory:

cd backend

Open the main.py file and update your MySQL database credentials:

DB_HOST = "localhost"
DB_USER = "YOUR_USERNAME" # e.g., "root"
DB_PASSWORD = "YOUR_PASSWORD" # e.g., "1234"

Install the required Python packages:

pip install -r requirements.txt

Start the backend server:

uvicorn main:app --reload --host 0.0.0.0 --port 8000

✅ Your backend will now be running on http://localhost:8000

3. Configure the Frontend
Open a new terminal and navigate to the frontend directory:

cd frontend

Install the necessary npm packages:

npm install

Start the frontend development server:

npm run dev

✅ Your frontend will now be running on http://localhost:5173

4. Access the Application
Open your web browser and navigate to the frontend URL:
👉 http://localhost:5173/

