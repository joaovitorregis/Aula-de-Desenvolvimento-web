# Desenvolvimento Web

Materiais e registros de quatro encontros de introdução ao desenvolvimento web ministrados por João Vitor Regis, que atuou como tutor de Web Coding.

Os encontros abordaram HTML, CSS, JavaScript e publicação de sites. Este repositório reúne os PDFs das aulas e um site de demonstração para consulta e estudo.

## Materiais das aulas

| Encontro | Tema | PDF |
|---|---|---|
| 1 | Fundamentos da web e HTML5 | [Abrir material](materiais/01-html5.pdf) |
| 2 | CSS, estilos, layout e responsividade | [Abrir material](materiais/02-css.pdf) |
| 3 | JavaScript e formulário com alert | [Abrir material](materiais/03-javascript.pdf) |
| 4 | Publicação do primeiro site | [Abrir material](materiais/04-publicacao.pdf) |

Os materiais estão organizados por tema. A numeração da capa do PDF de CSS difere da ordem apresentada nesta tabela.

## Registros dos encontros


| 08/09/2026 | 16/09/2026 | 30/09/2026 |
|---|---|---|
| ![Registro de 08 de setembro](registros/2026-09-08/registro-03.jpeg) | ![Registro de 16 de setembro](registros/2026-09-16/registro-06.jpeg) | ![Registro de 30 de setembro](registros/2026-09-30/registro-03.jpeg) |

[Ver todos os registros e sua procedência](registros/README.md).

## Site de demonstração

[Abrir a demonstração publicada](https://joaovitorregis.github.io/Aula-de-Desenvolvimento-web/).

Para estudar no computador:

1. Baixe o repositório em **Code → Download ZIP** e extraia os arquivos, ou clone com `git clone https://github.com/joaovitorregis/Aula-de-Desenvolvimento-web.git`.
2. Abra `index.html` no navegador, mantendo `styles.css` e `script.js` na mesma pasta.
3. Use **Adicionar clique** e **Reiniciar**, alterne o tema no cabeçalho e preencha o formulário com dados fictícios para observar o `alert`.

O exemplo usa HTML, CSS e JavaScript puro. Não precisa instalar dependências, executar um build ou configurar servidor.

O formulário demonstra comportamento de interface com `alert`; ele não envia nem armazena inscrições. Os exemplos são materiais introdutórios e não representam uma aplicação com backend.

## Publicação no GitHub Pages

A configuração consultada em 22/10/2026 publica a raiz (`/`) da branch `main` em GitHub Pages, sem domínio próprio.

Para publicar sua própria cópia:

1. Crie um fork ou envie os arquivos para um repositório seu, com `index.html`, `styles.css` e `script.js` na raiz.
2. Em **Settings → Pages**, selecione **Deploy from a branch**, a branch que contém os arquivos e a pasta **/(root)**; salve.
3. Aguarde a publicação e abra a URL indicada pelo GitHub. Confira o contador, o tema e o formulário na página publicada.

Alterações neste repositório só aparecem no site após chegarem à `main` e a publicação concluir. O endereço de uma página de código no GitHub (`/blob/.../index.html`) mostra o arquivo; use a URL do Pages para acessar o site.

## Organização

```text
materiais/   PDFs dos quatro encontros
registros/   imagens agrupadas pelas datas dos arquivos originais
index.html   estrutura do site de demonstração
styles.css   apresentação visual
script.js    interações
```

## Autoria

João Vitor Regis · Web Coding.

## Licenças

- Código de demonstração (`index.html`, `styles.css` e `script.js`): [MIT](LICENSE).
- Materiais didáticos em `materiais/` e textos de documentação: [CC BY 4.0](LICENSE-MATERIALS), com atribuição a João Vitor Regis.

As imagens de registro dos encontros em `registros/` ficam fora dessas licenças. Elementos de terceiros nos materiais conservam seus próprios direitos e licenças.
