<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Letícia 💜 Eu Te Amo</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@400;600;700&family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    <style>
        * { scroll-behavior: smooth; }
        body { font-family: 'Inter', sans-serif; background: #0F051F; color: white; }
        .font-cursive { font-family: 'Dancing Script', cursive; }
        .gradient-bg { background: linear-gradient(135deg, #1A0B2E 0%, #2D1B4E 50%, #4A2078 100%); }
        .card-glass { background: rgba(139,92,246,0.1); backdrop-filter: blur(12px); border: 1px solid rgba(167,139,250,0.2); border-radius: 16px; transition: all 0.3s ease; }
        .card-glass:hover { background: rgba(139,92,246,0.15); transform: translateY(-4px); box-shadow: 0 10px 30px rgba(139,92,246,0.15); }
        .btn-love { background: linear-gradient(90deg, #EC4899 0%, #A855F7 100%); border-radius: 999px; padding: 12px 32px; font-weight: 600; transition: all 0.3s ease; display: inline-block; }
        .btn-love:hover { transform: scale(1.05); box-shadow: 0 0 20px rgba(236,72,153,0.4); }
        .btn-outline { border: 1px solid #EC4899; background: transparent; }
        .text-gradient { background: linear-gradient(90deg, #F9A8D4 0%, #C4B5FD 100%); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
        .fade-in { opacity: 0; transform: translateY(20px); animation: fadeIn 1s ease forwards; }
        @keyframes fadeIn { to { opacity: 1; transform: translateY(0); } }
        .nav-link { position: relative; }
        .nav-link::after { content: ''; position: absolute; bottom: -4px; left: 0; width: 0; height: 2px; background: linear-gradient(90deg, #EC4899, #A855F7); transition: width 0.3s ease; }
        .nav-link:hover::after { width: 100%; }
    </style>
</head>
<body class="gradient-bg min-h-screen">

    <nav class="px-6 md:px-12 py-5 flex justify-between items-center sticky top-0 bg-black/30 backdrop-blur-md z-50">
        <a href="#inicio" class="text-2xl font-bold flex items-center gap-2">
            <span class="text-pink-400">♥</span> Letícia
        </a>
        <div class="hidden md:flex gap-8 text-sm font-medium text-purple-200">
            <a href="#inicio" class="nav-link hover:text-white transition">Início</a>
            <a href="#sobre" class="nav-link hover:text-white transition">Sobre Nós</a>
            <a href="#fotos" class="nav-link hover:text-white transition">Nossas Fotos</a>
            <a href="#planos" class="nav-link hover:text-white transition">Planos</a>
            <a href="#carta" class="nav-link hover:text-white transition">Carta de Amor</a>
        </div>
        <a href="#final" class="btn-love text-sm hidden md:block">Eu te amo ♥</a>
        <button class="md:hidden text-2xl">☰</button>
    </nav>

    <section id="inicio" class="relative min-h-[90vh] flex items-center px-6 md:px-12 overflow-hidden">
        <div class="absolute inset-0 bg-black/50 z-0"></div>
        <div class="absolute inset-0 z-[-1]">
            <img src="https://i.imgur.com/K6ZxQ8H.jpg" alt="Fundo" class="w-full h-full object-cover opacity-40">
        </div>
        <div class="relative z-10 max-w-2xl fade-in">
            <p class="text-purple-200 text-sm uppercase tracking-widest mb-4">O meu lugar favorito é ao seu lado</p>
            <h1 class="text-5xl md:text-7xl font-bold mb-4">
                Você é tudo<br>
                <span class="font-cursive text-5xl md:text-7xl text-gradient">pra mim ♥</span>
            </h1>
            <p class="text-purple-100 text-lg mb-8 max-w-lg">
                Cada dia com você é um motivo a mais para eu querer ser uma versão melhor de mim. Eu te amo, hoje e sempre.
            </p>
            <a href="#fotos" class="btn-love inline-flex items-center gap-2 mr-4 mb-4">
                Ver Nossas Fotos <i class="fa fa-camera"></i>
            </a>
            <a href="#carta" class="btn-love btn-outline inline-flex items-center gap-2">
                Ler Carta <i class="fa fa-heart"></i>
            </a>
        </div>
    </section>

    <section id="sobre" class="px-6 md:px-12 py-20">
        <div class="max-w-3xl mx-auto text-center fade-in">
            <h2 class="font-cursive text-4xl text-pink-300 mb-6">Sobre Nós 💜</h2>
            <p class="text-lg text-purple-100 leading-relaxed mb-4">
                Você chegou e transformou minha vida em algo mais colorido, mais leve e cheio de amor. Cada sorriso seu é o meu momento favorito.
            </p>
            <p class="text-lg text-purple-100 leading-relaxed">
                E o melhor de tudo: isso é só o começo. 💖
            </p>
        </div>
    </section>

    <section id="fotos" class="px-6 md:px-12 py-20">
        <div class="max-w-6xl mx-auto">
            <h2 class="font-cursive text-4xl text-center text-pink-300 mb-10">Nossos Momentos 📸</h2>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-6">
                <div class="card-glass p-3 fade-in">
                    <img src="https://i.imgur.com/9wP7dL9.jpg" alt="Nós" class="w-full h-80 object-cover rounded-xl">
                </div>
                <div class="card-glass p-3 fade-in" style="animation-delay:0.2s">
                    <img src="https://i.imgur.com/K6ZxQ8H.jpg" alt="Nós" class="w-full h-80 object-cover rounded-xl">
                </div>
                <div class="card-glass p-3 fade-in" style="animation-delay:0.3s">
                    <img src="https://i.imgur.com/sBnqR3Y.jpg" alt="Nós" class="w-full h-80 object-cover rounded-xl">
                </div>
                <div class="card-glass p-3 fade-in" style="animation-delay:0.4s">
                    <img src="https://i.imgur.com/9t5gFzM.jpg" alt="Nós" class="w-full h-80 object-cover rounded-xl">
                </div>
            </div>
            <div class="text-center mt-10">
                <a href="#carta" class="btn-love inline-flex items-center gap-2">
                    Ler Nossa Carta <i class="fa fa-arrow-down"></i>
                </a>
            </div>
        </div>
    </section>

    <section id="planos" class="px-6 md:px-12 py-20 bg-black/20">
        <div class="max-w-4xl mx-auto">
            <h2 class="font-cursive text-4xl text-center text-pink-300 mb-10">Nossos Planos ✨</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-6">
                <div class="card-glass p-6 text-center fade-in">
                    <p class="text-3xl mb-3">🌟</p>
                    <h3 class="font-semibold mb-2">Sonhos</h3>
                    <p class="text-purple-200 text-sm">Realizar tudo de mãos dadas.</p>
                </div>
                <div class="card-glass p-6 text-center fade-in" style="animation-delay:0.2s">
                    <p class="text-3xl mb-3">✈️</p>
                    <h3 class="font-semibold mb-2">Viagens</h3>
                    <p class="text-purple-200 text-sm">Criar memórias pelo mundo.</p>
                </div>
                <div class="card-glass p-6 text-center fade-in" style="animation-delay:0.4s">
                    <p class="text-3xl mb-3">💜</p>
                    <h3 class="font-semibold mb-2">Para Sempre</h3>
                    <p class="text-purple-200 text-sm">Uma vida inteira juntos.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="carta" class="px-6 md:px-12 py-20">
        <div class="max-w-2xl mx-auto">
            <h2 class="font-cursive text-4xl text-center text-pink-300 mb-10">Minha Carta 💌</h2>
            <div class="card-glass p-8 md:p-10 fade-in">
                <p class="text-lg leading-relaxed text-purple-50 mb-4">Minha amada Letícia,</p>
                <p class="text-lg leading-relaxed text-purple-50 mb-4">
                    Você é a pessoa mais especial da minha vida. Cada momento ao seu lado é um presente que eu valorizo mais a cada dia.
                </p>
                <p class="text-lg leading-relaxed text-purple-50 mb-4">
                    Obrigado por ser você, por existir e por escolher estar comigo. Quero te amar e te cuidar todos os dias.
                </p>
                <p class="text-center font-cursive text-2xl text-pink-300 mt-8">
                    Eu te amo infinitamente, Letícia 💜💕
                </p>
            </div>
        </div>
    </section>

    <section id="final" class="px-6 md:px-12 py-20 bg-black/20">
        <div class="max-w-xl mx-auto text-center fade-in">
            <p class="text-4xl text-pink-400 mb-4">♥</p>
            <h2 class="font-cursive text-4xl text-pink-300 mb-4">Você é o amor da minha vida</h2>
            <p class="text-purple-100 text-lg mb-8">Para sempre e para sempre. 💜</p>
            <a href="#inicio" class="btn-love inline-flex items-center gap-2">
                Voltar ao Início <i class="fa fa-heart"></i>
            </a>
        </div>
    </section>

    <footer class="text-center py-6 text-purple-300 text-sm">
        Feito com todo o amor do mundo 💜 | Para sempre seu
    </footer>

</body>
</html>
