# 🌟 Nova AI - Your Ultimate Student Productivity Companion

![Nova AI Banner](./public/assets/banner.png)

[![React](https://img.shields.io/badge/React-19-61DAFB?logo=react&logoColor=black)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-8.0-646CFF?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Framer Motion](https://img.shields.io/badge/Framer--Motion-12.0-0055FF?logo=framer&logoColor=white)](https://www.framer.com/motion/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

**Nova AI** is a premium, AI-driven dashboard designed to transform the way students learn, organize, and excel. Built with a sleek glassmorphism aesthetic and powered by modern AI, it provides a unified hub for all your academic needs.

---

## ✨ Key Features

### 🤖 1. AI Assistant (Chat)
Engage in deep reasoning and problem-solving with a dedicated AI assistant. Perfect for clarifying complex concepts or brainstorming essay structures.

### 📝 2. Study Notes & Summarizer
Upload **PDF** or **DOCX** files and get instant, intelligent summaries. Nova AI extracts key takeaways so you can focus on learning, not just reading.

### 📅 3. Task Organizer
Stay on top of your deadlines with an integrated task management system. Categorize, prioritize, and track your progress through a clean, intuitive interface.

### 🌌 4. Immersive Glassmorphism UI
A stunning, responsive design with dynamic background blobs, smooth transitions, and a premium "glass" feel that makes studying visually engaging.

---

## 🛠️ Tech Stack

- **Frontend Core:** [React 19](https://react.dev/) & [Vite](https://vitejs.dev/)
- **Animations:** [Framer Motion](https://www.framer.com/motion/)
- **Icons:** [Lucide React](https://lucide.dev/)
- **Document Parsing:** [Mammoth](https://github.com/mwilliamson/mammoth.js) (DOCX) & [PDF.js](https://mozilla.github.io/pdf.js/)
- **Styling:** Modern Vanilla CSS with CSS Variables & Glassmorphism

---

## 🚀 Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) (v18.0.0 or higher)
- [npm](https://www.npmjs.com/) or [yarn](https://yarnpkg.com/)

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/navigate.git
   cd navigate
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Set up environment variables:**
   Create a `.env.local` file in the root directory and add your AI configuration:
   ```env
   VITE_AI_API_KEY=your_api_key_here
   VITE_AI_BASE_URL=https://api.example.com/v1
   VITE_AI_MODEL=gpt-4-turbo
   ```

4. **Start the development server:**
   ```bash
   npm run dev
   ```

5. **Build for production:**
   ```bash
   npm run build
   ```

---

## 📁 Project Structure

```text
navigate/
├── public/                 # Static assets
│   └── assets/             # Images and banners
├── src/
│   ├── components/         # React components (Sidebar, Chat, etc.)
│   ├── utils/              # Helper functions (AI, Parsing)
│   ├── App.jsx             # Main App entry
│   └── index.css           # Global styles & design system
├── .env.local              # Environment variables (secret)
├── package.json            # Dependencies & scripts
└── vite.config.js          # Vite configuration
```

---

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

---

<p align="center">
  Built with ❤️ for students everywhere.
</p>

