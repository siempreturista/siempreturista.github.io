<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Infografía: Siempre Turista</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;900&display=swap" rel="stylesheet">
    <!-- Chosen Palette: Earthy & Natural Inverted -->
    <!-- Application Structure Plan: The SPA follows a clear narrative flow designed for a potential customer browsing a link-in-bio page. It starts with a strong hook (Title), explains the concept (Who We Are), details the offerings (Pillars), shows the process (How it Works), clarifies the value (What's Included), reinforces the brand's ethos (Values), and ends with a clear Call to Action. This structure is designed to be scannable, mobile-first, and to quickly convert interest into action by answering key questions in a logical sequence. -->
    <!-- Visualization & Content Choices: 
        - Pillars (Cultura, Gastronomía, Bienestar): Goal: Organize. Viz: Styled HTML cards with Unicode icons. Justification: Visually separates core concepts for easy scanning. Method: HTML/Tailwind. CONFIRMATION: NO SVG.
        - Process Flow (How it Works): Goal: Organize. Viz: A step-by-step visual flow. Justification: More engaging and clearer than a text list for showing a sequence. Method: HTML/Tailwind Flexbox. CONFIRMATION: NO SVG/Mermaid.
        - Value Proposition (What's Included): Goal: Inform. Viz: A styled list. Justification: Directly answers a key user question with clarity, based on user feedback to move away from charts. Method: HTML/Tailwind. CONFIRMATION: NO SVG.
        - Values: Goal: Organize. Viz: Styled tags/pills. Justification: Modern, scannable presentation for keywords. Method: HTML/Tailwind. CONFIRMATION: NO SVG.
    -->
    <!-- CONFIRMATION: NO SVG graphics used. NO Mermaid JS used. -->
    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #233d00;
            color: #ffeb9a;
        }
        .card {
            background-color: #447a00;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(221, 174, 228, 0.1), 0 4px 6px -2px rgba(221, 174, 228, 0.05);
        }
        .accent-text {
            color: #ddaee4;
        }
        .highlight-text {
            color: #fff3c1;
        }
        .step-bubble {
            background-color: #ddaee4;
            color: #233d00;
        }
        .value-tag {
             background-color: #ddaee4;
             color: #233d00;
        }
    </style>
</head>
<body>

    <div class="container mx-auto p-4 md:p-8 max-w-4xl">


        <main>
            <section id="quienes-somos" class="card rounded-lg shadow-lg p-6 md:p-8 mb-12 text-center">
                <h2 class="text-3xl font-bold accent-text mb-4">¿Quiénes Somos?</h2>
                <p class="text-lg max-w-2xl mx-auto">
                    Somos una comunidad de mujeres que explora la cultura, gastronomía y bienestar de Santiago a través de rutas temáticas y accesibles.
                </p>
            </section>

            <section id="pilares" class="mb-12">
                <h2 class="text-3xl font-bold text-center accent-text mb-8">Nuestros Plancitos se centran en 3 Pilares</h2>
                <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                    <div class="card rounded-lg shadow-lg p-6 text-center">
                        <div class="text-5xl mb-4">🏛️</div>
                        <h3 class="text-2xl font-bold highlight-text mb-2">Cultura</h3>
                        <p>Redescubre el patrimonio e historia de la Región Metropolitana.</p>
                    </div>
                    <div class="card rounded-lg shadow-lg p-6 text-center">
                        <div class="text-5xl mb-4">🍲</div>
                        <h3 class="text-2xl font-bold highlight-text mb-2">Gastronomía</h3>
                        <p>Explora la gastronomía local y sus sabores.</p>
                    </div>
                    <div class="card rounded-lg shadow-lg p-6 text-center">
                        <div class="text-5xl mb-4">🧘‍♀️</div>
                        <h3 class="text-2xl font-bold highlight-text mb-2">Bienestar</h3>
                        <p>Conecta contigo y con otras mujeres en un espacio seguro.</p>
                    </div>
                </div>
            </section>

            <section id="como-funciona" class="card rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h2 class="text-3xl font-bold text-center accent-text mb-8">Tu Experiencia Paso a Paso</h2>
                <div class="flex flex-col md:flex-row justify-center items-center space-y-4 md:space-y-0 md:space-x-4">
                    <div class="flex items-center flex-col md:flex-row text-center md:text-left">
                        <div class="step-bubble rounded-full w-12 h-12 flex items-center justify-center text-2xl font-bold">1</div>
                        <div class="mt-2 md:mt-0 md:ml-4">
                            <h3 class="font-bold text-lg highlight-text">Encuentro</h3>
                            <p>Nos reunimos en un punto accesible en transporte público.</p>
                        </div>
                    </div>
                    <div class="text-2xl accent-text font-bold transform rotate-90 md:rotate-0">→</div>
                     <div class="flex items-center flex-col md:flex-row text-center md:text-left">
                        <div class="step-bubble rounded-full w-12 h-12 flex items-center justify-center text-2xl font-bold">2</div>
                        <div class="mt-2 md:mt-0 md:ml-4">
                            <h3 class="font-bold text-lg highlight-text">Recorrido</h3>
                            <p>Un paseo a pie por barrios llenos de historia y datos curiosos.</p>
                        </div>
                    </div>
                    <div class="text-2xl accent-text font-bold transform rotate-90 md:rotate-0">→</div>
                    <div class="flex items-center flex-col md:flex-row text-center md:text-left">
                        <div class="step-bubble rounded-full w-12 h-12 flex items-center justify-center text-2xl font-bold">3</div>
                        <div class="mt-2 md:mt-0 md:ml-4">
                            <h3 class="font-bold text-lg highlight-text">Conexión</h3>
                            <p>Terminamos con un espacio de conversación y anécdotas.</p>
                        </div>
                    </div>
                </div>
            </section>
            
            <section id="incluye" class="card rounded-lg shadow-lg p-6 md:p-8 mb-12">
                <h2 class="text-3xl font-bold text-center accent-text mb-4">¿Qué incluye tu Plancito?</h2>
                <p class="text-center mb-8">El pago único asegura una experiencia completa y con todo lo necesario para disfrutar.</p>
                <div class="max-w-xl mx-auto">
                    <ul class="list-none space-y-3">
                        <li class="flex items-start"><span class="accent-text text-xl mr-3">✔</span> <span><span class="font-bold highlight-text">Guía y Recorrido:</span> Acompañamiento profesional en un paseo temático.</span></li>
                        <li class="flex items-start"><span class="accent-text text-xl mr-3">✔</span> <span><span class="font-bold highlight-text">Snack + Bebida:</span> Para reponer energías durante la actividad.</span></li>
                        <li class="flex items-start"><span class="accent-text text-xl mr-3">✔</span> <span><span class="font-bold highlight-text">Recuerdo del Plancito:</span> Un obsequio especial para llevarte a casa.</span></li>
                    </ul>
                </div>
            </section>

            <section id="valores" class="text-center mb-12">
                 <h2 class="text-3xl font-bold accent-text mb-8">Nuestros Valores</h2>
                 <div class="flex flex-wrap justify-center gap-4">
                    <span class="value-tag font-bold py-2 px-4 rounded-full">Comunidad</span>
                    <span class="value-tag font-bold py-2 px-4 rounded-full">Accesibilidad</span>
                    <span class="value-tag font-bold py-2 px-4 rounded-full">Empoderamiento</span>
                 </div>
            </section>
        </main>

        <footer class="text-center my-12">
             <p class="text-2xl font-bold accent-text">¡Únete a nuestra comunidad y sé una turista en tu propia ciudad!</p>
        </footer>

    </div>
</body>
</html>
```
