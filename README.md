# Trabaho1-SO

Trabalho Prático 1 - de 26/08/2021 a 11/10/2021

Os alunos devem confeccionar um programa com 2 processos da seguinte maneira:
a) Processo 1: cria o processo 2 e envia 10 mensagens por fila de mensagens numeradas (1 a 10) para o processo 2. 
   Quando o processo 2 morrer, remove a fila de mensagem e termina a execução.

b) Processo 2: executa um loop para receber 10 mensagens, onde 
   (i) recebe mensagem,  
   (ii) imprime o numero da mensagem e 
   (iii) dorme 5 segundos. 
   Ao final do loop, termina a execução.
 
 Observação: devem ser usadas chamadas de sistema Unix para criação e término de processos e chamadas de sistema do mecanismo IPC fila de mensagens.
 Observação: deve ser entregue o programa fonte em C no formato .txt
