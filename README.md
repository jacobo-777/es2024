Pregunta 1//
1)
es necesario hacer resize al vector ya que aunque se comporta como un arreglo dinamico todavia tiene limitaciones de memoria.Cuando se crea un vector se guarda un poco de memoria para el siguiente vector asi permitiendo almacenar sus elementos Si la memoria disponible se llena no habria espacio para agregar más elementos, al hacer el resize podemos reservar un nuevo espacio de memoria mas grande y pasar los elementos que ya existen al nuevo espacio
no es una mejor opcion reservar un nuevo espacio de memoria ya que desconocemos el tamaño de elementos que se va a querer guardar y no seria eficiente no utilizar el nuevo espacio de memoria por completo
2)
si podria ser mas eficiente  ya que al memento de poner y quitar elementos en cualquier posicion solo seria necesario actualizar los punteros y la forma en la cual se usa la memoria es de una mejor manera ya que cada nodo ocupa el espacio necesario para almacenar su valores

Pregunta 2
1)
La capacidad del vector x seria 10240 y su desperdicio 240
la capacidad del vector y seria 11568 y su desperdicio 1568 
la capacidad del vector z seria 12800 y su desperdicio 2800
2) 
el vector mas eficiente fue el vector x ya que podemos evaluar la eficiencia basandonos en el desperdicio de memoria, este fue el que menos memoria desperdicio 


Pregunta 3


3. Operaciones para adicionar y remover ciudades:
Agregar una ciudad:  añaCit(int city) 
Remover una ciudad: reCity(int city) 

añadir ciudad
    AdjacencyList ciudad;
    ciudad.añaCity(0);
    ciudad.añaCity(1);
    ciudad.añaCity(2);
    ciudad.añaCity(3);
    ciudad.añaCity(4);
    ciudad.añaCity(5);
    remover ciudad
    ciudad.reCity();
    ciudad.display();




