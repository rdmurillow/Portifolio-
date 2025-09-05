<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Murillo Romão Dibo - Currículo</title>
    <style>
        /* Variáveis de cores */
        :root {
            --primary-color: #2c3e50;
            --secondary-color: #3498db;
            --accent-color: #e74c3c;
            --light-color: #ecf0f1;
            --dark-color: #34495e;
            --text-color: #333;
            --background-color: #f9f9f9;
        }
        
        /* Reset e estilos base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            line-height: 1.6;
            color: var(--text-color);
            background-color: var(--background-color);
            padding: 0;
            margin: 0;
        }
        
        .container {
            max-width: 1000px;
            margin: 0 auto;
            padding: 20px;
            background-color: white;
            box-shadow: 0 0 15px rgba(0, 0, 0, 0.1);
        }
        
        /* Cabeçalho */
        header {
            text-align: center;
            padding: 30px 0;
            background: linear-gradient(135deg, var(--primary-color), var(--secondary-color));
            color: white;
            margin-bottom: 30px;
            border-bottom: 5px solid var(--accent-color);
        }
        
        h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
        }
        
        .contact-info {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            gap: 20px;
            margin-top: 15px;
        }
        
        .contact-item {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        /* Seções */
        section {
            margin-bottom: 30px;
        }
        
        h2 {
            color: var(--primary-color);
            padding-bottom: 10px;
            margin-bottom: 20px;
            border-bottom: 2px solid var(--secondary-color);
            display: flex;
            align-items: center;
        }
        
        h2 i {
            margin-right: 10px;
            color: var(--secondary-color);
        }
        
        /* Objetivo */
        .objective {
            background-color: var(--light-color);
            padding: 20px;
            border-radius: 8px;
            border-left: 5px solid var(--secondary-color);
        }
        
        /* Educação e Experiência */
        .timeline-item {
            margin-bottom: 25px;
            padding-left: 20px;
            border-left: 3px solid var(--secondary-color);
            position: relative;
        }
        
        .timeline-item:before {
            content: '';
            position: absolute;
            width: 15px;
            height: 15px;
            border-radius: 50%;
            background-color: var(--secondary-color);
            left: -9px;
            top: 5px;
        }
        
        .timeline-item h3 {
            color: var(--dark-color);
            margin-bottom: 5px;
        }
        
        .timeline-item .date {
            color: var(--accent-color);
            font-weight: bold;
            margin-bottom: 10px;
            display: block;
        }
        
        /* Projetos */
        .project {
            background-color: var(--light-color);
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
            border-left: 5px solid var(--accent-color);
        }
        
        .project h3 {
            color: var(--dark-color);
            margin-bottom: 10px;
        }
        
        /* Habilidades */
        .skills-container {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 20px;
        }
        
        .skill-category {
            background-color: var(--light-color);
            padding: 15px;
            border-radius: 8px;
        }
        
        .skill-category h3 {
            color: var(--dark-color);
            margin-bottom: 10px;
            border-bottom: 1px solid var(--secondary-color);
            padding-bottom: 5px;
        }
        
        .skill-list {
            list-style-type: none;
        }
        
        .skill-list li {
            padding: 5px 0;
            display: flex;
            align-items: center;
        }
        
        .skill-list li:before {
            content: '►';
            color: var(--secondary-color);
            margin-right: 10px;
            font-size: 0.8rem;
        }
        
        /* Idiomas */
        .languages {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        
        .language-item {
            background-color: var(--light-color);
            padding: 15px;
            border-radius: 8px;
            flex: 1;
            min-width: 150px;
            text-align: center;
        }
        
        /* Rodapé */
        footer {
            text-align: center;
            padding: 20px;
            margin-top: 30px;
            background-color: var(--primary-color);
            color: white;
            border-top: 5px solid var(--accent-color);
        }
        
        /* Responsividade */
        @media (max-width: 768px) {
            .container {
                padding: 15px;
            }
            
            h1 {
                font-size: 2rem;
            }
            
            .contact-info {
                flex-direction: column;
                gap: 10px;
            }
            
            .skills-container {
                grid-template-columns: 1fr;
            }
        }
    </style>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
</head>
<body>
    <header>
        <div class="container">
            <h1>Murillo Romão Dibo</h1>
            <div class="contact-info">
                <div class="contact-item">
                    <i class="fas fa-map-marker-alt"></i>
                    <span>São Paulo</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-phone"></i>
                    <span>11 99977-4405</span>
                </div>
                <div class="contact-item">
                    <i class="fas fa-envelope"></i>
                    <span>romaomudibo13@gmail.com</span>
                </div>
            </div>
        </div>
    </header>

    <div class="container">
        <section>
            <h2><i class="fas fa-bullseye"></i> Objetivo</h2>
            <div class="objective">
                <p>Desenvolvedor em formação com foco em Python, C, C++ e C#, dedicado a construir uma base sólida
                em algoritmos e lógica de programação. Experiência prática no desenvolvimento de bots para
                automação e integração com APIs. Combino habilidades técnicas em ascensão com competências
                interpessoais adquiridas na docência e no suporte ao cliente, buscando minha primeira oportunidade
                desafiadora na área de tecnologia.</p>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-graduation-cap"></i> Formação Acadêmica</h2>
            <div class="timeline-item">
                <h3>Educação Física – Licenciatura</h3>
                <span class="date">Universidade Cidade de São Paulo (UNICID) — Concluído em Dez/2023</span>
            </div>
            <div class="timeline-item">
                <h3>Análise e Desenvolvimento de Sistemas</h3>
                <span class="date">UNISA — Em andamento</span>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-code"></i> Projetos</h2>
            <div class="project">
                <h3>Bot de Gerenciamento de Lobby para Discord</h3>
                <p>Desenvolvimento de bot em Python para automatizar e organizar a criação de times em
                servidores de jogos, solucionando um problema recorrente em comunidades online.</p>
                <h4>Implementações:</h4>
                <ul class="skill-list">
                    <li>Sistema de fila de jogadores com comandos interativos</li>
                    <li>Algoritmo para divisão aleatória e equilibrada de times</li>
                    <li>Seleção automática de capitães</li>
                    <li>Integração robusta com a API do Discord via biblioteca discord.py</li>
                </ul>
                <h4>Habilidades demonstradas:</h4>
                <ul class="skill-list">
                    <li>Lógica de programação</li>
                    <li>Programação assíncrona</li>
                    <li>Manipulação de dados</li>
                    <li>Controle de versão com Git</li>
                </ul>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-cogs"></i> Habilidades e Conhecimentos</h2>
            <div class="skills-container">
                <div class="skill-category">
                    <h3>Linguagens de Programação</h3>
                    <ul class="skill-list">
                        <li>Python (em estudo)</li>
                        <li>C (em estudo)</li>
                        <li>C++ (em estudo)</li>
                        <li>C# (em estudo)</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Desenvolvimento & Frameworks</h3>
                    <ul class="skill-list">
                        <li>Discord.py</li>
                        <li>Desenvolvimento de bots</li>
                        <li>Integração com APIs</li>
                        <li>Lógica de programação e algoritmos</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Suporte Técnico & Infraestrutura</h3>
                    <ul class="skill-list">
                        <li>Troubleshooting básico de hardware e software</li>
                        <li>Configuração de redes locais</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Ferramentas de Design</h3>
                    <ul class="skill-list">
                        <li>Pacote Adobe (Premiere Rush, Photoshop)</li>
                        <li>Edição de vídeo para redes sociais (Reels, TikTok)</li>
                    </ul>
                </div>
                
                <div class="skill-category">
                    <h3>Soft Skills</h3>
                    <ul class="skill-list">
                        <li>Comunicação clara (vendas e ensino)</li>
                        <li>Trabalho em equipe</li>
                        <li>Criatividade</li>
                        <li>Didática</li>
                        <li>Proatividade</li>
                    </ul>
                </div>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-briefcase"></i> Experiências</h2>
            <div class="timeline-item">
                <h3>CLUBE ESPORTIVO DA PENHA & PREFEITURA MUNICIPAL</h3>
                <span class="date">São Paulo, SP | Jan 2024 – Jan 2025</span>
                <p><strong>Professor de Beach Tênis e Educação Física</strong></p>
                <ul class="skill-list">
                    <li>Ministração de aulas de Beach Tênis e Educação Física para grupos de diferentes idades e níveis técnicos</li>
                    <li>Desenvolvimento de planos de aula e atividades lúdicas, promovendo inclusão, disciplina e trabalho em equipe</li>
                </ul>
                <p><strong>Habilidades adquiridas:</strong> Didática, planejamento pedagógico, comunicação eficaz no ensino e gestão de grupos</p>
            </div>
            
            <div class="timeline-item">
                <h3>FLOWTEX</h3>
                <span class="date">São Paulo, SP | Jan 2022 – Set 2024</span>
                <p><strong>Técnico de Máquinas e Assistente de Marketing Digital</strong></p>
                <ul class="skill-list">
                    <li>Atuação técnica: Operação e suporte de software embarcado em máquinas, realizando ajustes e troubleshooting para garantir pleno funcionamento</li>
                    <li>Atuação em marketing digital: Criação e edição de conteúdo audiovisual (Reels, TikTok), aumentando o engajamento orgânico da marca nas redes sociais</li>
                </ul>
                <p><strong>Habilidades adquiridas:</strong> Raciocínio lógico para solução de problemas técnicos, noções de software, criatividade e edição de vídeo</p>
            </div>
            
            <div class="timeline-item">
                <h3>ACADEMIA JET VILA</h3>
                <span class="date">São Paulo, SP | Jan 2017 – Dez 2018</span>
                <p><strong>Professor de Natação/Musculação e Recepcionista</strong></p>
                <ul class="skill-list">
                    <li>Função como professor: Instrução em técnicas de natação e musculação, garantindo segurança, progresso técnico e desenvolvimento físico dos alunos</li>
                    <li>Função como recepcionista: Atendimento ao cliente, vendas de planos e suporte técnico básico à infraestrutura de TI (manutenção de computadores e configuração de rede local)</li>
                </ul>
            </div>
        </section>

        <section>
            <h2><i class="fas fa-language"></i> Idiomas e Cursos</h2>
            <h3>Idiomas</h3>
            <div class="languages">
                <div class="language-item">
                    <h4>Inglês</h4>
                    <p>Intermediário</p>
                </div>
                <div class="language-item">
                    <h4>Espanhol</h4>
                    <p>Intermediário</p>
                </div>
                <div class="language-item">
                    <h4>Libras</h4>
                    <p>Básico</p>
                </div>
            </div>
            
            <h3 style="margin-top: 20px;">Cursos Complementares</h3>
            <ul class="skill-list">
                <li>Algoritmos e Lógica de Programação em C, C++ e C# — Udemy (em curso)</li>
            </ul>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>Murillo Romão Dibo - Desenvolvedor em Formação</p>
            <p>Atualizado em Setembro de 2023</p>
        </div>
    </footer>
</body>
</html>
