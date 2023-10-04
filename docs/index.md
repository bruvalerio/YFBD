<h2><a href= "https://www.mackenzie.br">Universidade Presbiteriana Mackenzie</a></h2>
<h3><a href= "https://www.mackenzie.br/graduacao/sao-paulo-higienopolis/sistemas-de-informacao">Sistemas de Informação</a></h3>


<font size="+12"><center>
*&lt;Pizza Express&gt;*
</center></font>

**Conteúdo**

- [Autores](#Autores)
- [Descrição do projeto](#Descrição-do-projeto)
- [Análise de requisitos funcionais e não-fucionais](#Análise-de-requisitos-funcionais-e-não-fucionais)
- [Diagrama de casos de uso](#Diagrama-de-casos-de-uso)
- [Descrição dos casos de uso](#descrição-dos-casos-de-uso)
- [Diagrama de sequencia](#diagrama-de-sequencia)
- [Diagrama de classes](#diagrama-orientado-objetos)
- [Diagrama de componentes](#diagrama-estrutura-componente)
- [Decisões de arquitetura](#decisões-de-arquitetura)
- [Diagrama de implantação](#diagrama-de-hardware-software)
- [Referências](#referências)


# Autores

* Yasmin Toledo 
* Bruna Sousa  
* Fernanda Brazolin 
* Danilo Rocha 


# Descrição do projeto
<p> A pizza express está passando por uma crise após o seu concorrente desenvolver um um programa que garante entrega em 30 min desde a hora que pede até o pedido chegar na casa do cliente. 
A pizza express garante a entrega em 1h, com isso teve uma queda de 30% nos seus clientes. 
Atualmente os computadores usados por eles armazenam as operações e as funções usuais do negócio, mas não auxiliam no processo de entregas. 
A pizzaria express depende e um projeto feito pelo Eloon muske, que está responsável por desenvolver uma aplicação de software para identificar a localização das lojas de pizza pizza express mais próxima do cliente e para criar o sistema de software necessário para opera-las. 
A equipe precisa de uma opção para entregar os pedidos em menos de 30 minutos. Sua ideia foi, montar lojas de pizza express e focar apenas  nos pedidos que são para entregar, sem ter espaço para o varejo. 
Localizando a loja mais próxima do cliente, ela irá receber ordem através de uma central , processará e entregará o pedido dentro de 10 ou 15 minutos da entrada do pedido.</p>



# Análise de requisitos funcionais e não-funcionais
<p> Requisitos Funcionais:

1- Sistema de Localização de Lojas:

- O sistema deve ser capaz de identificar a localização do cliente   com precisão.
- Deve ser possível localizar a loja de pizza express mais próxima com base na localização do cliente.
- O sistema deve mostrar as opções de lojas disponíveis para o cliente.

2- Sistema de Pedido:

- Os clientes devem ser capazes de fazer pedidos online ou por telefone.
- As informações do pedido (itens, quantidade, endereço de entrega) devem ser registradas no sistema.

3- Central de Pedidos:

- Deve existir uma central de pedidos para receber, processar e encaminhar os pedidos às lojas correspondentes.
- A central deve ser capaz de priorizar os pedidos com base na localização das lojas e no horário de entrega desejado pelo cliente.
- Deve ser possível monitorar o status de todos os pedidos em tempo real.

4- Tempo de Entrega:

- O sistema deve calcular o tempo estimado de entrega com base na localização do cliente, na loja escolhida e na carga atual de pedidos.
- Os pedidos devem ser entregues em 10 ou 15 minutos a partir da entrada do pedido, dependendo da capacidade da loja e da distância do cliente.


Requisitos Não Funcionais:

1- Desempenho:

- O sistema deve ser capaz de processar pedidos rapidamente, minimizando atrasos.
- O tempo de resposta para consultas de localização e pedidos deve ser baixo.

2- Confiabilidade:

- O sistema deve ser altamente confiável, minimizando falhas e interrupções no serviço.
- Deve haver um plano de contingência para lidar com problemas técnicos.

3- Segurança:

- Os dados dos clientes, incluindo informações pessoais e de pagamento, devem ser protegidos contra acesso não autorizado.
- O sistema deve garantir que os pedidos sejam entregues apenas ao cliente correto.

4- Integração com GPS e Mapas:

- O sistema deve integrar-se a serviços de GPS e mapas para obter informações de localização precisas.

5- Compatibilidade de Plataforma:

- O sistema deve ser compatível com dispositivos móveis e navegadores da web para permitir que os clientes façam pedidos de várias plataformas.

6- Legislação e Regulamentação:

- O sistema deve estar em conformidade com regulamentações locais de segurança alimentar, privacidade de dados e direitos do consumidor.

7- Feedback dos Clientes:

- Deve haver um mecanismo para coletar feedback dos clientes sobre a qualidade do serviço e a precisão das entregas.

</p>


# Diagrama de casos de uso

![9ED68614-FFDA-4132-9A96-066B5624C21D](https://github.com/bruvalerio/YFBD/assets/144183243/c6006dbe-87c0-4e4e-aedd-3d4b0dbaa949)


# Descrição dos casos de uso

![UC06](https://github.com/bruvalerio/YFBD/assets/142839473/d4b37b32-06e3-449d-a132-60ecff687166)
<br>
![4100418f-15d3-4fb8-8456-771a7a8b0500](https://github.com/bruvalerio/YFBD/assets/142839473/743cd2ec-eb71-44f6-a87d-5e4e3a3f7b24)
<br>
![266bde17-be0b-4d46-b520-c25d58048008](https://github.com/bruvalerio/YFBD/assets/142839473/23d90a23-64c6-4644-8bd3-9a02122be9b5)
<br>
![c9c9e70f-3319-4bd4-ab7e-e2a185ab1570](https://github.com/bruvalerio/YFBD/assets/142839473/2a3414fd-bd93-4256-8d18-3ad49a882574)
<br>
![Captura de tela 2023-09-26 202053](https://github.com/bruvalerio/YFBD/assets/142839473/7c77b5a7-c0f2-4c9e-9263-239cb11d3b71)
<br>
![fdbe22ab-2357-4ce4-b734-9097e8b2fd1a](https://github.com/bruvalerio/YFBD/assets/142839473/1063ba18-ca01-488e-85fc-09fa2beec159)
<br>




# Diagrama de sequencia

![DiagramSequencia](https://github.com/bruvalerio/YFBD/assets/142839473/39e8dbf0-112e-4868-8b55-92a25ea1a08e)


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
