# Tag Div

A tag `<div>` é uma tag que faz o papel de um conteiner para outros elementos html, agrupando os elementos específicos determinados. A tag ainda faz a função de divisão de conteúdo, mas essa tag não possui semântica. Ela cria uma divisão genérica que muitas vezes pode ser substituída por outra tag de mesma função, mas contendo semântica. Por exemplo:

Podemos criar uma barra de navegação "menu" superior de uma página:

    <div>
        <ul>
            <li><a href=#>Home></a></li>
            <li><a href=#>Home></a></li>
            <li><a href=#>Home></a></li>
            <li><a href=#>Home></a></li>
        </ul>
    </div>

Teremos o mesmo efeito mas não possuimos seântica ao utilizarmos a tag div, então utilizamos aqui uma mais específica: 
    
    <nav>
        <ul>
            <li><a href=#>Home></a></li>
            <li><a href=#>Home></a></li>
            <li><a href=#>Home></a></li>
            <li><a href=#>Home></a></li>
        </ul>
    </nav>