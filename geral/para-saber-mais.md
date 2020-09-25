# Para saber mais

## Diferença Atividade x Evento

Fazendo um paralelo do que estudamos na aula passada e atual, sobre os elementos na notação BPMN - atividade e evento, você já parou para pensar nas diferenças dentro da notação BPMN associada ao uso destes elementos?

Vamos a elas, começando pelo reforço em algumas características que definem estes elementos:

- Atividades: são pontos do processo onde é executada uma ação, por algum executor conhecido no processo.

- Eventos: é algo que acontece durante o curso de um processo, sendo usualmente derivado da execução de um processo externo, sub-processo ou acionado (via gatilho previsto no processo) para ocorrer a partir da execução de uma atividade do próprio processo.

Assim, fazendo uma análise identificamos que eventos são derivados de atividades em nosso processo "Expande Vendas", como isso estes eventos, por exemplo não poderiam ser modificados para representação como atividades.

Reforçando que em nosso processo temos as seguintes derivações:

- O evento "Confirmar prazo de entrega" deriva da atividade "Realizar Pedido de Clientes" quando o item tem disponibilidade em estoque.

- O evento "Avaliar a possibilidade de vendas agregadas" deriva da atividade "Realizar Pedido de Clientes".

- O evento "Categorizar cliente" deriva da atividade "Cadastrar Cliente".

Pense se estes eventos lidos isoladamente sem estarem associados a atividades fariam algum sentido em nosso processo, com certeza não, concorda!?

Em suma, de acordo com o nosso exemplo, os 3 eventos citados são "engatilhados" para tratar os requisitos de nosso processo, a partir das atividades de "Realizar de Pedidos" e "Cadastrar de Clientes".
