# Informe-Tarea-9

Universidad de las Fuerzas Armadas - ESPE

Fundamentos de Circuitos Eléctricos 

1. Objetivos

Objetivo General

Analizar los conceptos de circuitos RLC, resonancia y filtros pasivos por medio de una ardua investigación en artículos y foros para aplicar el conocimiento adquirido en el desarrollo de ejercicios propuestos.

Objetivos Específicos

•	Investigar los conceptos de circuitos RLC y resonancia para su correcta aplicación

•	Investigar el concepto de filtros pasivos para su correcta comprensión

2. Marco teórico

CIRCUITOS RLC Y RESONANCIA

En un circuito RLC, los elementos más fundamentales de un resistor, inductor y condensador están conectados a través de una fuente de voltaje.

Todos estos elementos son de naturaleza lineal y pasiva. Los componentes pasivos son aquellos que consumen energía en lugar de producirla; Los elementos lineales son aquellos que tienen una relación lineal entre voltaje y corriente. 

Circuito RLC en serie

Un circuito RLC en serie contiene resistencia, inductancia y capacitancia. Como la reactancia inductiva y la reactancia capacitiva tienen efectos opuestos en el ángulo de fase del circuito, la reactancia total es menor que cualquier reactancia individual, siendo:

![image](https://user-images.githubusercontent.com/105565670/183273523-2e3261b9-38cb-41d5-8acb-50e3aefebb17.png)

La reactancia capacitiva (XC) tiene el efecto opuesto: provoca que la corriente se adelante con respecto al voltaje. Por tanto, XL y XC tienden a contrarrestarse entre sí, su fórmula es:

![image](https://user-images.githubusercontent.com/105565670/183273530-6283e09e-c9d4-4ddd-bd39-b82d6b7cad9e.png)

La impedancia total del circuito RLC, se presenta con la siguiente fórmula:

![image](https://user-images.githubusercontent.com/105565670/183273533-25292812-2f25-4bed-b120-f643ac562da3.png)

En un circuito RLC en serie, la resonancia en serie ocurre cuando XC = XL. La frecuencia a la cual tiene lugar la resonancia se llama frecuencia resonante y se designa mediante fr.

Para un circuito RLC en serie dado, la resonancia ocurre a sólo una frecuencia específica, su fórmula es:

![image](https://user-images.githubusercontent.com/105565670/183273548-3ebad219-a179-4a06-bb54-7ae2eed51894.png)

La magnitud de la impedancia es mínima en resonancia (Z = R) y su valor aumenta por encima y por debajo del punto resonante.

Circuito RLC en paralelo

La impedancia total se calcula utilizando el método del recíproco de la suma de recíprocos, exactamente como se hizo para circuitos con resistores en paralelo

![image](https://user-images.githubusercontent.com/105565670/183273550-b75b8ce8-09d5-4151-9b88-2d6b723f184a.png)

Un circuito RLC en paralelo es:

![image](https://user-images.githubusercontent.com/105565670/183273555-bc115e11-8376-458b-90c6-a2492fd39df8.png)

Las fórmulas fasoriales se vuelven a establecer aquí, siendo:

![image](https://user-images.githubusercontent.com/105565670/183273558-dcb8b5b8-a2fb-4d1a-87c9-a57b2d5f5bfe.png)

A medida que la frecuencia aumenta un poco más, XC se vuelve más pequeña que XL, y el circuito se vuelve capacitivo.

Efecto de la resistencia de devanado en la frecuencia resonante en paralelo

 Cuando se considera la resistencia de devanado, la condición resonante se expresa como:
 
 ![image](https://user-images.githubusercontent.com/105565670/183273563-a05f7a76-75c9-4082-987e-b44320c8be1b.png)

Una expresión precisa para fr en función de los valores de componente de circuito es:

![image](https://user-images.githubusercontent.com/105565670/183273565-cf4b8f5a-0723-4fbc-b14d-05cadffc094c.png)

Las fórmulas siguientes proporcionan la inductancia equivalente, Leq, y la resistencia en paralelo equivalente, Rp(eq):

![image](https://user-images.githubusercontent.com/105565670/183273570-46544c6f-501c-4094-a97b-b081a42aa29f.png)

La equivalencia de los circuitos significa que, a una frecuencia dada, cuando se aplica el mismo valor de voltaje a ambos circuitos, la misma corriente total fluye en ambos circuitos y los ángulos de fase son los mismos.

En un circuito RLC dispuesto en serie, la corriente es máxima a la frecuencia resonante (también conocida como frecuencia central) y se reduce a uno y otro lado de esta frecuencia. El ancho de banda, abreviado en ocasiones AB, es una característica importante de un circuito resonante.

En un circuito resonante en paralelo, la impedancia es máxima a la frecuencia resonante; de modo que la corriente total es mínima. El ancho de banda se define en relación con la curva de impedancia del mismo modo en que la curva de corriente fue utilizada en el circuito en serie.

El ancho de banda para circuitos resonantes en serie o en paralelo es el intervalo de frecuencias localizado entre las frecuencias críticas, su fórmula es:

![image](https://user-images.githubusercontent.com/105565670/183273576-c844339a-e629-4e3c-9a74-2e97d027956d.png)

La frecuencia central es:

![image](https://user-images.githubusercontent.com/105565670/183273578-8ffe1bc5-018d-4a10-81d8-0858cf899391.png)

La selectividad define qué tan bien responde un circuito resonante a cierta frecuencia y discrimina todas las demás frecuencias. Mientras más angosto es el ancho de banda, más grande es la selectividad.

FILTROS PASIVOS

Filtros pasabajas

Un filtro pasabajas deja pasar señales de bajas frecuencias desde la entrada hasta la salida mientras rechaza las frecuencias altas.

La frecuencia crítica (fc) es la frecuencia a la cual el voltaje de salida del filtro es un 70.7% del voltaje máximo

![image](https://user-images.githubusercontent.com/105565670/183273580-efbaf66e-eca7-49c9-b2ba-8f4d33610205.png)

El decibel es una medida logarítmica de la relación de una potencia a otra y de un voltaje a otro, la cual puede ser utilizada para expresar la relación de entrada a salida de un filtro, su fórmula es:

![image](https://user-images.githubusercontent.com/105565670/183273584-31b35e07-99f3-4d96-ab0f-ffcb3618920d.png)

En una relación de voltaje, su fórmula es:

![image](https://user-images.githubusercontent.com/105565670/183273587-5615b426-b379-4e53-a715-5d6f99ffd904.png)

![image](https://user-images.githubusercontent.com/105565670/183273594-92d7a42e-f875-470f-bd7e-d422f472716c.png)

Filtros pasaaltas

Un filtro pasaaltas deja pasar señales de alta frecuencia desde la entrada hasta la salida en tanto que rechaza las señales de baja frecuencia

![image](https://user-images.githubusercontent.com/105565670/183273598-df9d519e-8db3-4f9d-9ab2-4db37d5023ed.png)

La expresión para la frecuencia crítica del filtro pasaaltas es la misma que para el filtro pasabajas, siendo:

![image](https://user-images.githubusercontent.com/105565670/183273602-253b94a7-dedd-4100-a036-d9aff2c8863c.png)

La expresión para la frecuencia crítica de un filtro pasaaltas es la misma que para el filtro pasabajas, siendo:

![image](https://user-images.githubusercontent.com/105565670/183273603-a7d5bfdb-edf1-4076-be0e-ff1b7f5cafd3.png)

Filtros pasabanda

Un filtro pasabanda deja pasar cierta banda de frecuencias y atenúa o rechaza todas las frecuencias por debajo y por encima de la banda de paso.

El ancho de banda de un filtro pasabanda es el intervalo de frecuencias dentro del cual la corriente, y por tanto el voltaje de salida, es igual o mayor que el 70.7% de su valor en la frecuencia de resonancia.

Se calcula como:

![image](https://user-images.githubusercontent.com/105565670/183273612-7d483a28-3826-4267-9293-899f85f29f5c.png)

Se puede utilizar la combinación de un filtro pasabajas y un filtro pasaaltas para formar un filtro pasabanda, siendo:

![image](https://user-images.githubusercontent.com/105565670/183273614-291cddb7-4b50-4e32-9222-eb2fcb5205bd.png)

Filtros rechazabanda

Un filtro rechazabanda es, en esencia, lo opuesto de un filtro pasabanda en función de las respuestas. Un filtro rechazabanda deja pasar todas las frecuencias excepto aquellas que quedan dentro de cierta banda de rechazo.

Se puede formar un filtro rechazabanda con un filtro pasabajas y un filtro pasaaltas, siendo:

![image](https://user-images.githubusercontent.com/105565670/183273620-783bd28f-62c7-46ce-aac9-b6bbcccff896.png)

3. Resolución de ejercicios

Capítulo 17

2. Determine la impedancia en la figura 17-59 y exprésela en forma polar.

![image](https://user-images.githubusercontent.com/105565670/183273634-b1a37b23-2abe-463a-8354-6f0b7ee4e405.png)

4. Para el circuito de la figura 17-59, determine la reactancia neta que hará que la magnitud de la impedancia sea igual a 100 Ω.

![image](https://user-images.githubusercontent.com/105565670/183273639-b35743b0-984c-4871-bd40-e75c99992f9f.png)

6. Trace el diagrama fasorial de voltaje para el circuito de la figura 17-59

![image](https://user-images.githubusercontent.com/105565670/183273653-47001c98-8bfd-4108-a0e9-89739462c31a.png)

8. Para el circuito de la figura 17-59, ¿es la frecuencia resonante más alta o más baja que el valor indicado por los valores de reactancia?

![image](https://user-images.githubusercontent.com/105565670/183273660-4f8bd48d-807a-438a-a1be-c3ec72acd7b1.png)

10. En la figura 17-61, determine XL, XC, Z e I a la frecuencia resonante

![image](https://user-images.githubusercontent.com/105565670/183273667-904d6ee4-3e83-44cf-b248-0397d78da757.png)

12. Para el circuito RLC de la figura 17-62, determine la frecuencia resonante

![image](https://user-images.githubusercontent.com/105565670/183273670-cee3da8b-6903-4b10-a55c-315917d94ab2.png)

14. En la figura 17-62, determine el ángulo de fase entre el voltaje aplicado y la corriente a las frecuencias críticas. ¿Cuál es el ángulo de fase en condición de resonancia?

![image](https://user-images.githubusercontent.com/105565670/183273671-033afad2-358d-4f55-b832-8176c0b27c59.png)

16. Exprese en forma polar la impedancia del circuito de la figura 17-63

![image](https://user-images.githubusercontent.com/105565670/183273674-9a46caba-fa56-41f2-bcfc-30cf0c715b9a.png)

18. ¿A qué frecuencia el circuito de la figura 17-63 cambia su característica reactiva (de inductiva a capacitiva o viceversa)?

![image](https://user-images.githubusercontent.com/105565670/183273684-2ccbb63d-016b-4c6e-a6a5-87dee503afbc.png)

20. Determine la impedancia total del circuito de la figura 17-63 a 50 kHz

![image](https://user-images.githubusercontent.com/105565670/183273689-e5a8cd1f-2a25-45a9-a5bb-937c0cc09279.png)

22. ¿Cuál es la impedancia de un circuito resonante ideal dispuesto en paralelo (sin resistencia en las ramas)?

![image](https://user-images.githubusercontent.com/105565670/183273699-3204466c-322d-4945-abc8-39413bddb7b7.png)

24. ¿Cuánta corriente se extrae de la fuente de la figura 17-64 en condición de resonancia? ¿Cuáles son las corrientes inductiva y capacitiva en la frecuencia resonante?

![image](https://user-images.githubusercontent.com/105565670/183273706-1a5cf166-ee64-487a-8e48-5d3ff6165f5c.png)

26. Encuentre la impedancia total para cada circuito de la figura 17-65

![image](https://user-images.githubusercontent.com/105565670/183273722-c3d0b2f7-c49d-4519-aeb8-823546bf29c1.png)

28. Determine el voltaje entre las terminales de cada elemento mostrado en la figura 17-66, y expréselo en forma polar

![image](https://user-images.githubusercontent.com/105565670/183273736-90277a8a-e810-488d-8fe0-f1bbf65598b0.png)

![image](https://user-images.githubusercontent.com/105565670/183273737-44b55c89-8f3a-4210-8d1b-fc152e38f6b7.png)

30. ¿Cuál es la corriente a través de R2 en la figura 17-67?

![image](https://user-images.githubusercontent.com/105565670/183273744-b326e7bb-f961-453b-8e23-d7473b6b0b20.png)

32. Determine la resistencia y la reactancia totales en la figura 17-68

![image](https://user-images.githubusercontent.com/105565670/183273766-8bc939a4-4b43-4b9a-abc4-6001caaf9fc7.png)

34. Determine si existe un valor de C que hará Vab = 0 V en la figura 17-69. Si no lo hay, explique la razón

![image](https://user-images.githubusercontent.com/105565670/183273799-8e72297e-147a-4898-8158-f652742cad2e.png)

36. ¿Cuántas frecuencias resonantes hay en el circuito de la figura 17-70 ¿Por qué?

![image](https://user-images.githubusercontent.com/105565670/183273806-e50fa3ae-1ec1-443d-918c-9742f589100a.png)

38. Diseñe una red resonante en paralelo usando una sola bobina y capacitores seleccionables mediante un interruptor para producir las siguientes frecuencias resonantes: 8 MHz, 9 MHz, 10 MHz, y 11 MHz. Suponga una bobina de 10 uH con resistencia de devanado de 5 Ω

![image](https://user-images.githubusercontent.com/105565670/183273813-82da0155-9e4c-4537-acd6-1349acd7176e.png)

40. Si la frecuencia crítica baja es de 2400 Hz y la frecuencia crítica alta es de 2800 Hz, ¿cuál es el ancho de banda? ¿Cuál es la frecuencia resonante?

![image](https://user-images.githubusercontent.com/105565670/183273816-f134bbfc-6a96-4c55-84c4-9ff2d107aaf3.png)

42. En un circuito tanque, ¿qué valores de L y C deberán utilizarse para obtener una frecuencia resonante de 8 kHz? El ancho de banda debe ser de 800 Hz. La resistencia de devanado del circuito es de 10 Ω

![image](https://user-images.githubusercontent.com/105565670/183273821-46b5c9b4-419a-4c5c-8cbe-6e01e345f7d7.png)

Capítulo 18

2. Un filtro pasabajas tiene frecuencia crítica de 3 kHz. Determine a cuáles de las siguientes frecuencias se les permite pasar y cuáles son rechazadas:

![image](https://user-images.githubusercontent.com/105565670/183273837-cc8c370b-f0db-429a-8ff1-2ea760fdc026.png)

4. ¿Cuál es fc para cada filtro mostrado en la figura 18-38? Determine el voltaje de salida a fc en cada caso cuando Vent = 5 V































