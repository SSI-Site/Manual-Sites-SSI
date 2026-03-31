# O Site Principal (Site-SSI)

O Site-SSI é uma aplicação web construída em Next.js (React) focada em entregar uma excelente experiência para o participante do evento. Ele precisa ser bonito, escalável e aguentar o pico de acessos durante a semana da SSI.

## Estrutura e Páginas Principais
Analisando a arquitetura do nosso projeto, o site é dividido nas seguintes rotas principais (localizadas na pasta `pages/`):

* **Home (`index.js`):** A vitrine do evento, com as informações de maior impacto e os patrocinadores em destaque.
* **Sobre (`about.js`):** Conta a história e os propósitos da SSI.
* **Programação (`schedule.js`):** O coração da consulta pública, listando todas as atividades da semana separadas por dia.
* **Palestrantes (`palestrantes.js`):** Uma galeria dedicada a apresentar quem vai ministrar os conteúdos.
* **Comissão Organizadora (`co.js`):** Apresenta as equipes e membros por trás da construção do evento.
* **Área do Usuário (`user.js`):** Um ambiente logado exclusivo para o aluno inscrito.

## Funcionalidades Chave (Componentes)

Através da nossa pasta `src/components/`, encapsulamos regras de negócio complexas:

1. **Autenticação e Área Logada:** O site possui um sistema de login (`AuthModal`) que libera o acesso à área do usuário. Lá, o aluno consegue ver seu progresso de engajamento (`UserWatchedLecturesList`) e o status dos brindes que ele já desbloqueou (`UserGiftCard`).
2. **Cartões Dinâmicos:** Usamos extrema componentização para renderizar a grade do evento de forma organizada, como os cartões de palestra (`LectureCard`), de palestrantes (`SpeakerCard`) e os carrosséis de parceiros (`PartnerCard`).

## O Site após o Evento (Versão Genérica)
Para não deixar o domínio desativado após o fim da semana, mantemos uma "versão de prateleira". Nela, funcionalidades interativas pesadas (como a página do usuário, `user.js`, e modais de login) são escondidas, e a página passa a focar apenas no registro histórico da edição (quem patrocinou, quem palestrou, etc.).

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |