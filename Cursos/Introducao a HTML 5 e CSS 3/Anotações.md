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

![Box model](C:\Users\jefre\OneDrive\Documentos\Cursos\Dio.me\Projetos\dio-desafio-github-primeiro-repositorio\Cursos\Introducao a HTML 5 e CSS 3\imagens\Box-model.png)

**Margin** - espaçamento entre elementos.<br>

**Border** - circundam o padding e o content.  Podemos alterar a aparência (largura e cor).<br>

**Padding** - espaçamento entre a **"Border"** e a **"Content"**.<br>

**Content** - é o que o seu bloco representa: um texto, uma imagem ou um vídeo.<br>
