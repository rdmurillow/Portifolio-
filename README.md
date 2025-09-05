curriculo.py

"""
# Murillo Romão Dibo - Currículo em Python

Este arquivo Python contém informações profissionais e de contato formatadas
para exibição no GitHub.

## Informações de Contato
- Localização: São Paulo
- Telefone: 11 99977-4405
- Email: romaomudibo13@gmail.com
"""

class Professional:
    """Classe principal que contém todas as informações profissionais"""
    
    def __init__(self):
        self.name = "Murillo Romão Dibo"
        self.location = "São Paulo"
        self.phone = "11 99977-4405"
        self.email = "romaomudibo13@gmail.com"
        self.objective = self.get_objective()
        self.education = self.get_education()
        self.projects = self.get_projects()
        self.skills = self.get_skills()
        self.experience = self.get_experience()
        self.languages = self.get_languages()
        self.courses = self.get_courses()
    
    def get_objective(self):
        """Retorna o objetivo profissional"""
        return (
            "Desenvolvedor em formação com foco em Python, C, C++ e C#, dedicado a construir uma base sólida "
            "em algoritmos e lógica de programação. Experiência prática no desenvolvimento de bots para "
            "automação e integração com APIs. Combino habilidades técnicas em ascensão com competências "
            "interpessoais adquiridas na docência e no suporte ao cliente, buscando minha primeira oportunidade "
            "desafiadora na área de tecnologia."
        )
    
    def get_education(self):
        """Retorna a formação acadêmica"""
        return [
            {
                "course": "Educação Física – Licenciatura",
                "institution": "Universidade Cidade de São Paulo (UNICID)",
                "period": "Concluído em Dez/2023"
            },
            {
                "course": "Análise e Desenvolvimento de Sistemas",
                "institution": "UNISA",
                "period": "Em andamento"
            }
        ]
    
    def get_projects(self):
        """Retorna os projetos desenvolvidos"""
        return [
            {
                "name": "Bot de Gerenciamento de Lobby para Discord",
                "description": (
                    "Desenvolvimento de bot em Python para automatizar e organizar a criação de times em "
                    "servidores de jogos, solucionando um problema recorrente em comunidades online."
                ),
                "technologies": [
                    "Sistema de fila de jogadores com comandos interativos",
                    "Algoritmo para divisão aleatória e equilibrada de times",
                    "Seleção automática de capitães",
                    "Integração robusta com a API do Discord via biblioteca discord.py"
                ],
                "skills": [
                    "Lógica de programação",
                    "Programação assíncrona",
                    "Manipulação de dados",
                    "Controle de versão com Git"
                ]
            }
        ]
    
    def get_skills(self):
        """Retorna as habilidades técnicas"""
        return {
            "Linguagens de Programação": [
                "Python (em estudo)",
                "C (em estudo)", 
                "C++ (em estudo)",
                "C# (em estudo)"
            ],
            "Desenvolvimento & Frameworks": [
                "Discord.py",
                "Desenvolvimento de bots",
                "Integração com APIs",
                "Lógica de programação e algoritmos"
            ],
            "Suporte Técnico & Infraestrutura": [
                "Troubleshooting básico de hardware e software",
                "Configuração de redes locais"
            ],
            "Ferramentas de Design": [
                "Pacote Adobe (Premiere Rush, Photoshop)",
                "Edição de vídeo para redes sociais (Reels, TikTok)"
            ],
            "Soft Skills": [
                "Comunicação clara (vendas e ensino)",
                "Trabalho em equipe",
                "Criatividade",
                "Didática",
                "Proatividade"
            ]
        }
    
    def get_experience(self):
        """Retorna a experiência profissional"""
        return [
            {
                "company": "CLUBE ESPORTIVO DA PENHA & PREFEITURA MUNICIPAL",
                "position": "Professor de Beach Tênis e Educação Física",
                "location": "São Paulo, SP",
                "period": "Jan 2024 – Jan 2025",
                "responsibilities": [
                    "Ministração de aulas de Beach Tênis e Educação Física para grupos de diferentes idades e níveis técnicos",
                    "Desenvolvimento de planos de aula e atividades lúdicas, promovendo inclusão, disciplina e trabalho em equipe"
                ],
                "skills_acquired": [
                    "Didática",
                    "Planejamento pedagógico", 
                    "Comunicação eficaz no ensino",
                    "Gestão de grupos"
                ]
            },
            {
                "company": "FLOWTEX",
                "position": "Técnico de Máquinas e Assistente de Marketing Digital",
                "location": "São Paulo, SP", 
                "period": "Jan 2022 – Set 2024",
                "responsibilities": [
                    "Operação e suporte de software embarcado em máquinas, realizando ajustes e troubleshooting",
                    "Criação e edição de conteúdo audiovisual (Reels, TikTok) para aumentar engajamento orgânico"
                ],
                "skills_acquired": [
                    "Raciocínio lógico para solução de problemas técnicos",
                    "Noções de software",
                    "Criatividade",
                    "Edição de vídeo"
                ]
            },
            {
                "company": "ACADEMIA JET VILA",
                "position": "Professor de Natação/Musculação e Recepcionista",
                "location": "São Paulo, SP",
                "period": "Jan 2017 – Dez 2018", 
                "responsibilities": [
                    "Instrução em técnicas de natação e musculação, garantindo segurança e progresso técnico",
                    "Atendimento ao cliente, vendas de planos e suporte técnico básico à infraestrutura de TI"
                ],
                "skills_acquired": [
                    "Instrução técnica",
                    "Atendimento ao cliente",
                    "Vendas",
                    "Manutenção de computadores",
                    "Configuração de rede local"
                ]
            }
        ]
    
    def get_languages(self):
        """Retorna os idiomas"""
        return {
            "Inglês": "Intermediário",
            "Espanhol": "Intermediário", 
            "Libras": "Básico"
        }
    
    def get_courses(self):
        """Retorna os cursos complementares"""
        return [
            "Algoritmos e Lógica de Programação em C, C++ e C# — Udemy (em curso)"
        ]
    
    def display_resume(self):
        """Exibe o currículo de forma formatada"""
        print("=" * 50)
        print(f"{self.name.upper()}")
        print("=" * 50)
        print(f"Localização: {self.location}")
        print(f"Telefone: {self.phone}")
        print(f"Email: {self.email}\n")
        
        print("OBJETIVO")
        print("=" * 50)
        print(f"{self.objective}\n")
        
        print("FORMAÇÃO ACADÊMICA")
        print("=" * 50)
        for edu in self.education:
            print(f"- {edu['course']} | {edu['institution']} — {edu['period']}")
        print()
        
        print("PROJETOS")
        print("=" * 50)
        for project in self.projects:
            print(f"{project['name']}")
            print(f"- {project['description']}")
            print("- Implementações:")
            for tech in project['technologies']:
                print(f"  • {tech}")
            print("- Habilidades demonstradas:")
            for skill in project['skills']:
                print(f"  • {skill}")
            print()
        
        print("HABILIDADES E CONHECIMENTOS")
        print("=" * 50)
        for category, skills in self.skills.items():
            print(f"{category}:")
            for skill in skills:
                print(f"  • {skill}")
            print()
        
        print("EXPERIÊNCIAS")
        print("=" * 50)
        for exp in self.experience:
            print(f"{exp['company']} | {exp['position']}")
            print(f"{exp['location']} | {exp['period']}")
            print("- Responsabilidades:")
            for resp in exp['responsibilities']:
                print(f"  • {resp}")
            print("- Habilidades adquiridas:")
            for skill in exp['skills_acquired']:
                print(f"  • {skill}")
            print()
        
        print("IDIOMAS")
        print("=" * 50)
        for language, level in self.languages.items():
            print(f"- {language} — {level}")
        print()
        
        print("CURSOS COMPLEMENTARES")
        print("=" * 50)
        for course in self.courses:
            print(f"- {course}")
