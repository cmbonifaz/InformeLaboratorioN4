# Informe de laboratorio N°4

**Integrantes:**

Christian Bonifaz, Jean Jacome, Kevin Sandoval

**NRC:** 5406

**Docente:** Ing. Darwin Alulema

**Tema:** TEOREMA DE SUPERPOSICION

#### 1. OBJETIVOS 

•	El objetivo de esta práctica es demostrar el teorema de superposición por dos métodos uno experimental y el otro teórico a partir de cálculos por el mismo método, en la manera en que se logre entender la funcionalidad de facilitar el cálculo de mediciones.

•	Comparar los resultado obtenidos por el teorema con los simulados en tinkercad para demostrar la efectividad del proceso de calculo de voltajes y corrientes del teorema 

#### 2. MARCO TEÓRICO 

![image](https://user-images.githubusercontent.com/85208164/125861394-3c6dde80-a335-4a73-8ccc-573c9abf6722.png)

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

![1](https://user-images.githubusercontent.com/84586968/125867653-d0744c70-c352-4104-9c92-083429f302a4.PNG)

Calculamos la resistencia y corriente total

![2](https://user-images.githubusercontent.com/84586968/125867655-05f70c2b-87f3-4a1d-b80f-d554e6ad8379.PNG)

Con el divisor de corriente encontramos la corriente en I3

![3](https://user-images.githubusercontent.com/84586968/125867659-1fcba381-96d9-4302-8b37-9515038d3b9e.PNG)

Obtenemos:

![4](https://user-images.githubusercontent.com/84586968/125867664-7aed6f42-4c30-4e7e-bf72-0cbfb9d01d78.PNG)

**Corto Circuito en V2**

![v2](https://user-images.githubusercontent.com/84586968/125870488-509b2ba1-71b1-4fe7-9e46-890837a07625.PNG)

V1=0

Calculamos la resistencia equivalente de R1 y R2

![5](https://user-images.githubusercontent.com/84586968/125867667-4af3a375-6680-4d46-bf11-27a12bd248c9.PNG)

Sumamos la resistencia R3 y la resistencia equivalente

![6](https://user-images.githubusercontent.com/84586968/125867671-6fde70c9-8999-44d6-a971-c02d6a5baffa.PNG)

Y finalmente calculamos la resistencia total

![7](https://user-images.githubusercontent.com/84586968/125869805-d2e015ed-2b2e-42b1-ba2a-b12dfba8551f.PNG)

Encontramos la corriente total

![8](https://user-images.githubusercontent.com/84586968/125869806-4a54abe7-5f21-4c82-a854-67eb44fd8bfe.PNG)

Mediante el divisor de corriente encontramos I3

![9](https://user-images.githubusercontent.com/84586968/125869807-c4114e9d-610e-4354-816c-8bc90d967b28.PNG)

Calculamos el voltaje V3

![10](https://user-images.githubusercontent.com/84586968/125869809-ae515a9a-24a0-42cc-91f1-c3f6b3ca8870.PNG)

Mediante divisor de corriente encontramos I4

![11](https://user-images.githubusercontent.com/84586968/125869811-fd55e932-6260-4004-9d36-904e20b56c09.PNG)

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
