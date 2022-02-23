# Cores

Em cores temos três formas de declaramos uma cor que são elas:

- Pelo nome da cor
- Pelo formado rgb e rgba
- Pelo formado Hexadecimal

# Formato RGB e RGBA

O formato rgb expressa a junção de três cores: Vermelho, Verde e Azul. Necessitando então a tonalidade de cada uma dessas cores expressada por números entre 0 e 255.
0 seria a falta dessa tonalidade e 255 o valor máximo dessa tonalidade.

Quando colocamos a propriedade de algo com rgb passaremos então, na sequência, a tonalidade respectiva a ordem(RGB = Red, Green, Blue). Vamos exemplificar aplicando uma cor em um parágrafo:

Queremos por exemplo, que ele fique azul:

    p {
        color: rgb(0,0,255);
    }

O parágrafo acima possui os valores mínimos em Vermelho e Verde, e valor máximo em azul -> Seguindo a sequencia RGB

Se quisessemos que o parágrafo tenha a cor vermelha:

p {
    rgb(255, 0, 0);
}

Agora o parágrafo possui sua cor totalmente vermelha.

O formato rgba possui exatamente o mesmo funcionamento que o formato rbg, a única diferença é que ele possui uma "cor" a mais, que no caso é a ***transparência.***
Também é expresso por números mas ao invés de variar entre 0 e 255 varia somente entre 0 e 1. Onde 0 é o mais transparente e 1 o mais opaco. Por exemplo:

    p {
        color: rgba(0,0,255, 0.5);
    }

No parágrafo acima podemos identificar que ele possui a cor vermelha mas está em sua metade transparente.

# Formato Hexadecimal

O formato hexadecimal expressa as tonalidades de cores exatamente como o rgb expressa mas em valores diferente. O hexadecimal utiliza o sistema numérico hexadecimal que vai de 0 a 16, expressos por 0 até 9 e A até F, totalizando 16 'graus' de cores. Como exemplo colocaremos a cor azul em um parágrafo:

    p {
        color: #0000FF;
    }
Dessa forma expressamos somente o azul e mais nenhuma tonalidade de Vermelho nem Verde.