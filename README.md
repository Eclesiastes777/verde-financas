# Verde Finanças Online

Aplicativo de controle financeiro — preparação para GitHub + Vercel + Supabase.

## Situação
Este repositório é público. **Não coloque senhas, tokens, backups, lançamentos financeiros ou chaves secretas nele.**

A hospedagem na Vercel **ainda não foi publicada**. O aplicativo online ainda depende da integração do login e da sincronização.

## Preparação do Supabase
1. Crie um projeto Supabase.
2. Execute `supabase/schema.sql` no SQL Editor.
3. Ative autenticação por e-mail.
4. Configure no aplicativo apenas a URL e a chave **publishable/anon** do projeto. Nunca use a chave `service_role`.
5. Antes de importar dados reais, teste login, isolamento entre usuários e sincronização.

## Próximas etapas
- Integrar o HTML do Verde Finanças 2.2 ao Supabase Auth e à tabela `finance_data`.
- Testar backup, importação e conflitos entre dispositivos.
- Preparar a implantação na Vercel e solicitar aprovação explícita antes de publicar.
