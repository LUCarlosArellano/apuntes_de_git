## git tag

Nos sirve para crear etiquetas

Etiqueta ligera
`git tag <NombreEtiqueta>`
`git tag <NombreEtiqueta> <ValorDelCommit>`
Con esto creamos una etiqueta ligera, que apunta al ultimo commit que realizamos. 

Etiqueta anotada
`git tag -a <version> -m <'Mensaje de la version'>`
Se guardan en la base de datos de Git como objetos enteros. Tienen un check sum; contiene el nombre de la etiqueta ademas de que muestra un texto más amplio de en que consiste la etiqueta, como los datos del desarollador.

Muestrar información de una etiqueta.
`git show <etiqueta>`
Muestra la información de una etiqueta seleccionada.

Modificar el mostrar la lsita de etiquetas
`git tag -l <Patron>`

Con esto organizamos la lista de etiquetas que coincidan con el patron especificado.