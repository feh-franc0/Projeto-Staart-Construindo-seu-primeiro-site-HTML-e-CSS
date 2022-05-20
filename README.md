# Construindo seu Primeiro Site (HTML e CSS)

## MÓDULO: CSS

### AULA: Animações

#### Animações:

`Animações:`

    a{
        background-color: #E5E5E5;
        margin-left: 0px;
        transition-property: background-color, margin-left;
        transition-duration: 1s;
    }

    a:hover, a:focus{
        background-color: yellow;
        margin-left: 10px
    }

`Keyframes:`

- Keyframes nos permitem indicar o estado inicial e final do estilo CSS em uma animação. Nós podemos,inclusive,indicar o estado do estilo CSS em nenhum ou vários pontos de uma animação entre o início e o fim dela

    @keyframes anima {
        0% {top:0; left:0;}
        30% {top: 50px;}
        60% {left: 50px;}
        100% {top:100px; left:100px;}
    }

    nav{
        position: absolute;
        animation-name: anima;
        animation-duration: 3s;
        animation-iteration-count: infinite;
        animation-direction: alternate;
    }