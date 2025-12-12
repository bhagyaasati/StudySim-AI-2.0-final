<div align="center">
  <br />
  <div style="display: flex; justify-content: center; align-items: center; gap: 12px; padding-bottom: 10px;">
  
  <h1 style="margin: 0; font-size: 3rem; font-weight: 900; line-height: 1.2; padding-bottom: 5px; background: linear-gradient(to right, #2563EB, #9333EA, #DB2777); -webkit-background-clip: text; -webkit-text-fill-color: transparent;">StudySim AI</h1>
  </div>
  
  <p style="font-size: 1.2rem; color: #71717A; max-width: 600px; margin: 10px auto;">
    <b>Interactive learning for everyone.</b><br>
    Transform static content into active understanding with Generative Simulations.
  </p>

  <p>
    <a href="#-key-features">Features</a> •
    <a href="#-application-gallery">Gallery</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-getting-started">Get Started</a>
  </p>
  
  <br />
</div>

---

## 💡 About The Project

**StudySim AI** is not just another chatbot wrapper. It is a dedicated **Learning Architect** designed to transform passive study materials into active, interactive experiences.

By leveraging the multimodal capabilities of **Google Gemini 2.5 & 3.0**, StudySim analyzes your inputs—whether they are PDFs, lecture recordings, diagrams, or raw text—and constructs a structured learning plan. It then goes a step further by **writing and deploying custom HTML5 physics simulations** in real-time, allowing you to visualize and interact with the concepts you're learning.

Built with a stunning **Glassmorphism UI**, the application features a pill-shaped, rounded aesthetic that feels modern, fluid, and responsive across all devices.

---

## 🚀 Key Features

### 🧠 Context Architect
Unlike standard AI that jumps straight to an answer, StudySim employs a multi-stage pipeline (**Research** → **Plan** → **Draft** → **Code**). It deeply analyzes your topic to build a "Game Design Document" for your learning session before generating a single word of content.

### 🎮 Generative Simulators
The platform's flagship feature. StudySim automatically codes interactive **HTML5/Canvas physics engines** tailored to your specific topic. 
* *Studying Projectile Motion?* It builds a cannon simulator with gravity sliders.
* *Studying Economics?* It renders interactive supply/demand curves.
* **No coding required by the user.**

### ⚡ Multimodal Input
Learn from any source. The AI seamlessly synthesizes information from:
* 🎙️ **Audio:** Upload lecture recordings or voice notes.
* 📸 **Vision:** Snap photos of whiteboards or textbook diagrams.
* 📄 **Documents:** Parse PDFs, DOCX, and text files.

### 📝 Intelligent Notes & Quizzes
* **Deep Dive:** Comprehensive, LaTeX-formatted study guides.
* **Smart Assessment:** Adaptive quizzes that generate detailed explanations for every answer (correct or incorrect).
* **Export:** Download your mastery package as **PDF** or **DOCX**.

---

## 📸 Application Gallery

Explore the modern, dark-mode optimized interface of StudySim AI.

| **Immersive Landing Experience** | **The Study Architect** |
|:---:|:---:|
| ![Landing Page](https://github.com/user-attachments/assets/da668189-9a4e-4bc7-a3b8-8eab5bf8393f) | ![Architect Interface](https://github.com/user-attachments/assets/689c64b0-99ce-43f8-8076-caa0c84225bb) |

| **Real-Time Simulation** | **Interactive Quizzes** |
|:---:|:---:|
| ![Simulation Engine](https://github.com/user-attachments/assets/ec1bd2de-cf9d-48d7-a17d-d8a4e2ca893c) | ![Quiz Interface](https://github.com/user-attachments/assets/d54e9081-d839-423a-9134-08cf47dfc0b7) |

<div align="center">
  <br />
  <b>Full-Screen Deep Dive & Responsive Design</b>
  <br /><br />
  <img src="https://github.com/user-attachments/assets/8baaeafe-fea2-4af3-9e47-077408b5c08f" alt="Responsive Design" width="80%" style="border-radius: 16px; border: 1px solid #333;" />
</div>

---

## 🛠️ Tech Stack

* **Framework:** React 19 + Vite
* **Language:** TypeScript (ES2022)
* **AI Models:** Google Gemini 2.5 Flash & 3.0 Pro
* **Styling:** Tailwind CSS (Custom "Neo-Glass" Theme)
* **Math Rendering:** KaTeX
* **Export:** html2pdf.js

---

## 🏁 Getting Started

Follow these steps to run the architect locally.

### Prerequisites
* Node.js (v18 or higher)
* A Google Gemini API Key (Get one at [aistudio.google.com](https://aistudio.google.com))

### Installation

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/bhagyaasati/studysim-ai.git](https://github.com/bhagyaasati/studysim-ai.git)
    cd studysim-ai
    ```

2.  **Install dependencies**
    ```bash
    npm install
    ```

3.  **Configure Environment**
    Create a `.env.local` file in the root directory and add your API key:
    ```env
    GEMINI_API_KEY=your_api_key_here
    ```

4.  **Run the App**
    ```bash
    npm run dev
    ```

---

<div align="center">
  <p style="text-transform: uppercase; letter-spacing: 0.2em; font-size: 0.8rem; color: #71717A;">Visualized by</p>
  <h3 style="background: linear-gradient(to right, #06b6d4, #3b82f6, #9333ea); -webkit-background-clip: text; color: transparent; font-size: 1.5rem; margin-top: -10px; padding-bottom: 10px; line-height: 1.5;">Bhagya Asati</h3>
  
  <p>
    <a href="https://www.linkedin.com/in/bhagya-asati-7463a2379/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
    </a>
    &nbsp;
    <a href="https://github.com/bhagyaasati" target="_blank">
      <img src="https://img.shields.io/badge/GitHub-Connect-181717?style=for-the-badge&logo=github" alt="GitHub">
    </a>
  </p>
</div>
