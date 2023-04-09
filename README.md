# desafioSQL
Desafio de projeto - Projeto conceitual de Banco de Dados

Projeto conceitual de Banco de Dados - E-commerce

Narrativa
Os produtos são vendidos por uma única plataforma online, contudo, estes podem ter vendedores distintos.
Cada produto possui um fornecedor
Um ou mais produtos podem compor um pedido.

Cliente
O cliente pode se cadastrar no site com seu CPF ou CNPJ
O endereço do cliente irá determinar o valor do frete
Um cliente pode comprar mais de um pedido. Este tem um período de carência para devolução do produto

Pedido
Os pedidos são criados por clientes e possuem informações de compra, endereço e status de entrega
Um produto ou mais compõem o pedido
O pedido pode ser cancelado

Fornecedor e Produtos
Os produtos tem categoria, identificação, valor e descrição
Produto tem um ou mais fornecedores e um fornecedor disponibiliza um ou mais produtos
Fornecedor tem Razão social e CNPJ
Existe um estoque de produtos
O Estoque tem identificação, Local e quantidade
Existe mais de um estoque, que armazena mais de um produto

Refinando
Cliente PJ e PF - uma conta pode ser PJ ou PF, mas não pode ter as duas informações
Pagamento - Pode ter cadastrado mais de uma forma de pagamento
Entrega - possui status e código de rastreio
