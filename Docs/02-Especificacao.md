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

## 1 - Carlos Mendes, 35 anos – Supervisor de Produção
<p align="justify">Necessita monitorar dados de produção em tempo real e gerar relatórios sem depender do desktop. Busca uma solução rápida para identificar problemas e tomar decisões diretamente no chão de fábrica.</p>

## 2 - Ana Beatriz, 29 anos – Técnica de Manutenção
<p align="justify">Precisa registrar e acompanhar ocorrências de manutenção de forma ágil, sem ter que carregar um notebook para cada setor. Com um app no celular, consegue abrir, consultar e atualizar ordens de serviço imediatamente.</p>

## 3 - Marcos Oliveira, 40 anos – Operador de Máquina
<p align="justify">Necessita acessar informações sobre máquinas e materiais rapidamente. Muitas vezes, por não estar próximo de um computador, perde tempo esperando acesso a sistemas internos.</p>

## 4 - Fernanda Rocha, 42 anos – Gerente de Produção
<p align="justify">Precisa de uma visão consolidada dos indicadores da fábrica. Com um aplicativo mobile, consegue analisar gráficos e relatórios mesmo estando em reuniões ou áreas externas.</p>

## Histórias de usuários
Com base nas personas, foram levantadas as seguintes histórias:

|`PERSONA`|  `FUNCIONALIDADE` | `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Carlos Mendes     | Monitorar dados de produção em tempo real    | Tomar decisões rápidas no chão de fábrica |
|Ana Beatriz         | Registrar ocorrências de manutenção pelo celular | Reduzir o tempo de resposta e melhorar a eficiência |
|Marcos Oliveira    | Consultar informações de máquinas sem depender do desktop | Evitar atrasos e otimizar o tempo de operação |
|Fernanda Rocha    | 	Acompanhar indicadores e gerar relatórios a qualquer momento | Garantir visibilidade total e facilitar a gestão |

## Requisitos

### Requisitos funcionais

| ID  | FUNCIONALIDADE             | DESCRIÇÃO                                                                                                                                                  | PRIORIDADE |
|-----|----------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|------------|
| RF01| Gerenciar Dados da Peça    | Permitir a visualização de informações relacionadas às peças utilizadas na produção, garantindo rastreabilidade e atualização dos dados. | Alta       |
| RF02| Gerenciar Ciclo de Corte   | Permitir a visualização de informações relacionadas ao ciclo de corte da peça.                                    | Alta       |
| RF03| Gerenciar Ciclo de Produção| Permitir a visualização de informações relacionadas ao ciclo de produção.                                               | Alta       |
| RF04| Gerenciar Posicionamentos  | Permitir a visualização de informações relacionadas ao posicionamentos no destacker, garantindo precisão nos ajustes para otimização do processo.                                      | Média      |
| RF05| Gerenciar Dados            | Organizar e consolidar os dados coletados diariamente, possibilitando consultas e análises para outras funcionalidades do sistema.                       | Alta       |
| RF06| Gerar Gráficos             | Criar representações visuais dos dados coletados, permitindo análise de desempenho e tomada de decisão.                                                   | Alta       |
| RF07| Gerenciar Exportação       | Exportar dados e relatórios em formatos compatíveis (por exemplo, CSV, PDF), facilitando o compartilhamento e arquivamento das informações.               | Média      |
| RF08| Gerenciar Coleta de Dados  | Registrar medições e informações coletadas em campo, garantindo consistência e integridade dos dados.                                                     | Alta       |
| RF09| Gerenciar Inspeções        | Controlar registros de inspeções realizadas, incluindo status, observações e resultados para análise futura.                                               | Média      |
| RF10| Gerenciar Produção         | Acompanhar dados gerais da produção, como quantidade produzida, tempos de ciclo e eventuais desvios.                                                        | Alta       |
| RF11| Gerenciar Ordem de Serviço | Criar, atualizar, acompanhar e encerrar ordens de serviço, garantindo controle sobre atividades de manutenção e reparo.                                   | Alta       |
| RF12| Gerenciar Edições          | Controlar alterações feitas em ordens de serviço, máquinas e dados associados, mantendo histórico das modificações.                                       | Média      |
| RF13| Gerenciar Histórico        | Armazenar e permitir consulta ao histórico de falhas e eventos das máquinas, facilitando análises e previsões.                                             | Média      |
| RF14| Gerenciar Estoque          | Controlar entrada, saída e saldo de materiais no almoxarifado, evitando faltas ou excessos.                                                                 | Alta       |
| RF15| Gerenciar Consumo          | Registrar e analisar o consumo de materiais e insumos, permitindo melhor planejamento e reposição.                                                         | Alta       |
| RF16| Gerenciar Cadastro         | Permitir o cadastro e manutenção de dados de máquinas, peças e usuários do sistema.                                                                       | Alta       |
| RF17| Gerenciar Ocorrências      | Registrar e acompanhar ocorrências relacionadas à segurança, garantindo rastreabilidade e resolução.                                                       | Alta       |
| RF18| Gerenciar Preventivas      | Agendar, registrar e monitorar manutenções preventivas das máquinas, visando redução de falhas e aumento da confiabilidade.                               | Alta       |
| RF19| Gerenciar Custos           | Registrar custos operacionais, possibilitando análises financeiras e identificação de oportunidades de redução.                                           | Alta       |
| RF20| Gerenciar Propostas        | Criar e acompanhar propostas de redução de custos, registrando projeções, resultados esperados e acompanhamento da implementação.                         | Alta       |

### Requisitos não funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O aplicativo deve carregar qualquer página em até 2 segundos. | MÉDIA | 
|RNF-002| A geração de gráficos deve ser concluída em menos de 5 segundos |  BAIXA | 
|RNF-003| O aplicativo deve rodar em múltiplos dispositivos Android sem ajustes manuais. |  BAIXA | 
|RNF-004|  |   | 
|RNF-005|  |   | 
|RNF-006|  |  | 
|RNF-007|  |   |


## Restrições

| ID |                                                                 RESTRIÇÃO                                                                            |
|----|------------------------------------------------------------------------------------------------------------------------------------------------------|
|001 | O aplicativo deve permitir alterações em dados de produção apenas quando não houver processos ativos em execução para evitar inconsistências.        |
|002 | A exclusão de registros (ex.: peças, ordens de serviço, máquinas) deve exigir confirmação explícita do usuário para evitar perda acidental de dados. |
|003 | O aplicativo deve restringir o acesso a determinados módulos conforme as permissões definidas para cada usuário (quando implementado).               |
|004 | O registro de produção deve conter todos os campos obrigatórios preenchidos antes de ser salvo.                                                      |
|005 | A exportação de relatórios e gráficos deve seguir um formato padronizado e ser compatível com os dispositivos móveis.                                |
|006 | Alterações em dados compartilhados (ex.: estoque, ciclo de produção) devem ser refletidas em todas as telas do aplicativo de forma imediata.         |


## Diagrama de casos de uso




