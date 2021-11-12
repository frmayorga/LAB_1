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

**CALCULOS AUXILIARES**

VOLTAJE EN R2

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;V_{R_2}&space;=&space;\left&space;(&space;\frac{Vs}{RT}&space;\right&space;)R_2&space;=&space;\left&space;(&space;\frac{10&space;V}{4.87&space;k\Omega&space;}&space;\right&space;)2.067k\Omega&space;=&space;4.24&space;V" title="\bg_black \inline V_{R_2} = \left ( \frac{Vs}{RT} \right )R_2 = \left ( \frac{10 V}{4.87 k\Omega } \right )2.067k\Omega = 4.24 V" />

VOLTAJE EN R5

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;V_{R_5}&space;=&space;\left&space;(&space;\frac{Vs}{RT}&space;\right&space;)R_5&space;=&space;\left&space;(&space;\frac{10&space;V}{4.87&space;k\Omega&space;}&space;\right&space;)1.8k\Omega&space;=&space;3.70&space;V" title="\bg_black \inline V_{R_5} = \left ( \frac{Vs}{RT} \right )R_5 = \left ( \frac{10 V}{4.87 k\Omega } \right )1.8k\Omega = 3.70 V" />

# RESPUESTA DE INTERROGANTES

### TABLA 1

Mida el voltaje y corriente en cada uno de los elementos del circuito. Anote los resultados de las mediciones en la tabla 1.1.

| Variable | Valor Calculado | Valor Medido |
|------------- | -------------------- | ------------------ |
| V_R1 | 2.05 V | 2.05 V |
| I_R1 | 2.05 mA | 2.05 mA |
| V_R2 | 4.25 V | 4.25 V |
| I_R2 | 2.05 mA | 2.05 mA |
| V_R3 | 2.11 V | 2.12 V |
| I_R3 | 963 uA | 965 uA |
| V_R4 | 2.11 V | 2.12 V |
| I_R4 | 963 uA | 965 uA |
| V_R5 | 3.7 V | 3.7 V |
| I_R5 | 2.05 mA | 2.05 mA | 

**CALCULO DE ERROR**

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{I_{R3}}=\frac{|Valor&space;C&space;-&space;Valor&space;M|}{ValorC}&space;\times&space;&space;100&space;=&space;\frac{|963-965|}{963}&space;\times&space;100=&space;0.21%" title="\bg_black \inline e_{I_{R3}}=\frac{|Valor C - Valor M|}{ValorC} \times 100 = \frac{|963-965|}{963} \times 100= 0.21%" />

<img src="https://latex.codecogs.com/png.image?\dpi{200}&space;\bg_black&space;\inline&space;e_{I_{R4}}=\frac{|Valor&space;C&space;-&space;Valor&space;M}{ValorC}&space;\times&space;&space;100&space;=&space;\frac{|963-965|}{963}&space;\times&space;100=&space;0.21%" title="\bg_black \inline e_{I_{R4}}=\frac{|Valor C - Valor M}{ValorC} \times 100 = \frac{|963-965|}{963} \times 100= 0.21%" />

# VIDEO

# CONCLUSIONES

# BIBLIOGRAFIA

- Floyd, T. (2007). *Principios de circuitos eléctricos*. Octava edición. Mexico. Editorial Pearson.
- Robbins, A., Miller, W. (2008) *Analisis de circuitos Teoria y Practica*. Cuarta Edicion. Mexico. Editorial CENGAGE Learning.
- Torres, H. (24 de Enero de 2018) *La Ley de Ohm*. [archivo PDF]. https://hetpro-store.com/PDFs/La-Ley-de-Ohm.pdf 
- Salazar, A. (s.f.) *LEYES DE VOLTAJES Y CORRIENTES DE KIRCHHOFF*. [archivo PDF] http://wwwprof.uniandes.edu.co/~ant-sala/cursos/FDC/Contenidos/02_Leyes_de_Voltajes_y_Corrientes_de_Kirchhoffs.pdf 


