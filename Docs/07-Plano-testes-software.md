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


| **Caso de teste**  | **CT-005 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF05 - Gerenciar Dados |


| **Caso de teste**  | **CT-006 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF06 - Gerar Gráficos |

| **Caso de teste**  | **CT-007 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF07 - Gerenciar Exportação	 |

| **Caso de teste**  | **CT-008 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF08 - Gerenciar Coleta de Dados |

| **Caso de teste**  | **CT-009 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF09 - Gerenciar Inspeções |

| **Caso de teste**  | **CT-010 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF10 - Gerenciar Produção|

| **Caso de teste**  | **CT-011 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF11 - Gerenciar Ordem de Serviço |

| **Caso de teste**  | **CT-012 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF12 - Gerenciar Edições |

| **Caso de teste**  | **CT-013 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF13 - Gerenciar Histórico |

| **Caso de teste**  | **CT-014 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF14 - Gerenciar Estoque |

| **Caso de teste**  | **CT-015 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF15 - Gerenciar Ocorrências |

| **Caso de teste**  | **CT-016 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF16 - Gerenciar Preventivas |

| **Caso de teste**  | **CT-017 – **  |
|--------------------|---------------------------------------|
| **Requisito associado** | RF17 - Gerenciar Custos |



