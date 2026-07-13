# hotsite

Hotsite pessoal de **Bruno de Lima** — Head of AI Transformation.

Site estático, sem build, que **se adapta à faixa etária** de quem entra. A página inicial (`index.html`) pergunta a idade e direciona para uma de cinco experiências distintas.

🔗 **www.brimes.net**

## Páginas

| Faixa | Arquivo | Estilo |
|---|---|---|
| entrada | `index.html` | Porta que pergunta a faixa etária |
| 0–12 | `kids.html` | Infantil e colorido — brincadeiras fora das telas |
| 12–18 | `teen.html` | Jovem — carreira e a história do Bruno aos 14/16/17 |
| 18–35 | `pro.html` | Portfólio profissional (bilíngue PT/EN) + foto |
| 35–60 | `retro.html` | Mesmas infos em visual retrô anos 80/90 |
| 60+ | `jornal.html` | Preto e branco, estilo jornal antigo |

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
