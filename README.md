# ProdutorxConsumidor - SO em Java
Resolver o problema dos produtores e consumidores através do uso de threads e
monitores. Deverão existir os seguintes componentes:
-Thread Produtora: produzirá números aleatórios e colocará em um buffer
compartilhado. Após a produção de um número deverá dormir num tempo que varia
aleatoriamente entre 0 e 100 milissegundos. Caso o buffer esteja cheio deverá dormir
até que existam posições disponíveis.
- Thread Consumidora: fará a leitura dos números do buffer, apenas escrevendo os
mesmos na saída padrão do sistema. Caso não existam números para serem lidos
deverá dormir até que um novo número seja colocado no buffer.
- Buffer Compartilhado: deverá acomodar no máximo 20 números.
