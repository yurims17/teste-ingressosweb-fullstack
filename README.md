# Regras de Teste para Desenvolvedor Fullstack

## Objetivo
O objetivo deste documento é definir as regras de teste para avaliar as habilidades do desenvolvedor fullstack na construção de um sistema de ingressos para eventos, utilizando **React + Next.js** no frontend e **Node.js (Express) ou PHP (Laravel)** no backend.

## Requisitos Gerais
1. **Publicação no GitHub**: O código deve ser disponibilizado em um repositório público no GitHub ou plataforma similar.
2. **Compartilhamento**: O repositório deve ser compartilhado com o e-mail **rh@agroplaymusic.com.br**.
3. **Autoria do Código**: O desenvolvedor deve implementar o teste sem o uso de ferramentas de IA, como ChatGPT.

## Estrutura do Projeto
O sistema será dividido em **dois repositórios separados**, um para o backend e outro para o frontend.

### 1. Frontend (React + Next.js)
- Utilizar **React com Next.js** para a construção do frontend.
- Permitir o uso de bibliotecas UI (Material UI, Bootstrap, Tailwind, etc.) para o design.
- Criar componentes reutilizáveis e bem estruturados.

### 2. Backend (Node.js ou PHP Laravel)
- Se utilizar **Node.js**, pode escolher entre **Express** ou **Fastify**.
- Se utilizar **PHP**, deve implementar em **Laravel**.
- Criar endpoints RESTful para gerenciamento de ingressos e eventos.
- Implementar autenticação via **JWT**.

### 3. Banco de Dados
- Utilizar um banco **relacional** (PostgreSQL, MySQL, SQL Server, SQLite) ou **NoSQL** (MongoDB).
- Caso o banco não esteja disponível online, enviar as **variáveis de ambiente** e o tipo de banco escolhido.

## Funcionalidades do Sistema
### Tema: **Sistema de Ingressos**
- **Listagem de eventos disponíveis**: O aplicativo deve exibir todos os eventos ativos no banco de dados.
- **Compra de ingressos**: O sistema deve permitir que usuários comprem ingressos para eventos disponíveis.
- **Controle de lotação**: Cada evento deve ter um número máximo de ingressos disponíveis. Quando esgotados, o evento não deve ser exibido como disponível para compra.
- **Gestão de pedidos**: Os usuários devem conseguir visualizar seus ingressos comprados em uma área específica do sistema.
- **Tela Administrativa**: Deve permitir que administradores:
  - Cadastrem, editem e excluam eventos.
  - Acompanhem a venda de ingressos em tempo real.
- **Exportação de Relatórios**: O sistema deve permitir exportação de relatórios em **CSV** contendo:
  - Lista de eventos e número de ingressos vendidos.
  - Lista de eventos disponíveis e ingressos restantes.
- **Tela de Login**: Implementar autenticação (login), mas não é necessário recuperação de senha ou cadastro de usuários.

## Critérios de Avaliação
✔ Código bem estruturado e organizado.
✔ Uso correto das tecnologias escolhidas.
✔ Implementação funcional de todas as regras descritas.
✔ Interface intuitiva e responsiva.
✔ Documentação básica do projeto (README.md com instruções de instalação e execução).

## Considerações Finais
O desenvolvedor deve testar completamente o sistema antes de enviá-lo. A equipe responsável avaliará o código e o funcionamento da aplicação conforme os critérios acima.

**Boa sorte! Esperamos ver seu melhor trabalho! 🎟️✨**
