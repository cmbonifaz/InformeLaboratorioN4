# Informe de laboratorio N°4

**Integrantes:**

Christian Bonifaz, Jean Jacome, Kevin Sandoval

**NRC:** 5406

**Docente:** Ing. Darwin Alulema

**Tema:** TEOREMA DE SUPERPOSICION

#### 1. OBJETIVOS 

•	El objetivo de esta práctica es demostrar el teorema de superposición por dos métodos uno experimental y el otro teórico a partir de cálculos por el mismo método, en la manera en que se logre entender la funcionalidad de facilitar el cálculo de mediciones.

•	Comparar los resultado obtenidos por el teorema con los simulados en tinkercad para demostrar la efectividad del proceso de calculo de voltajes y corrientes del teorema 

•	Analizar el teorema de superposición en el circuito propuesto mediante la comprobación de mediciones experimentales y simulaciones con la ayuda de la herramienta tinkercad.

#### 2. MARCO TEÓRICO 

![image](https://user-images.githubusercontent.com/85208164/125888569-064b5a35-381a-49c3-a432-a9806dbb5b57.png)


#### 3. EXPLICACIÓN DEL PROCEDIMIENTO
3.1 El equipo requerido y utilizado para la elaboracion del circuito es el siguiente:

![materiales](https://user-images.githubusercontent.com/84586968/125867697-be7677ed-035d-4eb7-935f-35a15d9b7c23.PNG)

3.2 Implemente el circuito que se presenta en la figura

![normal](https://user-images.githubusercontent.com/84586968/125867778-d89cd500-30dc-48b0-8d72-87c5997aee28.PNG)

3.3 Con las dos fuentes conectadas, mida el voltaje VA y la corriente IX, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en las tablas respectivamente.

![circuito tinker](https://user-images.githubusercontent.com/84586968/125867694-baa7cbf7-e0d1-43cc-9f5c-2119bf31bcc1.PNG)

3.4 Haga “cero” la fuente de voltaje de 12 V (V2) y mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en las tablas respectivamente.

![simV1](https://user-images.githubusercontent.com/84586968/125867691-98746304-87f2-467b-ac5b-fcf5179e698e.PNG)

3.5 Haga “cero” la fuente de voltaje de 20 V (V1) y mida el voltaje VA y la corriente Ix, respetando tanto la polaridad del voltaje como el sentido de la corriente que se proporcionan. Anote el valor de las mediciones en las tablas respectivamente.

![simV2](https://user-images.githubusercontent.com/84586968/125867692-41375b0a-d2f3-4df6-bcea-75483edd02bf.PNG)

![tablas](https://user-images.githubusercontent.com/84586968/125867703-81946766-d0d5-45a6-9df1-ed18d1c59882.PNG)

#### 4. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR
**Corto circuito en V2** 

![V1](https://user-images.githubusercontent.com/84586968/125870487-376dc60e-3935-41a6-b582-10b6f964e05c.PNG)

V2=0

La corriente I4 es igual a 0 porque en la corriente I5 no existe resistencia

Por lo que la corriente va a fluir por I5 y no por I4

En la resistencia R4 no pasa ninguna corriente por lo que no le tomamos en cuenta

Calculamos la resistencia equivalente de R3 y R2

![1](https://user-images.githubusercontent.com/84586968/125896651-805d9ac5-ddaa-4306-b401-881c6aa42e46.PNG)

Calculamos la resistencia y corriente total

![2](https://user-images.githubusercontent.com/84586968/125896654-2534bfa8-d1e5-4de3-82a9-3bba822bd1f5.PNG)

Con el divisor de corriente encontramos la corriente en I3

![3](https://user-images.githubusercontent.com/84586968/125896662-3f9b2c34-b294-4d90-a1ea-ce6908dc8868.PNG)

Obtenemos:

![4](https://user-images.githubusercontent.com/84586968/125867664-7aed6f42-4c30-4e7e-bf72-0cbfb9d01d78.PNG)

**Corto Circuito en V2**

![v2](https://user-images.githubusercontent.com/84586968/125870488-509b2ba1-71b1-4fe7-9e46-890837a07625.PNG)

V1=0

Calculamos la resistencia equivalente de R1 y R2

![5](https://user-images.githubusercontent.com/84586968/125896671-58f9b2e9-6a0c-4b63-90e9-7c8b2417fc6a.PNG)

Sumamos la resistencia R3 y la resistencia equivalente

![6](https://user-images.githubusercontent.com/84586968/125896673-9a786f62-52f0-43aa-96f2-5dbbffabb805.PNG)

Y finalmente calculamos la resistencia total

![7](https://user-images.githubusercontent.com/84586968/125896679-11880471-10b1-4103-b561-49086507616a.PNG)

Encontramos la corriente total

![8](https://user-images.githubusercontent.com/84586968/125896681-f92ee969-4798-477d-8ed6-17eaf1655529.PNG)

Mediante el divisor de corriente encontramos I3

![9](https://user-images.githubusercontent.com/84586968/125896702-22bf9440-2c4d-48bd-a9ed-28c56e7f6f62.PNG)

Calculamos el voltaje V3

![10](https://user-images.githubusercontent.com/84586968/125896714-324f8d90-c2a3-481f-8168-9c8e8591f177.PNG)

Mediante divisor de corriente encontramos I4

![11](https://user-images.githubusercontent.com/84586968/125896720-4679c957-65f9-4ecc-bdd0-797c6ee88ec3.PNG)

Obtenemos:

![12](https://user-images.githubusercontent.com/84586968/125869812-56c08097-f38d-4aae-823b-816fe4c60a3c.PNG)

Restamos los voltajes y las corrientes para obtener los resultados reales 

![13](https://user-images.githubusercontent.com/84586968/125869813-6749453c-8193-49d5-b555-6b3e9360bc5f.PNG)

**Porcentajes de Error**

![error](https://user-images.githubusercontent.com/84586968/125867699-2d2c0e51-b5de-488b-a46e-0f5b253d2d37.PNG)

#### 5. VIDEO

[Simulación de Circuito - Laboratorio N°4](https://youtu.be/LZbgU99uJYQ "Simulación de Circuito - Laboratorio N°4")

#### 6. CONCLUSIONES 

•	Se concluye que el teorema de superposición es válido, la tensión entre los extremos (o la corriente) de un elemento en un circuito lineal es la suma algebraica de las tensiones (o corrientes) a través de ese elemento.

•	Mediante la aplicacion del teorema se observo que la corriente I3 busco el camino mas facil donde fluir elijiendo una la trayectoria de I5 donde no habia resistencia por lo que la corriente I3 quedo sin corriente.

• El Teorema de superposición permite evaluar los datos proporcionados por cada una de las fuentes en las diferentes resistencias del sistema para luego sumar estos datos y hallar los verdaderos valores proporcionados en el circuito

#### 7. BIBLIOGRAFÍA

Floyd,   T.   “ley   de   Ohm-   principio   de   superposición”   enPrincipios de circuitos Eléctricos, , 8th ed. México.

Charles,   A.   “Superposición,”   en  Fundamentos   de   circuitoseléctricos, 3th ed. México.


