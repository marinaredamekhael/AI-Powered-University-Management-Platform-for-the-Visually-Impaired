# University Management System for Blind Students 👩‍🦯📚

An accessible and inclusive web-based platform designed to empower blind and visually impaired students in higher education by providing intuitive academic and administrative tools enhanced with assistive technologies.

---

## 🔍 Abstract

The **University Management System for Blind Students** is a specialized solution developed to enhance accessibility and autonomy for visually impaired learners in university settings. Built using **TypeScript (backend)**, **Supabase (database)**, and a screen reader-friendly **HTML/CSS/JavaScript (frontend)**, the system allows students to manage academic tasks independently through voice assistance and text-to-speech capabilities.

It integrates AI-powered tools such as:
- **BART-based PDF summarization**
- **Math OCR and symbolic expression reading**
- **Text-to-speech** interfaces

Additionally, it introduces **new feature pages** that further enhance interaction and inclusivity—such as Braille conversion, AI tutoring, and audio-based campus tours.

---

## 🚀 Key Features

### 🎓 Core Features
- 🔐 **Login / Authentication**
- 🏠 **Dashboard** – Summary of courses, grades, and updates
- 📚 **Courses** – View and enroll in available subjects
- 📝 **Lectures** – Access lecture materials in audio/text format
- 📄 **PDF Summarization** – Auto-summarize lecture notes using `facebook/bart-large-cnn`
- ➗ **Math Reader** – Convert math equations to speech using OCR + SymPy
- 📈 **Grades** – Track academic performance
- 📢 **Announcements** – Hear real-time university updates
- 👤 **Profile Settings** – Manage user information and preferences

---

### 🆕 Innovative Accessibility Pages

| Page | Description |
|------|-------------|
| **🧠 AI Tutor Assistant** (`/ai-tutor`) | Voice-activated AI support for academic help |
| **🧭 Virtual Campus Tour** (`/campus-tour`) | Audio-guided, keyboard-navigable campus walkthrough |
| **📅 Study Planner & Goal Tracker** (`/goals`) | Schedule studies, track goals with audio prompts |
| **💬 Peer Support Forum** (`/community`) | A voice-enabled space for Q&A and social interaction |
| **⠕ Braille Converter** (`/braille-converter`) | Convert PDFs or text into Braille (Unicode/BRF download) |

All new features include:
- ✅ Voice command support
- ✅ Text-to-speech output
- ✅ Integration with existing user authentication

---

## 🧩 System Architecture

- **Frontend**: HTML, CSS, JavaScript with ARIA roles and keyboard navigation
- **Backend**: TypeScript (modular routing, RESTful API)
- **Database**: Supabase (real-time updates, scalable)
- **Python Integration**:
  - `summarizer.py`: Lecture summarization using BART
  - `pdfextract.py`: Math OCR + natural language translation
- **Speech Output**: Converts text and equations to spoken audio

---

## 🛠 Technologies Used

| Stack | Tech |
|-------|------|
| Frontend | HTML, CSS, JavaScript |
| Backend | TypeScript |
| Database | Supabase |
| AI/ML | BART Transformer (Hugging Face) |
| OCR & Math | PyMuPDF, texify, SymPy |
| Audio | pyttsx3 / gTTS for speech synthesis |

---


## 🔮 Future Enhancements

- 📱 **Mobile App** version with voice control
- 📊 **Analytics Dashboard** for learning progress
- 🤖 **AI Personal Agent** for reminders and scheduling
- 🎙️ **Voice-based form submission** for assignments
- 🧪 **Adaptive Learning** based on user performance

