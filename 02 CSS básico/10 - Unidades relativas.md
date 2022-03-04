# Unidades de medidas relativas

## Unidade `em`:
A unidade de medida `em` é uma unidade que erda seu valor do elemento pai. Por exemplo:
HTML:

    <div class="container">
        Texto da div
        <div class="interno">
            Texto interno
        </div>
    </div>

CSS:

    .container{
        font-size: 20px;
    }

    .interno{
        font-size: 1em;
    }

Neste exemplo o texto da classe `interno` possui exatamente o mesmo valor erdado da classe `container`, pois atribuimos o valor ***1em***. Caso atribuirmos o valor de ***2em***, o valor atribuido seria 40px, pois seria 2x o valor que a classe `interno` possui.

## Unidade `rem`:
A unidade de medida relativa `rem` possui as mesmas características de `em` mas sua diferença se da no elemento o qual ele erda. Enquanto o `em` erda do elemento pai o `rem` erda do elemento raiz (html). Então se atribuirmos o valor de `font-size: 20px` no html e por exemplo, atribuirmos `1rem` a um parágrafo ele erdará os 20px do html.

## Unidade `vw`:
Essa unidade tem por base o tamanho da tela do navegador em relação ao comprimento. Quando declaramos por exemplo 50vw estamos dizendo que queremos que, independente do tamanho da tela, o elemento ocupe 50% do tamanho total de comprimento. Se colocassemos 15vw estamos declarando que o elemento irá ocupar 15% do tamanho da tela no navegador.

## Unidade `vh`:
Essa unidade tem por base o tamanho da tela do navegador em relação a altura. Quando declaramos por exemplo 100vh estamos dizendo que queremos que o elemento ocupe 100% da altura do navegador.

## Unidade `%`:
Essa unidade tem por base o elemento pai. Por exemplo duas divs uma dentro da outra. Caso a div de fora possua um tamanho ajustável, como por exemplo o `vw`, se declaramos que a div interna possua um width de 100%, mesmo que aja alteração no valor da div externa, a div interna se adequará.