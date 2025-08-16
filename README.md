<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Başkanım Doğum Günün Kutlu Olsun 🎂</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background: linear-gradient(135deg, #1e3c72, #2a5298);
      color: white;
      text-align: center;
      overflow-x: hidden;
    }
    h1 {
      margin-top: 20px;
      font-size: 2.5em;
    }
    p {
      font-size: 1.2em;
      margin-bottom: 20px;
    }
    .slideshow {
      max-width: 600px;
      margin: 20px auto;
      position: relative;
    }
    .slideshow img {
      width: 100%;
      border-radius: 20px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.5);
      display: none;
    }
    .slideshow img.active {
      display: block;
      animation: fade 2s;
    }
    @keyframes fade {
      from {opacity: 0.4;}
      to {opacity: 1;}
    }
    footer {
      margin-top: 20px;
      font-size: 0.9em;
      opacity: 0.8;
    }
  </style>
</head>
<body>
  <h1>🎂 Başkanım Doğum Günün Kutlu Olsun 🎂</h1>
  <p>Başkanım Doğum günün kutlu olsun. Geç kalınca farklı bir şey yapayım dedim. Seviliyorsun Başki ❤️</p>

  <div class="slideshow">
    <img src="eren1.jpg" class="active" alt="Fotoğraf 1">
    <img src="eren2.jpg" alt="Fotoğraf 2">
    <img src="eren3.jpg" alt="Fotoğraf 3">
    <img src="eren4.jpg" alt="Fotoğraf 4">
    <img src="eren5.jpg" alt="Fotoğraf 5">
  </div>

  <!-- Trabzonspor marşı (YouTube embed) -->
  <iframe width="0" height="0" src="https://www.youtube.com/embed/NnWc1SWh4lg?autoplay=1&loop=1" frameborder="0" allow="autoplay"></iframe>

  <footer>Hazırlayan: Orucun ❤️</footer>

  <script>
    let index = 0;
    const images = document.querySelectorAll(".slideshow img");
    function showNext() {
      images[index].classList.remove("active");
      index = (index + 1) % images.length;
      images[index].classList.add("active");
    }
    setInterval(showNext, 4000);
  </script>
</body>
</html>
