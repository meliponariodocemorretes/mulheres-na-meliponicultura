# Mulheres na Meliponicultura

Página institucional do projeto de impacto socioambiental do Meliponário Doce Morretes, adaptada da apresentação IMPACTO_SOCIOAMBIENTAL.pdf.

Site estático em HTML e CSS, responsivo, com navegação por seções, contatos e download do PDF original. As imagens foram extraídas do documento e otimizadas em WebP.

## Publicação

GitHub Pages: branch `main`, pasta `/ (root)`.

Endereço público: `https://docemorretes.com/mulheresnameliponicultura/`.

A raiz `docemorretes.com` permanece na hospedagem original da loja. O Cloudflare Worker `mulheres-na-meliponicultura` encaminha somente esse caminho ao GitHub Pages em `https://meliponariodocemorretes.github.io/mulheres-na-meliponicultura/`. Não adicionar um arquivo `CNAME` ao repositório: o domínio principal pertence à loja.

## Edição

- `index.html`: conteúdo e contatos.
- `styles.css`: identidade visual e responsividade.
- `capa.webp`, `manejo.webp`, `meliponario.webp`: imagens do projeto.
- `projeto-mulheres-na-meliponicultura.pdf`: apresentação original.

Para visualizar localmente: `python -m http.server 8765` nesta pasta.
