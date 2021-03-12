Gabriel A. Jeannot - 2185887
Santiago Marmolejo - 2185317
Juan Carlos Lopez - 2175639
Raul A. Martinez - 2185502

Descripción: Apartamento tipo Loft de estrato 6, incluye dos cuartos, un baño, cocina, 
sala y dos pisos. Posee tonalidades neutras y una vista agradable a la ciudad.

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
 
Finalmente, decidimos dejar las puertas cerradas pero la persona que use la experiencia 
podrá traspasarlas para ingresar al cuarto, esto lo hicimos por motivos esteticos, ya que 
de esta forma se pueden observar las texturas que tienen las puertas y como se ven por 
fuera de los cuartos.  