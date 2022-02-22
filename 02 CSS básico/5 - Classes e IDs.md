# Classes e IDs

Quando utilizamos o CSS exteno anteriormente percebemos que o seletor CSS aplica os estilos de modo geral(em todas as tags) e não em uma especifica. Por exemplo, se utilizamos o seletor `<p>` todos os parágrafos serão modificados e não somente um específico. E por esse motivo que existe classes e ids.

## IDs

IDs são identificadores que podemos atribuir aos elementos HTML. Por exemplo, queremos que especificamente um parágrafo (e mais nenhum outro) tenha a cor cinza. Basta simplesmete em sua tag acrescentar um atributo `id` e seu valor iremos inserir um 'nome' com o intúito de identificação. Por exemplo:

    <p id="paragrafo-cinza"> ..... </p>


Agora em nosso arquivo CSS devemos utilizar o nome que foi dado e atribuir todos os estilos. Para isso devemos utilizar o (#) seguido de seu nome. Exemplo:

    #paragrafo-cinza{
        color: gray;
    }

***Atenção:*** Esse recuso de ID devem ser usado para um único elemento. Dois ou mais elementos não podem ter o mesmo ID. ID é único e deve ser utilizado somente em uma tag.

***Dica*** Ao atribuirmos um ID para um elemento HTML ele pode ser redirecionado através de um link `<a>`. Por exemplo, ao colocarmos que um parágrafo possui ID="texto-principal" e em qualquer lugar de nossa página criarmos um link que seu atributo `href` tenha como valor o ID do parágrafo(texto-principal), ao clicarmos nesse link seremos levados para a localização exata do parágrafo que contém esse ID.

    <a href="#texto-principal">Notícia</a>

        ...
    <p id="texto-principal">
        ...
    </p>


Neste exemplo ao clicarmos no link ***Notícia*** seremos redirecionados ao local exato onde o parágrafo que contem o id="texto-principal" está.
## Classes

Classes são identificadores para grupos determinados de tags. Podemos incluir em um grupo de tags uma classe e a partir disso podemos alterar o visual somente desse grupo de tags específicas. Diferentemente do ID que podemos selecionar somente uma tag. Para as classes incluiremos o atributo `class` em todas as tags que precisarmos e em seguida colocaremos em seu valor o nome para essa classe. Por exemplo:

    <p class="texto-padrao">
        ...
    
    </p>

    <p class="texto-padrao">
        ####    
    </p>

    <p class="texto-padrao">
        ***
    </p>

Aqui no nosso HTML atribuimos a classe a três parágrafos que queremos modificar o estilo. Agora em CSS iremos escrever o nome da classe precedido de um ponto (.):

    .texto-padrao {
        color: purple;
    }

Com essa declaração todos os paragráfos que tiverem o atributo `class` com o valor `texto-padrao` terá sua cor alterada para roxo.