# Aquarela · site

Página estática (HTML + CSS + JS), pronta para a Vercel. Não precisa de build.

## Antes de publicar
1. Abra `index.html` e procure `const CONTACT`:
   - `booking`: cole o link de agendamento (Calendly, Cal.com…)
   - `email`: cole o e-mail de contato
2. `SPOTS_TAKEN`: número de vagas do Founding Five já preenchidas.
3. Se o domínio final não for aquareladesign.com, troque as duas URLs `og:image` e `og:url` no topo do `index.html`.

## Publicar
- Pelo terminal: `npx vercel` dentro desta pasta (primeira vez) e `npx vercel --prod` para produção.
- Ou suba a pasta para um repositório no GitHub e importe em vercel.com/new (Framework: Other, sem build).

## Estrutura
- `index.html`: a página
- `media/`: vídeos (MP4)
- `images/`: fotos, capas dos vídeos e logos
- `og.jpg`: imagem de prévia para links compartilhados
- `favicon.svg`: o A da Aquarela
- `vercel.json`: cache longo para mídia
