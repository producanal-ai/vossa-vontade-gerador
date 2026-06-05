# Vossa Vontade — Gerador de Criativos

App gerador de prompts para criativos de artigos religiosos católicos.

## Deploy no Vercel

1. Faça upload deste projeto no GitHub
2. Acesse vercel.com e importe o repositório
3. Em **Environment Variables**, adicione:
   - Nome: `ANTHROPIC_API_KEY`
   - Valor: sua chave da Anthropic (console.anthropic.com)
4. Clique em Deploy

## Estrutura
- `public/index.html` — App principal
- `api/generate.js` — Backend seguro (protege a chave de API)
- `vercel.json` — Configuração do Vercel
