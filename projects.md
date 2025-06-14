---
layout: page
title: "Projects"
permalink: /projects/
description: "My projects"
show_tile: true
order: 4
---

<div style="padding-left: 20px;">
  <h2 style="border-bottom: 2px solid white; padding-bottom: 5px; display: inline-block;">Projects</h2>
</div>
<div class="projects-container">
<!-- Project 1 -->
<div class="project-box" onclick="openModal('modal1')">
  <div class="project-title">Clara: AI Compliance Companion Bot</div>
  <div class="project-subtitle">Click to learn more</div>
  <a href="https://bank-compliance-bot.streamlit.app" class="live-demo" target="_blank">Live Demo</a>
</div>

<div id="modal1" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal1')">&times;</span>
    <h3>Clara: AI Compliance Companion for Banks</h3>
    <p>Clara is a secure, AI-powered chatbot that enables banks and financial institutions to query encrypted audit logs, policy docs, and compliance manuals using natural language. It’s optimized for security, retrieval accuracy, and user-friendliness.</p>
    <ul>
      <li>🔐 MPC-based security ensures all queries over sensitive logs remain private</li>
      <li>🧠 Natural language query system powered by LangChain + OpenAI</li>
      <li>☁️ Retrieves unstructured policy documents directly from AWS S3</li>
      <li>📄 Handles multi-document retrieval with context-aware answers</li>
      <li>⚙️ Fast and interactive UI built with Streamlit</li>
    </ul>
    <p><strong>Tech Stack:</strong> LangChain, OpenAI GPT-4, Streamlit, AWS S3, Python, Secure MPC (simulated)</p>
  </div>
</div>
<!-- Project 2 -->
<div class="project-box" onclick="openModal('modal2')">
  <div class="project-title">AI Interview Recruiter</div>
  <div class="project-subtitle">Click to learn more</div>
  <a href="https://github.com/rajashree-shan/AI_Recruiter" class="live-demo" target="_blank">View Code</a>
</div>

<div id="modal2" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal2')">&times;</span>
    <h3>AI Recruiter – Your Automated Interview Assistant</h3>
    <p>AI Recruiter is a smart, voice-interactive mock interview assistant that helps candidates practice job interviews by asking personalized questions and scoring their responses automatically. If the candidate qualifies, it schedules a real interview.</p>
    <ul>
      <li>🔍 Parses job descriptions to extract key skills using LLMs</li>
      <li>🗣️ Asks tailored interview questions via voice</li>
      <li>🎤 Converts spoken answers into text (Speech-to-Text)</li>
      <li>📊 Scores answers based on relevance, tone, and confidence</li>
      <li>📅 Auto-schedules Google Meet interviews if thresholds are met</li>
    </ul>
    <p><strong>Tech Stack:</strong> OpenAI GPT-4, Whisper (Speech-to-Text), LangChain, Google Calendar API, Python, Streamlit</p>
  </div>
</div>
<!-- Project 3 -->
<div class="project-box" onclick="openModal('modal3')">
  <div class="project-title">RAG-Powered Python Code Reviewer</div>
  <div class="project-subtitle">Click to learn more</div>
  <a href="https://huggingface.co/spaces/rshree01/Code_Reviewer" class="live-demo" target="_blank">Live Demo</a>
</div>

<div id="modal3" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal3')">&times;</span>
    <h3> Code Reviewer and Refactor Assistant</h3>
    <p>This AI-powered assistant reviews Python code intelligently using Retrieval-Augmented Generation (RAG), allowing you to upload zipped projects or link GitHub PRs for structured and context-aware feedback.</p>
    <ul>
      <li>✅ Real-time code reviews with GPT-4</li>
      <li>📁 Upload zipped Python projects for batch analysis</li>
      <li>🔄 GitHub PR integration: Adds inline comments automatically</li>
      <li>✨ Uses custom guidelines from internal docs (RAG)</li>
      <li>🔐 Private repo authentication with GitHub tokens</li>
      <li>📎 Download & share code review summaries</li>
    </ul>
    <p><strong>Tech Stack:</strong> OpenAI GPT-4, FAISS, Sentence Transformers (MiniLM), Gradio, GitHub REST API (v3), Python</p>
  </div>
</div>
<!-- Project 4 -->
<div class="project-box" onclick="openModal('modal4')">
  <div class="project-title">AutoReply.AI - Recruiter Email Assistant</div>
  <div class="project-subtitle">Click to learn more</div>
  <a href="https://github.com/rajashree-shan/AutoReply.AI" class="live-demo" target="_blank">Live Demo</a>
</div>

