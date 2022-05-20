# Construindo seu Primeiro Site (HTML e CSS)

## MÓDULO: CSS

### AULA: Fontes

#### Fontes:

`para usar uma fonte:`

    font-family: Arial, Helvetica, sans-serif;

`para por o tamanho da fonte:`

    font-size: 10px;

`outros tipos de estilizaçãod e fonte:`

    font-style: italic;
    font-weight: bold;
    
`tamanho da linha:`

    line-height: 20px;

`Para definir fontes que estão na internet e passar para o nosso site:`

    <style>
    @import url('https://fonts.googleapis.com/css2?family=Macondo&display=swap');
    </style>

    font-family: 'Macondo', cursive;

`caso a gente baixe uma fonte e queira pegar no nosso diretorio:`

    @font-face{
        font-family: "Supermercado One";
        src: url(./Supermercado_One/SupermercadoOne-Regular.ttf);
    }

    font-family: "Supermercado One";