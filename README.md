# resumo-ferr-imp-azure
Nesse repositório estarei colocando resumidamente o que foi entendido nessa aula


O Microsoft Azure oferece um conjunto robusto de ferramentas para implantação que facilitam o desenvolvimento, a implementação e a gestão de aplicações na nuvem. Vou resumir as principais ferramentas e serviços de implantação que podem ser úteis para os desenvolvidos

1. Serviço de Aplicativo do Azure
   
O Azure App Service é uma plataforma de serviço (PaaS) que permite hospedar aplicações Web, APIs, funções e back-ends móveis. Com ele, você pode facilmente configurar e gerenciar ambientes para suas aplicações, seja em uma simples aplicação Web ou em uma arquitetura complexa baseada em microserviços. Ele oferece recursos de integração contínua com repositórios de código (como GitHub e Azure DevOps), autoescala e alta disponibilidade, além de suporte para vários idiomas

2. Azure DevOps
   
O Azure DevOps é um conjunto de ferramentas para automação de pipelines de CI/CD (Integração Contínua e Entrega Contínua) que permite gerenciar todo o ciclo de vida de desenvolvimento de software. Com ele, é possível realizar o planejamento (com Azure Boards), versionamento de código (com Azure Repos), criação de pipelines de CI/CD para implantação automática (Azure Pipelines), e monitoramento e feedback (Azure Test Plans e Azure Artifacts) . Ele oferece flexibilidade para trabalhar com outras ferramentas e serviços e integração completa com o ecossistema do Azure.

3. Gerenciador de Recursos do Azure (ARM)
   
O Azure Resource Manager permite que você implemente, gerencie e monitore todos os recursos do Azure em seu ambiente. Ele trabalha com modelos (ARM templates) em JSON, que permitem definir a infraestrutura e a configuração do seu aplicativo em código. Desta forma, é possível automatizar implantações complexas, garantindo consistência e controle sobre os recursos. Esses modelos são versionados e reutilizados, facilitando a criação de ambientes podem ser consistentes em diferentes

4. Serviço Azure Kubernetes (AKS)
   
Para arquiteturas baseadas em contêineres, o Azure Kubernetes Service (AKS) facilita o gerenciamento e a escalabilidade de clusters Kubernetes. Ele permite implantar, gerenciar e escalar contêineres automaticamente, integrando-se a outras ferramentas de CI/CD e com suporte completo para Docker. O AKS é ideal para soluções que desativam alta escalabilidade, como microserviços e cargas de trabalho de processamento intensivo, permitindo uma abordagem DevOps completa

5. Funções do Azure
O Azure Functions é uma solução de "serverless" (sem servidor) que permite criar aplicações baseadas em eventos, executando código em resposta a eventos (HTTP, cron jobs, filas, etc.). Ele oferece escalabilidade automática e cobra apenas pelo tempo de execução, sendo altamente econômico. Funciona bem para tarefas de backend, como automação e processamento de dados, especialmente quando integrados com outras ferramentas de DevOps para implantação

6. Instâncias de contêiner do Azure (ACI)
   
O Azure Container Instances é um serviço que permite executar contêineres em segundos, sem a necessidade de gerenciamento de infraestrutura de VM ou clusters. Ideal para cargas de trabalho temporárias e de curta duração, o ACI permite implantações rápidas e escaláveis ​​para soluções que não desativam um orquestrador completo, como Kubernetes. Ele também pode ser integrado a pipelines de CI/CD para automação de cargas de trabalho em contêineres.

7. Lote do Azure
    
Para necessidades de processamento em larga escala, o Azure Batch é uma ferramenta que permite a execução de grandes quantidades de trabalho em paralelo. Ele gerencia e aloca recursos automaticamente, ideal para tarefas que desativam carga intensiva, como simulações e renderização de vídeos. O Azure Batch se integra bem com scripts e automatizações de DevOps para criar pipelines de

8. Laboratórios Azure DevTest
   
Esse serviço é benéfico para a criação de ambientes de desenvolvimento e teste de maneira eficiente e econômica. Ele facilita o controle de custos e permite que as equipes criem ambientes rapidamente. O DevTest Labs pode ser configurado com políticas de uso e horários de desligamento automático, o que ajuda a manter o controle sobre os recursos e forçamento

9. Aplicativos lógicos do Azure
    
Para integrações entre serviços e automação de fluxos de trabalho, o Azure Logic Apps permite criar fluxos de trabalho complexos que automatizam processos de negócios. Ele se integra a vários serviços no Azure, além de ferramentas externas, como Office 365, Salesforce, e outros. Os Logic Apps ajudam a orquestrar e automatizar a implantação

Essas ferramentas de implantação no Azure oferecem flexibilidade e controle sobre diferentes aspectos do ciclo de vida do software, desde o desenvolvimento e testes até a produção. Em conjunto, eles formam um ecossistema robusto para apoiar as metodologias DevOps, reduzindo o ritmo de desenvolvimento e facilitando a entrega
