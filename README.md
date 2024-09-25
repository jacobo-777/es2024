1)
es necesario hacer resize al vector ya que aunque se comporta como un arreglo dinamico todavia tiene limitaciones de memoria.Cuando se crea un vector se guarda un poco de memoria para el siguiente vector asi permitiendo almacenar sus elementos Si la memoria disponible se llena no habria espacio para agregar más elementos, al hacer el resize podemos reservar un nuevo espacio de memoria mas grande y pasar los elementos que ya existen al nuevo espacio
no es una mejor opcion reservar un nuevo espacio de memoria ya que desconocemos el tamaño de elementos que se va a querer guardar y no seria eficiente no utilizar el nuevo espacio de memoria por completo
2) 
si podria ser mas eficiente  ya que al memento de poner y quitar elementos en cualquier posicion solo seria necesario actualizar los punteros y la forma en la cual se usa la memoria es de una mejor manera ya que cada nodo ocupa el espacio necesario para almacenar su valores
3
