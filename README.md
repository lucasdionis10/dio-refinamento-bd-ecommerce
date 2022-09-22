# dio-refinamento-bd-ecommerce
Modelo relacional refinado para o desafio do Bootcamp da DIO

# Descrição:
Melhorias em formas de pagamento, entrega e carrinho.

## Carrinho: 
Une informações de pedido e produtos.

## Pagamento:
As formas de pagamento foi detalhado com as opções: PIX, Boleto e Cartão. Este último foi detalhado com as opções crédito e débito.
o pagamento ainda reúne informações dos produtos do carrinho, valor total, frete, informações do cliente, comprovante e o status Além de exportar informações para as formas de pagamento.

* Cartão: Opção de crédito e débito; Número, validade. O cliente também importa as opções de cartão.
* PIX: Cria um id do pix para identificação interna, um código PIX copia e cola.
* Boleto: cria um código do boleto, e apresenta data de vencimento.

## Entrega:
A entrega foi detalhada com o status, valor do frete, tipo de entrega, código de rastreio, tempo estimado e distância estimada.
=======
Melhorias em formas de pagamento, entrega, carrinho, 


## Pagamento:
As formas de pagamento foi detalhado com as opções: PIX, Boleto e Cartão. Este último foi detalhado com as opções crédito e débito.

* Cartão: Opção de crédito e débito; Número, validade. Além disso, importa número do comprovante, os itens do carrinho e o id do pedido.
* PIX: Cria um id do pix para identificação interna, um código PIX copia e cola,   


## Entrega:
A entrega foi detalhada com o status, valor do frete, tipo de entrega, código de rastreio, tempo estimado e importa o ID do pedido e do cliente.
