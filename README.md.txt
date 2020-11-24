Lo primero que haremos es dupicar nuestros repositorios y colgarlos al repositorio online. Una vez ahí, desde carpetaCasa, 
realizaremos un git log --online para saber todos los commits y etiquetas que se han realizado.
Creamos una tag y volveremos al primer commit realizado.
Al volver al primer comit y hacer un cambio, nos dejara añadirlo e incluso hacer commit, pero al hacer push ya nos empieza a dar error.
Cuando intentamos volver con checkout master, nos dice que hay un cambio que omitirá pero que lo tendrá en cuenta por si queremos volver a él.
Por último, vemos que para subir la tag creada no vale con un git push, porque no se verá reflejado en nuestro repositorio online.
Para ello, debemos usar git push origin --tags, y así sí nos mostrará la etiqueta creada.