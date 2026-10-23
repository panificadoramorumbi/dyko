# Publicar Panificadora Morumbi Dyko no GitHub Pages

Este projeto foi preparado para o repositório `panificadoramorumbi.github.io/dyko/`.

1. Envie **todos os arquivos e pastas deste ZIP** para a raiz do repositório `dyko` no GitHub. Não envie o ZIP fechado; extraia-o primeiro.
2. Confirme que a pasta `.github/workflows/deploy.yml` também foi enviada. Se o GitHub não mostrar pastas iniciadas por ponto, ative a exibição de arquivos ocultos ou envie pelo Git.
3. Abra `Settings > Pages` e selecione **GitHub Actions** como Build and deployment source.
4. Abra a aba `Actions`, espere o fluxo `Deploy to GitHub Pages` terminar com sucesso.
5. Acesse `https://panificadoramorumbi.github.io/dyko/`.

O projeto usa Firebase. No Firebase Console, confirme que `panificadoramorumbi.github.io` está em Authentication > Settings > Authorized domains, e confira as regras do Firestore para o banco configurado no projeto. Não torne as regras públicas para “resolver” erros de permissão.
