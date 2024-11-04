## Introdução

O cenário é uma técnica que ajuda a entender e documentar como o sistema será utilizado em diferentes situações ou contextos. Ele consiste em narrativas detalhadas que descrevem uma sequência de eventos ou interações entre os usuários e o sistema, simulando casos de uso específicos e reais. Essa técnica é útil porque permite que os envolvidos (como analistas, desenvolvedores, e clientes) visualizem e compreendam como o sistema deve se comportar em diferentes situações. Os cenários ajudam a identificar requisitos específicos, incluindo requisitos funcionais e não funcionais também. Dessa forma, este artefato se torna bastante valioso para o sistema de Agenda online.

## Metodologia

Os cenários foram elaborados seguindo as seguintes etapas:

1. **Identificação do Objetivo:** Definir o objetivo principal do cenário, ou seja, o que o usuário busca alcançar com a ação.
2. **Definição do Contexto:** Descrever a situação, o contexto e as necessidades do usuário no cenário.
3. **Ator Principal:** Identificar o ator principal que protagoniza a ação no cenário.
4. **Recursos:** Listar os recursos e ferramentas que o usuário utiliza no cenário.
5. **Episódios:** Descrever os passos que o usuário realiza dentro da aplicação.
6. **Restrições:**  Identificar as limitações, condicionantes ou requisitos específicos do cenário.
7. **Resultado Esperado:** Descrever o resultado que o usuário busca alcançar com a ação no cenário.

## Cenários

**Persona 1: Paulo Henrique da Silva (Estudante de Medicina)**

### Cenário 1: Agendando Provas e Estudos

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Paulo precisa organizar seu cronograma de estudos e provas, incluindo horários de aula, datas de provas e tempo para seus hobbies.                                                                                                  |
| **Contexto**        | Paulo está em seu primeiro ano de medicina e precisa se organizar para não perder tempo com as tarefas da faculdade e ter tempo livre para suas atividades.                                                                         |
| **Atores**          | Paulo (usuário), Sistema da agenda online.                                                                                                                                                                                          |
| **Recursos**        | Computador, acesso à internet.                                                                                                                                                                                                      |
| **Episódios**       | 1. Paulo faz login na plataforma da agenda online.<br> 2. Ele escolhe o modo de visualização semanal.<br> 3. Paulo cria um novo evento chamado "Prova de Anatomia" com data e horário.<br> 4. Ele adiciona uma tarefa chamada "Estudar para prova de Anatomia" com prazo de uma semana.<br> 5. Paulo cria outro evento chamado "Aula de Fisiologia" com data e horário.<br> 6. Ele define a tarefa "Estudar Fisiologia" com prazo de dois dias, como dependência da tarefa "Estudar para prova de Anatomia".<br> 7. Paulo adiciona um evento "Corrida no Parque" com data e horário.<br> 8. Ele configura um lembrete para "Prova de Anatomia" dois dias antes da data.<br> 9. Paulo salva o cronograma da semana. |
| **Restrições**      | Paulo deve se lembrar de verificar o cronograma semanalmente para fazer alterações.<br> A agenda deve ser fácil de usar para que ele possa ajustar o cronograma conforme necessário.                                                |
| **Resultado Esperado** | Paulo consegue organizar seu cronograma de estudos de forma eficiente, visualizando suas tarefas e provas na semana e recebendo lembretes antecipados.                                                                          |


