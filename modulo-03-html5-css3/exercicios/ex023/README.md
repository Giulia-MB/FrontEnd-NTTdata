# 📄 Exercício 023 - Módulo 03 - Capítulo 21

## 📌 Enunciado

Exercício baseado no material **"Conteúdos em Tabelas"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

👉 [Material original](https://github.com/gustavoguanabara/html-css/blob/fe6653ecdafa5b7275a5ecb4c36a8ca14f5043e7/aulas-pdf/21%20-%20Tabelas.pdf)

## 💡 Objetivo

Aprender a criar, estruturar e estilizar tabelas em HTML, utilizando tags semânticas, alinhamentos, cabeçalho, rodapé, efeito zebrado, cabeçalho fixo e mesclagem de células.

## 🌐 Visualização

👉 [tabela001.html - Primeira tabela](https://giulia-mb.github.io/html-semantico/modulo-03-html5-css3/exercicios/ex023/tabela001.html)  
👉 [tabela002.html - Tabela grande](https://giulia-mb.github.io/html-semantico/modulo-03-html5-css3/exercicios/ex023/tabela002.html)  
👉 [tabela003.html - Mesclagem de células](https://giulia-mb.github.io/html-semantico/modulo-03-html5-css3/exercicios/ex023/tabela003.html)

## 🛠️ O que foi praticado

* Criação de tabelas com `table`, `tr`, `td` e `th`
* Uso de `caption` para título da tabela
* Organização com `thead`, `tbody` e `tfoot`
* Uso de `scope` para indicar escopo de cabeçalhos
* Estilização com `border-collapse`
* Alinhamento horizontal com `text-align`
* Alinhamento vertical com `vertical-align`
* Efeito zebrado com `nth-child()`
* Cabeçalho fixo com `position: sticky`
* Mesclagem de células com `colspan` e `rowspan`

## 📚 Aprendizados

* Tabelas devem ser usadas para apresentar dados tabulares, não para construir o layout inteiro de um site.

* A estrutura básica de uma tabela é formada por:

```html
<table>
  <tr>
    <td>Dado</td>
  </tr>
</table>
```

* `table` representa a tabela.

* `tr` representa uma linha da tabela.

* `td` representa uma célula de dados.

* `th` representa uma célula de cabeçalho.

* `caption` adiciona um título à tabela.

* Em tabelas maiores, a organização pode ser feita com:

```html
<thead></thead>
<tbody></tbody>
<tfoot></tfoot>
```

* `thead` representa o cabeçalho.

* `tbody` representa o corpo da tabela.

* `tfoot` representa o rodapé.

* O atributo `scope` melhora a semântica da tabela:

* `scope="col"` indica cabeçalho de coluna.

* `scope="row"` indica cabeçalho de linha.

* `border-collapse: collapse;` junta as bordas das células:


## 📄 Estrutura do exercício

### `tabela001.html`

Página demonstrando:

* criação de tabela simples
* uso de linhas e células
* bordas com CSS
* alinhamento horizontal e vertical
* classe para alinhar números à direita

### `tabela002.html`

Página demonstrando:

* tabela grande com dados de população
* uso de `caption`
* uso de `thead`, `tbody` e `tfoot`
* uso de `scope`
* efeito zebrado
* cabeçalho fixo
* total de habitantes no rodapé

### `tabela003.html`

Página demonstrando:

* mesclagem de células
* uso de `colspan`
* uso de `rowspan`
* organização visual de células expandidas

## 🚀 Resultado

O exercício mostrou como criar tabelas simples e grandes em HTML, aplicando organização semântica, estilização visual e recursos importantes para melhorar leitura e acessibilidade dos dados.

---

## 💬 Observação

Este capítulo reforça que tabelas são importantes para apresentar dados organizados, mas não devem ser usadas para montar a estrutura visual completa de um site. Para layout, o ideal é usar CSS.