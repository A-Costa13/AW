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
Este se puede incluir directamente dentro del head de esta forma
	```<script src="./javascript.js"></script>```
## ¿Que diferencia hay entre una clase y una ID
	El selenctor id está diseñado para ser añadido a un atributo único y así poder editar el estilo del mismo de forma individual.
	El selector class está diseñado para funcionar en varios elementos al mismo tiempo que pueden ser o no del mismo tipo.
## código para hacer un enlace a otra página y que esta se abra en una nueva ventana
	```<a href =”https://www.youtube.com/watch?v=mp28JPs25ek&ab_channel=ThePruld” target=”_blank”>Texto</a>.```
## ¿Qué son las pseudoclases?, pon ejemplos.
las pseudoclases son opciones concretas que se añaden a elementos para que estos funcionen de una forma determinada.
- Utilizando la pseudo clase :active en CSS cambia el estado del elemento en el que se utilice mientras el cursor está encima de este.
- Utilizando la pseudo clase :checked en CSS cambia el estado de un elemento para que este sea marcable de diferentes formas.
###### Ejemplos de pseudoclases en orden dentro de la carpeta Sandwichería a su vez dentro del repositorio AW.

## Explica el modelo de caja de CSS (margin, border y padding)
- Margin: El espacio que existe entre un elemento y los que tenga al rededor.
- Border: Es justo la línea que delita el borde del elemento.
- Padding: Es el espacio que hay entre el borde de un elemento y el elemento en si mismo, por ejemplo un texto.
## Explica que son los selectores de CSS y pon ejemplos
Los selectores CSS son las etiquetas a las que afectaran los parámetros que se establezcan inmediatamente después entre dos llaves {}.
- Selector universal * {}
- Selector de tipo o de etiqueta h1 {}; h2{}
- Selector descendente
- Selector de clase
- Selectores de id

