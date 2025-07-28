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

|ID    |   Descrição do Requisito    | Prioridade |
|------|-----------------------------|------------|
|RF-001| Gerenciar Dados da peça     |    ALTA    | 
|RF-002| Gerenciar Ciclo de corte    |        |
|RF-003| Gerenciar Ciclo de produção |        |
|RF-004| Gerenciar Posicionamentos   |       |
|RF-005| Gerenciar Dados             |      |
|RF-006| Gerar Gráficos              |       |
|RF-007| Gerenciar exportação        |       |
|RF-008| Gerenciar coleta de dados   |        |
|RF-009| Gerenciar inspeções         |       |
|RF-010| Gerenciar Produção          |       |
|RF-011| Gerenciar Ordem de Serviço  |       |
|RF-012| Gerenciar Edições           |       |
|RF-013| Gerenciar Histórico         |       |
|RF-014| Gerenciar Estoque           |       |
|RF-014| Gerenciar Consumo           |       |
|RF-014| Gerenciar Cadastro          |       |
|RF-014| Gerenciar Ocorrências       |       |
|RF-014| Gerenciar Preventivas       |       |
|RF-014| Gerenciar Custos            |       |
|RF-014| Gerenciar Propostas         |       |


### Requisitos não funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O aplicativo deve carregar qualquer página em até 2 segundos. | MÉDIA | 
|RNF-002| A geração de gráficos deve ser concluída em menos de 5 segundos |  BAIXA | 
|RNF-003| O aplicativo deve rodar em múltiplos dispositivos Android sem ajustes manuais. |  BAIXA | 
|RNF-004|  |  MÉDIA | 
|RNF-005|  |  ALTA | 
|RNF-006|  |  MÉDIA | 
|RNF-007|  |  ALTA |


## Restrições

## Diagrama de casos de uso




