
# Personal FinBuddy

## Visão Geral

O projeto financeiro é um aplicativo full stack desenvolvido para ajudar os usuários a gerenciar suas finanças pessoais. Ele oferece recursos como acompanhamento de transações, categorização de despesas, geração de relatórios e muito mais.

## Tecnologias Utilizadas

**Front-End:**
- React.js
- Next.js
- TypeScript
- Material-UI

**Back-End:**
- Nest.js
- TypeScript
- PostgreSQL
- Prisma

**Infraestrutura:**
- Docker
- AWS (Amazon Web Services)

## Funcionalidades Principais

1. **Autenticação de Usuários:**
- Permitir que os usuários criem contas e façam login para acessar o aplicativo. Isso inclui funcionalidades como registro de novos usuários, login com email/senha e autenticação de dois fatores (2FA) para garantir a segurança das contas dos usuários.

2. **Gestão de Transações:**
- Permitir que os usuários visualizem, adicionem, editem e excluam transações financeiras. Isso inclui funcionalidades como adicionar uma nova transação, editar informações de transações existentes e excluir transações antigas.

3. **Categorização de Despesas:**
- Permitir que os usuários categorizem suas despesas para melhor acompanhamento e análise. Isso envolve a criação de categorias personalizadas para diferentes tipos de despesas, como alimentação, transporte, moradia, etc.

4. **Geração de Relatórios:**
- Oferecer recursos para gerar relatórios personalizados com base nas transações e categorias selecionadas. Isso inclui a capacidade de selecionar um período de tempo específico, categorias de despesas específicas e visualizar informações como total de despesas, tendências de gastos ao longo do tempo, etc.

5. **Dashboard de Finanças:**
- Apresentar um painel de controle com visão geral das finanças do usuário, incluindo saldo atual, tendências de gastos, gráficos de despesas mensais, etc. Isso oferece aos usuários uma maneira rápida e fácil de visualizar e entender sua situação financeira atual.

6. **Notificações e Alertas:**
- Enviar notificações e alertas aos usuários sobre transações importantes, vencimentos de contas, etc. Isso ajuda os usuários a se manterem informados sobre sua atividade financeira e a não perderem prazos importantes, como datas de pagamento de contas.

7. **Segurança e Privacidade:**
- Implementar medidas de segurança robustas para proteger os dados dos usuários, como autenticação de dois fatores (2FA), criptografia de dados e conformidade com regulamentações de privacidade, como o GDPR. Isso é essencial para garantir a confiança dos usuários e proteger suas informações pessoais e financeiras.

## Fluxo de Dados

1. **Autenticação de Usuários:**
- O usuário envia suas credenciais (email/senha) para o servidor.
- O servidor valida as credenciais e retorna um token de acesso JWT.
- O token JWT é armazenado no lado do cliente e enviado junto com as solicitações subsequentes para autenticação.

2. **Gestão de Transações:**
- O usuário envia uma solicitação para adicionar/editar/excluir uma transação.
- O servidor processa a solicitação, valida os dados e realiza as operações necessárias no banco de dados.
- O servidor retorna uma resposta indicando o status da operação.

3. **Geração de Relatórios:**
- O usuário seleciona os parâmetros desejados para o relatório (período de tempo, categorias, etc.).
- O servidor gera o relatório com base nos parâmetros fornecidos e retorna os resultados ao usuário.

## Instalação e Configuração

1. **Pré-requisitos:**

- Node.js
- npm ou Yarn
- Docker

2. **Passos de Instalação:**
- Clone o repositório do projeto.
- Instale as dependências do frontend e backend usando npm ou Yarn.
- Configure o banco de dados PostgreSQL e execute as migrações usando Prisma.
- Inicie os serviços utilizando Docker Compose.

  

## Contribuindo

- Para contribuir com o projeto, siga as diretrizes de contribuição definidas no arquivo CONTRIBUTING.md.
- Se encontrar algum problema ou tiver sugestões de melhoria, por favor, abra uma issue no repositório do projeto.
