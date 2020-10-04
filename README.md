
# Crea tu propia aplicación de dibujo con Scratch

![Imagen principal](assets/app-dibujo-con-scratch.png)

## Descripción del taller

Crearemos una aplicación con Scratch para generar tus propios dibujos.

El Lápiz es una herramienta muy poderosa en Scratch. En parte basada en su precursor, [LOGO](https://g.co/kgs/VzQyzc), las posibilidades más extensas de Scratch permiten elaborar mucho más que sólo pintar.

En este tutorial te vamos a enseñar cómo pintar y dibujar con el ratón en Scratch: cuando haces clic, que vaya dibujando sobre el escenario; cuando levantas el dedo del ratón, que deje de dibujar.


![Vista previa de la aplicación](assets/vista_previa_lapiz.png)

## Requisitos

- Computadora (preferentemente), tablet o smart phone.
- Conexión a internet.
- Conocer qué es Scratch (Deseable)

## ¡Comencemos!

![Lápiz](assets/lapiz.png)


1.	Para iniciar, deberemos crear nuestro proyecto, para ello iremos a la [página de inicio de Scratch](https://scratch.mit.edu/)

![Página inicio Scratch](assets/inicio.png)

2.	Y daremos clic en el botón “Start creating” o “Empezar a crear”:

Inglés:
>-------
![Start creating](assets/empezar-a-crear-en.png)

Español: 
>-------
![Empezar a crear](assets/empezar-a-crear-es.png)

Ahí se abrirá nuestro espacio de trabajo. Donde también veremos diversas categorías de instrucciones para codificar.

Algo sencillo pero que nos puede dar muchas ideas para continuar programando, sobre todo para realizar proyectos artísticos y creativos.

### Cambiemos el idioma

Puede ser que tu espacio se vea en inglés, puedes cambiar el idioma dando clic en el globo: ![globo](assets/idiomas.png) y seleccionando de la lista “Español latinoamericano”.

Tu espacio de trabajo ahora se verá en español :wink:.


### Agreguemos la extensión "Lápiz"

3.	Agregaremos los controles de Lápiz. Para ello da clic en el ícono ![Agregar extensión](assets/extension-icono.png) (Agregar extensión), que se encuentra en la parte inferior izquierda de tu espacio de trabajo.

Se abrirá otra pantalla con la lista de extensiones disponibles, seleccionaremos la extensión llamada "Lápiz".

![Extensión lápiz](assets/extensiones.png)

Verás que ahora en tu espacio de trabajo tienes los controles relacionados a Lápiz:

![Extensión lápiz](assets/controles-lapiz.png)


### Seleccionemos el objeto "Lápiz"

4.	Del lado derecho de nuestro espacio de trabajo veremos al famoso gato de Scratch. Vamos a cambiar al gato por un lápiz, que irá acorde a nuestra aplicación (un lápiz pinta, el gato no jeje).

![Objeto Gato](assets/obj-gato.png)

Damos clic en el bote de basura, que sale sobre el gato:

![Objeto Gato Bote](assets/obj-gato-zoom.png)

Ahora, daremos clic en el siguiente ícono para generar un nuevo objeto (que es el que se verá en nuestra aplicación, o sea un lápiz).

![Elegir objeto](assets/elegir-obj.png)

Aquí nos salen muchas opciones como puedes ver:

![Elegir objeto](assets/buscar-imagen.png)

Buscaremos un lápiz, introducimos la palabra “pencil” en el campo “Buscar” (donde está la lupa, en el lado superior izquierdo de esta pantalla).

![Elegir objeto pencil](assets/obj-pencil.png)

Damos clic en la imagen del lápiz y veremos que ahora, en lugar del gato, tenemos un lápiz en nuestro espacio de trabajo:

![Objeto pencil](assets/obj-pencil-res.png)

**Ahora sí estamos listos, ¡a programar nuestra aplicación de dibujo! :wink: :smile:.**


## Construyendo nuestro programa

5.	En la sección de controles (del lado izquierdo en nuestro espacio de trabajo) seleccionaremos la categoría Eventos (color amarillo). 

![Controles Eventos](assets/controles-eventos.png)

Y ahí arrastraremos al centro de nuestro espacio de trabajo el elemento “Al presionar” ![Al presionar](assets/al-presionar.png)

Por lo que nuestro espacio de trabajo ahora se ve así:

![Espacio de trabajo](assets/overview1.png)

6.	Ahora, seleccionaremos la categoría Control, y así como hicimos con el elemento anterior, arrastraremos el elemento “Por siempre” a nuestro espacio de trabajo, debajo del elemento “al empezar” como si estuviéramos armando un rompecabezas:

![Espacio de trabajo](assets/overview2.png)

7.	Sigue los pasos anteriores, agregaremos ahora un par de elementos más para que tu espacio de trabajo quede así:

![Espacio de trabajo](assets/overview3.png)

El elemento “ir a” tiene opciones, selecciona “puntero del ratón”.

Esto hará que el lápiz en la sección de prueba (esquina superior derecha) se mueva conforme se mueve el puntero del ratón. 

Para probarlo, da clic en la bandera verde ![Bandera](assets/bandera.png).

Para detener la prueba y seguir programando, da clic en el octágono rojo ![Stop](assets/stop.png).

8.	Ahora, como hiciste en los pasos anteriores, agrega los siguientes elementos a tu espacio de trabajo:

| Control | Categoría |  Imagen |
| --------- | --------- | --------- |
| al presionar | Categoría Eventos (amarilla) | ![Cat amarilla](assets/cat-amarilla.png)|
| fijar tamaño a 50% | Categoría Apariencia (morada) | ![Cat morada](assets/cat-morada.png)|
| lápiz arriba | Categoría Lápiz | ![Cat lapiz](assets/cat-lapiz.png)|
| borrar todo | Categoría Lápiz | ![Cat lapiz](assets/cat-lapiz-borrar.png)|
| esperar 1 segundos | Categoría Control (naranja) | ![Cat naranja](assets/cat-naranja-espera.png)|
| por siempre(^) | Categoría Control (naranja) | ![Cat naranja](assets/cat-naranja-siempre.png)|

>(^)Dentro del elemento “por siempre” agrega los siguientes elementos: 

| Control | Categoría |  Imagen |
| --------- | --------- | --------- |
| esperar hasta que(^^) | Categoría Control (naranja) | ![Cat naranja](assets/cat-naranja-hastaque.png)|
| lápiz abajo | Categoría Lápiz | ![Cat lapiz](assets/cat-lapiz-abajo.png)|
| esperar hasta que(^^) | Categoría Control (naranja) | ![Cat naranja](assets/cat-naranja-hastaque.png)|
| lápiz arriba | Categoría Lápiz | ![Cat lapiz](assets/cat-lapiz.png)|

>(^^) Para este elemento, agregarás en el espacio en blanco los siguientes elementos:

| Control | Categoría |  Imagen |
| --------- | --------- | --------- |
| ¿ratón presionado? | Categoría Sensores | ![Ratón presionado](assets/raton-presionado.png)|
| no(^^^) | Categoría Operadores (verde) | ![Cat operadores](assets/cat-operadores-no.png)|


>(^^^) Y dentro de este elemento agregarás: ¿ratón presionado? (Categoría Sensores) 

![Ratón presionado](assets/raton-presionado.png)

Ahora, tu espacio de trabajo quedará así:

![Espacio de trabajo](assets/overview4.png)


**¡Listo!** :sunglasses:

## Probemos nuestro programa

9.	Para probar nuestro programa, da clic en la bandera verde ![Bandera](assets/bandera.png).

Verás que los bloques (elementos) tienen un contorno amarillo, esto significa que estás ejecutando tu programa. 


![Espacio de trabajo](assets/overview5.png)


¡Ahora dibuja! 

10.	Coloca el ratón en la sección de tu espacio de trabajo donde está el lápiz, mueve el ratón y verás que se mueve el lápiz. 

Da clic y deja presionado el botón del ratón y ve que pasa. Suelta el botón del ratón. 

¿Has visto lo que tu programa hace?

También, puedes hacer esa sección de tu espacio de trabajo más grande para que veas tus trazos. 

11.	Da clic en el ícono ![Maximiza](assets/max-icono.png) para hacer la sección más grande.

![Espacio de trabajo](assets/overview6-max.png)


Da clic en el ícono ![Minimiza](assets/min-icono.png) para regresar la sección a su tamaño original y regresar al espacio de trabajo.


12.	Para detener la prueba y seguir programando, da clic en el octágono rojo ![Stop](assets/stop.png).

Y es así como queda nuestro código para nuestra aplicación que hemos creado para dibujar:

![Espacio de trabajo](assets/overview7.png)

## Puedes agregar otras funcionalidades a tu aplicación

¿Qué tal quedaría tu app si agregamos efectos de sonido cuando el lápiz esté dibujando? o ¿qué tal si agregamos cambios de color a la línea que pinta tu lápiz?

¡Inténtalo!

![Espacio de trabajo](assets/overview8.png)

¡Agrega los elementos necesarios a tu programa y pruébalos!

Como puedes ver, puedes hacer muchas cosas programando :wink:

**Esperamos te hayas divertido.** :relaxed:

**¡GRACIAS!**

![Giti Ameyalli](assets/giti_ameyalli.png)

## Enlaces

Si aún quieres aprender más, visita la [página oficial de Scratch](https://scratch.mit.edu/) para ver más proyectos.

_Derechos reservados Giti Ameyalli [Girl Tech Fest MX](https://girltechfestmx.org/)_.