# Projeto Fonte Tensão Ajustável
  O objetivo do projeto era fazer uma fonte de tensão ajustável de 3V a 12V que fornecesse pelo menos 100mA de corrente na saída.
  A fonte recebe uma tensão de 127V ou 220V RMS da tomada e converte em uma tensão constante que pode ser usada nos dispositivos.
  
  A fonte funciona basicamente em 4 etapas: 
  1. Diminuir a tensão a partir de um transformador;
  2. Retificar a tensão a partir de uma ponte de diodos, pois a tensão que chega da tomada é alternada;
  3. Fazer com que a variação de tensão seja a menor possível com o uso de um capacitor;
  4. "Cortar" a tensão em um ponto em que não haja oscilação, tornando a tensão constante (essa etapa é feito com o uso de um diodo zener);
  

## Componentes usados

|Componente|Especificação|
|----------|-------------|
|Transformador|15V|
|Ponte retificadora|2W10|
|Capacitor|470uF|
|Resistor|820 Ohms|
|Potenciometro|10K|
|Diodo Zener|13V|
|Transistor|NPN|

## Circuito no falstad

![alt text](https://github.com/g-faccini/ProjetoFonte/blob/main/CircuitoFalstad.PNG "Circuito falstad")

[Clique aqui para acessar o circuito no falstad](https://tinyurl.com/2zzzodnc)


## Esquematico e PCB no Eagle

### -Esquematico

### -PCB
