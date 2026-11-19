# Atividade 01 - Box Model e Flexbox

Projeto em HTML e CSS puro, sem dependências.

## Arquivos
- `index.html` - estrutura da página (20 caixas + cabeçalho, menu, seção extra e rodapé).
- `style.css` - estilos, incluído de forma **externa** pela tag `<link rel="stylesheet" href="style.css">`.
- `README.md` - este arquivo.

## Como usar
Extraia o ZIP e abra o `index.html` em qualquer navegador. Os dois arquivos devem ficar na mesma pasta.

## Requisito 1 - Projeto com `index.html` e `style.css`
CSS externo via `<link>` dentro do `<head>`.

## Requisito 2 - 20 elementos com Box Model
Cada elemento `.caixa-1` a `.caixa-20` tem valores em todas as propriedades:
| Parte | Propriedades |
|---|---|
| Content | `width`, `height` |
| Padding | `padding-top`, `padding-right`, `padding-bottom`, `padding-left` |
| Border | `border-width`, `border-style`, `border-color`, `border-radius` |
| Margin | `margin-top`, `margin-right`, `margin-bottom`, `margin-left` |

## Requisito 3 - 20 propriedades de Flexbox
Todas comentadas e numeradas no `style.css`:
`display: flex`, `flex-direction`, `flex-wrap`, `flex-flow`, `justify-content`, `align-items`, `align-content`, `gap`, `row-gap`, `column-gap`, `order`, `flex-grow`, `flex-shrink`, `flex-basis`, `flex`, `align-self`, `place-content`, `place-items`, `display: inline-flex`, `flex-wrap: wrap-reverse`.

## Responsividade
As caixas quebram de linha automaticamente (`flex-wrap`) e há `@media queries` que mudam a direção do flex em telas pequenas. Redimensione a janela para ver o efeito.
