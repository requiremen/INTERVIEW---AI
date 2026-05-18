# Interview AI - Smart Interview Preparation Platform

An AI-powered platform designed to help candidates prepare for interviews by analyzing job descriptions and their own profiles (resumes or self-descriptions). It generates personalized interview reports, including technical and behavioral questions, preparation roadmaps, and even tailored resumes.

## 🚀 Features

- **Personalized Interview Plan**: Analyze job descriptions against your profile to generate a custom preparation strategy.
- **AI-Generated Questions**: Receive targeted technical and behavioral questions with model answers and interviewer intentions.
- **Match Score**: Get an instant assessment of how well your profile aligns with the job requirements.
- **Preparation Roadmap**: A structured, day-by-day plan to bridge skill gaps and prepare effectively.
- **Resume Tailoring**: Automatically generate a professional, ATS-friendly resume tailored to a specific job description.
- **PDF Export**: Download your AI-generated resume as a high-quality PDF.

## 🛠️ Tech Stack

### Frontend
- **React 19** with **Vite**
- **React Router 7** for navigation
- **Sass** for advanced styling
- **Axios** for API communication

### Backend
- **Node.js** with **Express 5**
- **MongoDB** with **Mongoose**
- **Google Gemini AI** (gemini-3-flash-preview) for intelligent analysis
- **Puppeteer** for high-fidelity PDF generation
- **Zod** for schema validation and structured AI responses
- **Multer** for file uploads (resumes)
- **JWT & Bcryptjs** for secure authentication

## 🏁 Getting Started

### Prerequisites
- Node.js (v18 or higher recommended)
- MongoDB (local or Atlas)
- Google Gemini API Key

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/requiremen/INTERVIEW---AI.git
   cd INTERVIEW---AI
   ```

2. **Backend Setup**:
   ```bash
   cd Backend
   npm install
   ```
   Create a `.env` file in the `Backend` directory:
   ```env
   PORT=3000
   MONGO_URI=your_mongodb_uri
   JWT_SECRET=your_secret_key
   GOOGLE_GENAI_API_KEY=your_gemini_api_key
   ```
   Start the backend:
   ```bash
   npm run dev
   ```

3. **Frontend Setup**:
   ```bash
   cd ../Frontend
   npm install
   ```
   Start the frontend:
   ```bash
   npm run dev
   ```

## 📂 Project Structure

- `Backend/`: Express server, AI services, and database models.
- `Frontend/`: React application with modular feature-based architecture.

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## 📄 License

This project is licensed under the ISC License.
