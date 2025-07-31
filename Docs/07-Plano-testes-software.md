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

| **Caso de teste**  | **CT-004 – Consultar Posicionamento**  |
|--------------------|-------------------------------------------|
| **Requisito associado** | RF04 - Gerenciar Posicionamentos |
| **Objetivo do teste** | Garantir que o usuário consiga buscar e visualizar as informações do posicionamento. |
| **Passos** | - Abrir o aplicativo <br> - Digitar o código da peça no campo de busca <br> - Clicar no botão "Buscar" <br> - Selecionar a opção "Posicionamento Destacker" <br> - Conferir as imagens exibidas |
| **Critério de êxito** | As imagens do posicionamento são exibidas corretamente para a peça pesquisada. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-005 – Gerar Gráfico de Produção**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF06 - Gerar Gráficos |
| **Objetivo do teste** | Verificar se o sistema gera corretamente o gráfico de produção com base no desenho, linha e período selecionado. |
| **Passos** |- Abrir o aplicativo <br> - Acessar a página "Gerar Gráficos" <br> - Selecionar a linha desejada <br> - Digitar o código do desenho <br> - Selecionar o tipo de período (Mensal ou Diário) <br> - Clicar no botão "Gerar Gráfico"|
| **Critério de êxito** | 	O gráfico é exibido corretamente com base nos dados correspondentes ao filtro selecionado. |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-006 – Exportar Gráficos**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF07 - Gerenciar Exportação	 |
| **Objetivo do teste** | Verificar se o sistema permite exportar os gráficos gerados para um arquivo. |
| **Passos** |- Abrir o aplicativo <br> - Acessar a página "Gerar Gráficos" <br> - Gerar um gráfico com filtros válidos <br> - Clicar no botão "Exportar Excel" e "Exportar PNG"  |
| **Critério de êxito** | O arquivo contendo o gráfico gerado é exportado corretamente para o formato selecionado e pode ser aberto sem erros.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-007 – Registrar uma Carta de CEP**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF08 - Gerenciar Coleta de Dados |
| **Objetivo do teste** | Garantir que o usuário consiga preencher e enviar corretamente o formulário de coleta de dados na página Carta de CEP. |
| **Passos** |- Abrir o aplicativo <br> - Acessar a página "Carta de CEP" <br> - Preencher os campos (Data, Hora, Linha, Turno, Team Leader, Operador, Fornecedor) <br> Clicar em "Salvar Dados"|
| **Critério de êxito** | Os dados inseridos no formulário são salvos com sucesso, e o sistema confirma o envio sem erros.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-008 – Registrar Inspeções**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF09 - Gerenciar Inspeções |
| **Objetivo do teste** | Garantir que o usuário consiga registrar o código da inspeção realizada durante a produção. |
| **Passos** |- Abrir o aplicativo <br> - Acessar a página "Carta de CEP" <br> - Digitar o código da inspeção no campo correspondente <br> - Clicar no botão "Salvar" <br> - Confirmar que o registro foi salvo com sucesso <br> |
| **Critério de êxito** | O código da inspeção é salvo corretamente e uma confirmação de sucesso é exibida ao usuário.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-009 – Registrar uma Ordem**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF11 - Gerenciar Ordem de Serviço |
| **Objetivo do teste** |Garantir que o usuário consiga criar, editar e gerenciar ordens de serviço corretamente no sistema.  |
| **Passos** |- Abrir o aplicativo <br> - Acessar a página "Ordem de Serviço" <br> - Clicar no botão "+" <br> - Preencher os campos (Problema, Descrição, Prioridade, Status) <br> - Clicar no botão "Salvar"  |
| **Critério de êxito** | As ordens de serviço são criadas, atualizadas e salvas com sucesso, refletindo corretamente as informações inseridas pelo usuário.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-010 – Registrar uma Falha**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF13 - Gerenciar Histórico |
| **Objetivo do teste** | Garantir que o sistema registre e exiba corretamente o histórico de falhas, permitindo rastreabilidade completa. |
| **Passos** | - Abrir o aplicativo <br> - Acessar a página "Linhas" <br> - Clicar no botão "Falhas" <br> - Clicar no botão "Adicionar" <br> - Preencher os campos (Problema, Data, Hora, Registro, Manutenção) <br> - Clicar no botão "Salvar"|
| **Critério de êxito** | O histórico é atualizado automaticamente com todas as ações relevantes, e as informações são exibidas corretamente para o usuário.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-011 – Consultar Estoque**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF14 - Gerenciar Estoque |
| **Objetivo do teste** | Garantir que o sistema permita buscar peças no estoque, simular retiradas e exibir corretamente o saldo atualizado e o estoque mínimo. |
| **Passos** | - Abrir o aplicativo <br> - Acessar a página "Almoxarifado" <br> - Preencher os campos (ID, Descrição, Centro de Custo) <br> - Clicar no botão "Pesquisar" <br> - Descer para a seção "Simular consumo" <br> - Preencher os campos (Código do item, Quantidade a consumir) <br> - Clicar no botão "Simular Consumo" |
| **Critério de êxito** | As buscas retornam as peças corretas, a simulação calcula o saldo futuro adequadamente e o estoque mínimo é exibido com precisão.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-012 – Registrar uma Ocorrência**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF15 - Gerenciar Ocorrências |
| **Objetivo do teste** | Garantir que o usuário consiga registrar, visualizar e atualizar ocorrências no aplicativo de forma correta. |
| **Passos** | - Abrir o aplicativo <br> - Acessar a página "Segurança" <br> - Clicar no botão "+" <br> - Preencher os campos (Galpão, Área, Registro, UTE, Relato do acidente ou quase acidente) <br> - Clicar no botão "Salvar" |
| **Critério de êxito** | As ocorrências são registradas, exibidas e atualizadas com sucesso, refletindo fielmente as informações fornecidas pelo usuário.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-013 – Registrar uma Preventiva**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF16 - Gerenciar Preventivas |
| **Objetivo do teste** | Garantir que o usuário consiga abrir o modal de cadastro de manutenção preventiva, preencher o formulário selecionando a data e salvar corretamente, fazendo com que o calendário destaque a data cadastrada. |
| **Passos** | - Abrir o aplicativo <br> - Acessar a página "Preventivas" <br> - Clicar no botão "+" <br> - Preencher os campos (Data, Descrição) <br> - Clicar no botão "Salvar" |
| **Critério de êxito** | Ao salvar a manutenção preventiva, o sistema registra os dados corretamente e exibe uma indicação (bolinha) no calendário na data selecionada.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |

| **Caso de teste**  | **CT-014 – Registrar uma Simulação**  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF17 - Gerenciar Custos |
| **Objetivo do teste** | Garantir que o usuário consiga simular a redução das medidas das peças e que o sistema calcule corretamente o custo de produção baseado nas alterações realizadas. |
| **Passos** | - Abrir o aplicativo <br> - Acessar a página "DMC" <br> - Digitar o número do desenho <br> - Clicar no botão "Buscar" <br> - Na seção "Proposta de Redução" preencher os campos que quiser utilizar <br> - Clicar no botão "Calcular"|
| **Critério de êxito** | A simulação é realizada com sucesso, e o custo de produção exibido reflete corretamente as medidas alteradas.	 |
| **Responsável pela elaboração do caso de teste** | Alan Lacerda Arantes |



