# AI Mock Interview App

## 📌 Project Overview
This is a Full Stack AI-powered Mock Interview App built using **Next.js**, **Drizzle ORM**, and **Google Gemini AI**. The app enables users to simulate interviews, record responses via speech-to-text, and receive AI-generated feedback.

## 🚀 Features
- **Drizzle ORM Setup**: PostgreSQL integration for structured data management.
- **User Authentication**: Secure user model with email and password.
- **Database Synchronization**: Ensures consistency between models and tables.
- **Gemini AI Integration**: Generates interview questions and provides feedback.
- **Speech-to-Text Recording**: Allows users to record and review answers.
- **Data Storage & Retrieval**: Saves responses and feedback for progress tracking.
- **Vercel Deployment**: Streamlined deployment with environment variable management.

## 📂 Tech Stack
- **Frontend**: Next.js (React framework for SSR & ISR)
- **Backend**: Drizzle ORM, PostgreSQL
- **AI Model**: Google Gemini AI
- **Deployment**: Vercel

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```sh
git clone <repo-url>
cd <project-folder>
```

### 2️⃣ Install Dependencies
```sh
npm install
```

### 3️⃣ Run the Development Server
```sh
npm run dev
```
Your application should now be running at `http://localhost:3000`.

## 📜 Environment Variables
Create a `.env.local` file in the root directory and add the following:
```env
DATABASE_URL=your_postgresql_connection_string
GEMINI_API_KEY=your_google_gemini_api_key
NEXT_PUBLIC_SITE_URL=http://localhost:3000
```

## 🚀 Deployment
Deploy the app to Vercel by running:
```sh
vercel
```
Make sure to set the environment variables in Vercel's dashboard.

## 📌 Key Insights
- **Drizzle ORM Setup**: Ensures seamless database operations and model synchronization.
- **User Model**: Provides structured data storage and authentication.
- **AI Integration**: Enhances user experience with AI-generated interview questions.
- **Speech-to-Text**: Improves accessibility and interactive engagement.
- **Data Persistence**: Enables long-term tracking of user performance.
- **Vercel Deployment**: Enables smooth CI/CD workflows.

## 🤝 Contributing
Feel free to open issues or submit pull requests for improvements.

## 📜 License
This project is licensed under the MIT License.

---

Happy Coding! 🚀
