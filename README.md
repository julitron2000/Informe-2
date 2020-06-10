# Informe N°2 ANÁLISIS DE MALLAS

AUTORES: DAVID HINOJOSA,
         JAVIER DELGADO,
         JULIO ROSERO.

## 1. PLANTEAMIENTO DEL PROBLEMA
Al momento de analizar circuitos, frecuentemente, se presentan casos en los que es indispensable aplicar un análisis por método de mallas, por lo que conocer y saber utilizar este método debe ser un requisito necesario para realizar cualquier análisis de un circuito tanto en la práctica como en la teoría.

## 2. OBJETIVOS
- Comprobar experimentalmente el Análisis de Mallas.
- Medir y registrar las corrientes en cada malla del circuito.

## 3. MARCO TEÓRICO 
Un circuito plano se define como un circuito hecho de tal manera que ninguna rama quede por debajo o por encima de ninguna otra rama.

![](https://analisisdecircuitos1.files.wordpress.com/2014/08/screenshot2971.jpg)

Una malla se define como un lazo o trayectoria cerrada que no contiene ningún otro lazo dentro de él.

![image](https://user-images.githubusercontent.com/64505672/84106123-ebf93380-a9df-11ea-8d54-332421d6126a.png)

El método de Mallas es un método utilizado para resolver circuitos planos.

Los pasos para determinar las corrientes de lazo son:
1. Asigne las corrientes de lazo i1
, i2
, …, in a los n lazos.
2. Aplique la LTK a cada uno de los n lazos. Use la ley de Ohm para expresar las tensiones en términos de las corrientes de lazo.
3. Resuelva las n ecuaciones simultáneas resultantes para obtener las
corrientes de lazo

## 4. DIAGRAMAS

![WINWORD_UQe0yFsSPQ](https://user-images.githubusercontent.com/66037763/84236229-f2a9a880-aabc-11ea-9cdd-f8f1072979fe.png)

El circuito base del cual se hace el respectivo análisis de mallas. Los nodos encerrados en rojo son referencia para la creación del circuito en simuladores. Se encuentra también graficados dentro de las mallas, las corrientes con la asumida dirección inicial que cada una tiene. 
Dentro del circuito el voltaje parte de dos fuentes ubicadas paralelamente en mallas distintas, la primera de 18v se encuentra en serie con el resistor de 820ohm, mientras que la otra de 5v está a su vez en serie con un resistor de 390ohm.

## 5. LISTA DE COMPONENTES
A. Fuente de Voltaje de C.D.


![chrome_FxjHlWp3kM](https://user-images.githubusercontent.com/66037763/84236034-96df1f80-aabc-11ea-9159-3d2235bc315b.png)


B. Multímetro Digital

![chrome_1E7H2m0GOE](https://user-images.githubusercontent.com/66037763/84236069-a6f6ff00-aabc-11ea-90f8-49d128847e17.png)


C. Resistor de 820 Ω


![chrome_H59RekD0Sn](https://user-images.githubusercontent.com/66037763/84236097-b4ac8480-aabc-11ea-88e9-0930cd8a6151.png)


D. Resistor de 390 Ω


![chrome_nYj42XTcAA](https://user-images.githubusercontent.com/66037763/84236121-bc6c2900-aabc-11ea-9052-20d1e126c649.png)


E. Resistor de 1 kΩ


![chrome_jPVmQCB5dn](https://user-images.githubusercontent.com/66037763/84236149-cbeb7200-aabc-11ea-96d9-4b01e8f8ef81.png)


F. Resistor de 1.2 kΩ


![chrome_RgP3H68Ui2](https://user-images.githubusercontent.com/66037763/84236162-d60d7080-aabc-11ea-864d-536485900f86.png)


G. Resistor de 2.2 kΩ

![chrome_u6waqAZiNN](https://user-images.githubusercontent.com/66037763/84236192-e0c80580-aabc-11ea-9767-487481f78259.png)


H. Protoboard

![chrome_gnkRWUT4Si](https://user-images.githubusercontent.com/66037763/84236208-e9b8d700-aabc-11ea-9985-2e94ef9d6adb.png)


## 6. DESCRIPCION DE PREREQUISITOS Y CONFIGURACION
Se tiene el circuito propuesto y se procedió a realizar las mediciones de caída de voltaje en función de las respectivas corrientes que pasan por cada malla. Para más adelante resolver un sistema de 3 ecuaciones con 3 incógnitas. 


![WINWORD_gH5Kq8tgYD](https://user-images.githubusercontent.com/66037763/84239112-a3b24200-aac1-11ea-97bf-b80464cfeed6.png)


Se obtuvo los valores medidos, calculados y simulados, y se registró en la siguiente tabla.


![chrome_U2wfQuI7Pj](https://user-images.githubusercontent.com/66037763/84238414-a52f3a80-aac0-11ea-8129-609c0742c5c8.png)


Gracias a la tabla se vuelve relativamente sencilla la comparación e interpretación de los resultados obtenidos en el experimento.

## 7. CRONOGRAMA
![0002](https://user-images.githubusercontent.com/66037557/84161169-98fd9b80-aa34-11ea-8945-b2883860b645.jpg)


## 8.CONCLUSIONES
-El valor obtenido del error experimental porcentual es de 0.29%, y se atribuye a factores como la presición del instrumento con el que se realiza las mediciones, la tolerancia que poseen las resistencias y el suministro de energía.

-Tras la elaboración de la practica pudimos observar y comprobar que nuestros datos experimentales y analíticos son muy cercanos entre sí, concluyendo así que las leyes de mallas de kirchoff se cumplen en nuestro circuito.

## 9.RECOMENDACIONES

-Armar el circuito de una forma didáctica para que todos puedan entender el funcionamiento del mismo.

-Hacer las respectivas mediciones con cuidado para no obtener datos errónes.

## 10. BIBLIOGRAFÍA

-M.Sadiku, C.Alexander, Fundamentos de circuitos eléctricos (3ra Edición), 2004.

-Allan, H.Robbins, Análisis de Circuitos. Teoría y práctica(4ta Edición), 2008.


 
