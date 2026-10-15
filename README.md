# MV Paula Dias — Clínica Veterinária 24h

Site institucional da Clínica Veterinária MV Paula Dias 24hrs (QN 305, Samambaia, Brasília-DF).

Site estático (HTML + CSS + JS, sem build), pronto para GitHub Pages.

## Estrutura

- `index.html` — página única (serviços, internação, avaliações, localização, FAQ)
- `assets/css/style.css` — estilos; cores da logo em `:root` (verde `#005142`, dourado `#E4D096`)
- `assets/js/main.js` — menu mobile, "ler mais" das avaliações e animações
- `assets/img/` — imagens usadas no site
- `fotos/` — fotos originais enviadas pela clínica
- `dados/google-maps.json` — dados extraídos do Google Maps (endereço, nota, avaliações)

## Rodar localmente

```bash
python3 -m http.server 8000
```
