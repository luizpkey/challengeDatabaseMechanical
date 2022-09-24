# challengeDatabaseMechanical
 Construindo um Esquema Conceitual para Banco De dados


  ## Descrição do Desafio
  Criado um esquema conceitual do zero. A partir da narrativa fornecida, relacionamentos e atributos. 

  ## Objetivo:
  Cria o esquema conceitual para o contexto de oficina com base na narrativa fornecida

  ## Narrativa:
  Sistema de controle e gerenciamento de execução de ordens de serviço em uma oficina mecânica
Clientes levam veículos à oficina mecânica para serem consertados ou para passarem por revisões  periódicas
Cada veículo é designado a uma equipe de mecânicos que identifica os serviços a serem executados e preenche uma OS com data de entrega.
A partir da OS, calcula-se o valor de cada serviço, consultando-se uma tabela de referência de mão-de-obra
O valor de cada peça também irá compor a OSO cliente autoriza a execução dos serviços
A mesma equipe avalia e executa os serviços
Os mecânicos possuem código, nome, endereço e especialidade
Cada OS possui: n°, data de emissão, um valor, status e uma data para conclusão dos trabalhos.


## Minha Analise
  1. Cada cliente pode fazer um ou mais pedidos de manutenção. 
  2. Uma equipe composta por um ou mais mecanicos analisa os pedidos do cliente adiciona o orçamento de peças e mão de obra e abre a O.S..
  3. A tabela tem que eu deveria ter renomeado para Orçamento contem os itens do pedido e seus respectivos valores para execução.
  4. Após a analise da equipe é repassado a previsão da data de entrega e abre a ordem de serviço que fica aguardando a autorização por parte do cliente.
  5. Serviço autorizado a equipe executa a O.S., caso contrário é arquivada.
