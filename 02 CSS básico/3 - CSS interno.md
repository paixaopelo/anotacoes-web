# CSS interno

Para utilizarmos CSS internamente em nossos documentos HTML, dentro da tag `<head>` colocaremos a tag `<style>`. Dentro dessa tag iremos colocar todo código CSS de nossa página.

    <head>
        <style>
            Aqui fica os códigos css.
        </style>
    </head>

## Seletores CSS
Agora que colocamos a tag podemos iniciar com nossos códigos CSS. Para isso devemos utilizar os chamados <ins>Seletores CSS</ins>. Eles que dirão para o navegador qual elemento HTML queremos aplicar o estilo. 

Os seletores CSS possuem o mesmo nome das tags HTML. Então por exemplo, quando quisermos selecionar parágrafos, utilizaremos o seletor ***p***, para título principal utilizaremos seletor ***h1*** e assim por diante.

Logo após o seletor abriremos chaves ({}). Colocaremos então todos os atributos ***CSS*** dentro delas. Dessa forma:

    p{
       color: red; 
    }

No exemplo acima selecionamos ***todos*** os parágrafos e atribuimos a cor vermelha.

## selecionando todos os elementos

Importante sabermos que ao utilizarmos seletores desse modo, estaremos atribuindo a todos os elementos que possuem a mesma tag. No exemplo acima atribuimos a todos os parágrafos da página a cor vermelha. Futuramente iremos aprender como selecionar um parágrafo específico e um também como selecionar um conjunto de parágrafos.

## Exemplo de declaração interna

Como resultado teremos essa estrutura:

    <head>
        <style>
            p{
                color: red;
            }
        <\style>
    <\head>