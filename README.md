### Mapa de Organizaciones Sociales de Vicente López

La versión 2020 del Mapa de las OSC de Vicente López permite conocer más sobre las organizaciones y su situación durante la pandemia de COVID. Con este mapa es posible ubicar geográficamente a las organizaciones sociales, ver aquellas que están más cerca de los y las vecinos/as y conocer más sobre ellas y obtener medios de contactos.

En esta nueva versión se ha agregado también la posibilidad de enviar un mail, que se ha puesto por default en "entidades.intermedias@vicentelopez.gov.ar". Para implementar esta nueva funcionalidad hay que modificar esa línea en app.R. Este último archivo contiene muchos comentarios sobre la fuente de los datos, las columnas que necesita para funcionar y diversas indicaciones para modificar algunas de las funcionalidades.

### Implementación

Las aplicaciones Shiny necesitan correr en un servidor que tenga corriendo [Shiny Server](https://rstudio.com/products/shiny/shiny-server/). En ese link van a encontrar la documentación para ponerlo en funcionamiento. Adicionalmente, hay dos métodos que fueron diseñados para poder escalar la aplicación en caso que sea necesario y están disponibles [acá](https://github.com/martinmontane/ShinyServerDockerUTF8) y [acá](https://github.com/martinmontane/shiny_nginx_loadbalancer). Finalmente, si ninguna de estas opciones luce adecuada, es posible usar el [servicio pago que brinda RStudio](https://www.shinyapps.io/)

### Versión de prueba

[En esta dirección](https://martinmontane.shinyapps.io/vicentelopez/) van a encontrar una versión en funcionamiento de esta aplicación, a modo de poder comparar la implementación local. Es posible que no pueda consultarse en caso de agotarse las condiciones del servicio, que se renuevan de manera mensual.
