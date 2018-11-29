# AW
## Estructura mínima de una web
```
<html>
	<head>
		<title></title>
	</head>
	<body>
	</body>
</html>
```
## Explica las 3 formas de usar CSS en HTML
- CSS Externo.
De esta forma se linkea un documento con los estilos CSS desde el inicio del documento para así acelerar lo máximo posible la carga de la página por el navegador
	```<link rel="stylesheet" type="text/css" href="index.css" />```
- CSS Interno.
Esta es la forma que más hemos utilizado en clase y al igual que en el CSS Externo este se incluye en la cabecera del fichero de HTML5  aunque esta vez directamente utilizando el atributo <style>.
```
<html>
<head>
    <title>Título de la página</title>
    <style type="text/css">
        div {
            background:#FFFFFF;
        }
    </style>
</head>
```
- CSS Embebido.
Esta es la forma más sencilla sw utilizar el CSS, no es muy recomendable y consta de utilizar el atributo style directamente en la etiqueta de, por ejemplo un párrafo <p>
```<p>¿Sabes <span style="color:#FF0000">VAREAR OLIVOS</span>?</p>```
	
## Crea una lista sin ordenar con 5 ingredientes de una receta de cocina
#### Tortilla de patata
- Huevo
- Patata
- Aceite
- Sal
- Cebolla (o no)
## Como se puede incluir javascript en HTML
Este se puede incluir directamente dentro del <head> de esta forma
	```<script src="./javascript.js"></script>```
## ¿Que diferencia hay entre una clase y una ID
	El selenctor id está diseñado para ser añadido a un atributo único y así poder editar el estilo del mismo de forma individual.
	El selector class está diseñado para funcionar en varios elementos al mismo tiempo que pueden ser o no del mismo tipo.
## código para hacer un enlace a otra página y que esta se abra en una nueva ventana
	
## ¿Qué son las pseudoclases?, pon ejemplos.
## Explica el modelo de caja de CSS (margin, border y padding)
## Explica que son los selectores de CSS y pon ejemplos