<div id="modal4" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal4')">&times;</span>
    <h3>AutoReply.AI: Chrome Extension to Manage Recruiter Emails</h3>
    <p>This smart Chrome extension uses AI to read and respond to recruiter emails automatically, saving time and boosting productivity during the job search.</p>
    <ul>
      <li>📥 Reads unread Gmail messages</li>
      <li>🧠 Classifies recruiter emails using spaCy NLP:</li>
      <ul>
        <li>❌ Rejection</li>
        <li>📅 Interview scheduling</li>
      </ul>
      <li>📆 Checks your Google Calendar (Mon–Fri, 9AM–5PM)</li>
      <li>🔎 Finds your next available 30-minute slot</li>
      <li>📤 Automatically replies to recruiters with availability</li>
    </ul>
    <p><strong>Tech Stack:</strong> JavaScript, Chrome Extension API, Gmail API, Google Calendar API, spaCy (Python), OAuth2</p>
  </div>
</div>
<!-- Project 5 -->
<div class="project-box" onclick="openModal('modal6')">
  <div class="project-title">ETL Pipeline Project</div>
  <div class="project-subtitle">Click to learn more</div>
  <a href="https://github.com/rajashree-shan/ETL-Pipeline-Project" class="live-demo" target="_blank">View Code</a>
</div>

<div id="modal6" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal6')">&times;</span>
    <h3>Airflow ETL Pipeline: PostgreSQL to Redshift</h3>
    <p>Designed a production-ready ETL pipeline using Apache Airflow to automate daily data transfers from a local PostgreSQL database to Amazon Redshift.</p>
    <ul>
      <li><strong>Extract:</strong> Connects to a local PostgreSQL sales table to retrieve data.</li>
      <li><strong>Transform:</strong> Cleans and transforms data using Pandas.</li>
      <li><strong>Load:</strong> Writes the cleaned dataset to a Redshift table for downstream analytics.</li>
      <li><strong>Notify:</strong> Sends a Slack notification on DAG completion or failure.</li>
    </ul>
    <p>Airflow connections used:</p>
    <ul>
      <li><code>postgres_conn</code> – source database</li>
      <li><code>redshift_conn</code> – destination warehouse</li>
      <li><code>slack_webhook</code> – alerting channel</li>
    </ul>
    <p><strong>Schedule:</strong> Runs daily via Airflow DAG scheduler</p>
    <p><strong>Tech Stack:</strong> Python, Apache Airflow, Pandas, PostgreSQL, Amazon Redshift, Slack API</p>
  </div>
</div>
<!-- Project 6 -->
<div class="project-box" onclick="openModal('modal6')">
  <div class="project-title">PoachAlert - Wildlife Poaching Detector</div>
  <div class="project-subtitle">Click to learn more</div>
  <a href="https://huggingface.co/spaces/rshree01/PoachAlert-system-demo" class="live-demo" target="_blank">Live Demo</a>
</div>

<div id="modal6" class="modal">
  <div class="modal-content">
    <span class="close" onclick="closeModal('modal6')">&times;</span>
    <h3>PoachAlert: Real-Time Wildlife Poaching Detection</h3>
    <p>Developed a computer vision system to detect illegal poaching activity using deep learning models. Aims to support conservation efforts in real-time surveillance scenarios.</p>
    <ul>
      <li>📸 Object detection using YOLO-Nano for lightweight deployment</li>
      <li>🧠 Face recognition of forest rangers via ArcFace</li>
      <li>⚠️ Flags unknown individuals and unauthorized activity in conservation zones</li>
      <li>🚀 Deployed as a demo on Hugging Face Spaces</li>
    </ul>
    <p><strong>Tech Stack:</strong> Python, YOLO-Nano, ArcFace, OpenCV, Gradio, Hugging Face Spaces</p>
  </div>
