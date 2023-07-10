# Consultas

## Introdução 

Segue abaixo sugestões de boas práticas de integração para que se possa obter um melhor uso e desempenho da nossa API de MultiProdutos:


## Cache das consultas
Nas duas consultas: Consultar Produtos e Consultar Valores por DDD, suas informações sofrem mudanças de forma esporádica em nossa base, por isso nossa recomendação é a persistência delas em formato de cache do lado do cliente. Dessa forma essas operações não fazem parte do fluxo normal de venda e sejam executadas em intervalos longos de tempo.


## Execução das consultas
Acerca do tema de desempenho é recomendado que as chamadas dos endpoints de consultas como a listagem de produtos e de valores por DDD sejam realizadas de forma sequencial e não-simultanêas para que não ocorram intermitências ocasionadas pela concorrência nas requisições.