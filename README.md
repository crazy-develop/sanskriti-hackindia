# 🚀 Suvidha Career Compass | Sanskriti HackIndia 2026

**Suvidha Career Compass** is a comprehensive AI-powered educational platform designed to empower students in their academic and professional journey. From finding the right colleges to solving complex academic problems instantly, this platform acts as a personal digital mentor.

---

## ✨ Key Features

### 1. 🧠 Suvidha-AI Question Solver (Scan & Solve)
The crown jewel of our project. It's an intelligent scanner that recognizes handwritten or printed academic questions and provides instant, step-by-step solutions.
- **Multimodal Input:** Upload a photo, scan from the camera, or type the question directly.
- **Regional Intelligence:** Solutions are provided in a mix of Hindi and English (Hinglish) for better conceptual clarity.
- **Advanced Engine:** Built on the Google Gemini 1.5 Flash engine for high-speed and accurate mathematical/logical reasoning.

### 2. 🏛️ Smart College & School Directory
A curated database of educational institutions in Jammu & Kashmir (Rajouri, Budhal, etc.).
- **Comparison Engine:** Compare two or more colleges based on fees, accreditation (NAAC), facilities, and streams offered.
- **Detailed Profiles:** View infrastructure, faculty, and stream details for individual colleges.

### 3. 💼 Opportunity Hub (Jobs & Internships)
Integrated with the **Jooble API** to provide real-time job and internship listings.
- **Tailored Search:** Students can search for roles specifically in the IT, Science, or Arts sectors.
- **Career Pathways:** Maps required skills for various job roles.

### 4. 🎨 Modern & Premium UI
The entire platform is built with a focus on user experience.
- **Responsive Design:** Works flawlessly on mobile, tablets, and desktops.
- **Glassmorphic Aesthetics:** Uses modern translucent effects and vibrant gradients for a premium feel.

---

## 🛠️ Tech Stack

### Frontend & UI
- **Core:** HTML5, CSS3 (Vanilla), JavaScript (ES6+).
- **Framework:** React + Vite (for the standalone Intelligence Engine).
- **Styling:** Custom CSS with Glassmorphic tokens, Tailwind CSS (for some sub-modules).
- **Icons:** Lucide-React.

### AI & Backend
- **AI Brain:** Google Gemini 1.5 API (Probing v1 and v1beta endpoints).
- **Backend:** Python Flask (Server-side processing and CORS management).
- **Deployment-Ready:** Integrated local dev servers for rapid demonstration.

---

## 🚀 Getting Started

### Prerequisites
- Node.js (for the AI Engine)
- Python 3.10+ (for the Backend)

### Installation & Demo Setup

1. **Clone the Repo:**
   ```bash
   git clone https://github.com/crazy-develop/sanskriti-hackindia.git
   cd sanskriti-hackindia
   ```

2. **Start the AI Engine (Vite):**
   ```bash
   cd HACATHON-MATHURA
   npm install
   npm run dev
   ```
   *The engine will run on http://localhost:3000*

3. **Start the Python Backend (Optional):**
   ```bash
   python app.py
   ```
   *The backend will run on http://localhost:5000*

4. **Launch the Main Platform:**
   Simply open `index.html` in your browser.

---

## 🛡️ Security & Scalability
- **API Management:** Centralized configuration through `js/config.js`.
- **Error Handling:** Robust multi-endpoint fallback system to ensure the AI never stops working.
- **Data Driven:** Scalable directory structure for adding more districts and institutions.

---

## 👥 Meet the Team
**Sanskriti HackIndia 2026 - Hackathon Mathura Participation**

Developed with ❤️ by the team at **Suvidha**.
