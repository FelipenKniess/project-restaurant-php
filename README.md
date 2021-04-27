
## Idéia de projeto para restaurante

### Páginas do sistema:
	* Login
	* Home(página para selecionar as mesas)
	* Cadastro/Mesa
	* Cadastro/Produto
	* Janela de Pedidos pendentes da mesa(Adicionar pedido, Pagar conta)
	* Relatórios/Vendas
	
### Requisitos das páginas:

#### Login:
	* Conterá um campo de nome do usuario
	* Conterá um campo de senha

#### Home :
	* Em todas as páginas do sistema o menu estará posicionado na parte superior.
	* No corpo da pagina principal terá todas as mesas registradas através de imagens.
	* Ao clicar nas mesas abrirá uma janela de pedidos daquela mesa.
	* O sistema conterá um rodapé fixo em todas as páginas.
	* na parte superior mostra que o usuario que estiver logado no sistema
	* A lista de mesas será através de imagens posicionadas lado a lado com o número da mesa
	
#### Cadastro/Mesa :
	* Campos: código da mesa e observação.
	* Toda vez que uma nova mesa é registrada, ela será adicionada na página home na lista de mesas.
	* Na mesma página de cadastro terá a lista de todos as mesas registradas.
	* as ações serão de excluir, editar e visualizar.
	
#### Cadastro/Produto:
	* Campos: Código do produto(autoIncremento), Nome do Produto, Preço do produto
	* Os produtos podem estar ativo/inativo. Apenas os ativos aparecerão na lista de produtos na hora do pedido.
	* As ações serão de excluir, editar e visualizar.



#### Janela de pedidos:
	* Terá a lista de todos os pedidos que estão pendentes naquela mesa.
	* Campos da tabela: Código do pedido, Numero da mesa, hora inicial do pedido.
	* Esta tela tera 2 botões para realizar ação: Incluir pedido, Pagar conta.
	
#### Janela de inclusão de pedidos:
	* Campos: Numero da mesa(sem opção de alteração);
	* Data/hora do pedido(Data e hora atual com opção de alteração);
	* Observação do pedido;
	* Grid com os produtos da lanchonete.
	* Tabela do grid com todos os campos do produto.
	* O valor de cada produto no pedido pode ser alterado  no momento do registro(descontos). 


#### Janela de pagamento:
	* Campo: numero da mesa ( sem opção de alteração );
	* Tabela com todos os pedidos realizados naquela mesa
	* Cada pedido pode ser vizualizado os seus itens(com opção de remover e adicionar itens)
	* Valor total da mesa( com opção de desconto ).
	* Pagar conta ( Ao pagar conta gera uma nota com os itens dos produtos em pdf)


#### Relatório/Vendas:
	* Tabela com todas as vendas realizadas.
	* Filtro de busca por data do pedido, podendo selecionar os pedidos vendidos naquele mês/dia/ano/semana.
								
