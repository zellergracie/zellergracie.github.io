---
layout: default
title: Gracie Zeller
---

<div class="hero">
  <div class="hero-inner" style="display: flex; justify-content: space-between; align-items: flex-start; gap: 2rem;">
    <div>
      <p><strong>Laboratory manager at UW-Madison.</strong></p>
      <p>I'm interested in children's conceptual development and the origins of numerical cognition. I currently work as a laboratory manager in <a href="https://cognitiveoriginslab.psych.wisc.edu/">Steve Ferrigno's Cognitive Origins lab</a>. In Fall 2026, I will be joining <a href="https://cognitiveconstructionlab.com/">Ben Pitt's lab</a> at UMass-Amherst as a PhD student.</p>
    </div>
    <img src="/headshot.jpg" alt="Gracie Zeller"
      style="width: 140px; height: 140px; object-fit: cover; border-radius: 6px; flex-shrink: 0; border: 1px solid #d9cfc0;">
  </div>
</div>

<div class="divider"></div>

<section id="work">
  <p class="section-label">projects</p>
  <div class="work-item" onclick="toggleAbstract(this)">
    <span class="work-title">One-to-one correspondence in children and macaques</span>
    <span class="work-year">2026</span>
    <span class="work-abstract">
      We found that cardinal principle knowledge is neither necessary nor sufficient to use one-to-one correspondence cues to make precise quantity discriminations. This challenges most existing accounts of how children learn the relationship between one-to-one correspondence and numerical equality. You can find our Cognitive Development Society poster <a href="/CDS_2026_poster.pdf" target="_blank" onclick="event.stopPropagation()">here</a>.
    </span>
  </div>
</section>

<div class="divider"></div>

<section id="cv">
  <p class="section-label">curriculum vitae</p>
  <p><a href="/cv.pdf" target="_blank" class="cv-link">cv</a></p>
</section>

<div class="divider"></div>

<section id="contact">
  <p class="section-label">contact</p>
  <div class="contact-links">
    <p><a href="#" id="email-link">email</a></p>
    <script>
      const u = 'gzeller2';
      const d = 'wisc.edu';
      const el = document.getElementById('email-link');
      el.href = 'mailto:' + u + '@' + d;
      el.textContent = u + '@' + d;
    </script>
    <p><a href="https://bsky.app/profile/zellergracie.bsky.social" target="_blank">bluesky</a></p>
    <p><a href="https://www.linkedin.com/in/gracie-zeller" target="_blank">linkedin</a></p>
  </div>
</section>
