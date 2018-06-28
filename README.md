# escalonador
Escalonador de Processos

1) Descrição
Este programa é um escalonador de processos.

2) Processos

Devem ser escalonador de 1 a 5 processos por vez a cada execução.
Ou seja, uma execução só é válida se possuir a quantidade de processos deste intervalo.

Para cada processo deve ser obrigatoriamente informado manualmente:
  Tempo de chegada  
  Tempo de execução
  Deadline
  Prioridade (de 0 a 99)
Para cada execução deve ser obrigatoriamente informado manualmente:
  Quantum do sistema (a partir de 1)
  Sobrecarga do sistema (a partir de 1)

A unidade de tempo utilizada será em segundos*.
O tempo real de execução deverá ser na proporção: a cada 1,5 segundos simulados, será 1 segundo real.

3) Algoritmos a serem implementados para a execução dos processos:

  FIFO
  O primeiro a chegar é o primeiro a ser executado
  Se mais de 1 processo chegar ao mesmo tempo executa em qualquer ordem.
  Não utiliza Quantum nem sobrecarga
  SJF
  O processo que tiver a menor quantidade de tempo de execução restante num dado instante de tempo será o próximo a ser executado
  Não utiliza Quantum nem sobrecarga
  Round Robin
  EDF


