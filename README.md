# K‑SIMADIAB (GitHub Pages)

Aplicação em HTML (tema claro) preparada para correr diretamente no **GitHub Pages**.

## Publicação
1. Faça _upload_ destes ficheiros para a **raiz** do repositório.
2. Em **Settings → Pages → Build and deployment**:
   - **Source**: Deploy from a branch
   - **Branch**: `main` e **/(root)**
3. Aguarde 30–60s e abra `https://<utilizador>.github.io/<repo>/`.

## Ficheiros incluídos
- `index.html` — aplicação principal (React + Recharts via CDN segura, ordem correta)
- `favicon.png` — ícone do site
- `404.html` — página amigável de erro
- `.github/workflows/pages-check.yml` — workflow simples que valida a existência do `index.html` na raiz

## Notas
- O botão **Imprimir / PDF** usa `window.print()` com estilos de impressão otimizados.
- Se a página ficar “escura”, confirme a **ordem dos scripts** e o **hard refresh** (Ctrl+F5).
- Caso pretenda domínio próprio, adicione um ficheiro `CNAME` com o domínio (uma linha).

> Qualquer melhoria (favicon personalizado, README detalhado, minificação): criar _issue_ ou PR.
