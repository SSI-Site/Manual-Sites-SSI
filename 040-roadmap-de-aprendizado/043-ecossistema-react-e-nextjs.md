# Nível 3: Ecossistema React e Next.js

**⚠️ Importante:** Este é o núcleo da nossa *stack* tecnológica. O Site-SSI e a CO-Dashboard são construídos com React (para as interfaces) e Next.js (como framework principal). Domine os conceitos deste documento, pois eles representam 90% do nosso trabalho diário.

## 1. React Básico
O React é uma biblioteca para criar interfaces de usuário baseada em componentes. Em vez de construir uma página inteira de uma vez, nós construímos pequenos blocos (botões, cards, modais) e os montamos como peças de Lego.

**Conceitos essenciais e Materiais de Estudo:**
* **Visão Geral e o que é o React:** [Artigo Sugerido](https://blog-next.kenzie.com.br/react)
* **Componentes e JSX:** Como escrever HTML dentro do JavaScript.
* **Props (Propriedades):** Como passar dados de um componente "Pai" para um componente "Filho".
* **Eventos:** Como lidar com cliques e interações do usuário.
* **State (Estado) e `useState`:** Como guardar dados que mudam e atualizam a tela automaticamente.
* **Hooks e Ciclo de Vida (`useEffect`):** Como executar códigos em momentos específicos (ex: buscar dados assim que a tela abre).
  * [Vídeo Sugerido contemplando os tópicos acima](https://www.youtube.com/watch?v=w7ejDZ8SWv8)
* **Renderização Condicional:** Como mostrar ou esconder coisas na tela (ex: mostrar algo só se o usuário estiver logado). [Vídeo sugerido](https://www.youtube.com/watch?v=rF6guBbfTl0)
* **Tutorial Oficial do React:** [Documentação do React](https://pt-br.react.dev/learn)

## 2. Next.js (O Framework)
O React puro cria aplicações SPA (Single Page Applications) que rodam apenas no navegador do usuário, o que é ruim para o SEO do Google. O Next.js resolve isso renderizando as páginas no servidor (SSR - Server Side Rendering) antes de enviá-las ao usuário. [saver mais sobre SPA](https://youtu.be/opxYpCKzlLk?si=q5xY5NDxSQIouxYW)

**Atenção:** O nosso projeto utiliza o padrão **Pages Router** do Next.js (não o App Router mais recente).

**Conceitos essenciais e Materiais de Estudo:**
* **O que é Next.js?** [Vídeo sugerido](https://www.youtube.com/watch?v=q_ZoX98uopM)
* **React vs Next.js:** Entenda as diferenças de SEO e SSR.
  * [Artigo sugerido 1](https://snipcart.com/blog/next-js-vs-react)
  * [Artigo sugerido 2](https://www.alura.com.br/artigos/next-js-vantagens)
* **Roteamento (Pages Router):** Como funciona a pasta `pages/` (onde `pages/sobre.js` vira automaticamente a rota `/sobre`). [Vídeo Sugerido](https://www.youtube.com/watch?v=4Tb8dp5GYqI)
* **Estruturação de Projetos Next.js:** [Vídeo FORTEMENTE sugerido](https://www.youtube.com/watch?v=mJK5oGixSYo)

## 3. Estilização Avançada (Styled Components)
Nós não usamos arquivos `.css` tradicionais no nosso projeto. Nós usamos CSS-in-JS com a biblioteca Styled Components. Isso impede que o estilo de um botão quebre o estilo do resto do site, pois todo o CSS é isolado.

**Conceitos essenciais e Materiais de Estudo:**
* **O que é e Vantagens:** [Artigo sugerido](https://blog.iteris.com.br/o-que-e-react-native-com-styled-components/#:~:text=Styled%20Components%20%C3%A9%20uma%20biblioteca,c%C3%B3digos%20CSS%20dentro%20do%20Javascript.)
* **Diferenças para o CSS comum:** [Artigo sugerido](https://medium.com/nossa-coletividad/styled-components-padr%C3%B5es-em-produ%C3%A7%C3%A3o-4958e91d4d92)
* **Uso prático (React e Next):**
  * [Vídeo: Styled Components com React](https://www.youtube.com/watch?v=R3S8DEzEn6s)
  * [Vídeo: Styled Components com Next.js](https://www.youtube.com/watch?v=mJK5oGixSYo)
* **Documentação Oficial:** [Styled Components Docs](https://styled-components.com/docs)

---

## 🚀 Hora de Praticar!

Com a base de React e Styled Components consolidada, é o momento de refatorar e modernizar o que você construiu no nível 1.

Acesse o guia do **[Exercício 02: Componentização em React](../050-exercicios-praticos/052-componentizacao-react.md)** para transformar a sua página estática em uma aplicação modularizada com Next.js.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |