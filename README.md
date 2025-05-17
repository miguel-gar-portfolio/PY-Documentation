## Descripción del proyecto

Este proyecto fue el primero que se me encargó en la empresa, y buscaba documentar de una forma clara, en un diagrama, la totalidad de los objetos que componen la base de datos de la compañía.

Tras un periodo de investigación, encontré una forma amable y dinámica de visualización proporcionada por **JavaObservable**, a partir de un código en JavaScript publicado por otra fuente. Esta representación consiste en un **diagrama de árbol dinámico**, cuyas ramas se expanden o contraen según lo requiera el visor. 

Esto facilita sobremanera la presentabilidad, dada la gran cantidad de ramas que componen el árbol.

Para crear el árbol es necesario alimentarlo con un archivo .json, por lo que tras una correccta extracción de la base de datos con TSQL se pasa el archivo por el código pyhton, y en pocas líneas se obtiene un archivo .json que el javascript entiende y convierte en el diagrama de árbol. Además del cuaderno jupyter, dejo un json de prueba para que veáis un ejemplo.

El árbol se puede encontrar [aquí](https://observablehq.com/@d3/collapsible-tree).
 

Más tarde, se procedió por otras vías, al no disponer esta representación de una opción de búsqueda. La continuación de esta resolución se encuentra [aquí](https://github.com/miguel-gar-portfolio/SQL-instances_documentation).
