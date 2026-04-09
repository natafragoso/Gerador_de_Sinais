O projeto desenvolvido visou gerar qualquer onda a partir de um PWM com valor médio variável.
No exemplo realizado o valor médio variou de forma senoidal, obtendo-se na saída uma onda próxima de uma senoide.
A fim de torna a onda ainda mais parecida com um seno foi usado um filtro passa-baixas de primeira ordem,
com um resistor de 2k&Omega; e um capacitor de 100nF.
Além disso, a frequência inicial do seno foi definido em 10 Hz podendo ser alterada quantas vezes for desejado no terminal via UART.
