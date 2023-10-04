
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;PizzariaExpress;*

(https://github.com/Neri04/PAYSANDU/files/12798065/4.WhatsApp.pdf)

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

Documentação da pizzaria


Visão geral:
A Pizzaria será dedicada a fornecer pizzas de alta qualidade com entrega rápida, com o compromisso de entregar a pizza na casa do cliente em menos de 30 minutos a partir do momento em que o pedido é feito. Este documento descreve os processos, políticas e procedimentos que a pizzaria irá seguir para atingir esse objetivo.


Missão:
Nossa missão é proporcionar aos nossos clientes a melhor experiência de pizza com entrega rápida, oferecendo produtos de alta qualidade e serviço excepcional.


Objetivo:
* Entregar todas as pizzas em menos de 30 minutos após o pedido ser feito.
* Manter a qualidade dos ingredientes e da pizza em todos os pedidos.
* Fornecer um cardápio variado com opções para todos os gostos.
* Garantir a satisfação do cliente em todas as interações.


Cardápio: 
* 1- Pizzas tradicionais com diversos sabores.
* 2- Pizzas especiais com ingredientes exclusivos.
* 3- Opções vegetarianas e veganas.
* 4- Opções de tamanhos de pizza: pequena, média, grande e família.
* 5- Bebidas, sobremesas e acompanhamentos.


Processo de pedido:


* O  processo inicia com o cliente decidindo o que deseja pedir do nosso cardápio.
* Após o cliente realizar e pagar o seu pedido, o pedido será enviado automaticamente para a nossa central.
* A central recebe o pedido e envia para a pizzaria que está localizada o mais próxima possível do cliente
* Com o pedido sendo recebido pela pizzaria, a produção irá fazer o pedido, onde apenas bastaria colocar as pizzas no forno, já que pretendemos deixar pizzas pré prontas antes de abrirmos para pedidos.
* Com a pizza finalizada, a produção entrega o pedido para o entregador, que parte para a localização do cliente entregar a sua desejada pizza.


Entrega rápida:
O nosso maior compromisso com o cliente é entregar o seu pedido o mais rápido possível dentro dos 30 minutos


* A frota de entregadores está equipada com sistemas de navegação em tempo real para otimizar as rotas.
* O tempo de preparação da pizza é mantido o mais curto possível, já que deixaremos pizzas pré prontas antes de abrirmos para pedidos
* O pedido será direcionado para a pizzaria mais próxima do cliente
* Os entregadores receberão notificações da pizzaria mais próxima a eles, para chegarem na pizzaria o mais rápido possível e partir para a entrega


Qualidade dos ingredientes:
Pode-se desconfiar de deixarmos as nossas pizzas pré prontas, mas garantimos que os ingredientes serão de qualidade, isso incluem:


* Massa fresca e feita diariamente.
* Molhos caseiros preparados com tomates frescos.
* Queijos de qualidade premium.
* Ingredientes frescos e legumes selecionados.


Atendimento ao cliente:
A satisfação do cliente é fundamental para nós. Para garantir um excelente atendimento ao cliente:


* Nossa equipe de atendimento é treinada para ser cortês e prestativa.
* O feedback dos clientes é bem-vindo e usado para melhorar nossos serviços.
* Estamos disponíveis para resolver quaisquer problemas ou preocupações dos clientes.


Políticas para qualidade garantida:
A Pizzaria mantém rigorosos padrões de qualidade, incluindo:
* Inspeções regulares de nossos ingredientes e fornecedores.
* Treinamento contínuo para nossa equipe de cozinha e entregadores.
* Monitoramento constante do tempo de entrega.
* As pizzas pré prontas ficarão em resfriador para prevenir de que bactérias estraguem o alimento

# Diagrama de casos de uso

![image](https://github.com/Neri04/PAYSANDU/assets/124932890/9df8fa8a-4b7b-4375-8217-4f1a765b4d7b)


# Descrição dos casos de uso

![image](https://github.com/Neri04/PAYSANDU/assets/124932890/5d0693de-8c1b-4634-84de-6cecec440a93)

# Diagrama de sequencia

![dd0751fe-6eaa-4914-b9ad-306de282e168](https://github.com/Neri04/PAYSANDU/assets/124932890/bd11ba52-45d1-4906-926b-641143b6bbd0)

# Referências

https://graduacao.mackenzie.br/pluginfile.php/1037193/mod_resource/content/2/SI_2J_IntroducaoEngenhariaSoftware_Apostila05_2.pdf

https://graduacao.mackenzie.br/pluginfile.php/1553039/mod_resource/content/2/SI2_Modelo_DescricaoCasoUso_2023_2.pdf

https://graduacao.mackenzie.br/pluginfile.php/1554983/mod_resource/content/2/Diagrama%20de%20Sequencia.pdf