### Cenário 2: Equilibrando Vida Acadêmica e Pessoal

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Paulo precisa reservar tempo para seus hobbies sem deixar de cumprir as responsabilidades da faculdade.                                                                                                                             |
| **Contexto**        | Paulo busca um equilíbrio entre os estudos e sua vida pessoal, garantindo tempo para correr no parque e se divertir com a família.                                                                                                 |
| **Atores**          | Paulo (usuário), Sistema da agenda online.                                                                                                                                                                                          |
| **Recursos**        | Computador, acesso à internet.                                                                                                                                                                                                      |
| **Episódios**       | 1. Paulo acessa a agenda online e escolhe o modo de visualização mensal.<br> 2. Ele configura um evento "Visita à Família" com data e horário.<br> 3. Paulo define a tarefa "Estudar para prova de Histologia" como dependência do evento "Visita à Família".<br> 4. Paulo cria outro evento "Corrida no Parque" com data e horário, definindo a tarefa "Estudar para prova de Histologia" como dependência deste.<br> 5. Ele define um lembrete para o evento "Visita à Família" dois dias antes da data.<br> 6. Paulo salva o cronograma do mês. |
| **Restrições**      | O sistema deve permitir que Paulo defina eventos e tarefas como dependentes, garantindo que ele consiga dedicar tempo para seus hobbies sem prejudicar os estudos.<br> Paulo deve se lembrar de verificar o cronograma mensalmente para realizar alterações.                                                |
| **Resultado Esperado** | Paulo consegue conciliar seus compromissos com a faculdade, as atividades esportivas e o tempo com sua família de forma equilibrada, utilizando a agenda para garantir a organização e lembretes.                                                                          |


**Persona 2: Ana Alice Costa (CEO de uma Startup)**

### Cenário 3: Reunindo a Equipe

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Ana Alice precisa agendar uma reunião com sua equipe para alinhar os objetivos estratégicos da empresa e acompanhar o progresso dos projetos.                                                                                       |
| **Contexto**        | Ana Alice é uma CEO que precisa garantir o bom funcionamento da empresa e manter uma comunicação eficaz com sua equipe.                                                                                                            |
| **Atores**          | Ana Alice (usuário), Sistema da agenda online, membros da equipe (usuários).                                                                                                                                                        |
| **Recursos**        | Computador, acesso à internet, aplicativo de videoconferência.                                                                                                                                                                      |
| **Episódios**       | 1. Ana Alice faz login na plataforma da agenda online.<br> 2. Ela cria um novo evento chamado "Reunião Estratégica" com data e horário.<br> 3. Ana Alice configura um lembrete para "Reunião Estratégica" dois dias antes da data.<br> 4. Ela adiciona um link para uma sala de videoconferência ao evento.<br> 5. Ana Alice compartilha o evento com a equipe.<br> 6. Os membros da equipe recebem uma notificação com o convite para a reunião.<br> 7. Ana Alice acessa o evento na data e horário marcados para se reunir com a equipe. |
| **Restrições**      | A agenda online deve permitir a criação de eventos e tarefas com links para outros aplicativos.<br> Ana Alice precisa se lembrar de verificar a lista de eventos para garantir que todos os membros da equipe estejam cientes das reuniões.                                                |
| **Resultado Esperado** | Ana Alice consegue agendar uma reunião com sua equipe de forma eficiente, garantindo que todos os membros estejam cientes da data e hora do evento e com acesso ao link da sala de videoconferência.                                                                          |


### Cenário 4: Priorizando Tarefas

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Ana Alice precisa organizar suas tarefas e eventos, definindo prioridades e compromissos mais importantes.                                                                                                                         |
| **Contexto**        | Ana Alice é uma CEO que precisa gerenciar seu tempo de forma eficiente e garantir que seus compromissos e projetos mais importantes não sejam esquecidos.                                                                          |
| **Atores**          | Ana Alice (usuário), Sistema da agenda online.                                                                                                                                                                                     |
| **Recursos**        | Computador, acesso à internet.                                                                                                                                                                                                      |
| **Episódios**       | 1. Ana Alice faz login na plataforma da agenda online.<br> 2. Ela cria um novo evento chamado "Apresentação para Investidores" com data e horário.<br> 3. Ana Alice define a prioridade do evento como "Alta".<br> 4. Ela cria uma tarefa chamada "Preparar slides para apresentação" com prazo de uma semana e define a prioridade como "Alta".<br> 5. Ana Alice cria outra tarefa chamada "Enviar proposta para novos investidores" com prazo de três dias e define a prioridade como "Média".<br> 6. Ela configura um lembrete para "Apresentação para Investidores" dois dias antes da data.<br> 7. Ana Alice salva o cronograma da semana. |
| **Restrições**      | A agenda online deve permitir a definição de prioridades para tarefas e eventos.<br> Ana Alice precisa se lembrar de verificar o cronograma semanalmente para fazer alterações.                                                    |
| **Resultado Esperado** | Ana Alice consegue organizar suas tarefas e eventos de forma eficiente, definindo prioridades e garantindo que os compromissos e projetos mais importantes não sejam esquecidos.                                               |



