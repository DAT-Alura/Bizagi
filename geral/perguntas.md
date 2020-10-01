# Perguntas

## Aula 1

### 1 - Vimos que o BPMN é a forma mais eficiente e padronizada de "representar graficamente uma sequência de ações para se atender um determinado objetivo, ou seja, um processo", assinale dentre as opções abaixo quais são os 3 principais benefícios de se utilizar o BPMN?

__A__ - Divulgação do conteúdo do processo – Ferramenta de comunicação do que acontecerá ao ser executado o processo
> O BPMN é um importante instrumento de comunicação que permite a visualização por diversas pessoas do passo a passo detalhado de um processo

B - Agilidade na execução do processo - Acelera o tempo de execução, pois, os detalhes do processo são conhecidos.

C - Qualidade do processo – Garantia de qualidade na execução do processo

D - Definição de funções e responsabilidades do processo – Indicação aos envolvidos do que se deve fazer dentro do processo

__E__ - Fácil leitura de um processo - Permite ilustrar o entendimento de um determinado processo para um leitor que não está envolvido no dia-a-dia do processo.
> O uso da notação de modelagem de processos de negócios (BPMN) devido ao uso padronizado de símbolos gráficos permite aos leitores uma rápida visualização de como uma sequência de ações é executada gerando um determinado resultado.

__F__ - Documentação de um processo – Registro em linguagem gráfica de um processo
> O BPMN permite o registro de maneira padronizada, clara e concisa de um processo

### 2 - Assinale dentre as opções abaixo aquela que representa a principal finalidade de uso da ferramenta Bizagi Modeler:

A - Serve para documentar uma reunião de identificação de todos os requisitos de um sistema

__B__ - Permite representar de maneira padronizada por meio de elementos gráficos os processos de negócios.
> A ferramenta Bizagi Modeler foi criada para permitir aos seus usuários representar usando BPMN processos de negócio.

C - Automatizar processos de negócio.

D - Representa uma forma de definir as funcionalidades de um sistema

### 3 - Dentre as ferramentas citadas abaixo assinale aquela que não apresenta funcionalidades semelhantes a Bizagi Modeler para representação de modelos de processos usando BPMN.

A - Sydle

B - ARIS Express

C - Heflo

__D__ - Oracle Primavera
> Esta ferramenta tem a finalidade auxiliar gerente de projetos no gerenciamento integrado/ acompanhamento de projetos e não representar processos usando BPMN

E - Draw io

## Aula 2

### 1 - Considerando que podemos entender uma “Atividade” como sendo uma ação que ocorre num determinado momento de um processo de negócio, assinale dentre os exemplos listados abaixo aquele que representa um exemplo de atividade.

A - Acesso ao banco de dados estoque

B - Análise dos perfis de consumo dos clientes

C - Associação de um Pedido com um cliente

__D__ - Cadastrar Pedido
> O uso do verbo para representar a ação de cadastrar um pedido denota uma atividade usando BPMN

### 2 - Considerando que podemos entender uma “Ligação” em BPMN serve para representar a conexão de uma sequência de ações, fluxo de mensagens, e/ou associar diferentes elementos de BPMN, assinale dentre os exemplos listados abaixo aquele que representa uma ligação.

A - Finalizar Pedido

__B__ - Demonstrar a conexão entre "Cadastrar um Pedido" e uma "Análise do Perfil de Consumo de um Cliente"
> A conexão entre os elementos “Cadastrar um Pedido” (Atividade) e “Análise do Perfil de Consumo de um Cliente” (Evento) – veremos este elemento com mais detalhes na próxima aula, representa uma sequência de acontecimentos (Ligação) num processo.

C - Venda Agregada

D - Consulta ao Estoque

### 3 - Considerando que podemos entender um “Subprocesso” como um grupo de elementos de BPMN que podem ser representados de maneira agrupada (colapsada) sem perda de informação e entendimento do processo principal que esta sendo modelado, assinale dentre os exemplos listados abaixo aquele que representa um subprocesso.

A - Apontar o caminho para a realização de uma Venda

B - Cadastrar Item de Pedido

C - Categorização de Cliente

