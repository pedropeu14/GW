# GW — exposição acionária

Página estática única, sem dependências externas. Abrediretamente do disco ou a partir do GitHub Pages.

## Publicar

1. Cria um repositório **privado** no GitHub e envia o conteúdo desta pasta.
2. Settings → Pages → Source: `main` / `root`.

> O GitHub Pages serve o site publicamente mesmo a partir de um repositório privado, exceto nos
> planos Enterprise com Pages privado. Os dados aqui já estão anonimizados — não há nome de cliente,
> números de conta nem IBANs — mas confirma a política interna antes de publicar.

## Atualizar os dados

Todos os números vivem no objecto `D` no final do `index.html`. Substitui esse JSON por um novo
extraído dos extratos e a página atualiza-se sozinha.
