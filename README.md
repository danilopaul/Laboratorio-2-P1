# Laboratorio-2-P1

                                                   Universodad de las Fuerzas Armadas - ESPE
                                                     Fundamentos de Circuitos Electróinicos
        Integrantes:
        - Cholca Paul
        - Sandal Andrés
        - Vasquez Lady
 
1.Objetivo

1.1 Objetivo General.

Definir las características y pasos empleados en el método de las corrientes de malla para aplicarlos en la resolución y cálculos de los ejercicios planteados por medio del uso adecuado de la ley de ohm como de la ley de kirchhoff de voltajes en el planteamiento de ecuaciones.

1.2 Objetivo  Especificos

-  Relacionar la ley de ohm con la ley de kirchhoff adecuadamente para el planteamiento y resolución de ecuaciones.
-  Realizar una inspección analítica correcta en el circuito para poder aplicar el método de mallas de la forma adecuada.
-  Obtener las ecuaciones necesarias para poder obtener los datos requeridos con los cuales se pueda comprobar que está bien armado el circuito.

2.Marco teorico.

![image](https://user-images.githubusercontent.com/105684550/172289671-37fbd75a-127d-49f3-abf7-e49fc4179894.png)

3.Requisitos previos

- Malla 1:

![image](https://user-images.githubusercontent.com/105684550/172289883-56c040e9-89ef-4f94-81da-8f2e4051b2d7.png)

- Malla 2:

![image](https://user-images.githubusercontent.com/105684550/172289900-f9a99611-6f56-4f64-9933-657f6005cc72.png)

- Malla 3:

![image](https://user-images.githubusercontent.com/105684550/172289922-e23d7ba4-c1c4-49ae-8c24-834adbc7783f.png)

4.Materiales y equipos requeridos

![image](https://user-images.githubusercontent.com/105684550/172290444-1b32cde8-f3e9-497e-ba3b-95e74281fca5.png)

5.Procedimiento

![image](https://user-images.githubusercontent.com/105684550/172298433-9be1b8e5-64ef-4816-a3dc-27a7da35a3ee.png)

- Malla 1: 

5V=0.82kΩ(I1)+1kΩ(I1-I2)

5V=0.82kΩ(I1)+1kΩ(I1)-1kΩ(I2)

5V=1.82kΩ(I1)-1kΩ(I2)       →      Ecuación N°1

- Malla 2:

0V=1.2kΩ(I2)+2.2kΩ(I2-I1)+1kΩ(I2-I3)

0V=1.2kΩ(I2)+2.2kΩ(I2-I1)+1kΩ(I2-I3)

0V=1.2kΩ(I2)+2.2kΩ(I2)-2.2kΩ(I3)+1kΩ(I2)-1kΩ(I1)

0V=-1kΩ(I1)+4.4kΩ(I2)-2.2kΩ(I3)       →       Ecuación N°2


- Malla 3: 

10V=0.39kΩ(I3)+2.2kΩ(I3-I2)

10V=0.39kΩ(I3)+2.2kΩ(I3)-2.2kΩ(I2)

10V=-2.2kΩ(I2)+2.59kΩ(I3)       →      Ecuación N°3

- Ahora resolvemos el sistema de ecuación y obtenemos las siguientes respuestas:

I1=5.86mA

I2=5.67mA

I3=8.86mA

![image](https://user-images.githubusercontent.com/105684550/172297833-86016d45-5e27-4fed-b468-6699360faef5.png)

- Cálulo de errores de medición en malla 1:

error%=((5,86mA-5.86mA)/5.86mA)×100=0%

- Cálulo de errores de medición en malla 2:

error%=((5,67mA-5.67mA)/5.67mA)×100=0%

- Cálulo de errores de medición en malla 3:

error%=((5,67mA-5.67mA)/5.68mA)×100=0.11%

5.Video


6.Conclusiones:

En conclusión, para realizar el análisis de mallas es necesario conocer los conceptos relacionados con la ley de Ohm y ley de voltaje de Kirchhoff, que nos permitir aplicar el método de mallas para calcular la corriente de cada una de ellas.

Los datos que se obtuvieron con el simulador Tinkercard y en el protoboard varían un poico desde ña corriente que ingresa al circuito, sin embargo, se observó que el simulador se obtuvo medidas más precisas a los cálculos cosa que no fue igual con el circuito armado en el protoboard. 

Finalmente, es necesario realizar una comparación de los datos obtenidos mediante la aplicación de las fórmulas para obtener las ecuaciones necesarias y calcular los valores necesarios para cálculo de la corriente en cada malla del circuito propuesto, por lo cual los datos que se obtuvieron en los simuladores varían con los datos medidos en el protoboard y con ellos obtener el cálculo de errores.    


7.Bibliografía

Floyd, TL (2007). Principios de Circuitos Eléctricos. CDMX: Persona Educación.