**Persona 3: Eduardo Mendes (Advogado)**

### Cenário 5: Agendando Audiências

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Eduardo precisa organizar seu cronograma de audiências e reuniões com clientes.                                                                                                                                                     |
| **Contexto**        | Eduardo é um advogado que precisa gerenciar seu tempo e evitar conflitos de horários em seu dia a dia.                                                                                                                             |
| **Atores**          | Eduardo (usuário), Sistema da agenda online.                                                                                                                                                                                        |
| **Recursos**        | Computador, acesso à internet.                                                                                                                                                                                                      |
| **Episódios**       | 1. Eduardo faz login na plataforma da agenda online.<br> 2. Ele escolhe a visualização semanal.<br> 3. Eduardo cria um novo evento chamado "Audiência no Tribunal" com data e horário.<br> 4. Ele adiciona informações sobre o caso, como o número do processo e o nome do cliente.<br> 5. Eduardo configura um lembrete para "Audiência no Tribunal" dois dias antes da data.<br> 6. Ele cria um evento chamado "Reunião com Cliente - Caso X" com data e horário.<br> 7. Eduardo adiciona informações sobre o cliente, como endereço, telefone e preferências.<br> 8. Ele salva o cronograma da semana. |
| **Restrições**      | Eduardo precisa se lembrar de verificar o cronograma semanalmente para fazer alterações.<br> A agenda deve permitir a edição de informações sobre o caso, incluindo dados sobre o cliente, como endereço, telefone e preferências. |
| **Resultado Esperado** | Eduardo consegue organizar seu cronograma de trabalho de forma eficiente, garantindo que ele esteja presente em todas as audiências e reuniões com clientes, além de ter acesso a informações importantes.                       |


### Cenário 6: Colaborando com a Equipe

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Eduardo precisa compartilhar seu cronograma de audiências e reuniões com sua equipe para que todos estejam cientes.                                                                                                                |
| **Contexto**        | Eduardo trabalha em um escritório de advocacia e precisa manter a equipe informada sobre suas atividades e eventos.                                                                                                                |
| **Atores**          | Eduardo (usuário), Sistema da agenda online, membros da equipe (usuários).                                                                                                                                                          |
| **Recursos**        | Computador, acesso à internet.                                                                                                                                                                                                      |
| **Episódios**       | 1. Eduardo faz login na plataforma da agenda online.<br> 2. Ele compartilha seu cronograma de audiências e reuniões com sua equipe.<br> 3. Os membros da equipe recebem uma notificação com o convite para visualização.<br> 4. Eduardo visualiza o cronograma da equipe para verificar eventos e compromissos de todos. |
| **Restrições**      | A agenda online deve permitir o compartilhamento do cronograma com a equipe.<br> Eduardo precisa se lembrar de verificar as atualizações no cronograma da equipe.                                                                  |
| **Resultado Esperado** | Eduardo consegue compartilhar seu cronograma de trabalho com sua equipe de forma eficiente, garantindo que todos estejam cientes de suas atividades e eventos.                                                                  |

**Persona 4: Juliana Pontes (Diarista)**

### Cenário 7: Agendando Compromissos com Clientes

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Juliana precisa organizar seu cronograma de trabalho para evitar conflitos de horários com seus clientes e lembrar de todos os detalhes.                                                                                           |
| **Contexto**        | Juliana trabalha em várias residências durante a semana e precisa se organizar para não esquecer de nenhum compromisso e atender todos seus clientes.                                                                              |
| **Atores**          | Juliana (usuário), Sistema da agenda online.                                                                                                                                                                                       |
| **Recursos**        | Smartphone, acesso à internet.                                                                                                                                                                                                     |
| **Episódios**       | 1. Juliana faz login na plataforma da agenda online.<br> 2. Ela escolhe o modo de visualização semanal.<br> 3. Juliana cria um novo evento chamado "Limpeza na casa da Sra. Maria" com data e horário.<br> 4. Ela adiciona informações sobre a Sra. Maria, como o endereço e telefone, além de detalhes sobre o tipo de limpeza a ser realizada.<br> 5. Juliana configura um lembrete para "Limpeza na casa da Sra. Maria" um dia antes da data.<br> 6. Ela cria outro evento chamado "Limpeza na casa do Sr. João" com data e horário, adicionando informações sobre o Sr. João.<br> 7. Juliana salva o cronograma da semana. |
| **Restrições**      | Juliana precisa se lembrar de verificar o cronograma semanalmente para fazer alterações e garantir que não tenha conflitos.<br> A agenda deve permitir a edição de informações sobre os clientes, incluindo endereço, telefone e observações sobre as preferências de cada um. |
| **Resultado Esperado** | Juliana consegue organizar seu cronograma de trabalho de forma eficiente, evitando conflitos de horários e lembrando-se de todos os detalhes importantes de seus clientes.                                                     |


