# Passo a Passo: Pull Request e Revisão

A Pull Request (PR) é o momento onde o seu código é enviado para avaliação antes de ser juntado ao projeto principal. Esse fluxo garante a qualidade e evita que quebremos o site em produção.

## Como abrir e gerenciar sua PR

Quando você finalizar o desenvolvimento e realizar o `git push` da sua branch local para o GitHub, siga este processo:

1. **Abertura:** Crie a Pull Request apontando a sua branch para a `main`.
2. **Revisão:** Ao criar a PR, você deve obrigatoriamente solicitar a revisão da conta técnica do setor (`SSI-Site`) ou do líder/diretor responsável.
3. **Atualização do quadro Kanban:** Volte no GitHub Projects e mova o seu card da coluna *In Progress* para **In Review**.
4. **Mapeamento de tempo:** Edite o título do seu card no Kanban incluindo o tempo aproximado que você gastou desenvolvendo aquela tarefa. Isso ajuda a gestão a metrificar o esforço do time.
   * *Exemplos:* `Navbar | 4h` ou `[Componente] TokenModal | 40m`.

## O Processo de Feedback

Se o código estiver fiel ao design (Figma) e seguir as boas práticas arquiteturais, a PR será aprovada (merge) e o card irá automaticamente (ou manualmente) para a coluna **Done**.

Caso contrário, o responsável pela revisão deixará comentários na PR apontando os ajustes necessários. Neste caso:

1. O card retorna para a coluna **In Progress**.
2. Você realiza as correções na sua branch local, commita e faz o push novamente.
3. A PR é atualizada sozinha, e o código entra em revisão mais uma vez.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |