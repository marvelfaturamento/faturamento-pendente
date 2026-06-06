# Painel 902 refatorado real v1

Base: Painel 902 v12.2 Paginação Supabase(9).html.

Alterações:
- CSS extraído para css/painel902.css.
- JavaScript extraído para js/app.js.
- Bibliotecas Supabase e XLSX via CDN.
- Tabelas pré-renderizadas removidas do HTML inicial.
- Paginação visual de 50 linhas por tabela no renderTable.

Como subir:
- Subir o conteúdo desta pasta na raiz do repositório.
- Manter as pastas css/ e js/.
- Testar primeiro em Vercel de homologação.


## v3 - regra exportação sem regra padrão
- Casos sem regra padrão, com UF destino EX, quando a UF da posição em BRASIL divergir da UF do remetente, sobem automaticamente para Alerta internacional expo.
