<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Joan Escobar - Contador Público & Especialista en Proyectos</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #0A192F; /* Azul oscuro principal */
            color: #CCD6F6; /* Texto claro principal */
        }
        .bg-light-navy {
            background-color: #112240; /* Azul oscuro más claro para tarjetas/secciones */
        }
        .text-primary-blue {
            color: #64B5F6; /* Azul primario brillante para acentos */
        }
        .border-primary-blue {
            border-color: #64B5F6;
        }
        .bg-primary-blue {
            background-color: #64B5F6;
        }
        .text-logo-main {
            color: #E6F1FF; /* Texto blanco/muy claro para logo y títulos */
        }
        .hover-text-primary-blue:hover {
            color: #64B5F6;
        }
        .section-padding {
            padding-top: 4rem; /* 64px */
            padding-bottom: 4rem; /* 64px */
        }
        .glow-effect {
            box-shadow: 0 0 15px rgba(100, 181, 246, 0.5), 0 0 30px rgba(100, 181, 246, 0.3);
        }
        /* Estilo para el logo - asegúrate que la imagen tenga fondo transparente o se ajuste */
        .logo-img {
            max-height: 50px; /* Ajusta según el tamaño de tu logo */
        }
    </style>
</head>
<body class="antialiased">
    <!-- Header -->
    <header class="bg-light-navy shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <div class="flex items-center">
                <!-- IMPORTANTE: Reemplaza 'URL_DE_TU_LOGO.png' con la URL real de tu imagen de logo -->
                <!-- Se recomienda usar la imagen 'ChatGPT Image 3 jun 2025, 22_02_53.jpg' por su claridad -->
                <img src="https://placehold.co/150x50/1E63B8/FFFFFF?text=JE+Logo" alt="Logo Joan Escobar" class="logo-img mr-3">
                <a href="#" class="text-2xl font-bold text-logo-main">Joan Escobar</a>
            </div>
            <nav class="hidden md:flex space-x-4">
                <a href="#inicio" class="text-lightest-slate hover-text-primary-blue px-3 py-2 rounded-md text-sm font-medium">Inicio</a>
                <a href="#sobre-mi" class="text-lightest-slate hover-text-primary-blue px-3 py-2 rounded-md text-sm font-medium">Sobre Mí</a>
                <a href="#servicios" class="text-lightest-slate hover-text-primary-blue px-3 py-2 rounded-md text-sm font-medium">Servicios</a>
                <a href="#contacto" class="text-lightest-slate hover-text-primary-blue px-3 py-2 rounded-md text-sm font-medium">Contacto</a>
            </nav>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-lightest-slate focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="md:hidden hidden bg-light-navy">
            <a href="#inicio" class="block text-lightest-slate hover-text-primary-blue px-4 py-2 text-sm">Inicio</a>
            <a href="#sobre-mi" class="block text-lightest-slate hover-text-primary-blue px-4 py-2 text-sm">Sobre Mí</a>
            <a href="#servicios" class="block text-lightest-slate hover-text-primary-blue px-4 py-2 text-sm">Servicios</a>
            <a href="#contacto" class="block text-lightest-slate hover-text-primary-blue px-4 py-2 text-sm">Contacto</a>
        </div>
    </header>
    <!-- Hero Section -->
    <section id="inicio" class="section-padding bg-cover bg-center" style="background-image: url('https://placehold.co/1920x1080/0A192F/112240?text=Fondo+Abstracto');">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-6xl font-bold text-logo-main mb-4">Joan Sebastian Escobar Rojas</h1>
            <h2 class="text-2xl md:text-3xl font-semibold text-primary-blue mb-6">Contador Público & Especialista en Gerencia de Proyectos</h2>
            <p class="text-lg text-lightest-slate mb-8 max-w-2xl mx-auto">Transformando tus finanzas y optimizando tus procesos para el éxito empresarial.</p>
            <a href="#contacto" class="bg-primary-blue text-white font-semibold py-3 px-8 rounded-lg text-lg hover:bg-opacity-80 transition duration-300 glow-effect">Solicita una Consultoría</a>
            <p class="mt-4 text-xl font-bold text-primary-blue">"IMPROVE YOUR PROCESS"</p>
        </div>
    </section>
    <!-- Sobre Mí Section -->
    <section id="sobre-mi" class="section-padding">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-primary-blue mb-12">Sobre Mí</h2>
            <div class="flex flex-col md:flex-row items-center md:space-x-12">
                <div class="md:w-1/3 mb-8 md:mb-0">
                    <!-- Reemplaza con la URL de tu foto profesional -->
                    <img src="https://placehold.co/400x400/112240/CCD6F6?text=Foto+Joan" alt="Joan Sebastian Escobar Rojas" class="rounded-lg shadow-xl mx-auto">
                </div>
                <div class="md:w-2/3">
                    <p class="text-lg text-lightest-slate mb-4">
                        Soy un Contador Público apasionado por la tecnología y la optimización de procesos, con una Especialización en Gerencia de Proyectos. Cuento con más de 8 años de experiencia liderando proyectos de implementación de software contable (como Netsuite), integrando sistemas y mejorando la eficiencia en diversos sectores: startups, servicios, salud e industrial.
                    </p>
                    <p class="text-lg text-lightest-slate mb-4">
                        Mi enfoque se centra en proporcionar información financiera real y confiable, desarrollando herramientas e ideas innovadoras que permiten a las empresas realizar sus tareas con mayor eficiencia. Me destaco por mi capacidad analítica, aprendizaje rápido y habilidades para la comunicación efectiva y el liderazgo de equipos.
                    </p>
                    <p class="text-lg text-lightest-slate mb-6">
                        Busco constantemente la mejora en cada área en la que participo, con el objetivo de generar valor y ayudar a las organizaciones a alcanzar sus metas.
                    </p>
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Habilidades Clave:</h3>
                    <ul class="list-disc list-inside text-lightest-slate space-y-1 mb-6">
                        <li>Liderazgo de Proyectos (Netsuite, NIIF 17)</li>
                        <li>Análisis y Optimización de Procesos Contables</li>
                        <li>Implementación de Software ERP y Contable</li>
                        <li>Análisis de Datos (Power BI, SAS, SQL, Excel Avanzado)</li>
                        <li>Gestión Financiera y Presupuestaria</li>
                        <li>Normas Internacionales de Información Financiera (NIIF)</li>
                    </ul>
                    <a href="https://www.linkedin.com/in/joan-s-escobar-r" target="_blank" class="inline-block bg-primary-blue text-white font-semibold py-2 px-6 rounded-lg hover:bg-opacity-80 transition duration-300">
                        Ver Perfil en LinkedIn
                    </a>
                </div>
            </div>
        </div>
    </section>
    <!-- Servicios Section -->
    <section id="servicios" class="section-padding bg-light-navy">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-primary-blue mb-12">Mis Servicios</h2>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Servicio 1 -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Consultoría Contable y Financiera</h3>
                    <p class="text-lightest-slate text-sm">Análisis, contabilidad general, gestión de cuentas, tesorería y presupuestos para optimizar tu salud financiera.</p>
                </div>
                <!-- Servicio 2 -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Implementación de Software ERP</h3>
                    <p class="text-lightest-slate text-sm">Asesoría e implementación de Netsuite y otros ERPs, integración de sistemas y migración de datos.</p>
                </div>
                <!-- Servicio 3 -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Gestión de Proyectos</h3>
                    <p class="text-lightest-slate text-sm">Liderazgo de proyectos contables, financieros y de implementación NIIF, con metodologías ágiles y tradicionales.</p>
                </div>
                <!-- Servicio 4 -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Análisis de Datos y BI</h3>
                    <p class="text-lightest-slate text-sm">Creación de dashboards en Power BI, análisis con SAS y SQL para insights estratégicos.</p>
                </div>
                <!-- Servicio 5 -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Optimización de Procesos</h3>
                    <p class="text-lightest-slate text-sm">Automatización con Excel, rediseño de procesos contables para mayor eficiencia.</p>
                </div>
                <!-- Servicio 6 -->
                <div class="bg-gray-800 p-6 rounded-lg shadow-lg transform hover:scale-105 transition-transform duration-300">
                    <h3 class="text-xl font-semibold text-primary-blue mb-3">Consultoría NIIF</h3>
                    <p class="text-lightest-slate text-sm">Asesoría en la aplicación de Normas Internacionales de Información Financiera, incluyendo NIIF 17.</p>
                </div>
            </div>
             <p class="text-center mt-10 text-lightest-slate">
                Para conocer el detalle completo de los servicios, <a href="#contacto" class="text-primary-blue font-semibold hover:underline">contáctame</a>.
            </p>
        </div>
    </section>
    <!-- Contacto Section -->
    <section id="contacto" class="section-padding">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center text-primary-blue mb-12">Contacto</h2>
            <div class="max-w-lg mx-auto bg-light-navy p-8 rounded-lg shadow-xl">
                <p class="text-center text-lightest-slate mb-6">
                    ¿Listo para mejorar tus procesos y optimizar tus finanzas? ¡Hablemos!
                </p>
                <form action="#" method="POST"> <!-- Configura la acción del formulario -->
                    <div class="mb-4">
                        <label for="name" class="block text-sm font-medium text-lightest-slate mb-1">Nombre Completo</label>
                        <input type="text" name="name" id="name" class="w-full px-3 py-2 rounded-md bg-gray-800 text-lightest-slate border border-gray-700 focus:ring-primary-blue focus:border-primary-blue" required>
                    </div>
                    <div class="mb-4">
                        <label for="email" class="block text-sm font-medium text-lightest-slate mb-1">Correo Electrónico</label>
                        <input type="email" name="email" id="email" class="w-full px-3 py-2 rounded-md bg-gray-800 text-lightest-slate border border-gray-700 focus:ring-primary-blue focus:border-primary-blue" required>
                    </div>
                    <div class="mb-4">
                        <label for="message" class="block text-sm font-medium text-lightest-slate mb-1">Mensaje</label>
                        <textarea name="message" id="message" rows="4" class="w-full px-3 py-2 rounded-md bg-gray-800 text-lightest-slate border border-gray-700 focus:ring-primary-blue focus:border-primary-blue" required></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-primary-blue text-white font-semibold py-3 px-8 rounded-lg hover:bg-opacity-80 transition duration-300 glow-effect">
                            Enviar Mensaje
                        </button>
                    </div>
                </form>
                <div class="mt-8 text-center">
                    <p class="text-lightest-slate">También puedes contactarme directamente:</p>
                    <p class="text-primary-blue font-semibold mt-2">
                        <a href="mailto:joan941011@gmail.com" class="hover:underline">joan941011@gmail.com</a>
                    </p>
                    <p class="text-primary-blue font-semibold">
                        <a href="tel:+573016341558" class="hover:underline">(+57) 301 634 1558</a>
                    </p>
                </div>
            </div>
        </div>
    </section>
    <!-- Footer -->
    <footer class="bg-light-navy py-8 text-center">
        <div class="container mx-auto px-6">
            <!-- Reemplaza 'URL_DE_TU_LOGO.png' con la URL real de tu imagen de logo -->
            <img src="https://placehold.co/100x30/1E63B8/FFFFFF?text=JE" alt="Logo Joan Escobar" class="mx-auto mb-4 h-8">
            <p class="text-sm text-slate">&copy; <span id="currentYear"></span> Joan Sebastian Escobar Rojas. Todos los derechos reservados.</p>
            <p class="text-sm text-slate">Diseño inspirado en tus objetivos.</p>
        </div>
    </footer>
    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                mobileMenu.classList.add('hidden'); // Close mobile menu on click
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
        // Set current year in footer
        document.getElementById('currentYear').textContent = new Date().getFullYear();
    </script>
</body>
</html>
