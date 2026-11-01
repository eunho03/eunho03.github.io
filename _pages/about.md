---
layout: page
title:
permalink: /
---
<style>
:root { --global-theme-color: #2455b3; }
html[data-theme='dark'] { --global-theme-color: #86b3ff; }
.container { max-width: 1100px; }
.post-header:has(.post-title:empty) { display: none; }
.academic-home { padding: 22px 0 36px; font-size: 17px; line-height: 1.65; }
.academic-home h1 { font-size: 44px; font-weight: 400; margin: 0 0 25px; letter-spacing: -1px; }
.academic-intro { display: grid; grid-template-columns: 255px minmax(0,1fr); gap: 48px; align-items: start; }
.portrait-column { margin: 0; }
.portrait-column img { width: 100%; height: auto; display: block; border-radius: 5px; box-shadow: 0 2px 12px #00000018; }
.profile-links { display: flex; justify-content: center; gap: 20px; margin-top: 18px; }
.profile-links a { color: var(--global-text-color); font-size: 29px; }
.academic-bio p { margin: 0 0 20px; }
.academic-bio .affiliation { margin-top: -15px; margin-bottom: 27px; color: var(--global-text-color-light); font-size: 15px; }
.academic-section { margin-top: 60px; }
.academic-section h2 { font-size: 32px; font-weight: 400; margin-bottom: 28px; }
.academic-row { display: grid; grid-template-columns: 255px minmax(0,1fr); gap: 48px; margin-bottom: 27px; }
.academic-date { font-size: 15px; font-weight: 600; padding-top: 3px; }
.academic-row p { margin-bottom: 4px; }
.academic-row h3 { font-size: 19px; font-weight: 500; margin: 0 0 7px; }
.academic-row .detail { font-size: 15px; color: var(--global-text-color-light); }
@media(max-width: 700px) {
 .academic-home { padding-top: 12px; font-size: 16px; }
 .academic-intro, .academic-row { grid-template-columns: 1fr; gap: 22px; }
 .portrait-column { width: min(220px, 72%); }
 .academic-home h1 { font-size: 36px; }
 .academic-section { margin-top: 42px; }
 .academic-row { gap: 7px; }
}
</style>
<div class="academic-home">
  <div class="academic-intro">
    <aside class="portrait-column" aria-label="Profile photo and contact links">
      <img src="{{ '/eunho.jpg' | relative_url }}" alt="Portrait of Eun Ho Koh" width="685" height="898">
      <div class="profile-links">
        <a href="mailto:ehko030715@unist.ac.kr" aria-label="Email Eun Ho Koh" title="Email"><i class="fa-solid fa-envelope" aria-hidden="true"></i></a>
        <a href="https://github.com/eunho03" aria-label="Eun Ho Koh on GitHub" title="GitHub"><i class="fa-brands fa-github" aria-hidden="true"></i></a>
      </div>
    </aside>
    <div class="academic-bio">
      <h1>Eun Ho Koh</h1>
      <p class="affiliation">Computer Science and Engineering · UNIST</p>
      <p>Hello! I am an undergraduate student in Computer Science and Engineering at <a href="https://www.unist.ac.kr/">Ulsan National Institute of Science and Technology (UNIST)</a>.</p>
      <p>My interests include data-driven modeling and prediction, efficient LLM inference, and LLM-based agent systems. Through coursework and project work, I have explored data analysis, mobile applications, and machine learning.</p>
      <p>I enjoy identifying problems in real-world data and connecting analysis with working software. During a reinforcement learning research internship, I also organized a textbook study group to learn together with fellow interns.</p>
      <p>You can find more about my work in <a href="{{ '/projects/' | relative_url }}">projects</a> and my <a href="{{ '/cv/' | relative_url }}">CV</a>. The best way to reach me is by <a href="mailto:ehko030715@unist.ac.kr">email</a>.</p>
    </div>
  </div>
  <section class="academic-section" aria-labelledby="education-heading">
    <h2 id="education-heading">education</h2>
    <div class="academic-row">
      <div class="academic-date">Mar 2022 – present</div>
      <div><h3><a href="https://www.unist.ac.kr/">UNIST</a></h3><p>B.S. in Computer Science and Engineering, in progress</p><p class="detail">GPA: 3.37 / 4.3</p></div>
    </div>
  </section>
  <section class="academic-section" aria-labelledby="experience-heading">
    <h2 id="experience-heading">selected experience</h2>
    <div class="academic-row">
      <div class="academic-date">Mobile computing</div>
      <div><h3>Mobile Sensing and Recognition</h3><p>Implemented locally running Android applications for object recognition and IMU sensor-based activity prediction.</p><p class="detail">Kotlin · Android Studio</p></div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Data analysis · 2026</div>
      <div><h3>Manufacturing Data Analysis</h3><p>Examined data quality through exploratory data analysis and contributed to baseline improvements using external data and additional features.</p><p class="detail">K-AI Manufacturing Data Analysis Competition</p></div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Research internship</div>
      <div><h3>Reinforcement Learning Study Group</h3><p>Organized a textbook study group with fellow interns and completed the planned half of the textbook over the summer.</p></div>
    </div>
  </section>
</div>
