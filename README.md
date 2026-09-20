# Gomes Hub — Vercel

Esta versão remove a configuração de runtime que causava o erro de detecção de PHP/AVA.

## Importante
Por segurança, a Vercel ainda precisa receber três variáveis secretas no projeto:
- SUPABASE_URL
- SUPABASE_SERVICE_ROLE_KEY
- ADMIN_TOKEN

Não existe forma segura de embutir a service-role key no ZIP/frontend.

O banco e a Edge Function do projeto Supabase já foram preparados na conversa.

## Deploy
Importe esta pasta/repositório na Vercel como projeto Node/Serverless. Não selecione PHP.

O `vercel.json` não declara runtime; a Vercel detecta `api/*.js` automaticamente.

Depois de definir as três variáveis, faça Redeploy.
