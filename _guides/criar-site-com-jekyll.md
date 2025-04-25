---
title: Como criar um site com Jekyll e GitHub
---
Jekyll é o gerador de site estático mais popular atualmente. Esse guia contém materiais para aprender a usar o Jekyll e hospedar o site com o GitHub Pages, além de usar GitHub actions para gerar o site automaticamente.

## Jekyll
Jekyll é um gerador de site estático. Ele pega o conteúdo escrito em uma linguagem de marcação e usa layouts para criar um site estático. Jekyll é uma gema do Ruby, então é preciso instalar Ruby para poder usar Jekyll.

Este site, por exemplo, foi criado usando Jekyll, e todo o conteúdo está escrito em arquivos Markdown. O conteúdo também pode ser escrito em HTML, que também é uma linguagem de marcação.

Links para aprender Jekyll:

- [Step by Step Tutorial by Jekyll](https://jekyllrb.com/docs/step-by-step/01-setup/)
- [Jekyll Tutorial by Giraffe Academy](https://www.youtube.com/playlist?list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB)

## GitHub Pages
GitHub Pages é um serviço de hospedagem gratuito de sites estáticos que pega arquivos HTML, CSS e JS de um repositório e publica um site. 

- [What is GitHub Pages?](https://docs.github.com/en/pages/getting-started-with-github-pages/what-is-github-pages)

O Jekyll possui integração nativa com o GitHub Pages, então basta mandar os arquivos fonte de um projeto Jekyll que o GitHub gera o site automaticamente. 

Porém, o site gerado localmente com o Jekyll nem sempre é o mesmo que o GitHub gera, além disso, nem todo plugin do Jekyll é suportado. Veja os plugins suportados pelo GitHub [aqui](https://pages.github.com/versions/).

{% include box-note.html content="Na criação deste site, tive um problema em que o GitHub Pages não conseguia compilar arquivos Sass com regras @use na construção do site, assim o site ficava sem estilos CSS, mas o site gerado localmente com Jekyll funcionava perfeitamente. Uma solução é trocar o @use pelo @import, porém essa regra é obsoleta e não deve mais ser usada em novos projetos." %}

## GitHub Actions
GitHub Actions é uma plataforma de Integração Contínua e Entrega/Implantação Contínua (CI/CD) que permite automatizar a pipeline de construção, teste e implantação.

- [Entendendo o GitHub Actions](https://docs.github.com/pt/actions/about-github-actions/understanding-github-actions)

No contexto de sites Jekyll, é possível usar GitHub Actions para construir e implantar sites Jekyll automaticamente com qualquer mudança no repositório do site, sem limitações de plugins e temas. O site construído é idêntico ao site construído localmente.

O Jekyll já fornece um fluxo de trabalho pronto para construção e implantação de sites Jekyll no GitHub. Para saber como usar, siga o tutorial no site do Jekyll:

- [Automatic Deployment with GitHub Actions](https://jekyllrb.com/docs/continuous-integration/github-actions/)
