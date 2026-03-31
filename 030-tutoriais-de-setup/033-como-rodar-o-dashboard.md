# Como rodar a CO-Dashboard localmente

O processo para rodar a plataforma da Comissão Organizadora é quase idêntico ao do site principal, mas os repositórios e chaves de ambiente são separados por questões de segurança.

## 1. Clonar o Repositório
Abra o terminal na pasta onde deseja salvar o projeto e execute:

```bash
git clone https://github.com/SSI-Site/CO-Dashboard-SSI.git
```

### Alternativa via GitHub Desktop
Se preferir interface gráfica, o clone também pode ser feito pelo GitHub Desktop:

1. Abra o GitHub Desktop.
2. Clique em **File > Clone repository...**.
3. Na aba **URL**, cole `https://github.com/SSI-Site/CO-Dashboard-SSI.git`.
4. Escolha a pasta local onde o repositório será salvo.
5. Clique em **Clone**.

## 2. Configurar Variáveis de Ambiente
A CO-Dashboard possui variáveis específicas para acessar as tabelas administrativas do banco de dados.

1. Entre na pasta do projeto clonado.
2. Crie um arquivo na raiz chamado `.env.local`.
3. Solicite as chaves exclusivas da Dashboard ao diretor do setor e cole neste arquivo.

## 3. Instalar as Dependências e Rodar
Dentro da pasta do projeto no terminal, instale os pacotes:

```bash
yarn install
```

E suba o servidor de desenvolvimento:

```bash
yarn dev
```

Assim como no Site-SSI, você pode executar tudo no terminal integrado da IDE.
No VS Code, abra em **Terminal > New Terminal** (atalho: `Ctrl + J`), entre na pasta do projeto e execute os comandos normalmente.

## 4. Acessar a Plataforma
Abra o seu navegador e acesse:
**[http://localhost:3000/](http://localhost:3000/)**

*Nota:* Como as duas aplicações (Site e Dashboard) utilizam a porta `3000` por padrão, não é possível rodar as duas simultaneamente sem alterar a porta de uma delas. Se precisar rodar as duas ao mesmo tempo, você pode iniciar uma delas passando uma porta diferente no terminal (ex: `yarn dev -p 3001`).

No terminal do VS Code, você pode deixar uma aba para o Site-SSI e outra para a Dashboard, cada uma com sua porta, para testar os dois projetos em paralelo.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |