# Arquitetura da solução

<span style="color:red">Pré-requisitos: <a href="04-Projeto-interface.md"> Projeto de interface</a></span>

<p align="justify">A arquitetura proposta segue o modelo cliente-servidor em três camadas, garantindo modularidade, escalabilidade e fácil manutenção. O sistema é composto por: front-end, back-end e banco de dados relacional.</p>
<p align="justify">O front-end é uma aplicação web responsiva desenvolvida com HTML, CSS e JavaScript, priorizando a experiência mobile. A aplicação pode ser empacotada como aplicativo híbrido através do Capacitor, possibilitando integração com recursos nativos do dispositivo. Essa camada é responsável pela interface com o usuário, coleta de dados e envio de requisições HTTP ao servidor.</p>
<p align="justify">O back-end, construído em Node.js com o framework Express, centraliza a lógica de negócios, autenticação, validação de dados e controle de acesso. Toda comunicação com o cliente ocorre via API RESTful, utilizando JSON para transporte de dados, assegurando interoperabilidade e eficiência.</p>
<p align="justify">A persistência dos dados será realizada em um banco de dados relacional SQL, escolhido pela necessidade de integridade referencial, normalização e robustez transacional, fundamentais para o gerenciamento de dados de produção, históricos de falhas, consumos e ordens de serviço. O modelo relacional permite estruturação rígida dos dados e consultas complexas, assegurando consistência e confiabilidade mesmo em cenários de alta concorrência.</p>
<p align="justify">Essa arquitetura garante separação clara de responsabilidades, viabilizando futuras evoluções, integrações e escalabilidade horizontal do sistema.</p>

![Image](Imagens/Arquitetura.png)

## Diagrama de classes

<p align="justify">O diagrama de classes a seguir representa a estrutura lógica da aplicação, destacando as principais entidades do sistema e seus relacionamentos. Ele foi projetado para sustentar o desenvolvimento orientado a objetos, garantindo organização, manutenibilidade e escalabilidade do sistema.</p>
<p align="justify">O modelo contempla as principais entidades do sistema, cada uma representando elementos centrais do processo produtivo e administrativo. Essas entidades possuem atributos e comportamentos próprios, estruturados para refletir as operações executadas pelos usuários e manter a integridade das informações dentro da aplicação.</p>
<p align="justify"></p>

![image]()
