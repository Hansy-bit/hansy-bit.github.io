---
title: Origami
layout: page
---
Origami is the art of folding a single (1) piece of paper. Here are some of my work.

<style>
.origami-gallery {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(325px, 1fr));
  gap: 24px;
  margin-top: 1.5rem;
}
.origami-title {
  position: absolute;
  bottom: 0;
  left: 0;
  background: #fff;
  color: #222;
  font-weight: bold;
  font-size: 0.95rem;
  padding: 12px;
  box-sizing: border-box;
  max-height: 0;
  overflow-y: auto;
  opacity: 0;
  z-index: 11;
  transition: max-height 0.35s ease, opacity 0.35s ease;
}
.origami-title.expanded {
  max-height: 60px;
  opacity: 1;
  /* Wait for the image's 0.6s expand transition to finish before revealing. */
  transition: max-height 0.35s ease 0.4s, opacity 0.35s ease 0.4s;
}
.origami-item {
  position: relative;
  aspect-ratio: 1 / 1;
  overflow: visible;
}
.origami-item img {
  position: absolute;
  top: 50%;
  left: 50%;
  width: 100%;
  height: 100%;
  max-width: none;
  object-fit: cover;
  display: block;
  z-index: 0;
  transform: translate(-50%, -50%);
  box-shadow: 0 0 0 0 #fff;
  transition: width 0.6s ease, height 0.6s ease, transform 0.6s ease, box-shadow 0.6s ease;
}
.origami-item img.expandable {
  cursor: zoom-in;
}
.origami-item img.expanded {
  z-index: 10;
  box-shadow: 0 0 0px 12px #fff;
}
.origami-caption {
  position: absolute;
  top: 0;
  left: 0;
  background: #fff;
  color: #222;
  padding: 12px;
  font-size: 0.85rem;
  box-sizing: border-box;
  max-height: 0;
  overflow-y: auto;
  opacity: 0;
  z-index: 11;
  transition: max-height 0.35s ease, opacity 0.35s ease;
}
.origami-caption.expanded {
  max-height: 160px;
  opacity: 1;
  /* Wait for the image's 0.6s expand transition to finish before revealing. */
  transition: max-height 0.35s ease 0.4s, opacity 0.35s ease 0.4s;
}
</style>

<div class="origami-gallery">
  <div class="origami-item">
    <div class="origami-title">Walking in the Rain - Chen Xiao</div>
    <img src="assets/Origami/Lady%20in%20rain.jpg" class="expandable" alt="Lady in rain">
    <div class="origami-caption">★★★★★★ Super long project (~15h) with very tedious crease pattern but the payoff was worth it. Beautiful design and the umbrella was very creative. One of my first advance project and holds a special place in my heart.</div>
  </div>
  <div class="origami-item">
    <div class="origami-title">Nazgul - Jason Ku</div>
    <img src="assets/Origami/Nazgul.jpeg" class="expandable" alt="Nazgul">
    <div class="origami-caption"> ★★★★★ If I recall correctly this one wasn't box pleated, yet the design nicely captured various features for both the Nazgul and the horse with a single sheet of paper. Details on the claw, mane, and the structure of the hood is very nice.</div>
  </div>
  <div class="origami-item">
    <div class="origami-title">Maid — Chen Xiao</div>
    <img src="assets/Origami/Anime%20Girl.jpeg" class="expandable" alt="Anime Girl">
    <div class="origami-caption">★★★★★ A fascinating design, both the humanoid shape and the garments are captured very well. Using foil paper gave it a glow that wasn't really captured in the image</div>
  </div>
  <div class="origami-item">
    <div class="origami-title">SongBird — Robert J Lang</div>
    <img src="assets/Origami/Bird.jpg" class="expandable" alt="Bird">
    <div class="origami-caption">★★★☆☆ Simple, and elegant, but fragile. Added a metal wire to the inner frame to help it stand. </div>
  </div>
  <div class="origami-item">
    <div class="origami-title">Cat — Katsuta Kyohei</div>
    <img src="assets/Origami/Cat.jpg" class="expandable" alt="Cat">
    <div class="origami-caption">★★★★★ Evokes a joy of Origami when I fold this time and time again. Geometric, stylish, and satisfying, without being complicated </div>
  </div>
  <div class="origami-item">
    <div class="origami-title">Yodas — Fumiaki Kawahata</div>
    <img src="assets/Origami/Yodas.jpeg" class="expandable" alt="Yodas">
    <div class="origami-caption">★★★★☆ Folded this one with a friend. Unexpectedly well designed with many satisfying steps, but also a few fustrating ones.</div>
  </div>
  <div class="origami-item">
    <div class="origami-title">Pianist and Violinist — Robert J Lang</div>
    <img src="assets/Origami/Pianist%20and%20Violinist.jpg" class="expandable" alt="Pianist and Violinist">
    <div class="origami-caption"> ★★★★★ Simple, satisfying, great looking.</div>
  </div>
