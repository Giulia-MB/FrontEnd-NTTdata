# 📄 Exercício 026 - Módulo 04 - Capítulo 25

## 📌 Enunciado

Exercício baseado no capítulo **"Media Queries"** do curso de HTML e CSS da plataforma **Curso em Vídeo**.

👉 [Material original](https://github.com/gustavoguanabara/html-css/blob/fe6653ecdafa5b7275a5ecb4c36a8ca14f5043e7/aulas-pdf/25%20-%20Media%20Queries.pdf)

## 💡 Objetivo

Aprender a criar páginas **responsivas**, adaptando o layout conforme o tipo de mídia, tamanho da tela, orientação do dispositivo e resolução, utilizando **Media Queries** em projetos práticos.

## 🌐 Visualização

👉 [mq001 - Estilo para Tela e Impressão](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/exercicios/ex026/mq001/index.html)  
👉 [mq002 - Orientation com CSS separado](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/exercicios/ex026/mq002/index.html)  
👉 [mq003 - Orientation com CSS único](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/exercicios/ex026/mq003/index.html)  
👉 [mq004 - Breakpoints por dispositivo](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/exercicios/ex026/mq004/index.html)  
👉 [mq005 - Menu Hambúrguer Responsivo](https://giulia-mb.github.io/html-semantico/modulo-04-html5-css3/exercicios/ex026/mq005/index.html)

## 🛠️ O que foi praticado

- Uso de `@media`
- Uso do atributo `media=""` no HTML
- Separação de CSS por tipo de mídia
- Responsividade para celular, tablet, desktop e TV
- Detecção de orientação da tela
- Menu hambúrguer responsivo
- Breakpoints personalizados
- Mobile First
- Troca de imagens conforme dispositivo
- Layout adaptável
- Estilo para impressão
- Organização de múltiplos arquivos CSS

## 📚 Aprendizados

- Media Queries permitem adaptar o site conforme o dispositivo  
- O mesmo HTML pode ter estilos diferentes para cada tela  
- `screen` é usado para telas  
- `print` é usado para impressão  
- `orientation: portrait` detecta tela em pé  
- `orientation: landscape` detecta tela deitada  
- `min-width` define largura mínima  
- `max-width` define largura máxima  
- Mobile First começa pelo celular  
- Menus podem mudar totalmente em telas pequenas

## 📄 Estrutura do exercício

### `mq001`

- estilos diferentes para monitor e impressora  
- uso de `media="screen"` e `media="print"`

### `mq002`

- mudança visual conforme orientação  
- CSS separado para retrato e paisagem

### `mq003`

- mesma proposta da mq002  
- Media Query dentro do próprio CSS

### `mq004`

- mudança conforme largura da tela  
- imagens específicas para:

  - celular
  - tablet
  - desktop
  - TV
  - impressão

### `mq005`

- menu tradicional em telas grandes  
- botão hambúrguer em telas pequenas  
- menu expansível com JavaScript

## 🚀 Resultado

O exercício apresentou aplicações reais de **responsividade moderna**, mostrando como adaptar interfaces para diferentes dispositivos e melhorar a navegação em qualquer tela.

---

## 💬 Observação

Media Queries são indispensáveis no desenvolvimento front-end atual. Hoje praticamente todo site profissional precisa funcionar bem no celular, tablet e computador.