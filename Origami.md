---
title: Origami
layout: page
---
I love making & teaching origami. 
(Left) Teaching in Shannon; (Right) Teaching in IRC

<style>
.origami-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
  gap: 12px;
  margin-top: 1.5rem;
}
.origami-item {
  position: relative;
  border-radius: 4px;
  overflow: hidden;
}
.origami-item img {
  width: 100%;
  height: 250px;
  object-fit: cover;
  display: block;
}
.origami-caption {
  position: absolute;
  bottom: 0;
  left: 0;
  right: 0;
  background: rgba(0, 0, 0, 0.65);
  color: #fff;
  padding: 12px;
  font-size: 0.85rem;
  opacity: 0;
  transition: opacity 0.25s ease;
}
.origami-item:hover .origami-caption {
  opacity: 1;
}
</style>

<div class="origami-gallery">
  <div class="origami-item">
    <img src="assets/Origami/Anime Girl.jpeg" alt="Anime Girl">
    <div class="origami-caption">Your review here.</div>
  </div>
  <div class="origami-item">
    <img src="assets/Origami/Bird.jpg" alt="Bird">
    <div class="origami-caption">Your review here.</div>
  </div>
  <div class="origami-item">
    <img src="assets/Origami/Cat.jpg" alt="Cat">
    <div class="origami-caption">Your review here.</div>
  </div>
  <div class="origami-item">
    <img src="assets/Origami/Lady in rain.jpg" alt="Lady in rain">
    <div class="origami-caption">Your review here.</div>
  </div>
  <div class="origami-item">
    <img src="assets/Origami/Nazgul.jpeg" alt="Nazgul">
    <div class="origami-caption">Your review here.</div>
  </div>
  <div class="origami-item">
    <img src="assets/Origami/Pianist and Violinist.jpg" alt="Pianist and Violinist">
    <div class="origami-caption">Your review here.</div>
  </div>
  <div class="origami-item">
    <img src="assets/Origami/Yodas.jpeg" alt="Yodas">
    <div class="origami-caption">Your review here.</div>
  </div>
</div>
