<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protocolo 20% - Paulo Cruz Fit</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;700;800&display=swap" rel="stylesheet">
    <style>
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg {
            background: linear-gradient(135deg, #22c55e 0%, #16a34a 100%);
        }
        .animate-pulse-slow {
            animation: pulse 3s cubic-bezier(0.4, 0, 0.6, 1) infinite;
        }
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: .8; }
        }
        html {
            scroll-behavior: smooth;
        }
        .faq-item {
            border-bottom: 1px solid #e5e7eb;
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900 overflow-x-hidden">
    <div class="bg-red-600 text-white text-center py-2 text-sm font-bold px-4">
        PROMOÇÃO EXCLUSIVA: De R$ 97,00 por apenas R$ 27,00 - Vagas Limitadas!
    </div>
    <!-- Hero Section -->
    <header class="py-12 md:py-20 px-4 bg-white border-b">
        <div class="max-w-6xl mx-auto flex flex-col md:flex-row items-center gap-12">
            <div class="md:w-1/2 space-y-6 text-center md:text-left">
                <span class="inline-block px-4 py-1 bg-green-100 text-green-700 rounded-full font-bold text-sm tracking-wider uppercase">
                    Método Paulo Cruz Fit
                </span>
                <h1 class="text-4xl md:text-6xl font-extrabold leading-tight tracking-tight">
                    Elimine até <span class="text-green-600">20% do seu peso</span> em 30 dias!
                </h1>
                <p class="text-lg md:text-xl text-gray-600">
                    Descubra o protocolo exato para destravar seu metabolismo e queimar gordura de forma acelerada, sem dietas restritivas.
                </p>
                <div class="pt-4">
                    <!-- BOTÃO ALTERADO: Agora leva para a seção #checkout abaixo -->
                    <a href="#checkout" class="inline-block w-full md:w-auto text-center px-8 py-5 bg-green-500 hover:bg-green-600 text-white text-xl font-black rounded-xl shadow-2xl transform hover:scale-105 transition-all animate-pulse-slow">
                        QUERO PERDER PESO AGORA!
                    </a>
                </div>
                <div class="flex items-center justify-center md:justify-start gap-2 text-sm text-gray-500">
                    <span class="flex text-yellow-400">★★★★★</span>
                    <span>+2.450 alunos satisfeitos</span>
                </div>
            </div>
            <div class="md:w-1/2 relative">
                <div class="bg-green-200 rounded-3xl p-4 rotate-3 absolute inset-0 -z-10"></div>
                <div class="bg-white border-2 border-gray-100 rounded-2xl shadow-2xl p-6 relative">
                    <div class="aspect-[3/4] bg-gray-200 rounded-lg flex flex-col items-center justify-center overflow-hidden">
                        <div class="gradient-bg w-full h-full p-8 flex flex-col justify-between text-white text-center">
                            <div>
                                <p class="text-xs font-bold tracking-widest mb-2">PAULO CRUZ FIT APRESENTA</p>
                                <h2 class="text-3xl font-black">PROTOCOLO 20% EM 30 DIAS</h2>
                            </div>
                            <div class="bg-white/20 backdrop-blur-sm rounded-lg p-4">
                                <p class="font-bold text-sm uppercase italic">O fim do efeito sanfona</p>
                            </div>
                            <div class="border-t border-white/30 pt-4">
                                <p class="text-xs">GUIA DIGITAL COMPLETO</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </header>
    <!-- Seção de Prova Social -->
    <section class="py-16 bg-gray-100 px-4">
        <div class="max-w-5xl mx-auto">
            <h2 class="text-center text-3xl font-bold mb-12 uppercase">Resultados Reais:</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-2xl shadow-md">
                    <p class="text-gray-600 italic mb-4">"Perdi 12kg no primeiro mês. O guia do Paulo é direto ao ponto e muito fácil de seguir!"</p>
                    <p class="font-bold text-green-600 text-sm">Amanda S. - São Paulo</p>
                </div>
                <div class="bg-white p-6 rounded-2xl shadow-md border-b-4 border-green-500">
                    <p class="text-gray-600 italic mb-4">"Nunca imaginei que por R$ 27 eu teria acesso a um conteúdo tão valioso. Mudou meu corpo!"</p>
                    <p class="font-bold text-green-600 text-sm">João P. - Curitiba</p>
                </div>
                <div class="bg-white p-6 rounded-2xl shadow-md">
                    <p class="text-gray-600 italic mb-4">"As receitas são deliciosas e eu não passo fome. Já se foram 8kg e sinto muito mais energia."</p>
                    <p class="font-bold text-green-600 text-sm">Beatriz M. - BH</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Oferta Principal -->
    <section id="checkout" class="py-20 px-4 bg-gray-50 border-t">
        <div class="max-w-xl mx-auto text-center">
            <h2 class="text-4xl font-black mb-8 uppercase">Acesso Imediato ao Método</h2>
            <div class="bg-white border-2 border-green-500 p-8 rounded-3xl shadow-2xl relative">
                <div class="absolute -top-4 left-1/2 -translate-x-1/2 bg-green-500 text-white px-6 py-1 rounded-full text-sm font-bold uppercase">
                    Oferta de Lançamento
                </div>
                <p class="text-gray-400 line-through text-xl">De R$ 97,00</p>
                <div class="flex flex-col mb-6">
                    <span class="text-sm font-bold text-gray-600">Por apenas</span>
                    <span class="text-7xl font-black text-green-600">R$ 27,00</span>
                    <span class="text-gray-500">Pagamento Único</span>
                </div>
                <div class="space-y-4 mb-8 text-left max-w-xs mx-auto">
                    <div class="flex items-center gap-3">
                        <span class="text-green-500 text-xl font-bold">✓</span>
                        <span>E-book Protocolo 20%</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-green-500 text-xl font-bold">✓</span>
                        <span>Lista de Compras Inteligente</span>
                    </div>
                    <div class="flex items-center gap-3">
                        <span class="text-green-500 text-xl font-bold">✓</span>
                        <span>Guia de Chás Emagrecedores</span>
                    </div>
                </div>
                <a href="https://pay.kirvano.com/710de087-46ca-46ed-9048-22329314487c?aff=1bf3f840-a5a4-499c-a541-0a2c1a4a3071" target="_blank" class="block w-full py-5 bg-green-500 hover:bg-green-600 text-white text-2xl font-black rounded-xl shadow-lg transition-all transform hover:scale-105 uppercase mb-6">
                    Quero Garantir Meu Guia!
                </a>
                <div class="flex flex-wrap justify-center gap-4 opacity-60 grayscale hover:grayscale-0 transition-all">
                    <img src="https://img.icons8.com/color/48/000000/visa.png" alt="Visa" class="h-6">
                    <img src="https://img.icons8.com/color/48/000000/mastercard.png" alt="Mastercard" class="h-6">
                    <img src="https://img.icons8.com/color/48/000000/pix.png" alt="Pix" class="h-6">
                </div>
            </div>
        </div>
    </section>
    <!-- Seção FAQ (Perguntas Frequentes) -->
    <section class="py-16 bg-white px-4">
        <div class="max-w-3xl mx-auto">
            <h2 class="text-3xl font-black text-center mb-10 uppercase tracking-tight">Dúvidas Frequentes</h2>
            <div class="space-y-6">
                <div class="faq-item pb-4">
                    <h3 class="font-bold text-lg text-green-700 mb-2">Como vou receber o acesso ao guia?</h3>
                    <p class="text-gray-600">Logo após a confirmação do pagamento, você receberá um e-mail com o link para baixar o E-book e todos os bônus no seu computador ou celular.</p>
                </div>
                <div class="faq-item pb-4">
                    <h3 class="font-bold text-lg text-green-700 mb-2">Preciso pagar mensalidade?</h3>
                    <p class="text-gray-600">Não! O pagamento de R$ 27,00 é único. Você paga uma vez e tem acesso vitalício ao material.</p>
                </div>
                <div class="faq-item pb-4">
                    <h3 class="font-bold text-lg text-green-700 mb-2">Em quanto tempo vejo resultados?</h3>
                    <p class="text-gray-600">Muitos alunos relatam desinflamação e perda de peso já na primeira semana, seguindo o protocolo de ativação metabólica corretamente.</p>
                </div>
                <div class="faq-item pb-4">
                    <h3 class="font-bold text-lg text-green-700 mb-2">O pagamento é seguro?</h3>
                    <p class="text-gray-600">Sim! Utilizamos a plataforma Kirvano, uma das maiores e mais seguras do Brasil. Seus dados estão 100% protegidos.</p>
                </div>
            </div>
        </div>
    </section>
    <!-- Contato -->
    <section class="py-12 bg-gray-50 px-4 border-t">
        <div class="max-w-4xl mx-auto text-center space-y-8">
            <div class="pt-6">
                <h4 class="text-lg font-bold mb-4 uppercase tracking-widest text-gray-500">Ainda tem dúvidas? Fale com o suporte:</h4>
                <div class="flex flex-col md:flex-row justify-center items-center gap-6">
                    <a href="mailto:jornadadoemagrecimento@paulocruzfit.com.br" class="flex items-center gap-2 text-gray-700 hover:text-green-600 transition-colors">
                        <svg class="w-5 h-5" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"></path></svg>
                        jornadadoemagrecimento@paulocruzfit.com.br
                    </a>
                    <a href="https://wa.me/5511959741331" class="flex items-center gap-2 text-gray-700 hover:text-green-600 transition-colors">
                        <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24"><path d="M12.031 6.172c-3.181 0-5.767 2.586-5.768 5.766-.001 1.298.38 2.27 1.025 3.12l-.694 2.54 2.595-.68c.843.54 1.703.831 2.842.831 3.181 0 5.767-2.586 5.768-5.766 0-3.18-2.587-5.766-5.768-5.766zM12.031 16.172c-1.025 0-1.78-.266-2.522-.72l-.181-.109-1.545.405.412-1.505-.12-.19c-.51-.81-.774-1.614-.774-2.487 0-2.44 1.985-4.425 4.425-4.425 2.441 0 4.426 1.985 4.426 4.425 0 2.44-1.985 4.425-4.426 4.425z"/></svg>
                        (11) 95974-1331
                    </a>
                </div>
            </div>
        </div>
    </section>
    <footer class="py-10 bg-white border-t text-center text-gray-400 text-[10px] px-4">
        <p class="mb-4">© 2024 Paulo Cruz Fit - Jornada do Emagrecimento</p>
        <p class="max-w-2xl mx-auto uppercase leading-relaxed">
            Este site não faz parte do Google ou do Facebook. Além disso, este site NÃO é endossado pelo Google ou Facebook de qualquer maneira. Facebook e Google são marcas comerciais de suas respectivas empresas.
        </p>
    </footer>

</body>
</html>
