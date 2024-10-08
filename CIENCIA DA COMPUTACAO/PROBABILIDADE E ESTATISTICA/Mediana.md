A mediana além de ser uma [[Separatriz]] ela é também uma medida de posição(ou uma medida de tendência central). Ela caracteriza a posição central de uma série de valores, também separa uma série de valores ordenados em duas partes iguais.

## Cálculo de uma mediana para dados não agrupados

Se n for ímpar: 
```math
Md=(xn+1)/2
```
Se n for par:
```math
Md=(xn/2+xn/2+1)/2
```

==Obs1: A mediana nem sempre coincidirá com um elemento da série de dados. Isso somente ocorrerá se o numero de elementos da série for ímpar.==

==Obs2: A mediana depende somente da posição e não dos valores dos elementos de uma série ordenada.==

## Cálculo de uma mediana para dados agrupados em classes

Para calcular a mediana de dados que estão agrupados por intervalo de classes, precisamos identificar a classe em que se encontra a mediana, a chamada classe mediana, que corresponde à frequência acumulada imediatamente igual ou superior à metade da frequência total, ou seja, metade da soma das frequências simples:

$Md=l_inf+((\sum_{n}^i-f_ac_ant)/f_i)*h$ 

Onde:
- Md = mediana
- $L_inf$ = limite inferior da classe mediana
- $F_i$ = frequência simples da classe mediana
- $F_acant$ = frequência acumulada da classe anterior à mediana
- h = amplitude

## Características

Uma das características principais da mediana é:
- a invariância à unidade de medida utilizada
- a robustez à presença de outliers(valores que estão fora da faixa normal)
- a identificação da observação mais presente
- o fato de, em seu cálculo, dar mais peso às observações mais frequentes.
- a normalização pelos desvios em relação à média