__D__ - Aumento de Produtos em Estoque
> O aumento de produtos em estoque é um sub-processo relacionado a um processo pai “Gestão de Estoque”.

## Aula 3

### 1 - Dentro de BPMN o Elemento “Evento” serve para indicar alguma coisa que acontece no processo entre seu início e fim, com base nesta definição assinale dentre os exemplos listados abaixo aquele melhor representa um Evento.

A - Cadastrar Pedido

B - Estoque atualizado

__C__ - Término de Finalizar Pedido
> Neste caso identificamos que foi criado um "Evento de Término” após a execução da atividade que sequencialmente ocorre dentro do processo (Finalizar Pedido)

D - Informar Vendedor

### 2 - Dentro de BPMN o Elemento “Desvio” serve para controlar o fluxo do processo e pode marcar o início ou o fim de um conjunto de caminhos alternativos ou paralelos, com base nesta definição assinale dentre os exemplos listados abaixo aquele melhor representa um Desvio.

__A__ - Confirmar ou não um pedido
> A opção de confirmação ou não de um pedido em um processo indica um ponto demarcado pelo elemento “Desvio”, que ao ser acessado permite a visualização de possíveis caminhos na sequência de execução do processo

B - Realizar Pedido de Compra

C - Compra Agregada

D - Início do Pedido de Compra

### 3 - A maioria dos especialistas em mapeamento de processos optam por representar em uma modelagem de processos os elementos “Eventos” e “Desvios” depois de identificar “Atividades, Ligações e Sub-Processos”, na sua opinião qual é principal finalidade de representarmos “Eventos” e “Desvios” neste 2º momento?

__A__ - Para indicar um ótimo momento para reflexão se o processo está de fato representando fielmente a realidade mapeada como requisito
> Exatamente, além disso a partir deste momento visualizamos que os mesmos estão de fato, repercutindo coisas que acontecem no contexto do processo e influenciam e direcionam sua execução

B - Devido ao fato de BPMN orientar a fazermos desta forma

C - Para que possamos já pensar nos detalhes de aspectos do modelo físico do processo

## Aula 4

### 1 - Dentro de BPMN o Elemento “Artefato” serve para representar, armazenar e consultar sistemas/informações geradas durante a execução do processo, com base nesta definição assinale dentre os exemplos listados abaixo aquele melhor representa um Artefato.

__A__ - Consulta a uma lista de pedidos
> Se considerarmos que os pedidos serão gerados e armazenados durante a execução de um processo de venda, a consulta a esta informação gerada na medida em que o processo é executado envolve a representação de “Pedidos” como um Artefato

B - Análise da Categoria de Cliente

C - Direcionar o caminho de uma consulta a um estoque

D - Cadastrar Cliente

### 2 - Dentro de BPMN o Elemento “Swimlane” serve para representar diferentes participantes num processo e melhor organizar a modelagem do processo como um todo ilustrando responsabilidades de entidades e local/organização onde o processo será executado, com base nesta definição assinale dentre os exemplos listados abaixo aquele melhor representa um Swimlane.

__A__ - O Vendedor de uma Livraria tira um pedido de um Cliente no Balcão.
> A descrição geral do processo será modelada no interior da swinlanes “Livraria” considerando as entidades “Vendedor” e “Cliente”.

B - Pedido Finalizado

C - Propor Vendas Agregadas

D - Atualizar valor do pedido na Base “Pedidos”

### 3 - Os elementos de BPMN “Artefatos e Swimlanes” dentro da modelagem de processo usando BPMN numa camada conceitual representam vários requisitos que deverão ser explorados com mais ênfase na fase do modelo lógico em nível de entendimento de interfaces, perfis e macro-processamentos do processo na medida em que o mesmo for sendo modelado. Assinale dentre as opções abaixo qual é o principal benefício da correta representação destes elementos no modelo conceitual?

__A__ - Produtividade e assertividade na elaboração do modelo físico mais a frente
> De fato, este entendimento inicial repercutirá na qualidade e eficiência da implementação do processo.

B - Diminuição do tempo de validação final do processo com o dono do negócio

C - Facilidade no uso de uma linguagem de programação
