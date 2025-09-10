---
layout: page
permalink: /repositories/
title: Gallery
description: Beautiful memories along our research journey!
nav: true
nav_order: 7

photos:
  - src: /assets/img/gallery/AMS.jpg
    alt: Presenting at AMS 2025
    caption: Presenting at AMS 2025
  - src: /assets/img/gallery/AGU-talk.png
    alt: Presenting at AGU 2024
    caption: Presenting at AGU 2024
  - src: /assets/img/gallery/AGU-chair.png
    alt: Chairing at AGU 2024
    caption: Chairing at AGU 2024
  - src: /assets/img/gallery/Talk.png
    alt: FLUXNET workshop
    caption: FLUXNET workshop
  - src: /assets/img/gallery/ECN.png
    alt: FLUXNET-ECN committee
    caption: FLUXNET-ECN committee
  - src: /assets/img/gallery/Group.png
    alt: Workshop group discussion
    caption: FLUXNET workshop group discussion
  - src: /assets/img/gallery/AGU-poster.png
    alt: Presenting at AGU poster session.
    caption: Presenting at AGU poster session.
  - src: /assets/img/gallery/AmeriFlux workshop.jpg
    alt: Hosting AmeriFlux Early Career Workshop
    caption: Hosting AmeriFlux Early Career Workshop   
  - src: /assets/img/gallery/AmeriFlux Annual Meeting.png
    alt: AmeriFlux Annual Meeting
    caption: AmeriFlux Annual Meeting
  - src: /assets/img/gallery/Sensor.png
    alt: Sensors
    caption: Sensors
  - src: /assets/img/gallery/Tower.png
    alt: Site Visiting
    caption: Site Visiting
  - src: /assets/img/gallery/Students.jpg
    alt: Mentor team and students at LBNL
    caption: Mentor team and students at LBNL
  - src: /assets/img/gallery/AmeriFlux Team.jpg
    alt: With AmeriFlux Friends
    caption: With AmeriFlux Friends
  - src: /assets/img/gallery/GCP friends.jpg
    alt: With GCP Friends
    caption: With GCP Friends 
  - src: /assets/img/gallery/Visit Google.jpg
    alt: Visit Google in 2024
    caption: Visit Google in 2024
  - src: /assets/img/gallery/Google Intern.jpg
    alt: Working at Google in 2019
    caption: Working at Google in 2019
  - src: /assets/img/gallery/Google Hallowen.jpg
    alt: Halloween at Google
    caption: Halloween at Google


 
  - src: /assets/img/gallery/Methane Friends.jpg
    alt: With Methane Friends   
    caption: With Methane Friends   

  - src: /assets/img/gallery/Stanford.jpg
    alt: Stanford corridor
    caption: At Stanford
  - src: /assets/img/gallery/Yosemite1.jpg
    alt: At Yosemite
    caption: At Yosemite

  - src: /assets/img/gallery/Collorado.jpg
    alt: At Yosemite
    caption: At Colorado Boulder

---

<!-- jQuery（Lightbox2 依赖） -->
<script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.1/jquery.min.js"></script>
<!-- Lightbox2 -->
<link href="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/css/lightbox.min.css" rel="stylesheet">
<script src="https://cdnjs.cloudflare.com/ajax/libs/lightbox2/2.11.3/js/lightbox.min.js"></script>

<style>
.gallery{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:16px}
.gallery figure{margin:0;border-radius:12px;overflow:hidden;background:var(--global-bg-color,#fff);box-shadow:0 2px 8px rgba(0,0,0,.06)}
.gallery a{display:block;text-decoration:none;outline:none}
.gallery img{width:100%;display:block;aspect-ratio:4/3;object-fit:cover;transition:transform .25s ease}
.gallery a:hover img{transform:scale(1.03)}
.gallery figcaption{font-size:.9rem;line-height:1.4;color:var(--global-text-color,#333);text-align:center;padding:8px 10px 12px;background:var(--global-bg-color,#fff);border-top:1px solid var(--global-divider-color,#eee)}
</style>

<div class="gallery">
  {% for p in page.photos %}
  <figure>
    <a href="{{ p.src }}" data-lightbox="lab-gallery" data-title="{{ p.caption }}">
      <img src="{{ p.src }}" alt="{{ p.alt | default: p.caption }}" loading="lazy">
    </a>
    <figcaption>{{ p.caption }}</figcaption>
  </figure>
  {% endfor %}
</div>