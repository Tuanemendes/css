
# Estudos CSS

![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)



<h2>Índice</h2>

* [Objetivo geral](#descrição-do-projeto)
* [Ferramentas Utilizadas](#ferramentas-utilizadas)
* [ O que é CSS](#)
* [Construção](#cosntrucao)
* [Desenvolvido Por](#desenvolvido-por)


<h2>💻Objetivo geral </h2>

<p>

* Fundamento CSS;
* Estilização básica com CSS;
* Unidade de Medida; 
* Posicionamento e displays; 
* Alinhamento de elementos(flexbox e grid);
* Responsividade;

</p>

<h2>🛠️Ferramentas Utilizadas</h2>

<p>

🟢  Sistema operacional Linux <br>
🟢  Editor de código VsCode<br>
🟢  Extençõés Emmet, Live Server
</p>


<h2>👩‍🎓 O que é CSS</h2>

<p>
Cascading Style Sheets(CSS) , ou folha de Estilo em Cascata, é um mecanismo para adcionar estilos a um documento  web (HTML)
<br>
Determina como deve ser o layout de um página e como os elementos do nosso site deve ser;
<br>
Criado em 1994  por Hakon Wium Lie para facilitar programação de sites.
<br> 
1995 o CSS1 foi desenvolvido pela W3C.
<br>
1997/1999 o CSS ficou conhecido porpularmente e atualemnte se encontra na versão CSS3.
<br>
Lembrando que o CSS não é um linguagem de programação e nem de marcação, mas sim de estilos. 
</p>

<h2>👩‍🎓 O que criar com o CSS</h2>
<p>
Layouts e estruturas de página;

Cores e fundos;

Tipografia;

Efeitos visuais;

Posicionamento e alinhamento;

Responsividade;

Formulários;

Navegação, Animações, Filtros;

</p>

<h2> ⛏️ Formas de declarar o CSS</h2>

<p>
<strong>CSS Inline: </strong> é adcionado o CSS utilizndo o atributo style dentro das tags HTML por elemento, Esta forma não é muito recomentado por causa do gerenciamento do CSS o que é um desvatagem caso precise fazer alterações tem que se fazer onde esta cada linha, outra importante informação é o inline sempre terá uma maior prioridade sobre as demais formas, fazendo como que possa sobrescrever outros estilos em casos necessários. </p>

```<h1 style="color: red; ">Trilha de CSS</h1>```
<br>

<strong>CSS Interno: </strong> O código é adicionada dentro da tag `<head>` da pagina HTML , é adicinado dentro dessa tag outra tag `<style>` onde é passado as regras de CSS, a vantagem é de esta tudo dentro de um mesmo arquivo , o que facilita o carregaento da página, por outro lado o gerecimento só fica disponivel para a mesma pagina se caso quiser utilizar em outros locais teria de copiar o estilo gerando  de forma repetida.
<br> 

```   <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>trilha CSS</title>
    <style>
        h1{
            color: red;
            background-color: black;
        }

    </style>

</head>
<body>
    <h1 >Trilha de CSS</h1>
</body>
</html>  

```

<strong>CSS Externo: </strong>  é criado por meio de um arquivo com a exteção .css  onde se tem todas as regras que podem ser aplicadas dentro do arquivo permitido ser utilizados dentro de todo projeto evitando as repições de estilos e melhorar o gerenciamento dos estilos, para referenciar o arquivo é necessário criar um tag  `<link> no HTML para indicar o caminho do arquivo com a exteção .css.

<br>

Arquivo index.html 
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="assets/css/style.css">
    <title>trilha CSS</title>
 

</head>
<body>
    <h1 >Trilha de CSS</h1>
</body>
</html>


```
Arquivo style.css

```
h1{
    background-color: black;
    color: red;
}
```

</p>


<h2> ⛏️ Seletores CSS</h2>

<p>
*Seletor de Tags : busca elementos por uam tag HTML 
<br>
*Seletor por Id (#):busca elementos através do atribruto id  
<br>
*Seletor por class (.):  busca elementos através de class 
<br>
*Seletor Universais(*): seleciona todos os estilos HTML
<br>
*Seletor atributo ([nameatribut="valor"]) ou ([nameatribut~="valor"])ou ([nameatribut|="valor-valor"])   : Seleciona elementos que tem nome do atributo e valor. para prefixo do atributo [nameatribut^="valor"] e paa fixos [nameatribut$="valor"] em qualquer lugar que tenha o valor [nameatribut*="valor"]

</p>
<h2> ⛏️Combinadores CSS</h2>

* Agrupamento 
<br>
* Combinador Descendente 
<br>
* Combinador Filho 
<br>
* Combinador Irmão
<br>

<h2> ⛏️ Construção</h2>

<p>
Primeiro processo...
</p>

<h2> 👩‍💻 Desenvolvido Por</h2>


Realizado o desafio por [Tuane](https://www.linkedin.com/in/tuane-mendes/)
