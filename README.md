# Computação Evolutiva
Implementação em ANSI-C de um _Algoritmo Genético_ capaz de resolver o problema das oito rainhas.  
  
# 8 Queens  
Este problema consiste, como próprio nome sugere, em encontrar posições para oito rainhas em um tableiro de xadrez, sem que elas se ameassem entre si.  
  
# Como o algoritmo funciona?  
O algorimo cria algumas estrutura simples de dados e, com elas, tenta simular comportametos biológicos envolvendo evolução, mutação, seleção e reprodução.  
As estruturas são:  
* cromossomo - composto por um conjunto de oito genes (cada um equivale a uma coluna do tabuleiro);
* individuo - possui um unico cromosso e um resulatdo chamado aptidao, que é calculado pelo algoritmo com base no numero de rainhas posicionadas corretamente;
* populacao -  um conjunto de cem indivíduos.  
A cada geração um grupo de 10% formado pelos mais aptos é preservado -elitismo-. os demais são substituidos por combinações entre o grupo sobrevivente.  
O alfabeto dos genes vai de 0 à 7 e representa a linha ocupada pela rainha.
  
# A  mutação  
Os 90% -novos indivíduos- terao um gene substituido aleatoriamente.
