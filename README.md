# Horto do Contorno — Landing Page

Site estático (HTML puro, sem build). Pronto pra subir no GitHub e conectar na Vercel.

## Estrutura
```
index.html   → a landing page
img/         → todas as fotos e a logo
vercel.json  → configuração básica de deploy
```

## Como subir no GitHub
```bash
git init
git add .
git commit -m "Landing page Horto do Contorno"
git branch -M main
git remote add origin <URL_DO_SEU_REPO>
git push -u origin main
```

## Como deployar na Vercel
1. Acesse vercel.com e faça login (pode usar sua conta do GitHub)
2. "Add New" → "Project"
3. Selecione o repositório que você acabou de subir
4. Framework Preset: **Other** (ou deixe em branco — é HTML estático, sem build)
5. Build Command / Output Directory: deixe em branco
6. Deploy

Pronto, a URL da Vercel já serve o `index.html` na raiz.

## Editar depois
- Trocar foto: substitua o arquivo dentro de `img/` mantendo o mesmo nome, ou troque o nome no `src=` correspondente dentro do `index.html`.
- Trocar telefone/WhatsApp: busque por `5575996148888` (WhatsApp) e `557536148888` (telefone fixo) no `index.html` e troque em todas as ocorrências.
- Trocar endereço: busque por "Eduardo Fróes da Mota" no `index.html` (aparece no mapa, no botão "Como chegar" e no rodapé).
