# Como rodar o Site-SSI localmente

Com as ferramentas base instaladas, você já pode baixar e rodar o projeto principal da SSI na sua máquina.

## 1. Clonar o Repositório
Abra o terminal na pasta onde você deseja guardar os projetos do DASI e execute o seguinte comando para baixar o código:

```bash
git clone https://github.com/SSI-Site/Site-SSI.git
```

### Alternativa via GitHub Desktop
Se preferir interface gráfica, você também pode clonar sem usar comando:

1. Abra o GitHub Desktop.
2. Clique em **File > Clone repository...**.
3. Na aba **URL**, cole `https://github.com/SSI-Site/Site-SSI.git`.
4. Escolha a pasta local onde o repositório será salvo.
5. Clique em **Clone**.

## 2. Configurar Variáveis de Ambiente
O projeto precisa de algumas chaves de segurança (como as credenciais do Firebase) para funcionar corretamente. 

1. Entre na pasta do projeto que você acabou de clonar.
2. Crie um arquivo na raiz da pasta chamado exatamente `.env.local`.
3. Solicite o conteúdo deste arquivo ao diretor do setor e cole dentro dele. ***(Nunca faça commit deste arquivo no GitHub!)***

## 3. Instalar as Dependências e Rodar
No terminal, certifique-se de que você está dentro da pasta do projeto e execute a instalação dos pacotes utilizando o **Yarn** (nosso gerenciador de pacotes padrão):

```bash
yarn install
```

Após a conclusão da instalação, inicie o servidor de desenvolvimento:

```bash
yarn dev
```

Você pode executar esses comandos tanto no terminal do sistema quanto no terminal integrado da IDE.
No VS Code, use **Terminal > New Terminal** (atalho: `Ctrl + J`), navegue até a pasta do projeto e rode os mesmos comandos.

## 4. Acessar o Site
O terminal indicará que o servidor está rodando. Abra o seu navegador e acesse:
**[http://localhost:3000/](http://localhost:3000/)**

Enquanto você estiver programando, deixe a janela do terminal aberta. Se você fechá-la, o site local cairá.

Se estiver usando o terminal do VS Code, mantenha a aba do terminal de desenvolvimento ativa durante os testes locais.

---

## 📝 Histórico de Revisões

Este documento é vivo e mantido pelas gestões do Setor de Sites da SSI. 

| Data | Autor(a) | Resumo da Alteração |
| :--- | :--- | :--- |
| 31/03/2026 | [Douglas Macedo](https://github.com/doug1412) | Adaptação para arquivos MD. |