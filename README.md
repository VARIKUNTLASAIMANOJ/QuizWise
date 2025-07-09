# 🎯 QuizWise

**QuizWise** is a full-stack quiz platform that enables users to create, manage, and take interactive quizzes with a modern UI and real-time backend logic. Built with Python, TypeScript, TailwindCSS, and Vite, it provides an intuitive and scalable solution for educational or entertainment-based quizzes.

---

## 🚀 Features

- 🧠 Create and take custom quizzes
- 🔒 Secure backend with environment configuration
- 🌐 Full-stack React + Python app
- 🎨 Sleek UI with Tailwind CSS
- ⚡️ Vite-powered frontend with React
- 📁 File handling support (`uploads/`)
- 🌍 Google API's Integration

---

## 🛠️ Tech Stack

### Frontend
- React
- Tailwind CSS
- Vite

### Backend
- Python 3.x
- FastAPI
- Google API Services (Script)
- dotenv for secure environment configs

---

## 📁 .env Configuration (Backend)

Create a `.env` file in the root directory of your backend with the following variables:

```env
GOOGLE_API_KEY="your-google-api-key"
GOOGLE_SCRIPT_URL="your-google-script-url"
GOOGLE_SERVICE_ACCOUNT_FILE="your-google-service.json"
````

---

## 📦 Project Structure

```
QuizWise/
├── main.py                  # Backend entry point
├── requirements.txt         # Python dependencies
├── .env                     # Backend environment variables
├── service_account.json     # Google Firebase credentials
├── frontend/                # Vite + React TypeScript frontend
│   ├── src/                 # Main React codebase
│   ├── index.html
│   ├── package.json
│   ├── tailwind.config.js
│   └── vite.config.ts
└── uploads/                 # Static upload folder
```

---

## 🔧 Installation

### Backend (Python)

```bash
# Navigate to backend root
cd QuizWise

# Create virtual environment
python -m venv .venv
source .venv/bin/activate  # or `.venv\Scripts\activate` on Windows

# Install dependencies
pip install -r requirements.txt

# Ensure your .env file is set correctly
```

### Frontend (React + Vite)

```bash
# Navigate to frontend
cd frontend

# Install Node dependencies
npm install

# Run development server
npm run dev
```

---

## 🧪 Usage

1. Start the backend server:

   ```bash
   python main.py
   ```

2. Run the frontend:

   ```bash
   cd frontend
   npm run dev
   ```

3. Visit the app at: [http://localhost:8000](http://localhost:8000)

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

---

## 📜 License

This project is licensed under the **MIT License**. See `LICENSE` for details.

---

## 👨‍💻 Author

**VARIKUNTLA SAI MANOJ**
📎 [GitHub Profile](https://github.com/VARIKUNTLASAIMANOJ)
