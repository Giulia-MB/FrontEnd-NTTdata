# 📄 Desafio 13 - Módulo 04 - Capítulo 22

## 📌 Enunciado

Desafio proposto no capítulo **"Inline Frames"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

👉 [Material original](https://github.com/gustavoguanabara/html-css/blob/fe6653ecdafa5b7275a5ecb4c36a8ca14f5043e7/aulas-pdf/22%20-%20Inline%20Frames.pdf)

## 💡 Objetivo

Criar uma página interativa simulando um **smartphone responsivo**, exibindo diferentes redes sociais dentro da tela do aparelho por meio de **iframes**, com navegação lateral e links externos.

## 🌐 Visualização

👉 [Projeto Redes Sociais](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/desafios/dextra/index.html)

## 🛠️ O que foi praticado

* Estruturação semântica com `main` e `section`
* Uso de `iframe` para trocar o conteúdo da tela do celular
* Definição de `name` no iframe e `target` nos links
* Centralização absoluta com `position: absolute`
* Uso de `transform: translate(-50%, -50%)`
* Aplicação de imagem como moldura do celular
* Menu lateral com ícones clicáveis
* Transformação de imagens quadradas em circulares com `border-radius: 50%`
* Efeito hover com sombra, borda e movimento
* Background fixo ocupando a tela inteira
* Links externos abrindo em nova aba com `target="_blank"`
* Ocultação da barra de rolagem interna
* Organização visual responsiva

## 📚 Aprendizados

* `iframe` permite carregar páginas HTML dentro de outra página  
* `src="home.html"` define a tela inicial carregada  
* `name="tela"` identifica o iframe para receber links via `target="tela"`  
* `position: absolute` permite posicionamento livre na tela  
* `top: 50%` e `left: 50%` posicionam o elemento no centro  
* `transform: translate(-50%, -50%)` corrige o centro real do elemento  
* `100vh` representa 100% da altura visível da tela  
* `100vw` representa 100% da largura visível da tela  
* `background-size: cover` faz a imagem preencher toda a área  
* `border-radius: 50%` transforma elementos quadrados em círculos  
* `box-shadow` adiciona profundidade visual  
* `transition` suaviza animações no hover  

## 📄 Estrutura do desafio

### `index.html`

Página principal contendo:

* fundo madeira
* moldura do smartphone
* iframe central
* menu lateral com redes sociais

### `home.html`

Tela inicial padrão exibida ao abrir o projeto.

### Páginas internas

* `youtube.html`
* `github.html`
* `instagram.html`
* `twitter.html`
* `facebook.html`

Cada página contém:

* imagem simulando a rede social
* botão **ACESSE**
* link externo real

### `style.css`

Responsável pelo layout principal:

* fundo
* posicionamento do celular
* iframe
* ícones laterais
* hover dos botões

### `social.css`

Responsável pelas páginas carregadas no iframe:

* imagem em largura total
* botão de acesso
* scrollbar oculta

## 🚀 Resultado

Projeto visual moderno e interativo, simulando o uso de um smartphone com navegação entre redes sociais, aplicando na prática iframes, posicionamento e efeitos visuais com CSS.

---

## 💬 Observação

Este desafio é excelente para praticar integração entre HTML e CSS, pois reúne layout, navegação dinâmica, responsividade e experiência do usuário em um único projeto.