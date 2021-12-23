# Introdução a criação de websites com HTML5 e CSS3

**Instrutor: Lucas Vilaboim**  

<br>  

- HTML criado em 1991;


- Existem 5 versões (HTLM5 lançado em 2014);<br>

<br>

## Estrutura básica de um documento HTML -

<br>**`<!DOCTYPE html>`** - informa ao navegador o que está sendo escrito (não é um elemento HTML).

**`<html>`** -  inicia os elementos (é a raiz do documento).

**`<head>`** -  teremos meta informações (informações usadas por um navegador, buscador de internet...).

> > **`<meta charset="UTF-8">`** -  codificação de caracteres que será utilizada pelo sistema.

> > **`<title> </title>`** -  coloca o título na aba do navegador.

**`</head>`**

**`<body>`** -  onde estará o conteúdo da página.<br>

**`</body>`**

**`</html>`**  

 <br><br>**OBS:** só pode haver um **`<h1>`** por página.  

  <br><br>

## Alguns elementos de semântica -  

<br>**`<section>`** - representa uma seção genérica de conteúdo. Ex: uma lista de artigos.

**`<header>`**  - cabeçalho da página ou de uma section.

**`<article>`** - representa um conteúdo relevante dentro de uma página, como um post de um blog.

**`<aside>`**   - é uma seção que engloba conteúdos relacionados ao conteúdo principal. Ex: artigos relacionados, biografia do autor e publicidade.

**`<footer>`**  - rodapé da página, de um section, um article e até do body.

**`<h1>-<h6>`** - marcar importância de títulos.<br><br><br>

# Introdução e Conceitos básicos do CSS3<br>

**Instrutor: Lucas Vilaboim** 

<br><br>

Criada em 1996.  É uma linguagem de estilo, você cria regras de estilo para elementos ou grupo de elementos.

**Ex:** uma regra **CSS** é formada por um seletor ou um grupo de seletores.  Dentro de um par de chaves temos as declarações.<br>

<br>

`a, p, h1, h3 {`

`color: blue;`

`font-size: 14px;`

`}`

<br>

Uma regra **CSS** é formada por um seletor ou um grupo de seletores (elementos **HTML**).<br>

Dentro de um par de chaves temos as declarações.<br>

Uma declaração é formada por uma propriedade e um valor.<br><br>

## ID x Classe

<br>

No **CSS**, uma **Classe** é precedida por um ponto ".".<br>

O **Id** é precedido por um "#".  Um **Id** só pode ser usado uma vez por página.<br><br><br>

## BOX Model

<br>

Num layout de um site, o navegador representa cada elemento **HTML**, com uma caixa retangular chamada **"Box Model"**.<br>

Possui 4 áreas: margin, border, padding e content.<br>

![Box model](https://github.com/JefreyJones/dio-desafio-github-primeiro-repositorio/blob/main/Cursos/Introducao%20a%20HTML%205%20e%20CSS%203/imagens/Box-model.png)

**Margin** - espaçamento entre elementos.<br>

**Border** - circundam o padding e o content.  Podemos alterar a aparência (largura e cor).<br>

**Padding** - espaçamento entre a **"Border"** e a **"Content"**.<br>

**Content** - é o que o seu bloco representa: um texto, uma imagem ou um vídeo.<br>

<br>

## Estilizando elementos<br>

<br>

### Padding e Margin

<br>

Se quisermos atribuir tamanhos diferentes para cada lado, podemos fazer de 3 formas:<br>

1 - Colocando 1 valor para as partes superior e inferior, depois para os lados esquerdo e direto.<br>

**Ex:**<br>

.post {

padding: 10px 5px;

}

Neste exemplo, o valor **"10px"** (eixo y - superior e inferior) e **"5px"** (eixo x - esquerdo e direito).<br><br>

2 - Colocando um valor para cada lado.<br>

**Ex:**<br>

.post {

padding: 10px 15px 5px 0;

}

Neste exemplo, o valor **"10px"** (topo),  **"15px"** (direita), **"5px"** (parte inferior) e **"0"** (lador esquerdo).<br><br>

3 - Usando as proriedades específicas para cada lado.  Mais uado quando temos uma padding ou margin com os 3 lados iguais e somente 1 diferente.<br>

**Ex:**<br>

.post {

padding-top: 15px:

padding-right: 10px;

padding-botton: 5px;

padding-left: 0;

}

<br>

