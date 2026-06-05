<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Happy Anniversary ❤️</title>

<link rel="stylesheet" href="style.css">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>

<body>

<!-- FLOATING ICONS -->
<div class="floating-container">
  <span>🖤</span>
  <span>📷</span>
  <span>✉️</span>
  <span>⭐</span>
</div>

<!-- MUSIC -->
<audio id="bgMusic" loop>
  <source src="assets/music/song.mp3" type="audio/mpeg">
</audio>

<!-- OPENING -->
<section id="opening" class="page active">

  <h1>Hi, Sayang.</h1>

  <p>
    Aku bikin sesuatu khusus buat kamu ✨
  </p>

  <button id="startBtn">
    Start Journey →
  </button>

</section>

<!-- GAME -->
<section id="game" class="page">

  <h2>Find The Stars ⭐</h2>

  <div class="score">
    <span id="score">0</span>/5
  </div>

  <div id="starArea"></div>

</section>

<!-- LOADING -->
<section id="loading" class="page">

  <h2 id="loadingText">
    Preparing your gift...
  </h2>

  <div class="loading-bar">
    <div id="progress"></div>
  </div>

  <div id="percent">0%</div>

</section>

<!-- MEMORY -->
<section id="memory" class="page">

  <div class="memory-wrapper">

    <div class="photo-card">
      <img src="assets/images/cover.jpg">
      <p>Our Favorite Memory</p>
    </div>

    <div class="envelope-wrapper">

      <div class="envelope" id="envelope">

        <div class="flap"></div>

        <div class="letter-preview">
          For You ❤️
        </div>

      </div>

      <p>Open Letter</p>

    </div>

  </div>

</section>

<!-- LETTER -->
<section id="letterPage" class="page">

  <div class="letter-box">

    <h2>Happy Anniversary ❤️</h2>

    <div class="letter-content">

      Happy 1 Year 1 Month Anniversary, Babe ❤️
      
Can't believe it's already been 1 year and 1 month with you. Time really flies when I'm with my favorite person. 🥺
Thank you for always accepting me for who I am, with all my flaws, moods, and everything that comes with me. Thank you for being so patient, understanding, and always trying to see things from my side even when I'm not at my best.
I honestly feel so lucky to have someone like you. You make me feel loved, safe, and appreciated every single day.
I hope you'll always stay the same sweet, caring, and patient guy that I've fallen in love with. And no matter what happens, I hope we keep growing together, supporting each other, and making more beautiful memories.
Thank you for always choosing me and loving me unconditionally. I love you so much, babe. Here's to many more months and years together. ❤️✨
Happy 1 year 1 month anniversary, my love. Forever sounds better with you. 🫶💕

      (GANTI ISI SURAT INI)

    </div>

    <button id="galleryBtn">
      Continue →
    </button>

  </div>

</section>

<!-- GALLERY -->
<section id="galleryPage" class="page">

  <h2>Our Memories 📸</h2>

  <div class="gallery">

    <img src="assets/images/gallery1.jpg">
    <img src="assets/images/gallery2.jpg">
    <img src="assets/images/gallery3.jpg">
    <img src="assets/images/gallery4.jpg">
    <img src="assets/images/gallery5.jpg">

  </div>

  <h2>Video Memory 🎥</h2>

  <video controls>
    <source src="assets/videos/memory.mp4">
  </video>

  <h2>Our Song 🎵</h2>

  <iframe
  src="https://open.spotify.com/embed/track/11dFghVXANMlKmJXsNCbNl"
  width="100%"
  height="152"
  frameborder="0"
  allowfullscreen>
  </iframe>

  <div class="ending">

    <h1>Happy Anniversary ❤️</h1>

    <p>
      Thank you for being part of my story.
    </p>

  </div>

</section>

<script src="script.js"></script>

</body>
</html>
