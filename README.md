Funciones
Práctica Integradora
Objetivo
Vamos a ejercitar lo visto sobre funciones, poniendo también en práctica temas de clases
anteriores.
Recuerda que puedes consultar el material para ayudarte a realizar estos ejercicios.
Además, recomendamos que amplíes los conceptos vistos en los sitios oficiales de las
tecnologías que estamos aprendiendo: como la de MDN Web Docs, W3School o foros
reconocidos como Stack Overflow.
¿Qué nos devuelve esta función?
Antes de empezar con los desafíos, preparémonos. Sin codificar nada, trata de pensar que
devuelve la siguiente función. ¿Qué piensas?
function area(largo,ancho){
return largo * ancho;
}
area(10,50);
1
Micro desafío 1:
Instrucciones
1. Crea una carpeta de trabajo y dentro de ella crea un archivo JavaScript (.js).
2. Crea una función que permita calcular el monto a pagar por el alquiler de un
vehículo, que reciba como parámetros: “tipo de vehículo”, “Días de alquiler” y “silla
para bebe”.
3. Define y realiza los cálculos para obtener el total a pagar, teniendo en cuenta las
siguientes consideraciones:
● De acuerdo al tipo de vehículo, se le cobra al cliente un monto por día:
○ Compacto: $14000
○ Mediano: $17000
○ Camioneta: $28000
● Si adicionalmente el cliente requiere la silla para niños, se le cobra un adicional por día
de $1200
4. Una vez creado el programa, ejecutalo. ¿Recuerdas cómo?
5. Para probar las diferentes respuestas invoca a la función, asigna diferentes valores o
argumentos. Usando el console.log(), muestra los resultados al usuario:
“Estimado cliente: en base al tipo de vehículo compacto alquilado, considerando los 3 días
utilizados, el monto total a pagar es de $42000 ” .
Recuerda que si el cliente pidió la silla para niños debe también indicarlo en el mensaje final.
2
Micro desafío 2:
Instrucciones
1. En la carpeta ya creada, crea un nuevo archivo JavaScript (.js).
2. El teach leader de la empresa nos pide construir un sistema para un local de venta de
comida rápida. Los clientes eligen el tipo de hamburguesa base con un precio base y,
por cada selección que el cliente agregue, se le suma el valor de su selección al
precio.
Por ejemplo, si partiendo de una hamburguesa base carne a la parrilla con un precio “a”, el
cliente les incorpora los adicionales: de queso “b” y tomate “c”, el total a pagar sería
a+b+c. Así sucesivamente con el resto de los ingredientes.
Es importante tener presente que cada uno de estos adicionales estarán representados por
valores booleanos, es decir, true o false, dependiendo de si aceptan o no cada uno de los
adicionales. Así recibiremos un total de ocho valores booleanos, uno por cada adicional.
Tu responsabilidad será la de crear dos funciones:
Primera función - Callback:
● Tendrá la responsabilidad de calcular el total a pagar por el cliente, en base a un total
de nueve parámetros que recibirá la función:
Un string para el tipo de hamburguesa, teniendo en cuenta las siguientes:
○ Carne a la parrilla: $1800
○ Pollo: $1500
○ Vegetariana: $1200
● Y recibirá los ocho valores booleanos de los adicionales, teniendo en cuenta los
siguientes:
○ Jamón = $30
○ Queso = $25
○ Salsa de tomate = $5
○ Mayonesa = $5
○ Mostaza = $5
○ Tomate = $15
3
○ Lechuga = $10
○ Cebolla = $10
Segunda función:
● Esta función tendrá la responsabilidad de devolver un mensaje al usuario donde le
indique su nombre, su apellido y el total a pagar en base al tipo de
hamburguesa seleccionado más los adicionales indicados. Tenga en cuenta que
esta función deberá recibir como parámetros: “nombre del usuario”, “apellido del
usuario”, “tipo de hamburguesa” y los ocho valores booleanos en función a los
adicionales que el cliente haya seleccionado.
Una vez creado el programa, ejecutalo. Para probar las diferentes respuestas, invoca a la
segunda función, asigna diferentes valores o argumentos. No olvides usar el console.log()
para mostrar los resultados al usuario, de acuerdo al siguiente mensaje:
Estimado Daniel Fuentes, el monto total a pagar es de: $1905
4
Desafío extra (opcional):
Instrucciones
Si llegaste hasta acá, significa que vienes trabajando muy bien. ¡Felicitaciones!
Para que no te quedes con las ganas y puedas seguir practicando, te proponemos que
desarrolles las siguientes funciones. Verás que presentan una dificultad extra, por lo que
tendrás que buscar algunos conceptos para poder resolverlos. Es recomendable que crees
este hábito ya que es algo muy común que los programadores realizamos todos los días.
En la carpeta ya creada, crea un nuevo archivo JavaScript (.js) por cada nueva función.
1. Crear una función que recibe un string en minúscula, lo convierte a mayúsculas
y lo retorna. Investiga qué hace el método de strings .toUpperCase()
2. Crear una función que recibe un parámetro y devuelve qué tipo de dato es ese
parámetro. Investiga qué hace la palabra reservada typeof().
3. Crear una función que calcule la edad de los perros, considerando que 1 año para
nosotros son 7 de ellos.
4. Crear una función que calcule el valor de una hora de trabajo, teniendo en cuenta que
dicha función recibe tres parámetros: El salario mensual, la cantidad de días
trabajados y la cantidad de horas que regularmente trabajada por día.
Cuando tengas alguna duda que te impida avanzar, puedes preguntarle a tus profesores.
¡ Éxitos !
5
