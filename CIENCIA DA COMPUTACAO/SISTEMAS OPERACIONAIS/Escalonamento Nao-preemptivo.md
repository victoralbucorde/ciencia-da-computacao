O escalonamento não-preemptivo é um tipo de [[Gerencia de processos e threads|gerência de processos]], que consiste em quando o processo ganhar o direito de utilizar a CPU, nenhum outro processo pode tirar esse recurso.

## First In First Out(FIFO)

O processo que chegar primeiro ao estado de pronto é o primeiro a ser escolhido a ocupar a CPU. Os processos são escolhidos por ordem de chegada e, quando um processo ganha o processador, ele executa até o fim sem trocar o contexto. Seu principal problema é a dificuldade de prever quando o processo terá sua execução iniciada.

## Shortest Job First(SJF)

Os processos são ordenados conforme seus tempos de execução do menor para o maior e, quando um processo ganha o processador ele executa até o fim sem trocar o contexto. Seu maior problema é determinar quanto de CPU cada processo necessita para seu processamento(baseado em estimativas).

## Corporativo 

Um processo em execução libera voluntariamente o processador, retornando à fila de pronto. Seu principal problema é que se ele não liberar o processador o processador é monopolizado pelo programa.

==Obs: Escalonamento FIFO e SJF não podem ser aplicados em sistemas de tempo compartilhado, no qual um tempo de resposta razoável deve ser garantido para usuários interativos.== 