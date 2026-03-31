# Nível 4: Ferramentas do Ecossistema (Git, Figma e Netlify)

Escrever código é apenas uma parte do trabalho de um desenvolvedor front-end. Em um ambiente profissional e colaborativo como o Site-SSI, você precisa saber como versionar seu código, como extrair informações de um protótipo visual e como a sua aplicação vai parar na internet.

## 1. Git e GitHub (Versionamento de Código)
O Git é o sistema de controle de versão que usamos localmente, e o GitHub é a plataforma na nuvem onde hospedamos nosso repositório em equipe. 

**Conceitos essenciais e Materiais de Estudo:**
* **Introdução (O que é Git e GitHub):** [Vídeo sugerido](https://www.youtube.com/watch?v=DqTITcMq68k)
* **Comandos Básicos:** Entender a diferença e o uso de `add`, `commit`, `push` e `pull`.
* **Gerenciamento de Repositórios:** Como criar, clonar (`clone`) e fazer `fork`.
* [Vídeo sugerido com todos os tópicos acima](https://www.youtube.com/watch?v=UBAX-13g8OM)

## 2. Figma (UI/UX e Leitura de Design)
Nós não criamos o design do site do zero; essa é a função da equipe de Criação e Comunicação. No entanto, o desenvolvedor front-end precisa saber "ler" o Figma para transformar o desenho em código (Next.js + Styled Components).

**Conceitos essenciais e Materiais de Estudo:**
* **Inspecionando Elementos:** Como clicar em um botão no Figma e descobrir sua cor (Hexadecimal), tamanho da fonte, `border-radius` e espaçamentos (`padding`/`margin`). [Vídeo sugerido](https://youtu.be/GjL5uKBt3Dc?si=BGD8f6WuQymNV6z3)
* **Design System:** Entender como padronizamos cores e tipografia para todo o projeto. [Artigo sobre Design System](https://medium.com/pretux/design-system-um-produto-servindo-outros-produtos-a12b1ee5b4bd)
* **Exportação de Assets:** Como baixar imagens e ícones (formato SVG) diretamente do protótipo para a pasta `public/` do nosso projeto.

## 3. Deploy Contínuo com Netlify
O *deploy* é o ato de colocar o site no ar. A opção padrão para projetos Next.js costuma ser a Vercel, porém, como utilizamos uma organização no GitHub (o que exigiria um plano pago na Vercel), o nosso setor adotou o **Netlify** como provedor de hospedagem oficial.

**Conceitos essenciais e Materiais de Estudo:**
* **Integração Contínua (CI/CD):** Entender que não precisamos enviar arquivos manualmente. Toda vez que um código é aprovado e entra na *branch* `main`, o Netlify baixa o projeto, roda o *build* (Yarn) e atualiza o site automaticamente.
* **Deploy Previews:** Uma das funcionalidades mais úteis que usamos. Quando você abre uma *Pull Request*, o Netlify gera um link temporário exclusivo para aquela PR. Isso permite que a equipe teste as suas alterações em um ambiente real antes de aprovar o código.

---

## 🎉 Parabéns!

Você concluiu o Roadmap de Aprendizado do Setor de Sites da SSI. 

Se você passou por todos os níveis e realizou os exercícios práticos, você já tem a base teórica e prática necessária para pegar a sua primeira *task* real no nosso quadro Kanban. Bem-vindo(a) oficialmente ao time de desenvolvimento!

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |