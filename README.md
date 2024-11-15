📊 Escopo do Sistema de Controle de Ordens de Serviço - Oficina Mecânica 🔧🚗
Objetivo do Projeto:
O projeto tem como objetivo a modelagem e implementação de um banco de dados para o controle de ordens de serviço (OS) em uma oficina mecânica, utilizando MySQL Workbench. O sistema gerencia informações sobre clientes, veículos, ordens de serviço, serviços realizados, peças utilizadas e mecânicos.

Entidades e Relacionamentos:
Cliente 🧑‍🤝‍🧑:

Armazena dados dos clientes, como nome, telefone, endereço e e-mail.
Relacionamento: Um cliente pode ter vários veículos.
Veículo 🚗:

Registra os veículos que pertencem aos clientes, com informações como modelo, placa e ano de fabricação.
Relacionamento: Cada veículo pode ter várias ordens de serviço.
Ordem de Serviço (OS) 📋:

Contém os detalhes das ordens de serviço, incluindo data de entrega e valor estimado.
Relacionamento: Cada ordem de serviço pode ter vários serviços e peças associadas.
Serviço 🛠️:

Representa os tipos de serviços realizados na oficina, como revisões, troca de óleo, etc.
Relacionamento: Cada serviço pode ser realizado em várias ordens de serviço e pode ser vinculado a um mecânico.
Peça ⚙️:

Armazena as peças utilizadas em cada ordem de serviço, incluindo nome, quantidade e preço.
Relacionamento: Cada peça pode ser associada a várias ordens de serviço.
Mecânico 👨‍🔧👩‍🔧:

Registra os dados dos mecânicos, como nome, especialidade, endereço e código de identificação.
Relacionamento: Um mecânico pode realizar vários serviços em diferentes ordens de serviço.
Relacionamentos entre Entidades:
Cliente (1) -> (N) Veículo: Um cliente pode ter vários veículos registrados.
Veículo (1) -> (N) Ordem de Serviço: Cada veículo pode gerar diversas ordens de serviço ao longo do tempo.
Ordem de Serviço (1) -> (N) Serviço: Cada ordem de serviço pode ter vários serviços associados.
Ordem de Serviço (1) -> (N) Peça: Uma ordem de serviço pode envolver o uso de várias peças.
Mecânico (1) -> (N) Serviço: Cada mecânico pode executar múltiplos serviços em várias ordens de serviço.
Tecnologias Utilizadas:
MySQL Workbench: Para o design e implementação do banco de dados, modelando as entidades e os relacionamentos descritos acima.
Benefícios Esperados:
Melhoria no gerenciamento das ordens de serviço e controle de estoque de peças.
Eficiência no cálculo de valores para serviços e peças, com base em dados integrados no sistema.
Maior controle das tarefas realizadas pelos mecânicos e a previsão de entrega dos veículos.
