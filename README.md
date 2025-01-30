# supabase
Criação de um webhook no supabase via Edge Functions em TypeScript


1. Instalar o supabase CLI no Windows ou Linux (cmd/prompt/terminal/powershell):

npm install -g supabase
ou
npm install supabase --save-dev -->(executar comando direto na pasta local onde irá criar a função)

2. Execute o comando init para iniciar, dentro da pasta local
npx supabase init 

3. Fazer login no supabase
npx supabase login

4. Alterar o index.ts com o código do GIT.

5. Executar o deploy dentro do supabase:
npx supabase functions deploy saveTypeFormWebhook --project-ref xyniruiylngpiffzxoxl

6. Caso queira remover a autorização de token, faça dentro do supabase, dentro da função:
Enforce JWT Verification
Require a valid JWT in the authorization header when invoking the function
