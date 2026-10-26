# Partitool

Site público Clave Sol: https://partitool.clavesol.com.br/

Escreva a apresentação em `content/apresentacao.md`. Edite também `site.json`, `content/index.md`, `content/privacy.md` e `content/contact.md`. Ao fornecer a política definitiva, marque `privacy_ready` como `true` em `site.json`.

Instalar dependência: `python3 -m pip install -r requirements.txt`

Gerar: `python3 build.py`

Visualizar: `python3 -m http.server 8000 --directory dist`

Publicação: Actions → Publicar aplicativo → Run workflow. O primeiro commit usa `[skip ci]`; pushes posteriores em main publicam automaticamente.

DNS: CNAME do subdomínio apontando para `djamessuhanko.github.io` (somente DNS). Em Settings → Pages, habilite Enforce HTTPS quando o certificado estiver pronto.

Publique apenas conteúdo público. Nunca inclua chaves de assinatura, credenciais ou dados de usuários.
