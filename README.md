#  escalonador
## Escalonador de Processos

1. Descrição

Este programa é um escalonador de processos.

2. Processos

Devem ser escalonador de 1 a 5 processos por vez a cada execução.
Ou seja, uma execução só é válida se possuir a quantidade de processos deste intervalo.

Para cada processo deve ser obrigatoriamente informado manualmente:
* Tempo de chegada
* Tempo de execução
* Deadline

Para cada execução deve ser obrigatoriamente informado manualmente:
  Quantum do sistema (a partir de 1)
  Sobrecarga do sistema (a partir de 1)

A unidade de tempo utilizada será em segundos*.
O tempo real de execução deverá ser na proporção: a cada 1,5 segundos simulados, será 1 segundo real.

3) Algoritmos a serem implementados para a execução dos processos:

  FIFO
  O primeiro a chegar é o primeiro a da fila de execução. (Não olha deadline nem prioridade).
  Se mais de 1 processo chegar ao mesmo tempo executa em qualquer ordem.
  Não utiliza Quantum nem sobrecarga
  SJF
  O processo que tiver a menor quantidade de tempo de execução restante num dado instante de tempo será o próximo a ser executado. (Não olha deadline nem prioridade).
  Não utiliza Quantum nem sobrecarga.
  Round Robin
  Organiza e fila de execução de forma circular. 
  Utiliza o Quantum e a sobrecarga
  Não olha o deadline.
  EDF
  Mostrar execução, sobrecarga, eventual estouro do deadline, deadline graficamente
 
4) Algoritmo de substituição de páginas de memória

* FIFO
* Menos Recentemente Utilizado

5) Mais alguns requisitos:

* Cada  processo  deve ter por padrão 10 páginas. 
* Cada  página  tem  4K  de  tamanho.  
* A  RAM pode armazenar até 50 páginas. 
* Ter uma abstração  de  DISCO  para  utilização  da  memória  virtual. Caso  ocorra  falta  de página,  utilize **N**  segundos para o uso  do  Disco. 
É opcional  a  criação  de qualquer abstração extra que se mostrar necessária.
* Os processos só executam se todas as suas páginas estiverem na RAM.
* Deve-se criar o gráfico de Gantt para mostrar as execuções dos processos, visualização da CPU e da RAM. 
* Deve-se criar o gráfico de uso da RAM e do Disco, mostrando as página presentes em tempo-real. A resposta deve ser dada em função do turnaround médio (tempo de espera + tempo de execução). Colocar delay para verificar a execução.
