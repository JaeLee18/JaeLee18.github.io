---
permalink: /
title: "About Lee, Jae Joong"
excerpt: "About me"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

- Jae Joong Lee is a Computer Science Ph.D. candidate at Purdue University, advised by [Prof. Bedrich Benes](https://www.cs.purdue.edu/homes/bbenes/) in the [Computer Graphics and Visualization Laboratory](https://www.cs.purdue.edu/homes/bbenes/students/). He works at the intersection of computer vision, 3D graphics, and generative AI to create digital twins.
  <br/>
- Jae Joong Lee received a Bachelor's Degree in Computer Science at [Purdue University](https://www.purdue.edu/).

<style>
.quicknav {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0.4em 0 1.6em;
}
.quicknav a {
  display: inline-block;
  padding: 6px 14px;
  border: 1px solid #d7dbe2;
  border-radius: 6px;
  background: #fff;
  color: #1e3a5f;
  font-size: 0.9em;
  font-weight: 600;
  text-decoration: none;
  transition: background 0.15s ease, color 0.15s ease, border-color 0.15s ease;
}
.quicknav a:hover { background: #1e3a5f; border-color: #1e3a5f; color: #fff; }
/* keep section targets clear of the sticky nav when jumping */
.page__content h1, .page__content h2 { scroll-margin-top: 80px; }
</style>

<div class="quicknav">
<a href="#publications">Publications</a>
<a href="#fundings">Fundings</a>
<a href="#work-experience">Work Experience</a>
<a href="#teaching">Teaching</a>
<a href="#awards">Awards</a>
<a href="#services">Services</a>
</div>

## Updates <span style="font-weight:400;font-size:0.7em;color:#888;">(last updated July 10, 2026)</span>
{: #updates}

<style>
.updates-box {
  max-height: 320px;
  overflow-y: auto;
  padding: 0.2em 1.1em 0.2em 0.9em;
  border: 1px solid #e3e3e3;
  border-radius: 8px;
  background: #fafafa;
  margin-bottom: 1.2em;
}
.updates-box ul { list-style: none; margin: 0; padding: 0; }
.updates-box li {
  padding: 0.6em 0.2em;
  border-bottom: 1px solid #ededed;
  line-height: 1.55;
}
.updates-box li:last-child { border-bottom: none; }
.updates-box a { color: #2c5282; }
/* Firefox */
.updates-box { scrollbar-width: thin; scrollbar-color: #c2c2c2 transparent; }
/* WebKit (Chrome/Safari/Edge) */
.updates-box::-webkit-scrollbar { width: 9px; }
.updates-box::-webkit-scrollbar-track { background: transparent; }
.updates-box::-webkit-scrollbar-thumb { background: #c2c2c2; border-radius: 5px; }
.updates-box::-webkit-scrollbar-thumb:hover { background: #9c9c9c; }
</style>

<div class="updates-box">
<ul>
<li>📜 My paper, <strong>Accuracy Without Grounding: Measuring the Visual Dependency Gap in Video LLM Benchmarks</strong>, is accepted to ACM Multimedia (ACM MM) 2026!</li>
<li>📜 My paper on <strong>plant point cloud completion from occluded scans</strong> has been accepted to <em>Plant Phenomics</em> (IF 8.2).</li>
<li>🏆 My proposal was selected for the Google Research Computing Grant.</li>
<li>🎉 Tree-D fusion is featured in the Re-Leaf exhibition at Rome’s <a href="https://www.palazzoesposizioniroma.it/mostra/re-leaf-vedere-la-citta-attraverso-i-suoi-alberi">Palazzo delle Esposizioni</a> in collaboration with the MIT Senseable City Lab.</li>
<li>📜 My paper, Tuning-Free Amodal Segmentation via the Occlusion-Free Bias of Inpainting Models, is accepted to AAAI 2026. (Acceptance Rate: 17.6%) <a href="https://arxiv.org/pdf/2503.18947">Paper</a></li>
<li>🎉 I was awarded GPU funding from the National Artificial Intelligence Research Resource Pilot as a PI.</li>
<li>🎉 I will join Zillow Group as an AI Applied Scientist Intern specializing in Computer Vision.</li>
<li>🏆 I was honored to receive the John R. Rice Partial Fellowship in Scientific Computing from the Department of Computer Science at Purdue University.</li>
<li>🤝 My work, Tree-D fusion, is used in the <a href="https://www.labiennale.org/en/architecture/2025/artificial/re-leaf">19th International Architecture Exhibition Biennale Venice, Re-Leaf Project</a> in collaboration with <a href="https://senseable.mit.edu/">MIT Senseable City Lab</a>.</li>
<li>📰 My recent work, Tree-D fusion, is covered by <a href="https://news.mit.edu/2024/advancing-urban-tree-monitoring-ai-powered-digital-twins-1121">MIT News</a> and <a href="https://ag.purdue.edu/news/2025/03/3d-tree-reconstruction-algorithm-contributes-to-a-new-era-of-urban-planning.html?feature">Purdue News</a>.</li>
<li>📜 Another paper, Single Image to 3D Point Cloud, is accepted to WACV 2025. <a href="https://www.jaejoonglee.com/wacv25_rgb2point/">Project Website</a></li>
<li>📜 My paper, Tree-D Fusion, is accepted to ECCV 2024. See you in Milan, Italy🇮🇹. <a href="https://www.jaejoonglee.com/treedfusion/">Project Website</a></li>
<li>🎉 Received Merit Recognition Award from Purdue University.</li>
<li>📜 "Latent L-systems: Transformer-based Tree Generator" is accepted to ACM Transactions on Graphics, and invited to present at SIGGRAPH2024!</li>
<li>🎉 Offered Samsung Electronics Scholarship.</li>
<li>I got a deep learning certification from the NVIDIA Deep Learning Institute.</li>
<li>💥 Finished Ph.D. Core Requirements <span style="font-size:0.85em;color:#777;">(Equivalent to a qualification exam in other universities.)</span></li>
<li>Started the first Ph.D. program semester in CS at Purdue University.</li>
<li>🎓 Received Bachelor of Science in Computer Science (CS) at Purdue University.</li>
</ul>
</div>

# Publications

<style>
.pubs {
  max-height: 660px;
  overflow-y: auto;
  padding: 0.4em 0.9em 0.4em 0.2em;
  margin-bottom: 1.2em;
}
/* Firefox */
.pubs { scrollbar-width: thin; scrollbar-color: #c2c2c2 transparent; }
/* WebKit (Chrome/Safari/Edge) */
.pubs::-webkit-scrollbar { width: 9px; }
.pubs::-webkit-scrollbar-track { background: transparent; }
.pubs::-webkit-scrollbar-thumb { background: #c2c2c2; border-radius: 5px; }
.pubs::-webkit-scrollbar-thumb:hover { background: #9c9c9c; }

.pub-card {
  display: flex;
  align-items: center;
  gap: 20px;
  padding: 16px;
  margin-bottom: 16px;
  border: 1px solid #e3e3e3;
  border-radius: 10px;
  background: #fff;
  box-shadow: 0 1px 3px rgba(0,0,0,0.06);
  transition: transform 0.15s ease, box-shadow 0.15s ease;
}
.pub-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 6px 18px rgba(0,0,0,0.10);
}
.pub-thumb { flex: 0 0 320px; max-width: 320px; }
.pub-thumb img { width: 100%; height: auto; border-radius: 6px; display: block; }
.pub-card h3 { margin-top: 0; margin-bottom: 0.35em; line-height: 1.3; }
.pub-authors { margin-bottom: 0.25em; }
.pub-venue { color: #555; font-style: italic; margin-bottom: 0.6em; }
.pub-links a {
  display: inline-block;
  padding: 7px 16px;
  margin: 4px 6px 0 0;
  background-color: #1e3a5f;
  color: #fff;
  text-decoration: none;
  border-radius: 4px;
  font-size: 0.9em;
}
.pub-links a:hover { background-color: #16293f; }

@media (max-width: 600px) {
  .pub-card { flex-direction: column; align-items: flex-start; }
  .pub-thumb { flex: 0 0 auto; width: 100%; max-width: 100%; }
}

/* ---- Topic tabs ---- */
.pub-tabs {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin: 0.4em 0 1.1em;
}
.pub-tab {
  -webkit-appearance: none;
  appearance: none;
  border: 1px solid #d7dbe2;
  background: #fff;
  color: #1e3a5f;
  font: inherit;
  font-size: 0.9em;
  font-weight: 600;
  padding: 7px 15px;
  border-radius: 6px;
  cursor: pointer;
  transition: background 0.15s ease, color 0.15s ease, border-color 0.15s ease, box-shadow 0.15s ease;
}
.pub-tab:hover { border-color: #1e3a5f; }
.pub-tab.is-active {
  background: #1e3a5f;
  border-color: #1e3a5f;
  color: #fff;
  box-shadow: 0 2px 8px rgba(30, 58, 95, 0.25);
}
.pub-card.is-hidden { display: none; }
</style>

<div class="pub-tabs">
<button type="button" class="pub-tab is-active" data-filter="selected">⭐ Selected</button>
<button type="button" class="pub-tab" data-filter="all">All</button>
<button type="button" class="pub-tab" data-filter="3d">3D Vision</button>
<button type="button" class="pub-tab" data-filter="gen">Generative AI</button>
<button type="button" class="pub-tab" data-filter="vlm">Vision-Language</button>
<button type="button" class="pub-tab" data-filter="vr">VR &amp; HCI</button>
</div>

<div class="pubs">
<div class="pub-card" data-topics="selected vlm">
<div class="pub-thumb"><img src="/images/ACM_MM_VDG.png" alt="accuracy without grounding teaser"></div>
<div class="pub-body">
<h3>Accuracy Without Grounding: Measuring the Visual Dependency Gap in Video LLM Benchmarks</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong></div>
<div class="pub-venue">ACM International Conference on Multimedia (ACM MM), 2026</div>
<div class="pub-links"></div>
</div>
</div>
<div class="pub-card" data-topics="3d">
<div class="pub-thumb"><img src="/images/a-occ-plant.png" alt="a-occ-plant teaser"></div>
<div class="pub-body">
<h3>A-Occ-Plant: Plant Occluded Point Cloud Completion via Amodal Segmentation</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong>, Bedrich Benes</div>
<div class="pub-venue">Plant Phenomics, 2026</div>
<div class="pub-links"><a href="https://doi.org/10.1016/j.plaphe.2026.100240">Paper</a><a href="https://github.com/JaeLee18/PlantPhenomics_Occlusion">Code</a></div>
</div>
</div>
<div class="pub-card" data-topics="vlm">
<div class="pub-thumb"><img src="/images/lgip.png" alt="lgip teaser"></div>
<div class="pub-body">
<h3>Language-Guided Invariance Probing of Vision Language Models</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong></div>
<div class="pub-venue">Pattern Recognition Letters, April 2026</div>
<div class="pub-links"><a href="https://arxiv.org/pdf/2511.13494">Paper</a><a href="https://github.com/JaeLee18/Language-Guided-Invariance-Probing-of-Vision-Language-Models">Code</a></div>
</div>
</div>
<div class="pub-card" data-topics="3d gen">
<div class="pub-thumb"><img src="/images/top2ground.png" alt="top2ground teaser"></div>
<div class="pub-body">
<h3>Top2Ground: A Height-Aware Dual Conditioning Diffusion Model for Robust Aerial-to-Ground View Generation</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong>, and Bedrich Benes</div>
<div class="pub-venue">arXiv</div>
<div class="pub-links"><a href="https://arxiv.org/pdf/2511.08258">Paper</a></div>
</div>
</div>
<div class="pub-card" data-topics="vlm">
<div class="pub-thumb"><img src="/images/access.jpg" alt="accessibility teaser"></div>
<div class="pub-body">
<h3>WebAccessVL: Making an Accessible Web via Violation-Conditioned VLM</h3>
<div class="pub-authors">Amber Yijia Zheng*, <strong>Jae Joong Lee*</strong>, Bedrich Benes, Raymond A. Yeh</div>
<div class="pub-venue">arXiv</div>
<div class="pub-links"><a href="https://arxiv.org/abs/2602.03850">Paper</a></div>
</div>
</div>
<div class="pub-card" data-topics="selected gen">
<div class="pub-thumb"><img src="/images/tuningfreeamodal.png" alt="tuningfreeamodal"></div>
<div class="pub-body">
<h3>Tuning-Free Amodal Segmentation via the Occlusion-Free Bias of Inpainting Models</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong>, Bedrich Benes and Raymond A. Yeh</div>
<div class="pub-venue">Association for the Advancement of Artificial Intelligence (AAAI), 2026</div>
<div class="pub-links"><a href="https://arxiv.org/pdf/2503.18947">Paper</a></div>
</div>
</div>
<div class="pub-card" data-topics="vr">
<div class="pub-thumb"><img src="/images/handsfreevr.png" alt="handsfreevr"></div>
<div class="pub-body">
<h3>Hands Free VR: LLM-based voice command VR</h3>
<div class="pub-authors">Jorge Askur Vazquez Fernandez*, <strong>Jae Joong Lee*</strong>, Santiago Andres Serrano Vacca, Alejandra Magana, Radim Pesa, Bedrich Benes and Voicu Popescu</div>
<div class="pub-venue">VISIGRAPP, 2025</div>
<div class="pub-links"><a href="https://arxiv.org/pdf/2402.15083">Paper</a></div>
</div>
</div>
<div class="pub-card" data-topics="selected 3d gen">
<div class="pub-thumb"><img src="/images/rgb2point.png" alt="rgb2point"></div>
<div class="pub-body">
<h3>RGB2Point: 3D Point Cloud Generation from Single RGB Images</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong>, Bedrich Benes</div>
<div class="pub-venue">IEEE/CVF Winter Conference on Applications of Computer Vision (WACV), 2025</div>
<div class="pub-links"><a href="https://www.arxiv.org/abs/2407.14979">Paper</a><a href="https://github.com/JaeLee18/RGB2point">Code</a><a href="https://www.jaejoonglee.com/wacv25_rgb2point/">Project</a></div>
</div>
</div>
<div class="pub-card" data-topics="selected 3d gen">
<div class="pub-thumb"><img src="/images/treedfusion.png" alt="treedfusion"></div>
<div class="pub-body">
<h3>Tree-D Fusion: Simulation-Ready Tree Dataset from Single Images with Diffusion Priors</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong>, Bosheng Li, Sara Beery, Jonathan Huang, Songlin Fei, Raymond A. Yeh, Bedrich Benes</div>
<div class="pub-venue">European Conference on Computer Vision (ECCV), 2024</div>
<div class="pub-links"><a href="https://www.arxiv.org/abs/2407.10330">Paper</a><a href="https://www.youtube.com/watch?v=SQzMkt3bt0E">Video</a><a href="https://github.com/JaeLee18/TreeDFusion_ECCV24">Code</a><a href="https://www.jaejoonglee.com/treedfusion/">Project</a></div>
</div>
</div>
<div class="pub-card" data-topics="selected gen">
<div class="pub-thumb"><img src="/images/latentlsystem.png" alt="Latent L-systems"></div>
<div class="pub-body">
<h3>Latent L-systems: Transformer-based Tree Generator</h3>
<div class="pub-authors"><strong>Jae Joong Lee</strong>, Bosheng Li, Bedrich Benes</div>
<div class="pub-venue">ACM Transactions on Graphics (ACM ToG), 2024 (SIGGRAPH Oral)</div>
<div class="pub-links"><a href="https://dl.acm.org/doi/10.1145/3627101">Paper</a><a href="https://www.youtube.com/watch?v=1SPSQ-IwcvQ">Video</a><a href="https://github.com/JaeLee18/ACM-TOG-Latent-L-systems-Transformer-based-Tree-Generator">Code</a></div>
</div>
</div>
</div>

<script>
(function () {
  var tabs = document.querySelectorAll('.pub-tabs .pub-tab');
  var cards = document.querySelectorAll('.pubs .pub-card');
  function countFor(filter) {
    if (filter === 'all') { return cards.length; }
    var n = 0;
    cards.forEach(function (card) {
      var topics = (card.getAttribute('data-topics') || '').split(/\s+/);
      if (topics.indexOf(filter) !== -1) { n++; }
    });
    return n;
  }
  tabs.forEach(function (tab) {
    tab.textContent += ' (' + countFor(tab.getAttribute('data-filter')) + ')';
  });
  function applyFilter(filter) {
    cards.forEach(function (card) {
      var topics = (card.getAttribute('data-topics') || '').split(/\s+/);
      var show = (filter === 'all') || topics.indexOf(filter) !== -1;
      card.classList.toggle('is-hidden', !show);
    });
  }
  tabs.forEach(function (tab) {
    tab.addEventListener('click', function () {
      tabs.forEach(function (t) { t.classList.remove('is-active'); });
      tab.classList.add('is-active');
      applyFilter(tab.getAttribute('data-filter'));
    });
  });
  applyFilter('selected');
})();
</script>

# Fundings

- Google Research Grant, PI, 2026
- NSF NAIRR Grant, PI, 2025

# Work Experience

<style>
.exp-list { margin-bottom: 1.2em; }
.exp-item { padding: 0.85em 0; border-bottom: 1px solid #ededed; }
.exp-item:last-child { border-bottom: none; }
.exp-head {
  display: flex;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 2px 16px;
  align-items: baseline;
}
.exp-role { font-size: 1.05em; }
.exp-role strong { color: #1e3a5f; }
.exp-date { color: #5b6675; font-size: 0.9em; white-space: nowrap; }
.exp-desc { color: #444; margin-top: 0.25em; line-height: 1.55; }
</style>

<div class="exp-list">
<div class="exp-item">
<div class="exp-head"><span class="exp-role"><strong>Zillow</strong> — Applied Scientist</span><span class="exp-date">May 2025 – Aug 2025</span></div>
<div class="exp-desc">Implemented a discrete VAE and latent diffusion backbone for high-fidelity indoor scene synthesis.</div>
</div>
<div class="exp-item">
<div class="exp-head"><span class="exp-role"><strong>Samsung Electronics</strong> — Research Scientist</span><span class="exp-date">May 2022 – Aug 2022</span></div>
<div class="exp-desc">Investigated out-of-distribution (OOD) detection using ResNet-based feature-space analysis to identify novel defects in semiconductor manufacturing.</div>
</div>
</div>

# Teaching

<div class="exp-list">
<div class="exp-item">
<div class="exp-head"><span class="exp-role"><strong>CS 177</strong> — Programming with Multimedia Objects (Python)</span><span class="exp-date">Aug 2021 – Dec 2022</span></div>
<div class="exp-desc">Graduate Teaching Assistant. Held office hours, automated grading scripts, and created exams and assignments.</div>
</div>
</div>

# Awards

<div class="exp-list">
<div class="exp-item">
<div class="exp-head"><span class="exp-role">John R. Rice Partial Fellowship in Scientific Computing</span><span class="exp-date">2025</span></div>
</div>
<div class="exp-item">
<div class="exp-head"><span class="exp-role">Purdue Employee Recognition Award</span><span class="exp-date">2024</span></div>
</div>
<div class="exp-item">
<div class="exp-head"><span class="exp-role">Samsung Electronics Excellence Scholarship</span><span class="exp-date">2022</span></div>
</div>
</div>

## Services
- Reviewer, SIGGRAPH
- Reviewer, IEEE/CVF Winter Conference on Applications of Computer Vision (WACV)
- Reviewer, IEEE/CVF Conference on Computer Vision and Pattern Recognition (CVPR)
- Reviewer, International Conference on Computer Vision (ICCV)
- Reviewer, IEEE Transactions on Visualization and Computer Graphics (TVCG)
- Reviewer, AAAI Conference on Artificial Intelligence (AAAI)
- Sergeant, KATUSA (Korean Augmentation to the United States Army), Eighth Army, U.S. Army, 2018–2020
