# 📄 Exercício 015 - Módulo 01 - Capítulo 12

## 📌 Enunciado

Exercício proposto no capítulo **"Trabalhando com estilos"** do curso de HTML e CSS da plataforma "Curso em Vídeo".

👉 [Material original](https://github.com/gustavoguanabara/html-css/blob/master/aulas-pdf/12%20-%20Trabalhando%20com%20estilos.pdf)

## 💡 Objetivo

Praticar a aplicação de estilos CSS externos, reutilizando a mesma folha de estilos em mais de uma página HTML.

## 🌐 Visualização

👉 [index.html](https://giulia-mb.github.io/FrontEnd-NTTdata/html-semantico/exercicios/ex015/index.html)  
👉 [pagina02.html](https://giulia-mb.github.io/FrontEnd-NTTdata/html-semantico/exercicios/ex015/pagina02.html)

## 🛠️ O que foi praticado

* Criação de arquivo CSS externo (`style.css`)  
* Uso da tag `<link>` para importar estilos  
* Reutilização de estilos em múltiplas páginas  
* Navegação entre páginas com links internos  
* Combinação de CSS externo com CSS interno e inline  

## 📚 Aprendizados

* O CSS externo permite separar totalmente estrutura e estilo  
* Um único arquivo CSS pode estilizar várias páginas ao mesmo tempo  
* Essa abordagem facilita manutenção, organização e reaproveitamento de código  
* Alterações no arquivo CSS refletem automaticamente em todas as páginas vinculadas  
* O CSS interno e inline continuam funcionando, mas afetam apenas o arquivo onde foram declarados  

### 📌 Exemplo prático deste exercício

* O arquivo `style.css` estiliza tanto a página principal quanto a segunda página  
* O estilo interno aplicado no `<h1>` da página principal (sublinhado) afeta apenas essa página  
* O estilo inline no link para a segunda página (`text-align: right`) também afeta apenas esse elemento  

Isso mostra claramente a diferença entre:

- CSS externo → reutilizável em várias páginas  
- CSS interno → limitado ao arquivo atual  
- CSS inline → limitado ao elemento específico  

## 🚀 Resultado

Pequeno site com duas páginas estilizadas por um único arquivo CSS externo, demonstrando como centralizar estilos de forma mais profissional.

---

## 💬 Observação

Este exercício é importante porque apresenta a forma mais recomendada de trabalhar com CSS em projetos reais: utilizando folhas de estilo externas para manter o código limpo, organizado e fácil de manter. O uso combinado de CSS interno e inline também ajuda a entender a prioridade entre estilos. 