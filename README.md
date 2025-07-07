# University Management System for Blind Students 👩‍🦯📚


An accessible and inclusive web-based platform designed to empower blind and visually impaired students in higher education by providing intuitive academic and administrative tools enhanced with assistive technologies.

![Homepage Screenshot](https://github.com/marinaredamekhael/AI-Powered-University-Management-Platform-for-the-Visually-Impaired/blob/main/img/img1.png)
![Homepage Screenshot](https://github.com/marinaredamekhael/AI-Powered-University-Management-Platform-for-the-Visually-Impaired/blob/main/img/img2.png)
![Homepage Screenshot](https://github.com/marinaredamekhael/AI-Powered-University-Management-Platform-for-the-Visually-Impaired/blob/main/img/img3.png)
---

## 🔍 Abstract

The **University Management System for Blind Students** is an intelligent, fully accessible, and inclusive web-based platform tailored for visually impaired students in higher education. It empowers students to independently manage their academic lives—from course enrollment to accessing lecture content, tracking performance, and receiving real-time updates—through a highly usable and screen-reader-friendly interface.

Built with modern technologies and assistive features, the platform combines a modular frontend (HTML, CSS, JavaScript with ARIA labels, keyboard support, high-contrast modes, and voice feedback) with a robust backend in TypeScript using Supabase for authentication, real-time updates, and data storage.

It integrates AI-powered tools such as:
- **BART-based PDF summarization**
- **Math OCR and symbolic expression reading**
- **Text-to-speech** interfaces

Additionally, it introduces **new feature pages** that further enhance interaction and inclusivity—such as Braille conversion, AI tutoring, and audio-based campus tours.

---

## 🚀 Key Features

### 🎓 Core Features

The University Management System for Blind Students provides an inclusive and accessible learning experience through a rich set of features designed with assistive technologies:

| Feature | Description |
|--------|-------------|
| 🔐 **Login / Authentication** | Secure login with role-based access for students, instructors, and admins. |
| 🏠 **Dashboard** | Overview of courses, grades, and announcements in a screen-reader-friendly format. |
| 📚 **Course Enrollment & Access** | Register for courses, access materials, and receive updates with text-to-speech integration. |
| 📝 **Lectures** | View and listen to lecture notes with summarization and voice support. |
| 📄 **PDF Summarization** | AI-generated summaries of long lecture PDFs using natural language processing. |
| ➗ **Math Reader** | Extract and convert math equations into audio-friendly formats for comprehension. |
| 📈 **Grades & Performance Tracking** | Real-time academic progress tracking with audio-based grade retrieval. |
| 📢 **Real-Time Announcements** | Instant university-wide updates presented via text and audio output. |
| 🗣️ **Voice Command Navigation** | Hands-free interface navigation through Web Speech API. |
| 📅 **Voice-Enabled Calendar** | Reminders and academic events delivered through voice prompts. |
| 🌐 **Multilingual Support** | Interface available in English, Arabic, and French for broader accessibility. |
| 📥 **Offline Mode** | Downloadable audio and summary content for offline study. |
| 🌙 **Dark & High-Contrast UI** | Customizable UI themes optimized for low-vision users. |
| 🤖 **AI Personalization (Planned)** | Adaptive feedback and content suggestions based on user activity. |
| 📲 **Mobile App (Planned)** | Mobile version to ensure on-the-go accessibility. |
| 💬 **Feedback System (Planned)** | Collect user suggestions to improve accessibility features continuously. |


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


##📚 Literature Review Table

| No. | Study / Source | Key Findings | Application to Our System |
|-----|----------------|--------------|----------------------------|
| 1 | [WGBH & NSF](https://www.wired.com/2000/12/disabled-need-tools-for-schools) | Emphasized the need for text descriptions, captions, and keyboard navigation for accessible education. | Adopted WCAG standards and keyboard shortcuts to improve accessibility. |
| 2 | [Schimmelpfeng & Ulbricht, 2021](https://www.intechopen.com/chapters/76384) | Early integration of accessibility using WAI-ARIA and gamification improves usability and inclusivity. | Implemented accessibility-first design and plans to add gamified features. |
| 3 | [Wesley College, Ghana](https://www.researchgate.net/publication/368029581) | Challenges included lack of Braille support and low digital literacy among visually impaired students. | Introduced offline access, audio-first navigation, and planned Braille export tools. |
| 4 | [Ugandan Universities Study](https://rsisinternational.org/journals/ijriss/articles/assessing-the-accessibility-and-inclusiveness-of-e-learning-systems-for-visually-impaired-students-in-selected-ugandan-universities-a-review) | Recommended structured HTML, screen reader support, and universal design learning (UDL). | Built with semantic HTML, screen-reader compatibility, and UDL principles. |
| 5 | [Beni Suef University](https://www.mdpi.com/2075-4698/14/12/255) | Cloud-based LMS solutions improved learning engagement among blind students. | System uses Supabase cloud backend for secure, scalable LMS functionality. |
| 6 | [Sultan Qaboos University](https://slejournal.springeropen.com/articles/10.1186/s40561-024-00358-x) | Peer collaboration and interactive platforms reduce accessibility barriers. | Planning peer-support community forums with voice and TTS support. |
| 7 | [Audio-Tactile Graphics Study](https://pubmed.ncbi.nlm.nih.gov/36433350) | Audio-tactile feedback enhances memory and understanding of math content. | Math OCR and speech engine help explain equations to blind students. |
| 8 | [Battle for Blindness](https://battleforblindness.org/accessible-learning-educational-tools-for-visually-impaired-students-learn-about-the-tool) | Mobile tools aid everyday tasks but lack structured academic support. | Designed for academic use with voice summaries, math support, and LMS integration. |
| 9 | [NVDA Screen Reader](https://en.wikipedia.org/wiki/NonVisual_Desktop_Access) | Open-source screen reader widely used in visually impaired communities. | UI fully compatible with NVDA, tested for keyboard and screen-reader navigation. |
| 10 | [Springer – UDL Framework](https://link.springer.com/chapter/10.1007/978-3-031-60049-4_12) | Universal Design for Learning enables equal access through multiple modes. | Follows UDL with multilingual support, TTS, visual/audio summaries, and adaptable UI. |

