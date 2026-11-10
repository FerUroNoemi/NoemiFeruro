# Proyecto: Fernandez_Urones_Noemi_Fase2

## Enlace a la web publicada
https://github.com/FerUroNoemi/NoemiFeruro.git

## Justificación técnica: CSS Grid vs. Flexbox

* CSS Grid (Para la estructura grande): Lo usamos en el contenedor principal de la página permite dividir la pantalla en grandes bloques (arriba la cabecera, en el medio el contenido y abajo el pie de página) para que todo encaje de forma ordenada y sea mas fácil hacer cambios según tamaño.
* Flexbox (Para alinear los detalles):Lo usamos para poner el botón a la izquierda y los logotipos a la derecha en el pie de página de manera automática.

## Versión móvil y punto de ruptura (Breakpoint)

* Punto de ruptura seleccionado: Se ha fijado en `max-width: 430px` mediante (`@media`) en la hoja de estilos.
* Cambios al móvil:
  * Se reducen los márgenes exteriores de la página y el grosor de los bordes para aprovechar mejor las pantallas pequeñas.
  * El tamaño de los títulos y de los enlaces del menú se encoge.
  * La zona de contenido y las imágenes reducen su altura y activan el desplazamiento interno (`scroll`) si el texto es largo, haciendo fácil la lectura.
  * Los logotipos del pie de página adaptan su tamaño máximo para integrarse con fluidez en dispositivos estrechos como los smartphone.