### Cenário 8: Recebendo Lembretes

| **Item**            | **Descrição**                                                                                                                                                                                                                       |
|---------------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Objetivo**        | Juliana precisa receber lembretes sobre seus compromissos para evitar esquecimentos e atrasos.                                                                                                                                      |
| **Contexto**        | Juliana é uma diarista que precisa se organizar para não perder seus compromissos com os clientes.                                                                                                                                  |
| **Atores**          | Juliana (usuário), Sistema da agenda online.                                                                                                                                                                                       |
| **Recursos**        | Smartphone, acesso à internet.                                                                                                                                                                                                     |
| **Episódios**       | 1. Juliana faz login na plataforma da agenda online e configura as notificações.<br> 2. Ela configura a opção de receber lembretes por email um dia antes do compromisso.<br> 3. Juliana cria um novo evento chamado "Limpeza na casa do Sr. Carlos" com data e horário.<br> 4. Ela configura um lembrete para "Limpeza na casa do Sr. Carlos" um dia antes da data.<br> 5. Juliana salva o cronograma.<br> 6. No dia anterior ao compromisso, Juliana recebe um email com o lembrete sobre o evento "Limpeza na casa do Sr. Carlos". |
| **Restrições**      | O sistema deve permitir a personalização das notificações, com opções de escolha de canal (email, notificação no aplicativo) e tempo de antecedência.<br> Juliana precisa se lembrar de configurar as notificações de acordo com suas preferências e verificar o cronograma para confirmar os eventos. |
| **Resultado Esperado** | Juliana consegue receber lembretes sobre seus compromissos e evitar esquecimentos e atrasos.                                                                                                                                    |

## Recursos e Funcionalidades Extras:

* **Integração com outros aplicativos:** A agenda online pode integrar com outras ferramentas como Google Workspace, Teams e Trello, além de assistentes de voz e inteligência artificial, para agendar compromissos, definir prioridades, criar links de reuniões e enviar notificações programadas.
* **Visualização de tarefas:** Permite a visualização das atividades do dia em um Kanban, como o Trello.
* **Compartilhamento:** Permite a opção de compartilhar a agenda com assistentes, colegas, permitindo uma gestão colaborativa de compromissos.
* **Relatórios e Insights:** Gera relatórios personalizados para visualizar o uso de tempo, como a quantidade de tempo dedicada a cada atividade, e identificar áreas de oportunidade para melhorar a produtividade.

## Considerações:

* A agenda online deve ser intuitiva, fácil de usar e acessível em qualquer dispositivo.
* A plataforma deve oferecer opções de personalização para atender às necessidades de cada usuário.
* É fundamental garantir a segurança e privacidade das informações dos usuários.
* A agenda online deve ser compatível com diferentes sistemas operacionais e navegadores.

## Bibliografia
> </a> Requisitos de Software. Bilheteria Digital (2023.1). Disponível em: [https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital](https://github.com/Requisitos-de-Software/2023.1-BilheteriaDigital). Acesso em: 15 mai. 2024.


|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0` | 03/11/2024 | Criação do documento | [Gabriel Moura](https://github.com/thegm445) | 03/11/2024  |  [Bianca Castro](https://github.com/BiancaPatrocinio7)  |
|`1.1` | 03/11/2024 | Adição de informação e padronização da estrutura | [Gabriel Souza](https://github.com/GabrielMS00) | 03/11/2024 | [Hugo Queiroz](https://github.com/melohugo) |
