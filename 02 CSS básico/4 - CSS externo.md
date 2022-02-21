# CSS Externo

Nossos códigos CSS preferencialmente deve ser armazenados em um arquivo externo, como no exemplo a seguir. Mas existem alguns casos que as outras duas maneiras são mais indicadas e veremos posteriormente.

CSS externo consistem em criarmos um documento separado do HTML somente para armazenar nossos códigos css. Devemos realizar duas ações para utilizarmos o CSS externo:

- Criar um arquivo com a extensão .css
- Linkar ao arquivo HTML nosso arquivo CSS.

Para criarmos esse arquivo a única regra é que ele tenha a extensão .css. Pode possuir qualquer nome, e dentro faremos nossas declarações css com os seletores que vimos anteriormente.

Já em nosso arquivo HTML incluiremos a tag `<link>` onde a mesma receberá dois atributos: `rel` e `href`.

- rel: atributo que recebe a relação referente ao arquivo que será carregado. *Stylesheet* será o valor atribuido aqui no nosso caso. 

- href: atributo que receberá o caminho/nome do arquivo .css

Exemplo:

Arquivo CSS:

nome do arquivo: <ins>style.css</ins>

    p {
        color: red;
    }

Arquivo HTML:

    <!DOCTYPE html>
        <html>
            <head>
                ...
                <link rel="stylesheet" href="style.css">
            </head>
            <body>
                ...
            </body>
        </html>