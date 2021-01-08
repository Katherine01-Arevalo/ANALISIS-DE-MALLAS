# ANALISIS-DE-MALLAS
**1.OBJETIVOS**

-Orientar al estudiante en el análisis de mallas de circuitos eléctricos.

-Contrastar los resultados teóricos y experimentales del análisis de malla.

-Generar los conocimientos y aptitudes para analizar circuitos eléctricos. 

**2. MARCO TEÓRICO**

![Marco_Teorico](https://github.com/Katherine01-Arevalo/ANALISIS-DE-MALLAS/blob/main/img/Marco_Teorico_Lab2.jpg)

**3.DIAGRAMAS**

![circuito](https://github.com/Katherine01-Arevalo/ANALISIS-DE-MALLAS/blob/main/img/circuito%20mallas.png)


**4.LISTA DE COMPONENTES**

|Cantidad | Material o Equipo|
| :---         |     ---:      |        
| 1 | Fuente de Voltaje de C.D.  |
| 1 |  Multímetro Digital | 
| 1 | Resistor de 820 Ω  | 
| 1 | Resistor de 390 Ω | 
| 1 | Resistor de 1 kΩ | 
| 1 | Resistor de 1.2 kΩ  | 
| 1 |  Resistor de 2.2 kΩ | 
| 1 | Protoboard  | 


**5.EXPLICACIÓN**

TEÓRICA

El circuito propuesto para el análisis tiene 3 mallas debido a que solo hay 3 caminos que son cerrados y no tienen un circuito dentro de ellos. 
Para hacer el estudio de cada malla es necesario hacer uso de la ley de voltajes de Kirchhoff, la cual manifiesta que la suma de voltajes debe ser igual a cero. 
Y de la ley de Ohm.

En la primera malla tenemos la fuente de 18 V., un resistor de 820 Ohm y otro de 1kOhm. El voltaje en la primera resistencia va a ser igual al producto de su resistencia por la Intensidad 1. El voltaje en la resistencia dos va a ser igual al producto de 1kOhm, que es su resistencia por la diferencia entre la Intensidad 1 y la Intensidad 2. Esta resta se da debido a que la Intensidad 2 fluye de manera opuesta a la Intensidad 1. La suma de estos voltajes en cada resistencia va a ser igual a 18V de la fuente.

En la segunda malla no tenemos fuentes de voltaje pero cada resistencia si va a tener un voltaje que fluya por ella. En la resistencia de 1kOhm hay un voltaje igual a la multiplicación de su resistencia por la diferencia de la Intensidad 2 menos la Intensidad 1. En este caso la Intensidad 2 es predominante, por ello se resta la corriente que fluye en dirección opuesta. El voltaje en la resistencia 2 va a ser igual a 1.2 kOhm por la Intensidad 2. El ultimo voltaje en esta malla es el que esta en la resistencia de 2.2 kOhm. Este es igual a el producto de 2.2 kOhm por la diferencia entre la Intensidad 2 menos la Intensidad 3. La Intensidad 3 esta opuesta a la Intensidad 2 en este resistor. La suma de todos estos voltajes debe ser igual a cero.  

La tercera malla tiene una fuente de voltaje de 5V. El voltaje en la resistencia de 2.2kOhm va a ser igual a la multiplicacion de su resistencia por la resta de Intensidad 3 menos Intensidad 2, aqui Intensidad 3 es preponderante por lo cual Intensidad 2 fluye contraria y se la resta. El voltaje de la resistencia de 390 Ohm va a ser el producto de esta con la Intensidad 3. La suma de estos tres voltajes debe ser giaul a cero. 

De cada malla se obtuvo una ecuacion. Se forma un sistema de ecuaciones que hay que resolverlo para determinar los valores de la intensidad de cada malla. 


PRÁCTICA

Haciendo uso del Software Proteus se construye un circuito como el propuesto y se coloca los amperimetros dentro de cada malla, en serie. Se necesita una placa de pruebas, 2 fuentes de voltaje de 18V y 5V cada una, 5 resistores (0.820, 1, 1.2, 2.2, 0.390)kOhm. Y 3 multímetros o amperímetros, uno para cada malla. De esta manera se puede medir la intensidad de corriente fluyendo en cada malla. 

**6.APORTACIONES**

![simulacion](https://github.com/Katherine01-Arevalo/ANALISIS-DE-MALLAS/blob/main/img/simulacion-malla.png)

TABLA 1.1

| MALLA | RESULTADO ANALÍTICO | RESULTADO EXPERIMENTAL |
| :---         |     :---:      |          ---: |
| 1            |  11.45mA  | 11.5mA |
| 2            | 2.847mA   | 2.85mA |
| 3            | 0.4881mA | 0.49mA |

ERROR 

eI%=|valor teorico-valorcalculado|/(valor teorico )*100

eI_1%=|11.45-11.50|/( 11.45)*100=0.4%

eI_2%=|2.847-2.85|/( 2.847)*100=0.1%

eI_3%=|0.4881-0.49|/( 0.4881)*100=0.3%



**7.Manual de Usuario**

**8. Prerrequisitos** 

Al instalar 

-Se finaliza la instalación dar clic derecho sobre el   icono, luego en "propiedades", luego en la pestaña "compatibilidad", marcar la casilla  donde indica "Ejecutar este  programa como administrador", dar clic en aplicar y luego en aceptar si no se realiza ese paso no cargará ninguna librería. 

-Al instante de generar la simulación tener en cuenta la unidad de media  para el uso del amperímetro

-Verificar que el circuito se encuentre bien conectado caso contrario  se generara datos erróneos

**8.CONCLUSIONES**

Se llega a la conclusión de  que la cantidad de corrientes del circuito depende de las mallas que tenga el mismo ,mediante la ley de voltaje de Kirchoff  facilita  analizar las mallas que tiene el circuito en estudio, se llegó a obtener un sistema de ecuaciones el cual arrojo el valor de cada corriente en dicha malla.

De manera teórica y práctica se llega a verificar que el análisis de mallas facilita el estudio del circuito propuesto se  observa un mínimo error  el cual se da por la cantidad de decimales que se maneja.


**9.BIBLIOGRAFIA**

-Alulema, D. (2020) Práctica No. 2 Análisis de Mallas. Recuperado de: https://classroom.google.com/c/MTcyOTU5MzQ3MDgw/m/MTk1NTU3MTAxMTAz/details

-Alulema, D. (2020) Fundamentos de Circuitos Eléctricos: CAP3 v1.1. Recuperado de: https://classroom.google.com/c/MTcyOTU5MzQ3MTAw/m/MTk1NTE4ODg1ODQz/details

-Burgos, J., Pinillos, C. y García, S. (2014) Análisis de Malla-Divisor de Tensión. Universidad Distrital Francisco José de Caldas. Recuperado de: https://www.studocu.com/co/document/universidad-distrital-francisco-jose-de-caldas/circuitos-i/informe/lab-no-3-analisis-de-mallas/4990704/view

-Universidad Distrital Francisco José de Caldas. (s.f.) Circuitos Mediante Análisis de Mallas. Universidad Distrital Francisco José de Caldas. Recuperado de: https://www.studocu.com/co/document/universidad-distrital-francisco-jose-de-caldas/circuitos-i/practica/laboratorio-6/4966522/view

-García, A. (2013) Ley de los voltajes de Kirchhoff: Método de Mallas. Panamahitek. Recuperado de: http://panamahitek.com/ley-de-los-voltajes-de-kirchhoff-metodo-de-mallas/#:~:text=En%20un%20circuito%20el%C3%A9ctrico%2C%20una,formadas%20por%204%20caminos%20cerrados.&text=Si%20multiplicamos%20las%20corrientes%20de,el%20total%20debe%20ser%20cero.

-Calculadora de Matrices. (s. f.). matrixcalc. Recuperado 8 de enero de 2021, de https://matrixcalc.org/es/

**9.ANEXOS**
