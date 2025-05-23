<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GEMARK - Registro e Proteção de Marcas</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            font-family: 'Inter', sans-serif;
            scroll-behavior: smooth; /* Adicionado para rolagem suave global */
        }
        .hero-bg {
            /* Imagem de fundo da seção de introdução atualizada */
            background-image: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://i.postimg.cc/mkDTspPs/cyber-security-concept-digital-art.jpg');
            background-size: cover;
            background-position: center;
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 15px -3px rgba(0,0,0,0.1), 0 4px 6px -2px rgba(0,0,0,0.05);
        }
        .floating-whatsapp {
            position: fixed;
            bottom: 20px;
            right: 20px;
            background-color: #25D366;
            color: white;
            padding: 15px;
            border-radius: 50%;
            box-shadow: 0 4px 8px rgba(0,0,0,0.2);
            z-index: 1000;
            transition: transform 0.3s ease;
        }
        .floating-whatsapp:hover {
            transform: scale(1.1);
        }
        /* Adiciona um fallback para a imagem do logo caso ela não carregue */
        .logo-img {
            content: url('https://i.postimg.cc/nLg47Ntd/OFICIAL.png');
        }
        .logo-img[onerror] {
            content: url('https://placehold.co/120x40/000000/FFFFFF?text=GEMARK'); /* Placeholder em caso de erro */
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">

    <header class="bg-[#000000] shadow-md sticky top-0 z-50">
        <div class="container mx-auto px-6 py-4 flex justify-between items-center">
            <img src="https://i.postimg.cc/nLg47Ntd/OFICIAL.png" alt="Logotipo GEMARK" class="h-10 logo-img" onerror="this.onerror=null; this.src='https://placehold.co/120x40/000000/FFFFFF?text=GEMARK';">
            <nav class="hidden md:flex space-x-6 items-center">
                <a href="#inicio" class="text-white hover:text-yellow-500 transition duration-300">Início</a>
                <a href="#servicos" class="text-white hover:text-yellow-500 transition duration-300">Serviços</a>
                <a href="#como-funciona" class="text-white hover:text-yellow-500 transition duration-300">Como Funciona</a>
                <a href="#contato" class="text-white hover:text-yellow-500 transition duration-300">Contato</a>
                <a href="https://wa.me/553799625652" target="_blank" class="bg-[#ffffff] hover:bg-gray-200 text-[#000000] font-semibold px-4 py-2 rounded-lg transition duration-300">Fale com um Especialista</a>
            </nav>
            <div class="md:hidden">
                <button id="mobile-menu-button" class="text-white focus:outline-none">
                    <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16m-7 6h7"></path></svg>
                </button>
            </div>
        </div>
        <div id="mobile-menu" class="md:hidden hidden bg-[#000000] shadow-lg">
            <a href="#inicio" class="block px-6 py-3 text-white hover:bg-yellow-500 hover:text-black transition duration-300">Início</a>
            <a href="#servicos" class="block px-6 py-3 text-white hover:bg-yellow-500 hover:text-black transition duration-300">Serviços</a>
            <a href="#como-funciona" class="block px-6 py-3 text-white hover:bg-yellow-500 hover:text-black transition duration-300">Como Funciona</a>
            <a href="#contato" class="block px-6 py-3 text-white hover:bg-yellow-500 hover:text-black transition duration-300">Contato</a>
            <a href="https://wa.me/553799625652" target="_blank" class="block px-6 py-3 bg-[#ffffff] text-[#000000] text-center font-semibold rounded-b-lg hover:bg-gray-200 transition duration-300">Fale com um Especialista</a>
        </div>
    </header>

    <section id="inicio" class="hero-bg text-white py-20 md:py-32">
        <div class="container mx-auto px-6 text-center">
            <h1 class="text-4xl md:text-6xl font-bold mb-6 leading-tight">GEMARK: Nosso Negócio é PROTEGER O SEU</h1>
            <p class="text-lg md:text-xl mb-8 max-w-2xl mx-auto">Especialistas em registro e proteção de marcas, garantindo a exclusividade e o valor do seu negócio em todo o Brasil.</p>
            <a href="https://wa.me/553799625652" target="_blank" class="bg-[#03268f] hover:bg-blue-800 text-white font-semibold px-8 py-3 rounded-lg text-lg transition duration-300">Quero registrar minha marca</a>
        </div>
    </section>

    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-2 text-gray-700">Por que Registrar sua Marca?</h2>
            <p class="text-center text-gray-600 mb-12 max-w-xl mx-auto">Garanta a segurança e a exclusividade do seu maior patrimônio.</p>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="bg-[#000000] p-6 rounded-lg shadow-lg text-center text-white">
                    <i class="fas fa-shield-alt fa-3x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Exclusividade Nacional</h3>
                    <p>Sua marca protegida em todo o território brasileiro, impedindo o uso por terceiros.</p>
                </div>
                <div class="bg-[#000000] p-6 rounded-lg shadow-lg text-center text-white">
                    <i class="fas fa-lock fa-3x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Proteção Contra Cópia</h3>
                    <p>Segurança jurídica para combater a concorrência desleal e o uso indevido.</p>
                </div>
                <div class="bg-[#000000] p-6 rounded-lg shadow-lg text-center text-white">
                    <i class="fas fa-arrow-trend-up fa-3x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Agrega Valor ao Negócio</h3>
                    <p>Uma marca registrada é um ativo valioso que pode ser licenciado ou franqueado.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="servicos" class="py-16 bg-[#000000]">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-2 text-white">Nossos Serviços Especializados</h2>
            <p class="text-center text-gray-300 mb-12 max-w-xl mx-auto">Soluções completas para a proteção da sua identidade no mercado.</p>
            <div class="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-white p-6 rounded-lg shadow-lg service-card transition duration-300 text-gray-700">
                    <i class="fas fa-file-signature fa-2x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Registro de Marca</h3>
                    <p class="mb-4">Análise de viabilidade, preparação e depósito do pedido de registro no INPI.</p>
                    <a href="https://wa.me/553799625652" target="_blank" class="text-yellow-500 hover:text-yellow-600 font-semibold">Saiba Mais <i class="fas fa-arrow-right ml-1"></i></a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg service-card transition duration-300 text-gray-700">
                    <i class="fas fa-search fa-2x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Acompanhamento de Processos</h3>
                    <p class="mb-4">Monitoramento semanal do seu processo no INPI e comunicação de todas as etapas.</p>
                    <a href="https://wa.me/553799625652" target="_blank" class="text-yellow-500 hover:text-yellow-600 font-semibold">Saiba Mais <i class="fas fa-arrow-right ml-1"></i></a>
                </div>
                <div class="bg-white p-6 rounded-lg shadow-lg service-card transition duration-300 text-gray-700">
                    <i class="fas fa-gavel fa-2x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Notificações e Defesas</h3>
                    <p class="mb-4">Elaboração de oposições, manifestações, recursos e notificações extrajudiciais.</p>
                    <a href="https://wa.me/553799625652" target="_blank" class="text-yellow-500 hover:text-yellow-600 font-semibold">Saiba Mais <i class="fas fa-arrow-right ml-1"></i></a>
                </div>
                 <div class="bg-white p-6 rounded-lg shadow-lg service-card transition duration-300 md:col-span-2 lg:col-span-1 text-gray-700 lg:col-start-2"> <i class="fas fa-lightbulb fa-2x text-yellow-500 mb-4"></i>
                    <h3 class="text-xl font-semibold mb-2">Consultoria Estratégica</h3>
                    <p class="mb-4">Orientação completa sobre a melhor forma de proteger seus ativos intelectuais.</p>
                    <a href="https://wa.me/553799625652" target="_blank" class="text-yellow-500 hover:text-yellow-600 font-semibold">Saiba Mais <i class="fas fa-arrow-right ml-1"></i></a>
                </div>
            </div>
        </div>
    </section>

    <section id="como-funciona" class="py-16 bg-[#03268f] text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Como Funciona o Registro da Sua Marca?</h2>
            <div class="grid md:grid-cols-4 gap-8 text-center">
                <div>
                    <div class="bg-white text-[#03268f] rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">1</div>
                    <h3 class="text-xl font-semibold mb-2">Consulta de Viabilidade</h3>
                    <p>Analisamos gratuitamente se sua marca pode ser registrada.</p>
                </div>
                <div>
                    <div class="bg-white text-[#03268f] rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">2</div>
                    <h3 class="text-xl font-semibold mb-2">Depósito do Pedido</h3>
                    <p>Preparamos e protocolamos seu pedido junto ao INPI.</p>
                </div>
                <div>
                    <div class="bg-white text-[#03268f] rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">3</div>
                    <h3 class="text-xl font-semibold mb-2">Acompanhamento Semanal</h3>
                    <p>Monitoramos seu processo e informamos cada atualização.</p>
                </div>
                <div>
                    <div class="bg-white text-[#03268f] rounded-full w-16 h-16 flex items-center justify-center mx-auto mb-4 text-2xl font-bold">4</div>
                    <h3 class="text-xl font-semibold mb-2">Marca Registrada!</h3>
                    <p>Com o deferimento, sua marca está protegida por 10 anos.</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contato" class="py-16 bg-gray-700 text-white">
        <div class="container mx-auto px-6">
            <h2 class="text-3xl font-bold text-center mb-12">Entre em Contato</h2>
            <div class="max-w-3xl mx-auto bg-white text-gray-700 p-8 rounded-lg shadow-xl">
                <!-- O atributo action="#" e method="POST" são placeholders.
                     Para funcionalidade real, um endpoint de backend ou serviço de email é necessário. -->
                <form action="#" method="POST" id="contactForm">
                    <div class="grid md:grid-cols-2 gap-6 mb-6">
                        <div>
                            <label for="nome" class="block mb-2 font-semibold">Nome Completo</label>
                            <input type="text" id="nome" name="nome" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent" required>
                        </div>
                        <div>
                            <label for="email" class="block mb-2 font-semibold">E-mail</label>
                            <input type="email" id="email" name="email" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent" required>
                        </div>
                    </div>
                    <div class="mb-6">
                        <label for="telefone" class="block mb-2 font-semibold">Telefone (com DDD)</label>
                        <input type="tel" id="telefone" name="telefone" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent" required>
                    </div>
                    <div class="mb-6">
                        <label for="assunto" class="block mb-2 font-semibold">Assunto</label>
                        <input type="text" id="assunto" name="assunto" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent">
                    </div>
                    <div class="mb-6">
                        <label for="mensagem" class="block mb-2 font-semibold">Sua Mensagem</label>
                        <textarea id="mensagem" name="mensagem" rows="5" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-yellow-500 focus:border-transparent" required></textarea>
                    </div>
                    <div class="text-center">
                        <button type="submit" class="bg-yellow-500 hover:bg-yellow-600 text-white font-semibold px-8 py-3 rounded-lg text-lg transition duration-300">Enviar Mensagem</button>
                    </div>
                </form>
                <div id="form-feedback" class="mt-4 text-center"></div>
            </div>
             <div class="text-center mt-12">
                <p class="text-lg mb-2">Ou fale conosco diretamente:</p>
                <p class="text-xl font-semibold mb-1"><i class="fas fa-phone mr-2"></i> (37) 99962-5652</p>
                <p class="text-xl font-semibold"><i class="fas fa-envelope mr-2"></i> registrodemarcasgemark@gmail.com</p>
            </div>
        </div>
    </section>

    <footer class="bg-gray-800 text-gray-300 py-12">
        <div class="container mx-auto px-6 text-center">
            <img src="https://i.postimg.cc/nLg47Ntd/OFICIAL.png" alt="Logotipo GEMARK" class="h-10 mx-auto mb-6 logo-img" onerror="this.onerror=null; this.src='https://placehold.co/120x40/FFFFFF/000000?text=GEMARK';">
            <p class="mb-2">GEMARK - Registro e Proteção de Marcas</p>
            <p class="mb-2">Rua Exemplo, 123 - Cidade, Estado - CEP 00000-000</p> <p class="mb-6">CNPJ: XX.XXX.XXX/0001-XX</p> <div class="flex justify-center space-x-6 mb-6">
                <a href="#" class="text-gray-400 hover:text-yellow-500 transition duration-300" aria-label="Facebook"><i class="fab fa-facebook-f fa-lg"></i></a>
                <a href="#" class="text-gray-400 hover:text-yellow-500 transition duration-300" aria-label="Instagram"><i class="fab fa-instagram fa-lg"></i></a>
                <a href="#" class="text-gray-400 hover:text-yellow-500 transition duration-300" aria-label="LinkedIn"><i class="fab fa-linkedin-in fa-lg"></i></a>
            </div>
            <p class="text-sm">&copy; <span id="currentYear"></span> GEMARK. Todos os direitos reservados.</p>
            <p class="text-xs mt-1">Desenvolvido com <i class="fas fa-heart text-yellow-500"></i></p>
        </div>
    </footer>

    <a href="https://wa.me/553799625652?text=Olá!%20Gostaria%20de%20mais%20informações%20sobre%20o%20registro%20de%20marcas."
       target="_blank"
       class="floating-whatsapp"
       aria-label="Fale conosco pelo WhatsApp">
        <i class="fab fa-whatsapp fa-2x"></i>
    </a>

    <script>
        // Script para menu mobile
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        if (mobileMenuButton && mobileMenu) {
            mobileMenuButton.addEventListener('click', () => {
                mobileMenu.classList.toggle('hidden');
            });
        }

        // Script para ano atual no rodapé
        const currentYearElement = document.getElementById('currentYear');
        if (currentYearElement) {
            currentYearElement.textContent = new Date().getFullYear();
        }

        // Smooth scroll para links âncora
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                if (targetElement) {
                    // Esconde o menu mobile ao clicar em um link (se estiver visível)
                    if (mobileMenu && !mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                    // Rolagem suave para o elemento
                    targetElement.scrollIntoView({
                        behavior: 'smooth'
                    });
                }
            });
        });

        // Simulação de envio de formulário (apenas para demonstração)
        const contactForm = document.getElementById('contactForm');
        const formFeedback = document.getElementById('form-feedback');

        if (contactForm && formFeedback) {
            contactForm.addEventListener('submit', function(event) {
                event.preventDefault(); // Impede o envio real do formulário

                // Simula um delay de envio
                formFeedback.textContent = 'Enviando mensagem...';
                formFeedback.className = 'mt-4 text-center text-blue-600';

                setTimeout(() => {
                    // Simula uma resposta de sucesso
                    formFeedback.textContent = 'Mensagem enviada com sucesso! Entraremos em contato em breve.';
                    formFeedback.className = 'mt-4 text-center text-green-600';
                    contactForm.reset(); // Limpa o formulário
                }, 2000);

                // Para um formulário real, você usaria fetch() para enviar os dados para um servidor:
                // const formData = new FormData(contactForm);
                // fetch('/seu-endpoint-de-envio', {
                //     method: 'POST',
                //     body: formData
                // })
                // .then(response => response.json())
                // .then(data => {
                //     console.log('Success:', data);
                //     formFeedback.textContent = 'Mensagem enviada com sucesso!';
                //     formFeedback.className = 'mt-4 text-center text-green-600';
                //     contactForm.reset();
                // })
                // .catch((error) => {
                //     console.error('Error:', error);
                //     formFeedback.textContent = 'Ocorreu um erro ao enviar a mensagem. Tente novamente.';
                //     formFeedback.className = 'mt-4 text-center text-red-600';
                // });
            });
        }
    </script>

</body>
</html>
