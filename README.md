# GreenTech-MVP-Sostenible_Elias_PerezArroyo

Todos los siguientes cambios realizados en código se han hecho con el objetivo de optimizar la página web y minimizar el uso de recursos para su funcionamiento manteniendo la mayor similitud con el diseño anterior: <br>

1.Se ha refactorizado el código eliminando las referencias a Bootstrap tanto de CSS y JavaScript consiguiendo reducir el peso entre 250KB Y 300KB.<br>

2.Se ha optimizado la descarga de fuentes al quitar los pesos 100,400 y 900, solo dejando 300 y 700 que son los que se usan. <br>

3.Se ha sustituido el icono de Font Awesome por un emoji simple permitiendo deshacerse de la librería de iconos que pesa unos 30KB.<br>

4.Se ha optimizado la imagen de fondo que se usaba reduciendo su tamaño de 3000px a 1920px, reduciendo su calidad de 80 a 75 y cambiado el formato a WebP [1] consiguiendo pasar de una imagen de 3MB a una de 250KB sin que el impacto visual sea importante. Esto reducirá el consumo de ancho de banda y todo el calor que produciría esto. <br>

5.Se han eliminado las librerias jQuery y Moment.js del footer que llevaban a cabo un script que tenía un gran consumo respecto a lo que aportaba en la web. Menos procesos conllevará a menos trabajo de los componentes.<br>

6.Se ha optado por no usar el atributo Lazy Loading ya que su uso en este caso no ofrecería beneficios al usarse en la imagen principal que siempre se cargará primero. En caso de hubiera otras imágenes en la web que no se vean de primera o que no sea necesaria su vista, si sería recomendable para estas.<br>

7.Los CSS de Bootstrap han sido sustituidos por CSS nativos que se asemejan lo máximo posible a los anteriores, añadiendo nuevos y modificando algunos ya existentes.<br>

8.Los atributos de botones también han sido sustituidos por el ya existente nativo que ha sido modificado también.<br>

9.Todos los estilos de CSS se han refactorizado a un archivo CSS externo llamado estilos.css.

Todas estas optimizaciones consiguen que el estrés y consumo de energía en los componentes tanto de los ordenadores personales como los de centros de datos que producirían calor y a su vez un impacto negativo en el medioambiente se reduzcan ya que necesitan menos potencia para trabajar con archivos menos pesados y operaciones menos complejas. A su vez también se consigue que la potencia de cualquier ordenador no importe, no imponemos nuestras requerimientos como programadores a los usuarios sino que trabajamos para la comodidad y facilidad de uso por ellos adaptando nuestros trabajos como puede ser esta web aplicando buenas prácticas con nuestros conocimientos así aportando a la sostenibilidad del entorno del hardware.<br>

### Fuentes
[1] Google Developers, "WebP: An image format for the Web," Google Open Source, 2024. [Online]. Available: https://developers.google.com/speed/webp.<BR>

[2] Sustainable Web Design, "Standard for Sustainable Web Design," Mightybytes and Wholegrain Digital, 2023. [Online]. Available: https://sustainablewebdesign.org/. <BR>