</div>
  <!-- Project 7 -->
  <div class="project-box" onclick="openModal('modal7')">
    <div class="project-title">MIFNet: Gastric Cancer Detection and Classification</div>
    <div class="project-subtitle">Click to learn more</div>
    <a href="https://doi.org/10.33436/v33i4y202309" class="live-demo" target="_blank">Link</a>
  </div>
  <div id="modal7" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal7')">&times;</span>
      <h3>MIFNet: Gastric Cancer Detection</h3>
      <p>Developed a deep learning model (MIFNet) for accurate gastric cancer classification and localization in histopathological images.</p>
      <ul>
        <li>Multi-Task Net, Global Net, and Fusion Net architecture</li>
        <li>98% accuracy</li>
        <li>Published in peer-reviewed journal</li>
      </ul>
      <p><strong>Tech Stack:</strong> Python, TensorFlow, OpenCV</p>
    </div>
  </div>

  <!-- Project 8 -->
  <div class="project-box" onclick="openModal('modal8')">
    <div class="project-title">Movie Recommendation System</div>
    <div class="project-subtitle">Click to learn more</div>
  </div>
  <div id="modal8" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal8')">&times;</span>
      <h3>Hybrid Movie Recommendation</h3>
      <p>Built a hybrid movie recommender using collaborative and content-based filtering with dynamic user feedback learning.</p>
      <ul>
        <li>TF-IDF, cosine similarity, adaptive scoring</li>
        <li>Achieved 92% accuracy</li>
      </ul>
      <p><strong>Tech Stack:</strong> Python, Scikit-learn, Flask</p>
    </div>
  </div>

  <!-- Project 9 -->
  <div class="project-box" onclick="openModal('modal9')">
    <div class="project-title">Crime Analysis: A Data-Driven Approach to
Public Safety</div>
    <div class="project-subtitle">Click to learn more</div>
    <a href="https://public.tableau.com/app/profile/rajashree.shanmuganathan/viz/Crime_Data_Analysis/Dashboard1" class="live-demo" target="_blank">Live Demo</a>
  </div>
  <div id="modal9" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal9')">&times;</span>
      <h3>Crime Data Analysis</h3>
      <p>Analyzed public datasets to predict and visualize high-risk areas using machine learning and visual analytics.</p>
      <ul>
        <li>Cleaned and processed Buffalo state data</li>
        <li>Built visual dashboards to show trends</li>
        <li>Used Random Forest, XGBoost for predictions</li>
      </ul>
      <p><strong>Tech Stack:</strong> Python, Pandas, Seaborn, Tableau</p>
    </div>
  </div>

  <!-- Project 10 -->
  <div class="project-box" onclick="openModal('modal10')">
    <div class="project-title">Diabetes Prediction System</div>
    <div class="project-subtitle">Click to learn more</div>
  </div>
  <div id="modal10" class="modal">
    <div class="modal-content">
      <span class="close" onclick="closeModal('modal10')">&times;</span>
      <h3>Diabetes Prediction System</h3>
      <p>End-to-end pipeline for diabetes prediction using EDA, ML, and Streamlit for real-time interaction.</p>
      <ul>
        <li>Used GridSearchCV, EDA, Streamlit UI</li>
        <li>Included user-uploaded CSV for analysis</li>
      </ul>
      <p><strong>Tech Stack:</strong> Python, Scikit-learn, Streamlit, PySpark</p>
    </div>
  </div>





<style>
.projects-container {
  display: flex;
  flex-wrap: wrap;
  justify-content: center; /* Ensures rows center-align */
  gap: 20px;
  max-width: 1000px; /* Optional: controls overall width */
  margin: 0 auto;     /* Center container */
}


.project-box {
  width: 300px;
  background: #1e1e1e;
  margin-bottom: 30px;
  color: #f0f0f0;
  border-radius: 10px;
  padding: 20px;
  box-shadow: 0 4px 10px rgba(0,0,0,0.3);
  cursor: pointer;
  text-align: center;
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}

.project-box:hover {
  transform: scale(1.02);
  box-shadow: 0 0 15px rgba(255, 165, 0, 0.5);
  cursor: pointer;
}

.project-title {
  font-size: 1.2rem;
  font-weight: bold;
  margin-bottom: 10px;
}

.project-subtitle {
  font-size: 0.85rem;
  color: #ccc;
  margin-bottom: 15px;
}

.live-demo {
  display: inline-block;
  padding: 6px 12px;
  background-color: #ff9800;
  color: #fff;
  border-radius: 5px;
  text-decoration: none;
  font-size: 0.85rem;
  transition: background 0.3s;
}

.live-demo:hover {
  background-color: #e68900;
}

.modal {
  display: none;
  position: fixed;
  z-index: 10;
  left: 0;
  top: 0;
  width: 100%;
  height: 100%;
  overflow: auto;
  background-color: rgba(0,0,0,0.9);
}

.modal-content {
  background-color: #2e2e2e;
  margin: 5% auto;
  padding: 30px;
  border: 1px solid #888;
  width: 80%;
  max-width: 600px;
  color: #fff;
  border-radius: 10px;
}

.close {
  color: #aaa;
  float: right;
  font-size: 28px;
  font-weight: bold;
}

.close:hover, .close:focus {
  color: #fff;
  text-decoration: none;
  cursor: pointer;
}
</style>

<script>
function openModal(id) {
  document.getElementById(id).style.display = "block";
}

function closeModal(id) {
  document.getElementById(id).style.display = "none";
}
</script>
