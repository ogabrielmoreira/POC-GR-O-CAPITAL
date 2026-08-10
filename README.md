# Grão Capital · Safra+

Protótipo navegável de app de fidelidade para produtores rurais: pontos por notas fiscais de café e soja, resgates na cooperativa e ranking regional.

**Demo:** [https://ogabrielmoreira.github.io/POC-GR-O-CAPITAL/](https://ogabrielmoreira.github.io/POC-GR-O-CAPITAL/)

## Sobre

Case de produto por **Gabriel · [@gabrieltechdesign](https://instagram.com/gabrieltechdesign)**. Dados fictícios; fluxo completo de onboarding, NF-e, resgates e ranking em layout estilo iOS.

## Estrutura

| Arquivo            | Descrição                                      |
|--------------------|------------------------------------------------|
| `docs/index.html`  | App single-page (React embutido) — publicado no Pages |
| `index.html`       | Cópia local na raiz (opcional para editar)     |

## GitHub Pages

Publicação a partir da pasta **`/docs`** na branch **`main`**. O arquivo **`docs/.nojekyll`** desliga o Jekyll (necessário porque o React minificado usa `{{` e quebraria o build).

**Settings → Pages:** branch **main**, pasta **`/docs`**.

URL: https://ogabrielmoreira.github.io/POC-GR-O-CAPITAL/

## Rodar localmente

Abra `index.html` no navegador ou use um servidor estático:

```bash
cd docs && python3 -m http.server 8080
```

Acesse [http://localhost:8080](http://localhost:8080).
