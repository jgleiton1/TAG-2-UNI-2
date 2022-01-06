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


