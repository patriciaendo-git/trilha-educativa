# Trilha de introdução à pesquisa · dotLAB

Página com os materiais da trilha do dotLAB para as estudantes do projeto Isso é normal?.

## Nomes dos arquivos

Os PDFs têm **nome fixo, sem versão e sem número da trilha** (ex.: `pdfs/boas-vindas-ao-dotlab.pdf`). O material de apoio leva o nome do material que acompanha, com `-apoio` no fim (ex.: `pdfs/documento-de-estudo-apoio.pdf`).

A versão aparece na capa do PDF e na página. O histórico de versões fica nos commits do GitHub.

## Como atualizar um material

1. Envie o PDF novo para `pdfs/`, **com o mesmo nome** do antigo. O GitHub substitui o arquivo.
2. Em `index.html`, atualize `ver` (ex.: `"Versão 1.2 · novembro de 2026"`) e, se mudou, `pag`, na linha do material na lista `MATS`.
3. Faça o commit. O GitHub Pages atualiza a página em um ou dois minutos.

## Como publicar um material novo

Envie o PDF para `pdfs/` e, na linha do material em `MATS`, acrescente `pdf`, `pag` e `ver`:

```js
{n:"8", t:"Conhecer os dados", d:"...", tipo:"p", pdf:"pdfs/conhecer-os-dados.pdf", pag:5, ver:"Versão 1.0 · outubro de 2026"},
```
