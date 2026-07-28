---
permalink: /photos/
title: "Photo Gallery"
layout: single
author_profile: false
---

## Life Beyond the Lab
{: #gallery}

<div class="gallery-intro">
  A glimpse into my world outside of research — conferences, team outings, and everyday moments.
</div>

<!-- ====== ACADEMIC EVENTS ====== -->
<h3 class="gallery-category">🎤 Academic Events</h3>

<div class="gallery-grid">
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/academic/academic_01.jpg" loading="lazy" alt="Academic event" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/academic/academic_02.jpg" loading="lazy" alt="Academic event" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/academic/academic_03.jpg" loading="lazy" alt="Academic event" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/academic/academic_04.jpg" loading="lazy" alt="Academic event" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/academic/academic_05.jpg" loading="lazy" alt="Academic event" onclick="openLightbox(this.src)">
  </div>
</div>

<!-- ====== TEAM & FRIENDS ====== -->
<h3 class="gallery-category">🤝 Team &amp; Friends</h3>

<div class="gallery-grid">
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_01.png" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_02.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_03.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_04.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_05.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_06.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_07.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_08.jpg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/team/team_09.jpeg" loading="lazy" alt="Team photo" onclick="openLightbox(this.src)">
  </div>
</div>

<!-- ====== PERSONAL MOMENTS ====== -->
<h3 class="gallery-category">📸 Personal Moments</h3>

<div class="gallery-grid">
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_01.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_02.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_03.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_04.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_05.jpeg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_06.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_07.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_08.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
  <div class="gallery-item">
    <img src="{{ base_path }}/images/gallery/life/life_09.jpg" loading="lazy" alt="Personal moment" onclick="openLightbox(this.src)">
  </div>
</div>

<!-- Lightbox -->
<div id="lightbox" class="lightbox" onclick="closeLightbox()">
  <span class="lightbox-close">&times;</span>
  <img id="lightbox-img" src="" alt="Enlarged photo">
</div>

<script>
function openLightbox(src) {
  document.getElementById('lightbox-img').src = src;
  document.getElementById('lightbox').classList.add('active');
  document.body.style.overflow = 'hidden';
}
function closeLightbox() {
  document.getElementById('lightbox').classList.remove('active');
  document.body.style.overflow = '';
}
document.addEventListener('keydown', function(e) {
  if (e.key === 'Escape') closeLightbox();
});
</script>
