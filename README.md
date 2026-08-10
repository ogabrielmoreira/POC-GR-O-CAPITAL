# Grão Capital · Safra+

Protótipo navegável de app de fidelidade para produtores rurais: pontos por notas fiscais de café e soja, resgates na cooperativa e ranking regional.

**Demo:** [https://ogabrielmoreira.github.io/POC-GR-O-CAPITAL/](https://ogabrielmoreira.github.io/POC-GR-O-CAPITAL/)

## Sobre

Case de produto por **Gabriel · [@gabrieltechdesign](https://instagram.com/gabrieltechdesign)**. Dados fictícios; fluxo completo de onboarding, NF-e, resgates e ranking em layout estilo iOS.

## Estrutura

| Arquivo       | Descrição                                      |
|---------------|------------------------------------------------|
| `index.html`  | App single-page (React embutido) — site estático |

## GitHub Pages

Deploy automático via [GitHub Actions](.github/workflows/pages.yml) a cada push na `main`. Não há build — o artefato é o site estático na raiz (`.nojekyll` evita processamento Jekyll).

Se for a primeira vez: em **Settings → Pages**, confirme que a origem é **GitHub Actions**.

## Rodar localmente

Abra `index.html` no navegador ou use um servidor estático:

```bash
python3 -m http.server 8080
```

Acesse [http://localhost:8080](http://localhost:8080).
