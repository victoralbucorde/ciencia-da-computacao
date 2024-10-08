Uma das principais funções executadas pelo [[Sistemas operacionais]] é a de escalonar processos, que surgiu por causa dos sistemas dos sistemas multiprogramados no qual foi possível a CPU compartilhar diversos processos, uma política de escalonamento é usada em um [[Sistemas operacionais|sistema operacional]] para decidir quais processos ou threads devem executar num determinado instante

## Objetivos do escalonador

- Manter a CPU ocupada o maior tempo possível
- Balancear a utilização do processador entre os diversos processos
- Maximizar o throughput(rendimento) do sistema
- Oferecer um tempo de resposta razoável para os usuários interativos
- Maximizar a utilização de recursos(Hardware e Software)
- Minimizar a sobrecarga de gerenciamento do SO
- Garantir uma previsibilidade no atendimento
- Favorecer as rotinas de maior prioridade
- Evitar postergação indefinida de um processo

## Critérios de escalonamento

- **Utilização de CPU:** É desejável que o processador fique a maior parte do tempo ocupado
- **Rendimento:** O rendimento representa o numero de processos executados em um intervalo de tempo. Maximizar o rendimento é desejado na maioria dos sistemas.
- **Tempo de Turnaround:** Tempo que um processo leva desde sua admissão no sistema até seu término, levando em consideração o tempo de alocação na memória, espera na fila de processos prontos para execução, processamento de CPU e operações de entrada e saída.
- **Tempo de resposta:** Em sistemas interativos, o tempo de resposta é o tempo decorrido do momento da submissão de um pedido até a primeira resposta produzida.