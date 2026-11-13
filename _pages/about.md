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
.profile-cv { text-align: center; margin: 16px 0 0; font-size: 17px; }
.profile-links { display: flex; justify-content: center; gap: 20px; margin-top: 18px; }
.profile-links a { color: var(--global-text-color); font-size: 29px; }
.academic-bio p { margin: 0 0 20px; }
.academic-bio .affiliation { margin-top: -15px; margin-bottom: 27px; color: var(--global-text-color-light); font-size: 15px; }
.academic-section { margin-top: 40px; }
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
 .portrait-column { width: 150px; }
 .academic-home h1 { margin-bottom: 20px; }
 .academic-bio { overflow-wrap: anywhere; }
 .academic-home h1 { font-size: 36px; }
 .academic-section { margin-top: 42px; }
 .academic-row { gap: 7px; }
}

/* Native details keeps roles visible and expands content in document flow. */
.research-peek { border-bottom: 1px solid var(--global-divider-color); }
.research-peek summary { display: grid; grid-template-columns: 220px minmax(0, 1fr) 20px; gap: 44px; align-items: start; padding: 18px 0; cursor: pointer; list-style: none; }
.research-peek summary::-webkit-details-marker { display: none; }
.research-peek summary strong { font-size: 17px; font-weight: 500; }
.peek-date { font-size: 15px; font-weight: 600; color: var(--global-text-color); }
.peek-role { display: block; margin-top: 4px; font-size: 14px; color: var(--global-text-color); }
.peek-meta { display: block; margin-top: 3px; font-size: 14px; color: var(--global-text-color-light); }
.peek-plus { color: var(--global-theme-color); text-align: center; }
.peek-plus::before { content: "+"; }
.research-peek[open] .peek-plus::before { content: "−"; }
.research-peek[open] summary strong { color: var(--global-theme-color); }
.research-peek summary:focus-visible { outline: 2px solid var(--global-theme-color); outline-offset: 3px; }
.peek-panel { margin: 0 0 24px 264px; padding: 0 16px; border-left: 2px solid var(--global-divider-color); font-size: 15px; line-height: 1.65; }
.peek-panel p { margin: 0 0 12px; }
.peek-panel p:last-child { margin-bottom: 0; }
@media(max-width: 700px) {
 .research-peek summary { grid-template-columns: minmax(0, 1fr) 20px; gap: 4px 12px; }
 .peek-date { grid-column: 1; }
 .research-peek summary > span:nth-child(2) { grid-column: 1; }
 .peek-plus { grid-column: 2; grid-row: 1 / 3; }
 .peek-panel { margin: 0 0 20px; padding: 0 14px; }
}
</style>
<div class="academic-home">
  <div class="academic-intro">
    <aside class="portrait-column" aria-label="Profile photo and contact links">
      <img src="{{ '/eunho.jpg' | relative_url }}" alt="Portrait of Eunho Koh" width="685" height="898">
      <p class="profile-cv"><a href="{{ "/CV.pdf" | relative_url }}?v=20261113">Curriculum Vitae</a></p>
      <div class="profile-links">
        <a href="mailto:ehko030715@unist.ac.kr" aria-label="Email Eunho Koh" title="Email"><i class="fa-solid fa-envelope" aria-hidden="true"></i></a>
        <a href="https://github.com/eunho03" aria-label="Eunho Koh on GitHub" title="GitHub"><i class="fa-brands fa-github" aria-hidden="true"></i></a>
      </div>
    </aside>
    <div class="academic-bio">
      <h1>Eunho Koh</h1>
      <p class="affiliation">Computer Science and Engineering · UNIST</p>
      <p>I am an undergraduate student in Computer Science and Engineering at <a href="https://www.unist.ac.kr/">UNIST</a>. My research interests lie in <strong>Human-Computer Interaction (HCI)</strong> and <strong>Human-Centered AI</strong>, with a focus on AI evaluation, reliable machine learning, and distribution shift.</p>

      <p>My experience includes reinforcement learning, graph-based community detection, and applied data analysis. My proposed K-SHIFT project focuses on diagnostic evaluation of Korean natural language inference.</p>

      <p class="detail"><a href="{{ '/projects/' | relative_url }}">Research &amp; projects</a> · <a href="mailto:ehko030715@unist.ac.kr">Email</a></p>
    </div>
  </div>
  <section class="academic-section" aria-labelledby="interests-heading">
    <h2 id="interests-heading">research interests</h2>
    <p>Human-Computer Interaction (HCI) · Human-Centered AI · AI Evaluation · Reliable Machine Learning · Distribution Shift</p>
  </section>
  <section class="academic-section" aria-labelledby="experience-heading">
    <h2 id="experience-heading">research experience</h2>
    <details class="research-peek">
      <summary><span class="peek-date">Jun 2026 – Aug 2026</span><span><strong>AI-CORE Lab</strong><span class="peek-role">Reinforcement Learning Research Intern</span></span><span class="peek-plus" aria-hidden="true"></span></summary>
      <div class="peek-panel"><p><strong>Activity</strong><br>Reviewed offline reinforcement learning papers, including conservative value estimation and distribution correction. Presented research seminars and led a textbook study group on reinforcement learning fundamentals.</p><p><a href="https://sites.google.com/view/unist-aicorelab">AI-CORE Lab</a> · <a href="https://www.ysjang.me/">Prof. YoungSoo Jang</a></p></div>
    </details>
    <details class="research-peek">
      <summary><span class="peek-date">Apr 2026 – Oct 2026</span><span><strong>Data Mining Lab · AICP</strong><span class="peek-role">Research Participant · Research poster co-author</span></span><span class="peek-plus" aria-hidden="true"></span></summary>
      <div class="peek-panel"><p><strong>Research topic</strong><br>Embedding-Based Structure-Preserving Graph Rewiring for Community Detection</p><p><a href="https://sites.google.com/view/dm-unist/home">Data Mining Lab</a> · <a href="https://sites.google.com/view/junghoon-kim">Prof. Junghoon Kim</a><br><a href="https://bts.unist.ac.kr/pgdocument/aicp">Artificial Intelligence Challengers Program</a></p></div>
    </details>
    <details class="research-peek">
      <summary><span class="peek-date">Apr 2026 – Jul 2026</span><span><strong>Insurance Enrollment Prediction</strong><span class="peek-role">Collaborative Research Participant</span><span class="peek-meta">Korea Workers’ Compensation &amp; Welfare Service</span></span><span class="peek-plus" aria-hidden="true"></span></summary>
      <div class="peek-panel"><p>Conducted exploratory data analysis and geocoded enrolled businesses’ addresses using the Kakao API to visualize their spatial distribution.</p></div>
    </details>
  </section>
  <section class="academic-section" aria-labelledby="projects-heading">
    <h2 id="projects-heading">selected projects</h2>
    <p class="detail">Coursework and competition contributions. Proposed work is listed separately below.</p>
    <div class="academic-row">
      <div class="academic-date">Mar 2026 – Jun 2026</div>
      <div><h3><a href="{{ '/projects/' | relative_url }}#batt-route">BATT-Route</a></h3><p class="detail">Battery-aware routing for mobile LLM services · 4-member team</p><p>Proposed battery-aware edge-cloud LLM routing and implemented the routing algorithm using battery level and query characteristics. Selected evaluation datasets and established baselines.</p></div>
    </div>
    <div class="academic-row">
      <div class="academic-date">Sep 2026 – Oct 2026</div>
      <div><h3><a href="{{ '/projects/' | relative_url }}#manufacturing">K-AI Manufacturing Data Analysis Competition</a></h3><p class="detail">EDA &amp; feature engineering · 3-member team</p><p>Identified duplicated power-use patterns, integrated weather and holiday data, and screened approximately 100 candidate features using a random forest with SHAP and permutation importance.</p></div>
    </div>
    <h3>Proposed research</h3>
    <div class="academic-row">
      <div class="academic-date">Sep 2026 – present</div>
      <div><h3><a href="{{ '/projects/' | relative_url }}#k-shift">K-SHIFT</a></h3><p class="detail">Korean NLI evaluation · 2-member team · Proposal stage</p><p>Formulated a research question and reviewed prior work on diagnostic testing under changes in negation, quantity, and conditional expressions. My planned role is experimental design; a teammate will conduct implementation and experiments.</p></div>
    </div>
  </section>
  <section class="academic-section" aria-labelledby="education-heading">
    <h2 id="education-heading">education</h2>
    <div class="academic-row">
      <div class="academic-date">Mar 2022 – present</div>
      <div><h3><a href="https://www.unist.ac.kr/">UNIST</a></h3><p>B.S. in Computer Science and Engineering, in progress</p><p class="detail">Coursework: Mobile Computing, Data Structures, Database Systems.<br>Currently taking: Deep Learning and Introduction to Data Mining.</p></div>
    </div>
  </section>

  <section class="academic-section" aria-labelledby="honors-heading">
    <h2 id="honors-heading">honors &amp; service</h2>
    <div class="academic-row"><div class="academic-date">Sep 2026</div><div><h3>Student Merit Award · UNIST</h3><p>Team recognition for service through CSE Supporters, the CSE Student Council.</p></div></div>
    <div class="academic-row"><div class="academic-date">May 2023</div><div><h3>First Place · Student Startup Competition, KAIST</h3><p>Awarded to a five-member team by the Director of the KAIST Center for Entrepreneurship.</p></div></div>
    <div class="academic-row"><div class="academic-date">Leadership &amp; service</div><div><p>CSE Supporters member (Mar 2026–present); HeXA Computing Club member (Mar–Jul 2025); president of UNIST Startup Bible (Dec 2022–Sep 2023).</p><p>As USB president, secured KRW 8 million through Ulsan’s 2023 Youth Community Revitalization Program.</p><p><a href="{{ '/cv/' | relative_url }}">Full CV, skills &amp; background →</a></p></div></div>
  </section>
</div>
