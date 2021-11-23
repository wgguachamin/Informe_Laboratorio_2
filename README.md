PRÁCTICA N°02 ANÁLISIS DE MALLAS

1.1. OBJETIVOS DE LA PRÁCTICA

OBJETIVO GENERAL:
- Comprobar de forma experimental el análisis de mallas, mediante la simulación de un circuito mixto, para poder aplicar los conocimiento adquiridos en la clase.

OBJETIVOS GENERALES:
- Determinar el número de mallas que existen en el circuito mixto.
- Utilizar de forma correcta los conceptos obtenidos de la Ley de Ohm.
- Emplear la Ley de los voltajes de Kirchhoff para encontrar el voltaje que recorre por cada malla.

1.2. MARCO TEÓRICO

- RAMA

Se define como la parte o elemento que se encuentra entre dos nodos. Cabe recalcar que por todos los componentes de una rama circula la misma corriente.

- NODO

Se le conoce como el punto de unión de 3 o más ramas. Es importante mencionar que la suma de las corrientes entrantes a un nodo debe ser igual a la suma de todas las corrientes salientes. (Ley de las corrientes de Kirchhoff).

- MALLA

Una malla es el camino que forman 2 o más ramas de un circuito. Además en una malla la suma de todas las tensiones, cada una con su signo correspondiente, es igual a 0 (Ley de los voltajes de Kirchhoff). Esto se da porque la suma de todas las subidas de tensión debe ser igual a la suma de todas las caídas de tensión.

![image](https://user-images.githubusercontent.com/94008521/142939919-92907f80-59a2-4d63-8ac8-0022884b0b5b.png)

- GRÁFICO DE RECONOCIMIENTO DE RAMAS, NODOS Y MALLAS

![image](https://user-images.githubusercontent.com/94008521/142940229-0d2b1ca4-9be0-4de3-b9ed-1cb531a5327e.png)

- ANÁLISIS DE MALLAS

Es un método general que sirve para resolver circuitos cuyos elementos están conectados en serie, en paralelo o de forma mixta, es decir, cuando no se distingue claramente el tipo de conexión. El circuito debe ser plano, o al menos debe ser posible re-dibujarlo como tal. A su vez este tipo de técnica emplea la LVK (Ley de los voltajes de Kirchhoff) con el objetivo de expresar voltajes en función de corrientes. 

1.3. EXPLICACIÓN DEL PROCEDIMIENTO
Materiales y Equipos requeridos

![image](https://user-images.githubusercontent.com/93415377/142961419-e8ca8402-a66a-44f0-9ede-18e390e9df3b.png)


Analisis del Circuito

![image](https://user-images.githubusercontent.com/93415377/142960467-72f18302-cfce-4d71-8c36-ee492a08175f.png)

Para realizar el cálculo de las corrientes existentes en cada una de las 3 mallas existentes en el circuito de la figura 2.1 primero asignamos el sentido de las corrientes en sentido horario y una vez asignadas las corrientes se escribe la ley de Kirchhoff de las tensiones para cada malla a fin de obtener ecuaciones que nos permitan encontrar el valor de las corrientes. 

Malla 1:

![image](https://user-images.githubusercontent.com/93960809/142963382-765036a6-e6d3-4906-b848-cd6d619ab635.png)

Malla 2:

![image](https://user-images.githubusercontent.com/93960809/142963401-909db9d2-435a-4848-b36e-68d23468ea96.png)

Malla 3:

![image](https://user-images.githubusercontent.com/93960809/142963419-ab766201-a6da-4575-b7a3-c0ab9eca9593.png)

 Resolviendo sistema de ecuaciones: 
 
 ![image](https://user-images.githubusercontent.com/93960809/142963435-3c140e55-9ffa-4b4c-a404-31a5bca0137d.png)

I1 = 176/15365 = 11.45mA

I2 = 5/1756 = 2.847mA

I3 = 3/6146 = 488µA

Resultados de corrientes en el laboratorio virtual Tinkercad:

![image](https://user-images.githubusercontent.com/93960809/142963468-a456de6d-f273-4630-85bd-21b2495ed141.png)

Resultados de corrientes en el simulador Multisim:

![image](https://user-images.githubusercontent.com/93960809/143025118-25b845d0-b5cd-4f19-bc75-6c1d4bc7ec9c.png)

Tabla 2.1 Resultados obtenidos para el circuito de la figura 2.1:

![image](https://user-images.githubusercontent.com/93960809/143025233-cb03fce6-e6b0-41b5-b40a-a5194d4aa88e.png)


1.4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR

![image](https://user-images.githubusercontent.com/93415377/142960421-8aad7c93-6dcb-4f8d-b068-1c23fa9f0340.png)


1.5. VIDEO

1.6. CONCLUSIONES

- Al realizar el análisis completo del circuito se tiene que en total hay unicamente 3 mallas, es importante mencionar que no se deben de confundir a las mallas con las trayectorias, dado que una malla no posee ninguna rama en su interior, mientras que una trayectoria si puede tener 1 o más ramas en su interior.
- Para realizar correctamente el cálculo de corrientes por el método de mallas es necesario asignar el sentido a las corrientes de forma que se pueda aplicar la ley de Kirchhoff de las tensiones en cada una de las mallas a tratar. 
- Los resultados obtenidos manualmente como en el simulador (TINKERCAD), varian en una mínima proporción debido a los factores utilizados en los calculos, debido a esto se diría que nunca daremos con una medida exacta ni precisa solo una aproximación. 


1.7. BIBLIOGRAFÍA

-	Bustamente, J. (18 de Octubre de 2019). Obtenido de https://media.utp.edu.co/ingenieria-fisica/archivos/Practica_4Gen.pdf
-	González, F. (02 de Junio de 2018). Obtenido de https://nanopdf.com/download/tema-3-5b1270f411227_pdf
-	Infante, M. (2015). Solucionario de circuitos eléctricos en estado estable. Riobamba: La caracola.
-	Salazar, A. (07 de Marzo de 2017). Obtenido de http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/03_Analisis_por_Nodos_y_Mallas.pdf
-	Yanez, E. (27 de Marzo de 2012). Obtenido de https://es.slideshare.net/amerika_09/mallas-y-nodos
