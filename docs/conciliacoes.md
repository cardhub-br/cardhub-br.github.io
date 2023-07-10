

## Vendas com meio de pagamento eletrônico
Para vendas digitais com seu meio de pagamento eletrônico, deve se atentar que o fluxo: solicitação de venda -> cancelamento/confirmação de venda tem seu formato alterado adicionando uma nova operação que é a de pagamento. Como podemos observar na imagem abaixo as execuções das operações de cancelamento ou confirmação dependem do resultado da transação de meio de pagamento.

![Vendas-Pgto-Eletronico](/assets/images/vendas-com-meio-de-pgto.png#center)

## Conciliação de transações
Outra boa prática a ser adotada é o processo de conciliação das transações realizadas, conforme podemos observar na ilustração esse processo tem o objetivo de garantir que todas as operações iniciadas na API MultiProdutos sejam resolvidas independentemente de seu resultado final. Dessa forma, é suma importância a adoção dessa prática em seu meio transacional para que haja conformidade nos relatórios transacionais.

![Conciliação de transações](/assets/images/sobre-conciliacao-de-transacoes.png#center)

