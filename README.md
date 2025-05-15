# bootstrap
practica Boostrap
agrerar los link desde la pagina de bootstrap, link de CDN y Script
luego crear contenedor div.

y div clase=" row" para una fila de columnas.

div class="col-md-4 sm-4" cuando la pantalla sea mediana es de 4 grillas y cuando la pnatlla sea pequeña se mantiene en 4 grillas.

copia de nav desde bootstrap

nav class="navbar navbar-expand-lg bg-body-tertiary", cambia la posición de las cosas al llegar al tamaño LG, expand 991px.

 navbar-expand-lg, es el que da la posicion ,tamaño de las letras, color de texto, si se elimina, el nav matiene su posicion resumida y no se expande.

bg-body-tertiary, es el color del background, 
a class="navbar-brand" href="#">Mi empresa, para cambiar el titulo del NAV
span class="navbar-toggler-icon", Muestra el texto un poco mas fuerte...

div id="carouselExample" class="carousel slide", para crear un carrusel primero hay que crear un ID y una clase.

div class="carousel-item active,indica que es la primera imagen

button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev",
boton de navegación, # para navegar obtener info del mismo archivo, misma class del titulo, prev indica la flecha hacia atras.

span class="carousel-control-prev-icon" aria-hidden="true", para mostrar icono.

span class="visually-hidden">Previous, para flecha izquierda.

para crear flechas de navegacion tambien se puede asi.
a href="carousel-item" class="carousel-control-next-icon" role="button" data-bs-slide="next">
span class="carousel-control-prev-icon" aria-hidden="true"></span>
span class="visually-hidden">Previous span
                        /a
div class="carousel-indicators", para generar navegadores de barra
                        button type="button" data-bs-target="#carouselExample" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1">
                            button type="button" data-bs-target="#carouselExample" data-bs-slide-to="1" aria-label="Slide 2">
                            button type="button" data-bs-target="#carouselExample" data-bs-slide-to="2" aria-label="Slide 3">
                         
