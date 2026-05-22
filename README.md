# Site Combustão - Ambiente de Teste

Este projeto contém duas páginas HTML:

- `index.html` — Página principal com conteúdo hero e formulário de demonstração.
- `demonstracao.html` — Página de inscrição corporativa com formulário completo.

## Como iniciar o servidor de teste

1. Abra o terminal na pasta `c:\Users\david\Downloads\siteCOmbustao`
2. Execute:

```bash
npm install
npm start
```

3. Acesse o site no navegador via:

- `http://localhost:8080/index.html`
- `http://localhost:8080/demonstracao.html`

## Acesso via IP de rede

Para testar em outro dispositivo da rede local, use o IP da sua máquina. Exemplo:

- `http://192.168.x.x:8080/index.html`
- `http://192.168.x.x:8080/demonstracao.html`

> O servidor já está configurado para `0.0.0.0`, então ele aceita conexões do seu subnet local.

## Deploy no Vercel

Este é um site estático. Para publicar no Vercel:

1. Crie um repositório Git privado no GitHub.
2. Faça `git push` para esse repositório.
3. No Vercel, importe o repositório e conecte-o ao projeto.

O arquivo `vercel.json` já está incluído para servir `index.html` como página inicial.

## Ajustes aplicados

- Corrigido o mapeamento de links âncora em `index.html` (`#hero`, `#features`, `#ingredients`).
- Adicionadas meta tags de descrição e melhor renderização em mobile.
- Otimização de imagens e responsividade para desktop e mobile.
- Pequenas melhorias de usabilidade e acessibilidade.
