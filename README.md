# TAG-2-UNI-2

1. Objetivos

1.1. Objetivo General

Conocer a cerca del analisis de ramas, lazos y nodos, además del electomagnetismo y  manegtismo, mediante la lectura de la informmación encontrada en el libro y en otras fuentes , para elaborar organizadores gráficos que contengan información contundente y así poder aplicar en la resolución de los ejercicios propuestos en cada capítulo. 

1.2. Objetivos específicos

Realizar organizadores gráficos donde muestren información sobre los temas principales  de analisis de ramas, lazos y nodos, de igual manera con el tema de manectismo y electromagnetismo.

Resolver los ejercicios de manera correcta, aplicando conceptos importantes. 

Identificar las formulas a utiliza en la resolución de los problemas planteados . 

2. Marco Teórico

![image](https://user-images.githubusercontent.com/93958596/148309262-1ea36cb1-29c1-4e57-8016-2257dca37d4b.png)

![image](https://user-images.githubusercontent.com/93958596/148309275-d5f6fa8e-fab4-4254-938f-2c6dfce9b648.png)

3. Explicación y resolución de ejercicios

Capitulo 9 

1. Con el método de sustitución, resuelva el siguiente conjunto de ecuaciones para IR1 e IR2.

![image](https://user-images.githubusercontent.com/94153604/148318244-9ab43641-00b8-4173-b494-b489970a6cfd.png)

![image](https://user-images.githubusercontent.com/94153604/148318284-7f73b4f0-7f9e-4f3d-be2f-5feb67a90750.png)

2. Utilizando determinantes, resuelva el siguiente conjunto de ecuaciones para ambas corrientes:

![image](https://user-images.githubusercontent.com/94153604/148318335-e4463827-c1f8-4662-8afb-62ddc596b9cf.png)

![image](https://user-images.githubusercontent.com/94153604/148318358-44c4a63b-5db5-4938-9c9b-a4f207f384be.png)

3. Evalúe cada uno de los determinantes:

![image](https://user-images.githubusercontent.com/94153604/148318394-9eeaff5b-747f-4a33-b84b-12ecdc861f36.png)

-4800-6000-(1920+3750)=-16470

![image](https://user-images.githubusercontent.com/94153604/148318434-20febca5-8738-48b1-8407-6d9fbc0f6d94.png)

-2.40+0-1.72-(1.17-3.69+0)=-1.6

4. Resuelva para I1, I2, I3 en el siguiente conjunto de ecuaciones con determinantes:

![image](https://user-images.githubusercontent.com/94153604/148318480-919ea881-93fa-468b-8bb0-ac88ef0e91bb.png)

![image](https://user-images.githubusercontent.com/94153604/148318519-5be02f62-44cc-4b92-bf58-f4e25580c470.png)

5. Resuelva las dos ecuaciones simultáneas del problema 1 con su calculadora.

![image](https://user-images.githubusercontent.com/94153604/148318549-2766e79e-812c-458e-b79a-91013fe61e99.png)
![image](https://user-images.githubusercontent.com/94153604/148318560-82df3bd5-1bc5-4169-93fb-37af16d3df51.png)

6. Escriba la ecuación de la corriente de Kirchhoff para la asignación de corriente mostrada en el nodo A en la figura 9-26.

![image](https://user-images.githubusercontent.com/94153604/148318591-2f6dbaec-c91a-47eb-8f6c-96108cf4d9ff.png)

Ecuación (Kirchhoff): ![image](https://user-images.githubusercontent.com/94153604/148318650-51d7c896-c5b1-498f-a722-0027d2ecd7ff.png)

7. Determine la caída de voltaje entre los extremos de cada resistor mostrado en la figura 9-26

![image](https://user-images.githubusercontent.com/93958596/148322925-72c2f67e-a78d-4810-9fe9-5ffbf0b8a5a8.png)

    Aplicando la ley del voltaje de Kirchhoff alrededor del lazo izquierdo se obtiene:
    VR1 + VR2 + VS1 = 0
    8.2 Ω * I1 + 10 Ω * I2 + 12 V = 0		(1)

    Aplicando la ley del voltaje de Kirchhoff alrededor del lazo izquierdo se obtiene:
    VR2 + 6V – VR3 = 0
    10 Ω * I2 + 6 V – 5.6 Ω * I3 = 0		(2)

    En el nodo A, la ecuación de corriente es:
    I1 – I2 – I3 = 0
    I1 = I2 + I3

    Sustituimos I1 en la primera ecuación (1) y despejamos I2. Para facilidad no colocamos las unidades:
    8.2* (I2 + I3) + 10 * I2 + 12 = 0
    8.2*I2 + 8.2*I3 + 10 * I2 + 12 = 0
    18.2*I2 + 8.2*I3 = -12
    18.2*I2 = -12 – 8.2*I3
    I2 = (-12 – 8.2*I3) / 18.2

    Reemplazamos I2 en la ecuación (2) y hallamos I3.
    10 * (-12 – 8.2*I3) / 18.2 + 6 – 5.6 * I3 = 0
    (-120 – 82*I3) / 18.2 – 5.6 * I3 = -6
    (-120 – 82*I3 – 101.92*I3) / 18.2 = -6
    -120 – 183.92*I3 = -6*18.2
    -183.92*I3 = -109.2 + 120
    I3 = 10.8 / -183.92 = -0.0587 A = -58.7 mA

    Ahora reemplazamos I3 en la ecuación (2):
    10*I2 + 6 – 5.6*(-0.0587) = 0
    10*I2 = -6 – 0.33
    10*I2 = -6.33
    I2 = -6.33 / 10
    I2 = -0.633 A = -633 mA

    Ahora reemplazamos I2 en la ecuación (1):
    8.2*I1 + 10*(-0.633) + 12 = 0
    8.2*I1 = 6.33 – 12
    I1 = -5.67 / 8.2
    I1 = -0.6915 A = -691.5 mA

    Entonces los voltajes son:
    VR1 = 8.2 Ω * 0.6915 A = 5.67 V
    VR2 = 10 Ω * 0.633 A = 6.33 V
    VR3 = 5.6 Ω * 0.0587 A = 0.328 V = 328 mV

8. Indique la polaridad real de los voltajes hallados en el ejercicio 13.

Como las corrientes salieron negativas, la dirección de los voltajes queda de la siguiente manera

![image](https://user-images.githubusercontent.com/93958596/148323076-725407d1-1825-472c-acfa-81714f1b41b7.png)

9. Con el método de la corriente en lazos, determine las corrientes en los lazos que aparecen en la figura 9-28

![image](https://user-images.githubusercontent.com/93958596/148323117-16d65471-b710-4775-8127-351c735783c1.png)

Hallar las ecuaciones en función de las corrientes y las resistencias:

    Para el lazo A:
    (1000 + 560) * IA – 560 * IB - 4 - 2 = 0
    1560 * IA – 560 * IB = 6		(1)

    Para e lazo B:
    -560 * IA + (560 + 820) * IB + 6 – 4 = 0
     -560 * IA + 1380 * IB = -2	(2)

    Despejamos IA en la primera ecuación (1):
    IA = (6 + 560 * IB) / -1560

    Reemplazamos en la ecuación (2):
    -560 * (6 + 560 * IB) / -1560 + 1380 * IB = -2
    0.36 * (6 + 560 * IB) + 1380 * IB = -2
    2.16 + 201.6*IB + 1380*IB = -2
    1581.6*IB = -2.16 – 2
    IB = -4.16 / 1581.6 = -0.00263 A = -2.63 mA

    Reemplazamos IB en la segunda ecuación (2):
    -560 * IA + 1380 * -0.00263 A = -2
    -560 *IA - 3.63 = -2
    560 * IA = 1.38
    IA = 1.38 / 560 = 0.0025 A = 2.5 mA

10.	Determine los voltajes y sus polaridades apropiadas en cada uno de los resistores mostrados en la figura 9-28

![image](https://user-images.githubusercontent.com/93958596/148323230-6af443ba-0743-432d-a24d-241356d5eae4.png)

    La corriente en I1 = IA
    V1 = 1000 Ω * 0.0025 A = 2.5 V
    La corriente en I2 = IB
    V1 = 820 Ω * 0.00263 A = 2.2 V
    La corriente I3 = IA – IB = 0.0025 A – (-0.00263 A) = 0.26 A
    V3 = 560 Ω * 0.26 A = 145.6 V

La polaridad es:

![image](https://user-images.githubusercontent.com/93958596/148323273-bc3b179d-abca-4088-920e-c753457c4212.png)

11. Resuelva para las corrientes de lazo en la figura 9-29 con su calculadora:

![image](https://user-images.githubusercontent.com/93958596/148323303-cf39d2fb-c411-4694-906f-cfc2c10441fd.png)

    Para el lazo A:
    (47 + 10) * IA – 10 * IB = 1.5

    Para el lazo B:
    -10 * IA + (10 + 27 + 4.7) * IB = -3 

    Para el lazo C:
    -4.7 * IB + (4.7 + 15) * IC = -1.5 + 3

![image](https://user-images.githubusercontent.com/93958596/148323357-b3ffee9f-655b-4ad4-89a3-da654e31c869.png)

Entonces las corrientes son:

    IA = 0.0143 A = 14.3 mA
    IB = -0.0613 A = -61.3 mA
    IC = 0.0615 A = 61.5 mA

Determine el voltaje entre las terminales del puente abierto, A y B

![image](https://user-images.githubusercontent.com/94011974/148329620-c6edfc2c-de85-4784-9343-81ed8485fd56.png)

![image](https://user-images.githubusercontent.com/94011974/148329661-d1585295-a894-4ecb-807d-479d94bec086.png)

12. Escriba las ecuaciones de lazo en la forma eestandar para el ciercuito puente T 

![image](https://user-images.githubusercontent.com/94011974/148329787-5010ea39-e225-4471-8a0e-3666b3b0b153.png)

![image](https://user-images.githubusercontent.com/94011974/148329843-df863544-7cae-4f55-9635-856360ed2c08.png)

13. Cuales son los valores de corriente de rama En cada rama muestre la direccion real de la corriente

![image](https://user-images.githubusercontent.com/94011974/148329980-4fd8f7c5-f7ae-44c2-85b1-7b619783e1ef.png)

![image](https://user-images.githubusercontent.com/94011974/148330019-d3abeb76-3c15-454c-bd8e-75fb9330ca69.png)

14. Use el analisis de nodos para determunar el voltaje en los puntos A y B con respecto a tierra

![image](https://user-images.githubusercontent.com/94011974/148330130-49f55a17-bbe9-47c6-b321-0681b4b0452c.png)

15. Use el analisis de nodos el de lazos o cualquier otro procedimeineto para determinar las corrientes y los voltajes en cada nodo desconocido

![image](https://user-images.githubusercontent.com/94011974/148330297-73a1c749-130e-4a87-adc8-bc82f27c0259.png)

![image](https://user-images.githubusercontent.com/94011974/148330336-32e5239e-d313-48d6-8574-453919933220.png)

Capitulo 10

1. El area de seccion transversal de un campo magnetico se incrementa, pero el flujo no cambia . La densidad de flujo aumenta o disminuye.

        Disminuye

2.Cual es el flujo en un matrerial magnetico cuando la densidad de flujo es de 2500x10 -6 T y el area de seccion transversal mide 150 cm 

        37.5 uWb

3. Un iman permanente muy fuerte tiene un campo magnetico de 1000000uT Exprese esta densidad de flujo en gauss

        1000 G

4. Cual es la permeabbilidad relativa de un material ferromagnetico cuya permeabilidad absoluta es de 750x10-6 Wb/At-m?

        597

5. Cual es la fuerza magnetomotriz en una bobina de 50 vueltas de hilo hay 3 A de corriente a traves de el

        150 At
        
6. ¿Qué fuerza mueve el émbolo de imán cuando se activa un solenoide? ¿Qué fuerza hace que el émbolo de imán regrese a su posición de reposo?

        -	La fuerza que lo mueve es el campo electromagnético
        -	El resorte hace que el émbolo regrese a su posición

7. ¿Qué ocasiona que la aguja instalada en un movimiento de d’Arsonval se deflexione cuando circula corriente a través de la bobina?

        Las fuerzas producidas por la interacción del campo electromagnético y el campo magnético permanente hacen que la aguja se deflexione

8. ¿Cómo se puede cambiar la densidad de flujo en la figura 10-44 sin alterar las características físicas del núcleo?

![image](https://user-images.githubusercontent.com/93958596/148383155-95164fd3-9536-4d4a-8c29-7acada31f38c.png)

        Esto se puede hacer cambiando la corriente
        
9. Determine a partir de las curvas de histéresis mostradas en la figura 10-45 qué material tiene más retentividad.

![image](https://user-images.githubusercontent.com/93958596/148383212-a09c40e5-ae4e-4005-a79e-8210e23393d7.png)

        El material que tiene mayor retentividad es el material A

10. ¿Cuáles son los tres factores que determinan el voltaje en un conductor que se mueve en dirección perpendicular al campo magnético?

La intensidad del campo magnético, la longitud del conductor expuesta al campo, y la velocidad de rotación del conductor

11. ¿Cómo complementa la ley de Lenz a la ley de Faraday?

La ley de Lenz define la polaridad o dirección del voltaje inducido.

Explique el propósito del conmutador y de las escobillas en la figura 10-35.

![image](https://user-images.githubusercontent.com/94153604/148386693-23d894d5-a667-4493-abf8-b956fba4ef47.png)

El ensamble de conmutador y escobilla conecta eléctricamente la espira al circuito externo

13. Suponga que se agrega otra espira, a 90 grados de la primera, al generador de cd del problema 24. Trace una gráfica del voltaje contra el tiempo para mostrar cómo aparece el voltaje de salida. Sea de 10 V el voltaje máximo.

![image](https://user-images.githubusercontent.com/94153604/148386788-5e92be3f-57af-4278-97b4-74732bf1e5d8.png)

4. Video

https://www.youtube.com/watch?v=ofYJrRA_9JY

5. Conclusiones

En el analisis de  ramas, lazos y nodos se encuentran las ecuaciones de segundo y tercer grado, mediate su soluciòn se obtendra el valor de las incognitas, se puede resolver por medio de sustituciòn, determinantes o la calculadora. El metodo de  la corriente en ramas  conlleva unos pasos a seguir para facilitar  la solución del problema , así mismo el método del voltaje de nodos y el método de la corriente en trayectorias cerradas. El electomagnetismo  se divide en diferentes subtemas con la presencia de varias formulas. 

En la solución de los ejercicios se debe manejar de manera correcta los metodos para resolver ecuaciones d eprimer y segundo orden ásdema de conocer que el método  de la corriente en ramas  utiliza  las leyes de voltaje y de la corriente de kirchhoff,en el caso de magnetismo y electromagnetismo , se puede definor que el grupo de líneas de fuerza que van del polo norte al polo sur de un imán se llama flujo magnetico, la densidad de flujo magnético es la cantidad de flujo por unidad de área perpendicular al campo magnético, también s eencuentran presentes las propiedades electromagnéticas. 

En el caso de analisis de  ramas, lazos y nodos no existen formulas definidas, puesto que como se manifiesta que se analiza el circuito para poder establecer ecuaciones de segundo o tercer orden,  pero en el caso de magnetismo y electromagnetismo se  determina la formula de  densidad de flujo magnetico , permeabilidad, entre otros. 

6. Bibliografía

Floyd, T. (2007). Principio de Circuitos Eléctricos. Pearson, Prentice Hall
