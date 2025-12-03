# template-psico-gold
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dra. [Nome] - Psicóloga Clínica</title>
    
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <!-- Calendly -->
    <link href="https://assets.calendly.com/assets/external/widget.css" rel="stylesheet">
    <script src="https://assets.calendly.com/assets/external/widget.js" type="text/javascript" async></script>
    
    <style>
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
    
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#FDFBF7',
                        dark: '#333333',
                        accent: '#8B7355',
                        accentHover: '#6B5745'
                    }
                }
            }
        }
    </script>
</head>
<body class="bg-primary text-dark">

    <!-- Header -->
    <header class="fixed w-full bg-primary/95 backdrop-blur-sm shadow-sm z-50">
        <nav class="container mx-auto px-4 py-4 flex justify-between items-center max-w-6xl">
            <div class="text-2xl font-bold text-accent">Dra. [Nome]</div>
            <button onclick="Calendly.initPopupWidget({url: 'https://calendly.com/[SEU-LINK]'});return false;" 
                    class="bg-accent hover:bg-accentHover text-white px-6 py-2 rounded-full font-medium transition-all duration-300 shadow-md hover:shadow-lg">
                Agendar Consulta
            </button>
        </nav>
    </header>

    <!-- Hero Section -->
    <section class="pt-32 pb-20 px-4">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <!-- Lado Esquerdo -->
                <div class="space-y-6">
                    <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold leading-tight">
                        Liberte-se da ansiedade e retome o controle da sua vida
                    </h1>
                    <p class="text-lg md:text-xl text-gray-600">
                        Atendimento humanizado e baseado em evidências científicas. Sua jornada de transformação começa aqui.
                    </p>
                    <button onclick="Calendly.initPopupWidget({url: 'https://calendly.com/[SEU-LINK]'});return false;" 
                            class="bg-accent hover:bg-accentHover text-white px-8 py-4 rounded-full text-lg font-semibold transition-all duration-300 shadow-lg hover:shadow-xl inline-block">
                        Quero Agendar Minha Consulta
                    </button>
                    <p class="text-sm text-gray-500">✓ Presencial e Online | ✓ Horários Flexíveis</p>
                </div>
                
                <!-- Lado Direito -->
                <div class="flex justify-center">
                    <img src="https://placehold.co/600x600/E8DED2/8B7355?text=Dra.+%5BNome%5D" 
                         alt="Dra. [Nome]" 
                         class="rounded-2xl shadow-2xl w-full max-w-md object-cover">
                </div>
            </div>
        </div>
    </section>

    <!-- Sessão de Identificação (A Dor) -->
    <section class="py-20 px-4 bg-white">
        <div class="container mx-auto max-w-6xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">
                Você se identifica com algum desses sintomas?
            </h2>
            <p class="text-center text-gray-600 mb-12 max-w-2xl mx-auto">
                Reconhecer o que você está sentindo é o primeiro passo para a mudança
            </p>
            
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-6">
                <!-- Card 1 -->
                <div class="bg-primary p-6 rounded-xl shadow-md hover:shadow-xl transition-all duration-300">
                    <div class="text-4xl mb-4">😰</div>
                    <h3 class="font-semibold text-xl mb-2">Ansiedade Constante</h3>
                    <p class="text-gray-600 text-sm">Pensamentos acelerados e preocupação excessiva com o futuro</p>
                </div>
                
                <!-- Card 2 -->
                <div class="bg-primary p-6 rounded-xl shadow-md hover:shadow-xl transition-all duration-300">
                    <div class="text-4xl mb-4">😔</div>
                    <h3 class="font-semibold text-xl mb-2">Tristeza Profunda</h3>
                    <p class="text-gray-600 text-sm">Sensação de vazio e falta de motivação para atividades do dia a dia</p>
                </div>
                
                <!-- Card 3 -->
                <div class="bg-primary p-6 rounded-xl shadow-md hover:shadow-xl transition-all duration-300">
                    <div class="text-4xl mb-4">😴</div>
                    <h3 class="font-semibold text-xl mb-2">Insônia</h3>
                    <p class="text-gray-600 text-sm">Dificuldade para dormir ou manter o sono durante a noite</p>
                </div>
                
                <!-- Card 4 -->
                <div class="bg-primary p-6 rounded-xl shadow-md hover:shadow-xl transition-all duration-300">
                    <div class="text-4xl mb-4">💔</div>
                    <h3 class="font-semibold text-xl mb-2">Relacionamentos Difíceis</h3>
                    <p class="text-gray-600 text-sm">Conflitos frequentes ou dificuldade em se conectar com outras pessoas</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Sessão Sobre Mim -->
    <section class="py-20 px-4">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-2 gap-12 items-center">
                <!-- Foto -->
                <div class="flex justify-center md:justify-start">
                    <img src="https://placehold.co/400x400/E8DED2/8B7355?text=Dra.+%5BNome%5D" 
                         alt="Dra. [Nome]" 
                         class="rounded-2xl shadow-xl w-full max-w-sm object-cover">
                </div>
                
                <!-- Texto -->
                <div class="space-y-6">
                    <h2 class="text-3xl md:text-4xl font-bold">Sobre Mim</h2>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Olá! Sou a Dra. [Nome], psicóloga clínica com mais de [X] anos de experiência no acolhimento e tratamento de questões emocionais. Minha abordagem é humanizada, respeitosa e baseada em evidências científicas.
                    </p>
                    <p class="text-lg text-gray-700 leading-relaxed">
                        Acredito que cada pessoa possui dentro de si a capacidade de transformação. Meu papel é te acompanhar nessa jornada, oferecendo um espaço seguro e acolhedor.
                    </p>
                    
                    <!-- Formações -->
                    <div class="space-y-3 pt-4">
                        <div class="flex items-start">
                            <span class="text-accent mr-3">✓</span>
                            <span class="text-gray-700">CRP [NÚMERO] - Conselho Regional de Psicologia</span>
                        </div>
                        <div class="flex items-start">
                            <span class="text-accent mr-3">✓</span>
                            <span class="text-gray-700">Especialização em [ÁREA] pela [INSTITUIÇÃO]</span>
                        </div>
                        <div class="flex items-start">
                            <span class="text-accent mr-3">✓</span>
                            <span class="text-gray-700">Formação em [ABORDAGEM TERAPÊUTICA]</span>
                        </div>
                        <div class="flex items-start">
                            <span class="text-accent mr-3">✓</span>
                            <span class="text-gray-700">[MAIS DE X] pacientes atendidos com sucesso</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- O Método (Como Funciona) -->
    <section class="py-20 px-4 bg-white">
        <div class="container mx-auto max-w-6xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">Como Funciona</h2>
            <p class="text-center text-gray-600 mb-16 max-w-2xl mx-auto">
                Um processo simples e acolhedor para sua transformação
            </p>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Passo 1 -->
                <div class="text-center space-y-4">
                    <div class="w-16 h-16 bg-accent text-white rounded-full flex items-center justify-center text-2xl font-bold mx-auto">
                        1
                    </div>
                    <h3 class="text-xl font-semibold">Agendamento Fácil</h3>
                    <p class="text-gray-600">
                        Escolha o melhor horário para você através da nossa plataforma de agendamento online. Rápido e sem burocracia.
                    </p>
                </div>
                
                <!-- Passo 2 -->
                <div class="text-center space-y-4">
                    <div class="w-16 h-16 bg-accent text-white rounded-full flex items-center justify-center text-2xl font-bold mx-auto">
                        2
                    </div>
                    <h3 class="text-xl font-semibold">A Primeira Sessão</h3>
                    <p class="text-gray-600">
                        Um espaço seguro e acolhedor para você compartilhar suas questões. Vamos juntos entender suas necessidades e traçar um caminho.
                    </p>
                </div>
                
                <!-- Passo 3 -->
                <div class="text-center space-y-4">
                    <div class="w-16 h-16 bg-accent text-white rounded-full flex items-center justify-center text-2xl font-bold mx-auto">
                        3
                    </div>
                    <h3 class="text-xl font-semibold">Sua Transformação</h3>
                    <p class="text-gray-600">
                        Com sessões regulares e acompanhamento personalizado, você vai reconquistar seu equilíbrio emocional e qualidade de vida.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- Depoimentos -->
    <section class="py-20 px-4">
        <div class="container mx-auto max-w-6xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-4">O Que Meus Pacientes Dizem</h2>
            <p class="text-center text-gray-600 mb-16">
                Depoimentos reais de quem já iniciou sua jornada de transformação
            </p>
            
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Depoimento 1 -->
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex mb-3">
                        <span class="text-yellow-500">⭐⭐⭐⭐⭐</span>
                    </div>
                    <p class="text-gray-700 mb-4 italic">
                        "A Dra. [Nome] me ajudou a superar momentos muito difíceis. Sua escuta atenta e empatia fizeram toda a diferença no meu processo de cura."
                    </p>
                    <p class="font-semibold">Maria S.</p>
                    <p class="text-sm text-gray-500">Paciente há 8 meses</p>
                </div>
                
                <!-- Depoimento 2 -->
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex mb-3">
                        <span class="text-yellow-500">⭐⭐⭐⭐⭐</span>
                    </div>
                    <p class="text-gray-700 mb-4 italic">
                        "Profissional extremamente competente e acolhedora. Consegui entender e trabalhar questões que me acompanhavam há anos. Recomendo muito!"
                    </p>
                    <p class="font-semibold">João P.</p>
                    <p class="text-sm text-gray-500">Paciente há 1 ano</p>
                </div>
                
                <!-- Depoimento 3 -->
                <div class="bg-white p-6 rounded-xl shadow-md">
                    <div class="flex mb-3">
                        <span class="text-yellow-500">⭐⭐⭐⭐⭐</span>
                    </div>
                    <p class="text-gray-700 mb-4 italic">
                        "A terapia mudou minha vida. Aprendi a lidar com a ansiedade de forma saudável e hoje me sinto muito mais leve e confiante."
                    </p>
                    <p class="font-semibold">Ana C.</p>
                    <p class="text-sm text-gray-500">Paciente há 6 meses</p>
                </div>
            </div>
        </div>
    </section>

    <!-- FAQ -->
    <section class="py-20 px-4 bg-white">
        <div class="container mx-auto max-w-4xl">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12">Perguntas Frequentes</h2>
            
            <div class="space-y-4">
                <!-- FAQ 1 -->
                <details class="bg-primary rounded-lg shadow-md">
                    <summary class="px-6 py-4 cursor-pointer font-semibold text-lg hover:text-accent transition-colors">
                        Você aceita convênio?
                    </summary>
                    <div class="px-6 pb-4 text-gray-700">
                        <p>Atualmente trabalho apenas com atendimento particular. Os valores das consultas são informados no primeiro contato e você recebe o recibo para reembolso pelo seu plano de saúde.</p>
                    </div>
                </details>
                
                <!-- FAQ 2 -->
                <details class="bg-primary rounded-lg shadow-md">
                    <summary class="px-6 py-4 cursor-pointer font-semibold text-lg hover:text-accent transition-colors">
                        Os atendimentos são online ou presenciais?
                    </summary>
                    <div class="px-6 pb-4 text-gray-700">
                        <p>Ofereço as duas modalidades! Você pode escolher a que for mais confortável para você. As consultas online são realizadas por videochamada com total segurança e sigilo.</p>
                    </div>
                </details>
                
                <!-- FAQ 3 -->
                <details class="bg-primary rounded-lg shadow-md">
                    <summary class="px-6 py-4 cursor-pointer font-semibold text-lg hover:text-accent transition-colors">
                        Qual o valor da consulta?
                    </summary>
                    <div class="px-6 pb-4 text-gray-700">
                        <p>O investimento por sessão é de R$ [VALOR]. Ofereço também pacotes mensais com condições especiais. Entre em contato para mais informações.</p>
                    </div>
                </details>
                
                <!-- FAQ 4 -->
                <details class="bg-primary rounded-lg shadow-md">
                    <summary class="px-6 py-4 cursor-pointer font-semibold text-lg hover:text-accent transition-colors">
                        Quanto tempo dura cada sessão?
                    </summary>
                    <div class="px-6 pb-4 text-gray-700">
                        <p>Cada sessão tem duração de 50 minutos. Esse é o tempo padrão estabelecido pelo Conselho Federal de Psicologia para garantir um atendimento de qualidade.</p>
                    </div>
                </details>
                
                <!-- FAQ 5 -->
                <details class="bg-primary rounded-lg shadow-md">
                    <summary class="px-6 py-4 cursor-pointer font-semibold text-lg hover:text-accent transition-colors">
                        Como funciona a primeira consulta?
                    </summary>
                    <div class="px-6 pb-4 text-gray-700">
                        <p>Na primeira sessão, vamos nos conhecer melhor. Você compartilha suas questões e juntos definimos os objetivos do tratamento. É um momento de acolhimento e escuta, sem julgamentos.</p>
                    </div>
                </details>
            </div>
        </div>
    </section>

    <!-- CTA Final -->
    <section class="py-20 px-4 bg-accent text-white">
        <div class="container mx-auto max-w-4xl text-center space-y-6">
            <h2 class="text-3xl md:text-4xl font-bold">
                Pronto para dar o primeiro passo?
            </h2>
            <p class="text-lg md:text-xl opacity-90">
                Agende sua consulta agora e comece sua jornada de transformação
            </p>
            <button onclick="Calendly.initPopupWidget({url: 'https://calendly.com/[SEU-LINK]'});return false;" 
                    class="bg-white text-accent hover:bg-gray-100 px-8 py-4 rounded-full text-lg font-semibold transition-all duration-300 shadow-lg hover:shadow-xl inline-block">
                Agendar Minha Consulta Agora
            </button>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-dark text-white py-12 px-4">
        <div class="container mx-auto max-w-6xl">
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Coluna 1 -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Dra. [Nome]</h3>
                    <p class="text-gray-400">Psicóloga Clínica</p>
                    <p class="text-gray-400">CRP [NÚMERO]</p>
                </div>
                
                <!-- Coluna 2 -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Contato</h3>
                    <p class="text-gray-400 mb-2">📍 [Endereço do Consultório]</p>
                    <p class="text-gray-400 mb-2">📧 [email@exemplo.com]</p>
                    <p class="text-gray-400">📱 [Telefone]</p>
                </div>
                
                <!-- Coluna 3 -->
                <div>
                    <h3 class="text-xl font-bold mb-4">Horários</h3>
                    <p class="text-gray-400 mb-2">Segunda a Sexta: 8h às 20h</p>
                    <p class="text-gray-400">Sábados: 8h às 14h</p>
                </div>
            </div>
            
            <div class="border-t border-gray-700 mt-8 pt-8 text-center text-gray-400 text-sm">
                <p>&copy; 2024 Dra. [Nome]. Todos os direitos reservados.</p>
            </div>
        </div>
    </footer>

    <!-- Botão Flutuante WhatsApp -->
    <a href="https://wa.me/5511999999999?text=Olá!%20Gostaria%20de%20agendar%20uma%20consulta" 
       target="_blank"
       class="fixed bottom-6 right-6 bg-green-500 hover:bg-green-600 text-white w-16 h-16 rounded-full shadow-2xl flex items-center justify-center text-3xl transition-all duration-300 hover:scale-110 z-50">
        💬
    </a>

</body>
</html>
