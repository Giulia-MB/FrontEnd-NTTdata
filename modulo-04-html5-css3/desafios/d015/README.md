# 📄 Desafio 015 - Módulo 04 - Capítulo 25

## 📌 Enunciado

Desafio proposto ao final do capítulo **"Media Queries"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

👉 [Material original](https://github.com/gustavoguanabara/html-css/blob/fe6653ecdafa5b7275a5ecb4c36a8ca14f5043e7/aulas-pdf/25%20-%20Media%20Queries.pdf)

## 💡 Objetivo

Criar uma **tela de login responsiva**, adaptando o layout para **celular, tablet e desktop**, utilizando **Mobile First**, Media Queries, formulário estilizado e interface moderna.

## 🌐 Visualização

👉 [Tela de Login Responsiva](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/desafios/d015/index.html)

## 🛠️ O que foi praticado

* Estrutura semântica com `main`, `section`, `form`
* Desenvolvimento no padrão **Mobile First**
* Uso de `@media` para tablet e desktop
* Layout centralizado com `position: absolute`
* Formulário de login com campos de e-mail e senha
* Uso de ícones do Google Material Icons
* Campos estilizados com `border-radius`
* Fundo com gradiente em telas maiores
* Imagem decorativa responsiva
* Botão principal de login
* Botão secundário “Esqueci a senha”
* Transições suaves com `transition`
* Uso de `calc()` em inputs
* Estados `hover`
* `autocomplete`, `required`, `maxlength`, `minlength`

## 📚 Aprendizados

* Mobile First começa criando a versão para celular  
* Media Queries ajustam o layout para telas maiores  
* `min-width` permite aplicar estilos após determinada largura  
* `transform: translate(-50%, -50%)` centraliza elementos  
* `calc()` permite cálculos dinâmicos no CSS  
* `hover` melhora interação visual  
* Inputs bem estilizados melhoram experiência do usuário  
* `autocomplete` agiliza preenchimento  
* Interfaces modernas dependem de responsividade

## 📄 Estrutura do desafio

### `index.html`

Página principal contendo:

* card de login centralizado
* imagem superior/lateral
* título e texto explicativo
* formulário funcional
* botão de acesso
* link de recuperação de senha

### `style.css`

Responsável pela versão mobile:

* layout base
* card vertical
* imagem no topo
* campos empilhados
* botões estilizados

### `media-query.css`

Responsável pela responsividade:

#### Tablet

* imagem à esquerda
* formulário à direita
* card horizontal

#### Desktop

* imagem à direita
* formulário à esquerda
* card maior
* textos ampliados

## 🚀 Resultado

Projeto moderno de tela de login adaptável para diferentes dispositivos, com ótima apresentação visual e aplicação prática de Media Queries.

---

## 💬 Observação

Este desafio é excelente para portfólio, pois simula uma interface real utilizada em sistemas web, reunindo formulário, responsividade, layout profissional e experiência do usuário.