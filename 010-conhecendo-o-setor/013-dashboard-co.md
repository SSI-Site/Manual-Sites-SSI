# Plataforma da Comissão Organizadora (CO-Dashboard)

Enquanto o site principal foca no público externo, o `CO-Dashboard` é o painel de controle logístico da SSI. Também construído em Next.js, ele foca em segurança, confiabilidade e acesso rápido à manipulação de dados pelos membros da organização durante o calor do evento.

## Autenticação Segura
O acesso ao painel é estritamente restrito. Ele utiliza uma camada de proteção global (`AuthContext` e `useAuth`) para garantir que apenas administradores da CO consigam visualizar as telas e realizar ações críticas.

## Estrutura e Ferramentas (Páginas)
Observando a organização das rotas (`pages/`), o painel entrega um leque muito maior de ferramentas de controle comparado ao site principal:

* **Gestão de Alunos (`students.js` e `studentView.js`):** Permite listar todos os inscritos e visualizar o detalhamento individual (como buscar um aluno por e-mail para checar quantas presenças ele tem).
* **Registro Presencial (`presential.js`):** Uma interface ágil, geralmente usada no celular ou no notebook na porta do auditório, para dar "check-in" manual nos alunos presentes fisicamente.
* **Controle de Palestras (`talks.js` e `talkForm.js`):** Onde a organização cadastra os horários, edita informações em tempo real e acompanha o status de cada atividade.
* **Geração de Tokens (`token.js`):** A ferramenta vital para as *lives*. É aqui que a CO gera o código que os alunos usarão no site principal (`TokenModal`) para computar as presenças online.
* **Sorteios e Ganhadores (`giveaway.js` e `winners.js`):** Um módulo dedicado a cruzar a base de alunos presentes, rodar um cronômetro e realizar sorteios ao vivo, guardando o histórico de quem ganhou.
* **Controle de Brindes (`gifts.js`):** Gestão visual do estoque ou do desbloqueio de recompensas baseadas na participação.

## Domínio e Acesso

A plataforma da CO não requer a compra de um domínio isolado. Utilizamos o próprio domínio do site principal através da configuração de um subdomínio (prefixo). 

* **Exemplo de acesso:** `co-dashboard.semanadesi.com`

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |