# 🧩 Exercício 028 - Módulo 05 - Capítulo 28

## 📝 Enunciado

Exercício baseado no capítulo **"Grid Layout CSS"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

## 🎯 Objetivo

Aprender a construir layouts bidimensionais com **CSS Grid Layout**, organizando elementos em linhas e colunas, controlando espaçamentos, alinhamentos, áreas e o posicionamento dos itens dentro da grade.

## 👀 Visualização

[grid001 - Anatomia e propriedades básicas do Grid](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/exercicios/ex028/grid001/index.html)  
[grid002 - Atalhos grid-template, place-items e place-content](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/exercicios/ex028/grid002/index.html)  
[grid003 - repeat, fr e linhas automáticas](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/exercicios/ex028/grid003/index.html)  
[grid004 - Posicionamento com grid-row-start e grid-column-start](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/exercicios/ex028/grid004/index.html)  
[grid005 - Posicionamento com grid-row e grid-column](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/exercicios/ex028/grid005/index.html)  
[grid006 - Posicionamento com grid-area](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/exercicios/ex028/grid006/index.html)

## 🛠️ O que foi praticado

- Criação de um grid container com `display: grid`
- Organização de elementos em linhas e colunas
- Uso de `grid-template-columns`
- Uso de `grid-template-rows`
- Uso de `grid-template`
- Espaçamento entre itens com `gap`
- Alinhamento dos itens com `align-items` e `justify-items`
- Alinhamento do grid com `align-content` e `justify-content`
- Atalhos de alinhamento com `place-items` e `place-content`
- Criação de repetições com `repeat()`
- Divisão proporcional do espaço com a unidade `fr`
- Criação de linhas automáticas com `grid-auto-rows`
- Criação de colunas automáticas com `grid-auto-columns`
- Posicionamento de elementos com `grid-row-start`, `grid-row-end`, `grid-column-start` e `grid-column-end`
- Uso dos atalhos `grid-row` e `grid-column`
- Posicionamento com `grid-area`
- Uso de valores negativos para alcançar a última linha do Grid

## 📚 Aprendizados

- O CSS Grid trabalha com duas dimensões: linhas e colunas
- O elemento que recebe `display: grid` se torna o grid container
- Os filhos diretos do container se tornam grid items
- `grid-template-columns` define a estrutura das colunas
- `grid-template-rows` define a estrutura das linhas
- `grid-template` permite declarar linhas e colunas em uma única propriedade
- `gap` cria espaçamento entre linhas e colunas
- `align-items` e `justify-items` alinham os itens dentro das células
- `align-content` e `justify-content` alinham o conjunto do grid dentro do container
- `place-items` é um atalho para `align-items` e `justify-items`
- `place-content` é um atalho para `align-content` e `justify-content`
- `repeat()` evita repetição manual ao criar linhas ou colunas
- A unidade `fr` divide o espaço disponível em frações
- `grid-auto-rows` define o tamanho das linhas criadas automaticamente
- `grid-auto-columns` define o tamanho das colunas criadas automaticamente
- `grid-row` e `grid-column` simplificam o posicionamento dos itens
- `grid-area` pode posicionar um item usando a ordem linha inicial, coluna inicial, linha final e coluna final

## 📁 Estrutura do exercício

### `grid001`

- introdução ao `display: grid`
- criação de três colunas e três linhas com `auto`
- uso de `gap`
- primeiros testes com `align-items`, `justify-items`, `align-content` e `justify-content`
- observação da anatomia do Grid com itens de `A` até `H`

### `grid002`

- uso do atalho `grid-template`
- criação de linhas e colunas com `repeat(3, auto)`
- alinhamento dos itens com `place-items`
- alinhamento do conjunto do Grid com `place-content`
- combinação de valores como `start center` e `space-between end`

### `grid003`

- criação de linhas com `repeat(3, 80px)`
- criação de colunas usando valores mistos: `100px`, `40%` e `repeat(2, 1fr)`
- prática com a unidade `fr`
- uso de `grid-auto-flow`
- definição de linhas automáticas com `grid-auto-rows`
- definição de colunas automáticas com `grid-auto-columns`

### `grid004`

- posicionamento manual de elementos usando propriedades longas
- uso de `grid-row-start`
- uso de `grid-row-end`
- uso de `grid-column-start`
- uso de `grid-column-end`
- criação de um layout com três áreas visuais usando caixas coloridas
- uso de `-1` para indicar a última linha do Grid

### `grid005`

- mesma estrutura visual do `grid004`
- substituição das propriedades longas pelos atalhos `grid-row` e `grid-column`
- posicionamento mais curto e organizado
- prática da sintaxe `início / fim`

### `grid006`

- mesma estrutura visual dos exercícios anteriores
- uso de `grid-area` para posicionar os elementos
- prática da ordem `row-start / column-start / row-end / column-end`
- redução do código necessário para posicionar cada caixa no Grid

## ✅ Resultado

O exercício apresentou a base prática do **CSS Grid Layout**, mostrando como criar uma grade, controlar linhas e colunas, alinhar itens, distribuir espaços e posicionar elementos em regiões específicas da página.

---

## 💡 Observação

CSS Grid é uma ferramenta essencial para criar layouts modernos. Ele é especialmente útil quando o projeto precisa organizar elementos em duas dimensões, permitindo controlar colunas, linhas, espaços e áreas de forma mais clara e flexível.
