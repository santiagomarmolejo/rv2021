Gabriel A. Jeanott - 2185887
Santiago Marmolejo - 2185317
Juan Carlos Lopez - 2175639
Raul A. Martinez - 2185502

Descripción: 

Apartamento tipo Loft de estrato 6, incluye dos cuartos, un baño, cocina, 
sala y dos pisos. Posee tonalidades neutras y una vista agradable a la ciudad.

La importancia de este proyecto radica en ofrecer una nueva experiencia tipo Realidad 
Virtual, la cual consiste en un entorno generado mediante tecnología informática, con el 
fin de generar una inmersión mayor a los usuarios. Es por esto que decidimos elaborar 
esta experiencia.

Problemas y soluciones: 

Primero que todo, cabe mencionar que no tuvimos ningún problema con temas de iluminación
o uso del sonido, y, diseñamos la estructura del apartamento, es decir, la división de 
los cuartos, el baño, las escaleras y los dos pisos en la aplicación de modelado 3D:
Autodesk Maya.

Para la realización de este proyecto en el grupo tuvimos varios inconvenientes a la hora 
de importar objetos en la escena de realidad virtual del apartamento tipo loft. El 
principal y más influyente siendo el uso de texturas, puesto que al principio se estaban
importando objetos de tipo .obj, y que al intentar importar las texturas de estos
ocurrían algunos errores con el archivo mtl de los mismos, y por más que se intentó no 
fuimos capaces de seguir utilizando este tipo de objetos, incluso intentamos crear 
objetos en Autodesk Maya, pero tampoco. Sin embargo, llegamos a una solución, y fue 
cambiar el tipo de objeto que estabamos importando, sustituyendo el .obj por un objeto 
tipo .gtfl; este cambió nos ayudó totalmente, puesto que ya eramos capaces de utilizar 
los objetos con sus respectivas texturas. Así mismo, decidimos cambiar la página desde
la que estabamos descargando los modelos, siendo Clara.io inicialmente, pero decidimos 
empezar a descargar los .gtfl desde skethfab.com.

El otro problema que tuvimos fue respecto a las "paredes invicibles" y la colisión de
los modelos. El primer gran problema con esto fue la localización y el tamaño de las 
paredes invicibles, pues al principio intentamos hacerlas usando entidades (<a-entity>)
pero no lograbamos hacer que los objetos colisionaran, por lo tanto, probamos hacer las
colisiones con cajas (<a-box>) y planos (<a-plane> invicibles, lo cual nos permitió 
agregar las físicas y las colisiones en la escena. El siguiente problema fue la posición
de estas, pues teníamos que hacerlas muy grandes para que las paredes quedaran todas 
con su respectiva colisión y de esta manera no se tendría que llenar la escena de cubos
invicibles, o en su defecto que esta no tenga demasiados. La colisión de las escaleras
también fue un poco engañosa, pues no funcionaba solo con cubos, por lo que decidimos
combinar cubos y planos y posicionarlos en diagonal, de esta forma se pueden usar las 
escaleras para subir al segundo piso y ver los cuartos.

Sin embargo, y a pesar de las soluciones que encontramos respecto a las colisiones con
las paredes y los objetos, hay un pequeño "bug" que se mantuvo, siendo que, en la pared
ubicada a la izquierda de las escaleras, a veces la colisión no se efectúa, la mayor 
parte del tiempo no pasa nada y la colisión funciona como debería, pero algunas veces
algo sucede y esta colisión no toma lugar, ocasionando que la cámara traspase la pared
y caiga en caída libre fuera del apartamento. 

Tuvimos dificultades en encontrar un skymap que representara una luz tenue y oscura, 
o que, en su defecto, fuera de noche, es por esto que optamos por utilizar un skymap 
de una ciudad costera de día, y posteriormente procedimos a editar dicha imagen en 
Photoshop, donde jugamos con la saturación de colores, las tonalidades del cielo y la 
exposición del color, transformando el skymap en una vista que, sin duda, representa la 
sensación de un apartamento moderno y muy bien ubicado.
 
Finalmente, decidimos dejar las puertas cerradas pero la persona que use la experiencia 
podrá traspasarlas para ingresar al cuarto, esto lo hicimos por motivos esteticos, ya que 
de esta forma se pueden observar las texturas que tienen las puertas y como se ven por 
fuera de los cuartos.  