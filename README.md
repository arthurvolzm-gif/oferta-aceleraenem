# Oferta Acelera Enem

Página de vendas do Acelera Enem, publicada em `metodoaceleraenem.vercel.app`.

- `index.html`: a página inteira (HTML, CSS e JS num arquivo só, sem build).
- `img/`: páginas reais do material (`topico-1` a `topico-12`) e o print usado na seção "A estrutura de cada tema" (`anatomia-tema`).
- Links de checkout, Pixel e datas do ENEM ficam no objeto `window.OFERTA`, no topo do `index.html`.
  Plano Pro (R$ 29,90), Essencial (R$ 14,90) e Pro pelo pop-up (R$ 19,90) têm cada um o seu checkout na Zuptos.

Origem: a página foi desenvolvida em `arthurvolzm-gif/app-enem` (`/oferta`). As imagens saem dos PDFs gerados por `materiais/gerar-flash.cjs` daquele repositório.
