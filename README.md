# -Process-scheduler
Escalonamento
Esse projeto tem como objetivo simular algoritmos de escalonamento com e sem preempção (SJF, RR, PS ,FCFS).

Exemplo de arquivo de entrada:

5 -> numero de processos
3 ->  quantum do RR
3 10 2 -> 3 = tempo de chegada, 10 = burst time , 2 = Prioridade
4 12 1
9 15 2
3 16 1
12 8 5


Gráfico de saída: SJF   
---1111111111CS55555555CS222222222222CS333333333333333CS4444444444444444CS



Gráfico de saída: PrioritySecurity   
---4444444444444444CS222222222222CS1111111111CS333333333333333CS55555555CS


Gráfico de saída: First-Come First Served  
---1111111111CS4444444444444444CS222222222222CS333333333333333CS55555555CS


Gráfico de saída: RoundRobin organizado por prioridade
---444CS444CS222CS444CS222CS444CS222CS444CS222CS4CS111CS333CS111CS333CS111CS333CS1CS333CS333CS555CS555CS55CS
