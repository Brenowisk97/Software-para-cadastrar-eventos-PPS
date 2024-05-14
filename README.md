# Programa de Cadastro de Eventos-PPS
# 1-Entendimento do problema e definição do Escopo

Luiza é gerente de uma empresa de eventos que abrange uma ampla gama de atividades, desde pequenas reuniões corporativas até grandes festivais e shows. No entanto, ela está enfrentando desafios significativos ao tentar gerenciar manualmente todos esses eventos. As planilhas estão se tornando cada vez mais confusas e propensas a erros, e a falta de um programa eficaz está afetando negativamente a eficiência das operações.

Diante desses obstáculos, Luiza tomou a decisão de procurar um desenvolvedor para criar um programa personalizado que atenda às necessidades específicas de sua empresa. Ela está buscando uma solução abrangente que possibilite a criação e o armazenamento de eventos, a venda de ingressos, a busca por eventos, a atualização e exclusão de eventos, além da exibição de eventos.

Essa solução será essencial para simplificar e agilizar o processo de gerenciamento de eventos, permitindo que Luiza e sua equipe tenham uma visão clara e organizada de todas as atividades planejadas, contribuindo assim para o sucesso contínuo de sua empresa de eventos.

O Software não terá uma interface gráfica, sendo acessado apenas por meio de linhas de comando. Isso significa que todas as interações e operações serão realizadas por meio de comandos de texto, sem uma interface visual.

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
Optamos por utilizar a técnica de entrevistar a stakeholder, pois a entrevista facilita o contato direto entre o desenvolvedor e o stakeholder do produto, permitindo a obtenção de informações tácitas do entrevistado e proporcionando, consequentemente, uma compreensão mais profunda dos requisitos.

Esta Documentação será atualizada a cada revisão com a stakeholder do Projeto(Luiza), o primeiro encontro foi realizado em 16/04/2024 no qual o principal objetivo foi o levantamento dos requisitos do projeto e o próximo está marcado para 30/04/2024 no qual o principal objetivo será a entrega de uma versão útil do programa que possibilitará um feedback do stakeholder para possíveis alterações e melhoras do programa.

# Requisitos Funcionais
||Descrição|
|----|-------------|
|01| O programa deve permitir que o usuário consiga criar múltiplos eventos.|
|02| Os eventos devem ser armazenados durante toda a execução do programa em um arquivo Txt.|
|03| O programa deve permitir que o usuário consiga vender ingressos.|
|04| O programa deve permitir a busca de um evento pelo nome.|
|05| Deve ser possível excluir um evento já criado.|
|06|O programa deve permitir atualizar um evento criado, modificando a data e o local (os demais dados devem ser preservados).|
|07| Deve ser possível exibir todos os eventos cadastrados, exibindo nome, local e data do evento.|
|08| O programa deve incluir um calendário  que exiba todos os eventos programados e suas respectivas datas e horários, facilitando a visualização e o planejamento.|
|08| Os usuários devem receber notificações automáticas sobre eventos importantes, como confirmação de compra de ingressos, e lembretes o quando o evento estiver chegando.|


# Requisitos Não Funcionais
||Descrição|
|----|-------------|
|01| O sistema deve ser capaz de lidar eficientemente com um grande volume de eventos e operações, garantindo tempos de resposta rápidos para a criação, atualização, exclusão e exibição de eventos, mesmo em condições de carga elevada.|
|02| O tempo de persistência dos dados em arquivo deve ser otimizado, minimizando o impacto no desempenho geral do sistema durante a execução e encerramento do programa.|
|03| A interface de texto deve ser responsiva e fluída, proporcionando uma experiência de usuário ágil, mesmo em terminais com recursos limitados.|
|04| O tratamento de exceções deve ser eficiente, garantindo que as operações do sistema não sejam prejudicadas por situações de erro inesperadas, e que as mensagens de erro sejam claras e informativas para o usuário.|
|05|O sistema deve ser desenvolvido de forma eficiente em termos de custo, considerando o orçamento disponível para o projeto (R$ 5.000) e minimizando os custos de manutenção e operação ao longo do tempo.|

# 3-Documentação dos Requisitos
 Decidimos por usar histórias de usuário com critérios de aceitação para descrever os requisitos do programa de cadastro de eventos de forma mais adequada. Isso se deve à necessidade de detalhar os requisitos apresentados em cada história, permitindo uma compreensão clara das funcionalidades e comportamentos esperados do sistema.

# História 1: Criação de Eventos
Como usuário do sistema, eu gostaria de criar múltiplos eventos, para que eu possa organizar e gerenciar diferentes atividades.
Critérios de Aceitação: O usuário deve ter a opção de criar um novo evento no sistema, o sistema deve permitir que o usuário insira informações detalhadas sobre o evento, como data, local, tipo de evento e informações adicionais relevantes e após a criação, o evento deve ser armazenado de forma persistente no sistema.


# História 2: Venda de Ingressos
Como usuário do sistema durante a venda de ingressos, eu gostaria de poder escolher o evento desejado, para que eu possa comprar ingressos para eventos específicos.
Critérios de Aceitação: Durante o processo de venda de ingressos, o sistema deve exibir uma lista de eventos disponíveis para escolha, o usuário deve ser capaz de selecionar o evento desejado a partir da lista apresentada, após a escolha do evento, o sistema deve prosseguir com o processo de venda de ingressos.

# História 3: Busca de Eventos
Como usuário do sistema, eu gostaria de buscar um evento pelo nome, para que eu possa encontrar rapidamente informações específicas sobre um evento.
Critérios de Aceitação: O sistema deve fornecer uma funcionalidade de busca onde o usuário pode inserir o nome do evento desejado e após a busca, o sistema deve exibir os eventos correspondentes ao nome inserido pelo usuário.

# História 4: Exclusão de Eventos
Como usuário do sistema, eu gostaria de excluir um evento já criado, para que eu possa remover eventos desnecessários ou cancelados.
Critérios de Aceitação: O sistema deve fornecer uma opção para excluir um evento existente e ao selecionar a opção de exclusão, o sistema deve solicitar a confirmação do usuário antes de remover permanentemente o evento.

# História 5: Atualização de Eventos
Como usuário do sistema, eu gostaria de atualizar um evento já criado, modificando a data e o local, para que eu possa corrigir informações erradas ou alterar detalhes do evento.
Critérios de Aceitação: O sistema deve permitir que o usuário selecione o evento que deseja atualizar , após a seleção, o usuário deve ter a opção de modificar a data e/ou local do evento, as demais informações do evento devem ser preservadas sem alterações.

# História 6: Exibição de Eventos
Como usuário do sistema, eu gostaria de visualizar uma lista de todos os eventos cadastrados, para que eu possa ter uma visão geral completa das atividades.
Critérios de Aceitação: O sistema deve fornecer uma funcionalidade que exiba todos os eventos cadastrados e a lista de eventos deve ser apresentada de forma clara e organizada, mostrando informações relevantes de cada evento.

# História 6: Notificações automáticas
Como gestor de eventos, eu gostaria que os usuários recebessem automaticamente confirmações de compra de ingressos e lembretes sobre os eventos para garantir uma experiência sem problemas.
Critérios de Aceitação: O sistema deve enviar notificações por e-mail ou mensagem para os usuários após a compra de ingressos e antes do evento programado.



