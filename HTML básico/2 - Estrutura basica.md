# Estrutura básica de uma página HTML

Toda página HTML deve começar com um ***comando*** e não uma tag. Esse comando é: `<!DOCTYPE html>`.

> Esse comando indica para o navegador que estamos utilizando a versão mais recente do HTML.

A Segunda tag necessária em um documento html é a própia tag `<html>`


> Nós colocaremos todo o conteúdo entre a tag de abertura e de fechamento da tag `<html>`

A terceira tag é uma tag que se chama: `<head>`.
> Dentro dela colocaremos tags de configuraçoes como codificação, título da aba, icone da aba etc. Ela possui tag de fechamento.

Nossa última tag é a tag `<body>`.
> Nela que colocaremos nosso conteúdo. Título, parágrafos, imágens etc.

<hr>

Dentro da tag `<head>` devemos colocar tags de configuração, como dito anteriormente. Existem tags super importantes que sempre devemos utilizar, que são:

    <meta charset="utf-8"> -> Tag de formatação.
    <title> Titulo da aba </title> -> Tag de título da aba.

> Podemos perceber que a tag meta possui mais conteúdo que as outras. Isso porque ela possui um atributo (charset) e isso é que faz a configuração das letras serem exibidas conforme necessario. Ela é uma tag self-closing, ou seja, não possui tag de fechamento.

Em resumo a estrutura básica de uma página HMTL fica:

    <!DOCTYPE html>
    <html>
        <head>
            <meta charset="utf-8">
            <title>Título da janela</title>
        </head>
        <body>
                aqui colocaremos nosso conteúdo de fato, como parágrafos, títulos, imagens etc.
        </body>
    </html>



dica: Um site muito bom que pode nos auxiliar com HTML, CSS e JavaScitp:
http://www.w3schools.com