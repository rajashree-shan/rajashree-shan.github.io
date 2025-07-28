---
layout: page
title: "Work Experience"
permalink: /work-experience/
show_tile: true
description: "My professional work experience."
order: 2
---

<div style="padding-left: 20px;">
  <h2 style="border-bottom: 2px solid white; padding-bottom: 5px; display: inline-block;">Work Experience</h2>
</div>

<style>
  .timeline {
    position: relative;
    max-width: 960px;
    margin: 0 auto;
    padding: 40px 20px;
  }

  .timeline::after {
    content: '';
    position: absolute;
    width: 4px;
    background-color: #444;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -2px;
  }

  .timeline-entry {
    position: relative;
    width: 50%;
    padding: 30px 40px;
    box-sizing: border-box;
  }

  .timeline-entry.left {
    left: 0;
  }

  .timeline-entry.right {
    left: 50%;
  }

  .timeline-entry::before {
    content: " ";
    position: absolute;
    top: 40px;
    right: -10px;
    border-width: 10px;
    border-style: solid;
    border-color: transparent transparent transparent #1f2a38;
  }

  .timeline-entry.right::before {
    left: -10px;
    right: auto;
    border-color: transparent #1f2a38 transparent transparent;
  }

  .timeline-content {
    background: #1f2a38;
    color: white;
    padding: 25px;
    border-radius: 8px;
    box-shadow: 0 6px 20px rgba(0,0,0,0.25);
  }

  .timeline-content h3 {
    margin-top: 0;
    font-size: 1.5rem;
  }

  .timeline-content p {
    font-size: 1rem;
    line-height: 1.6;
  }

  .timeline-content .year {
    display: inline-block;
    margin-top: 12px;
    background: rgba(255,255,255,0.1);
    padding: 6px 12px;
    border-radius: 5px;
    font-size: 0.85rem;
    color: #ddd;
  }

  @media screen and (max-width: 768px) {
    .timeline::after {
      left: 10px;
    }
    .timeline-entry {
      width: 100%;
      padding-left: 30px;
      padding-right: 15px;
    }
    .timeline-entry.right {
      left: 0;
    }
    .timeline-entry::before,
    .timeline-entry.right::before {
      left: 10px;
      border: none;
    }
  }
</style>

<div class="timeline">

<!-- Pear -->
  <div class="timeline-entry left">
    <div class="timeline-content">
      <h3>Data Science/ML Intern @ Pear</h3>
      <p>
        Developed an unsupervised learning algorithm on big data (6M+ rows) to cluster medical referral patterns resulting in a dimension reduction of 95%.
        Created an LLM implementation of LLaMA3 to synthesize machine generated output into natural language descriptions providing improved customer engagement.
        Implemented PySpark data processing techniques to ingest Big Data and Developed alongside LLM subject-matter-experts a locally hosted LLM with RAG architecture to ingest proprietary medical data to be used for diagnosis.
      </p>
      <div class="year">MAY 2024 - AUG 2024</div>
    </div>
  </div>

  <!-- Barclays -->
  <div class="timeline-entry right">
    <div class="timeline-content">
      <h3>Data Engineer @ Barclays</h3>
      <p>
        Led an AWS infrastructure cost-optimization initiative by developing Python-based automation to manage EC2 lifecycle and archive inactive S3 resources. Designed high-performance ETL pipelines using Ab Initio and SQL to support AWS data migration. Deployed applications across multi-env setups with integrated testing and monitoring, improving operational reliability. Collaborated with US-based teams to deliver scalable, production-grade solutions.
      </p>
      <div class="year">AUG 2022 – JUL 2024</div>
    </div>
  </div>

  
  <!-- Sparks Foundation -->
  <div class="timeline-entry left">
    <div class="timeline-content">
      <h3>Data Science Intern @ The Sparks Foundation</h3>
      <p>
        Developed supervised and unsupervised ML models to solve business analytics challenges using Python and Scikit-learn. Created data pipelines to preprocess and analyze structured datasets. Designed Tableau dashboards to visualize insights and enable non-technical stakeholders to act on data trends. Contributed to model performance improvements and interpretability.
      </p>
      <div class="year">JUL 2021 - AUG 2021</div>
    </div>
  </div>

</div>
