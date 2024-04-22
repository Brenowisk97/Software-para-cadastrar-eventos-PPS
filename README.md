# Programa-para-cadastrar-eventos-PPS
# 1-Entendimento-do-problema-e-definição-do-Escopo
Luiza é gerente de uma empresa de eventos que organiza uma variedade de atividades, desde pequenas reuniões corporativas até grandes festivais e shows. Ela está enfrentando dificuldades para acompanhar o gerenciamento de todos os eventos de forma manual. As planilhas estão se tornando confusas e propensas a erros, e a falta de um sistema centralizado está afetando a eficiência das operações. Luiza decidiu procurar um desenvolvedor para criar um programa sob medida que atenda às necessidades específicas de sua empresa. Ela deseja uma solução que permita:Criação e Armazenamento de Eventos, Venda de Ingressos, Busca de Eventos, Atualização e Exclusão de Eventos e Exibição de Eventos.

# Criação e Armazenamento de Eventos
Luiza quer poder criar e armazenar informações detalhadas sobre cada evento, incluindo data, local, tipo de evento e informações adicionais relevantes.
# Venda de Ingressos
É essencial para Luiza que o sistema permita a venda de ingressos de forma eficiente durante a execução do evento. Ela quer que os clientes possam escolher facilmente o evento desejado ao comprar os ingressos.
# Busca de Eventos
Como Luiza lida com muitos eventos, ela precisa de uma maneira rápida e fácil de encontrar informações específicas sobre um evento. Portanto, a capacidade de buscar eventos pelo nome é fundamental.
# Atualização e Exclusão de Eventos
Luiza precisa da flexibilidade de atualizar ou excluir eventos conforme necessário. Ela deseja poder modificar detalhes como data e local, mantendo os demais dados do evento intactos.
# Exibição de Eventos
Para garantir uma visão geral completa de todos os eventos, Luiza quer poder visualizar uma lista de todos os eventos cadastrados no sistema.

# 2-Levantamento dos Requisitos
Optamos por utilizar a técnica de entrevistar o stakeholder, pois a entrevista facilita o contato direto entre o desenvolvedor e o stakeholder do produto, permitindo a obtenção de informações tácitas do entrevistado e proporcionando, consequentemente, uma compreensão mais profunda dos requisitos.

Esta Documentação será atualizada a cada revisão com o stakeholder do Projeto(Luiza), o primeiro encontro foi realizado em 16/04/2024 no qual o principal objetivo foi o levantamento dos requisitos do projeto e o próximo está marcado para 30/04/2024 no qual o principal objetivo será a entrega de uma versão útil do programa que possibilitará um feedback do stakeholder para possíveis alterações e melhoras do programa.

# Requisitos Funcionais
-O programa deve permitir a criação de múltiplos eventos.

- Os eventos devem ser armazenados durante toda a execução do programa.

- Durante a venda do ingresso, o usuário deve poder escolher o evento desejado.

- O programa deve permitir a busca de um evento pelo nome.

- Deve ser possível excluir um evento já criado.

- programa deve permitir atualizar um evento criado, modificando a data e o local (os demais dados devem ser preservados).

- Deve ser possível exibir todos os eventos cadastrados.

# Requisitos Não Funcionais
- O sistema deve ser capaz de lidar eficientemente com um grande volume de eventos e operações, garantindo tempos de resposta rápidos para a criação, atualização, exclusão e exibição de eventos, mesmo em condições de carga elevada.

- O tempo de persistência dos dados em arquivo deve ser otimizado, minimizando o impacto no desempenho geral do sistema durante a execução e encerramento do programa.

- A interface de texto deve ser responsiva e fluída, proporcionando uma experiência de usuário ágil, mesmo em terminais com recursos limitados.

- O tratamento de exceções deve ser eficiente, garantindo que as operações do sistema não sejam prejudicadas por situações de erro inesperadas, e que as mensagens de erro sejam claras e informativas para o usuário.
