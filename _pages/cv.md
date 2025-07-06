---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-section {
  margin-bottom: 30px;
}
.cv-section h2 {
  color: #2196F3;
  border-bottom: 2px solid #e9ecef;
  padding-bottom: 5px;
  margin-bottom: 15px;
}
.cv-item {
  margin-bottom: 15px;
}
.cv-item h3 {
  margin-bottom: 5px;
  color: #495057;
}
.cv-meta {
  color: #6c757d;
  font-style: italic;
  margin-bottom: 5px;
}
.cv-description {
  margin-left: 20px;
}
.award-highlight {
  background: linear-gradient(120deg, #a2facf 0%, #64b3f4 100%);
  background-clip: text;
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  font-weight: bold;
}
</style>

{% include base_path %}

<div class="cv-section">
<h2>🎓 Education</h2>

<div class="cv-item">
<h3>Ph.D. in Civil and Environmental Engineering</h3>
<div class="cv-meta">University of California, Los Angeles (UCLA) | 2024 - Present</div>
<div class="cv-description">
• Focus: Intelligent Transportation Systems, Autonomous Driving, AI for Smart Mobility<br>
• Advisor: Prof. [Advisor Name]<br>
• GPA: 4.0/4.0
</div>
</div>

<div class="cv-item">
<h3>M.S. in Computer Science</h3>
<div class="cv-meta">New York University (NYU) | 2022 - 2024</div>
<div class="cv-description">
• Specialization: Machine Learning, Deep Learning, Computer Vision<br>
• Thesis: "Advanced Methods for Trajectory Prediction in Urban Environments"<br>
• GPA: 3.9/4.0
</div>
</div>

<div class="cv-item">
<h3>B.E. in Computer Science and Engineering</h3>
<div class="cv-meta">University of California, Davis (UC Davis) | 2018 - 2022</div>
<div class="cv-description">
• <strong>Summa Cum Laude</strong> (Top 5%)<br>
• Senior Project: YOLOv5-based Mask Detection System<br>
• GPA: 3.8/4.0
</div>
</div>
</div>

<div class="cv-section">
<h2>💼 Research Experience</h2>

<div class="cv-item">
<h3>Graduate Research Assistant</h3>
<div class="cv-meta">UCLA Mobility Lab | 2024 - Present</div>
<div class="cv-description">
• Leading research on intersection safety systems for autonomous vehicles<br>
• Developed AI algorithms that secured <span class="award-highlight">$750k U.S.DOT funding</span><br>
• Published papers on trajectory prediction and semantic trajectory mining<br>
• Mentoring undergraduate researchers in machine learning projects
</div>
</div>

<div class="cv-item">
<h3>Research Intern</h3>
<div class="cv-meta">TikTok | Summer 2023</div>
<div class="cv-description">
• Worked on large-scale recommendation systems and content understanding<br>
• Implemented deep learning models for user behavior prediction<br>
• Collaborated with cross-functional teams on production ML systems<br>
• Optimized model performance for real-time applications
</div>
</div>

<div class="cv-item">
<h3>Undergraduate Research Assistant</h3>
<div class="cv-meta">UC Davis Computer Science Department | 2020 - 2022</div>
<div class="cv-description">
• Developed computer vision applications for COVID-19 safety compliance<br>
• Implemented object detection algorithms using YOLOv5<br>
• Contributed to research on knowledge-graph constrained text generation<br>
• Received Outstanding Research Award
</div>
</div>
</div>

<div class="cv-section">
<h2>🏆 Honors and Awards</h2>

<div class="cv-item">
• <strong>2025</strong>: <span class="award-highlight">Tier 1 Winner</span>, U.S. DOT Intersection Safety Challenge ($750k award)<br>
• <strong>2024</strong>: <span class="award-highlight">Best Paper Award</span>, IEEE ITSC 2024<br>
• <strong>2024</strong>: Graduate Research Fellowship, UCLA<br>
• <strong>2022</strong>: Summa Cum Laude, UC Davis (Top 5%)<br>
• <strong>2021</strong>: Dean's List, UC Davis (Multiple Terms)<br>
• <strong>2020</strong>: Outstanding Research Award, UC Davis Computer Science Department
</div>
</div>

<div class="cv-section">
<h2>🛠️ Technical Skills</h2>

<div class="cv-item">
<strong>Programming Languages:</strong> Python, C++, Java, JavaScript, R, MATLAB, SQL<br>
<strong>Machine Learning:</strong> PyTorch, TensorFlow, Keras, scikit-learn, OpenCV<br>
<strong>Big Data & Cloud:</strong> AWS, Google Cloud, Apache Spark, Hadoop, Docker<br>
<strong>Web Technologies:</strong> React, Node.js, Flask, Django, HTML/CSS<br>
<strong>Tools & Platforms:</strong> Git, Linux, Jupyter, VS Code, LaTeX, SUMO, CARLA<br>
<strong>Databases:</strong> MySQL, MongoDB, PostgreSQL, Redis
</div>
</div>

<div class="cv-section">
<h2>📝 Publications</h2>
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
</div>

<div class="cv-section">
<h2>🎤 Talks and Presentations</h2>
<ul>{% for post in site.talks reversed %}
  {% include archive-single-talk-cv.html  %}
{% endfor %}</ul>
</div>

<div class="cv-section">
<h2>👨‍🏫 Teaching Experience</h2>
<ul>{% for post in site.teaching reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
</div>

<div class="cv-section">
<h2>🤝 Professional Service</h2>

<div class="cv-item">
<strong>Conference Reviewer:</strong><br>
• IEEE Intelligent Transportation Systems Conference (ITSC) 2024-2025<br>
• Transportation Research Board (TRB) Annual Meeting 2025<br>
• IEEE International Conference on Big Data 2024
</div>

<div class="cv-item">
<strong>Journal Reviewer:</strong><br>
• IEEE Transactions on Intelligent Transportation Systems<br>
• Transportation Research Part C: Emerging Technologies
</div>

<div class="cv-item">
<strong>Professional Memberships:</strong><br>
• IEEE Member<br>
• Transportation Research Board (TRB) Member<br>
• Association for Computing Machinery (ACM) Member
</div>
</div>

<div class="cv-section">
<h2>🌐 Languages</h2>
<div class="cv-item">
• <strong>English:</strong> Native/Fluent<br>
• <strong>Mandarin Chinese:</strong> Native<br>
• <strong>Spanish:</strong> Conversational
</div>
</div>

---

<center>
<a href="/files/YifanLiu_CV.pdf" target="_blank">📄 Download PDF Version</a>
</center>

*Last updated: January 2025*
