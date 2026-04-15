# Instalação das Ferramentas Base

Antes de baixar o código do projeto, você precisa preparar o seu ambiente de desenvolvimento. Siga este passo a passo para instalar todas as ferramentas necessárias.

## 1. Conta no GitHub
Caso ainda não tenha, acesse o [GitHub](https://github.com/) e crie sua conta. 
*Dica: Adicione o seu e-mail USP como secundário, pois o GitHub oferece diversos benefícios gratuitos para estudantes no pacote GitHub Student Developer Pack.*

## 2. Node.js e NPM
O Node.js é o ambiente de execução do JavaScript que permite rodar o Next.js e o React na sua máquina. O NPM é o gerenciador de pacotes que vem junto com ele.

* **Windows e MacOS:** Acesse o [site oficial do Node.js](https://nodejs.org/), baixe o instalador da versão LTS (Long Term Support) e siga as instruções padrão.
* **Linux:** Recomendamos instalar via gerenciador de pacotes. Consulte as [instruções oficiais para Linux](https://nodejs.org/en/download/package-manager).

**Como testar se deu certo:**
Abra o seu terminal (ou prompt de comando) e digite:
```bash
npm --version
```
Se o comando retornar um número (ex: `8.19.3`), a instalação foi um sucesso.

## 3. Yarn (Gerenciador de Pacotes Oficial)
No projeto do Site-SSI, utilizamos o **Yarn** para gerenciar as dependências. Ele garante que todos os desenvolvedores utilizem exatamente as mesmas versões de bibliotecas, evitando erros de compilação.

**Como instalar:**
Com o Node.js já instalado, rode o seguinte comando no seu terminal:
```bash
npm install --global yarn
```

**Como testar:**
```bash
yarn --version
```

> ⚠️ **Atenção:** Nunca utilize o comando `npm install` dentro da pasta do projeto Site-SSI. Isso gera um arquivo de trava diferente e causa conflitos no repositório. Use sempre apenas o comando `yarn`.

## 4. Git e GitHub Desktop
O Git é a ferramenta de versionamento que usamos para gerenciar o código.

* **Instalação do Git:** Acesse o [site oficial do Git](https://git-scm.com/downloads) e baixe a versão para o seu sistema operacional.
* **Configuração Inicial:** Após instalar, configure seu nome e e-mail no terminal:
  ```bash
  git config --global user.name "Seu Nome"
  git config --global user.email "seuemail@exemplo.com"
  ```

  Para mais informações acesse [Configuração Inicial do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git).

* **GitHub Desktop (Opcional, mas recomendado):** Se você não tem familiaridade com comandos de terminal, o [GitHub Desktop](https://desktop.github.com/) oferece uma interface visual amigável para criar branches, fazer commits e gerenciar as Pull Requests.

## 4. Terminal da IDE (VS Code)
Além do terminal do sistema operacional, você também pode executar todos os comandos do projeto no terminal integrado da sua IDE, como o do VS Code.

Abra o terminal em **Terminal > New Terminal** (atalho: `Ctrl + J`) e rode os comandos por lá (`git`, `yarn`, etc.). Essa abordagem facilita o fluxo, pois você edita os arquivos e executa o site na mesma janela.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI.

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |
| 15/04/2026 | [Douglas Macedo](https://github.com/doug1412) | Adição da etapa de instalação do Yarn e avisos de compatibilidade. |