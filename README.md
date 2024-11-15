🚗🔧 Escopo do Sistema de Controle de Ordens de Serviço - Oficina Mecânica 💼📊
Objetivo do Projeto:
O objetivo deste projeto é o desenvolvimento de um sistema de controle e gerenciamento de ordens de serviço para uma oficina mecânica. O sistema tem como propósito otimizar a gestão das ordens de serviço (OS), o controle de clientes, veículos, serviços realizados, peças utilizadas e os mecânicos responsáveis pelas manutenções. Com isso, a oficina poderá agilizar o atendimento, melhorar o controle financeiro e garantir uma comunicação mais eficiente entre os clientes e a equipe de mecânicos.

Escopo Funcional:
Cadastro de Clientes 🧑‍🤝‍🧑:

Armazenamento de informações detalhadas sobre os clientes da oficina, como nome, telefone, e-mail e endereço.
Cadastro de Veículos 🚗:

Registro de veículos, incluindo dados como modelo, placa, ano de fabricação e histórico de manutenção.
Ordens de Serviço (OS) 📋:

Criação de ordens de serviço que incluem os serviços solicitados, peças necessárias e a previsão de entrega do veículo.
Cálculo de valores com base na tabela de mão de obra e no valor das peças.
Cadastro de Serviços 🛠️:

Tipos de serviços oferecidos pela oficina (ex.: troca de óleo, revisão geral, alinhamento, etc.).
Relacionamento das ordens de serviço com os serviços que serão realizados.
Cadastro de Peças ⚙️:

Registro de peças que serão utilizadas nas ordens de serviço, incluindo preço e quantidade disponível.
Mecânicos 👨‍🔧👩‍🔧:

Informações sobre os mecânicos, incluindo código, nome, especialidade e endereço.
Atribuição de mecânicos às ordens de serviço de acordo com a especialidade.
Relatórios 📈:

Geração de relatórios de ordens de serviço, clientes atendidos, serviços realizados e peças utilizadas.
Relacionamento entre Entidades:
Cliente (1) -> (N) Veículo: Um cliente pode ter vários veículos.
Veículo (1) -> (N) Ordem de Serviço: Um veículo pode ter várias ordens de serviço.
Ordem de Serviço (1) -> (N) Serviço: Cada ordem de serviço pode conter vários serviços.
Ordem de Serviço (1) -> (N) Peça: Cada ordem de serviço pode incluir várias peças.
Mecânico (1) -> (N) Serviço: Cada mecânico pode executar diversos serviços em várias ordens de serviço.
