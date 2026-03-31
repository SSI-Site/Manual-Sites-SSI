# Exercício 02: Componentização com React e Next.js

Chegou o momento de elevar o nível do seu código. Neste exercício, você vai abandonar o HTML e CSS puros e recriar o layout do Exercício 01 utilizando as tecnologias oficiais do Site-SSI: **Next.js**, **React** e **Styled Components**.

O objetivo aqui é entender como fragmentar uma interface visual em pequenos "blocos de Lego" (componentes) inteligentes e reutilizáveis.

## O Desafio
Você deve refazer a página responsiva do Exercício 01 (que continha no mínimo 3 cards com imagem e texto), mas agora dentro de um projeto Next.js.

### Requisitos Fundamentais:
1. **Setup do Projeto:** Inicie um projeto básico utilizando Next.js (padrão Pages Router).
2. **O Componente Card:** É **obrigatório** que você crie um componente isolado para o seu card (ex: `<MeuCard />`). Você não pode simplesmente copiar e colar o código HTML do card três vezes na página principal.
3. **Uso de Props:** O seu componente de card deve ser dinâmico. Ele precisa receber a imagem e o texto de fora, através de `props`. A página principal é quem deve "passar" essas informações para o componente.
4. **Estilização com Styled Components:** É **obrigatório** o uso da biblioteca `styled-components` para todo o layout e estilo do projeto. 
   * **Atenção:** Não deve haver nenhum arquivo `.css` (ou similar) no seu projeto, com exceção de um possível arquivo de estilos globais (`GlobalStyle`). O CSS de cada componente deve viver no mesmo arquivo JavaScript que ele.
5. **Responsividade Mantida:** A metodologia Mobile First e o Flexbox continuam sendo obrigatórios.

## Orientações Adicionais
* **Estrutura de Pastas:** Não se preocupe em criar uma arquitetura de pastas complexa logo de cara. Tente focar em ter a sua página em `pages/index.js` e os seus componentes em uma pasta `src/components/`.
* **Map:** Tente colocar os dados dos seus 3 cards (título, texto e url da imagem) dentro de um array de objetos em JavaScript e utilize a função `.map()` para renderizar os componentes na tela automaticamente.

## Referências de Exemplo
Se precisar de inspiração ou quiser ver como organizamos o código, acesse:
* [Exemplo de Repositório em Next.js e Styled Components](https://github.com/LucasMS115/mobile-first-test-next-version)
* [Visualização do Exemplo](https://resp-cards.netlify.app/)

## Entrega
Suba o seu projeto para um novo repositório no seu GitHub pessoal. Certifique-se de que o código está limpo, sem pacotes não utilizados e pronto para revisão.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |