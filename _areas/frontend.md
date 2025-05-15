---
title: Frontend
---
Frontend é a parte visual e interativa de um aplicativo. Uma boa interface gráfica é responsiva, acessível e visualmente atraente.

## Cursos de frontend
Alguns cursos gratuitos recomendados para aprender frontend:

### MDN Curriculum
Currículo criado pela Mozilla com o objetivo de ser o guia definitivo para aprender todas as habilidades e práticas essenciais para ser um bom desenvolvedor frontend.

- [MDN Curriculum](https://developer.mozilla.org/en-US/curriculum/)

### The Odin Project
Curso open source mantido pela comunidade. Esse curso é focado em atividades práticas, fornecendo ótimos projetos para mostrar no seu currículo ao longo do curso.

- [The Odin Project](https://www.theodinproject.com/paths/foundations/courses/foundations)

{% include box-tip.html content="Dê uma olhada em algumas coisas que você vai aprender no [mapa do frontend](https://roadmap.sh/frontend?r=frontend)" %}

## HTML
HTML (HyperText Markup Language ou Linguagem de Marcação de Hipertexto) é usado para dar estrutura ao site, que depois pode ser estilizado com CSS e deixar interativo com JavaScript.

- [MDN: Introdução ao HTML](https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML)
- [W3Schools: HTML Tutorial](https://www.w3schools.com/html/default.asp)

## HTML Semântico
Um elemento semântico é um elemento que tem conteúdo bem definido. Escrever HTML semântico ajuda com a legibilidade do código, além de deixar seu site mais acessível.

- [web.dev: HTML Semântico](https://web.dev/learn/html/semantic-html?hl=pt-br)
- [W3Schools: HTML Semantics](https://www.w3schools.com/html/html5_semantic_elements.asp)
- [freeCodeCamp(): HTML Best Practices](https://www.freecodecamp.org/news/html-best-practices/)

Veja mais:

{% include box-learn-more.html content="
- [Qual a diferença semântica entre &lt;section&gt; e &lt;article&gt;?](https://pt.stackoverflow.com/questions/326021/qual-a-diferen%c3%a7a-sem%c3%a2ntica-entre-section-e-article)
- [What's the difference between &lt;b&gt; and &lt;strong&gt;, &lt;i&gt; and &lt;em&gt;?](https://stackoverflow.com/questions/271743/whats-the-difference-between-b-and-strong-i-and-em)
" %}

## Acessibilidade
Acessibilidade é a prática de fazer com que os seus sites sejam acessíveis para o maior número de pessoas.

- [MDN: Boas práticas em acessibilidade](https://developer.mozilla.org/pt-BR/docs/Learn/Accessibility/HTML)
- [w3.org: Developing for Web Accessibility](https://www.w3.org/WAI/tips/developing/)

{% include box-tip.html content="A ferramenta [Validator](https://validator.w3.org/) feita pela W3C (World Wide Web Consortium) avalia se o seu código HTML está bem escrito." %}

## Search Engine Optimization (SEO)
Otimização de mecanismos de pesquisa (SEO) é a técnica usada no seu site para aumentar a visibilidade nos mecanismos de pesquisa como Google e Bing.

- [Central da Pesquisa Google](https://developers.google.com/search/docs)

## CSS
CSS (Cascading Style Sheets ou Folha de Estilos em Cascata) é usado para estilizar suas paǵinas web.

- [MDN: Primeiros passos com CSS](https://developer.mozilla.org/pt-BR/docs/Learn/CSS/First_steps)
- [W3Schools: CSS Tutorial](https://www.w3schools.com/css/)

## Box model
Box model é basicamente uma caixa que envolve todo elemento HTML.

- [W3Schools: CSS Box Model](https://www.w3schools.com/css/css_boxmodel.asp)
- [Tableless: CSS Box Model](https://tableless.github.io/iniciantes/manual/css/box-model.html)

## Layout
A ferramenta escolhida para fazer o layout vai influenciar na acessibilidade do site nos navegadores antigos e o nível de complexidade de implementação.

### Display
A propriedade display é usada para controlar como os elementos são mostrados no site.

- [W3Schools: CSS Display](https://www.w3schools.com/css/css_display_visibility.asp)
- [Tableless: Propriedade Display](https://tableless.github.io/iniciantes/manual/css/display.html)

### Float
Usado para flutuar um elemento para a esquerda ou direita.

- [Tableless: Propriedade Float e Clear](https://tableless.github.io/iniciantes/manual/css/float-clear.html)
- [CSS Tricks: All About Floats](https://css-tricks.com/all-about-floats/)
- [W3Schools: CSS Floats](https://www.w3schools.com/css/css_float.asp)

### Position
Usado para definir o tipo de posicionamento de um elemento.

- [freeCodeCamp(): A propriedade position no CSS explicada e com exemplos](https://www.freecodecamp.org/portuguese/news/a-propriedade-position-no-css-explicada-e-com-exemplos/)
- [W3Schools: CSS Position](https://www.w3schools.com/css/css_positioning.asp)

{% include box-note.html content="Fazer layouts usando apenas float e position pode ser complexo de implementar, mas pode ser necessário se o objetivo é fazer um site que funciona bem em navegadores antigos como o Internet Explorer."%}

{% include box-tip.html content="[CanIUse](https://caniuse.com/) é um ótimo site para saber se uma propriedade, elemento, etc, funciona em uma versão de navegador específica." %}

### Flexbox
É uma forma mais eficiente de alinhar e distribuir espaço entre itens em um container.

- [MDN: Conceitos básicos de flexbox](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_flexible_box_layout/Basic_concepts_of_flexbox)
- [Jogo Flexbox Froggy](https://flexboxfroggy.com/)
- [CSS Tricks: A Complete Guide to Flexbox](https://css-tricks.com/snippets/css/a-guide-to-flexbox/)

### Grid
CSS Grid é uma forma de layout bidimensional baseada em grade.

- [MDN: Conceitos básicos de Grid Layout](https://developer.mozilla.org/pt-BR/docs/Web/CSS/CSS_Grid_Layout/Basic_Concepts_of_Grid_Layout)
- [Jogo Grid Garden](https://cssgridgarden.com/)
- [W3Schools: CSS Grid Layout Module](https://www.w3schools.com/css/css_grid.asp)
- [CSS Tricks: A Complete Guide to CSS Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)

{% include box-note.html content="Navegadores antigos como o Internet Explorer não possuem o flexbox e o grid totalmente implementado."%}

## Responsive Web Design (RWD)
Web Design Responsivo é a técnica de garantir que o seu site seja responsivo, ou seja, que se adapte bem a qualquer tamanho de tela.

- [W3Schools: Responsive Web Design](https://www.w3schools.com/css/css_rwd_intro.asp)
- [web.dev: Design Responsivo](https://web.dev/learn/design/welcome?hl=pt-br)

## Metodologias CSS
Modificar o código CSS vai ficando mais difícil conforme o sistema cresce de forma desorganizada ([código espaguete](https://pt.stackoverflow.com/questions/31315/o-que-%C3%A9-c%C3%B3digo-spaghetti)).

Uma metodologia CSS pode ser usada para dividir um site em unidades pequenas e modulares, facilitando a organização e manutenção do código.

### BEM
BEM é uma metodologia que trabalha com Blocos, Elementos e Modificadores (BEM). É uma convenção popular para dar nome às classes.

BEM é uma aplicação dos conceitos do OOCSS.

- [BEM: guia definitivo do padrão CSS mais famoso](https://desenvolvimentoparaweb.com/css/bem/)
- [BEM: Introduction](https://getbem.com/introduction/)
- [BEM: Naming](https://getbem.com/naming/)

### OOCSS
CSS Orientado a Objetos (OOCSS, sigla em inglês) busca reduzir repetição de código com objetos CSS, que é todo padrão visual que se repetirá no site.

- [Arquitetura CSS: OOCSS](https://allonsmandy.netlify.app/blog/arquitetura-css-oocss/)
- [Object Oriented CSS – A teoria das classes reutilizáveis](https://imasters.com.br/css/object-oriented-css-a-teoria-das-classes-reutilizaveis-oocss)

### SMACSS
Arquitetura Escalável e Modular para CSS (SMACSS, sigla em inglês). Seu objetivo principal é categorizar regras CSS.

- [SMACSS – Scalable and Modular Architecture for CSS](https://www.anselme.com.br/2024/05/29/smacss-scalable-and-modular-architecture-for-css/)
- [SMACSS](https://smacss.com/)

## Pré-processadores
Pré-processador é um programa que permite gerar CSS a partir de uma sintaxe única desse pré-processador, além de adicionar algumas funcionalidades extras que não existem no CSS puro.

### Sass
Sass é um pré-processador para CSS que adiciona funcionalidades como variáveis, aninhamento, mixins, entre outros.

- [Sass Basics](https://sass-lang.com/guide/)
- [Sass: documentation](https://sass-lang.com/documentation/)
- [W3Schools: Sass introduction](https://www.w3schools.com/sass/sass_intro.php)
- [O que é SASS? Venha entender esse novo método de escrever CSS](https://www.ufsm.br/pet/sistemas-de-informacao/2021/09/22/o-que-e-sass-venha-entender-esse-novo-metodo-de-escrever-css)

{% include box-note.html content="@import foi descontinuado e seu uso é desencorajado. Em seu lugar, use o @use e @forward.
- [Stop using @import with Sass](https://www.youtube.com/watch?v=CR-a8upNjJ0&ab_channel=KevinPowell)
- [The New SASS Module System: Out with @import, In with @use](https://stefaniefluin.medium.com/the-new-sass-module-system-out-with-import-in-with-use-e1bd8ba032d0)
"%}

{% include box-tip.html content="SASS tem integração nativa com BEM." %}

{% include box-tip.html content="Com o SASS, você pode usar a [estrutura de arquivos 7-1](https://sass-guidelin.es/#the-7-1-pattern): 7 diretórios, 1 arquivo." %}

## JavaScript
JavaScript permite adicionar interatividade aos sites.

- [W3Schools: JavaScript Tutorial](https://www.w3schools.com/js/)
- [MDN: Primeiros passos com JavaScript](https://developer.mozilla.org/pt-BR/docs/Learn/JavaScript/First_steps/What_is_JavaScript)

## DOM
O Document Object Model (DOM), é a interface entre a linguagem Javascript e os objetos do HTML.

- [rocketseat: Introdução ao DOM](https://blog.rocketseat.com.br/introducao-ao-dom/)
- [W3Schools: JS HTML DOM](https://www.w3schools.com/js/js_htmldom.asp)
- [JavaScript.info: DOM tree](https://javascript.info/dom-nodes)
- [Tableless: O que é DOM?](https://tableless.github.io/iniciantes/manual/obasico/oquedom.html)

## Gerenciador de pacote
Gerenciadores de pacote permitem gerenciar códigos escritos por você ou por outros.

### npm
npm é o gerenciador de pacote para JavaScript mais popular.

- [Modern JavaScript Explained For Dinosaurs](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html)
- [hostinger: O Que É npm?](https://www.hostinger.com.br/tutoriais/o-que-e-npm)

## Frameworks
Frameworks são códigos reutilizáveis escritos por alguém, que ajudam a solucionar problemas comuns com mais facilidade.

### Bootstrap
Bootstrap é uma ferramenta gratuita para desenvolvimento HTML, CSS e JS.

- [Bootstrap](https://getbootstrap.com.br/)

### React
React é a biblioteca para JavaScript mais popular atualmente.

- [React: início rápido](https://pt-br.react.dev/learn)
- [roadmap.sh: React Developer](https://roadmap.sh/react)

### Vue.js
Vue.js é uma framework JS de código livre para construir interfaces de usuários.

- [Vue: Introdução](https://pt.vuejs.org/guide/introduction.html)
- [roadmap.sh: Vue Developer](https://roadmap.sh/vue)

## Geradores de sites estáticos
Um gerador de site estático é uma ferramenta que gera um site HTML estático completo com base em dados brutos e um conjunto de modelos.

- [O que é um gerador de site estático?](https://www.cloudflare.com/pt-br/learning/performance/static-site-generator/)

### Jekyll
Jekyll é um gerador de site estático. Ele pega o conteúdo escrito em uma linguagem de marcação e usa layouts para criar um site estático. Jekyll é uma gema do Ruby, então é preciso instalar Ruby para poder usar Jekyll.

- [Step by Step Tutorial by Jekyll](https://jekyllrb.com/docs/step-by-step/01-setup/)
- [Jekyll Tutorial by Giraffe Academy](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)
- [Como criar um site com Jekyll e GitHub]({% link _guides/criar-site-com-jekyll.md %})