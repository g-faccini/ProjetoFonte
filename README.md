# Projeto Fonte Tensão Ajustável
  O objetivo do projeto era fazer uma fonte de tensão ajustável de 3V a 12V que fornecesse pelo menos 100mA de corrente na saída.
  A fonte recebe uma tensão de 127V RMS da tomada e converte em uma tensão constante que pode ser utilizada nos dispositivos.
  
  A fonte funciona basicamente em 4 etapas: 
  1. Usar um transformados para diminuir a tensão da tomada de 127V RMS para uma tensão menor (~25V-15V) para que possa ser usada pelo circuito;
  2. Usar uma ponte retificadora (ou ponte de diodos) para transformar a corrente alternada que sai do transformador em corrente contínua;
  3. Fazer com que a variação de tensão seja a menor possível com o uso de um capacitor;
  4. "Cortar" a tensão em um ponto em que não haja oscilação, tornando a tensão constante (essa etapa é feita com o uso de um diodo zener);
  

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

![](https://github.com/g-faccini/ProjetoFonte/blob/main/CircuitoFalstad.PNG "Circuito falstad")

[Clique aqui para acessar o circuito no falstad](https://tinyurl.com/2bvrmt42)


## Esquematico e Board no Eagle

### - Esquematico
![](https://github.com/g-faccini/ProjetoFonte/blob/main/Esquematico.PNG "Esquemático no Eagle")

### - Board
![](https://github.com/g-faccini/ProjetoFonte/blob/main/PCB.PNG "Esquemático no Eagle")

## Fotos do Projeto final
### 1.Fonte na tensão máxima (perto de 12V)
![](https://github.com/g-faccini/ProjetoFonte/blob/main/Tmax.jpeg)


### 2.Fonte na tensão mínima (perto de 3V)
![](https://github.com/g-faccini/ProjetoFonte/blob/main/Tmin.jpeg)

## Alunos

1. Gustavo Hitomi da Silva
2. Gustavo Poffo
3. Gabriel Faccini


