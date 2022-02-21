# Links

Links possibilita acessarmos outras páginas. Através do click, podemos ir de uma pagina a outra.

Para utilizarmos links usaremos a tag `<a>` que receberá uma propriedade `href` acompanhada do endereço da página. Esse href significa hyperlink reference, ou seja, referência para uma outra página html. O uso dessa tag ficará assim:

    <a href="contato.html>Nome da página</a>

Utilizamos o nome do arquivo "contato.html" por considerar que as duas páginas estão na mesma pasta. Caso o arquivo contrato.html estivesse em uma pasta chamada por exemplo: links, faremos o seguinte:

    <a href="links/contato.html>Contato</a>

Caso não estivermos essa página em nosso projeto, utilizaremos link absoluto.

Link absoluto é o endereço completo de uma página, e aconselha-se utilizar somente em sites externos. Ex:

    <a href="https://www.google.com>Google</a>
    <a href="https://www.facebook.com>Facebook</a>
