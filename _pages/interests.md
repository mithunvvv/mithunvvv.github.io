---
permalink: /interests/
layout: page
title: "Interests"
---

<style>
.interests-page {
  max-width: 900px;
  margin: 0 auto;
  line-height: 1.65;
}

.interests-intro {
  margin: 0 0 2.5rem;
  font-size: 1.1em;
}

.interest-section {
  margin: 2.75rem 0;
}

.interest-section h2 {
  margin-bottom: 0.35rem;
}

.interest-section > p {
  margin-top: 0;
  color: #666;
}

.interest-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(min(100%, 220px), 1fr));
  gap: 1.25rem;
  margin: 1.25rem 0 0;
}

.interest-gallery figure {
  margin: 0;
  overflow: hidden;
  border: 1px solid #e5e5e5;
  border-radius: 10px;
  background: #fff;
  box-shadow: 0 3px 12px rgba(0, 0, 0, 0.06);
}

.interest-gallery img {
  display: block;
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
}

.interest-gallery figcaption {
  padding: 0.7rem 0.9rem;
  color: #555;
  font-size: 0.9em;
}

.interest-gallery--feature {
  grid-template-columns: minmax(0, 620px);
}

@media (max-width: 600px) {
  .interest-section {
    margin: 2.25rem 0;
  }
}
</style>

<div class="interests-page">

<p class="interests-intro">Outside of research, I enjoy getting outdoors, travelling, and taking photos. Here are a few snapshots from some of the places and activities I love.</p>

<section class="interest-section">
<h2>Outdoors</h2>

I love hiking and exploring the national parks of Canada's west coast.

<div class="interest-gallery interest-gallery--feature">
<figure>
  <img src="/files/yoho.png" alt="Hiking in Yoho National Park">
  <figcaption>Yoho National Park</figcaption>
</figure>
</div>
</section>

<section class="interest-section">
<h2>Travel</h2>

Some favourite trips have taken me to China, Egypt, and northern Canada, each offering its own mix of culture, food, and unforgettable scenery.

<div class="interest-gallery">
  <figure>
    <img src="/files/pku.png" alt="Peking University">
    <figcaption>Peking University</figcaption>
  </figure>

  <figure>
    <img src="/files/egypt.png" alt="Pyramids of Egypt">
    <figcaption>Pyramids of Egypt</figcaption>
  </figure>

  <figure>
    <img src="/files/nunavut.png" alt="Ice fishing in Iqaluit, Nunavut">
    <figcaption>Ice fishing in Iqaluit, Nunavut</figcaption>
  </figure>
</div>
</section>

<section class="interest-section">
<h2>Modelling &amp; Photography</h2>

I occasionally model and enjoy taking photographs, especially on evening walks through the city.

<div class="interest-gallery">
<figure>
  <img src="/files/soccor.jpg" alt="Casual modelling shoot">
  <figcaption>Casual shoot</figcaption>
</figure>

<figure>
  <img src="/files/facecard.jpg" alt="Late night in Chinatown, Toronto">
  <figcaption>Chinatown, Toronto, after dark</figcaption>
</figure>
</div>
</section>
</div>
