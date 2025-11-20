### Quarto Semestre (2024-2)

No quarto semestre do curso de ADS, desenvolvemos um projeto em parceria com a **JJM LOG**, empresa do setor de logística. Os requisitos foram apresentados por **Matheus**, representante da empresa e cliente final do projeto.  

Os processos de trabalho da empresa estavam dispersos entre diferentes equipes, tornando difícil acompanhar responsabilidades, auditar atividades e garantir que todas as etapas fossem executadas de maneira consistente. Como a operação logística possui rotinas específicas e grande volume de interações entre setores, surgiram problemas de comunicação, retrabalho e falta de rastreabilidade das ações, o que impactava diretamente a eficiência e a confiabilidade das operações.

Como solução, minha equipe criou o **Logflow**, um sistema web completo, projetado para otimizar processos de trabalho, promover a colaboração entre equipes e garantir a auditoria eficiente das atividades. O sistema oferece funcionalidades como:  

- **Descrição e monitoramento de fluxos de trabalho**, garantindo o cumprimento de cada etapa;  
- **Cadastro de clientes** para gerenciamento eficiente de informações;  
- **Dashboards com indicadores de desempenho** e **relatórios analíticos** para apoiar a tomada de decisões;  
- **Automação de faturamento**, otimizando processos financeiros;  
- **Roteirização de viagens**, facilitando o planejamento logístico;  
- **Portal do funcionário** para acesso a documentos pessoais e informações importantes;  
- **Ferramentas de comunicação interna**, como agenda e chat, promovendo integração e agilidade nas interações.  

Essa solução foi desenvolvida para atender às necessidades específicas da JJM LOG, garantindo maior eficiência operacional e melhor integração entre as equipes.

- [GIT](https://github.com/C0demain/logflow)

---

#### Tecnologias Utilizadas

As seguintes tecnologias foram utilizadas neste projeto:
- **Figma**: Ferramenta online para design e prototipação de interfaces, com colaboração em tempo real.  
- **Trello**: Plataforma de gerenciamento de tarefas baseada em quadros Kanban.  
- **Nest.js**: Framework Node.js para construção de APIs escaláveis.
- **Next.js**: Framework React para aplicações web com SSR e SSG.
- **TailwindCSS**: Framework CSS utilitário para estilização rápida.
- **DaisyUI**: Biblioteca de componentes pronta para TailwindCSS.
- **Docker**: Plataforma para criação e gerenciamento de contêineres.
- **Typescript**: Superset de JavaScript com tipagem estática.
- **TypeORM**: ORM para integração com bancos de dados relacionais.
- **PostgreSQL**: Banco de dados relacional robusto e extensível.
- **AWS**: Plataforma de serviços em nuvem escalável da Amazon.

---

#### Contribuições Pessoais

No projeto, atuei como membro do **Dev Team**, sendo responsável pela **containerização completa** utilizando **Docker** desde o início. Desenvolvi um Dockerfile para containerizar a API e configurei um docker-compose para orquestrar os contêineres do **banco de dados**, **frontend** e do serviço de gerenciamento de banco (**pgAdmin**).  

Essa abordagem proporcionou um ambiente de desenvolvimento **distribuído e consistente**, com melhor gerenciamento de dependências e eliminação de erros relacionados ao clássico problema "*funciona na minha máquina*".  

Também liderei o processo de **deploy na AWS**, garantindo uma transição eficiente do ambiente de desenvolvimento para produção.  

Além disso, implementei um **chat básico** para facilitar a comunicação interna entre os usuários da aplicação.

---

#### Hard Skills

Exercitei as seguintes hard skills durante esse projeto:
- **Nest.js**: Uso com autonomia;
- **Next.js**: Uso com ajuda;
- **Docker**: Uso com autonomia;
- **PostgreSQL**: Uso com autonomia;
- **AWS**: Uso com autonomia;
- **GitFlow** - Uso com autonomia;
- **Git Pull Requests** - Uso com autonoia
- **Typescript** - Uso com autonomia

---

#### Soft Skills

- **Gestão de Tempo Orientada ao Pipeline DevOps**: Estruturei minhas tarefas considerando dependências entre backend, frontend e infraestrutura. Planejei entregas críticas — como containerização com Docker, configuração de docker-compose e deploy na AWS — garantindo que estivessem prontas antes das integrações de equipe.

- **Compreensão de Fluxos Logísticos Reais**: Analisei detalhadamente os processos operacionais da JJM LOG, mapeando etapas, dependências e pontos de comunicação entre setores para garantir que a modelagem técnica refletisse corretamente a complexidade das operações logísticas.

- **Resolução de Problemas em Infraestrutura Distribuída**: Enfrentei e solucionei desafios relacionados à orquestração de múltiplos contêineres, compatibilidade de imagens, portas e redes internas, garantindo que os microsserviços funcionassem de forma integrada no ambiente de desenvolvimento e produção.

- **Suporte Técnico Interno (Docker e AWS)**: Auxiliei outros membros da equipe a compreender e operar contêineres, solucionar erros de build e configurar variáveis de ambiente, promovendo um ambiente de desenvolvimento mais uniforme e reduzindo o tempo gasto em dificuldades individuais.

- **Adaptabilidade a Mudanças de Arquitetura**: Ajustei rapidamente a estrutura do docker-compose, configuração da API ou ambiente AWS conforme surgiam novos requisitos ou descobertas durante o desenvolvimento, demonstrando flexibilidade e precisão técnica.

---

<div align="center">
<img src="./Imagens/banner-logflow.png" alt="LogFlow Logo"/>
</div>