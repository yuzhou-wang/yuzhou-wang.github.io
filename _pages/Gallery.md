---
layout: archive
title: "Gallery"
permalink: /photos/
author_profile: true
---

<style>
.gallery-grid {
  display: grid;
  grid-template-columns: 1fr 1fr; /* Creates exactly two columns */
  gap: 30px; /* Space between the photos */
  margin-top: 20px;
}

/* Mobile responsiveness: switch to 1 column on small screens */
@media (max-width: 600px) {
  .gallery-grid {
    grid-template-columns: 1fr; 
  }
}

.gallery-item {
  display: flex;
  flex-direction: column;
  align-items: center; /* Centers the caption */
}

.gallery-item img {
  width: 100%; /* Fills the column width */
  height: 250px; /* Sets a fixed height for uniformity */
  object-fit: cover; /* Crops the image slightly to fill the square without stretching */
  border-radius: 4px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}

.gallery-item img:hover {
  transform: scale(1.02); /* Subtle zoom effect on hover */
}

.gallery-caption {
  margin-top: 10px;
  font-size: 0.9em;
  color: #555;
  text-align: center;
  font-style: italic;
  line-height: 1.4;
}
</style>

<div class="gallery-grid">

  <div class="gallery-item">
    <img src="/images/news/Group_dinner2.jpg" alt="Group Dinner 2">
    <span class="gallery-caption">End of semester group dinner, Nov 2025.</span>
  </div>

  <div class="gallery-item">
    <img src="/images/news/Group_dinner1.jpg" alt="Group Dinner 1">
    <span class="gallery-caption">First group dinner, August 2025.</span>
  </div>


</div>
