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

Site estático na raiz do repositório (`index.html` + `.nojekyll`). Não precisa de build.

**Ativar (uma vez):** [Settings → Pages](https://github.com/ogabrielmoreira/POC-GR-O-CAPITAL/settings/pages) → **Build and deployment** → **Deploy from a branch** → Branch **main**, pasta **/ (root)** → Save.

Depois de alguns minutos o protótipo fica em:  
https://ogabrielmoreira.github.io/POC-GR-O-CAPITAL/

## Rodar localmente

Abra `index.html` no navegador ou use um servidor estático:

```bash
python3 -m http.server 8080
```

Acesse [http://localhost:8080](http://localhost:8080).
