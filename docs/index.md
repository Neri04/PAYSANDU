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

A rede de pizzarias "Pizza-Express" enfrenta desafios significativos em relação à eficiência de suas entregas, que estão prejudicando seus rendimentos em 30% em comparação com sua principal concorrente, que realiza entregas em até 30 minutos após o pedido do cliente. Para abordar esse problema, a empresa está buscando soluções tecnológicas por meio de dois projetos de software distintos:

Projeto 1: Sistema de Software para Atendimento de Pedidos e Localização de Lojas

O primeiro projeto visa melhorar o atendimento ao cliente e a localização das lojas mais próximas. Suas principais características incluem:

Atendimento de Pedidos: Desenvolver um sistema de software que permita aos clientes fazer pedidos de forma rápida e eficiente, seja por meio de um aplicativo móvel ou site. Isso deve incluir a seleção de itens do menu, opções de personalização e pagamento online.

Localização de Lojas: Implementar um mecanismo que identifique automaticamente a loja mais próxima do cliente que fará a entrega. Isso pode ser baseado na localização do cliente ou em algoritmos que calculam a proximidade das lojas.

Rastreamento de Pedidos: Oferecer aos clientes a capacidade de rastrear o status de seus pedidos em tempo real, incluindo a preparação da pizza e a entrega.

Integração de Mapas: Integração de mapas para orientar os entregadores até o destino do cliente.

Projeto 2: Sistema de Software para Suporte às Operações da Fábrica de Pizzas

O segundo projeto concentra-se nas operações internas da fábrica de pizzas para garantir que as pizzas sejam preparadas e entregues de forma eficiente. Suas principais características incluem:

Gestão de Pedidos Internos: Um sistema para registrar e gerenciar pedidos internos na fábrica, garantindo que todos os detalhes do pedido sejam seguidos com precisão.

Controle de Tempo de Preparação: Implementar um sistema de controle de tempo que garanta que a preparação da pizza seja concluída dentro de um intervalo de tempo de 10 a 15 minutos após o recebimento do pedido.

Roteamento Interno de Entregadores: Se necessário, criar uma solução para rotear entregadores internamente, garantindo que as pizzas sejam entregues de forma eficiente e dentro do prazo.

Integração com Pedidos dos Clientes: Assegurar que o sistema de fábrica de pizzas esteja integrado ao sistema de atendimento de pedidos para uma operação perfeita.

O objetivo final desses projetos é criar um serviço de entrega que seja capaz de realizar a entrega de pizzas em menos de 30 minutos após o pedido, alinhando-se com a concorrente. Essas soluções tecnológicas devem ajudar a Pizza-Express a melhorar sua eficiência operacional, atender às expectativas dos clientes e recuperar seu rendimento perdido

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
