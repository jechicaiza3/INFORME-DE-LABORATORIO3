# INFORME-DE-LABORATORIO3
**UNIVERSIDAD DE LAS FUERZAS ARMADAS**

**DEPARTAMENTO DE ELECTRICA Y ELECTRÓNICA**

**FUNDAMENTOS DE CIRCUITOS ELECTRICOS**

Nombres : Martin Coronel, Jefferson Chicaiza, Tito Obando 

NRC: 10133

***Objetivo General***

- Analizar los voltajes en diferentes nodos de un circuito cerrado, mediante una práctica de laboratorio para comprender cómo se comportan las tensiones en los diferentes nodos. 

***Objetivo Especificos***
- Conocer los conceptos de nodos para identificar los principales y el de referencia.
- Realizar un circuito en un protoboard siguiendo la estructura dada por el docente para analizar las tensiones en los nodos 
- Medir  con el multimetro valores de las corrientes de las diferentes mallas. 
- Comparar los valores calculados por el método de tensiones en los nodos con los valores medidos para  determinar mayor validez a nuestro analisis.

**2.MARCO TEORICO**

![image](https://user-images.githubusercontent.com/84757114/172504113-aada31e6-8fd8-4bac-816d-7d5f4555563c.png)

**3.MATERIAL Y EQUIPO REQUERIDO**

![image](https://user-images.githubusercontent.com/84757114/172429785-a1d269ac-652e-4092-af92-523cf2796da2.png)

**4.EXPLICACIÓN DEL PROCEDIMIENTO**

*1. Arme el circuito que se muestra en la figura 1.1*

![image](https://user-images.githubusercontent.com/84757114/172430286-77dcd4bd-fd87-467d-be1d-992f4a8728c3.png)
![image](https://user-images.githubusercontent.com/84757114/172437594-ef571a6c-7c24-4a67-b533-f16201efd05e.png)

Primeramente se muestra el circuito realizado en el simulador tinkercad en el que se observa todos los componentes que se especifican en el diagrama como son los resistores, cables, fuentes de voltaje  y además la inicialización de la simulación.    

*2. Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1.*

![image](https://user-images.githubusercontent.com/84757114/172437721-6ef51291-7ede-4aa1-991e-f8d124277ee7.png)
Aquí se muestra la respectiva medición del voltaje en el primer nodo principal  con respecto al nodo de referencia en el que marca  el valor de 1.67 voltios. 

![image](https://user-images.githubusercontent.com/84757114/172437922-4901f847-e88f-47fe-ac67-befe273f3da7.png)
De la misma manera, en la medición del  segundo nodo principal se marca un valor de 5.39 voltios, es importante mencionar que el nodo de referencia se lo puede conectar en cualquier parte en donde actúe dicho nodo.

*3. Simule en el software Multisim, Proteus, o cualquier otro simulador, el circuito de la figura 3.1, obteniendo los valores de los voltajes de nodo. Anote los resultados en la tabla 3.1.*

![image](https://user-images.githubusercontent.com/84757114/172440338-6726437b-3c0c-4197-bcf5-0b7f130c439e.png)
En cuanto al circuito creado en multisim online se realizó la respectiva medición del primer nodo principal con respecto al nodo de referencia, dando como resultado 1.66 volteos 

![image](https://user-images.githubusercontent.com/84757114/172440628-23338a6e-9784-45bd-bcad-ce5ed4538335.png)
De la misma manera, la medición del voltaje en el  segundo nodo principal nos da un valor de 5.38 voltios con respecto al nodo de referencia.

*Calculos del voltaje por el método de tensiones en los nodos*

![image](https://user-images.githubusercontent.com/84757114/172441809-28715ca3-9bcd-4b8f-8cd0-40637d8df7f6.png)

Primeramente se identifican los nodos principales, el nodo de referencia y el sentido de la corriente, además se toma en cuenta que todas las corrientes de los nodos salen.    

![image](https://user-images.githubusercontent.com/84757114/172501505-fed80596-68f3-4956-98bc-967aad312c45.png)

Por lo tanto, la sumatoria de todas las corrientes que salen del nodo son iguales a cero. Al formarse una igualdad se debe establecer que dichas corrientes son iguales  al voltaje sobre la resistencia en base a la ley de ohm, por lo que se forman dos ecuaciones en función a los dos voltajes que quieren calcular. Dichas ecuaciones se las puede resolver mediante una calculadora de Sistemas ecuaciones lineales en este caso se utilizó symbolab en donde X=V 1 y Y=V2.

![image](https://user-images.githubusercontent.com/84757114/172502709-c02c2f15-b934-46a9-8b23-d0b8a1227e3c.png)

Como respuesta tenemos:
![image](https://user-images.githubusercontent.com/84757114/172502653-10ae2203-1bd3-45d4-bc11-2ccf5dc6da6c.png)

Pues si bien un resultado nos da negativo es importante mencionar que solo se tomó la  dirección de salida de la corriente para ambos nodos principales 

![image](https://user-images.githubusercontent.com/84757114/172502874-9a8cc516-693c-4e86-9fee-568cd4aba1a5.png)

*4. Compare los valores de la tabla 3.1 y realice sus conclusiones.*

![image](https://user-images.githubusercontent.com/84757114/172442135-2d27ea6d-e8b4-4f38-b981-797a496e2fd7.png)

**5. RESPUESTA A INTERROGANTES Y CALCULO DEL ERROR**

La comprobación de todos los valores de voltaje en los nodos principales por medio de la práctica, el cálculo y una simulación nos arrojaron valores muy similares entre ellos, por lo que la tensión en los nodos del circuito fueron obtenidos de manera correcta.

![image](https://user-images.githubusercontent.com/84757114/172503912-242d8978-edfa-4c37-9ca4-3f52a31b2ea1.png)

**6. VIDEO:**

https://youtu.be/x0atHrLqt2w

**7. CONCLUSIONES**
- Tener los conceptos claros en lo que ue se refiere a corriente y al definición de un nodo principal y de referencia nos ayudó a medir de forma precisa los diferentes voltajes que pasan por los nodos. 
- Se pudo observar que las leyes de kirchhoff son el camino para calcular los voltajes en los diferentes nodos. 
- Los valores analiticos, experimentales, simulados muestran una gran semejanza entre ellos, lo que signfica que los voltajes obtenidos en los nodos son precisos.
- Conocer el funcionamiento del multimetro nos ayudó a poder realizar de manera precisa las medicones en las mallas del circuito.

**8. BIBLIOGRAFÍA**

Floyd, T. (2007). *Principios de circuitos electricos* (Ed. 8va). Pearson EDUCATION.

Khan. (2015).*Khan Academy Las Leyes de Kirchhoff*. https://es.khanacademy.org/science/physics/circuits-topic/circuits-resistance/a/ee-kirchhoffs-laws

https://es.symbolab.com/solver/calculus-calculator/%F0%9D%91%99%F0%9D%91%96%F0%9D%91%9A%20%F0%9D%91%A5%E2%86%922%5Cfrac%7Bsen%5Cleft(x%5Cright)-sen%5Cleft(x%5Cright)%7D%7Bx-a%7D
