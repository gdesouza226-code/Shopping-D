SHOPPING D + ARGOPLAN — VERSÃO FINAL

ESTRUTURA:
- index.html = LINK PÚBLICO. Pessoas podem pesquisar lojas e ver vagas. NÃO existe botão de administração.
- admin.html = LINK ADMINISTRATIVO. Exige login e permite:
  • adicionar lojas
  • excluir lojas
  • alterar quantidade de vagas
- config.js = conexão com o Supabase já preenchida.
- setup_supabase.sql = configuração do banco e carga inicial das lojas.
- argoplan-shoppingd.png = logo.

LOGIN ADMINISTRATIVO:
E-mail: admin@shoppingd.com.br
Senha: argoplangabriel2026

PARA FUNCIONAR EM TODOS OS DISPOSITIVOS:
1. No Supabase, abra SQL Editor.
2. Cole TODO o conteúdo de setup_supabase.sql.
3. Clique RUN.
4. Publique estes arquivos no GitHub Pages.

DEPOIS DE PUBLICADO, VOCÊ TERÁ DOIS ENDEREÇOS:
PÚBLICO:
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/

ADMINISTRATIVO:
https://SEU-USUARIO.github.io/NOME-DO-REPOSITORIO/admin.html

O público não possui botão ou link para a página administrativa.
As alterações feitas no admin ficam no Supabase e aparecem no link público em qualquer dispositivo.


CORREÇÃO APLICADA:
- pgcrypto configurado no schema extensions.
- crypt() corrigido para extensions.crypt().
- gen_salt() corrigido para extensions.gen_salt().

AGORA:
1. Abra setup_supabase.sql.
2. Ctrl+A e Ctrl+C.
3. Cole no SQL Editor do Supabase.
4. Clique Run.
