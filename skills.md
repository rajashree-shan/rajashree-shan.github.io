---
layout: page
title: "Skills"
permalink: /skills/
description: "My technical and soft skills."
show_tile: true
order: 3
---
<div style="padding-left: 20px;">
  <h2 style="border-bottom: 2px solid white; padding-bottom: 5px; display: inline-block;">Skills</h2>
</div>

<html>
<head>
  <style>
    .skill-item {
      position: relative;
      text-align: center;
      margin: 10px;
      display: inline-block;
      width: 100px;
    }

    .skill-image {
      width: 100%;
      height: 100px;
      object-fit: contain;
      transition: transform 0.3s ease;
    }

    .skill-name {
      position: absolute;
      bottom: -20px;
      left: 50%;
      transform: translateX(-50%);
      background-color: rgba(0, 0, 0, 0.75);
      color: white;
      padding: 5px 10px;
      border-radius: 5px;
      opacity: 0;
      transition: opacity 0.3s ease;
      white-space: nowrap;
    }

    .skill-item:hover .skill-name {
      opacity: 1;
    }

    .skill-item:hover .skill-image {
      transform: scale(1.1);
    }

    .skills-group {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      margin-bottom: 30px;
    }

    .group-title {
      font-size: 1.5em;
      font-weight: bold;
      text-align: center;
      margin-bottom: 15px;
    }
  </style>
</head>
<body>

  <!-- Data Science / Machine Learning -->
  <div class="group-title">Data Science / Machine Learning</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" class="skill-image"><div class="skill-name">Python</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/r/r-original.svg" alt="R" class="skill-image"><div class="skill-name">R</div></div>
    <div class="skill-item"><img src="https://upload.wikimedia.org/wikipedia/commons/0/05/Scikit_learn_logo_small.svg" alt="Scikit-learn" class="skill-image"><div class="skill-name">Scikit-learn</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/tensorflow/tensorflow-original.svg" alt="TensorFlow" class="skill-image"><div class="skill-name">TensorFlow</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pytorch/pytorch-original.svg" alt="PyTorch" class="skill-image"><div class="skill-name">PyTorch</div></div>
  </div>

  <!-- Big Data / Cloud -->
  <div class="group-title">Big Data / Cloud</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/apache/apache-original.svg" alt="Apache Spark" class="skill-image"><div class="skill-name">Apache Spark</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/hadoop/hadoop-original.svg" alt="Hadoop" class="skill-image"><div class="skill-name">Hadoop</div></div>
    <div class="skill-item"><img src="/assets/images/aws.png" alt="AWS" class="skill-image"><div class="skill-name">AWS</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/googlecloud/googlecloud-original.svg" alt="GCP" class="skill-image"><div class="skill-name">GCP</div></div>
    <div class="skill-item"><img src="https://www.databricks.com/wp-content/uploads/2021/10/db-nav-logo.svg" alt="Databricks" class="skill-image"><div class="skill-name">Databricks</div></div>
  </div>

  <!-- Database -->
  <div class="group-title">Database</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original-wordmark.svg" alt="SQL" class="skill-image"><div class="skill-name">SQL</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" class="skill-image"><div class="skill-name">PostgreSQL</div></div>
  </div>

  <!-- ETL / Data Engineering -->
  <div class="group-title">ETL / Data Engineering</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn-icons-png.flaticon.com/512/3078/3078986.png" alt="ETL" class="skill-image"><div class="skill-name">ETL</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" class="skill-image"><div class="skill-name">Docker</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" class="skill-image"><div class="skill-name">Git</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/bash/bash-original.svg" alt="Shell Scripting" class="skill-image"><div class="skill-name">Shell Scripting</div></div>
  </div>

  <!-- Visualization -->
  <div class="group-title">Visualization</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn.worldvectorlogo.com/logos/tableau-software.svg" alt="Tableau" class="skill-image"><div class="skill-name">Tableau</div></div>
  </div>

  <!-- Data Processing -->
  <div class="group-title">Data Processing</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/numpy/numpy-original.svg" alt="Numpy" class="skill-image"><div class="skill-name">Numpy</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pandas/pandas-original.svg" alt="Pandas" class="skill-image"><div class="skill-name">Pandas</div></div>
  </div>

  <!-- LLM / NLP -->
  <div class="group-title">LLM / NLP</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://img.icons8.com/ios-filled/50/000000/search--v1.png" alt="RAG" class="skill-image"><div class="skill-name">RAG</div></div>
    <div class="skill-item"><img src="https://img.icons8.com/ios-filled/50/000000/database.png" alt="FAISS" class="skill-image"><div class="skill-name">FAISS</div></div>
    <div class="skill-item"><img src="https://img.icons8.com/ios-filled/50/000000/robot-2.png" alt="LLMs" class="skill-image"><div class="skill-name">LLMs</div></div>
  </div>

  <!-- Web Development -->
  <div class="group-title">Web Development</div>
  <div class="skills-group">
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML" class="skill-image"><div class="skill-name">HTML</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS" class="skill-image"><div class="skill-name">CSS</div></div>
    <div class="skill-item"><img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" class="skill-image"><div class="skill-name">JavaScript</div></div>
  </div>

  <!-- Soft Skills -->
  <div class="group-title">Soft Skills</div>
  <div class="skills-group">
    <div class="skill-item">
      <img src="https://img.icons8.com/ios-filled/50/000000/communication.png" alt="Communication" class="skill-image">
      <div class="skill-name">Communication</div>
    </div>
    <div class="skill-item">
      <img src="https://img.icons8.com/ios-filled/50/000000/teamwork.png" alt="Teamwork" class="skill-image">
      <div class="skill-name">Teamwork</div>
    </div>
    <div class="skill-item">
      <img src="https://img.icons8.com/ios-filled/50/000000/light-on.png" alt="Problem-Solving" class="skill-image">
      <div class="skill-name">Problem-Solving</div>
    </div>
    <div class="skill-item">
      <img src="https://img.icons8.com/ios-filled/50/000000/time-management.png" alt="Time Management" class="skill-image">
      <div class="skill-name">Time Management</div>
    </div>
    <div class="skill-item">
      <img src="https://img.icons8.com/ios-filled/50/000000/leader.png" alt="Leadership" class="skill-image">
      <div class="skill-name">Leadership</div>
    </div>
  </div>
</body>
</html>
