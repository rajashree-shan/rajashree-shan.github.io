---
layout: page
title: "Work Experience"
permalink: /work-experience/
description: "My professional work experience."
order: 2
---

<div style="padding-left: 20px;">
  <h2 style="border-bottom: 2px solid white; padding-bottom: 5px; display: inline-block;">Work Experience</h2>
</div>

<html>
<head>
  <style>
    .experience-container {
      display: flex;
      flex-wrap: wrap;
      gap: 40px; /* Further increased gap between boxes */
      justify-content: center;
    }
    .experience-item {
      position: relative;
      width: 730px; /* Further increased box size */
      height: 730px; /* Further increased box size */
      background-size: cover; /* Ensure background image covers the box */
      background-position: center;
      border-radius: 20px;
      box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      padding: 38px; /* Further increased padding */
      color: white; /* Text color */
    }
    .experience-item::before {
      content: '';
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(0, 0, 0, 0.75); /* Dark overlay for better text visibility */
      z-index: 1;
    }
    .experience-content {
      position: relative;
      z-index: 2;
      opacity: 0;
      animation: fadeIn 1s ease forwards;
    }
    .experience-content p {
      margin: 0;
      opacity: 0;
      animation: slideIn 0.5s ease forwards;
      animation-delay: calc(var(--index) * 0.3s); /* Delay for line-by-line animation */
    }
    .company-logo {
      width: 180px; /* Further increased logo size */
      height: 140px; /* Further increased logo size */
      margin-bottom: 20px; /* Further increased margin */
      opacity: 0;
      animation: fadeIn 0.5s ease forwards;
      animation-delay: 0.5s;
    }
    .experience-title {
      font-size: 32px; /* Further increased font size */
      font-weight: bold;
      margin-bottom: 30px; /* Further increased margin */
      opacity: 0;
      animation: fadeIn 0.5s ease forwards;
      animation-delay: 0.8s;
    }
    .experience-summary {
      font-size: 20px; /* Further increased font size */
      margin-bottom: 40px; /* Further increased margin */
      opacity: 0;
      animation: fadeIn 0.5s ease forwards;
      animation-delay: 1.1s;
    }
    .year-button {
      font-size: 15px; /* Further increased font size */
      padding: 10px 10px 10px 10px; /* Further increased button size */
      background-color: rgba(255, 255, 255, 0.2); /* Semi-transparent button */
      color: white;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      opacity: 0;
      animation: fadeIn 0.5s ease forwards;
      animation-delay: 1.4s;
    }
    .year-button:hover {
      background-color: rgba(255, 255, 255, 0.3); /* Hover effect */
    }

    /* Keyframes for animations */
    @keyframes fadeIn {
      to {
        opacity: 1;
      }
    }
    @keyframes slideIn {
      from {
        transform: translateY(20px);
        opacity: 0;
      }
      to {
        transform: translateY(0);
        opacity: 1;
      }
    }
  </style>
</head>
<body>

  <div class="experience-container">
    <!-- Barclays - Data Engineer -->
    <div class="experience-item" style="background-image: url('/assets/images/bg.jpg');">
      <div class="experience-content">
        <img src="/assets/images/Barclays-Logo.png" alt="Barclays" class="company-logo">
        <div class="experience-title">Data Engineer</div>
        <div class="experience-summary">
          Developed an AWS infrastructure optimization initiative by developing Python-based lifecycle management solutions for streamlined data archiving and file transitions . Drove significant cost savings through custom automation scripts that identified and managed idle EC2 instances, eliminating resource waste. Designed and implemented high-performance ETL workflows leveraging Ab Initio and SQL, enabling seamless data integration and analytics capabilities during AWS migration. Led end-to-end application deployment across multiple environments, incorporating comprehensive testing and monitoring systems to enhance operational efficiency and system reliability. Successfully delivered these solutions to USA clients, ensuring optimized performance and scalability.
        </div>
        <button class="year-button">2022 - 2024</button>
      </div>
    </div>

    <!-- The Sparks Foundation - Data Science -->
    <div class="experience-item" style="background-image: url('https://images.unsplash.com/photo-1551288049-bebda4e38f71?ixlib=rb-1.2.1&auto=format&fit=crop&w=1350&q=80');">
      <div class="experience-content">
        <img src="/assets/images/sf.jpeg" alt="The Sparks Foundation" class="company-logo">
        <div class="experience-title">Data Science Intern</div>
        <div class="experience-summary">
          Analyzed diverse datasets and developed predictive models using Supervised & Unsupervised Learning techniques in Python to drive data-driven decision-making. Optimized machine learning models to improve performance and accuracy. Designed interactive dashboards in Tableau, leveraging data visualization techniques to present key insights to stakeholders, enabling better strategic planning and trend analysis. The tech stack included Python, Scikit-learn, TensorFlow, Tableau, and SQL for data processing, modeling, and visualization.
        </div>
        <button class="year-button">2021</button>
      </div>
    </div>
  </div>

</body>
</html>