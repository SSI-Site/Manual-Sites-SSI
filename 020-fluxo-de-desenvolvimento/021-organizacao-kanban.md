# Organização e Kanban

Para gerenciar nossas tarefas e o progresso do desenvolvimento, utilizamos o **GitHub Projects** no formato Kanban, inspirado na metodologia ágil Scrum.

Este quadro é a nossa fonte da verdade sobre o que precisa ser feito, quem está fazendo e qual o status de cada página ou componente.

## Colunas do nosso Quadro

O quadro é dividido nas seguintes etapas:

* `Backlog:` Tarefas mapeadas, mas que ainda não estão prontas ou detalhadas o suficiente para o desenvolvimento.
* `Ready:` Tarefas especificadas e liberadas para os desenvolvedores assumirem.
* `In progress:` Tarefas atualmente em desenvolvimento, indicando os responsáveis e o prazo.
* `In review:` Código pronto e com Pull Request (PR) aberta, aguardando revisão da diretoria/liderança técnica.
* `Done:` Tarefas revisadas, aprovadas e integradas (merge) ao código principal do site.

## Como assumir uma Task (Tarefa)

O desenvolvimento é autogerenciado. Os membros devem puxar as tasks da coluna `Ready`. O trabalho em dupla (Pair Programming) é super encorajado! 

Ao escolher uma task, siga estes passos:

1. **Atribuição:** Atribua o card a você (em *Assignees*).
2. **Movimentação:** Arraste o card de `Ready` para `In Progress`.
3. **Prazos:** Defina a data de início (*Start date*) para o dia atual e a data de entrega (*End Date*) para, no máximo, **duas semanas** à frente.
4. **Contexto:** Leia atentamente a descrição do card, pois nela estarão regras, dicas e diretrizes importantes para o desenvolvimento daquela interface específica.
5. **Crie a branch para a task:** Crie a branch a partir da `main` atualizada. Se preferir, você pode criar a branch direto pelo card no GitHub Projects, que já sugere um nome automaticamente.
6. **Desenvolva a task:** Implemente o que foi pedido seguindo o Figma e os padrões do setor. Faça commits frequentes e com mensagens claras para facilitar a revisão.
7. **Abra a Pull Request:** Faça `git push`, abra a PR para a `main`, solicite revisão (conta técnica `SSI-Site` ou da liderança) e mova o card para `In review`.

---

## 📝 Histórico de Revisões
Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |
