<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Alan Joel Arias Moron</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
    
    body {
      font-family: 'Inter', system-ui, sans-serif;
    }
    
    .hero-bg {
      background: linear-gradient(135deg, #0f172a 0%, #1e2937 100%);
    }
    
    .card-hover {
      transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
    }
    
    .card-hover:hover {
      transform: translateY(-8px);
      box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
    }
  </style>
</head>
<body class="bg-zinc-950 text-zinc-200">
  
  <!-- Hero Section -->
  <header class="hero-bg border-b border-zinc-800">
    <div class="max-w-5xl mx-auto px-6 py-16">
      <div class="flex flex-col md:flex-row items-center gap-10">
        <!-- Avatar -->
        <div class="flex-shrink-0">
          <div class="w-48 h-48 bg-gradient-to-br from-emerald-500 to-cyan-500 rounded-2xl p-1">
            <div class="w-full h-full bg-zinc-900 rounded-[14px] flex items-center justify-center overflow-hidden">
              <i class="fa-solid fa-user-tie text-8xl text-emerald-400"></i>
            </div>
          </div>
        </div>
        
        <!-- Info -->
        <div class="text-center md:text-left">
          <h1 class="text-5xl font-bold mb-2 bg-gradient-to-r from-white to-emerald-300 bg-clip-text text-transparent">
            Alan Joel Arias Morón
          </h1>
          <p class="text-2xl text-emerald-400 font-medium mb-4">
            Ingeniero Informático
          </p>
          <p class="text-zinc-400 text-lg max-w-lg">
            Desarrollador web apasionado por crear aplicaciones seguras y escalables. 
            <span class="text-emerald-300">Linux enthusiast</span> | Seguridad Web &amp; Desarrollo Full-Stack
          </p>
          
          <div class="flex justify-center md:justify-start gap-4 mt-8">
            <a href="#" class="px-6 py-3 bg-emerald-600 hover:bg-emerald-500 transition-colors rounded-xl font-medium flex items-center gap-2">
              <i class="fa-brands fa-github"></i>
              <span>Ver Proyectos</span>
            </a>
            <a href="mailto:tuemail@ejemplo.com" class="px-6 py-3 border border-zinc-700 hover:border-zinc-500 transition-colors rounded-xl font-medium flex items-center gap-2">
              <i class="fa-solid fa-envelope"></i>
              Contactar
            </a>
          </div>
        </div>
      </div>
    </div>
  </header>

  <div class="max-w-5xl mx-auto px-6 py-12 grid md:grid-cols-12 gap-8">
    
    <!-- About -->
    <div class="md:col-span-7">
      <div class="mb-10">
        <h2 class="text-3xl font-semibold mb-4 flex items-center gap-3">
          <i class="fa-solid fa-user text-emerald-500"></i>
          Sobre mí
        </h2>
        <div class="prose prose-invert text-zinc-300 text-lg">
          <p class="leading-relaxed">
            Soy un Ingeniero Informático con fuerte enfoque en el desarrollo web y la seguridad informática. 
            Trabajo principalmente con Linux como entorno de desarrollo y me apasiona construir aplicaciones robustas, 
            seguras y con excelente experiencia de usuario.
          </p>
          <p class="leading-relaxed mt-4">
            Me especializo en arquitecturas modernas full-stack, implementando buenas prácticas de seguridad 
            (OWASP, autenticación segura, protección contra vulnerabilidades comunes) y optimización de rendimiento.
          </p>
        </div>
      </div>

      <!-- Experiencia / Enfoque -->
      <div>
        <h2 class="text-3xl font-semibold mb-6">Enfoque principal</h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
          <div class="bg-zinc-900 border border-zinc-800 rounded-2xl p-6 card-hover">
            <div class="text-emerald-500 text-4xl mb-4">
              <i class="fa-solid fa-globe"></i>
            </div>
            <h3 class="text-xl font-semibold mb-2">Desarrollo Web</h3>
            <p class="text-zinc-400">Aplicaciones modernas, rápidas y escalables utilizando las últimas tecnologías.</p>
          </div>
          <div class="bg-zinc-900 border border-zinc-800 rounded-2xl p-6 card-hover">
            <div class="text-red-500 text-4xl mb-4">
              <i class="fa-solid fa-shield-halved"></i>
            </div>
            <h3 class="text-xl font-semibold mb-2">Seguridad Web</h3>
            <p class="text-zinc-400">Protección de aplicaciones, auditorías de seguridad y buenas prácticas.</p>
          </div>
        </div>
      </div>
    </div>

    <!-- Skills Sidebar -->
    <div class="md:col-span-5 space-y-8">
      
      <!-- Tech Stack -->
      <div>
        <h2 class="text-2xl font-semibold mb-5 flex items-center gap-2">
          <i class="fa-solid fa-code"></i>
          Tecnologías
        </h2>
        
        <div class="flex flex-wrap gap-3">
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">Vue.js</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">Laravel</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">PHP</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">JavaScript</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">Java</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">PostgreSQL</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">MySQL</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">Tailwind CSS</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">Linux</span>
          <span class="px-5 py-2 bg-zinc-900 hover:bg-zinc-800 border border-zinc-700 rounded-2xl text-sm font-medium transition-colors">VS Code</span>
        </div>
      </div>

      <!-- Herramientas -->
      <div>
        <h3 class="text-xl font-medium mb-4 text-zinc-400">Herramientas &amp; Entorno</h3>
        <div class="flex items-center gap-8 text-4xl text-zinc-500">
          <i class="fa-brands fa-linux hover:text-orange-500 transition-colors"></i>
          <i class="fa-brands fa-vuejs hover:text-emerald-500 transition-colors"></i>
          <i class="fa-brands fa-laravel hover:text-red-500 transition-colors"></i>
          <i class="fa-brands fa-java hover:text-blue-500 transition-colors"></i>
        </div>
      </div>

      <!-- Otros lenguajes -->
      <div class="bg-zinc-900 border border-zinc-800 rounded-3xl p-6">
        <p class="text-zinc-400 text-sm mb-3">También conozco:</p>
        <div class="flex gap-4 text-sm">
          <span class="px-4 py-1.5 bg-zinc-800 rounded-2xl">Pascal</span>
          <span class="px-4 py-1.5 bg-zinc-800 rounded-2xl">NetBeans</span>
        </div>
      </div>

    </div>
  </div>

  <!-- Footer / Contact -->
  <footer class="border-t border-zinc-800 bg-zinc-950 py-10">
    <div class="max-w-5xl mx-auto px-6">
      <div class="flex flex-col md:flex-row justify-between items-center gap-6">
        <div class="text-zinc-500 text-sm">
          © 2026 Alan Joel Arias Morón • Hecho con ❤️ y código limpio
        </div>
        
        <div class="flex gap-6 text-2xl">
          <a href="#" class="hover:text-emerald-400 transition-colors"><i class="fa-brands fa-github"></i></a>
          <a href="#" class="hover:text-emerald-400 transition-colors"><i class="fa-brands fa-linkedin"></i></a>
          <a href="#" class="hover:text-emerald-400 transition-colors"><i class="fa-solid fa-envelope"></i></a>
        </div>
      </div>
    </div>
  </footer>

  <script>
    // Tailwind script already loaded via CDN
    console.log('%c✅ Perfil de GitHub listo para Alan Joel Arias Morón', 'color: #10b981; font-family: monospace;');
  </script>
</body>
</html>
