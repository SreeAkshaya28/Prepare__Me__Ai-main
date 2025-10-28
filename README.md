# 🌌 Prepare_Me_AI: AI-Powered Teacher Assistant 🌌

Welcome to *Prepare_Me_AI*, an innovative AI-driven teacher assistant developed by Team Ad Astra. Designed to alleviate the burden on overworked teachers in large and under-resourced classrooms, this solution automates grading, delivers personalized feedback, and transforms learning into an immersive experience. Built using Google Developer Technologies (Gemini APIs, IDX, Vertex AI) and a robust tech stack, it empowers educators with actionable insights while enhancing student engagement.

## 🛠️ Project Overview

*Prepare_Me_AI* addresses the challenge of overburdened teachers struggling to provide personalized feedback by leveraging advanced AI and machine learning. It converts educational content (PDFs, YouTube videos) into interactive modules, offers real-time doubt resolution, and adapts learning paths based on student emotions and performance. Teachers benefit from detailed reports, while students enjoy a dynamic, personalized learning journey.

### ✨ Key Features:

- *Automated Grading & Feedback:* Streamlines assignment evaluation and provides tailored suggestions.
- *Personalized Learning Paths:* Adapts content based on student performance and emotional analysis.
- *Content Processing:* Transforms PDFs and YouTube videos into topic-based modules with simplified explanations.
- *Teacher Insights:* Delivers comprehensive performance reports and class-wide statistics.
- *Future Vision:* Plans for holographic immersion, quantum-enhanced tutoring, and a decentralized knowledge network.

## 🚀 Getting Started

### 1. *Prerequisites:*
- Node.js and Python 3.x installed on your system.
- Google Cloud Platform (GCP) account for Gemini APIs, Vertex AI, and Cloud Spanner (optional for full functionality).
- MongoDB or a similar database for local testing.
- Basic setup for TensorFlow and PyTorch (for AI/ML components).

### 2. *Setting Up:*

- Clone the repository:
  ```bash
  git clone https://github.com/Rishi01010010/Prepare_Me_AI.git
  cd Prepare_Me_AI
  ```

- Install Node.js dependencies:
  ```bash
  npm install
  ```

- Install Python dependencies:
  ```bash
  pip install tensorflow pytorch mermaid
  ```

- Set up environment variables in `.env` (e.g., API keys for Gemini APIs).
- Start the server:
  ```bash
  node server.js
  ```

- Access the application at `http://localhost:3000`.

### 3. *Using the System:*
- Upload PDFs or YouTube links via the frontend to generate modules.
- Interact with the contextual chatbot for real-time doubt clarification.
- View performance reports and customize tests through the teacher dashboard.

### 4. *Sample Data:*
- Test with content in the `trials/` or `video.mp4/` folders.

## 💾 File Structure

```bash
Prepare_Me_AI/
│
├── Buddy-AI-Complete/    # Main project folder
│   ├── frontend/         # Frontend assets and UI files
│   ├── node_modules/     # Node.js dependencies
│   ├── on_working/       # Work-in-progress files (compressed archive)
│   ├── output/           # Output files from processing
│   ├── st_understand_model/ # Model understanding or testing files
│   ├── trials/           # Trial data or test cases
│   ├── video.mp4/        # Video content for processing
│   ├── vikky/            # Additional development or test folder
│   ├── you/              # Another test or development folder
│   ├── .env              # Environment variables
│   ├── dummyserver.js    # Dummy server script for testing
│   ├── mermaid.py        # Python script for generating flowcharts
│   ├── mermaidCode       # Mermaid code snippets (text file)
│   ├── on_working.zip    # Compressed working files
│   ├── package.json      # Node.js project configuration
│   ├── package-lock.json # Locked dependency versions
│   ├── server.js         # Main server script with Express.js
│
└── [Additional folders may exist for future enhancements]
```

### 📝 Code Explanation

1. *server.js*:
   - Core Node.js server using Express.js to handle API requests, file uploads, and frontend rendering.

2. *mermaid.py*:
   - Python script to generate simplified explanations and flowcharts using the Mermaid library.

3. *dummyserver.js*:
   - A test server script for development and debugging purposes.

4. *frontend/*:
   - Contains HTML5, CSS, and JavaScript files for the responsive web interface (to be replaced with Flutter in the final product).

5. *on_working.zip*:
   - Compressed archive of ongoing development files, including potential prototypes or backups.

## 🌐 System Configuration

- *API Setup:* Configure Gemini APIs and Vertex AI credentials in `.env` for NLP and ML tasks.
- *Database:* Use Cloud Spanner (GCP) or a local MongoDB instance for storing student data and reports.
- *Content Input:* Ensure PDFs and videos are compatible with the ingestion system (e.g., clear text, standard formats).

## 🛠️ How It Works

1. *Content Ingestion*: Upload PDFs or YouTube links; Gemini APIs extract topics and generate modules.
2. *Learning Adaptation*: TensorFlow analyzes time spent and test scores, tailoring content dynamically.
3. *Teacher Support*: Reports and statistics are generated via the Analytics Engine, accessible through the dashboard.
4. *Student Engagement*: The chatbot and future AR features (via ARCore) enhance interaction.

## 🎯 Project Intent

Developed by Team Ad Astra (led by Risheek R) as part of the Solution Challenge, *Prepare_Me_AI* tackles the problem of overburdened teachers in large classrooms. It’s a proof-of-concept for an evolving AI assistant that combines automation, personalization, and immersive learning, with a vision for global scalability and quantum enhancements.

## 🔧 Customization

Enhance the project with these ideas:
- *Holographic Integration:* Implement HKI using ARCore for 3D topic exploration.
- *Quantum Upgrade:* Integrate TensorFlow Quantum for predictive tutoring (simulated initially).
- *Global Network:* Use Google Blockchain Node Engine to enable the Global Brain Network.
- *Mobile App:* Transition the frontend to Flutter for cross-platform support.

## 📌 Links
- **Snapshots of MVP:** https://drive.google.com/drive/folders/1j31nXWLG_5i_pv-MWMU_HTOWHp3Lw12usp=shanina](https://drive.google.com/drive/folders/1j31nXWtG_5j_pv-ZM9VMD_HToWHp3Lwf
- **Demo Video:** https://youtu.be/iTnQm49VIDg
