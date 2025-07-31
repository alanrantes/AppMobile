# Especificação do projeto

## Definição do problema

<p align="justify">O principal problema identificado durante minha experiência como jovem aprendiz na Stellantis foi a dificuldade de acesso rápido a informações e processos industriais, uma vez que a maioria dos sistemas internos estava disponível apenas em plataformas desktop. Isso resultava em atrasos frequentes, já que colaboradores precisavam estar próximos de um computador ou carregar um notebook constantemente para executar tarefas simples ou consultar dados. Essa dependência dificultava a agilidade operacional e a tomada de decisões em tempo real.</p>

## Solução

<p align="justify">A solução proposta é o desenvolvimento de um aplicativo mobile voltado para a gestão industrial, com funcionalidades que otimizam processos internos e eliminam a necessidade de acesso exclusivo via desktop. O aplicativo centraliza informações importantes, permite coleta de dados diretamente no chão de fábrica e fornece ferramentas para consulta e análise de forma rápida e prática, utilizando um dispositivo que todos já carregam: o smartphone.
</p>

<p align="justify">Dessa forma, busca-se reduzir a dependência de notebooks, melhorar a eficiência operacional e agilizar a comunicação entre as áreas.</p>

## Ferramentas e Técnicas

- **Diagrama de Personas:** Representação dos perfis dos usuários-alvo da aplicação.

- **Histórias de Usuários:** Levantamento das necessidades e expectativas dos usuários com base em suas rotinas e desafios.

- **Requisitos Funcionais e Não Funcionais:** Definição detalhada das funcionalidades essenciais e dos aspectos técnicos que a solução deve atender.

- **Diagrama de Caso de Uso:** Modelagem dos principais fluxos de interação dos usuários com o sistema.

## Personas

**1. Carlos Mendes, 35 anos**

Profissão: Supervisor de Produção

Localização: Betim - MG

Estado civil: Casado

Perfil: Profissional experiente no controle da produção, responsável por monitorar a eficiência da fábrica e tomar decisões rápidas no chão de fábrica. Costuma lidar com grande volume de dados e relatórios diariamente.

Motivação: Quer acesso rápido a informações consolidadas para resolver problemas e manter a produção estável sem depender de sistemas desktop.

Frustrações:
- Atrasos na tomada de decisão devido à falta de acesso imediato aos dados.
- Dificuldade em gerar relatórios quando está fora do escritório.

---------------

**2. Ana Beatriz, 29 anos**

Profissão: Técnica de Manutenção

Localização: Contagem - MG

Estado civil: Solteira

Perfil: Técnica especializada em manutenção preventiva e corretiva. Está constantemente se deslocando entre setores da fábrica, muitas vezes sem acesso a um computador.

Motivação: Quer registrar, acompanhar e atualizar ocorrências de manutenção diretamente pelo celular, reduzindo tempo de resposta e agilizando reparos.

Frustrações:
- Necessidade de carregar notebook para registrar ordens de serviço.
- Dificuldade em acessar históricos de manutenção rapidamente no local da ocorrência.

---------------

**3. Marcos Oliveira, 40 anos**

Profissão: Operador de Máquina

Localização: Betim - MG

Estado civil: Casado

Perfil: Responsável pela operação e monitoramento diário de máquinas. Precisa de informações rápidas sobre status e materiais para evitar paradas e atrasos na produção.

Motivação: Quer otimizar tempo consultando dados diretamente pelo smartphone, garantindo que a produção siga sem interrupções.

Frustrações:
- Perda de tempo aguardando acesso a sistemas em computadores fixos.
- Falta de uma plataforma integrada para consultar informações sobre máquinas.

---------------

**4. Fernanda Rocha, 42 anos**

Profissão: Gerente de Produção

Localização: Belo Horizonte - MG

Estado civil: Divorciada

Perfil: Responsável pelo gerenciamento geral da produção e análise de indicadores. Passa boa parte do tempo em reuniões e áreas externas, precisando de mobilidade para acompanhar dados em tempo real.

Motivação: Quer ter uma visão consolidada da produção e gerar relatórios de qualquer lugar, facilitando a tomada de decisões estratégicas.

Frustrações:
- Falta de visibilidade imediata sobre indicadores-chave da fábrica.
- Dificuldade em acompanhar o desempenho quando está longe do escritório.

## Histórias de usuários
Com base nas personas, foram levantadas as seguintes histórias:

|     `PERSONA`    |                            `FUNCIONALIDADE`                   |                   `MOTIVO/VALOR`                    |
|------------------|---------------------------------------------------------------|-----------------------------------------------------|
|Carlos Mendes     | Monitorar dados de produção em tempo real                     | Tomar decisões rápidas no chão de fábrica           |
|Ana Beatriz       | Registrar ocorrências de manutenção pelo celular              | Reduzir o tempo de resposta e melhorar a eficiência |
|Marcos Oliveira   | Consultar informações de máquinas sem depender do desktop     | Evitar atrasos e otimizar o tempo de operação       |
|Fernanda Rocha    | 	Acompanhar indicadores e gerar relatórios a qualquer momento | Garantir visibilidade total e facilitar a gestão    |

## Requisitos

<p align="justify">A definição dos requisitos foi realizada para orientar o desenvolvimento do aplicativo, assegurando que todas as funcionalidades essenciais, critérios técnicos e limitações operacionais estejam claramente documentados. A seguir, são apresentados os requisitos funcionais, requisitos não funcionais e restrições que guiarão a implementação do sistema.

</p>

### Requisitos funcionais

| ID  |       FUNCIONALIDADE       |                                                                        DESCRIÇÃO                                                                     |  PRIORIDADE |
|-----|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------|-------------|
| RF01| Gerenciar Dados da Peça    | Permitir a visualização de informações relacionadas às peças utilizadas na produção, garantindo rastreabilidade e atualização dos dados.             |     ALTA    |
| RF02| Gerenciar Ciclo de Corte   | Permitir a visualização de informações relacionadas ao ciclo de corte da peça.                                                                       |     ALTA    |
| RF03| Gerenciar Ciclo de Produção| Permitir a visualização de informações relacionadas ao ciclo de produção.                                                                            |     ALTA    |
| RF04| Gerenciar Posicionamentos  | Permitir a visualização de informações relacionadas ao posicionamentos no destacker, garantindo precisão nos ajustes para otimização do processo.    |     MÉDIA   |
| RF05| Gerenciar Dados            | Organizar e consolidar os dados coletados diariamente, possibilitando consultas e análises para outras funcionalidades do sistema.                   |     ALTA    |
| RF06| Gerar Gráficos             | Criar representações visuais dos dados coletados, permitindo análise de desempenho e tomada de decisão.                                              |     ALTA    |
| RF07| Gerenciar Exportação       | Exportar dados e relatórios em formatos compatíveis (por exemplo, CSV, PDF), facilitando o compartilhamento e arquivamento das informações.          |     MÉDIA   |
| RF08| Gerenciar Coleta de Dados  | Registrar medições e informações coletadas em campo, garantindo consistência e integridade dos dados.                                                |     ALTA    |
| RF09| Gerenciar Inspeções        | Registrar códigos de inspeções realizadas nas máquinas durante a produção, para controle simples do processo.                                        |     MÉDIA   |
| RF10| Gerenciar Produção         | Acompanhar dados gerais da produção, como quantidade produzida, tempos de ciclo e eventuais desvios.                                                 |     ALTA    |
| RF11| Gerenciar Ordem de Serviço | Criar, atualizar, acompanhar e encerrar ordens de serviço, garantindo controle sobre atividades de manutenção e reparo.                              |     ALTA    |
| RF12| Gerenciar Edições          | Controlar alterações feitas em ordens de serviço, máquinas e dados associados, mantendo histórico das modificações.                                  |     MÉDIA   |
| RF13| Gerenciar Histórico        | Armazenar e permitir consulta ao histórico de falhas e eventos das máquinas, facilitando análises e previsões.                                       |     MÉDIA   |
| RF14| Gerenciar Estoque          | Controlar o saldo de materiais no almoxarifado por meio de consultas e simulações de retirada, considerando o estoque mínimo cadastrado.             |     ALTA    |
| RF15| Gerenciar Ocorrências      | Registrar e acompanhar ocorrências relacionadas à segurança, garantindo rastreabilidade e resolução.                                                 |     ALTA    |
| RF16| Gerenciar Preventivas      | Agendar, registrar e monitorar manutenções preventivas das máquinas, visando redução de falhas e aumento da confiabilidade.                          |     ALTA    |
| RF17| Gerenciar Custos           | Permitir simular redução nas medidas das peças, calculando automaticamente o custo de produção com base nas alterações realizadas.                   |     ALTA    |


### Requisitos não funcionais

|ID     |                                                      Descrição do Requisito                                                             |Prioridade |
|-------|-----------------------------------------------------------------------------------------------------------------------------------------|-----------|
|RNF-001| O aplicativo deve carregar qualquer página em até 2 segundos.                                                                           |   MÉDIA   | 
|RNF-002| A geração de gráficos deve ser concluída em menos de 5 segundos                                                                         |   BAIXA   | 
|RNF-003| O aplicativo deve rodar em múltiplos dispositivos Android sem ajustes manuais.                                                          |   BAIXA   | 
|RNF-004| O sistema deve assegurar a integridade e segurança das informações transmitidas, utilizando protocolos de comunicação criptografados    |   ALTA    | 
|RNF-005| O tempo de inicialização do aplicativo não deve exceder 3 segundos em dispositivos com especificações mínimas recomendadas.             |   MÉDIA   | 
|RNF-006| O aplicativo deve ser compatível com as versões do Android mais utilizadas, garantindo cobertura de pelo menos 90% da base de usuários. |   ALTA    | 
|RNF-007| A sincronização de dados entre servidor e dispositivo deve ocorrer em segundo plano, sem interrupções na experiência do usuário.        |   ALTA    |


## Restrições

| ID |                                                                 RESTRIÇÃO                                                                            |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------|
|001 | O aplicativo deve permitir alterações em dados de produção apenas quando não houver processos ativos em execução para evitar inconsistências.        |
|002 | A exclusão de registros (ex.: peças, ordens de serviço, máquinas) deve exigir confirmação explícita do usuário para evitar perda acidental de dados. |
|003 | O aplicativo deve restringir o acesso a determinados módulos conforme as permissões definidas para cada usuário (quando implementado).               |
|004 | O registro de produção deve conter todos os campos obrigatórios preenchidos antes de ser salvo.                                                      |
|005 | A exportação de relatórios e gráficos deve seguir um formato padronizado e ser compatível com os dispositivos móveis.                                |

## Diagrama de casos de uso




