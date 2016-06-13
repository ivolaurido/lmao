#include <stdio.h>
 int eleccion,a,b,c;
 int puntuacion = 20;
 printf("-bienvenido a la torre de las preguntas yo soy el mago de de la torre\n");
 printf("-vos sos...\n");
 printf("a-elfo\n");
  printf("b-orco\n");
printf("c-dragon\n");
 eleccion = getchar();
 //este switch es para elegir la falsa raza
    switch(eleccion) {
    
 case 'a'  :
      printf("-de ahora en adelante seras un elfo (hasta que reinicies el juego)");
    break;
	
  case 'b'  :
      printf("-de ahora en adelante seras un orco (hasta que reinicies el juego)");
      break; 
	  case 'c' :
      printf("-de ahora en adelante seras un dragon (hasta que reinicies el juego)");
      break;
  
      default : 
      printf("-ahora por vivo sos humano y te resto un punto\n");
      puntuacion = puntuacion - 1;
      break;
 
   } 
printf("\n-si deseas superar la torre de las preguntas deberas responer 11 de 20 preguntas correctamente\nde lo contrario quedaras atrapado en esta hasta el fin de tus dias\n");
  printf("-1¿Quien sabia que no sabia nada'?\n 1 Aristoteles\n 2 Ortega y Gasset\n 3 Socrates \n");
  scanf("%d",eleccion);
  if(eleccion == 3){
  	printf("correcto,Sócrates sabía que no sabía nada. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
printf("-2-¿Qué es un 'ewok'? \n1 Un libro en formato digital\n2 Un ser de 'La guerra de las Galaxias'\n3 El jefe de una nación india\n");
  scanf("%d",eleccion);
  if(eleccion == 2){
  	printf("correcto,Los 'ewok' habitan la luna de Endor en la saga de George Lucas. \n");

  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
  printf("-3-¿Quién es el autor del Gaucho Martín Fierro?\n1 Martín Fierro\n2 José Hernández \n3 El autor es anónimo\n");
  scanf("%d",eleccion);
  if(eleccion == 2){
  	printf("correcto,Martín Fierro es obra de José Hernández \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
  printf("-4-¿Cual es la moneda oficial de Panamá?\n1 El Dolar panameño\n2 El Dolar estadounidense\n3 El Balboa\n");
  scanf("%d",eleccion);
  if(eleccion == 3 ){
  	printf("correcto,La moneda oficial es el Balboa \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
  printf("-5-¿En qué no cree un budista?\n1 En la reencarnación\n2 En el nirvana\n3 En un dios\n");
  scanf("%d",eleccion);
  if(eleccion == 3 ){
  	printf("correcto\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-6-¿Cómo muere don Quijote?\n1 Se cae del caballo cuando acomete al molino que confunde con un gigante\n2 En un enfrentamiento con bandoleros\n3 En la cama\n");
  scanf("%d",eleccion);
  if(eleccion == 3){
  	printf("correcto,Alonso Quijano muere en la cama; confesado, cuerdo y no creyéndose don Quijote. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-7-El Principito le pide a Saint-Exupery que le dibuje...\n1 Un sombrero\n2 Un cordero\n3 Un elefante en el estomago de una boa\n");
  scanf("%d",eleccion);
  if(eleccion == 2 ){
  	printf("correcto,¡Dibujame un cordero!, le pide El Principito al aviador. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-8 China es un régimen...\n1 Comunista\n2 Maoísta\n3 Capitalista\n");
  scanf("%d",eleccion);
  if(eleccion == 1){
  	printf("correcto\nEl régimen político chino sigue siendo comunista a pesar de la apertura de su economía al capitalismo. Dejó de ser maoísta en 1978.\n ");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-9¿A que edificio trepo King Kong?\n1 A la Casa Blanca.\n2 Al Empire State\n3 A la Torre Eiffel\n");
  scanf("%d",eleccion);
  if(eleccion == 2){
  	printf("correcto,King Kong escaló el Empire State Building de Nueva York. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-10¿Qué miembros de los Beatles siguen vivos?\n1 Todos, menos John Lennon\n2 Ringo Starr y Paul McCartney\n Paul McCartney y George Harrison\n");
  scanf("%d",eleccion);
  if(eleccion == 2 ){
  	printf("correcto\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-11-¿Quién no tiene asiento permanente en el Consejo de Seguridad de la ONU? \n1 Francia\n2 Alemania\n3 China\n");
  scanf("%d",eleccion);
  if(eleccion == 2 ){
  	printf("correcto,Alemania no tiene asiento permanente en el Consejo de Seguridad de la ONU.\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-12-¿Qué se coloca entre los números de una dirección de IP?\n1 Puntos \n2 Doble barra\n3 Guiones \n");
  scanf("%d",eleccion);
  if(eleccion == ){
  	printf("correcto\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-13¿En qué lugar del cuerpo se produce la insulina? \n1 En la hipófisis\n2 En el páncreas \n3 En el duodeno \n");
  scanf("%d",eleccion);
  if(eleccion == 2 ){
  	printf("correcto,La insulina se produce en el páncreas. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-14¿Con que se fabricaba el pergamino?\n1 Con piel de animales\n2 Con tiras de madera\n3 Con hojas de arbusto \n");
  scanf("%d",eleccion);
  if(eleccion ==1 ){
  	printf("correcto,El pergamino se hacía con piel de res u otros animales.  \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-15¿Qué país no tiene al euro como moneda? \n1 Portugal\n2 Suiza\n3 Francia\n");
  scanf("%d",eleccion);
  if(eleccion == 2 ){
  	printf("correcto,Los suizos siguen fieles a su franco.\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-16¿En cuántos estados pueden aparecer los elementos? \n1 En dos \n2En tres \n3 Al menos en cuatro\n");
  scanf("%d",eleccion);
  if(eleccion == 3 ){
  	printf("correcto\nLos elementos pueden aparecer en estado sólido, líquido, gaseoso, plasmático y se investigan nuevas formas de agregación. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-17¿Qué enfermedad se considera erradicada?\n1 Peste \n2 Viruela\n3 Cólera \n");
  scanf("%d",eleccion);
  if(eleccion == 2 ){
  	printf("correcto,La viruela está erradicada\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-18¿Qué le pasa en realidad al gato de Schrödinger? \n1 Que está muerto\n2 Que está vivo \n3 Que está muerto y vivo\n");
  scanf("%d",eleccion);
  if(eleccion == 3 ){
  	printf("correcto,El gato de Schrödinger está vivo y muerto. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-19¿Cuál es el primero de la lista de los números primos?\n1 El 1.\n2 El 2\n3 El 3\n");
  scanf("%d",eleccion);
  if(eleccion == 2){
  	printf("correcto,El primer puesto de la lista de los números primos lo ocupa el 2.\n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
   printf("-20¿A qué Ciudad-Estado pertenecía la localidad natal de Leonardo Da Vinci?\n1 A Venecia \n2 A Florencia\n3 A Milán \n");
  scanf("%d",eleccion);
  if(eleccion == 2){
  	printf("correcto,Anchiano y Vinci eran parte de Florencia, en la Toscana italiana. \n");
  }
  else{
  	printf("incorrecto\n");
  		puntuacion = puntuacion - 1;
  }
  
     scanf(" ");
   return 0;
}
