# Calculadora-LogicaDigital
Project for Digital Logic Lab, 2023, ICMC-USP

(Placa Pequena) DE0-CV:
Cyclone V: 5CEBA4F23C7

O primeiro numero da operação é definido pelos botões sw0,sw1,sw2,sw3 e sw4.Seu sinal e sua magnitude são mostrados no display hex5 e hex4 respectivamente.
O segundo numero da operação é definido pelos botões sw5,sw6,sw7,sw8 e sw9.Seu sinal e sua magnitude são mostrados no display hex3 e hex2 respectivamente.
As operações dessa calculadora são:Soma,Subtração,Mutiplicação,Divisão,Radiciação e Comparação.
A operação default é a soma.
Para escolher subtração pressione key0.
Para escolher mutiplicação pressione key1.
Para escolher divisão pressione key2.
Para escolher radiciação pressione key3.
Para escolher comparação pressione key0 e key1 ao mesmo tempo.

*RADICIAÇÃO* 
Na radiciação o input de 8 bits é mostrado em hex5 e hex4.
O resto é mostrado em hex2 e hex3.
O resultado é mostrado em hex0 e hex1.

*COMPARAÇÃO*
Na comparação caso o Primeiro numero seja maior,o ledr8 acende.
Caso o segundo numero seja maior,o ledr7 acende.
Caso sejam iguais o ledr6 acende.

O resultado  da subtração,soma e mutiplicação serão exibidos no hex0 e hex1.O sinal do resultado será indicado em ledr0.
O resultado da divisão será exibido em hex0 e o resto em hex1.O sinal do resultado será indicado em ledr0 e o sinal do resto em ledr1.
