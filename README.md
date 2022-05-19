# Construindo seu Primeiro Site (HTML e CSS)

## MÓDULO: CSS

### AULA: Seletores, Classes e Pseudo-classes

#### SELETORES:

`Por tag/elementos:`

    h1{ color:red; }

`Seletor universal:`

    *{color:blue;}

`Seletor de um elemento que esta dentro de outro elemento:`

    p strong{color:red;}

`Selecionar um elemento que esta logo depois de outro elemento:`

    li + li + li {padding-left:15px;}


`Selecionar por classe:`

    .sec{background-color:orange;}

`Selecionar por id:`

    #publicacoes{color:brown;}

`Selecionar mais de um elemento usando varios tipos de seletores:`

    #publicacoes, .sec, h1 {margin:20px;}

`Selecionar um elemento específico que contém um atributo específico:`

    a[href="#formacao"] {padding-left:50px}


#### PSEUDO-CLASSES

`Quando tivermos o elemento focado ou passarmos o mouse por cima do elemento o nosso elemento ele muda de cor:`

    a:link {background-color: yellow;}
    a:focus,a:hover {background-color: pink;}

`Acrescenta conteúdo dentro do nosso elemento,acrescenta no inicio:`

    a:before { content: "Ola " }

`Acrescenta conteúdo dentro do nosso elemento,acrescenta no final:`

    a:after { content: " Tchau" }



