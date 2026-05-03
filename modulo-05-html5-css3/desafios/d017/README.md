# 📄 Desafio 017 - Módulo 05 - Capítulo 28

## 📌 Enunciado

Desafio proposto ao final do capítulo **"Grid Layout CSS"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

## 💡 Objetivo

Criar uma estrutura de página utilizando **CSS Grid Layout**, organizando as principais áreas de um site em topo, menu, conteúdo principal, conteúdo secundário e rodapé.

## 🌐 Visualização

👉 [Layout com CSS Grid](https://giulia-mb.github.io/html-semantico/modulo-05-html5-css3/desafios/d017/index.html)

## 🛠️ O que foi praticado

* Estruturação da página com tags semânticas
* Uso de `header`, `nav`, `main`, `aside` e `footer`
* Criação de um grid container com `display: grid`
* Definição de colunas com `grid-template-columns`
* Definição de linhas com `grid-template-rows`
* Espaçamento entre áreas com `gap`
* Posicionamento dos elementos com `grid-area`
* Organização de layout em duas colunas
* Criação de áreas horizontais ocupando toda a largura
* Uso de `100vw` e `100vh` para ocupar toda a tela
* Aplicação de reset básico com `margin`, `padding` e `box-sizing`
* Estilização visual das áreas com borda, cor de fundo e alinhamento de texto

## 📚 Aprendizados

* CSS Grid permite montar layouts completos de página com poucas propriedades
* `grid-template-columns` controla a largura das colunas do layout
* `grid-template-rows` controla a altura das linhas do layout
* `grid-area` pode posicionar elementos usando a ordem `linha inicial / coluna inicial / linha final / coluna final`
* O topo, o menu e o rodapé podem ocupar todas as colunas do grid
* A área principal pode dividir espaço com uma barra lateral
* Tags semânticas deixam a estrutura HTML mais organizada e significativa
* `gap` facilita a criação de espaçamentos entre as partes do layout
* `box-sizing: border-box` ajuda a controlar melhor o tamanho dos elementos

## 📄 Estrutura do desafio

### `index.html`

Página principal contendo:

* container geral do layout
* cabeçalho representado por `header`
* menu de navegação representado por `nav`
* conteúdo principal representado por `main`
* conteúdo secundário representado por `aside`
* rodapé representado por `footer`

### `style.css`

Arquivo responsável pela aparência e organização do layout:

* reset básico dos elementos
* grid ocupando toda a largura e altura da tela
* duas colunas: uma flexível e uma lateral fixa
* quatro linhas para topo, menu, conteúdo e rodapé
* espaçamento com `gap`
* posicionamento das áreas com `grid-area`
* caixas com bordas tracejadas e cor de fundo

## 🚀 Resultado

O desafio apresentou a criação de um layout clássico de página usando **CSS Grid**, com cabeçalho, menu, área principal, barra lateral e rodapé bem distribuídos na tela.

---

## 💬 Observação

Este desafio mostra como o CSS Grid facilita a criação de estruturas completas de sites. Em vez de depender de várias adaptações manuais, o layout pode ser organizado diretamente em linhas e colunas, deixando o código mais claro e fácil de manter.