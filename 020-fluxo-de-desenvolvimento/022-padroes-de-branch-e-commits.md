# Padrões de Branch e Commits

Trabalhar em equipe exige organização no Git. Nunca codificamos diretamente na branch `main`, pois ela é protegida e representa a versão oficial do projeto.

## 1. Padrão de Nomenclatura de Branches

Toda nova tarefa exige a criação de uma branch específica. Adotamos o padrão **kebab-case em minúsculo**, utilizando nomes curtos e descritivos relacionados à feature.

* ❌ **Errado:** `MinhaBranch`, `modal de login`, `nova_navbar`
* ✅ **Correto:** `navbar`, `section-1-deslogada`, `token-modal`

**Obs.:** Também é possível criar a branch diretamente pela task no GitHub Projects. Nesse fluxo, o GitHub sugere e cria automaticamente um nome de branch.

**Atenção antes de criar:** Sempre execute um `git fetch` e `git pull` na branch `main` antes de ramificar, garantindo que você está partindo do código mais atualizado.

## 2. Padrões de Desenvolvimento (Figma e Mobile First)

Nós desenvolvemos com o Figma aberto lado a lado com o editor de código. É fundamental respeitar o Design System (fontes, cores, espaçamentos).

* **Mobile First:** Comece desenvolvendo sempre para telas de celular (Design Mobile) e use *Media Queries* progressivas para adaptar até o desktop.
* **Medidas relativas:** Evite usar medidas absolutas como `px` (pixels) para tamanhos e margens. Utilize `rem`, que é relativo e melhora a acessibilidade e a escalabilidade do layout.

## 3. Padrões de Commit

Faça commits frequentes e com mensagens claras que expliquem o que foi feito.
Se a tarefa foi desenvolvida em dupla, não esqueça de usar o recurso de **co-authored commit** (commits com coautores) para que ambos recebam os créditos no GitHub.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |