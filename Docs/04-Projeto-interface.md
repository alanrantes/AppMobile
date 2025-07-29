# Projeto de interface

<span style="color:red">Pré-requisitos: <a href="02-Especificacao.md"> Especificação do projeto</a></span>

<p align="justify">O projeto de interface foi desenvolvido visando agilidade operacional e praticidade no acesso às informações industriais, atendendo às necessidades identificadas nas personas e histórias de usuários. A proposta prioriza navegação intuitiva, organização clara das informações e responsividade, permitindo que os colaboradores realizem consultas e registros diretamente pelo smartphone, eliminando a dependência exclusiva de estações desktop.</p>

 ## Arquitetura da Interface
<p align="justify">A interface é estruturada em módulos independentes, integrados por uma navbar superior e menu lateral (drawer), permitindo acesso rápido às principais funcionalidades. A navegação foi projetada para minimizar cliques e oferecer fluxos lineares, essenciais em contextos produtivos com alta demanda por agilidade.</p>

- **Página Inicial:** ponto central de interação, com campo de busca responsivo para inserção de códigos de peças e botões de acesso rápido às consultas mais frequentes (Dados da Peça, Ciclo de Corte, Ciclo de Produção e Posicionamento Destacker).
 
- **Páginas de Consulta Técnica:** exibição estruturada de dados operacionais em formato de campos de leitura (inputs bloqueados), permitindo rápida identificação de parâmetros críticos. Imagens técnicas possuem recurso de expansão (zoom) para detalhamento visual.
 
- **Menu Lateral (Navbar):** acesso modular às funcionalidades de análise, gestão e registro.

### Navbar

   - **Gerar Gráficos:** filtros por linha, ID e período (mensal/diário), com exportação em Excel e PNG para relatórios de desempenho.
  
   - **Carta de CEP:** interface de coleta de dados de produção, armazenando registros essenciais para análise estatística.
   
   - **Ordens de Serviço:** módulo de criação, edição e acompanhamento de ordens, com controle de prioridade e status.
  
   - **Máquinas:** monitoramento do estado operacional (operando, parada, manutenção) e acesso ao histórico de falhas.
 
   - **Almoxarifado:** consultas de estoque e simulação de consumo para gestão de materiais.
   
   - **Segurança:** registro e rastreamento de ocorrências, com busca por código e galpão.
   
   - **Preventivas:** agenda de manutenções preventivas com calendário interativo.
  
   - **DMC (Redução de Custos):** criação e acompanhamento de propostas para otimização de processos e redução de custos.

### Fluxo de Navegação
A navegação foi desenhada para minimizar tempo de execução das tarefas e reduzir a curva de aprendizado:

**1. Entrada do Código da Peça** na Página Inicial.

**2. Seleção do Módulo** (consulta técnica, geração de gráficos, gestão de ocorrências, etc.).

**3. Interação direta com os dados,** com suporte a exportação, registros e análises em tempo real.

<p align="justify">Esse fluxo garante que o usuário realize suas atividades com o menor número de interações possíveis, atendendo aos requisitos funcionais RF01 a RF20.</p>





















<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
<p align="justify"></p>
