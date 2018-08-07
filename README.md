# Lab1
Practica laboratorio 1  de informática II
Estudiante: Jhon Jair Murillo Delgado
Fecha: 08/2018
 
 
Estructura llamada "Calendario", que solo contiene un campo de bits de tipo 
unsigned short int para los componentes de la fecha: anio, mes y dia.
Diseñe una funcion llamada "checkDate" que reciba como parametro una estructura "Calendario"
esa funcion debe ser capaz de verificar cualquier error en la fecha que este guardada en la estructura que le entra como parametro,
es decir, debe verificar que el dia no sea mayor a 31 a 30, a 29 o 28 segun el mes, ni menor que 1. 
El anio es un numero entre 0 y 127, el anio 0 corresponde a 1990, luego el anio 2018 por ejemplo
corresponderia al anio 28. Tambien debe verificar si el anio es bisiesto, en ese caso Febrero
puede tener 29 dias (enlace sugerido: http://www.disfrutalasmatematicas.com/medida/anos-bisiestos.html)
La funcion debe retornar un valor booleano que indique si la fecha ingresada esta bien o mal.
