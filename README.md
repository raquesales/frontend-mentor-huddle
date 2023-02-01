# Frontend Mentor - Solução para a página inicial do Huddle

Esta é uma solução para o desafio Huddle do Frontend Mentor. [Huddle landing page with single introductory section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/huddle-landing-page-with-a-single-introductory-section-B_2Wvxgi0).


### O Desafio

Consiste em criar uma página onde o usuário poderá visualizar o melhor layout dependendo do tamanho de tela de seu dispositivo, além de observar como os elementos da página interagem ao estado de foco.

### Screenshot

<img src = "tela.gif" alt = "Tela inicial do projeto Hunddle">


### Feito com

[![IDE](https://img.shields.io/badge/Visual_studio_code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)](https://code.visualstudio.com/)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/pt-BR/docs/Web/CSS)

### Aprendizados

Neste projeto eu pude praticar, principalmente, como deixar o layout responsivo e também como posicionar os elementos na tela utilizando Flexbox e CSS Grid.

```css
.about {
    display: grid;
    grid-template-columns: 60% 40%;
}

@media(max-width: 786px) {
    .about {
       display: flex;
       flex-direction: column;
    }
}

```

### Desenvolvimento Contínuo

Esse teste foi dasafiador e percebi que ainda há muito para aprender sobre responsividade, Flexbox e CSS Grid.

### Author

- Frontend Mentor - [@raquesales](https://www.frontendmentor.io/profile/raquesales)


