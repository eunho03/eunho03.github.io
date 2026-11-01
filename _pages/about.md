---
layout: page
title:
permalink: /
---
<style>
.post-header:has(.post-title:empty) { display: none; }
.academic-home { padding: 22px 0 36px; font-size: 17px; line-height: 1.65; }
.academic-home h1 { font-size: 40px; font-weight: 400; margin: 0 0 25px; letter-spacing: -1px; }
.academic-intro { display: grid; grid-template-columns: 220px minmax(0,1fr); gap: 44px; align-items: start; }
.portrait-column { margin: 0; }
.portrait-column img { width: 100%; height: auto; display: block; border-radius: 5px; box-shadow: 0 2px 12px #00000018; }
.profile-links { display: flex; justify-content: center; gap: 20px; margin-top: 18px; }
.profile-links a { color: var(--global-text-color); font-size: 29px; }
.academic-bio p { margin: 0 0 20px; }
.academic-bio .affiliation { margin-top: -15px; margin-bottom: 27px; color: var(--global-text-color-light); font-size: 15px; }
.academic-section { margin-top: 60px; }
.academic-section h2 { font-size: 25px; font-weight: 400; margin-bottom: 28px; }
.academic-row { display: grid; grid-template-columns: 220px minmax(0,1fr); gap: 44px; margin-bottom: 27px; }
.academic-date { font-size: 15px; font-weight: 600; padding-top: 3px; }
.academic-row p { margin-bottom: 4px; }
.academic-row ul { padding-left: 20px; margin: 12px 0 0; }
.academic-row li { margin-bottom: 6px; }
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
      <p>I am an undergraduate student in Computer Science and Engineering at <a href="https://www.unist.ac.kr/">UNIST</a>. My interests lie in data-driven prediction and efficient AI inference.</p>
      <p>My experience includes graph community detection research at the <a href="https://sites.google.com/view/dm-unist/home">Data Mining Lab</a>, insurance enrollment prediction, and a course research project on battery-aware mobile LLM routing. I previously interned at <a href="https://sites.google.com/view/unist-aicorelab">AI-CORE Lab</a>, advised by <a href="https://www.ysjang.me/">Prof. YoungSoo Jang</a>.</p>
      <p class="detail"><a href="{{ '/projects/' | relative_url }}">Research &amp; projects</a> · <a href="{{ '/cv/' | relative_url }}">CV</a> · <a href="mailto:ehko030715@unist.ac.kr">Email</a></p>
    </div>
  </div>
  <section class="academic-section" aria-labelledby="education-heading">
    <h2 id="education-heading">education</h2>
    <div class="academic-row">
      <div class="academic-date">Mar 2022 – present</div>
      <div><h3><a href="https://www.unist.ac.kr/">UNIST</a></h3><p>B.S. in Computer Science and Engineering, in progress</p></div>
    </div>
  </section>
  <section class="academic-section" aria-labelledby="experience-heading">
    <h2 id="experience-heading">research &amp; academic experience</h2>
    <div class="academic-row">
      <div class="academic-date">Apr – Oct 2026</div>
      <div><h3>Graph Community Detection Research · <a href="https://sites.google.com/view/dm-unist/home">Data Mining Lab</a></h3>
        <p class="detail">Advisor: <a href="https://sites.google.com/view/junghoon-kim">Prof. Junghoon Kim</a> · UNIST<br><a href="https://edu.unist.ac.kr/aicp/">Artificial Intelligence Challengers Program (AICP)</a></p>
        <ul><li><strong>Participated in team research on structure-preserving graph rewiring</strong> for community detection; co-authored the research poster.</li></ul>
      </div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Apr – Jul 2026</div>
      <div><h3>Insurance Enrollment Prediction · Collaborative Research</h3>
        <p class="detail">Korea Workers' Compensation &amp; Welfare Service (근로복지공단)</p>
        <ul><li><strong>Participated in experiments to predict enrollment in a specific insurance product</strong> using employment and labor insurance subscriber data.</li></ul>
      </div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Research internship</div>
      <div><h3>Reinforcement Learning Research Intern · <a href="https://sites.google.com/view/unist-aicorelab">AI-CORE Lab</a></h3>
        <p class="detail">Advisor: <a href="https://www.ysjang.me/">Prof. YoungSoo Jang (장영수)</a></p>
        <ul><li><strong>Led a reinforcement learning textbook study group</strong> to support fellow interns' learning.</li><li>Completed the planned half of the textbook over the summer.</li></ul>
      </div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Data analysis · 2026</div>
      <div><h3>Manufacturing Data Analysis</h3>
        <p class="detail">K-AI Manufacturing Data Analysis Competition</p>
        <ul><li><strong>Contributed to improving baseline performance</strong> through data and feature refinement.</li><li>Assessed data quality using exploratory data analysis (EDA).</li><li>Replaced low-quality data with external data and expanded the feature set.</li></ul>
      </div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Mobile Computing</div>
      <div><h3>BATT-Route: Battery-aware Routing for Mobile LLM Services</h3>
        <p class="detail">Course research project · 4-member team</p>
        <ul><li><strong>Reviewed and presented three research papers</strong> and co-authored the team's course research report.</li><li>The team developed a prototype for battery-aware edge–cloud LLM routing and evaluated accuracy, latency, and client-side battery cost.</li></ul>
        <p><a href="{{ '/projects/' | relative_url }}">Project details</a></p>
      </div>
    </div>
  </section>
</div>
