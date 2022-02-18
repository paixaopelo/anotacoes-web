# Tabelas

O HTML permite criarmos tabelas em nossos documentos. Utilizaremos mais tags que o convencional para criarmos tags e suas céluas.

Para criamos uma tabela utilizaremos as tags `<table> ... </table>`. Dentro dessas tags devemos utilizar uma tag chamada `<tr>`. Essa tag é necessária para criarmos uma linha em nossa tabela, então sempre que formos criar uma nova linha devemos utilizar essa tag. Dentro dessa tag `<tr>` podemos criar um cabeçalho ou colocarmos dados dentro dessa tabela. Para colocarmos um cabeçalho utilizaremos a tag `<th>...</th>` e para colocarmos dados utilizaremos a tag `<td>`. Por exemplo:

    <table>
        <tr>
            <th>Nome</th>
            <th>Telefone</th>
            <th>Email</th>
        </tr>
        <tr>
            <td>João da Silva</td>
            <td>61999999999</td>
            <td>joao.dasilva@gmail.com</td>
        </tr>
    </table>
