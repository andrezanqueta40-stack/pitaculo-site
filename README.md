# Pitáculo — Site

Site institucional da Pitáculo (criação de sites profissionais). Arquivo único: `index.html`.

## Antes de publicar
Abra o `index.html` e procure por `var WHATS=""` perto do final. Coloque o número do WhatsApp com DDD, sem espaços:

    var WHATS="5535999999999";

Assim o formulário de orçamento abre a conversa direto no WhatsApp.

## Como publicar no GitHub Pages
1. Crie um repositório novo no GitHub (ex.: `pitaculo-site`).
2. Clique em **Add file > Upload files** e envie `index.html` e `.nojekyll`.
3. Vá em **Settings > Pages**.
4. Em **Source**, escolha **Deploy from a branch**, branch `main` e pasta `/ (root)`, e salve.
5. Em 1 a 2 minutos o site abre em `https://SEU-USUARIO.github.io/pitaculo-site/`.

## Domínio próprio
Em **Settings > Pages > Custom domain**, informe o domínio e aponte o DNS conforme a orientação do GitHub.
