# hotsite

Hotsite pessoal de **Bruno de Lima** — Head of AI Transformation.

Site estático de página única (portfólio + carreira), bilíngue **PT/EN**, sem build e auto-contido em um único `index.html`.

🔗 **brimes.net**

## Stack

- HTML + CSS + JavaScript puro (zero dependências de build)
- Fontes: Space Grotesk + Inter (Google Fonts)
- i18n PT/EN com toggle e persistência via `localStorage`
- Animações de reveal com `IntersectionObserver`
- Responsivo (desktop / tablet / mobile)

## Rodar localmente

Basta abrir o arquivo no navegador:

```bash
open index.html
```

## Deploy

Por ser 100% estático, pode ser publicado em qualquer host de arquivos estáticos
(Cloudflare Pages, GitHub Pages, Netlify, etc.) apontando para a raiz do projeto.
