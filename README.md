# Totsik — site

Site do DJ **Totsik** (Ayrton Siqueira) — São Paulo, BR.
HTML/CSS estático, sem build step, sem dependências.

## Páginas

| Arquivo | O quê |
|---|---|
| `index.html` | Home: hero em vídeo, #01 Sobre, #02 Conquistas, #03 Solta o som, #04 Próximas datas, #05 Contato |
| `sala-club.html` | O projeto: 15 artistas convidados + 10 episódios do Totsik |
| `artista-*.html` | Uma página por artista convidado (estilo, origem, set em vídeo e áudio) |
| `v2.html` | Versão alternativa: onepage resumida |

## Assets

- `assets/style.css` — folha única, mobile first
- `assets/v2.css` — folha da onepage
- `assets/*.ttf` — Archivo e Inter estáticas, servidas localmente
- `assets/sets/` — capas dos episódios do Sala Club
- `assets/artistas/` — fotos dos artistas convidados
- `assets/TOTSIK-PRESS-KIT.pdf` — press kit em PDF (o botão do site abre a pasta do Google Drive)

## Rodar local

Abrir `index.html` no navegador. Não precisa de servidor.

## Deploy

Vercel, estático. `vercel.json` cuida das URLs limpas (`/sobre` → `sobre.html`).

## Pendências

- Bios de 8 artistas convidados (Dionne, Por Um Fio, CHRIZ, PJ Sessions, DEV, Neck,
  Petrone, Vicky Fonttana) — as páginas existem e dizem "perfil em construção".
- As bios publicadas foram montadas de fontes públicas e estão marcadas como
  "a validar com o artista", com as fontes linkadas na própria página.
