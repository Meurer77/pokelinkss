# PokéLinks

PokéLinks é um jogo de conexões inspirado no formato de 16 Pokémon e 4 grupos.

## Publicar no GitHub Pages

1. Crie um repositório público chamado `pokelinks`.
2. Envie todos os arquivos desta pasta para a raiz do repositório.
3. Abra **Settings → Pages**.
4. Em **Build and deployment**, selecione **Deploy from a branch**.
5. Escolha a branch `main` e a pasta `/ (root)`.
6. Salve e aguarde o GitHub Pages publicar.

O endereço normalmente ficará parecido com:
`https://SEU-USUARIO.github.io/pokelinks/`

## Arquivos

- `index.html` — jogo principal.
- `404.html` — página personalizada para rotas inexistentes.
- `favicon.svg` — ícone do site.
- `manifest.webmanifest` — instalação como aplicativo/PWA.
- `sw.js` — cache básico para carregamento offline do shell do site.
- `robots.txt` — instrução básica para buscadores.

## Observações

As imagens e dados dos Pokémon são carregados pela PokéAPI em tempo de execução. O jogo não contém os arquivos de arte dos Pokémon no repositório.
