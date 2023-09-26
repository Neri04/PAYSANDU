<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Nome do Projeto&gt;*
</center></font>

>*Observação 1: A estrutura inicial deste documento é só um exemplo. O seu grupo deverá alterar esta estrutura de acordo com o que está sendo solicitado na disciplina.*

>*Observação 2: O índice abaixo não precisa ser editado se você utilizar o Visual Studio Code com a extensão **Markdown All in One**. Essa extensão atualiza o índice automaticamente quando o arquivo é salvo.*

**Conteúdo**

- [Autores](#nome-alunos)
- [Descrição do projeto](#introdução-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#descrição-dos-requisitos)
- [Diagrama de casos de uso](#diagrama-de-comportamento-atores)
- [Descrição dos casos de uso](#descrição-das-funcões)
- [Diagrama de senquencia](#diagrama-de-ordem-interações)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Gabriel Neri ( 32366851 )
* Matheus Ramalho ( 32335776 )
* Caue Lemos ( 32315104 )
* Igor Bragança ( 42119316 ) 

# Descrição do projeto

 O diagrama de caso de uso representa como a Pizza-Express, uma cadeia de 40 lojas de fast-food e entrega em casa, interage com seus clientes e gerencia suas operações de entrega de pizza.

Realizar Pedido de Pizza:
Neste caso de uso, os clientes iniciam o processo ao fazerem um pedido de pizza. O sistema de software registra o pedido, identifica a loja Pizza-Express mais próxima do cliente e encaminha o pedido para a loja escolhida. Os clientes recebem uma confirmação do pedido.

Processar Pedido na Loja:
Este caso de uso é acionado quando uma loja de pizza recebe um pedido da central. A loja prepara a pizza de acordo com o pedido, atualiza o status de preparação e entrega a pizza a um entregador.

Entregar Pizza ao Cliente:
Após a pizza ser preparada na loja, o entregador assume o pedido e entrega a pizza ao cliente. O cliente confirma a entrega.

Desenvolver Software para Atendimento de Pedido e Operações da Fábrica de Pizzas:
Elonn Muske, o gerente de sistemas de informação, é responsável por desenvolver dois sistemas de software essenciais. O primeiro sistema é para o atendimento de pedidos, que registra os pedidos dos clientes e identifica a loja mais próxima. O segundo sistema é para operações na fábrica de pizzas, auxiliando na preparação eficiente dos pedidos.

Relações entre os Casos de Uso:

O caso de uso "Realizar Pedido de Pizza" depende dos sistemas de software desenvolvidos por Elonn Muske para identificar a loja mais próxima.
O caso de uso "Processar Pedido na Loja" depende do caso de uso "Realizar Pedido de Pizza", pois a preparação do pedido começa após o pedido do cliente.
O caso de uso "Entregar Pizza ao Cliente" depende do caso de uso "Processar Pedido na Loja", pois a entrega ocorre após a preparação.
Em resumo, o diagrama de caso de uso descreve como os clientes fazem pedidos, como as lojas de pizza processam esses pedidos, e como a entrega é realizada. Ele também destaca a importância dos sistemas de software desenvolvidos por Elonn Muske para facilitar essas operações e garantir a eficiência do serviço de entrega da Pizza-Express. 

# Análise de requisitos funcionais e não-funcionais
*1. Realizar Pedido de Pizza:

Os clientes podem fazer pedidos de pizza através deste caso de uso.
O sistema deve registrar os pedidos dos clientes de forma precisa.
O sistema deve determinar a localização da loja Pizza-Express mais próxima com base na ordem de serviço.
O sistema deve encaminhar os pedidos para a loja selecionada.
Confirmações de pedidos devem ser enviadas aos clientes.

2. Processar Pedido na Loja:

A Loja de Pizza recebe pedidos da Central.
A preparação de pedidos deve ser eficiente e precisa.
O status de preparação deve ser comunicado ao sistema.
As pizzas preparadas devem ser entregues a um entregador.

3. Entregar Pizza ao Cliente:

A entrega das pizzas é realizada pelos entregadores.
Os entregadores devem receber as pizzas da Loja de Pizza.
A entrega deve ser feita dentro do prazo estabelecido (potencialmente em menos de 30 minutos).
Os clientes devem confirmar a entrega.

O sucesso do caso de uso "Realizar Pedido de Pizza" depende dos sistemas de software desenvolvidos por Elonn Muske, pois eles são responsáveis por determinar a localização da loja mais próxima.
O caso de uso "Processar Pedido na Loja" depende do caso de uso "Realizar Pedido de Pizza", pois a preparação dos pedidos começa após o pedido ser feito pelo cliente.
O caso de uso "Entregar Pizza ao Cliente" depende do caso de uso "Processar Pedido na Loja", uma vez que a entrega ocorre após a preparação dos pedidos.
Considerações Adicionais:

Há uma pressão para reduzir o tempo de entrega para menos de 30 minutos, o que requer otimização e eficiência nas operações.
A Pizza-Express busca se adaptar à concorrência que promove a entrega em 30 minutos.
A ênfase em desenvolver sistemas de software eficazes indica a importância da tecnologia na operação da Pizza-Express.*

# Diagrama de casos de uso

*&lt;Diagrama para visualizar o comportamento dos atores&gt;*

# Descrição dos casos de uso

*&lt;Descrição do comportamento entre os atores/resquisitos&gt;*

# Diagrama de sequencia

*&lt;Diagrama de ordem e interação dos objetos&gt;*

# Diagrama de classes

*&lt;Diagrama de relacionamento entre classes para os seus atributos e operações&gt;*

# Diagrama de Componentes

*&lt;Diagrama para exibir a relação estrutural dos componentes de um sistema de software

# Decisões de arquitetura

*&lt;Descrever a infraestrutura escolhida para arquitetura do projeto&gt;*

# Diagrama de implantação

*&lt;Diagrama para exibir o relacionamento de hardware e software no projeto&gt;*

# Referências

*&lt;Lista de referências&gt;*
