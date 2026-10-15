# NIGHTRUN

Painel responsivo para gestão de pedidos, funcionários, clientes salvos, valor total e integração com webhook do Discord.

## Iniciar no GitHub Codespaces
1. Na pasta do projeto execute `npm install`.
2. Crie a configuração com `cp .env.example .env`.
3. Abra `.env` e preencha `SESSION_SECRET` com uma frase longa e aleatória e `DISCORD_WEBHOOK_URL` com o webhook privado do canal desejado.
4. Execute `npm start` e abra a porta 3000 na aba Ports/Portas.
5. Crie o primeiro usuário pela opção Cadastre-se; a primeira conta será administradora. As contas seguintes serão funcionários.

Os dados são guardados em `data/nightrun.sqlite`. Não compartilhe `.env` nem o webhook. O código de confirmação é mostrado no próprio site e expira em 10 minutos; para uso público real, implemente verificação externa e configure HTTPS e armazenamento persistente de sessões.
