# Curso de HTML 5

## Aula 04 - Figure, Favicon, Metatags

* Figure: Semântica da tag figure
* Favicon: ícone que aparece na aba do navegador
* Metatags: determinam comportamentos da nossa página

### Tags utilizadas na aula

* figure
* meta
* link

### Link para criar favicon
<https://genfavicon.com/pt/>

### Favicon

* Ícone Favorito, ele aparecerá na aba do navegador
* na identificação da página quando for adicionada em favoritos

### Tags meta

* Determinam comportamentos da nossa página
* Possuem vários atributos, charset, http-equiv, content, name.

~~~html
<!-- definir mapa de caracteres ou codificação de caracteres -->
<meta charset="UTF-8">

<!-- indicar compatibilidade com internet explorer -->
<meta http-equiv="X-UA-Compatible" content="IE=edge">

<!-- definir área visível largura 'responsividade' -->
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<link rel="icon" href="img/favicon.png" /> <!-- favicon -->
~~~

#### Atributos meta
* charset="UTF-8" determina o mapa de caracteres.
* http-equiv e content
* name, content

### link
~~~html
<!-- favicon -->
<link rel="icon" href="img/favicon.png" />

<!-- importar arquivo CSS -->
<link rel="stylesheet" href="css/style.css" />
~~~
