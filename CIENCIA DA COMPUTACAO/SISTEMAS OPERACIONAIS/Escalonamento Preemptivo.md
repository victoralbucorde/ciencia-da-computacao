O escalonamento preemptivo é um tipo de [[Gerencia de processos e threads]], no qual diferente do [[Escalonamento Nao-preemptivo]] o sistema pode interromper um processo em execução para que outro, com maior prioridade, utilize o processador. Proporcionando melhores tempos de resposta em sistemas compartilhado e melhor compartilhamento mais uniforme entre processos.

## Circular(Round Robin)

O processo em execução tem tempo limite para a utilização da CPU(time-slice), terminando o tempo, o processo volta para estado de pronto. Este mecanismo é definido como preempção por tempo. Seu principal problema é que ele não faz o compartilhamento equitativo, pois este trata todos os processos de maneira igual.

## Por prioridades

O processo vai para fila de pronto com uma prioridade maior que o que está em execução, o sistema deve interromper o processo em execução, colocá-lo em estado de pronto e selecionar o com maior prioridade para ser processado

