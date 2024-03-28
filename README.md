# Learning-Thread

O objetivo deste trabalho é desenvolver um programa que utilize a programação paralela
para a verificação de números primos em um arquivo.
O programa deve ler um arquivo de entrada e realizar o processamento identificando os
números primos. O resultado, uma lista de números primos, devem ser gravados em um
arquivo de saída, na mesma ordem do arquivo original
Para fins de análise, deverão ser desenvolvidas três implementações distintas:
1) Implementação usando o modelo de programação sequencial (uma thread)
2) Implementação de um modelo de programação paralela usando 5 threads
3) Implementação de um modelo de programação paralela usando 10 threads

## Equipe
- Gabriel Claudino
- Gabriel Dunkel
- Giulia Franca

## Resultados
A tabela abaixo apresenta os tempos de execução associados a cada número de thread. 
Evidencia-se uma tendência clara: à medida que o número de threads aumenta, o tempo de execução diminui.
| Num Threads | Tempo (ms) |
| ----------- | --------- |
| 1           |    398  |
| 5           |   94  |
| 10          | 82    |

No gráfico abaixo, é possível visualizar o padrão mencionado anteriormente.

<div align="lefth">
<img src="https://github.com/gabrielsdunkel/Learning-Threads/assets/90232353/ab8d33a3-c68a-4c22-883e-114f79261837" width = "400px"/>
</div>
