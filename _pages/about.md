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

.research-peek { position:relative; border-bottom:1px solid var(--global-divider-color); }
.research-peek summary { display:grid; grid-template-columns:220px 1fr 20px; gap:44px; align-items:start; padding:18px 0; cursor:pointer; list-style:none; }
.research-peek summary::-webkit-details-marker { display:none; }
.research-peek summary strong { font-size:17px; font-weight:500; }
.peek-date { font-size:15px; font-weight:600; color:var(--global-text-color); }
.peek-meta { font-size:14px; color:var(--global-text-color-light); }
.peek-meta { display:block; margin-top:3px; }
.peek-plus { color:var(--global-theme-color); }
.research-peek[open] { z-index:5; }
.research-peek[open] summary strong { color:var(--global-theme-color); }
.research-peek[open] .peek-plus { transform:rotate(45deg); }
.research-peek summary:focus-visible { outline:2px solid var(--global-theme-color); outline-offset:3px; }
.peek-panel { position:absolute; left:264px; right:0; top:calc(100% - 4px); padding:20px 24px; background:var(--global-bg-color); border:1px solid var(--global-divider-color); border-radius:6px; box-shadow:0 8px 28px #00000018; font-size:15px; line-height:1.65; }
.peek-panel p { margin:0 0 12px; }
.peek-panel p:last-child { margin-bottom:0; }
@media(max-width:700px) { .research-peek summary { grid-template-columns:1fr 20px; gap:4px 12px; } .peek-date { grid-column:1; } .research-peek summary>span:nth-child(2) { grid-column:1; } .peek-plus { grid-column:2; grid-row:1 / 3; } .peek-panel { position:static; margin-bottom:15px; padding:16px; box-shadow:none; } }
@media print { .research-peek .peek-panel { display:block; position:static; box-shadow:none; } }
</style>
<div class="academic-home">
  <div class="academic-intro">
    <aside class="portrait-column" aria-label="Profile photo and contact links">
      <img src="{{ '/eunho.jpg' | relative_url }}" alt="Portrait of Eun Ho Koh" width="685" height="898">
      <p class="profile-cv"><a href="{{ "/CV.pdf" | relative_url }}?v=20261102-3">Curriculum Vitae</a></p>
      <div class="profile-links">
        <a href="mailto:ehko030715@unist.ac.kr" aria-label="Email Eun Ho Koh" title="Email"><i class="fa-solid fa-envelope" aria-hidden="true"></i></a>
        <a href="https://github.com/eunho03" aria-label="Eun Ho Koh on GitHub" title="GitHub"><i class="fa-brands fa-github" aria-hidden="true"></i></a>
      </div>
    </aside>
    <div class="academic-bio">
      <h1>Eun Ho Koh</h1>
      <p class="affiliation">Computer Science and Engineering · UNIST</p>
      <p>I am an undergraduate student in Computer Science and Engineering at <a href="https://www.unist.ac.kr/">UNIST</a>. I am interested in how data quality and composition affect model learning and generalization, particularly when deployment conditions differ from training.</p>

      <p class="detail"><a href="{{ '/projects/' | relative_url }}">Research &amp; projects</a> · <a href="mailto:ehko030715@unist.ac.kr">Email</a></p>
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
    <h2 id="experience-heading">research experience</h2>
    <details class="research-peek">
      <summary><span class="peek-date">Jun 2026 – Aug 2026</span><span><strong>Reinforcement Learning</strong><span class="peek-meta">AI-CORE Lab</span></span><span class="peek-plus" aria-hidden="true">+</span></summary>
      <div class="peek-panel"><p><strong>Activity</strong><br>Reviewed reinforcement learning papers in weekly meetings, presented seminars, and led an intern textbook study group.</p><p><a href="https://sites.google.com/view/unist-aicorelab">AI-CORE Lab</a> · <a href="https://www.ysjang.me/">Prof. YoungSoo Jang</a></p></div>
    </details>
    <details class="research-peek">
      <summary><span class="peek-date">Apr 2026 – Oct 2026</span><span><strong>Graph Community Detection</strong><span class="peek-meta">Data Mining Lab · AICP</span></span><span class="peek-plus" aria-hidden="true">+</span></summary>
      <div class="peek-panel"><p><strong>Research poster co-author</strong><br>Embedding-Based Structure-Preserving Graph Rewiring for Community Detection</p><p><a href="https://sites.google.com/view/dm-unist/home">Data Mining Lab</a> · <a href="https://sites.google.com/view/junghoon-kim">Prof. Junghoon Kim</a><br><a href="https://bts.unist.ac.kr/pgdocument/aicp">Artificial Intelligence Challengers Program</a></p></div>
    </details>
    <details class="research-peek">
      <summary><span class="peek-date">Apr 2026 – Jul 2026</span><span><strong>Insurance Enrollment Prediction</strong><span class="peek-meta">Korea Workers’ Compensation &amp; Welfare Service</span></span><span class="peek-plus" aria-hidden="true">+</span></summary>
      <div class="peek-panel"><p><strong>Role</strong><br>Collaborative Research Participant</p></div>
    </details>
  </section>
</div>

<script>
document.querySelectorAll('.research-peek').forEach(function(item) {
  const summary = item.querySelector('summary');
  let pinned = false;
  item.addEventListener('pointerenter', function(event) {
    if (event.pointerType === 'mouse') item.open = true;
  });
  item.addEventListener('pointerleave', function() {
    if (!pinned && !item.contains(document.activeElement)) item.open = false;
  });
  summary.addEventListener('click', function(event) {
    event.preventDefault();
    pinned = !pinned;
    item.open = pinned;
  });
  item.addEventListener('focusout', function(event) {
    if (!pinned && !item.contains(event.relatedTarget)) item.open = false;
  });
  item.addEventListener('keydown', function(event) {
    if (event.key === 'Escape') {
      pinned = false;
      item.open = false;
      summary.focus();
    }
  });
});
</script>
