# Terra Axial — Página de Cronologia

Pacote responsivo para hospedagem em GitHub Pages, Netlify, Vercel ou uso em iframe.

## Arquivos

- `index.html`: estrutura da página.
- `styles.css`: identidade holográfica, responsividade e animações.
- `chronology-data.js`: conteúdo canônico integral de 9000 A.R. a 12 D.R.
- `app.js`: busca, filtros, navegação, leitura progressiva, menu móvel e transições.
- `assets/`: artes vetoriais locais usadas nos cards e painéis.
- `cronologia-standalone.html`: versão com CSS e JavaScript incorporados em um único HTML.

## Publicação em iframe

1. Envie toda a pasta para um repositório público.
2. Ative o GitHub Pages na raiz do projeto.
3. Use a URL final de `index.html` como origem do iframe.
4. Para Tumblr, o iframe deve usar `width="100%"`, altura suficiente e `border="0"`.

## Personalização rápida

- Logo e links: início de `index.html`.
- Cores: bloco `:root` em `styles.css`.
- Imagens dos quatro volumes: objeto `visualMap` em `app.js`.
- Texto: `chronology-data.js`.

## Atualização de leitura

- Textos narrativos justificados com hifenização em português.
- Ritmo tipográfico otimizado nos cards, registros, conclusão e nota de continuidade.
- Efeito analógico global com separação cromática sutil, brilho de fósforo e oscilação de sinal.
- O controle `FX` e a preferência `prefers-reduced-motion` desativam a oscilação tipográfica.

- Textos narrativos justificados sem hifenização automática; palavras sempre inteiras.


## Imagens oficiais da cronologia

- Livro I: https://i.imgur.com/0QDCRQs.png
- Livro II: https://i.imgur.com/QUdMzqd.png
- Livro III: https://i.imgur.com/ufqCiNt.png
- Livro IV: https://i.imgur.com/xrh2f6H.png
- Encerramento do Vigia: https://i.imgur.com/FG0C553.png
