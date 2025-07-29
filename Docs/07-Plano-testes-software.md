# Plano de testes de software
<span style="color:red">Pré-requisitos: <a href="02-Especificacao.md"> Especificação do projeto</a></span>, <a href="04-Projeto-interface.md"> Projeto de interface</a>

<p align="justify">O plano de testes de software foi desenvolvido para assegurar que todas as funcionalidades essenciais do aplicativo móvel atendam aos requisitos definidos na fase de especificação. O objetivo é validar o correto funcionamento do sistema, verificando desempenho, integridade dos dados e aderência às expectativas dos usuários.</p>

<p align="justify">Os testes foram realizados de forma incremental, acompanhando o desenvolvimento das funcionalidades, com execuções parciais durante a implementação e, posteriormente, com a versão consolidada do aplicativo.</p>

<p align="justify">A seguir, apresentam-se os casos de teste elaborados para avaliar a estabilidade, confiabilidade e usabilidade do sistema, abrangendo atividades como registro de dados operacionais, acompanhamento de manutenções, geração de relatórios e gerenciamento de ocorrências.</p>

| **Caso de teste**  | **CT-001 – Consultar Dados da Peça**  |
|--------------------|--------------------------------------|
| **Requisito associado** | RF01 - Gerenciar Dados da Peça |
| **Objetivo do teste** | Validar se o usuário consegue buscar e visualizar as informações de uma peça pelo código inserido na tela inicial. |
| **Passos** | - Abrir o aplicativo <br> - Digitar o código da peça no campo de busca da tela inicial <br> - Clicar no botão "Buscar" <br> - Selecionar a opção "Dados da Peça" <br> - Conferir as informações apresentadas (Nome, número de furos, linha de origem, embalagem etc.) |
| **Critério de êxito** | As informações corretas da peça são exibidas conforme o código pesquisado. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-002 – Consultar Ciclo de Corte**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF02 - Gerenciar Ciclo de Corte |
| **Objetivo do teste** | Validar se o usuário consegue buscar e visualizar as informações do ciclo de corte da peça. |
| **Passos** | - Abrir o aplicativo <br> - Digitar o código da peça no campo de busca da tela inicial <br> - Clicar no botão "Buscar" <br> - Selecionar a opção "Ciclo de Corte" <br> - Conferir as informações exibidas (Comprimento, largura, espessura, qualidade, etc.) |
| **Critério de êxito** | As informações corretas do ciclo de corte são exibidas conforme o código pesquisado. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-003 – Consultar Ciclo de Produção**  |
|--------------------|-------------------------------------------|
| **Requisito associado** | RF03 - Gerenciar Ciclo de Produção |
| **Objetivo do teste** | Garantir que o usuário consiga buscar e visualizar as informações do ciclo de produção da peça. |
| **Passos** | - Abrir o aplicativo <br> - Digitar o código da peça no campo de busca <br> - Clicar no botão "Buscar" <br> - Selecionar a opção "Ciclo de Produção" <br> - Conferir as informações exibidas (estampos, batentes destacker, número de embaladores etc.) |
| **Critério de êxito** | Os dados do ciclo de produção são exibidos corretamente para a peça pesquisada. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-004 – Gerar Gráficos de Produção**  |
|--------------------|-------------------------------------------|
| **Requisito associado** | RF06 - Gerar Gráficos |
| **Objetivo do teste** | Verificar se o usuário consegue gerar gráficos de produção com base nos dados inseridos. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Gerar Gráficos" <br> - Preencher os campos (Linha, ID, Mensal/Diário) <br> - Clicar em "Gerar Gráfico" <br> - Visualizar o gráfico gerado <br> - Utilizar a opção de exportar em Excel ou PNG |
| **Critério de êxito** | O gráfico correto é gerado e as opções de exportação funcionam sem erros. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-005 – Criar Ordem de Serviço**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF11 - Gerenciar Ordem de Serviço |
| **Objetivo do teste** | Verificar se o usuário consegue criar uma nova ordem de serviço no sistema. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Ordens de Serviço" <br> - Clicar no botão "+" para criar nova ordem <br> - Preencher os campos obrigatórios (Problema, Descrição, Prioridade, Status) <br> - Clicar em "Salvar" |
| **Critério de êxito** | A ordem de serviço é criada com sucesso e aparece na lista de ordens. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-006 – Registrar Ocorrência de Segurança**  |
|--------------------|-------------------------------------------------|
| **Requisito associado** | RF17 - Gerenciar Ocorrências |
| **Objetivo do teste** | Validar se o usuário consegue registrar uma nova ocorrência de segurança no sistema. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Segurança" <br> - Clicar no botão "+" para registrar ocorrência <br> - Preencher os campos obrigatórios (Galpão, Área, Registro, UTE, Relato do acidente) <br> - Clicar em "Salvar" |
| **Critério de êxito** | A ocorrência de segurança é registrada e exibida na lista de ocorrências. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-007 – Registrar Carta de CEP**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF08 - Gerenciar Coleta de Dados |
| **Objetivo do teste** | Verificar se o usuário consegue registrar uma nova Carta de CEP ao final da produção. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Carta de CEP" <br> - Preencher os campos obrigatórios (Data, Hora, Linha, Turno, Team Leader, Operador, Fornecedor, Inspeções, Refugos/Reparação, Produção) <br> - Clicar no botão "Salvar" |
| **Critério de êxito** | A carta de CEP é registrada com sucesso e fica disponível para gerar gráficos. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-008 – Consultar Estoque no Almoxarifado**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF14 - Gerenciar Estoque |
| **Objetivo do teste** | Validar se o usuário consegue consultar materiais e simular consumo no módulo de almoxarifado. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Almoxarifado" <br> - Digitar o nome ou código do material desejado <br> - Visualizar o saldo disponível e realizar simulação de consumo |
| **Critério de êxito** | O sistema exibe corretamente o saldo e permite simular o consumo sem erros. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-009 – Agendar Preventiva**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF18 - Gerenciar Preventivas |
| **Objetivo do teste** | Garantir que o usuário consiga agendar uma manutenção preventiva. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Preventivas" <br> - Clicar no botão "+" <br> - Preencher os campos obrigatórios (Data, Descrição) <br> - Clicar em "Salvar" |
| **Critério de êxito** | A manutenção preventiva é agendada e aparece marcada no calendário. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-010 – Criar Proposta de Redução de Custos (DMC)**  |
|--------------------|---------------------------------------------------------|
| **Requisito associado** | RF20 - Gerenciar Propostas |
| **Objetivo do teste** | Verificar se o usuário consegue criar uma proposta de redução de custos no módulo DMC. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "DMC" <br> - Preencher os campos obrigatórios da proposta <br> - Clicar em "Salvar" |
| **Critério de êxito** | A proposta de redução de custos é registrada com sucesso no sistema. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-011 – Consultar histórico de falhas da máquina**  |
|--------------------|---------------------------------------------------------|
| **Requisito associado** | RF13 - Gerenciar Histórico |
| **Objetivo do teste** | Verificar se o usuário consegue visualizar corretamente o histórico de falhas de uma máquina. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Máquinas" <br> - Digitar o código da máquina no campo de busca <br> - Clicar no botão "Falhas" da máquina desejada |
| **Critério de êxito** | O sistema exibe todo o histórico de falhas da máquina selecionada sem erros. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-012 – Alterar status da máquina**  |
|--------------------|---------------------------------------------------------|
| **Requisito associado** | RF12 - Gerenciar Edições |
| **Objetivo do teste** | Garantir que o usuário consiga alterar o status operacional de uma máquina. |
| **Passos** | - Abrir o aplicativo <br> - Acessar o menu lateral ☰ e selecionar "Máquinas" <br> - Digitar o código da máquina no campo de busca <br> - Clicar no botão "Alterar" <br> - Selecionar o novo status (Operando, Parada ou Manutenção) <br> - Confirmar a alteração |
| **Critério de êxito** | O status da máquina é atualizado corretamente e refletido em todas as telas do sistema. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |



