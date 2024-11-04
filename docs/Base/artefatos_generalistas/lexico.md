# Léxicos

## Introdução

Sendo um documento fundamental na engenharia de requisitos, especialmente nas fases iniciais do desenvolvimento de um novo projeto de software, o artefato Léxico funciona como repositório de termos e expressões relevantes, organizados de forma a garantir que todos que estejam envolvidos na criação do software possam compartilhar uma visão comum do domínio e das funcionalidades da aplicação. Este artefato busca atuar como um glossário formalizado, capaz de reduzir ambiguidades e, consequentemente, garantir um produto final mais próximo das expectativas dos clientes.

Além de conseguir promover uma compreensão mais uniforme sobre o projeto, o artefato léxico também contribui para a documentação de conhecimento sobre o domínio da aplicação, auxiliando assim a transição de informações equipes ou em futuras fases de manutenção.

## Metodologia

Os léxicos da aplicação Agenda foram identificados a partir de um estudo das necessidades dos usuários dentro de aplicações semelhantes. As informações sobre o léxico da aplicação foram organizadas em um formato único de tabela, seguindo uma padronização conforme mostrado na tabela abaixo:

| Léxico                  | Descrição             | Sinônimo             | Classificação       | Relacionamentos              | Fonte              |
| ----------------------- | --------------------- | -------------------- | ------------------- | ---------------------------- | ------------------ |
| Código - Nome do léxico | Descrição do léxico   | Sinônimo             | Verbo/Objeto/Estado | Relações que o léxico possui | Pessoa responsável |

<div style="text-align: center">
<p><b>Tabela 1:</b> Modelo dos léxicos (Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024).</p>
</div>

## Objetos

Os léxicos do tipo objeto referem-se às entidades, elementos ou objetos que são manipulados ou sobre os quais as ações são realizadas dentro da aplicação. Na tabela 2, é possível verificar os principais léxicos classificados como objetos que foram identificados para a aplicação Agenda.

| Léxico         | Descrição             | Sinônimo             | Classificação       | Relacionamentos              | Fonte              |
| -------------- | --------------------- | -------------------- | ------------------- | ---------------------------- | ------------------ |
| L01 - Compromisso    | Evento com data e horário definidos, que representa uma reunião, encontro ou atividade que o usuário deve cumprir. | Evento, Encontro | Objeto | Relacionado com: "Data", "Horário", "Notificação", "Usuário". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L02 - Tarefa         | Atividade a ser realizada, geralmente com prazo específico, mas sem horário fixo. | Atividade | Objeto | Relacionado com: "Data", "Categoria", "Prioridade". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L03 - Categoria      | Classificação atribuída a compromissos ou tarefas para facilitar a organização. | Etiqueta, Tag | Objeto | Relacionado com: "Compromisso", "Tarefa". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L04 - Notificação    | Alerta enviado ao usuário para lembrá-lo de um compromisso ou tarefa próximo do horário de execução. | Lembrete | Objeto | Relacionado com: "Compromisso", "Horário", "Usuário". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L05 - Usuário        | Pessoa que utiliza a aplicação para organizar seus compromissos e tarefas. | - | Objeto | Relacionado com: "Compromisso", "Tarefa", "Notificação". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L06 - Agenda         | Visualização organizada dos compromissos e tarefas ao longo do tempo, exibindo datas e horários. | Calendário, Cronograma | Objeto | Relacionado com: "Compromisso", "Tarefa", "Usuário". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L07 - Lista de tarefas | Visualização específica que organiza todas as tarefas, permitindo acompanhar o progresso e marcar tarefas concluídas. | To-do list | Objeto | Relacionado com: "Tarefa", "Prioridade", "Status de Conclusão". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L08 - Evento Recorrente | Compromisso ou tarefa que se repete de acordo com uma frequência definida, como diariamente ou semanalmente. | Repetição | Objeto | Relacionado com: "Compromisso", "Data". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L09 - Notas | Informações adicionais associadas a compromissos ou tarefas, usadas para registrar detalhes importantes ou lembretes adicionais. | Comentário, Anotação | Objeto | Relacionado com: "Compromisso", "Tarefa". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L10 - Localização | Endereço ou ponto de referência associado a um compromisso, especialmente útil para compromissos presenciais. | Local | Objeto | Relacionado com: "Compromisso", "Agenda". | [Gabriel Souza](https://github.com/GabrielMS00) |

<div style="text-align: center">
<p><b>Tabela 2:</b> Léxicos com classificação Objeto (Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024).</p>
</div>

## Verbos

Os léxicos do tipo verbo representam ações ou operações que os usuários podem executar dentro da aplicação da Agenda. Essas ações detalham as funcionalidades acessíveis para os usuários, permitindo interações específicas e operações dentro do sistema. Na tabela 3, é possível conferir os principais léxicos classificados como verbos que foram identificados.

| Léxico           | Descrição             | Sinônimo             | Classificação       | Relacionamentos              | Fonte              |
| ---------------- | --------------------- | -------------------- | ------------------- | ---------------------------- | ------------------ |
| L11 - Adicionar  | Ação de incluir um novo compromisso, tarefa ou nota na agenda, com todas as informações relevantes. | Incluir, Criar | Verbo | Relacionado com: "Compromisso", "Tarefa", "Agenda". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L12 - Editar     | Ação de modificar um compromisso ou tarefa existente, permitindo atualizar informações como data, horário, prioridade, etc. | Alterar, Atualizar | Verbo | Relacionado com: "Compromisso", "Tarefa", "Categoria". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L13 - Excluir    | Ação de remover um compromisso ou tarefa da agenda, eliminando-o definitivamente. | Apagar, Remover | Verbo | Relacionado com: "Compromisso", "Tarefa", "Agenda". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L14 - Visualizar | Ação de acessar os detalhes de um compromisso ou tarefa, exibindo informações completas para o usuário. | Consultar, Ver | Verbo | Relacionado com: "Compromisso", "Tarefa", "Notificação". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L15 - Marcar como concluído | Ação de indicar que uma tarefa foi finalizada, atualizando seu estado para refletir que não é mais pendente. | Finalizar, Completar | Verbo | Relacionado com: "Tarefa", "Prioridade". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L16 - Configurar | Ação de ajustar as preferências de notificação, repetição e outras configurações da agenda conforme as preferências do usuário. | Ajustar, Personalizar | Verbo | Relacionado com: "Notificação", "Repetição", "Usuário". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L17 - Reagendar | Ação de alterar a data ou horário de um compromisso ou tarefa, mantendo outras informações. | Alterar data, Remarcar | Verbo | Relacionado com: "Compromisso", "Horário", "Data". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L18 - Pesquisar | Ação de buscar compromissos, tarefas ou notas na agenda com base em termos específicos ou filtros. | Buscar, Localizar | Verbo | Relacionado com: "Agenda", "Tarefa", "Categoria". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L19 - Ordenar | Ação de organizar compromissos ou tarefas por critérios como data, prioridade, ou categoria. | Classificar | Verbo | Relacionado com: "Agenda", "Tarefa", "Prioridade". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L20 - Sincronizar | Ação de atualizar a agenda com dados de outros dispositivos ou aplicativos para mantê-la consistente e atualizada. | Atualizar | Verbo | Relacionado com: "Agenda", "Usuário". | [Gabriel Souza](https://github.com/GabrielMS00) |

<div style="text-align: center">
<p><b>Tabela 3:</b> Léxicos com classificação Verbo (Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024).</p>
</div>

## Estados

Os léxicos do tipo estado referem-se às condições, situações ou configurações específicas que podem ocorrer dentro da aplicação.  Esses estados representam diversos cenários em que o usuário ou o sistema pode se encontrar durante a interação com o sistema. Na Tabela 4, é possível verificar os principais léxicos classificados como estados que foram identificados.

| Léxico | Descrição | Sinônimo | Classificação | Relacionamentos | Fonte |
| :-: | :-: | :-: | :-: | :-: | :-: |
| L21 - Prioridade | Nível de importância ou urgência atribuído a uma tarefa, indicando a ordem em que deve ser realizada. | Nível de Urgência | Estado | Relacionado com: "Tarefa", "Categoria". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L22 - Data | Dia específico associado a um compromisso ou prazo de uma tarefa. | - | Estado | 	Relacionado com: "Compromisso", "Tarefa", "Horário". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L23 - Horário | Hora específica associada a um compromisso ou notificação, indicando o momento em que deve ocorrer. | Tempo, Momento | Estado | Relacionado com: "Compromisso", "Notificação". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L24 - Repetição | Configuração que permite que um compromisso ou tarefa se repita automaticamente em intervalos definidos, como diariamente ou semanalmente. | Recorrência | Estado | Relacionado com: "Compromisso", "Tarefa". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L25 - Status de Conclusão | Condição de uma tarefa que indica se ela está concluída ou pendente. | Estado de Finalização | Estado | Relacionado com: "Tarefa", "Prioridade". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L26 - Atraso | Estado em que uma tarefa ou compromisso ultrapassa a data ou horário planejado sem ter sido concluído ou atendido. | Em atraso | Estado | Relacionado com: "Tarefa", "Horário", "Data". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L27 - Disponível | Estado de uma janela de tempo na agenda em que o usuário não possui compromissos ou tarefas agendadas, indicando espaço livre. | Livre | Estado | Relacionado com: "Agenda", "Usuário". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L28 - Ocupado | Estado que indica que o usuário tem compromissos ou tarefas agendados para uma data ou horário específicos, impossibilitando novas atividades. | Indisponível | Estado | Relacionado com: "Agenda", "Compromisso". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L29 - Férias | 	Período de tempo em que o usuário está indisponível para compromissos, normalmente devido a um período de descanso planejado. | Pausa, Descanso | Estado | Relacionado com: "Usuário", "Compromisso". | [Gabriel Souza](https://github.com/GabrielMS00) |
| L30 - Pessoal | Status de uma tarefa ou compromisso que indica ser um item privado e, em alguns casos, visível apenas ao próprio usuário. | Privado | Estado | Relacionado com: "Categoria", "Agenda". | [Gabriel Souza](https://github.com/GabrielMS00) | 

<div style="text-align: center">
<p><b>Tabela 4:</b> Léxicos com classificação Estado (Autor: <a href="https://github.com/GabrielMS00">Gabriel Souza</a>, 2024).</p>
</div>

## Bibliografia

> SERRANO, Milene. Requisitos - Aula 10. Local: UnB-FGA, Gama, DF. Apresentação de Power Point. 35, color. Disponível em: [Requisitos - Aula 10](https://aprender3.unb.br/pluginfile.php/2845027/mod_resource/content/1/Aula%2010.pdf).

## Histórico de Versões

|Versão|Data|Descrição|Autor(es)|Data de revisão|Revisor(es)|
|:----:|:----:|:---------:|:-----:|:-----:|:-------:|
|`1.0` | 03/11/2024 | Criação do documento e adição dos lexicos. | [Gabriel Souza](https://github.com/GabrielMS00) | 03/11/2024  |  [Bianca Castro](https://github.com/BiancaPatrocinio7)  |
