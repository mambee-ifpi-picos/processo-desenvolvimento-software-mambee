# Processo de Desenvolvimento de Software da Mambee
 
 O Objetivo deste documento é descrever o processo base de desenvolvimento de software da Fábrica Escola de Software Mambee.
 
 ## Pápeis e responsabilidades
 
 ### Líder de Projeto (Team Leader)
 
 - Liderar o projeto em relação ao orçamento, escopo e cronograma juntamente com o cliente e equipe de desenvolvimento;
 - Apresentar relatórios de acompanhamento e conclusão do projeto;
 - Prover interação entre cliente e equipe;
 - Obter recursos necessários para o planejamento, execução e encerramento do projeto.

### Líder Técnico (Tech Leader)
- Liderar a definição de arquitetura e tecnologias do projeto;
- Liderar e dar suporte a equipe de desenvolvimento em relação ao fluxo de trabalho e uso de ferramentas;
- Gerenciar conflitos e expectativas dentro da equipe de desenvolvimento;
- Garantir a qualidade do código por meio de revisão e alinhamento de estilos e padrões;
- Promover a colaboração e o uso de boas práticas pela equipe de desenvolvimento.

### Dono do Produto (Product Owner - PO)

- Levantar requisitos funcionais e não funcionais de sistema;
- Definir e priorizar os itens do backlog;
- Garantir que o Backlog do Produto esteja acessível e compreensível por todos;
- Detalhar Histórias de Usuários (HU);
- Clarificar e negociar o escopo da Sprint para o time de desenvolvimento;
- Identificar e registrar falhas e não conformidades com requisitos definidos;
- Definir os critérios de aceitação para HUs e defeitos;

### Designer de UX/UI - (UX - User Experience, UI User Interface)

- Definir identidade visual do projeto;
- Desenhar interface do aplicativo com o cliente/usuário;
- Desenvolvover de protótipos de baixa e alta fidelidade;
- Analisar e validar Usabilidade da interface gráfica.

### Desenvolvedor Front-end
- Manter a base centra de código organizada de acordo com o fluxo de trabalho definido para o projeto;
- Implementar front-end das funcionalidades de acordo com as HUs;
- Implementar requisitos não-funcionais do front-end de acordo com as especificações;
- Refatorar o código-fonte para manter-se atualizado e de acordo com as boas práticas e arquitetura do sistema;
- Criar e manter testes automatizados de unidade e integração de acordo com as HUs;
- Criar e manter o processo de automatização de implantação do sistema.

### Desenvolvedor Back-end
- Manter a base centra de código organizada de acordo com o fluxo de trabalho definido para o projeto;
- Implementar back-end das funcionalidades de acordo com as HUs;
- Implementar requisitos não-funcionais do back-end de acordo com as especificações;
- Refatorar o código-fonte para manter-se atualizado e de acordo com as boas práticas e arquitetura do sistema;
- Criar e manter testes automatizados de unidade e integração de acordo com as HUs;
- Criar e manter o processo de automatização de implantação do sistema.

### Testador (Quality Assurance - QA)

- Garantir a qualidade do produto;
- Levantar casos e executá-los;
- Acompanhar a implementação e modificação do sistema de acordo com os requisitos definidos;
- Promover o entendimento dos critérios de aceitação;
- Realizar a abertura e validação de bugs;
- Implementar e executar testes de sistemas (e2e) automatizados.

 ## Ciclo de vida do processo de desenvolvimento de software
 
 O ciclo de vida de desenvolvimento de software - SDLC (Software Development Life Cycle em inglês) é uma estrutura que define todas as etapas envolvidas no processo de planejamento, criação, teste e implantação de software.
 
 o SDLC descreve todas as tarefas necessárias para desenvolver e implantar um software, tendo como principal objetivo guiar o desenvolvimento de um produto de alta qualidade conforme a exigência do cliente. 
 
Principais **benefícios** do SDLC:
- Definir um fluxo de trabalho para toda a equipe;
- Cria um vocabulário comum para cada passo ao longo do desenvolvimento do projeto;
- Definir canais de comunicação e expectativas entre desenvolvedores e partes interessadas do projeto;
- Definir funções e responsabilidades claras para toda a sua equipe (desenvolvedores, designers, gestores, cliente, etc...);

A figura abaixo ilustra o ciclo de vida do processo de desenvolvimento de software da Mambee.

```mermaid
flowchart LR
    A((Concepção)) --> B((Planejamento))
    B --> C((Projeto))
    subgraph Desenvolvimento
     direction RL
     D((Planejar)) --> E((Codificar))
     E --> F((Testar))
     F --> G((Implantar))
     G --> H((Feedback e \n Validação))
     H --> D
    end
    C --> Desenvolvimento
    Desenvolvimento --> I((Encerramento))
```

A seguir será detalhado cada etapa do processo:

### 1. Concepção

Quando surgir uma demanda por um novo  projeto, a primeira etapa é a concepção, que envolve a identificação do problema e levantamento dos requisitos iniciais. Isso inclui:

- **Identificação do problema:** Qual o problema e real necessidade do cliente?
- **Disponibilidade e alocação de recursos** : A Mambee tem as pessoas e as ferramentas necessárias para fazer isso?
- **Estimativa de custos**: quanto vai custar?
- **Agendamento de projetos**: como esse projeto se encaixa nos objetivos da Mambee?
- **Alinhamento**: Como esse projeto se conecta à missão e visão da Mambee?
- **Definição do líder do projeto**: Definição de um líder do projeto dentro da Mambee.
Nesta fase deve ser envolvido todos as pessoas da Mambee que serão afetadas pelo projeto (Coordenador, professor e equipe de desenvolvimento).

No final da fase de planejamento, o líder do projeto deve ter informações suficientes para montar um escopo de trabalho de alto nível SOW (scope of work em inglês) – um plano que detalha o que está será construído, por que e como se alinha com os objetivos da Mambee.

> **Entradas**: Documento da proposta de projeto [[Template]](#)
> 
> **Saídas**: Documento de escopo de trabalho de alto nível (scope of work - [SOW](https://plan.io/blog/scope-of-work/)) [[Template]](#)
> 
> **Responsáveis**: Líder do projeto
> 
> **Participantes**: Todos os interessados no projeto





---
## Referências
- [https://plan.io/blog/software-development-process/#3-design-and-prototyping](https://plan.io/blog/software-development-process/#3-design-and-prototyping)
- [https://docs.google.com/document/d/1lbi95nYKUjW-eiylRH-ZZ4hutI__hF0MFh5ewp03gOc/edit?usp=sharing](https://docs.google.com/document/d/1lbi95nYKUjW-eiylRH-ZZ4hutI__hF0MFh5ewp03gOc/edit?usp=sharing)
