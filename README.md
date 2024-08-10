<h1 align="center" style="background: linear-gradient(90deg, #ff7e5f, #feb47b); -webkit-background-clip: text; color: transparent; animation: gradient 3s ease infinite;">
  Hi 👋, I'm Chinmay Kumar Panda
</h1>
<h3 align="center">AWS & DevOps Enthusiast from India</h3>

<style>
  @keyframes gradient {
    0% {background-position: 0% 50%;}
    50% {background-position: 100% 50%;}
    100% {background-position: 0% 50%;}
  }
</style>
<style>
  a img:hover {
    transform: scale(1.2);
    transition: all 0.3s ease-in-out;
  }
</style>
<div id="particles-js"></div>
<script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
<script>
  particlesJS.load('particles-js', 'https://vincentgarreau.com/particles.js/assets/particles.json', function() {
    console.log('callback - particles.js config loaded');
  });
</script>

<style>
  #particles-js {
    position: absolute;
    width: 100%;
    height: 100%;
    top: 0;
    left: 0;
    z-index: -1;
  }
</style>
<style>
  body {
    scroll-behavior: smooth;
  }
  
  .fade-in {
    opacity: 0;
    animation: fadeIn 2s ease-in forwards;
  }
  
  @keyframes fadeIn {
    to {
      opacity: 1;
    }
  }
</style>

<div class="fade-in">
  <!-- Your content here -->
</div>
<style>
  body {
    scroll-behavior: smooth;
  }
  
  .fade-in {
    opacity: 0;
    animation: fadeIn 2s ease-in forwards;
  }
  
  @keyframes fadeIn {
    to {
      opacity: 1;
    }
  }
</style>

<div class="fade-in">
  <!-- Your content here -->
</div>
<div id="quote" align="center"></div>

<script>
  const quotes = [
    "Believe you can and you're halfway there.",
    "The only way to do great work is to love what you do.",
    "Success is not the key to happiness. Happiness is the key to success."
  ];

  let i = 0;
  function changeQuote() {
    document.getElementById("quote").innerText = quotes[i];
    i = (i + 1) % quotes.length;
  }
  
  setInterval(changeQuote, 5000);
  changeQuote();
</script>

<style>
  #quote {
    font-size: 18px;
    margin-top: 20px;
    color: #ff7e5f;
    animation: fade 3s ease-in-out infinite;
  }
  
  @keyframes fade {
    0%, 100% { opacity: 0; }
    50% { opacity: 1; }
  }
</style>
<svg viewBox="0 0 1440 320">
  <path fill="#ff7e5f" fill-opacity="1" d="M0,160L60,165.3C120,171,240,181,360,202.7C480,224,600,256,720,266.7C840,277,960,267,1080,240C1200,213,1320,171,1380,149.3L1440,128L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path>
</svg>
<svg viewBox="0 0 1440 320">
  <path fill="#ff7e5f" fill-opacity="1" d="M0,160L60,165.3C120,171,240,181,360,202.7C480,224,600,256,720,266.7C840,277,960,267,1080,240C1200,213,1320,171,1380,149.3L1440,128L1440,320L1380,320C1320,320,1200,320,1080,320C960,320,840,320,720,320C600,320,480,320,360,320C240,320,120,320,60,320L0,320Z"></path>
</svg>
<button onclick="toggleDarkMode()">Toggle Dark Mode</button>

<script>
  function toggleDarkMode() {
    document.body.classList.toggle("dark-mode");
  }
</script>

<style>
  .dark-mode {
    background-color: #1a1a1a;
    color: white;
  }
</style>
