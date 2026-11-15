<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mis 15 Años - Eloisa Simone</title>

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- FontAwesome CDN -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Alex+Brush&family=Cinzel:wght@400;600;700&family=Great+Vibes&family=Montserrat:ital,wght@0,300;0,400;0,500;0,600;0,700;1,300;1,400&display=swap" rel="stylesheet">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        blush: {
                            50: '#fff5f7',
                            100: '#ffeef2',
                            200: '#ffd6e0',
                            300: '#fbb6ce',
                            400: '#f787b1',
                            500: '#ef5b94',
                            600: '#db3373',
                            700: '#b81e57',
                        },
                        gold: {
                            light: '#fcf6ba',
                            mid: '#d4af37',
                            dark: '#aa771c',
                        },
                        rosegold: '#be8a96'
                    },
                    fontFamily: {
                        script: ['Great Vibes', 'Alex Brush', 'cursive'],
                        cinzel: ['Cinzel', 'serif'],
                        sans: ['Montserrat', 'sans-serif'],
                    }
                }
            }
        }
    </script>

    <style>
        /* Custom Keyframes & Animations */
        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-10px) rotate(2deg); }
        }
        @keyframes pulse-gold {
            0%, 100% { filter: drop-shadow(0 0 5px rgba(212, 175, 55, 0.4)); transform: scale(1); }
            50% { filter: drop-shadow(0 0 15px rgba(212, 175, 55, 0.8)); transform: scale(1.03); }
        }
        @keyframes flutter {
            0%, 100% { transform: rotate(0deg) scaleX(1); }
            50% { transform: rotate(6deg) scaleX(0.5); }
        }

        .animate-float { animation: float 4s ease-in-out infinite; }
        .animate-pulse-gold { animation: pulse-gold 3s ease-in-out infinite; }
        .butterfly-flutter { animation: flutter 0.8s ease-in-out infinite alternate; }

        /* Custom Gradients & Glassmorphism */
        .gold-text-gradient {
            background: linear-gradient(135deg, #aa771c 0%, #d4af37 35%, #fcf6ba 50%, #d4af37 70%, #8a5a00 100%);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .glass-card {
            background: rgba(255, 255, 255, 0.82);
            backdrop-filter: blur(14px);
            -webkit-backdrop-filter: blur(14px);
            border: 1px solid rgba(212, 175, 55, 0.35);
        }

        .glass-card-pink {
            background: rgba(255, 240, 245, 0.88);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(247, 135, 177, 0.4);
        }

        /* Particle Overlay Canvas */
        #bgCanvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 10;
        }

        /* Royal Portrait Frame */
        .royal-portrait-border {
            position: relative;
            background: linear-gradient(135deg, #d4af37, #fcf6ba, #aa771c, #d4af37);
            padding: 6px;
            border-radius: 9999px 9999px 2rem 2rem;
            box-shadow: 0 15px 35px -5px rgba(219, 51, 115, 0.25), 0 0 25px rgba(212, 175, 55, 0.3);
        }

        /* Smooth Scrollbar */
        ::-webkit-scrollbar { width: 8px; }
        ::-webkit-scrollbar-track { background: #fff5f7; }
        ::-webkit-scrollbar-thumb { background: #f787b1; border-radius: 4px; }
    </style>
</head>
<body class="bg-blush-50 font-sans text-gray-800 antialiased overflow-x-hidden relative selection:bg-blush-200 selection:text-blush-700">

    <!-- Interactive Canvas Layer for Floating Butterflies & Gold Dust -->
    <canvas id="bgCanvas"></canvas>

    <!-- MUSIC CONTROLLER BUTTON -->
    <div class="fixed top-4 right-4 z-50 flex items-center gap-2">
        <button id="musicBtn" onclick="toggleAudio()" 
                class="glass-card bg-white/90 text-blush-700 hover:text-blush-600 p-3.5 rounded-full shadow-lg border border-gold-mid/40 flex items-center justify-center transition-all duration-300 transform hover:scale-110 group">
            <i id="musicIcon" class="fas fa-music text-xl"></i>
            <span class="max-w-0 overflow-hidden group-hover:max-w-xs transition-all duration-500 ease-in-out whitespace-nowrap text-xs font-semibold ml-0 group-hover:ml-2 text-gray-700">Música de Fondo</span>
        </button>
    </div>

    <!-- WELCOME OVERLAY / ENVELOPE MODAL -->
    <div id="welcomeOverlay" class="fixed inset-0 z-50 flex items-center justify-center bg-gradient-to-br from-blush-100 via-blush-50 to-pink-100 p-4 transition-opacity duration-700">
        <div class="max-w-md w-full glass-card p-8 rounded-3xl text-center shadow-2xl border-2 border-gold-mid/40 relative overflow-hidden transform animate-float">
            <!-- Decorative Crowns -->
            <div class="absolute top-3 left-3 text-gold-mid opacity-40 text-xl"><i class="fas fa-crown"></i></div>
            <div class="absolute top-3 right-3 text-gold-mid opacity-40 text-xl"><i class="fas fa-crown"></i></div>
            
            <div class="mb-4">
                <svg class="w-16 h-16 mx-auto text-gold-mid animate-pulse-gold" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M5 16L3 5l5.5 5L12 4l3.5 6L21 5l-2 11H5zm14 3c0 .6-.4 1-1 1H6c-.6 0-1-.4-1-1v-1h14v1z"/>
                </svg>
            </div>

            <p class="font-cinzel text-xs tracking-[0.25em] uppercase text-blush-600 mb-2 font-semibold">Te invito a celebrar</p>
            <h1 class="font-script text-5xl sm:text-6xl gold-text-gradient mb-2 drop-shadow-sm">Eloisa Simone</h1>
            <h2 class="font-cinzel text-xl text-gray-700 font-bold mb-6 tracking-widest">MIS 15 AÑOS</h2>
            
            <div class="w-20 h-0.5 bg-gradient-to-r from-transparent via-gold-mid to-transparent mx-auto mb-6"></div>

            <button onclick="openInvitation()" class="w-full py-4 px-6 rounded-full bg-gradient-to-r from-blush-500 via-blush-400 to-gold-mid text-white font-cinzel font-bold text-sm tracking-widest shadow-xl hover:shadow-2xl transition-all duration-300 transform hover:-translate-y-0.5 flex items-center justify-center gap-3 group">
                <span>ABRIR INVITACIÓN</span>
                <i class="fas fa-envelope-open text-base group-hover:rotate-12 transition-transform"></i>
            </button>
            <p class="text-xs text-gray-500 mt-4 italic">Haz clic para iniciar la experiencia</p>
        </div>
    </div>

    <!-- MAIN CONTAINER -->
    <main class="max-w-3xl mx-auto px-4 py-8 space-y-16 relative z-20">

        <!-- HERO SECTION WITH PORTRAIT -->
        <section class="text-center pt-6 pb-2 relative">
            <!-- Crown SVG Icon Top -->
            <div class="mb-3 inline-block relative">
                <svg class="w-20 h-20 mx-auto text-gold-mid filter drop-shadow-md animate-pulse-gold" viewBox="0 0 24 24" fill="currentColor">
                    <path d="M5 16L3 5l5.5 5L12 4l3.5 6L21 5l-2 11H5zm14 3c0 .6-.4 1-1 1H6c-.6 0-1-.4-1-1v-1h14v1z"/>
                </svg>
                <!-- Floating Butterfly Badges -->
                <span class="absolute -left-6 top-1 text-blush-400 text-xl animate-bounce"><i class="fas fa-butterfly"></i></span>
                <span class="absolute -right-6 top-1 text-blush-400 text-xl animate-bounce" style="animation-delay: 0.5s;"><i class="fas fa-butterfly"></i></span>
            </div>

            <p class="font-cinzel text-sm uppercase tracking-[0.3em] text-blush-600 font-semibold mb-1">¡Estás invitado a celebrar!</p>
            <h1 class="font-script text-6xl sm:text-7xl md:text-8xl gold-text-gradient py-2 font-normal drop-shadow">Eloisa Simone</h1>
            <p class="font-cinzel text-2xl md:text-3xl text-gray-700 tracking-widest font-semibold mt-1">MIS 15 AÑOS</p>

            <!-- ROYAL PORTRAIT FRAME -->
            <div class="mt-8 mb-6 inline-block relative">
                <div class="royal-portrait-border max-w-xs sm:max-w-sm mx-auto overflow-hidden">
                    <div class="relative overflow-hidden rounded-t-full rounded-b-2xl aspect-[3/4] bg-blush-100 group">
                        
                        <!-- Fixed Static Image -->
                        <img id="quinceaneraPhoto" class="w-full h-full object-cover transition-transform duration-500 group-hover:scale-105" 
                             src="foto_eloisa.jpg" 
                             alt="Eloisa Simone">
                        
                    </div>
                </div>

                <!-- Floating Butterfly Badge -->
                <div class="absolute -top-4 -right-4 bg-white/95 p-3.5 rounded-full shadow-lg border border-gold-mid/50 text-gold-mid text-2xl animate-float">
                    🦋
                </div>
                <div class="absolute -bottom-3 -left-3 bg-white/95 p-3.5 rounded-full shadow-lg border border-gold-mid/50 text-gold-mid text-xl animate-float" style="animation-delay: 1.5s;">
                    👑
                </div>
            </div>

            <!-- Intro Phrase Card -->
            <div class="glass-card max-w-xl mx-auto p-6 rounded-2xl shadow-md border-t-2 border-gold-mid mt-4">
                <p class="font-script text-3xl md:text-4xl text-blush-700 mb-2">"Hay momentos inolvidables..."</p>
                <p class="text-gray-600 text-sm md:text-base leading-relaxed italic font-light">
                    "Hay momentos en la vida que son especiales por sí solos, pero compartirlos con las personas que más quiero los hace verdaderamente inolvidables. ¡Te espero para celebrar juntos mi noche mágica!"
                </p>
            </div>
        </section>

        <!-- COUNTDOWN TIMER -->
        <section class="text-center">
            <h3 class="font-cinzel text-sm sm:text-base tracking-[0.2em] text-gray-700 mb-4 font-bold uppercase flex items-center justify-center gap-2">
                <span class="w-8 h-px bg-gold-mid"></span>
                <i class="far fa-clock text-gold-mid"></i> Faltan Tan Solo
                <span class="w-8 h-px bg-gold-mid"></span>
            </h3>

            <div class="grid grid-cols-4 gap-2 sm:gap-4 max-w-lg mx-auto">
                <div class="glass-card p-3 sm:p-4 rounded-2xl shadow-sm text-center border-b-4 border-blush-400">
                    <span id="days" class="block font-cinzel text-2xl sm:text-4xl font-bold text-blush-700">00</span>
                    <span class="text-[10px] sm:text-xs font-semibold uppercase tracking-wider text-gray-500">Días</span>
                </div>
                <div class="glass-card p-3 sm:p-4 rounded-2xl shadow-sm text-center border-b-4 border-blush-400">
                    <span id="hours" class="block font-cinzel text-2xl sm:text-4xl font-bold text-blush-700">00</span>
                    <span class="text-[10px] sm:text-xs font-semibold uppercase tracking-wider text-gray-500">Horas</span>
                </div>
                <div class="glass-card p-3 sm:p-4 rounded-2xl shadow-sm text-center border-b-4 border-blush-400">
                    <span id="minutes" class="block font-cinzel text-2xl sm:text-4xl font-bold text-blush-700">00</span>
                    <span class="text-[10px] sm:text-xs font-semibold uppercase tracking-wider text-gray-500">Minutos</span>
                </div>
                <div class="glass-card p-3 sm:p-4 rounded-2xl shadow-sm text-center border-b-4 border-blush-400">
                    <span id="seconds" class="block font-cinzel text-2xl sm:text-4xl font-bold text-blush-700">00</span>
                    <span class="text-[10px] sm:text-xs font-semibold uppercase tracking-wider text-gray-500">Segundos</span>
                </div>
            </div>
        </section>

        <!-- EVENT DETAILS CARDS -->
        <section class="space-y-6">
            <div class="text-center mb-6">
                <h2 class="font-cinzel text-2xl md:text-3xl text-gray-800 font-bold">¿Dónde & Cuándo?</h2>
                <div class="w-16 h-0.5 bg-gold-mid mx-auto mt-2"></div>
            </div>

            <div class="grid md:grid-cols-2 gap-6">
                <!-- Date & Time Card -->
                <div class="glass-card p-6 rounded-3xl text-center shadow-lg hover:shadow-xl transition-all border border-gold-mid/30 relative overflow-hidden group">
                    <div class="w-14 h-14 bg-blush-100 text-blush-600 rounded-full flex items-center justify-center mx-auto mb-4 text-2xl shadow-inner group-hover:scale-110 transition-transform">
                        <i class="far fa-calendar-alt"></i>
                    </div>
                    <h3 class="font-cinzel text-xl font-bold text-gray-800 mb-1">Fecha y Hora</h3>
                    <p class="text-blush-600 font-bold text-lg">Sábado, 26 de Diciembre de 2026</p>
                    <p class="text-gray-700 font-semibold text-base mt-1">21:30 hs.</p>
                    
                    <div class="mt-6 pt-4 border-t border-gray-100">
                        <a href="https://calendar.google.com/calendar/render?action=TEMPLATE&text=Mis+15+A%C3%B1os+-+Eloisa+Simone&dates=20261226T213000/20261227T050000&details=Celebraci%C3%B3n+de+15+A%C3%B1os+de+Eloisa+Simone&location=Pas%C3%B3n+Fiestas+y+Eventos,+15000+Gral.+L%C3%ADber+Seregni,+Canelones" 
                           target="_blank" 
                           class="inline-flex items-center gap-2 text-xs font-bold font-cinzel text-blush-700 hover:text-blush-800 uppercase tracking-wider bg-blush-100/90 hover:bg-blush-200 py-3 px-5 rounded-full transition-all shadow-sm">
                            <i class="far fa-calendar-plus"></i> Agendar en Google Calendar
                        </a>
                    </div>
                </div>

                <!-- Location Card -->
                <div class="glass-card p-6 rounded-3xl text-center shadow-lg hover:shadow-xl transition-all border border-gold-mid/30 relative overflow-hidden group">
                    <div class="w-14 h-14 bg-blush-100 text-blush-600 rounded-full flex items-center justify-center mx-auto mb-4 text-2xl shadow-inner group-hover:scale-110 transition-transform">
                        <i class="fas fa-map-marker-alt"></i>
                    </div>
                    <h3 class="font-cinzel text-xl font-bold text-gray-800 mb-1">Lugar de la Fiesta</h3>
                    <p class="text-blush-600 font-bold text-lg">Pasión Fiestas y Eventos</p>
                    <p class="text-gray-600 text-sm mt-1 px-2">15000 Gral. Líber Seregni, Departamento de Canelones</p>
                    
                    <div class="mt-6 pt-4 border-t border-gray-100">
                        <a href="https://maps.google.com/?q=15000+Gral.+L%C3%ADber+Seregni,+Departamento+de+Canelones" 
                           target="_blank" 
                           class="inline-flex items-center gap-2 text-xs font-bold font-cinzel text-white bg-gradient-to-r from-blush-500 to-gold-mid hover:from-blush-600 hover:to-gold-dark py-3 px-6 rounded-full shadow-md transition-all transform hover:-translate-y-0.5">
                            <i class="fas fa-location-arrow"></i> Cómo Llegar (Google Maps)
                        </a>
                    </div>
                </div>
            </div>
        </section>

        <!-- DRESS CODE & SPECIAL RESERVATION NOTE -->
        <section class="glass-card-pink p-8 rounded-3xl shadow-xl border-2 border-blush-300 relative overflow-hidden">
            <div class="absolute -top-6 -right-6 text-blush-200 text-9xl opacity-30 pointer-events-none">
                <i class="fas fa-crown"></i>
            </div>
            
            <div class="text-center max-w-xl mx-auto space-y-4 relative z-10">
                <div class="inline-flex items-center justify-center p-3.5 bg-white rounded-full text-gold-mid text-2xl shadow-md">
                    <i class="fas fa-user-tie"></i>
                </div>
                <h3 class="font-cinzel text-2xl font-bold text-gray-800">Dress Code: Semiformal</h3>
                <p class="text-gray-600 text-sm">Queremos que te veas elegante y disfrutes de una noche mágica con nosotros.</p>
                
                <!-- HIGHLIGHTED RESERVED COLOR BOX -->
                <div class="bg-white/95 p-6 rounded-2xl shadow-md border-2 border-blush-400 mt-4 text-center transform hover:scale-[1.01] transition-transform">
                    <div class="text-3xl mb-2 text-blush-500">👑 🌸</div>
                    <h4 class="font-cinzel font-bold text-blush-700 text-lg mb-1 tracking-wide">NOTA ESPECIAL</h4>
                    <p class="text-gray-800 font-semibold text-base md:text-lg leading-relaxed">
                        "Por favor, reservamos el <span class="font-bold text-blush-600 underline decoration-gold-mid decoration-2">color rosa</span> exclusivamente para la Quinceañera."
                    </p>
                </div>
            </div>
        </section>

        <!-- RSVP / CONFIRMATION FORM -->
        <section id="rsvp" class="glass-card p-6 sm:p-8 rounded-3xl shadow-xl border border-gold-mid/30 relative">
            <div class="text-center mb-6">
                <span class="text-gold-mid text-3xl inline-block mb-1"><i class="fas fa-envelope-open-text"></i></span>
                <h2 class="font-cinzel text-2xl sm:text-3xl font-bold text-gray-800">Confirmar Asistencia</h2>
                <p class="text-gray-600 text-xs sm:text-sm mt-1">Por favor confirma tu presencia para esperarte con todo preparado</p>
                <div class="w-16 h-0.5 bg-gold-mid mx-auto mt-3"></div>
            </div>

            <form id="rsvpForm" onsubmit="handleRSVP(event)" class="space-y-4 max-w-lg mx-auto">
                <div>
                    <label class="block text-xs font-cinzel font-bold text-gray-700 uppercase mb-1">Nombre Completo *</label>
                    <input type="text" id="rsvpName" required placeholder="Ej: María García" 
                           class="w-full px-4 py-3 rounded-xl border border-gray-300 focus:border-blush-500 focus:ring-2 focus:ring-blush-200 outline-none transition text-sm bg-white/90">
                </div>

                <div>
                    <label class="block text-xs font-cinzel font-bold text-gray-700 uppercase mb-1">¿Asistirás a la Fiesta? *</label>
                    <select id="rsvpStatus" required class="w-full px-4 py-3 rounded-xl border border-gray-300 focus:border-blush-500 focus:ring-2 focus:ring-blush-200 outline-none transition text-sm bg-white/90">
                        <option value="Sí, ¡allí estaré con mucho gusto!">¡Sí, confirmo mi asistencia! 🎉</option>
                        <option value="Lamentablemente no podré asistir">Lamentablemente no podré asistir 😔</option>
                    </select>
                </div>

                <div>
                    <label class="block text-xs font-cinzel font-bold text-gray-700 uppercase mb-1">Restricción Alimentaria</label>
                    <select id="rsvpDiet" class="w-full px-4 py-3 rounded-xl border border-gray-300 focus:border-blush-500 focus:ring-2 focus:ring-blush-200 outline-none transition text-sm bg-white/90">
                        <option value="Ninguna">Ninguna</option>
                        <option value="Celíaco / Sin TACC">Celíaco / Sin TACC</option>
                        <option value="Vegetariano">Vegetariano</option>
                        <option value="Vegano">Vegano</option>
                        <option value="Intolerante a la Lactosa">Intolerante a la Lactosa</option>
                    </select>
                </div>

                <div>
                    <label class="block text-xs font-cinzel font-bold text-gray-700 uppercase mb-1">Mensaje para Eloisa (Opcional)</label>
                    <textarea id="rsvpMessage" rows="2" placeholder="¡Felicidades Elo! Te quiero mucho..." 
                              class="w-full px-4 py-3 rounded-xl border border-gray-300 focus:border-blush-500 focus:ring-2 focus:ring-blush-200 outline-none transition text-sm bg-white/90"></textarea>
                </div>

                <button type="submit" 
                        class="w-full py-4 px-6 rounded-xl bg-gradient-to-r from-blush-600 via-blush-500 to-gold-mid hover:from-blush-700 hover:to-gold-dark text-white font-cinzel font-bold text-sm tracking-wider shadow-lg hover:shadow-xl transition-all transform hover:-translate-y-0.5 flex items-center justify-center gap-3">
                    <i class="fab fa-whatsapp text-xl"></i> Confirmar vía WhatsApp
                </button>
            </form>
        </section>

        <!-- SONG SUGGESTION SECTION -->
        <section class="glass-card p-6 sm:p-8 rounded-3xl shadow-lg border border-gold-mid/30 text-center max-w-lg mx-auto">
            <div class="w-12 h-12 bg-blush-100 text-blush-600 rounded-full flex items-center justify-center mx-auto mb-3 text-xl shadow-inner">
                <i class="fas fa-music"></i>
            </div>
            <h3 class="font-cinzel text-xl font-bold text-gray-800">¿Qué canción no puede faltar?</h3>
            <p class="text-gray-600 text-xs sm:text-sm mt-1 mb-4">Ayúdame a armar la playlist perfecta para bailar toda la noche 🎶</p>

            <form id="songForm" onsubmit="handleSongSubmit(event)" class="space-y-3">
                <input type="text" id="songName" required placeholder="Ej: Shakira - Bizarrap / Taylor Swift" 
                       class="w-full px-4 py-3 rounded-xl border border-gray-300 focus:border-blush-500 focus:ring-2 focus:ring-blush-200 outline-none transition text-sm bg-white/90">
                <button type="submit" class="w-full py-3 px-4 rounded-xl bg-blush-100 text-blush-700 hover:bg-blush-200 font-cinzel font-bold text-xs uppercase tracking-wider transition-colors flex items-center justify-center gap-2">
                    <i class="fas fa-plus-circle"></i> Sugerir Canción
                </button>
            </form>
        </section>

        <!-- GIFTS / CBU SECTION -->
        <section class="glass-card p-6 sm:p-8 rounded-3xl shadow-lg border border-gold-mid/30 text-center max-w-xl mx-auto">
            <div class="w-12 h-12 bg-gold-light text-gold-dark rounded-full flex items-center justify-center mx-auto mb-3 text-xl shadow-inner">
                <i class="fas fa-gift"></i>
            </div>
            <h3 class="font-cinzel text-xl font-bold text-gray-800 mb-2">Muestra de Cariño</h3>
            <p class="text-gray-600 text-sm leading-relaxed mb-4">
                "Tu presencia es mi mejor regalo". Sin embargo, si deseas hacerme un presente para acompañarme a cumplir mis proyectos:
            </p>

            <button onclick="toggleGiftDetails()" class="py-3 px-6 rounded-full bg-white border border-gold-mid text-gold-dark font-cinzel font-bold text-xs uppercase tracking-wider hover:bg-gold-light/40 transition-all shadow-sm">
                <i class="fas fa-university mr-1"></i> Ver Datos Bancarios / Cuenta
            </button>

            <!-- Expandable Bank Info -->
            <div id="giftDetails" class="hidden mt-6 p-4 bg-white/95 rounded-2xl border border-gray-200 text-left space-y-3 text-xs text-gray-700">
                <div class="flex justify-between items-center border-b pb-2">
                    <span class="font-semibold">Titular:</span>
                    <span class="font-bold text-gray-900">Eloisa Simone</span>
                </div>
                <div class="flex justify-between items-center border-b pb-2">
                    <span class="font-semibold">Cuenta / Banco:</span>
                    <span>BROU / Mercado Pago</span>
                </div>
                <div class="flex justify-between items-center border-b pb-2">
                    <span class="font-semibold">Alias / Cuenta:</span>
                    <span id="cbuText" class="font-mono font-bold text-blush-700">eloisa.simone.15</span>
                </div>
                <button onclick="copyCBU()" class="w-full py-2.5 bg-blush-50 hover:bg-blush-100 text-blush-700 rounded-lg font-semibold transition text-center flex items-center justify-center gap-2">
                    <i class="far fa-copy"></i> <span id="copyBtnText">Copiar Datos de Transferencia</span>
                </button>
            </div>
        </section>

        <!-- FOOTER -->
        <footer class="text-center pt-8 pb-12 text-gray-500 text-xs space-y-3">
            <div class="flex justify-center items-center gap-3 text-gold-mid">
                <span class="w-8 h-px bg-gold-mid/40"></span>
                <i class="fas fa-crown"></i>
                <span class="w-8 h-px bg-gold-mid/40"></span>
            </div>
            <p class="font-cinzel font-semibold tracking-wider text-gray-700">ELOISA SIMONE • MIS 15 AÑOS</p>
            <p class="text-gray-400">26 de Diciembre de 2026 — Pasión Fiestas y Eventos</p>
            <p class="text-[10px] text-gray-400 opacity-75">15000 Gral. Líber Seregni, Canelones 🌸</p>
        </footer>

    </main>

    <!-- TOAST NOTIFICATION MODAL -->
    <div id="toast" class="fixed bottom-6 right-6 z-50 transform translate-y-24 opacity-0 transition-all duration-300 max-w-xs bg-gray-900 text-white text-xs px-4 py-3 rounded-xl shadow-2xl flex items-center gap-3">
        <i class="fas fa-check-circle text-emerald-400 text-lg"></i>
        <span id="toastMsg">¡Mensaje listo para enviar!</span>
    </div>

    <!-- HTML5 AUDIO PLAYER -->
    <audio id="bgMusic" loop preload="auto">
        <source src="let_her_go.mp3" type="audio/mpeg">
    </audio>

    <!-- JAVASCRIPT LOGIC -->
    <script>
        // TARGET DATE: Dec 26, 2026, 21:30:00
        const targetDate = new Date('2026-12-26T21:30:00').getTime();

        function updateCountdown() {
            const now = new Date().getTime();
            const distance = targetDate - now;

            if (distance < 0) {
                document.getElementById('days').innerText = "00";
                document.getElementById('hours').innerText = "00";
                document.getElementById('minutes').innerText = "00";
                document.getElementById('seconds').innerText = "00";
                return;
            }

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);

            document.getElementById('days').innerText = String(days).padStart(2, '0');
            document.getElementById('hours').innerText = String(hours).padStart(2, '0');
            document.getElementById('minutes').innerText = String(minutes).padStart(2, '0');
            document.getElementById('seconds').innerText = String(seconds).padStart(2, '0');
        }

        setInterval(updateCountdown, 1000);
        updateCountdown();

        // RSVP FORM TO WHATSAPP
        function handleRSVP(event) {
            event.preventDefault();
            const name = document.getElementById('rsvpName').value.trim();
            const status = document.getElementById('rsvpStatus').value;
            const diet = document.getElementById('rsvpDiet').value;
            const message = document.getElementById('rsvpMessage').value.trim();

            let text = `¡Hola Eloisa! Soy *${name}*.\n`;
            text += `*Confirmación:* ${status}\n`;
            if (diet !== 'Ninguna') text += `*Restricción Alimentaria:* ${diet}\n`;
            if (message) text += `*Mensaje:* ${message}\n`;

            const encodedText = encodeURIComponent(text);
            const whatsappURL = `https://wa.me/?text=${encodedText}`;

            showToast("¡Redirigiendo a WhatsApp!");
            window.open(whatsappURL, '_blank');
        }

        // SONG SUGGESTION TO WHATSAPP
        function handleSongSubmit(event) {
            event.preventDefault();
            const song = document.getElementById('songName').value.trim();
            if (!song) return;

            const text = `¡Hola Eloisa! Sugiero este tema para la fiesta: *${song}* 🎶`;
            const whatsappURL = `https://wa.me/?text=${encodeURIComponent(text)}`;

            showToast("¡Sugerencia enviada!");
            window.open(whatsappURL, '_blank');
            document.getElementById('songName').value = "";
        }

        // BANK DETAILS TOGGLE
        function toggleGiftDetails() {
            const details = document.getElementById('giftDetails');
            details.classList.toggle('hidden');
        }

        // COPY ALIAS / CBU TO CLIPBOARD
        function copyCBU() {
            const textToCopy = "eloisa.simone.15";
            const btnText = document.getElementById('copyBtnText');

            try {
                const tempInput = document.createElement('input');
                tempInput.value = textToCopy;
                document.body.appendChild(tempInput);
                tempInput.select();
                document.execCommand('copy');
                document.body.removeChild(tempInput);

                btnText.innerText = "¡Alias Copiado!";
                showToast("Alias copiado al portapapeles");
                setTimeout(() => { btnText.innerText = "Copiar Datos de Transferencia"; }, 3000);
            } catch (err) {
                showToast("Alias: eloisa.simone.15");
            }
        }

        // TOAST NOTIFICATION DISPLAY
        function showToast(msg) {
            const toast = document.getElementById('toast');
            const toastMsg = document.getElementById('toastMsg');
            toastMsg.innerText = msg;
            toast.classList.remove('translate-y-24', 'opacity-0');
            setTimeout(() => {
                toast.classList.add('translate-y-24', 'opacity-0');
            }, 3500);
        }

        // WELCOME OVERLAY & AUDIO MUSIC
        let bgMusic;
        let isPlaying = false;

        // Initialize HTML5 Audio
        window.addEventListener('DOMContentLoaded', () => {
            bgMusic = document.getElementById('bgMusic');
        });

        function openInvitation() {
            const overlay = document.getElementById('welcomeOverlay');
            overlay.classList.add('opacity-0');
            setTimeout(() => {
                overlay.style.display = 'none';
            }, 700);

            // Attempt to play music when invitation is opened
            if (bgMusic) {
                bgMusic.play().then(() => {
                    isPlaying = true;
                    document.getElementById('musicIcon').className = "fas fa-volume-up text-xl text-blush-600 animate-pulse";
                }).catch((error) => {
                    console.log("Autoplay prevented by browser: ", error);
                });
            }
        }

        function toggleAudio() {
            const musicIcon = document.getElementById('musicIcon');
            if (!bgMusic) {
                showToast("Cargando reproductor...");
                return;
            }

            if (isPlaying) {
                bgMusic.pause();
                isPlaying = false;
                musicIcon.className = "fas fa-music text-xl text-gray-500";
                showToast("Música pausada");
            } else {
                bgMusic.play().then(() => {
                    isPlaying = true;
                    musicIcon.className = "fas fa-volume-up text-xl text-blush-600 animate-pulse";
                    showToast("Música activada");
                });
            }
        }

        // CANVAS PARTICLE SYSTEM: Floating Golden Dust & Pink Butterflies
        const canvas = document.getElementById('bgCanvas');
        const ctx = canvas.getContext('2d');

        let width = canvas.width = window.innerWidth;
        let height = canvas.height = window.innerHeight;

        window.addEventListener('resize', () => {
            width = canvas.width = window.innerWidth;
            height = canvas.height = window.innerHeight;
        });

        class Particle {
            constructor() {
                this.reset();
            }

            reset() {
                this.x = Math.random() * width;
                this.y = Math.random() * height + height;
                this.size = Math.random() * 3.5 + 1;
                this.speedY = Math.random() * 0.8 + 0.3;
                this.speedX = Math.random() * 0.4 - 0.2;
                this.opacity = Math.random() * 0.5 + 0.3;
                this.color = Math.random() > 0.4 ? '#d4af37' : '#f787b1';
                this.isButterfly = Math.random() > 0.82;
                this.wingAngle = 0;
            }

            update() {
                this.y -= this.speedY;
                this.x += Math.sin(this.y * 0.01) * 0.5;
                this.wingAngle += 0.15;

                if (this.y < -20) {
                    this.reset();
                }
            }

            draw() {
                ctx.save();
                ctx.globalAlpha = this.opacity;
                ctx.fillStyle = this.color;

                if (this.isButterfly) {
                    ctx.translate(this.x, this.y);
                    const flapScale = Math.sin(this.wingAngle) * 0.5 + 0.5;
                    ctx.scale(flapScale, 1);
                    
                    ctx.beginPath();
                    ctx.arc(-4, -4, 4, 0, Math.PI * 2);
                    ctx.arc(4, -4, 4, 0, Math.PI * 2);
                    ctx.arc(-3, 2, 3, 0, Math.PI * 2);
                    ctx.arc(3, 2, 3, 0, Math.PI * 2);
                    ctx.fill();
                } else {
                    ctx.beginPath();
                    ctx.arc(this.x, this.y, this.size, 0, Math.PI * 2);
                    ctx.fill();
                }

                ctx.restore();
            }
        }

        const particles = Array.from({ length: 40 }, () => new Particle());

        function animateParticles() {
            ctx.clearRect(0, 0, width, height);
            particles.forEach(p => {
                p.update();
                p.draw();
            });
            requestAnimationFrame(animateParticles);
        }

        animateParticles();
    </script>
</body>
</html>
