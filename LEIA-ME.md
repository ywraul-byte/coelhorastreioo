# Coelho Rastreia — arquivos do site

Este pacote contém o código-fonte, imagens, testes e migrações do site.
Não é um aplicativo instalável: para usar sem instalação, acesse https://coelho-rastreia-caminho.lovable.app.

## Executar localmente

1. Instale Node.js e Bun.
2. Abra esta pasta no terminal e execute `bun install`.
3. Configure as variáveis públicas de conexão do Lovable Cloud em um arquivo `.env` local: `VITE_SUPABASE_URL`, `VITE_SUPABASE_PUBLISHABLE_KEY` e `VITE_SUPABASE_PROJECT_ID`.
4. Execute `bun run dev` e abra o endereço exibido no terminal.

O login, os pedidos e a equipe dependem do Lovable Cloud. O ZIP não contém senhas, sessões, dados de clientes nem uma cópia do banco de dados. As migrações documentam a estrutura; não as execute no banco ativo sem revisão técnica. Publicar em outra hospedagem exige configurar o ambiente e os endereços permitidos de autenticação.
