# Projeto-Sistema-SUS
Sistema completo para agendamento de consultas (modelo SUS-like), estimativa de custos para RH e emissão de relatórios detalhados.  Tecnologias: React (Frontend) e Node.js (Backend).


<h2>🏥 Sistema de Agendamento Médico</h2>

Plataforma completa para agendamento de consultas (modelo SUS-like), controle financeiro e gestão de membros.

<h2>📝 Sobre o Projeto</h2>

- Agendamento de consultas
- Controle financeiro (Estimativa de custos para RH)
- Gestão de membros (Pacientes/Usuários)
- Relatórios gráficos
- Emissão de documentação de recibos
- Autenticação de entrada (Login de usuários/membros)


<h2>📋 Índice</h2>

- Projeto
- Funcionalidades do Projeto
- Tecnologias Usadas
- Arquitetura
- Uso / API Endpoints
- Teste de Credenciais
- Problemas Conhecidos
- Licença



<h2>Anotações pessoais</h2>
<h3>Modo de construção</h3>

Etapas:
1- Definição de tecnologias
  - Front: Next, React, Typescript
  - Back: Node, express, API rest
  - Others: docker, npm, git, github 
    Inicialização do projeto
  - Pré-definição e configuração de pastas e rotas
       - Front
         - npx create-next-app@latest
            - accept: tailwindcss, react, react-dom, typescript, eslint
         - Dockerfile
         - (Você não precisa de um index.js. O Next.js tem sua própria lógica de inicialização baseada na estrutura de pastas (src/app ou src/pages))
       - Back
         -  npm init -y
         -  npm install express pg cors
         -  npm install --save-dev nodemon
           -  Adicionar em "scripts" : { "dev": "nodemon index.js" }
         -  Dockerfile
         -  index.js (apenas dentro da pasta backend, é o arquivo principal que o Node.js lê para iniciar o seu servidor)
         - .env 
  - Criação do documento docker-compose
<h4>2- Inicialização</h4>
  - /backend
    - 
  - /frontend
    - 
  - All
    - First: docker-compose up -d
    - Iniciar: docker-compose up
    - docker-compose stop
    
