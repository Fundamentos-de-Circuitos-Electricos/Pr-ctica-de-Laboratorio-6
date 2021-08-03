![caratula_page-0001 (1)](https://user-images.githubusercontent.com/85137398/127920652-28844a24-a12d-4244-bea5-533f2ad7fa5d.jpg)

# Práctica de Laboratorio 6

1. OBJETIVOS

*General*

- Aplicar el teorema de máxima transferencia de potencia en un circuito electrico para poder tranferir aquella potencia que sera igual al valor ohmico de la resistencia de la fuente presente en el circuito. 

*Especificos*

-	Identificar bien como es la aplicación del teorema de máxima transferencia de potencia en circuitos eléctricos.

-	Reforzar el teorema de Thevenin, el cual nos facilitara los cálculos de la máxima transferencia de potencia.

-	Analizar el circuito planteado de forma analítica con los cálculos algebraicos y de forma experimental como el simulador para hacer que se cumpla el teorema de máxima transferencia de potencia.

2. MARCO TEÓRICO 

![Diagrama en blanco (10)](https://user-images.githubusercontent.com/85137398/127933005-eb451215-1a2b-4032-b756-3a1d92aeeefe.png)

![Diagrama en blanco (11)](https://user-images.githubusercontent.com/85137398/127933017-dc883df5-ca9e-4b1e-a39e-08bb2beea2f0.png)

3. EXPLICACIÓN DEL PROCESO

- Material y equipo requerido

![image](https://user-images.githubusercontent.com/85137398/127920784-1f6d7561-bc74-48dd-8c59-f70397cc64d9.png)

- Descripcion de equipo y material

Protoboard: Un protoboard es una placa de pruebas en la que se pueden insertar componentes electrónicos y cables, donde se puede ensamblar un circuito sin la necesidad de soldar ningún componente. El protoboard tiene agujeros conectados entre sí, por medio de pequeñas láminas metálicas.

Resistores: Una resistencia o resistor al componente electrónico diseñado para introducir una resistencia eléctrica determinada entre dos puntos de un circuito eléctrico.

Fuente de voltaje: En electrónica, el elemento activo que puede transferir energía se llama fuente de voltaje.

Multímetro digital: Un multímetro digital es una herramienta que sirve para medir dos o más valores eléctricos, principalmente tensión (voltios), corriente (amperios) y resistencia (ohmios).

- Armado del circuito

I. Escoger la fuente de energia de 15v.

![image](https://user-images.githubusercontent.com/85137398/127922341-c70d65ca-850f-4cb6-a4b4-67edeaf820f0.png)

II. Escoger correctamente los resistores con su codificación de colores.

![image](https://user-images.githubusercontent.com/85137398/127924948-b497ccef-796d-4311-8b23-2c19930a0d83.png)

III. Conectar el circuito en base al diagrama de conexión.

- Diagrama esquemático

![image](https://user-images.githubusercontent.com/85137398/127924370-721421d0-9129-4e04-9261-26b18a5cfb9c.png)

- Conexión del circuito

![image](https://user-images.githubusercontent.com/85137398/127924317-d395133d-93da-40c9-84c6-5225ffc6b380.png)

4. RESPUESTAS A INTERROGANTES Y CÁLCULO DEL ERROR

* Mida el voltaje y la corriente para cada valor de RL que se indica en la tabla 6.1. Anote los resultados medidos.

* Calcule las potencia consumida por RL, para cada valor dado y anote los resultados en la tabla 6.1.

Cálculos

R = 220 Ω

I_T=  V_T/R_eq =  (15 V)/(1420 Ω)= 10.56 mA

P= I^2⋅R=(10.56⋅〖10〗^(-3) )^2 (220)=0.024 W

R = 470 Ω

I_T=  V_T/R_eq =  (15 V)/(1670 Ω)= 8.98 mA

P= I^2⋅R=(8.98⋅〖10〗^(-3) )^2 (470)=0.024 W

R = 680 Ω

I_T=  V_T/R_eq =  (15 V)/(1880 Ω)= 7.98 mA

P= I^2⋅R=(7.98⋅〖10〗^(-3) )^2 (680)=0.024 W

R = 820 Ω

I_T=  V_T/R_eq =  (15 V)/(2020 Ω)= 7.42 mA

P= I^2⋅R=(7.42⋅〖10〗^(-3) )^2 (820)=0.045 W

R = 1000 Ω

I_T=  V_T/R_eq =  (15 V)/(2200 Ω)= 6.81 mA

P= I^2⋅R=(6.81⋅〖10〗^(-3) )^2 (1000)=0.04637 W

R = 1500 Ω

I_T=  V_T/R_eq =  (15 V)/(2700 Ω)= 5.55 mA

P= I^2⋅R=(5.55⋅〖10〗^(-3) )^2 (1500)=0.04629 W


R = 1800 Ω

I_T=  V_T/R_eq =  (15 V)/(3000 Ω)= 5 mA

P= I^2⋅R=(5⋅〖10〗^(-3) )^2 (1800)=0.045 W

R = 2200 Ω

I_T=  V_T/R_eq =  (15 V)/(3400 Ω)= 4.41 mA

P= I^2⋅R=(4.41⋅〖10〗^(-3) )^2 (2200)=0.0428 W

R = 3900 Ω
I_T=  V_T/R_eq =  (15 V)/(5100 Ω)= 2.94 mA

P= I^2⋅R=(2.94⋅〖10〗^(-3) )^2 (3900)=0.033 W

R = 4700 Ω

I_T=  V_T/R_eq =  (15 V)/(5900 Ω)= 2.54 mA

P= I^2⋅R=(2.54⋅〖10〗^(-3) )^2 (4700)=0.030 W


* Tabla 6.1. Parámetros Eléctricos del circuito de la figura 6.1.

![image](https://user-images.githubusercontent.com/84390820/127960761-af179d45-aa67-4041-81e1-b27bc68f5d17.png)

* ¿Se cumple el Teorema de la Máxima Transferencia de Potencia? Argumente su respuesta.

El teorema de transferencia de potencia máxima se usa para encontrar la resistencia de carga para lo cual habría la máxima cantidad de transferencia de energía desde la fuente a la carga. Por lo que en el análisis se cumple el teorema en verificar la máxima transferencia de potencia comparando la tabla de datos del circuito.

* ¿Cuál fue la potencia máxima en RL? 
 
0.047 Watts

* ¿Para qué valor de RL se obtiene la MTP?

1000 Ω

5. VIDEO

https://youtu.be/co8Y1IdnwfA

6. CONCLUSIONES

* El teorea de transferencia de potencia máxima, se deriva del teorema de Thevenin y el de Norton y bases de cálculo elemental, ademas de que la potencia maxima se da cuando la carga toma de resistencia de igual a la resistencia de Thevenin o Norton.

* La máxima transferencia de potencia, la fuente y la resistencia de carga se combinan, y con esto, la eficiencia se convierte en 50% con el flujo de potencia máxima de la fuente a la carga.

7. BIBLIOGRAFÍA

- Electronica Lugo. (23 de 01 de 2021). TEOREMA MÁXIMO DE TRANSFERENCIA DE ENERGÍA. Obtenido de TEOREMA MÁXIMO DE TRANSFERENCIA DE ENERGÍA: https://electronicalugo.com/teorema-maximo-de-transferencia-de-energia/

- La fisica y quimica. (14 de 03 de 2019). Circuitos. Obtenido de Teorema de transferencia de potencia máxima: https://lafisicayquimica.com/teorema-de-transferencia-de-potencia-maxima/

- Wikipedia. (12 de 12 de 2020). Teorema de máxima potencia. Obtenido de Teorema de máxima potencia: https://es.wikipedia.org/wiki/Teorema_de_m%C3%A1xima_potencia



