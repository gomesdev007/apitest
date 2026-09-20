# Gomes Hub V3

ESTA É A VERSÃO COMPLETA.

Estrutura:
- api/licenses.js
- api/stats.js
- public/index.html
- GomesHub.lua
- package.json

Não existe `vercel.json` nesta versão.

## Vercel
As funções em `api/` são detectadas automaticamente.

Variáveis necessárias:
- SUPABASE_URL
- SUPABASE_SERVICE_ROLE_KEY
- ADMIN_TOKEN

Não coloque a chave secreta do Supabase no Lua ou no frontend.
