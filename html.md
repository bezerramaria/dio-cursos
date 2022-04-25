#HTML

##Curso: Introdução a criação de websites com HTML5 e CSS3

###Estrutura HTML

- etiqueta de abertura (pode incluir nome do atributo e valor)
- conteúdo
- etiqueta de fechamento

Exemplo:
<h1 class="titulo">Aqui coloca o conteúdo. </h1>

###Estrutura Básica

<!DOCTYPE html>
<html>
	
	<head>
		<meta charset="UTF-8">
		<title>  </title>
	</head>

	<body>
	</body>

</html>

####Semântica

*<section>*

Representa uma seção genérica de conteúdo quando não houver um elemento mais específico para isso.

*<header>*

É o cabeçalho da página ou de uma seção da página e normalmente contém logotipos, menus, campos de busca.

*<article>*

Representa um conteúdo independente e de maior relevância dentro de uma página, como um post de blog, uma notícia em uma barra lateral ou um bloco de comentários. Um article pode conter outros elementos, como header, cabeçalhos, parágrafos e imagens.

*<aside>*

É uma seção que engloba conteúdos relacionados ao conteúdo principal, como artigos relacionados, biografia do autor e publicidade. Normalmente são representadas como barras laterais.

*<footer>*

Esse elemento representa o rodapé do conteúdo ou de parte dele, pois ele é aceito dentro de vários elementos, como article e section e até do body. Exemplos de conteúdo de um <footer> são informações de autor e links relacionados.

#####Textos e Links

<h1>-<h6>
Parágrafos

- <p> representa um parágrafo

- <a> significa anchor/âncora, ele representa um hyperlink

- href e o target são atributos do elemento a

- O href representa o hyperlink para onde sua âncora aponta.

- O target neste momento vai servir para nos ajudar a abrir nossos links em outra aba do navegador usando o valor _blank.
