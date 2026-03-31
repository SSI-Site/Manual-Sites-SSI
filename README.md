# 🌐 Manual do Setor de Sites | SSI - USP Leste

Bem-vindo(a) ao repositório oficial de documentação, arquitetura e capacitação do **Setor de Sites** da Semana de Sistemas de Informação (SSI) da USP Leste.

Este repositório é a nossa fonte única de verdade. Ele foi criado para centralizar o conhecimento da equipe, guiar o *onboarding* (integração) de novos membros e documentar os padrões técnicos dos nossos dois principais produtos web: o **Site-SSI** (voltado ao público) e a **CO-Dashboard** (plataforma administrativa).

---

## 🚀 Como utilizar este manual?

Se você acabou de entrar no time, siga a ordem das pastas abaixo. Elas foram organizadas como uma trilha progressiva, saindo da visão geral de negócios até a escrita de código.

### 📁 [010. Conhecendo o Setor](./010-conhecendo-o-setor)
Entenda o porquê existimos, quais são as nossas responsabilidades e a história tecnológica da SSI.
* [Introdução ao Setor](./010-conhecendo-o-setor/011-introducao.md)
* [O Site Principal](./010-conhecendo-o-setor/012-site.md)
* [A Plataforma da CO](./010-conhecendo-o-setor/013-dashboard-co.md)
* [Museu de Sites e Domínios](./010-conhecendo-o-setor/014-museu.md)

### 📁 [020. Fluxo de Desenvolvimento](./020-fluxo-de-desenvolvimento)
Aprenda como trabalhamos em equipe, como gerenciamos nossas tarefas e como enviamos código para produção sem quebrar o site.
* [Organização e Kanban](./020-fluxo-de-desenvolvimento/021-organizacao-kanban.md)
* [Padrões de Branch e Commits](./020-fluxo-de-desenvolvimento/022-padroes-de-branch-e-commits.md)
* [Fluxo de Pull Request e Revisão](./020-fluxo-de-desenvolvimento/023-fluxo-pull-request.md)

### 📁 [030. Tutoriais de Setup](./030-tutoriais-de-setup)
Guia prático para configurar o seu computador, instalar as ferramentas corretas e rodar os projetos da SSI pela primeira vez.
* [Instalação das Ferramentas Base](./030-tutoriais-de-setup/031-instalacao-ferramentas-base.md)
* [Como rodar o Site-SSI](./030-tutoriais-de-setup/032-como-rodar-o-site.md)
* [Como rodar a CO-Dashboard](./030-tutoriais-de-setup/033-como-rodar-o-dashboard.md)

### 📁 [040. Roadmap de Aprendizado](./040-roadmap-de-aprendizado)
Nossa trilha de estudos oficial. Comece aqui se você quer nivelar seus conhecimentos técnicos com a *stack* do projeto.
* [Nível 1: Fundações Web (HTML e CSS)](./040-roadmap-de-aprendizado/041-fundacoes-web-html-css.md)
* [Nível 2: JavaScript Básico ao ES6+](./040-roadmap-de-aprendizado/042-javascript-basico-ao-es6.md)
* [Nível 3: Ecossistema React e Next.js](./040-roadmap-de-aprendizado/043-ecossistema-react-e-nextjs.md)
* [Nível 4: Ferramentas do Ecossistema](./040-roadmap-de-aprendizado/044-ferramentas-git-figma-netlify.md)

### 📁 [050. Exercícios Práticos](./050-exercicios-praticos)
Valide o que você aprendeu no Roadmap construindo pequenos projetos com as mesmas exigências do nosso código oficial.
* [Exercício 01: Responsividade Mobile First](./050-exercicios-praticos/051-responsividade-e-mobile-first.md)
* [Exercício 02: Componentização com React](./050-exercicios-praticos/052-componentizacao-react.md)

---

## 🛠️ Nosso Stack Tecnológico

Caso queira saber o que roda debaixo do capô dos nossos projetos:
* **Framework Principal:** Next.js (Pages Router)
* **Biblioteca de UI:** React
* **Estilização:** Styled Components (CSS-in-JS)
* **Comunicação e API:** Axios (API Saphira)
* **Autenticação e Backend:** Firebase
* **Gerenciador de Pacotes:** Yarn
* **Hospedagem e Deploy Contínuo:** Netlify

---

## 🤝 Como contribuir com este manual

Este repositório é vivo. Conforme novas tecnologias surgirem ou nossos processos mudarem, este manual deve ser atualizado. 
Se você encontrou um erro, um link quebrado ou quer adicionar um novo material de estudo:
1. Crie uma *branch* a partir da `main`.
2. Edite ou adicione os arquivos Markdown.
3. Não se esqueça de adicionar o seu nome e data na tabela de **Histórico de Revisões** no final do arquivo que você alterou!
4. Abra uma Pull Request.

---

## 📄 Licença

Este projeto é distribuído sob a licença [MIT](./LICENSE). Sintam-se livres para utilizar, copiar e adaptar esta estrutura para outros diretórios ou projetos acadêmicos, contanto que os devidos créditos sejam mantidos.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Criação do repositório, mapeamento de arquitetura e documentação inicial. |