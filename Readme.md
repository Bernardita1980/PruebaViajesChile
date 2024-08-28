Una barra de navegación fija en la parte superior de la pantalla que incluye un logo y
los links a las diferentes secciones de la página.
● Un carrusel de Bootstrap que muestra las imágenes destacadas del sitio.
● Una sección de “quienes somos” con información de la agencia (La imagen de esta
sección debe desaparecer en tamaños pequeños de pantalla).
● Una sección de destacados que muestre 4 cards horizontales con los destinos
principales de la agencia. (En pantallas de tamaño pequeño estas cards se modifican
a verticales).
● Una sección con los testimonios de clientes.
● Una sección de formulario de contacto (Incluyendo tooltips y modal en los términos y
condiciones)
● Una sección con los datos de redes sociales de la agencia y números de contacto.

  **Requerimientos**


1. Instalar Bootstrap mediante la terminal usando el gestor de paquetes NPM. (1
Punto)
2. Importar las dependencias necesarias para trabajar con Bootstrap usando Sass. (1
Punto)
○ Importar correctamente en nuestro archivo main.scss, el archivo de bootstrap
necesario para utilizar todas las clases del framework.
○ Realizar la compilación del archivo y vincular el archivo css compilado en
nuestro index.html.
3. Agregar componentes de Bootstrap en las secciones correspondientes (2 Puntos)
○ Menú de navegación.
○ Aplicar carrusel con las imágenes destacadas, este debe tener un alto de
500px en dispositivos grandes y un alto de 300px en dispositivos con tamaño
de pantalla pequeño.
○ Cards con los destinos destacados de la agencia replicando el diseño
sugerido en la maqueta.
○ Formulario de contacto.
4. Se debe utilizar la grilla de Bootstrap para distribuir los elementos del sitio según la
maqueta. (2 Puntos)
○ En la sección de “quienes somos” se debe crear una columna para la imagen
y otra para la descripción. (La imagen debe desaparecer en tamaños
pequeños de pantalla)
○ Las cards con los destinos destacados deben mostrarse en una sola línea en
tamaños de pantalla grandes, y en 2 filas.
○ En la sección de contacto, el formulario debe mostrarse al costado izquierdo
y los datos de contacto al costado derecho (en dispositivos grandes) en
dispositivos pequeños queda el formulario arriba de los datos de contacto.
5. Utilizar metodología BEM en sección de testimonios. (1 Punto)
○ En esta sección se debe crear otro archivo .sass y los estilos se deben aplicar
solo usando CSS y la metodología BEM para nombrar las clases.
○ En este archivo pueden añadir los estilos que sean necesarios para las otras
secciones si es que el desarrollo lo requiere (Opcional)
6. Aplicar componentes que utilicen JavaScript. (3 Puntos)
○ Importar los archivos necesarios para utilizar JavaScript.
○ Aplicar tooltips en los labels del formulario para entregar información de
ayuda para el usuario