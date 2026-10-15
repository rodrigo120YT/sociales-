<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CAN Kawaii Study App 💜✨</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Google Fonts: Quicksand & Fredoka -->
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;600;700&family=Quicksand:wght@500;600;700&display=swap" rel="stylesheet">
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <!-- Canvas Confetti for rewards -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.6.0/dist/confetti.browser.min.js"></script>

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        lavender: {
                            50: '#faf5ff',
                            100: '#f3e8ff',
                            200: '#e9d5ff',
                            300: '#d8b4fe',
                            400: '#c084fc',
                            500: '#a855f7',
                            600: '#9333ea',
                            700: '#7e22ce',
                            800: '#6b21a8',
                            900: '#581c87',
                            950: '#3b0764'
                        }
                    },
                    fontFamily: {
                        sans: ['Quicksand', 'sans-serif'],
                        display: ['Fredoka', 'sans-serif']
                    }
                }
            }
        }
    </script>

    <style>
        /* Mobile usability tweaks & custom backgrounds */
        body {
            background-color: #f6f0fc;
            background-image: radial-gradient(#d8b4fe 1.2px, transparent 1.2px), radial-gradient(#d8b4fe 1.2px, #f6f0fc 1.2px);
            background-size: 36px 36px;
            background-position: 0 0, 18px 18px;
            color: #4a3e56;
            -webkit-tap-highlight-color: transparent;
        }

        /* 3D Flip Card Effect */
        .perspective-1000 {
            perspective: 1000px;
        }
        .transform-style-3d {
            transform-style: preserve-3d;
        }
        .backface-hidden {
            backface-visibility: hidden;
            -webkit-backface-visibility: hidden;
        }
        .rotate-y-180 {
            transform: rotateY(180deg);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            height: 6px;
            width: 6px;
        }
        ::-webkit-scrollbar-track {
            background: #f3e8ff;
        }
        ::-webkit-scrollbar-thumb {
            background: #c084fc;
            border-radius: 10px;
        }

        /* Gentle float animation */
        @keyframes float-kawaii {
            0%, 100% { transform: translateY(0); }
            50% { transform: translateY(-4px); }
        }
        .animate-float {
            animation: float-kawaii 2.5s infinite ease-in-out;
        }

        /* Fade in animation */
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(6px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .animate-fadeIn {
            animation: fadeIn 0.3s ease-out forwards;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col font-sans pb-20 md:pb-8 selection:bg-lavender-300 selection:text-lavender-900">

    <!-- MOBILE-FRIENDLY HEADER -->
    <header class="bg-gradient-to-r from-lavender-500 via-lavender-400 to-lavender-600 text-white shadow-md rounded-b-3xl px-4 py-5 border-b-4 border-lavender-300 sticky top-0 z-30">
        <div class="max-w-3xl mx-auto flex items-center justify-between gap-3">
            <div class="flex items-center gap-3">
                <div class="bg-white p-2.5 rounded-2xl shadow text-lavender-600 text-2xl animate-float">
                    <i class="fa-solid fa-cat"></i>
                </div>
                <div>
                    <h1 class="font-display font-bold text-xl md:text-3xl text-white leading-tight">
                        Aprende CAN Kawaii 💜
                    </h1>
                    <p class="text-lavender-100 text-xs md:text-sm font-medium">
                        Comunidad Andina &bull; Bolivia &amp; Miembros
                    </p>
                </div>
            </div>
            <div class="hidden sm:flex bg-white/20 px-3 py-1.5 rounded-full text-xs font-bold items-center gap-1.5 border border-white/30">
                <i class="fa-solid fa-star text-yellow-300"></i> Móvil Ready
            </div>
        </div>
    </header>

    <!-- MOBILE TABS / NAVIGATION (Bottom Sticky Bar on Mobile, Top Navbar on Desktop) -->
    <nav class="fixed bottom-0 left-0 right-0 md:relative md:top-0 bg-white/95 backdrop-blur-md border-t-2 md:border-2 border-lavender-200 md:rounded-3xl shadow-lg md:shadow-md max-w-3xl mx-auto z-40 my-0 md:my-6">
        <div class="flex justify-around items-center p-1.5 md:p-2">
            <button onclick="switchTab('videos', event)" id="tab-videos" class="tab-btn flex flex-col md:flex-row items-center gap-1 md:gap-2 px-3 py-1.5 md:py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold text-lavender-800 bg-lavender-100 transition">
                <i class="fa-solid fa-circle-play text-base md:text-lg text-lavender-600"></i>
                <span>Vídeos</span>
            </button>
            <button onclick="switchTab('info', event)" id="tab-info" class="tab-btn flex flex-col md:flex-row items-center gap-1 md:gap-2 px-3 py-1.5 md:py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold text-gray-500 hover:bg-lavender-50 transition">
                <i class="fa-solid fa-book-open text-base md:text-lg text-lavender-500"></i>
                <span>Repaso</span>
            </button>
            <button onclick="switchTab('flashcards', event)" id="tab-flashcards" class="tab-btn flex flex-col md:flex-row items-center gap-1 md:gap-2 px-3 py-1.5 md:py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold text-gray-500 hover:bg-lavender-50 transition">
                <i class="fa-solid fa-clone text-base md:text-lg text-lavender-500"></i>
                <span>Fichas</span>
            </button>
            <button onclick="switchTab('quiz', event)" id="tab-quiz" class="tab-btn flex flex-col md:flex-row items-center gap-1 md:gap-2 px-3 py-1.5 md:py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold text-gray-500 hover:bg-lavender-50 transition">
                <i class="fa-solid fa-award text-base md:text-lg text-lavender-500"></i>
                <span>Examen</span>
            </button>
            <button onclick="switchTab('game', event)" id="tab-game" class="tab-btn flex flex-col md:flex-row items-center gap-1 md:gap-2 px-3 py-1.5 md:py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold text-gray-500 hover:bg-lavender-50 transition">
                <i class="fa-solid fa-gamepad text-base md:text-lg text-lavender-500"></i>
                <span>Juego</span>
            </button>
        </div>
    </nav>

    <!-- MAIN APP CONTAINER -->
    <main class="max-w-3xl mx-auto w-full px-3 md:px-4 mt-4 flex-grow">

        <!-- ================= SECTION 1: YOUTUBE VIDEOS (2 VIDEOS ÚNICAMENTE) ================= -->
        <section id="sec-videos" class="tab-content space-y-4 animate-fadeIn">
            <div class="bg-white p-4 md:p-6 rounded-3xl shadow-sm border-2 border-lavender-200">
                <div class="flex items-center gap-2.5 mb-4">
                    <span class="bg-lavender-100 text-lavender-700 p-2.5 rounded-2xl text-xl">
                        <i class="fa-solid fa-video"></i>
                    </span>
                    <div>
                        <h2 class="font-display font-bold text-lg md:text-2xl text-lavender-900">Videoteca CAN 🎬</h2>
                        <p class="text-xs md:text-sm text-gray-600">Aprende rápidamente observando estos minivídeos explicativos.</p>
                    </div>
                </div>

                <div class="space-y-5">
                    <!-- Video 1 -->
                    <div class="bg-lavender-50 p-3 md:p-4 rounded-2xl border border-lavender-200 space-y-2">
                        <h3 class="font-display font-bold text-sm md:text-base text-lavender-900 flex items-center justify-between">
                            <span>Resumen de la CAN en 1 Minuto</span>
                            <span class="text-[10px] md:text-xs bg-lavender-200 text-lavender-800 px-2 py-0.5 rounded-full font-bold">Concepto General</span>
                        </h3>
                        <div class="relative w-full aspect-video rounded-xl overflow-hidden shadow bg-black border border-lavender-200">
                            <iframe class="w-full h-full" src="https://www.youtube-nocookie.com/embed/clyqMUbN4YQ" title="¿Qué es la Comunidad Andina?" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <p class="text-xs text-gray-600">Video explicativo animado sobre la creación, historia y principios del organismo andino.</p>
                    </div>

                    <!-- Video 2 -->
                    <div class="bg-lavender-50 p-3 md:p-4 rounded-2xl border border-lavender-200 space-y-2">
                        <h3 class="font-display font-bold text-sm md:text-base text-lavender-900 flex items-center justify-between">
                            <span>Beneficios de la CAN para Bolivia</span>
                            <span class="text-[10px] md:text-xs bg-purple-200 text-purple-900 px-2 py-0.5 rounded-full font-bold">Bolivia & Beneficios</span>
                        </h3>
                        <div class="relative w-full aspect-video rounded-xl overflow-hidden shadow bg-black border border-lavender-200">
                            <iframe class="w-full h-full" src="https://www.youtube-nocookie.com/embed/IIgywEaHgeU" title="Beneficios Ciudadanos CAN" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
                        </div>
                        <p class="text-xs text-gray-600">Conoce los derechos de tránsito libre con Cédula de Identidad, estatutos de trabajo y aranceles 0%.</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= SECTION 2: INFORMACIÓN & PAÍSES ================= -->
        <section id="sec-info" class="tab-content hidden space-y-4 animate-fadeIn">
            <!-- Selector interactivo de países -->
            <div class="bg-white p-4 md:p-6 rounded-3xl shadow-sm border-2 border-lavender-200 space-y-4">
                <div class="flex items-center gap-2.5">
                    <span class="bg-lavender-100 text-lavender-700 p-2.5 rounded-2xl text-xl">
                        <i class="fa-solid fa-earth-americas"></i>
                    </span>
                    <div>
                        <h2 class="font-display font-bold text-lg md:text-2xl text-lavender-900">Países Miembros 🌎</h2>
                        <p class="text-xs md:text-sm text-gray-600">Toca cada bandera para ver sus detalles dentro de la CAN.</p>
                    </div>
                </div>

                <div class="grid grid-cols-4 gap-2">
                    <button onclick="selectCountry('bolivia', this)" class="country-btn bg-lavender-200 text-lavender-950 p-2 md:p-3 rounded-2xl border-2 border-lavender-400 transition flex flex-col items-center gap-1 shadow-sm font-bold">
                        <span class="text-2xl md:text-3xl">🇧🇴</span>
                        <span class="font-display text-[11px] md:text-xs">Bolivia</span>
                    </button>
                    <button onclick="selectCountry('colombia', this)" class="country-btn bg-lavender-50 text-lavender-900 p-2 md:p-3 rounded-2xl border-2 border-lavender-200 transition flex flex-col items-center gap-1 shadow-sm">
                        <span class="text-2xl md:text-3xl">🇨🇴</span>
                        <span class="font-display text-[11px] md:text-xs">Colombia</span>
                    </button>
                    <button onclick="selectCountry('ecuador', this)" class="country-btn bg-lavender-50 text-lavender-900 p-2 md:p-3 rounded-2xl border-2 border-lavender-200 transition flex flex-col items-center gap-1 shadow-sm">
                        <span class="text-2xl md:text-3xl">🇪🇨</span>
                        <span class="font-display text-[11px] md:text-xs">Ecuador</span>
                    </button>
                    <button onclick="selectCountry('peru', this)" class="country-btn bg-lavender-50 text-lavender-900 p-2 md:p-3 rounded-2xl border-2 border-lavender-200 transition flex flex-col items-center gap-1 shadow-sm">
                        <span class="text-2xl md:text-3xl">🇵🇪</span>
                        <span class="font-display text-[11px] md:text-xs">Perú</span>
                    </button>
                </div>

                <!-- Country Details Card -->
                <div id="country-display" class="bg-gradient-to-r from-lavender-100 to-purple-50 p-4 rounded-2xl border-2 border-lavender-200 flex items-start gap-3">
                    <div id="country-flag" class="text-3xl md:text-4xl p-2 bg-white rounded-xl shadow-sm border border-lavender-200">🇧🇴</div>
                    <div class="space-y-1">
                        <h3 id="country-name" class="font-display font-bold text-sm md:text-base text-lavender-900">Bolivia (Estado Plurinacional)</h3>
                        <p id="country-info" class="text-gray-700 text-xs md:text-sm leading-relaxed">
                            Zona andina de libre comercio. Libre circulación de productos sin pago de aranceles. Los ciudadanos bolivianos pueden desplazarse a Colombia, Ecuador y Perú presentando únicamente su Cédula de Identidad (sin visa ni pasaporte).
                        </p>
                    </div>
                </div>
            </div>

            <!-- Acordeón interactivo de Contenido Académico -->
            <div class="bg-white p-4 md:p-6 rounded-3xl shadow-sm border-2 border-lavender-200 space-y-3">
                <div class="flex items-center gap-2 mb-1">
                    <span class="bg-lavender-100 text-lavender-700 p-2 rounded-2xl text-lg">
                        <i class="fa-solid fa-graduation-cap"></i>
                    </span>
                    <h2 class="font-display font-bold text-lg md:text-2xl text-lavender-900">Temario de Estudio 📚</h2>
                </div>

                <!-- Accordion 1 -->
                <div class="border-2 border-lavender-100 rounded-2xl overflow-hidden">
                    <button onclick="toggleAccordion('acc-1')" class="w-full text-left p-3 md:p-4 bg-lavender-50 hover:bg-lavender-100 font-display font-bold text-xs md:text-sm text-lavender-900 flex justify-between items-center">
                        <span><i class="fa-solid fa-star text-lavender-500 mr-1.5"></i> ¿Qué es la Comunidad Andina?</span>
                        <i id="acc-1-icon" class="fa-solid fa-chevron-down text-lavender-500 text-xs"></i>
                    </button>
                    <div id="acc-1" class="hidden p-3 md:p-4 bg-white text-xs md:text-sm text-gray-700 border-t border-lavender-100 leading-relaxed">
                        Es un organismo de integración regional con el propósito de impulsar el desarrollo económico y social de sus países miembros mediante la libre circulación de bienes, servicios y personas, y la coordinación de políticas comunes.
                    </div>
                </div>

                <!-- Accordion 2 -->
                <div class="border-2 border-lavender-100 rounded-2xl overflow-hidden">
                    <button onclick="toggleAccordion('acc-2')" class="w-full text-left p-3 md:p-4 bg-lavender-50 hover:bg-lavender-100 font-display font-bold text-xs md:text-sm text-lavender-900 flex justify-between items-center">
                        <span><i class="fa-solid fa-calendar-check text-lavender-500 mr-1.5"></i> Acuerdo de Cartagena (1969)</span>
                        <i id="acc-2-icon" class="fa-solid fa-chevron-down text-lavender-500 text-xs"></i>
                    </button>
                    <div id="acc-2" class="hidden p-3 md:p-4 bg-white text-xs md:text-sm text-gray-700 border-t border-lavender-100 leading-relaxed">
                        Fundada oficialmente el <b>26 de mayo de 1969</b> mediante el Acuerdo de Cartagena. Nació con el objetivo de promover un desarrollo equilibrado y armónico entre sus integrantes.
                    </div>
                </div>

                <!-- Accordion 3 -->
                <div class="border-2 border-lavender-100 rounded-2xl overflow-hidden">
                    <button onclick="toggleAccordion('acc-3')" class="w-full text-left p-3 md:p-4 bg-lavender-50 hover:bg-lavender-100 font-display font-bold text-xs md:text-sm text-lavender-900 flex justify-between items-center">
                        <span><i class="fa-solid fa-sitemap text-lavender-500 mr-1.5"></i> Sistema Andino de Integración (S.A.I.)</span>
                        <i id="acc-3-icon" class="fa-solid fa-chevron-down text-lavender-500 text-xs"></i>
                    </button>
                    <div id="acc-3" class="hidden p-3 md:p-4 bg-white text-xs md:text-sm text-gray-700 space-y-2 border-t border-lavender-100 leading-relaxed">
                        <p>Estructura institucional conformada por:</p>
                        <ul class="list-disc pl-4 space-y-1">
                            <li><b>Consejo Presidencial Andino:</b> Máxima reunión de Jefes de Estado.</li>
                            <li><b>Consejo Andino de Ministros de RR.EE.:</b> Formulación de política exterior.</li>
                            <li><b>Comisión de la CAN:</b> Órgano normativo comercial.</li>
                            <li><b>Secretaría General (Lima, Perú):</b> Órgano ejecutivo.</li>
                            <li><b>Tribunal Andino de Justicia:</b> Control de legalidad.</li>
                        </ul>
                    </div>
                </div>

                <!-- Accordion 4 -->
                <div class="border-2 border-lavender-100 rounded-2xl overflow-hidden">
                    <button onclick="toggleAccordion('acc-4')" class="w-full text-left p-3 md:p-4 bg-lavender-50 hover:bg-lavender-100 font-display font-bold text-xs md:text-sm text-lavender-900 flex justify-between items-center">
                        <span><i class="fa-solid fa-user-tie text-lavender-500 mr-1.5"></i> Autoridad Actual (Secretario General)</span>
                        <i id="acc-4-icon" class="fa-solid fa-chevron-down text-lavender-500 text-xs"></i>
                    </button>
                    <div id="acc-4" class="hidden p-3 md:p-4 bg-white text-xs md:text-sm text-gray-700 border-t border-lavender-100 leading-relaxed">
                        La Secretaría General tiene su sede principal en la ciudad de <b>Lima, Perú</b>. El actual Secretario General es el diplomático embajador <b>Gonzalo Gutiérrez Reinel</b>.
                    </div>
                </div>
            </div>
        </section>

        <!-- ================= SECTION 3: FLASHCARDS 3D ================= -->
        <section id="sec-flashcards" class="tab-content hidden space-y-4 animate-fadeIn">
            <div class="bg-white p-4 md:p-6 rounded-3xl shadow-sm border-2 border-lavender-200 text-center space-y-4">
                <div>
                    <h2 class="font-display font-bold text-lg md:text-2xl text-lavender-900">Fichas de Estudio 🃏</h2>
                    <p class="text-xs text-gray-500">Toca la ficha para girarla y revelar la respuesta.</p>
                </div>

                <!-- 3D Card Container -->
                <div class="flex justify-center my-2">
                    <div onclick="flipFlashcard()" class="w-full max-w-sm h-64 md:h-72 perspective-1000 cursor-pointer active:scale-98 transition-transform">
                        <div id="flashcard-inner" class="relative w-full h-full transform-style-3d transition-transform duration-500 shadow-md rounded-3xl border-4 border-lavender-300 bg-gradient-to-br from-white to-lavender-50">
                            <!-- Front -->
                            <div class="absolute inset-0 backface-hidden flex flex-col justify-between p-5 rounded-3xl text-lavender-900">
                                <div class="flex justify-between items-center text-[10px] md:text-xs font-bold text-lavender-500 uppercase tracking-wider">
                                    <span><i class="fa-solid fa-circle-question"></i> Pregunta</span>
                                    <span id="fc-counter">1 / 6</span>
                                </div>
                                <div class="my-auto px-2">
                                    <p id="fc-question" class="font-display font-bold text-base md:text-xl text-lavender-800 leading-snug">
                                        ¿Cuándo y mediante qué acuerdo se creó la Comunidad Andina?
                                    </p>
                                </div>
                                <div class="text-[11px] text-lavender-400 font-semibold flex items-center justify-center gap-1">
                                    <i class="fa-solid fa-rotate"></i> Toca para girar ✨
                                </div>
                            </div>
                            <!-- Back -->
                            <div class="absolute inset-0 backface-hidden rotate-y-180 flex flex-col justify-between p-5 rounded-3xl bg-gradient-to-br from-lavender-500 to-lavender-700 text-white">
                                <div class="flex justify-between items-center text-[10px] md:text-xs font-bold text-lavender-200 uppercase tracking-wider">
                                    <span><i class="fa-solid fa-circle-check"></i> Respuesta Explicada</span>
                                    <i class="fa-solid fa-heart text-xs"></i>
                                </div>
                                <div class="my-auto px-2">
                                    <p id="fc-answer" class="font-sans font-semibold text-xs md:text-base text-white leading-relaxed">
                                        El 26 de mayo de 1969 mediante la firma del histórico Acuerdo de Cartagena.
                                    </p>
                                </div>
                                <div class="text-[11px] text-lavender-200 font-semibold flex items-center justify-center gap-1">
                                    <i class="fa-solid fa-rotate"></i> Toca para regresar
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Navigation Controls -->
                <div class="flex justify-center items-center gap-3 pt-1">
                    <button onclick="prevFlashcard()" class="bg-lavender-100 hover:bg-lavender-200 active:bg-lavender-300 text-lavender-800 px-4 py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold shadow-sm transition">
                        <i class="fa-solid fa-arrow-left mr-1"></i> Anterior
                    </button>
                    <button onclick="nextFlashcard()" class="bg-lavender-500 hover:bg-lavender-600 active:bg-lavender-700 text-white px-5 py-2.5 rounded-2xl font-display text-xs md:text-sm font-bold shadow transition">
                        Siguiente <i class="fa-solid fa-arrow-right ml-1"></i>
                    </button>
                </div>
            </div>
        </section>

        <!-- ================= SECTION 4: EXAMEN INTERACTIVO CON RETROALIMENTACIÓN ================= -->
        <section id="sec-quiz" class="tab-content hidden space-y-4 animate-fadeIn">
            <div class="bg-white p-4 md:p-6 rounded-3xl shadow-sm border-2 border-lavender-200 space-y-4">
                <!-- Header -->
                <div class="flex justify-between items-center border-b border-lavender-100 pb-3">
                    <div>
                        <h2 class="font-display font-bold text-lg md:text-2xl text-lavender-900">Examen Kawaii 📝</h2>
                        <p class="text-xs text-gray-500">Explicación instantánea al responder cada pregunta.</p>
                    </div>
                    <div class="bg-lavender-100 px-3 py-1.5 rounded-2xl border border-lavender-300 font-display font-bold text-lavender-800 text-xs md:text-sm">
                        Puntaje: <span id="quiz-score-num" class="text-lavender-600">0</span>/100
                    </div>
                </div>

                <!-- Progress Bar -->
                <div class="w-full bg-lavender-100 rounded-full h-2.5 overflow-hidden">
                    <div id="quiz-progress" class="bg-gradient-to-r from-lavender-400 to-lavender-600 h-full w-0 transition-all duration-300"></div>
                </div>

                <!-- Question Box -->
                <div id="quiz-box" class="space-y-4">
                    <h3 id="quiz-question-title" class="font-display font-bold text-sm md:text-base text-lavender-900 leading-snug">
                        Cargando pregunta...
                    </h3>

                    <!-- Options list -->
                    <div id="quiz-options" class="space-y-2">
                        <!-- Options filled dynamically -->
                    </div>

                    <!-- EXPLANATION FEEDBACK BANNER -->
                    <div id="quiz-explanation" class="hidden p-4 rounded-2xl border-2 space-y-1.5 transition-all text-xs md:text-sm">
                        <div class="flex items-center gap-2 font-display font-bold" id="explanation-header">
                            <!-- Title -->
                        </div>
                        <p id="explanation-text" class="text-gray-700 leading-relaxed">
                            Explicación...
                        </p>
                    </div>

                    <div class="flex justify-end pt-1">
                        <button id="quiz-next-btn" onclick="nextQuizQuestion()" class="hidden bg-lavender-500 active:bg-lavender-700 text-white font-display font-bold text-xs md:text-sm px-5 py-2.5 rounded-2xl shadow transition items-center gap-1">
                            Siguiente <i class="fa-solid fa-angles-right text-xs"></i>
                        </button>
                    </div>
                </div>

                <!-- Results view -->
                <div id="quiz-results" class="hidden text-center space-y-4 py-6">
                    <div class="text-5xl text-lavender-500 animate-float">
                        <i class="fa-solid fa-trophy"></i>
                    </div>
                    <h3 class="font-display font-bold text-2xl text-lavender-900">¡Examen Completado!</h3>
                    <p id="quiz-final-msg" class="text-gray-700 text-sm font-semibold max-w-xs mx-auto">
                        Obtuviste tu nota final.
                    </p>
                    <button onclick="restartQuiz()" class="bg-lavender-500 hover:bg-lavender-600 active:bg-lavender-700 text-white font-display font-bold px-6 py-3 rounded-2xl shadow transition text-sm">
                        <i class="fa-solid fa-rotate-right mr-1"></i> Intentar de nuevo
                    </button>
                </div>
            </div>
        </section>

        <!-- ================= SECTION 5: MINIJUEGO INTERACTIVO SAI ================= -->
        <section id="sec-game" class="tab-content hidden space-y-4 animate-fadeIn">
            <div class="bg-white p-4 md:p-6 rounded-3xl shadow-sm border-2 border-lavender-200 text-center space-y-4">
                <div>
                    <h2 class="font-display font-bold text-lg md:text-2xl text-lavender-900">Juego: Empareja el SAI 🎮</h2>
                    <p class="text-xs text-gray-500">Toca un Órgano y luego toca su Función correspondiente.</p>
                </div>

                <div class="grid grid-cols-1 md:grid-cols-2 gap-3 text-left">
                    <!-- Organs -->
                    <div class="space-y-2">
                        <h4 class="font-display font-bold text-xs text-lavender-700 uppercase tracking-wider text-center">🏛️ Órganos</h4>
                        <div id="game-organs" class="space-y-2"></div>
                    </div>
                    <!-- Functions -->
                    <div class="space-y-2">
                        <h4 class="font-display font-bold text-xs text-lavender-700 uppercase tracking-wider text-center">🎯 Funciones</h4>
                        <div id="game-functions" class="space-y-2"></div>
                    </div>
                </div>

                <div id="game-status" class="bg-lavender-50 p-3 rounded-2xl border border-lavender-200 font-display font-bold text-lavender-800 text-xs">
                    Selecciona un elemento para empezar.
                </div>

                <button onclick="initGame()" class="bg-lavender-500 active:bg-lavender-700 text-white font-display font-bold px-5 py-2.5 rounded-2xl shadow transition text-xs">
                    <i class="fa-solid fa-rotate mr-1"></i> Reiniciar Juego
                </button>
            </div>
        </section>

    </main>

    <!-- FOOTER -->
    <footer class="mt-8 text-center text-[11px] text-lavender-600 font-semibold space-y-1 mb-16 md:mb-4 px-4">
        <p>Comunidad Andina (CAN) &bull; Aplicación Didáctica para Ciencias Sociales 🇧🇴</p>
        <p class="text-lavender-400">Estética Kawaii Lila Móvil-First ✨ 2026</p>
    </footer>

    <!-- JAVASCRIPT LOGIC EXHAUSTIVELY VERIFIED -->
    <script>
        /* ================= NAVIGATION TABS ================= */
        function switchTab(tabName, evt) {
            document.querySelectorAll('.tab-content').forEach(el => el.classList.add('hidden'));
            document.querySelectorAll('.tab-btn').forEach(btn => {
                btn.classList.remove('bg-lavender-100', 'text-lavender-800');
                btn.classList.add('text-gray-500');
            });

            const targetSec = document.getElementById(`sec-${tabName}`);
            if (targetSec) {
                targetSec.classList.remove('hidden');
            }
            
            const btn = evt ? evt.currentTarget : document.getElementById(`tab-${tabName}`);
            if (btn) {
                btn.classList.add('bg-lavender-100', 'text-lavender-800');
                btn.classList.remove('text-gray-500');
            }
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }

        /* ================= COUNTRY DISPLAY ================= */
        const countryData = {
            bolivia: {
                flag: '🇧🇴',
                name: 'Bolivia (Estado Plurinacional)',
                info: 'Zona andina de libre comercio. Libre circulación de productos sin pago de aranceles. Los ciudadanos bolivianos pueden desplazarse a Colombia, Ecuador y Perú presentando únicamente su Cédula de Identidad (sin visa ni pasaporte).'
            },
            colombia: {
                flag: '🇨🇴',
                name: 'Colombia',
                info: 'País fundador. Beneficios comerciales de aranceles cero, reconocimiento de títulos universitarios y roaming celular sin recargo internacional en la subregión.'
            },
            ecuador: {
                flag: '🇪🇨',
                name: 'Ecuador',
                info: 'Miembro activo desde la creación en 1969. Promueve la cooperación para el desarrollo sustentable y la protección social comunitaria.'
            },
            peru: {
                flag: '🇵🇪',
                name: 'Perú',
                info: 'Sede central de la Secretaría General de la CAN (Lima). Centro administrativo del proceso de integración andina.'
            }
        };

        function selectCountry(key, btnElement) {
            const data = countryData[key];
            if (!data) return;

            document.getElementById('country-flag').innerText = data.flag;
            document.getElementById('country-name').innerText = data.name;
            document.getElementById('country-info').innerText = data.info;

            document.querySelectorAll('.country-btn').forEach(b => {
                b.className = "country-btn bg-lavender-50 text-lavender-900 p-2 md:p-3 rounded-2xl border-2 border-lavender-200 transition flex flex-col items-center gap-1 shadow-sm";
            });

            if (btnElement) {
                btnElement.className = "country-btn bg-lavender-200 text-lavender-950 p-2 md:p-3 rounded-2xl border-2 border-lavender-400 transition flex flex-col items-center gap-1 shadow-sm font-bold";
            }
        }

        /* ================= ACCORDION ================= */
        function toggleAccordion(id) {
            const content = document.getElementById(id);
            const icon = document.getElementById(`${id}-icon`);
            if (!content || !icon) return;

            if (content.classList.contains('hidden')) {
                content.classList.remove('hidden');
                icon.classList.replace('fa-chevron-down', 'fa-chevron-up');
            } else {
                content.classList.add('hidden');
                icon.classList.replace('fa-chevron-up', 'fa-chevron-down');
            }
        }

        /* ================= FLASHCARDS 3D ================= */
        const flashcardList = [
            {
                q: "¿Cuándo y mediante qué acuerdo se creó la Comunidad Andina?",
                a: "El 26 de mayo de 1969 mediante la firma del histórico Acuerdo de Cartagena."
            },
            {
                q: "¿Cuáles son los 4 países miembros de la CAN?",
                a: "Bolivia, Colombia, Ecuador y Perú."
            },
            {
                q: "¿Qué beneficio de viaje tienen los ciudadanos bolivianos en la CAN?",
                a: "Pueden ingresar y circular por los países miembros mostrando únicamente su Cédula de Identidad, sin requerir pasaporte ni visa."
            },
            {
                q: "¿Dónde está la Secretaría General y quién es el Secretario General actual?",
                a: "Está en Lima, Perú. El Secretario General actual es el embajador Gonzalo Gutiérrez Reinel."
            },
            {
                q: "¿Qué es el Sistema Andino de Integración (S.A.I.)?",
                a: "Es el conjunto de órganos e instituciones (Consejo Presidencial, Ministros, Comisión, Tribunal) articulados para la integración."
            },
            {
                q: "¿Cuál es la función del Tribunal Andino de Justicia?",
                a: "Es la entidad encargada de controlar la legalidad de las normas y actos de los Órganos e Instituciones del SAI."
            }
        ];

        let fcIndex = 0;
        let isFlipped = false;

        function updateFlashcardUI() {
            isFlipped = false;
            const inner = document.getElementById('flashcard-inner');
            if (inner) inner.classList.remove('rotate-y-180');
            
            document.getElementById('fc-counter').innerText = `${fcIndex + 1} / ${flashcardList.length}`;
            document.getElementById('fc-question').innerText = flashcardList[fcIndex].q;
            document.getElementById('fc-answer').innerText = flashcardList[fcIndex].a;
        }

        function flipFlashcard() {
            isFlipped = !isFlipped;
            const inner = document.getElementById('flashcard-inner');
            if (!inner) return;

            if (isFlipped) {
                inner.classList.add('rotate-y-180');
            } else {
                inner.classList.remove('rotate-y-180');
            }
        }

        function nextFlashcard() {
            fcIndex = (fcIndex + 1) % flashcardList.length;
            updateFlashcardUI();
        }

        function prevFlashcard() {
            fcIndex = (fcIndex - 1 + flashcardList.length) % flashcardList.length;
            updateFlashcardUI();
        }

        /* ================= QUIZ WITH EXPLANATION ================= */
        const quizData = [
            {
                q: "¿Mediante qué acuerdo histórico se creó la Comunidad Andina en 1969?",
                options: [
                    "Acuerdo de Cartagena",
                    "Tratado de Versalles",
                    "Pacto de Lima",
                    "Tratado de Paz y Amistad"
                ],
                correct: 0,
                explanation: "El Acuerdo de Cartagena fue firmado el 26 de mayo de 1969, dando nacimiento formal al proceso de integración andino."
            },
            {
                q: "¿Cuáles son los 4 países miembros de la Comunidad Andina?",
                options: [
                    "Chile, Argentina, Paraguay y Bolivia",
                    "Bolivia, Colombia, Ecuador y Perú",
                    "Venezuela, Brasil, Uruguay y Colombia",
                    "México, Perú, Ecuador y Chile"
                ],
                correct: 1,
                explanation: "Actualmente la CAN está integrada por 4 naciones: Bolivia, Colombia, Ecuador y Perú."
            },
            {
                q: "Para viajar de Bolivia a Perú o Ecuador dentro de la CAN, ¿qué documento es suficiente?",
                options: [
                    "Visa consular obligatoria",
                    "Pasaporte internacional andino",
                    "Cédula de Identidad (DNI)",
                    "Permiso de trabajo temporal"
                ],
                correct: 2,
                explanation: "La normativa comunitaria permite el libre tránsito de ciudadanos presentando únicamente su Cédula de Identidad personal."
            },
            {
                q: "¿Dónde se ubica la sede principal de la Secretaría General de la CAN?",
                options: [
                    "La Paz, Bolivia",
                    "Bogotá, Colombia",
                    "Quito, Ecuador",
                    "Lima, Perú"
                ],
                correct: 3,
                explanation: "La sede administrativa de la Secretaría General de la CAN está en Lima, Perú."
            },
            {
                q: "¿Quién es el actual Secretario General de la CAN?",
                options: [
                    "Gonzalo Gutiérrez Reinel",
                    "Nelson Quispe Fernández",
                    "Simón Bolívar",
                    "Antonio José de Sucre"
                ],
                correct: 0,
                explanation: "El embajador peruano Gonzalo Gutiérrez Reinel ejerce el cargo de Secretario General de la Comunidad Andina."
            }
        ];

        let quizCurrent = 0;
        let quizScore = 0;
        let quizAnswered = false;

        function loadQuizQuestion() {
            quizAnswered = false;
            const q = quizData[quizCurrent];

            const progPercent = (quizCurrent / quizData.length) * 100;
            document.getElementById('quiz-progress').style.width = `${progPercent}%`;

            document.getElementById('quiz-question-title').innerText = `${quizCurrent + 1}. ${q.q}`;
            document.getElementById('quiz-explanation').classList.add('hidden');
            
            const nextBtn = document.getElementById('quiz-next-btn');
            nextBtn.classList.add('hidden');
            nextBtn.classList.remove('flex');

            const optionsContainer = document.getElementById('quiz-options');
            optionsContainer.innerHTML = '';

            q.options.forEach((optText, index) => {
                const btn = document.createElement('button');
                btn.className = "w-full text-left p-3 md:p-4 rounded-2xl border-2 border-lavender-200 bg-white hover:bg-lavender-50 active:bg-lavender-100 font-semibold text-xs md:text-sm text-gray-800 transition flex items-center justify-between shadow-sm";
                btn.innerHTML = `<span>${optText}</span> <i class="fa-regular fa-circle text-lavender-300"></i>`;
                btn.onclick = () => handleQuizAnswer(index, btn);
                optionsContainer.appendChild(btn);
            });
        }

        function handleQuizAnswer(selectedIndex, btnElement) {
            if (quizAnswered) return;
            quizAnswered = true;

            const q = quizData[quizCurrent];
            const allOptionBtns = document.querySelectorAll('#quiz-options button');
            const expBanner = document.getElementById('quiz-explanation');
            const expHeader = document.getElementById('explanation-header');
            const expText = document.getElementById('explanation-text');

            allOptionBtns.forEach(b => b.classList.add('cursor-not-allowed'));

            if (selectedIndex === q.correct) {
                quizScore += 20;
                document.getElementById('quiz-score-num').innerText = quizScore;
                btnElement.className = "w-full text-left p-3 md:p-4 rounded-2xl border-2 border-green-400 bg-green-50 font-bold text-xs md:text-sm text-green-900 flex items-center justify-between shadow-sm";
                btnElement.querySelector('i').className = "fa-solid fa-circle-check text-green-500 text-base";

                expBanner.className = "p-4 rounded-2xl border-2 border-green-300 bg-green-50 text-green-950 space-y-1 block animate-fadeIn";
                expHeader.innerHTML = `<i class="fa-solid fa-circle-check text-green-600"></i> ¡Correcto! ✨`;
                expText.innerText = q.explanation;

                if (typeof confetti === 'function') {
                    confetti({ particleCount: 25, spread: 50, origin: { y: 0.7 } });
                }
            } else {
                btnElement.className = "w-full text-left p-3 md:p-4 rounded-2xl border-2 border-red-300 bg-red-50 font-bold text-xs md:text-sm text-red-900 flex items-center justify-between shadow-sm";
                btnElement.querySelector('i').className = "fa-solid fa-circle-xmark text-red-500 text-base";

                const correctBtn = allOptionBtns[q.correct];
                if (correctBtn) {
                    correctBtn.className = "w-full text-left p-3 md:p-4 rounded-2xl border-2 border-green-400 bg-green-50 font-bold text-xs md:text-sm text-green-900 flex items-center justify-between shadow-sm";
                    correctBtn.querySelector('i').className = "fa-solid fa-circle-check text-green-500 text-base";
                }

                expBanner.className = "p-4 rounded-2xl border-2 border-purple-300 bg-purple-50 text-purple-950 space-y-1 block animate-fadeIn";
                expHeader.innerHTML = `<i class="fa-solid fa-circle-info text-lavender-600"></i> Explicación didáctica:`;
                expText.innerText = `Respuesta correcta: "${q.options[q.correct]}".\n\nExplicación: ${q.explanation}`;
            }

            const nextBtn = document.getElementById('quiz-next-btn');
            nextBtn.classList.remove('hidden');
            nextBtn.classList.add('flex');
        }

        function nextQuizQuestion() {
            quizCurrent++;
            if (quizCurrent < quizData.length) {
                loadQuizQuestion();
            } else {
                showQuizResults();
            }
        }

        function showQuizResults() {
            document.getElementById('quiz-box').classList.add('hidden');
            document.getElementById('quiz-results').classList.remove('hidden');
            document.getElementById('quiz-progress').style.width = `100%`;

            const finalMsg = document.getElementById('quiz-final-msg');
            finalMsg.innerText = `Puntaje final: ${quizScore} de 100 puntos. ¡Excelente esfuerzo!`;

            if (quizScore >= 80 && typeof confetti === 'function') {
                confetti({ particleCount: 80, spread: 70, origin: { y: 0.6 } });
            }
        }

        function restartQuiz() {
            quizCurrent = 0;
            quizScore = 0;
            document.getElementById('quiz-score-num').innerText = '0';
            document.getElementById('quiz-results').classList.add('hidden');
            document.getElementById('quiz-box').classList.remove('hidden');
            loadQuizQuestion();
        }

        /* ================= MATCH GAME ================= */
        const gamePairs = [
            { id: 1, organ: "Consejo Presidencial", func: "Máxima reunión de Jefes de Estado." },
            { id: 2, organ: "Ministros de RR.EE.", func: "Formula la política exterior común." },
            { id: 3, organ: "Comisión de la CAN", func: "Órgano normativo comercial." },
            { id: 4, organ: "Tribunal de Justicia", func: "Controla la legalidad de los actos." }
        ];

        let selectedOrgan = null;
        let matchedCount = 0;

        function initGame() {
            selectedOrgan = null;
            matchedCount = 0;
            const gameStatus = document.getElementById('game-status');
            gameStatus.innerText = "Selecciona un Órgano y luego su Función.";
            gameStatus.className = "bg-lavender-50 p-3 rounded-2xl border border-lavender-200 font-display font-bold text-lavender-800 text-xs";

            const organsDiv = document.getElementById('game-organs');
            const funcsDiv = document.getElementById('game-functions');

            organsDiv.innerHTML = '';
            funcsDiv.innerHTML = '';

            const shuffledFuncs = [...gamePairs].sort(() => Math.random() - 0.5);

            gamePairs.forEach(item => {
                const btn = document.createElement('button');
                btn.className = "organ-btn w-full text-left p-3 rounded-xl border-2 border-lavender-200 bg-white active:bg-lavender-100 font-bold text-xs text-lavender-900 transition shadow-sm";
                btn.innerText = item.organ;
                btn.dataset.id = item.id;
                btn.onclick = () => selectOrganBtn(btn, item.id);
                organsDiv.appendChild(btn);
            });

            shuffledFuncs.forEach(item => {
                const btn = document.createElement('button');
                btn.className = "func-btn w-full text-left p-3 rounded-xl border-2 border-lavender-200 bg-white active:bg-lavender-100 font-semibold text-[11px] text-gray-700 transition shadow-sm";
                btn.innerText = item.func;
                btn.dataset.id = item.id;
                btn.onclick = () => selectFuncBtn(btn, item.id);
                funcsDiv.appendChild(btn);
            });
        }

        function selectOrganBtn(btn, id) {
            document.querySelectorAll('.organ-btn').forEach(b => {
                if (!b.disabled) b.className = "organ-btn w-full text-left p-3 rounded-xl border-2 border-lavender-200 bg-white active:bg-lavender-100 font-bold text-xs text-lavender-900 transition shadow-sm";
            });
            btn.className = "organ-btn w-full text-left p-3 rounded-xl border-2 border-lavender-500 bg-lavender-200 font-bold text-xs text-lavender-900 transition shadow";
            selectedOrgan = id;
            document.getElementById('game-status').innerText = "Toca su función correspondiente.";
        }

        function selectFuncBtn(btn, id) {
            if (!selectedOrgan) {
                document.getElementById('game-status').innerText = "⚠️ Selecciona primero un Órgano.";
                return;
            }

            if (selectedOrgan === id) {
                matchedCount++;
                const organBtn = document.querySelector(`.organ-btn[data-id="${id}"]`);

                if (organBtn) {
                    organBtn.className = "w-full text-left p-3 rounded-xl border-2 border-green-300 bg-green-100 font-bold text-xs text-green-900 opacity-60 cursor-not-allowed";
                    organBtn.disabled = true;
                }
                
                btn.className = "w-full text-left p-3 rounded-xl border-2 border-green-300 bg-green-100 font-semibold text-[11px] text-green-900 opacity-60 cursor-not-allowed";
                btn.disabled = true;
                selectedOrgan = null;

                document.getElementById('game-status').innerText = "✨ ¡Pareja Correcta!";

                if (matchedCount === gamePairs.length) {
                    const gameStatus = document.getElementById('game-status');
                    gameStatus.innerText = "🎉 ¡Completaste el Minijuego!";
                    gameStatus.className = "bg-green-100 p-3 rounded-2xl border border-green-300 font-display font-bold text-green-900 text-xs";
                    if (typeof confetti === 'function') {
                        confetti({ particleCount: 40, spread: 60 });
                    }
                }
            } else {
                document.getElementById('game-status').innerText = "❌ No coincide. Intenta otra función.";
            }
        }

        window.onload = function() {
            updateFlashcardUI();
            loadQuizQuestion();
            initGame();
        };
    </script>
</body>
</html>
