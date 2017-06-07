# Partícula "Buscador-avanzado"
Partícula para Gantry 5 que te permite incluir una buscador dentro de tu sitio. Pudiendo modificar el ícono de busqueda, definir diferentes estilos y comportamientos avanzados.
![particula-buscador-avanzado](https://user-images.githubusercontent.com/9434043/26899065-9465a1c4-4b93-11e7-9387-7b5d7d56f14c.png)


Instalación
-----------
NOTA: Estar particula requiere el átomo nativo de Gantry: "Lightcase", necesario para generar el efecto Lightbox (Ventana modal).
No hemos incluido un instalador ya que deseamos que esta partícula pueda ser usada tanto en Joomla como en Wordpress. 
El modo de instalación es muy sencillo:

+ Crear la carpeta "particles" dentro de tu carpeta "custom" en tu plantilla Gantry. Ejem: g5_hydrogen/custom/particles
+ Cópie los archivos buscador-avanzando.html.twig y buscador-avanzando.yaml
+ Cópie el archivo ubicado en "scss/_buscador-avanzando.scss" dentro de tu carpeta "scss". Ejem: g5_hydrogen/custom/scss
+ Llame al archivo desde tu custom.scss colocando la siguiente linea al comienzo: 

  /* Estilos partícula Buscador avanzado */
  
  @import "buscador-avanzando";


Modo de uso
-----------
+ Desde el Layout Manager encontrarás la partícula con el nombre "Buscador avanzando". 
+ Arrástrala a tu  diseño y configúrala.
+ Desde el Gestor de Módulos, coloque su módulo de búsqueda en la posición modular:"posicion_buscar"

Saludos
http://www.aulaideal.com


