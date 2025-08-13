<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografía: Siempre Turista</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
        .chart-container {
            position: relative;
            width: 100%;
            max-width: 400px;
            margin-left: auto;
            margin-right: auto;
            height: 300px;
            max-height: 350px;
        }
        @media (min-width: 768px) {
            .chart-container {
                height: 350px;
            }
        }
    </style>
</head>
<body class="bg-[#233d00]">

    <!-- Palette: Earthy & Natural Invertida -->
    <!-- NEITHER Mermaid JS NOR SVG were used in this output. -->
    <!-- 
        Narrative Plan:
        1.  Hook/Intro: "Siempre Turista" title and tagline to grab attention.
        2.  Who We Are: A clear, concise mission statement.
        3.  Core Pillars: Visually represent the three main pillars (Culture, Gastronomy, Well-being) using cards.
        4.  How it Works: A step-by-step flowchart of the experience.
        5.  Value Proposition (What's Included): Use a list to show what the single payment covers, enhancing transparency and value perception.
        6.  Our Values: Reinforce the community's core principles.
        7.  Call to Action: A clear final message encouraging users to join.

        Visualization Choices:
        -   Pillars (Cultura, Gastronomía, Bienestar): Goal: Organize. Chosen Viz: Styled HTML Cards with Unicode icons. Justification: Clear, scannable, and visually separates the core concepts without needing complex charts. NO SVG.
        -   How it Works Flow: Goal: Organize. Chosen Viz: Flow Chart using structured HTML/CSS. Justification: Clearly shows a process sequentially. A better fit than a text list. NO SVG, NO MERMAID JS.
        -   What's Included: Goal: Inform/Organize. Chosen Viz: Styled HTML list. Justification: A direct and simple way to show what the payment covers, which is easier to digest than a chart for this specific data. NO SVG.
    -->

    <div class="container mx-auto p-4 md:p-8 max-w-4xl">

        <header class="text-center my-12">
            <h1 class="text-5xl md:text-6xl font-black text-[#ddaee4]">¡Siempre Turista!</h1>
            <p class="mt-4 text-xl md:text-2xl font-bold text-[#fff3c1]">Desbloquea el asombro de tu ciudad</p>
        </header>

        <main>
            <section id="quienes-somos" class="bg-[#447a00] rounded-lg shadow-lg p-6 md:p-8 mb-12 text-center">
                <h2 class="text-3xl font-bold text-[#ddaee4] mb-4">¿Quiénes Somos?</h2>
                <p class="text-lg text-[#ffeb9a] max-w-2xl mx-auto">
                    Somos una comunidad de mujeres que explora la cultura, gastronomía y bienestar de Santiago a través de rutas temáticas y accesibles, creando un espacio seguro para conectar y redescubrir la ciudad.
                </p>
            </section>

            <section id="pilares" class="mb-12">
                <h2 class="text-3xl font-bold text-center text-[#ddaee4] mb-8">Nuestros Plancitos se centran en 3 Pilares</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="bg-[#447a00] rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🏛️</div>
                        <h3 class="text-2xl font-bold text-[#fff3c1] mb-2">Cultura</h3>
                        <p class="text-[#ffeb9a]">Redescubre el patrimonio e historia de la Región Metropolitana.</p>
                    </div>
                    <div class="bg-[#447a00] rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🍲</div>
                        <h3 class="text-2xl font-bold text-[#fff3c1] mb-2">Gastronomía</h3>
                        <p class="text-[#ffeb9a]">Explora la gastronomía local y sus sabores únicos.</p>
                    </div>
                    <div class="bg-[#447a00] rounded-lg shadow-lg p-6 text-center transform hover:scale-105 transition-transform duration-300">
                        <div class="text-5xl mb-4">🧘‍♀️</div>
                        <h3 class="text-2xl font-bold text-[#fff3c1] mb-2">Bienestar</h3>
                        <p class="text-[#ffeb9a]">Conecta contigo y con otras mujeres en un espacio seguro.</p>
                    </div>
                </div>
            </section>

            <section id="como-funciona" class="bg-[#447a00] rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h2 class="text-3xl font-bold text-center text-[#ddaee4] mb-8">Tu Experiencia Paso a Paso</h2>
                <div class="flex flex-col md:flex-row justify-center items-center space-y-4 md:space-y-0 md:space-x-4">
                    <div class="flex items-center flex-col md:flex-row text-center md:text-left">
                        <div class="bg-[#ddaee4] text-[#233d00] rounded-full w-12 h-12 flex items-center justify-center text-2xl font-bold">1</div>
                        <div class="mt-2 md:mt-0 md:ml-4">
                            <h3 class="font-bold text-lg text-[#fff3c1]">Encuentro</h3>
                            <p class="text-[#ffeb9a]">Punto accesible en transporte público.</p>
                        </div>
                    </div>
                    <div class="text-2xl text-[#ddaee4] font-bold transform rotate-90 md:rotate-0">→</div>
                     <div class="flex items-center flex-col md:flex-row text-center md:text-left">
                        <div class="bg-[#ddaee4] text-[#233d00] rounded-full w-12 h-12 flex items-center justify-center text-2xl font-bold">2</div>
                        <div class="mt-2 md:mt-0 md:ml-4">
                            <h3 class="font-bold text-lg text-[#fff3c1]">Recorrido</h3>
                            <p class="text-[#ffeb9a]">Paseo a pie con historia y datos curiosos.</p>
                        </div>
                    </div>
                    <div class="text-2xl text-[#ddaee4] font-bold transform rotate-90 md:rotate-0">→</div>
                    <div class="flex items-center flex-col md:flex-row text-center md:text-left">
                        <div class="bg-[#ddaee4] text-[#233d00] rounded-full w-12 h-12 flex items-center justify-center text-2xl font-bold">3</div>
                        <div class="mt-2 md:mt-0 md:ml-4">
                            <h3 class="font-bold text-lg text-[#fff3c1]">Conexión</h3>
                            <p class="text-[#ffeb9a]">Espacio de conversación y anécdotas.</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="presupuesto" class="bg-[#447a00] rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h2 class="text-3xl font-bold text-center text-[#ddaee4] mb-4">¿Qué incluye tu Plancito?</h2>
                <p class="text-center text-[#ffeb9a] mb-8">El pago único de $14.990 asegura una experiencia completa y con todo lo necesario para disfrutar.</p>
                <div class="max-w-xl mx-auto">
                    <ul class="list-disc list-inside space-y-2 text-lg text-[#ffeb9a]">
                        <li><span class="font-bold text-[#ddaee4]">Guía profesional:</span> Acompañamiento durante todo el recorrido.</li>
                        <li><span class="font-bold text-[#ddaee4]">Recorrido temático:</span> Un paseo a pie por barrios con historia y datos curiosos.</li>
                        <li><span class="font-bold text-[#ddaee4]">Snack + Bebida:</span> Para reponer energías durante la actividad.</li>
                        <li><span class="font-bold text-[#ddaee4]">Recuerdo del plancito:</span> Un obsequio especial para llevarte a casa.</li>
                    </ul>
                </div>
            </section>

            <section id="valores" class="text-center mb-12">
                 <h2 class="text-3xl font-bold text-[#ddaee4] mb-8">Nuestros Valores</h2>
                 <div class="flex flex-wrap justify-center gap-4">
                    <span class="bg-[#ddaee4] text-[#233d00] font-bold py-2 px-4 rounded-full">Comunidad</span>
                    <span class="bg-[#ddaee4] text-[#233d00] font-bold py-2 px-4 rounded-full">Accesibilidad</span>
                    <span class="bg-[#ddaee4] text-[#233d00] font-bold py-2 px-4 rounded-full">Empoderamiento</span>
                    <span class="bg-[#ddaee4] text-[#233d00] font-bold py-2 px-4 rounded-full">Sostenibilidad</span>
                     <span class="bg-[#ddaee4] text-[#233d00] font-bold py-2 px-4 rounded-full">Autenticidad</span>
                 </div>
            </section>
        </main>

        <footer class="text-center my-12">
             <p class="text-2xl font-bold text-[#ddaee4]">¡Únete a nuestra comunidad y sé una turista en tu propia ciudad!</p>
        </footer>

    </div>
</body>
</html>