</div>

<br>
<br>
## Teaching
I've been teaching origami for the past 5 years and it's something I love. I've taught at highschool, college, for NGO, for Charlottesville, etc.

<div style="display:flex; gap:16px; justify-content:center; flex-wrap:wrap; margin-top:1.5rem;">
  <div style="flex:1 1 250px; max-width:300px; text-align:center;">
    <img src="assets/Origami/Teaching/Shannon.jpg" alt="Teaching in Shannon" style="width:100%;">
    <div style="font-size:0.75rem; color:#888; margin-top:4px;">Shannon</div>
  </div>
  <div style="flex:1 1 250px; max-width:300px; text-align:center;">
    <img src="assets/Origami/Teaching/Cville.jpg" alt="Teaching in Charlottesville" style="width:100%;">
    <div style="font-size:0.75rem; color:#888; margin-top:4px;">Charlottesville New Year</div>
  </div>
  <div style="flex:1 1 250px; max-width:300px; text-align:center;">
    <img src="assets/Origami/Teaching/Highschool.jpg" alt="Teaching at a high school" style="width:100%;">
    <div style="font-size:0.75rem; color:#888; margin-top:4px;">High school</div>
  </div>
</div>

<script>
document.querySelectorAll('.origami-item img.expandable').forEach(function (img) {
  var title = img.previousElementSibling;
  var caption = img.nextElementSibling;
  var ZOOM = 1.32;
  function expand() {
    var box = img.parentElement.clientWidth; // square side in px
    var nw = img.naturalWidth, nh = img.naturalHeight;
    if (!nw || !nh) return;
    var ratio = nw / nh;
    var width, height;
    // Keep the side that already fits at the box size, grow only the cropped
    // side to reveal the full image, then zoom in by ZOOM on top of that.
    if (ratio >= 1) {            // landscape: height fits, width was cropped
      height = box * ZOOM;
      width = box * ratio * ZOOM;
    } else {                     // portrait: width fits, height was cropped
      width = box * ZOOM;
      height = (box / ratio) * ZOOM;
    }
    img.style.width = width + 'px';
    img.style.height = height + 'px';
    img.classList.add('expanded');

    var gap = 8;
    var shadow = 12;

    if (title) {
      // Mirror the caption: pop the title out above the image, growing
      // upward, matching the zoomed image's visual (shadow-inclusive) width.
      title.style.width = (width + shadow * 2) + 'px';
      title.style.left = (((box - width) / 2) - shadow) + 'px';
      title.style.bottom = ((box + height) / 2 + gap) + 'px';
      title.classList.add('expanded');
    }

    if (caption) {
      // Drop the caption below the zoomed image, matching its width,
      // starting just under its bottom edge.
      caption.style.width = (width + shadow * 2) + 'px';
      caption.style.left = (((box - width) / 2) - shadow) + 'px';
      caption.style.top = ((box + height) / 2 + gap) + 'px';
      caption.classList.add('expanded');
    }
  }
  function reset() {
    img.style.width = '';
    img.style.height = '';
    img.classList.remove('expanded');

    // Leave width/left/top/bottom in place so they fade out where they are
    // instead of snapping back to their default position mid-transition.
    if (title) {
      title.classList.remove('expanded');
    }
    if (caption) {
      caption.classList.remove('expanded');
    }
  }
  img.addEventListener('mouseenter', expand);
  img.addEventListener('mouseleave', reset);
});
</script>