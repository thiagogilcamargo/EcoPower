# EcoPower - Solução de Gestão e Otimização de Energia

## Visão Geral

### Nome do Projeto
**EcoPower - Solução de Gestão e Otimização de Energia**

### Descrição
EcoPower é uma plataforma integrada e inteligente, desenvolvida para otimizar o consumo de energia em tempo real, tanto para empresas quanto para residências. Seu principal objetivo é reduzir os custos de energia, promovendo práticas sustentáveis e o uso eficiente de recursos energéticos. A plataforma oferece interfaces para web e dispositivos móveis, onde os usuários podem monitorar o consumo, gerar relatórios detalhados e tomar decisões baseadas em dados analíticos. 

EcoPower também integra fontes de energia renováveis, como solar e eólica, e sugere práticas sustentáveis para os usuários, ajudando a reduzir sua pegada de carbono e custos com energia elétrica.

### Objetivo
O principal objetivo do **EcoPower** é fornecer uma solução eficaz e acessível para monitorar e otimizar o consumo energético. A plataforma tem como foco:
- **Monitoramento em tempo real** do consumo energético.
- **Análise e relatórios detalhados** sobre padrões de consumo e oportunidades de economia.
- **Agendamento inteligente** para otimização do uso de dispositivos.
- **Integração com fontes de energia renováveis** e recomendações para práticas sustentáveis.

## Tecnologias Utilizadas

### Backend

- **Java (Spring Framework)**: Utilizado para desenvolver os serviços principais do sistema, oferecendo uma base robusta e escalável para a criação de APIs e microserviços, além de facilitar a integração com bancos de dados relacionais e NoSQL.
- **ASP.NET Core**: Framework de código aberto utilizado para a criação de APIs de integração com sistemas externos, como dispositivos de monitoramento de consumo e bancos de dados. Sua alta performance e escalabilidade o tornam ideal para plataformas que lidam com grandes volumes de dados.
- **Oracle Database**: Banco de dados relacional utilizado para armazenar dados transacionais críticos, como registros de consumo e perfis de usuários. Sua confiabilidade e segurança são fundamentais para garantir a integridade e o desempenho do sistema.
- **MongoDB**: Banco de dados NoSQL utilizado para armazenar dados históricos e realizar análises de longo prazo sobre o consumo de energia. Sua flexibilidade e escalabilidade são essenciais para lidar com grandes volumes de dados não estruturados.

### Frontend

- **React**: Biblioteca JavaScript para o desenvolvimento da interface web, oferecendo uma experiência interativa e dinâmica com componentes reutilizáveis e renderização eficiente utilizando o Virtual DOM.
- **Kotlin**: Linguagem utilizada no desenvolvimento do aplicativo mobile nativo para Android, proporcionando uma experiência de desenvolvimento ágil e código limpo.

### Mastering Relational and Non-Relational Databases

- **Modelagem de Banco de Dados**: Utilização de modelagem relacional em **Oracle** e modelagem NoSQL em **MongoDB**, garantindo eficiência na gestão de dados.
- **Procedures e Funções**: Implementação de procedures para automação de processos e validação de dados.
- **Triggers e Auditoria**: Uso de triggers para rastrear e auditar alterações de dados, como inserções e modificações de registros de consumo.

### DevOps e Cloud Computing

- **Azure DevOps**: Plataforma para gerenciamento do ciclo de vida do projeto, com integração entre desenvolvimento, testes e deploy.
- **Pipelines e Docker**: Automação de build, teste e deploy utilizando Azure DevOps pipelines e Docker para containerização.
- **Deploy na Nuvem**: Implantação na infraestrutura de nuvem da **Azure**, garantindo alta disponibilidade e resiliência do sistema.

### Java Avançado

- **Desenvolvimento de APIs RESTful**: Criação de APIs para integração com dispositivos e sistemas externos, utilizando **Spring Boot**.
- **Injeção de Dependência**: Princípios de injeção de dependência são utilizados para facilitar a manutenção e escalabilidade do sistema.

## Funcionalidades Principais

### Cadastro e Monitoramento de Dispositivos
Permite aos usuários cadastrar e monitorar dispositivos de consumo de energia em tempo real. O sistema rastreia o uso de energia de cada dispositivo e exibe as métricas em um painel central.

### Relatórios Personalizados
Geração de relatórios detalhados sobre o consumo de energia, permitindo aos usuários visualizar padrões de consumo, identificar oportunidades de economia e tomar decisões informadas para otimizar seu uso de energia.

### Agendamento Inteligente
Funcionalidade que permite aos usuários agendar automaticamente o funcionamento de dispositivos, de acordo com os períodos de menor custo de energia ou as preferências de consumo sustentável.

### Integração com Fontes Renováveis
Monitoramento de dispositivos que utilizam fontes de energia renováveis, como solar e eólica. O sistema sugere práticas sustentáveis, como o uso de energia solar durante o dia, para otimizar o consumo e reduzir a dependência da rede elétrica convencional.

### Exportação de Dados
Permite que os usuários exportem seus dados de consumo em formato JSON, facilitando a análise externa e a criação de relatórios personalizados fora da plataforma.

## Arquitetura e Funcionamento

### Arquitetura do Sistema
O sistema será baseado em uma arquitetura **Microservices**, onde cada componente (backend, frontend e banco de dados) será isolado e pode ser escalado de maneira independente. Isso garantirá maior flexibilidade e escalabilidade conforme a plataforma cresce e o número de usuários aumenta.

### Fluxo de Dados
1. **Coleta de Dados**: Dispositivos conectados à plataforma enviam dados de consumo para o backend.
2. **Armazenamento**: Os dados são armazenados em **Oracle** para registros transacionais e em **MongoDB** para dados históricos.
3. **Análise e Relatórios**: O sistema processa os dados e gera relatórios detalhados, que são enviados para os usuários em tempo real.
4. **Visualização**: Os usuários podem visualizar o consumo através de dashboards interativos na interface web ou no aplicativo móvel.

## Conclusão
O **EcoPower** visa revolucionar a forma como empresas e residências gerenciam seu consumo de energia, tornando o processo mais eficiente e sustentável. Ao integrar tecnologias avançadas e práticas de análise de dados, a plataforma não só ajuda a reduzir custos, mas também contribui para um futuro mais verde, utilizando fontes de energia renováveis e promovendo o consumo consciente.

---
**Equipe de Desenvolvimento:**
- **Cauã Couto Basques** (RM97755)
- **Kaique Agostinho de Oliveira** (RM550815)
- **Leonardo Matheus Mariano** (RM99824)
- **Thiago Gil Camargo** (RM551211)
