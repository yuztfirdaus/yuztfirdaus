## Hi world 👋
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>IYUS Firdaus — AI Mentor & Architect</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    html {
      scroll-behavior: smooth;
    }
    /* Animasi Glow Neon */
    .neon {
      text-shadow: 0 0 10px #6366f1, 0 0 20px #6366f1, 0 0 30px #6366f1;
    }
    /* Efek floating untuk foto profil */
    .float {
      animation: float 4s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
    }
  </style>
</head>

<body class="bg-gradient-to-b from-gray-900 via-gray-800 to-black text-white font-sans">

  <!-- NAVBAR -->
  <nav class="flex justify-between items-center px-8 py-5 bg-transparent fixed w-full backdrop-blur-md z-50">
    <h1 class="text-2xl font-bold tracking-wide text-indigo-400 neon">IYUS FIRDAUS</h1>
    <ul class="hidden md:flex space-x-8 text-gray-300">
      <li><a href="#about" class="hover:text-white">About</a></li>
      <li><a href="#skills" class="hover:text-white">Skills</a></li>
      <li><a href="#projects" class="hover:text-white">Projects</a></li>
      <li><a href="#contact" class="hover:text-white">Contact</a></li>
    </ul>
  </nav>

  <!-- HERO SECTION -->
  <section class="h-screen flex flex-col justify-center items-center text-center px-6">
    <img 
      src="https://i.ibb.co/0n1V7zB/ai-avatar.jpg" 
      alt="IYUS Firdaus Profile" 
      class="w-40 h-40 rounded-full border-4 border-indigo-500 shadow-lg mb-6 float"
    >
    <h2 class="text-gray-400 text-lg mb-2">👋 Hi, I'm</h2>
    <h1 class="text-5xl md:text-6xl font-bold mb-4 bg-gradient-to-r from-indigo-400 to-purple-500 bg-clip-text text-transparent neon">
      IYUS FIRDAUS
    </h1>
    <p class="text-xl text-gray-300 mb-6">AI Mentor • Creative Director • System Architect</p>
    <a href="#projects" class="px-6 py-3 bg-indigo-500 rounded-full hover:bg-indigo-600 transition-all shadow-lg shadow-indigo-500/40">
      View My Work
    </a>
  </section>

  <!-- ABOUT -->
  <section id="about" class="py-20 px-8 max-w-4xl mx-auto text-center">
    <h2 class="text-3xl font-semibold mb-6 text-indigo-400 neon">About Me</h2>
    <p class="text-gray-300 leading-relaxed text-lg">
      I'm an <span class="text-white font-semibold">AI Mentor, Creative Director, and System Architect</span> at 
      <a href="https://paradiesstudio.com" class="text-indigo-400 underline" target="_blank">Paradies</a> — 
      an international R&D collective focused on <b>Prompt Engineering, AI Systems, and Digital Artistry</b>.
      <br><br>
      <em class="text-indigo-300">“Technology is art, and code is imagination structured.”</em>
    </p>
  </section>

  <!-- SKILLS -->
  <section id="skills" class="py-20 bg-gray-800 relative overflow-hidden">
    <div class="absolute inset-0 opacity-20 bg-[radial-gradient(circle_at_center,_#6366f1_0%,_transparent_70%)] animate-pulse"></div>
    <div class="max-w-5xl mx-auto text-center px-8 relative z-10">
      <h2 class="text-3xl font-semibold mb-10 text-indigo-400 neon">Expertise</h2>
      <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-gray-300">
        <div class="p-4 bg-gray-900 rounded-xl hover:scale-105 transition shadow-lg shadow-indigo-500/20">AI & Machine Learning</div>
        <div class="p-4 bg-gray-900 rounded-xl hover:scale-105 transition shadow-lg shadow-indigo-500/20">Prompt Engineering</div>
        <div class="p-4 bg-gray-900 rounded-xl hover:scale-105 transition shadow-lg shadow-indigo-500/20">System Architecture</div>
        <div class="p-4 bg-gray-900 rounded-xl hover:scale-105 transition shadow-lg shadow-indigo-500/20">Creative Direction</div>
      </div>
    </div>
  </section>

  <!-- PROJECTS -->
  <section id="projects" class="py-20 px-8 max-w-6xl mx-auto text-center">
    <h2 class="text-3xl font-semibold mb-10 text-indigo-400 neon">Featured Projects</h2>
    <div class="grid md:grid-cols-3 gap-8">
      <div class="bg-gray-900 p-6 rounded-xl hover:shadow-lg hover:scale-105 transition">
        <img src="https://source.unsplash.com/600x400/?ai,technology" alt="Project 1" class="rounded-lg mb-4">
        <h3 class="text-xl font-semibold mb-2">AI Prompt System</h3>
        <p class="text-gray-400 text-sm">Custom AI automation framework for creative workflows.</p>
      </div>
      <div class="bg-gray-900 p-6 rounded-xl hover:shadow-lg hover:scale-105 transition">
        <img src="https://source.unsplash.com/600x400/?coding,art" alt="Project 2" class="rounded-lg mb-4">
        <h3 class="text-xl font-semibold mb-2">Paradies Studio</h3>
        <p class="text-gray-400 text-sm">R&D platform for AI art and intelligent systems.</p>
      </div>
      <div class="bg-gray-900 p-6 rounded-xl hover:shadow-lg hover:scale-105 transition">
        <img src="https://source.unsplash.com/600x400/?creative,design" alt="Project 3" class="rounded-lg mb-4">
        <h3 class="text-xl font-semibold mb-2">Digital Artistry Hub</h3>
        <p class="text-gray-400 text-sm">Collaborative ecosystem for generative design.</p>
      </div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="py-20 text-center bg-gray-900 relative">
    <h2 class="text-3xl font-semibold mb-6 text-indigo-400 neon">Get In Touch</h2>
    <p class="text-gray-300 mb-8">Interested in collaboration or mentorship? Let's connect.</p>
    <a href="mailto:iyusfirdaus@gmail.com" class="px-8 py-3 bg-indigo-500 rounded-full hover:bg-indigo-600 transition shadow-lg shadow-indigo-500/40">
      Say Hello 👋
    </a>
    <div class="mt-8 flex justify-center space-x-6 text-gray-400">
      <a href="#" class="hover:text-white">LinkedIn</a>
      <a href="#" class="hover:text-white">GitHub</a>
      <a href="#" class="hover:text-white">Instagram</a>
    </div>
  </section>

  <!-- FOOTER -->
  <footer class="py-6 text-center text-gray-500 text-sm border-t border-gray-800">
    © 2025 IYUS Firdaus — Crafted with ❤️ using TailwindCSS & Neon Motion
  </footer>

</body>
</html>
