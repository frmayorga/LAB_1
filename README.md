# LAB_1

# OBJETIVOS

## OBJETIVO GENERAL 
 
Explicar y demostrar experimentalmente la Ley de Kirchhoff de Voltajes y la Ley de Kirchhoff de Corrientes, a través del uso del conocimiento teórico y simuladores virtuales. Además sustentando la investigación con el uso de tablas y materiales bibliográficos.

## OBJETIVO ESPECIFICO


# MARCO TEORICO

![lab1 1](https://user-images.githubusercontent.com/93561706/141365791-99e5f16a-eec6-4482-a5da-2cec4cf9452d.jpg)

![lab1 22](https://user-images.githubusercontent.com/93561706/141365810-79bdb7fc-da8f-4f0d-abf2-27da61c10277.jpg)

![lab1 3](https://user-images.githubusercontent.com/93561706/141369551-a6dd8746-624c-4750-a00e-e513e7d6b6eb.jpg)

**CODIGO DE COLORES PARA RESISTORES DE 4 BANDAS** 

| DIGITO | COLOR |
|--------|------------|
| 0 | Negro |
| 1 | Café |
| 2 | Rojo |
| 3 | Naranja |
| 4 | Amarillo |
| 5 | Verde |
| 6 | Azul |
| 7 | Violeta |
| 8 | Gris |
| 9 | Blanco |

TOLERANCIA : Oro +- 5%; Plata +- 10%.

![image](https://user-images.githubusercontent.com/93361435/141390249-a1bc9655-3102-4c92-97af-515aacc43518.png)

**RELACION LINEAL CORRIENTE - VOLTAJE**

Con un valor constante de R, si el valor de V se incrementa, el valor de I se incrementa; si V disminuye, I disminuye. Si V se mantiene constante y R se incrementa, I disminuye. Asimismo, si V se mantiene constante y R disminuye, I se incrementa.

En la siguiente imagen podemos observar la relación lineal entre corriente y voltaje con una resistencia constante: 

![image](https://user-images.githubusercontent.com/93361435/141390367-4ed4d2d6-c8b0-4317-8499-c4ceecd5975a.png)

**RELACION INVERSA CORRIENTE - RESISTENCIA**

Y en la siguiente imagen la relación inversa de corriente y resistencia con un voltaje constante: 

![image](https://user-images.githubusercontent.com/93361435/141390563-0c3d1077-a8f6-459d-bd22-20c62d5e3b33.png)

# PROCEDIMIENTO

Se utilizo los siguientes materiales 

| CANTIDAD | MATERIAL O EQUIPO |
|----------|-------------------------|
| 1 | Fuente de voltaje de C.D. |
| 2 | Multímetros Digitales |
| 1 | Resistor de 1 kΩ |
| 2 | Resistores de 2.2 kΩ |
| 1 | Resistor de 1.8 kΩ |
| 1 | Resistor de 3.9 kΩ |
| 1 | Protoboard |

Por consiguiente se armo el siguiente circuito en el simulador virtual TINKERCAD: 

![image](https://user-images.githubusercontent.com/93361435/141212814-970f588c-f726-407f-a879-8d9a3a8c4add.png)

## PROCEDIMIENTO TABLA 1: 

Usamos resistores equivalentes para poder calcular la corriente y voltaje de los resistores.
En el primer resistor es posible calcular la intensidad mediante la ley de ohm y el voltaje mediante la ley de ohm o la relación entre voltaje y resistores

![image](https://user-images.githubusercontent.com/93361435/141399359-91b8de7a-7151-404b-9e73-29db4fc333b7.png)

En el segundo resistor se usó una resistencia equivalente para encontrar el valor del voltaje , la intensidad es la misma ya que se encuentra en serie con los demás resistores 

En el tercer resistor se utilizo el valor total de R´´ como están conectadas en serie R´´ tiene el mismo valor que R´ para R3 como esta conectada en serie tiene la mitad de R´ ya que como podemos observar R´ = 2R_3, para la intensidad en R3 se utilizo el valor de volatje de R´ ya que en paralelo tienen el mismo voltaje y calculamos con la ley de ohm 

![image](https://user-images.githubusercontent.com/93361435/141398063-ee158f51-6345-4d1d-b6d8-24b777af52ec.png)

En el cuarto resistor como esta conectado en serie con R_3 la intensidad es la misma y el voltaje lo calculamos como R´ = 2V_2
En el quinto resistor podemos calcularlo con la ley de ohm ya que se encuentra en serie la corriente seria la misma que la inicial y el voltaje lo calculamos con la ley de ohm 

![image](https://user-images.githubusercontent.com/93361435/141398087-ae606651-67c9-40ae-b313-5e37b4d47863.png)

![image](https://user-images.githubusercontent.com/93361435/141398100-336ad601-7155-4294-88ef-894ff143108e.png)

Ahora calculamos el error:

En la intensidad de R_3 y R_4

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{I_{R3}}=\frac{|Valor&space;C&space;-&space;Valor&space;M|}{ValorC}&space;\times&space;&space;100&space;=&space;\frac{|963-965|}{963}&space;\times&space;100=&space;0.21%" title="\bg_black \inline e_{I_{R3}}=\frac{|Valor C - Valor M|}{ValorC} \times 100 = \frac{|963-965|}{963} \times 100= 0.21%" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{I_{R4}}=\frac{|Valor&space;C&space;-&space;Valor&space;M}{ValorC}&space;\times&space;&space;100&space;=&space;\frac{|963-965|}{963}&space;\times&space;100=&space;0.21%" title="\bg_black \inline e_{I_{R4}}=\frac{|Valor C - Valor M}{ValorC} \times 100 = \frac{|963-965|}{963} \times 100= 0.21%" />

Y el voltaje en R2, R3 Y R4, R5

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{R2}&space;=&space;\frac{|Vc-Vm|}{Vc}=&space;\frac{|4.24-4.25|}{4.24}&space;=&space;0.24&space;%" title="\bg_black \inline e_{R2} = \frac{|Vc-Vm|}{Vc}= \frac{|4.24-4.25|}{4.24} = 0.24 %" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{R3}&space;=&space;\frac{|Vc-Vm|}{Vc}=&space;\frac{|2.118&space;-&space;2.12|}{2.118}&space;=&space;0.094&space;%" title="\bg_black \inline e_{R3} = \frac{|Vc-Vm|}{Vc}= \frac{|2.118 - 2.12|}{2.118} = 0.094 %" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{R5}&space;=&space;\frac{|Vc-Vm|}{Vc}=&space;\frac{|3.69&space;-&space;3.70|}{3.69}&space;=&space;0.27&space;%" title="\bg_black \inline e_{R5} = \frac{|Vc-Vm|}{Vc}= \frac{|3.69 - 3.70|}{3.69} = 0.27 %" />

## PROCEDIMIENTO TABLA 2:

Se debe partir del circuito anterior para poder resolver lo que nos pide el enunciado:

![image](https://user-images.githubusercontent.com/93561706/141404339-3f4f0e48-0ce1-4865-8fc9-a7b2e5cfbb2b.png)

Para facilitarnos los calculos, vamos a dividirlos por trayectorias, a cada trayectoria vamos a calcular los voltajes de las resistencias correspondientes: 

* Trayectoria 1:

![image](https://user-images.githubusercontent.com/93561706/141406371-e9b4e676-1458-4a8e-a0eb-3fcf540a10f9.png)

* Trayectoria 2:

![image](https://user-images.githubusercontent.com/93561706/141407750-81093a2d-1d2f-45c7-9d9a-3987da7afbd6.png)

* Trayectoria 3:

![image](https://user-images.githubusercontent.com/93561706/141407816-4350e99c-3667-4c48-91aa-b90ab394cb51.png)

Una vez que ya determinamos nuestra trayectorias, pasamos a los calculos y tambien comprobaremos que los calculos esten bien con la ayuda del simulador.
Iniciamos calculando la reciestencia total de cada trayectoria, para asi poder utilizar la formula de la division de volteja, esta formula nos ayuda a determinar el valor del voltaje en nuestra resistencia, pero tambien hay que tener en cuenta que estos valores de los voltejes de las resistencias van ha ser negativos ya que estos biene hacer las caidas del voltaje, asi que usaremos este principio de la teoria.

![image](https://user-images.githubusercontent.com/93561706/141408898-098aa3d7-490e-486d-a99f-47ac9c364596.png)

Luego para verificar que los resultados esten bien usaremos el princio de la Ley del voltaje de Kirchhoff la cual nos dice que la suma de los voltajes de las resistencias es igual al voltaje inicial del circuito o en otras palabras que el voltaje inicial menos la suma de los voltajes de las resistencias es igual a cero.  

![image](https://user-images.githubusercontent.com/93561706/141409120-1bff19e0-be11-4c82-bd9b-77fa372db194.png)

Para concluir colocamos los resultados en la tabla y pasamos a vericas con el simular que esten bien.


## procedimiento tabla  3 
- por la teoria recibida en clases se sabe que para que se cumpla la ley de las corrientes es necesario que ∑I = 0 de esta manera los calculos que demuestran la valides de los resultados obtenidos en la tabla son los siguientes:  
-![image](https://user-images.githubusercontent.com/93398718/141456106-ee3f9aa5-b336-4cf4-9ec3-c35c9d0f11a2.png)

#### nodo 1:  
![image](https://user-images.githubusercontent.com/93398718/141457787-09aad061-4406-4762-8d06-705a8b9a5c77.png)

#### nodo 2:   
![image](https://user-images.githubusercontent.com/93398718/141458515-eb3e1218-5bc7-439d-934c-758bc7ccb0e2.png)

#### nodo 3:
![image](https://user-images.githubusercontent.com/93398718/141459061-6e13eda8-a83e-48c9-ad80-b8b08d82b91f.png)

#### nodo 4:  
![image](https://user-images.githubusercontent.com/93398718/141459474-079aa900-8839-4e9e-962d-c57669aec664.png)

#### nodo 5:  
![image](https://user-images.githubusercontent.com/93398718/141459724-d142f356-9284-4041-925a-a0e256119f98.png)

- en el nodo 4 se hace uso del valor calculado y el valor medido porque fue el unico punto en el cual los resultados fueron diferentes.
- a continuacion se presentan los valores medidos en el programa tinkercad:  
![image](https://user-images.githubusercontent.com/93398718/141460409-daf75c6a-1c3a-4355-be56-1b4d85b959de.png)



# RESPUESTA DE INTERROGANTES

### TABLA 1

Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1.

| Variable | Valor Calculado | Valor Medido | Error |
|------------- | -------------------- | ------------------ | --------------- |
| V_R1 | 2.05 V | 2.05 V | 0 % |
| I_R1 | 2.05 mA | 2.05 mA | 0 % |
| V_R2 | 4.24 V | 4.25 V | 0.24 % |
| I_R2 | 1.087 mA | 1.09 mA | 0.27 % |
| V_R3 | 2.118 V | 2.12 V | 0 % |
| I_R3 | 963 uA | 965 uA | 0.21 % |
| V_R4 | 2.118 V | 2.12 V | 0.094 % |
| I_R4 | 963 uA | 965 uA | 0.21 % |
| V_R5 | 3.69 V | 3.7 V | 0.27 % |
| I_R5 | 2.05 mA | 2.05 mA | 0 % | 

**CALCULO DE ERROR**

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{R2}&space;=&space;\frac{|Vc-Vm|}{Vc}=&space;\frac{|4.24-4.25|}{4.24}&space;=&space;0.24&space;%" title="\bg_black \inline e_{R2} = \frac{|Vc-Vm|}{Vc}= \frac{|4.24-4.25|}{4.24} = 0.24 %" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{I_{R3}}=\frac{|Valor&space;C&space;-&space;Valor&space;M|}{ValorC}&space;\times&space;&space;100&space;=&space;\frac{|963-965|}{963}&space;\times&space;100=&space;0.21%" title="\bg_black \inline e_{I_{R3}}=\frac{|Valor C - Valor M|}{ValorC} \times 100 = \frac{|963-965|}{963} \times 100= 0.21%" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{R3}&space;=&space;\frac{|Vc-Vm|}{Vc}=&space;\frac{|2.118&space;-&space;2.12|}{2.118}&space;=&space;0.094&space;%" title="\bg_black \inline e_{R3} = \frac{|Vc-Vm|}{Vc}= \frac{|2.118 - 2.12|}{2.118} = 0.094 %" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{I_{R4}}=\frac{|Valor&space;C&space;-&space;Valor&space;M}{ValorC}&space;\times&space;&space;100&space;=&space;\frac{|963-965|}{963}&space;\times&space;100=&space;0.21%" title="\bg_black \inline e_{I_{R4}}=\frac{|Valor C - Valor M}{ValorC} \times 100 = \frac{|963-965|}{963} \times 100= 0.21%" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{R5}&space;=&space;\frac{|Vc-Vm|}{Vc}=&space;\frac{|3.69&space;-&space;3.70|}{3.69}&space;=&space;0.27&space;%" title="\bg_black \inline e_{R5} = \frac{|Vc-Vm|}{Vc}= \frac{|3.69 - 3.70|}{3.69} = 0.27 %" />

### TABLA 2

![image](https://user-images.githubusercontent.com/93561706/141405640-ddb56582-e391-4833-890d-d5e373381e88.png)

![image](https://user-images.githubusercontent.com/93561706/141405787-bea7f391-1784-4d0f-b7a0-7170f47645dd.png)

![image](https://user-images.githubusercontent.com/93561706/141405808-653bd5ac-14e5-49fb-812a-86568b834650.png)

![image](https://user-images.githubusercontent.com/93561706/141405874-1f5fbfa4-cf86-4baf-b117-27684157de90.png)

![image](https://user-images.githubusercontent.com/93561706/141405900-03db7ad1-f9e2-4b8e-bbec-2e29e9365ac4.png)

![image](https://user-images.githubusercontent.com/93561706/141405974-531e1b67-dc59-4eca-94a1-906490ff45aa.png)

![image](https://user-images.githubusercontent.com/93561706/141405993-8530b9d8-1998-4bfc-9b6e-7716f240531a.png)

### TABLA 3

![image](https://user-images.githubusercontent.com/93398718/141452992-e35cd211-8533-475b-b554-106c715d2626.png)   

- Como se puede apreciar en el nodo dos y el nodo cuatro obtenemos valores que no son iguales a cero, sin embargo , si son proximos a cero esto sucede debido a los diferentes errores de calculo que pueden suceder he inclusive a la confiabilidad del aparato de medicion.

# VIDEO

# CONCLUSIONES

# BIBLIOGRAFIA

- Floyd, T. (2007). *Principios de circuitos eléctricos*. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) *Analisis de circuitos Teoria y Practica*. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
- Torres, H. (24 de Enero de 2018) *La Ley de Ohm*. [archivo PDF]. https://hetpro-store.com/PDFs/La-Ley-de-Ohm.pdf 
- Salazar, A. (s.f.) *LEYES DE VOLTAJES Y CORRIENTES DE KIRCHHOFF*. [archivo PDF] http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/02_Leyes_de_Voltajes_y_Corrientes_de_Kirchhoffs.pdf 


