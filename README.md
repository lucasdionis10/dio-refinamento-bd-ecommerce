# dio-refinamento-bd-ecommerce
Modelo relacional refinado para o desafio do Bootcamp da DIO


## Descrição do Desafio
O esquema deverá ser adicionado a um repositório do Github para futura avaliação do desafio de projeto. Adicione ao Readme a descrição do projeto conceitual para fornecer o contexto sobre seu esquema.

## Objetivo:
Refine o modelo apresentado acrescentando os seguintes pontos:

* Cliente PJ e PF – Uma conta pode ser PJ ou PF, mas não pode ter as duas informações;
* Pagamento – Pode ter cadastrado mais de uma forma de pagamento;
* Entrega – Possui status e código de rastreio;


# Descrição da mudança:
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
