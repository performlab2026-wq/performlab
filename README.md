# PerformLab — Consultoria 1:1

Landing page de consultoria esportiva 1:1 (Paulo). Site estático de página única.

## Stack

- HTML/CSS puro (sem build), fontes Google (Anton + Manrope)
- Hospedagem: Vercel (config em `vercel.json`)
- Arquivo principal: `index.html`
- Identidade visual: vermelho `#FF2D3D` sobre fundo `#0A0A0B`

## Editar conteúdo

Tudo está em `index.html`. Placeholders entre colchetes (ex: `[PAULO]`, `[CREF Nº ______]`, `[FOTO PAULO — 800×1000]`) marcam o que falta preencher.

## Deploy

Com o Vercel CLI instalado e logado:

```bash
vercel deploy --prod --yes
```

Cada push para a branch `main` no GitHub pode disparar deploy automático se o projeto Vercel estiver conectado ao repositório.

## Estrutura

```
index.html         # página principal (Consultoria.html original do design)
icon-192.svg       # favicon
vercel.json        # config do Vercel (cleanUrls)
.vercelignore      # exclui pacote de design original do deploy
```

## Histórico

Design original em HTML veio de um pacote Claude Design (`project-maguila`) — preservado integralmente sem alteração de identidade visual.
