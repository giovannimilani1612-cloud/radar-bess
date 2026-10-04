# Radar BESS

Seletor de sites para estudar energia solar, armazenamento (BESS), setor elétrico e transição energética. São 59 sites separados em 11 categorias.

- **Busca** por nome, assunto ou domínio, e **filtro** por categoria.
- **🎲 Sortear um site**: deixa a sorte escolher o que estudar (pode pular os já estudados).
- **✓ Estudado**: marque os sites que já viu; o progresso fica salvo no navegador.
- Tema claro/escuro e layout para celular.

É um único arquivo (`index.html`), sem servidor nem dependências: basta abrir no navegador.

## Publicar no GitHub Pages

Settings → Pages → *Deploy from a branch* → `main` / `(root)`. O site fica em
`https://giovannimilani1612-cloud.github.io/radar-bess/`.

## Adicionar ou remover sites

Edite a lista `SITES` em `index.html`. Cada linha é:

```js
['categoria', 'Nome', 'https://site.com', 'Descrição curta.', 'PT'],
```

As categorias ficam na lista `CATEGORIES`, logo acima.
