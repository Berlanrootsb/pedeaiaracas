
PEDE AI ARACAS - KIT FINAL 100% SUPABASE SEM LOCALSTORAGE

ESTRUTURA:
- index.html (raiz) = Vitrine publica (todas lojas)
- /admin/index.html = Admin que cria lojas direto na Supabase
- /login/index.html = Login dinamico (slug + senha lido da Supabase)
- /painel/index.html = Painel lojista que le ?loja= da URL
- /vitrine/index.html = Copia da vitrine

COMO SUBIR NO HOST:
1. Upload index.html na raiz
2. Upload admin/index.html em /admin/
3. Upload login/index.html em /login/
4. Upload painel/index.html em /painel/

TESTE:
- login: maria-pastel / maria123
- login: berlan-burger / berlan123

SUPABASE:
URL: https://bgsuefrrtjhzidxmtnak.supabase.co
Tabelas: lojas, produtos, pedidos, cupons

FLUXO:
Vitrine -> POST /pedidos {loja_slug} -> Painel filtra por loja_slug -> WhatsApp da loja
