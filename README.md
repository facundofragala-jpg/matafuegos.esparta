<!DOCTYPE html>
<html lang="es" class="scroll-smooth">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Matafuegos Esparta | Protección Total</title>
  
  <!-- Tailwind CSS via CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  
  <!-- Lucide Icons -->
  <script src="https://unpkg.com/lucide@latest"></script>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;700&display=swap" rel="stylesheet">

  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              red: '#b91c1c',
              redHover: '#991b1b',
              dark: '#0f172a',
              card: '#1e293b',
              footer: '#020617'
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Hero background with dark overlay for better text readability */
    .hero-bg {
      background-image: linear-gradient(rgba(15, 23, 42, 0.8), rgba(15, 23, 42, 0.8)), url('https://images.unsplash.com/photo-1581092918056-0c4c3acd3789?auto=format&fit=crop&q=80');
      background-size: cover;
      background-position: center;
      background-attachment: fixed;
    }
  </style>
</head>
<body class="bg-brand-dark text-slate-200 font-sans antialiased">

  <!-- Navbar -->
  <nav class="fixed w-full z-50 bg-brand-dark/95 backdrop-blur-sm border-b border-slate-800 transition-all">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="flex justify-between items-center h-20">
        <!-- Logo -->
        <div class="flex-shrink-0 flex items-center gap-2">
          <i data-lucide="flame" class="text-brand-red w-8 h-8"></i>
          <span class="font-bold text-2xl text-white tracking-tight">Matafuegos Esparta</span>
        </div>
        
        <!-- Desktop Menu -->
        <div class="hidden md:flex space-x-8">
          <a href="#" class="text-slate-300 hover:text-white hover:text-brand-red transition-colors duration-300 font-medium">Inicio</a>
          <a href="#servicios" class="text-slate-300 hover:text-white hover:text-brand-red transition-colors duration-300 font-medium">Servicios</a>
          <a href="#nosotros" class="text-slate-300 hover:text-white hover:text-brand-red transition-colors duration-300 font-medium">Nosotros</a>
          <a href="#contacto" class="text-slate-300 hover:text-white hover:text-brand-red transition-colors duration-300 font-medium">Contacto</a>
        </div>

        <!-- Mobile Menu Button -->
        <div class="md:hidden flex items-center">
          <button id="mobile-menu-btn" class="text-slate-300 hover:text-white focus:outline-none">
            <i data-lucide="menu" class="w-6 h-6"></i>
          </button>
        </div>
      </div>
    </div>

    <!-- Mobile Menu Panel -->
    <div id="mobile-menu" class="hidden md:hidden bg-brand-card border-b border-slate-700">
      <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
        <a href="#" class="block px-3 py-2 rounded-md text-base font-medium text-white hover:bg-brand-red transition-colors">Inicio</a>
        <a href="#servicios" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-white hover:bg-brand-red transition-colors">Servicios</a>
        <a href="#nosotros" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-white hover:bg-brand-red transition-colors">Nosotros</a>
        <a href="#contacto" class="block px-3 py-2 rounded-md text-base font-medium text-slate-300 hover:text-white hover:bg-brand-red transition-colors">Contacto</a>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="hero-bg relative min-h-[80vh] flex items-center pt-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
      <div class="inline-flex items-center gap-2 px-4 py-2 rounded-full bg-brand-red/20 text-red-400 border border-brand-red/30 mb-6 shadow-lg shadow-brand-red/10">
        <i data-lucide="shield-check" class="w-5 h-5"></i>
        <span class="text-sm font-semibold tracking-wide uppercase">Seguridad Garantizada</span>
      </div>
      <h1 class="text-5xl md:text-7xl font-bold text-white mb-6 leading-tight drop-shadow-lg">
        Protección Total <br/><span class="text-brand-red">Contra Incendios</span>
      </h1>
      <p class="mt-4 text-xl md:text-2xl text-slate-300 max-w-3xl mx-auto font-light mb-10">
        Venta, recarga y mantenimiento de matafuegos. Especialistas en mantener tu empresa y hogar seguros.
      </p>
      <div class="flex flex-col sm:flex-row justify-center gap-4">
        <a href="#contacto" class="px-8 py-4 bg-brand-red hover:bg-brand-redHover text-white font-bold rounded-lg transition-all duration-300 transform hover:-translate-y-1 shadow-lg shadow-brand-red/30 flex items-center justify-center gap-2">
          Contactanos Ahora
          <i data-lucide="arrow-right" class="w-5 h-5"></i>
        </a>
        <a href="#servicios" class="px-8 py-4 bg-transparent border-2 border-slate-500 hover:border-white text-white font-bold rounded-lg transition-all duration-300 flex items-center justify-center">
          Ver Servicios
        </a>
      </div>
    </div>
  </section>

  <!-- Servicios Section -->
  <section id="servicios" class="py-24 bg-brand-dark">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Nuestros Servicios</h2>
        <div class="w-24 h-1 bg-brand-red mx-auto rounded-full"></div>
        <p class="mt-4 text-slate-400 max-w-2xl mx-auto">Soluciones integrales adaptadas a las normativas vigentes para garantizar la máxima seguridad.</p>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Card 1 -->
        <div class="bg-brand-card p-8 rounded-2xl border border-slate-700 hover:border-brand-red/50 transition-all duration-300 hover:shadow-2xl hover:shadow-brand-red/10 group">
          <div class="w-14 h-14 bg-brand-red/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-brand-red/20 transition-colors">
            <i data-lucide="shopping-cart" class="text-brand-red w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold text-white mb-3">Venta de Equipos</h3>
          <p class="text-slate-400 leading-relaxed">Proveemos matafuegos nuevos, homologados y certificados para todo tipo de uso: comercial, industrial y vehicular.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-brand-card p-8 rounded-2xl border border-slate-700 hover:border-brand-red/50 transition-all duration-300 hover:shadow-2xl hover:shadow-brand-red/10 group">
          <div class="w-14 h-14 bg-brand-red/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-brand-red/20 transition-colors">
            <i data-lucide="refresh-cw" class="text-brand-red w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold text-white mb-3">Recarga Rápida</h3>
          <p class="text-slate-400 leading-relaxed">Servicio de recarga ágil y seguro realizado por personal técnico cualificado en plantas certificadas bajo normas IRAM.</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-brand-card p-8 rounded-2xl border border-slate-700 hover:border-brand-red/50 transition-all duration-300 hover:shadow-2xl hover:shadow-brand-red/10 group">
          <div class="w-14 h-14 bg-brand-red/10 rounded-xl flex items-center justify-center mb-6 group-hover:bg-brand-red/20 transition-colors">
            <i data-lucide="wrench" class="text-brand-red w-7 h-7"></i>
          </div>
          <h3 class="text-xl font-bold text-white mb-3">Mantenimiento</h3>
          <p class="text-slate-400 leading-relaxed">Control anual obligatorio y mantenimiento preventivo integral para asegurar que tus equipos estén siempre listos.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Nosotros Section -->
  <section id="nosotros" class="py-24 bg-brand-card relative overflow-hidden">
    <!-- Decorative background elements -->
    <div class="absolute top-0 right-0 -mr-20 -mt-20 w-64 h-64 rounded-full bg-brand-red/5 blur-3xl"></div>
    <div class="absolute bottom-0 left-0 -ml-20 -mb-20 w-80 h-80 rounded-full bg-blue-900/10 blur-3xl"></div>

    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10">
      <div class="flex flex-col md:flex-row items-center gap-12">
        <div class="w-full md:w-1/2">
          <img src="https://images.unsplash.com/photo-1605809794348-18567119e7a4?auto=format&fit=crop&q=80&w=800" alt="Inspección de Matafuego" class="rounded-2xl shadow-2xl border border-slate-700">
        </div>
        <div class="w-full md:w-1/2">
          <h2 class="text-3xl md:text-4xl font-bold text-white mb-6">Sobre Matafuegos Esparta</h2>
          <div class="w-16 h-1 bg-brand-red rounded-full mb-6"></div>
          <p class="text-lg text-slate-300 mb-6 leading-relaxed">
            Con años de experiencia en el sector, en <strong class="text-white">Matafuegos Esparta</strong> nos dedicamos a proteger vidas y bienes. Ofrecemos soluciones confiables y eficaces para la seguridad contra incendios.
          </p>
          <p class="text-lg text-slate-300 mb-8 leading-relaxed">
            Trabajamos exclusivamente con profesionales certificados, garantizando la máxima calidad en cada servicio, desde la asesoría inicial hasta el mantenimiento preventivo anual.
          </p>
          
          <div class="grid grid-cols-2 gap-6">
            <div class="flex items-center gap-3">
              <i data-lucide="check-circle" class="text-brand-red w-6 h-6 flex-shrink-0"></i>
              <span class="text-slate-200 font-medium">Personal Capacitado</span>
            </div>
            <div class="flex items-center gap-3">
              <i data-lucide="check-circle" class="text-brand-red w-6 h-6 flex-shrink-0"></i>
              <span class="text-slate-200 font-medium">Normas IRAM</span>
            </div>
            <div class="flex items-center gap-3">
              <i data-lucide="check-circle" class="text-brand-red w-6 h-6 flex-shrink-0"></i>
              <span class="text-slate-200 font-medium">Atención Rápida</span>
            </div>
            <div class="flex items-center gap-3">
              <i data-lucide="check-circle" class="text-brand-red w-6 h-6 flex-shrink-0"></i>
              <span class="text-slate-200 font-medium">Garantía Total</span>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Contacto Section -->
  <section id="contacto" class="py-24 bg-brand-dark">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="text-center mb-16">
        <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">Ponte en Contacto</h2>
        <div class="w-24 h-1 bg-brand-red mx-auto rounded-full"></div>
        <p class="mt-4 text-slate-400 max-w-2xl mx-auto">Solicitá tu presupuesto sin cargo o hacenos cualquier consulta. Estamos para ayudarte.</p>
      </div>

      <div class="flex flex-col lg:flex-row gap-12 bg-brand-card rounded-2xl overflow-hidden border border-slate-700 shadow-2xl">
        <!-- Info Column -->
        <div class="lg:w-2/5 bg-slate-800 p-10 flex flex-col justify-center">
          <h3 class="text-2xl font-bold text-white mb-8">Información de Contacto</h3>
          
          <div class="space-y-8">
            <div class="flex items-start gap-4">
              <div class="bg-brand-red/10 p-3 rounded-lg text-brand-red">
                <i data-lucide="phone" class="w-6 h-6"></i>
              </div>
              <div>
                <p class="text-sm text-slate-400 font-medium mb-1">Teléfono</p>
                <p class="text-lg text-white font-semibold">11-1234-5678</p>
              </div>
            </div>
            
            <div class="flex items-start gap-4">
              <div class="bg-brand-red/10 p-3 rounded-lg text-brand-red">
                <i data-lucide="mail" class="w-6 h-6"></i>
              </div>
              <div>
                <p class="text-sm text-slate-400 font-medium mb-1">Email</p>
                <p class="text-lg text-white font-semibold">contacto@matafuegosesparta.com</p>
              </div>
            </div>

            <div class="flex items-start gap-4">
              <div class="bg-brand-red/10 p-3 rounded-lg text-brand-red">
                <i data-lucide="map-pin" class="w-6 h-6"></i>
              </div>
              <div>
                <p class="text-sm text-slate-400 font-medium mb-1">Ubicación</p>
                <p class="text-lg text-white font-semibold">Buenos Aires, Argentina</p>
              </div>
            </div>
          </div>
        </div>

        <!-- Form Column -->
        <div class="lg:w-3/5 p-10">
          <form id="contactForm" class="space-y-6">
            <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
              <div>
                <label for="name" class="block text-sm font-medium text-slate-400 mb-2">Nombre Completo</label>
                <input type="text" id="name" required class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-red focus:ring-1 focus:ring-brand-red transition-colors" placeholder="Tu nombre">
              </div>
              <div>
                <label for="phone" class="block text-sm font-medium text-slate-400 mb-2">Teléfono</label>
                <input type="tel" id="phone" required class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-red focus:ring-1 focus:ring-brand-red transition-colors" placeholder="Tu número">
              </div>
            </div>
            
            <div>
              <label for="email" class="block text-sm font-medium text-slate-400 mb-2">Correo Electrónico</label>
              <input type="email" id="email" required class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-red focus:ring-1 focus:ring-brand-red transition-colors" placeholder="tucorreo@ejemplo.com">
            </div>

            <div>
              <label for="message" class="block text-sm font-medium text-slate-400 mb-2">Mensaje o Consulta</label>
              <textarea id="message" rows="4" required class="w-full bg-slate-900 border border-slate-700 rounded-lg px-4 py-3 text-white placeholder-slate-500 focus:outline-none focus:border-brand-red focus:ring-1 focus:ring-brand-red transition-colors resize-none" placeholder="¿En qué te podemos ayudar?"></textarea>
            </div>

            <button type="submit" class="w-full bg-brand-red hover:bg-brand-redHover text-white font-bold py-4 rounded-lg transition-colors flex justify-center items-center gap-2">
              Enviar Mensaje
              <i data-lucide="send" class="w-5 h-5"></i>
            </button>

            <!-- Success Message (Hidden by default) -->
            <div id="successMsg" class="hidden bg-green-900/50 border border-green-500 text-green-300 p-4 rounded-lg text-center mt-4">
              ¡Gracias! Tu mensaje ha sido enviado correctamente. Nos comunicaremos a la brevedad.
            </div>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-brand-footer py-12 border-t border-slate-800">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 flex flex-col md:flex-row justify-between items-center gap-6">
      <div class="flex items-center gap-2">
        <i data-lucide="flame" class="text-brand-red w-6 h-6"></i>
        <span class="font-bold text-xl text-white tracking-tight">Matafuegos Esparta</span>
      </div>
      
      <p class="text-slate-500 text-sm text-center md:text-left">
        © 2026 Matafuegos Esparta. Todos los derechos reservados.
      </p>

      <div class="flex gap-4">
        <a href="#" class="w-10 h-10 rounded-full bg-slate-800 flex items-center justify-center text-slate-400 hover:bg-brand-red hover:text-white transition-all">
          <i data-lucide="facebook" class="w-5 h-5"></i>
        </a>
        <a href="#" class="w-10 h-10 rounded-full bg-slate-800 flex items-center justify-center text-slate-400 hover:bg-brand-red hover:text-white transition-all">
          <i data-lucide="instagram" class="w-5 h-5"></i>
        </a>
      </div>
    </div>
  </footer>

  <!-- Floating WhatsApp Button -->
  <a href="https://wa.me/5491112345678" target="_blank" class="fixed bottom-6 right-6 bg-green-500 hover:bg-green-600 text-white w-14 h-14 rounded-full flex items-center justify-center shadow-lg shadow-green-500/30 transition-transform transform hover:scale-110 z-50">
    <svg xmlns="http://www.w3.org/2000/svg" width="28" height="28" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="lucide lucide-message-circle"><path d="M7.9 20A9 9 0 1 0 4 16.1L2 22Z"/></svg>
  </a>

  <!-- Scripts -->
  <script>
    // Initialize Lucide Icons
    lucide.createIcons();

    // Mobile Menu Toggle
    const btn = document.getElementById('mobile-menu-btn');
    const menu = document.getElementById('mobile-menu');

    btn.addEventListener('click', () => {
      menu.classList.toggle('hidden');
    });

    // Close mobile menu on link click
    const mobileLinks = menu.querySelectorAll('a');
    mobileLinks.forEach(link => {
      link.addEventListener('click', () => {
        menu.classList.add('hidden');
      });
    });

    // Form Submission Simulation
    const form = document.getElementById('contactForm');
    const successMsg = document.getElementById('successMsg');

    form.addEventListener('submit', (e) => {
      e.preventDefault();
      // Simulate sending data
      const btn = form.querySelector('button[type="submit"]');
      const originalText = btn.innerHTML;
      btn.innerHTML = '<i data-lucide="loader" class="w-5 h-5 animate-spin"></i> Enviando...';
      lucide.createIcons();
      
      setTimeout(() => {
        btn.innerHTML = originalText;
        form.reset();
        successMsg.classList.remove('hidden');
        
        // Hide success message after 5 seconds
        setTimeout(() => {
          successMsg.classList.add('hidden');
        }, 5000);
      }, 1500);
    });
  </script>
</body>
</html>
