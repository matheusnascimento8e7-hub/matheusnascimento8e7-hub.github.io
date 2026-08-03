# Portfólio · Matheus Nascimento — Analista de BI

Página estática (HTML + CSS + React via CDN) com 5 cases de Business Intelligence:
Financeiro, RH, Logística, Marketing e Governança de Dados.

> Empresas e dados dos cases são fictícios, criados apenas para demonstração.

## Estrutura

```
index.html          página completa (auto-contida, sem build)
assets/perfil.png   foto de perfil  (adicionar)
.nojekyll           desliga o Jekyll no GitHub Pages
```

## Publicar no GitHub Pages

1. Criar repositório **público** chamado `matheusnascimento8e7-hub.github.io`
2. Subir os arquivos (`index.html`, `assets/`, `.nojekyll`) na branch `main`
3. Settings → Pages → Source: `Deploy from a branch` → `main` / `root`
4. Aguardar ~1 min → no ar em `https://matheusnascimento8e7-hub.github.io`

## Rodar localmente

```bash
python3 -m http.server 8000
# abrir http://localhost:8000
```

## Pendências

Colocar em `assets/`:

- `perfil.png` — foto (o `<img>` já aponta para lá; se faltar, ele some sem quebrar o layout)

Contatos (LinkedIn, GitHub e e-mail) já estão preenchidos.
