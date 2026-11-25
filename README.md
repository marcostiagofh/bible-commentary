# Navegador local da Bíblia e comentários

Aplicação web local para navegar, pesquisar e ouvir o texto bíblico e seus comentários.

## Instalação

Na primeira execução:

```bash
npm install
```

## Executar

```bash
npm start
```

Depois, acesse:

```text
http://127.0.0.1:3000
```

O comando equivalente, sem o atalho do npm, é:

```bash
node local_bible_browser_server.js
```

Se a porta 3000 estiver ocupada:

```bash
PORT=3001 npm start
```

O servidor Express entrega os arquivos da pasta `public/` e mantém disponíveis as rotas locais em `/api`.

[Demonstração](https://marcostiagofh.github.io/bible-commentary/public/)
