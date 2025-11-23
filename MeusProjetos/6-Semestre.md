### Sexto Semestre (2025-2)

No sexto semestre do curso de **Análise e Desenvolvimento de Sistemas da Fatec São José dos Campos**, desenvolvemos um projeto em parceria com a **Xertica**, empresa com referência internacional no ramo de desenvolvimento de soluções inteligentes utilizando IAs. O desafio apresentado tinha como requisito o uso do **Google Agent Development Kit (ADK)** — um framework moderno voltado à criação de agentes de inteligência artificial. 

A área de nutrição enfrenta um desafio recorrente: muitas pessoas têm dificuldade em compreender conceitos nutricionais, interpretar necessidades metabólicas e transformar essas informações em hábitos alimentares coerentes com seus objetivos. Além disso, profissionais e estudantes lidam com grande volume de dados — como cálculos de taxa metabólica, estimativas energéticas, composição de alimentos e anamnese — tornando o processo de orientação mais lento e sujeito a variações de interpretação. Essa combinação de informações complexas e dispersas dificulta oferecer recomendações precisas, consistentes e personalizadas, especialmente quando cada indivíduo possui perfis metabólicos e rotinas muito diferentes.

A solução desenvolvida, denominada **NutriXpert**, teve como objetivo a criação de um **agente conversacional inteligente para nutrição**, capaz de oferecer orientações alimentares, cálculos metabólicos, planos personalizados com base em dados reais de composição nutricional e anamnese do usuário.

O **NutriXpert** foi concebido como um sistema multiagente, no qual um **agente raiz (Root Agent)** coordena múltiplos **subagentes especializados** — cada um responsável por um domínio do conhecimento nutricional (como metabolismo, planejamento alimentar, educação nutricional e cálculo de macronutrientes).

Em resumo, o foco do projeto foi desenvolver habilidades relacionadas a machine learning e fine tuning utilizando o **Google Agent Development Kit (ADK)**.

- [GIT](https://github.com/C0demain/nutriXpert)

---

#### Tecnologias Utilizadas

As tecnologias e ferramentas aplicadas durante o desenvolvimento do **NutriXpert** incluem:

* **Python (ADK / FastAPI)** – Criação dos agentes e endpoints de orquestração;
* **Google Agent Development Kit (ADK)** – Framework principal para estruturação do sistema multiagente;
* **PostgreSQL** – Banco de dados para persistência de contexto, logs e informações nutricionais;
* **ChromaDB** - Banco de dados para persistência de dados vetoriais;
* **RAG (Retrieval-Augmented Generation)** – Técnica aplicada para permitir respostas contextualizadas a partir de documentos nutricionais confiáveis;
* **LangChain** – Framework que integra modelos de linguagem (LLMs) com fluxos de dados e armazenamento vetorial.
* **PDFPlumber** - Ferramenta usada para extração de texto de documentos PDF, preservando estrutura e legibilidade do conteúdo original.
* **Pandas** - Biblioteca utilizada para leitura e tratamento dos dados da tabela taco em formato Excel.
* **Hugging Face Transformers** - Gera embeddings semânticos dos chunks de texto, permitindo busca vetorial por similaridade durante a recuperação de contexto.
* **Gemini Flash Model** – Utilização do modelo 'gemini-2.0-flash' para inferência dos agentes;
* **Vue.js / Nuxt 3** – Interface front-end para interação com o agente e visualização dos resultados;
* **TailwindCSS** – Estilização e responsividade do front-end.

---

#### Contribuições Pessoais

Atuei principalmente na **engenharia dos agentes e na arquitetura de orquestração multiagente**, sendo responsável por:

* **Desenvolvimento da lógica de orquestração do Root Agent**, responsável por delegar tarefas aos subagentes de nutrição, metabolismo, planejamento e educação alimentar;
* **Implementação do pipeline RAG**, integrando o banco vetorial e a busca contextual para fornecer respostas fundamentadas na base TACO;
* **Criação e modelagem da tabela TACO no PostgreSQL**, garantindo normalização e acesso eficiente às informações nutricionais de cada alimento;
* **Definição e refinamento dos prompts de cada subagente**, assegurando coerência entre os papéis (ex: Agente_Nutricional, Agente_Metabólico, Agente_Planejamento e Agente_Educativo);
* **Implementação do HITL (Human In The Loop)**, permitindo que o usuário avalie cada resposta do agent, gerando um feedback via ação humana, e contribundo no aprendizado de máquina para gerar novas respostas personalizadas.
* **Implementação da Geração de Insights Automáticos**, permitindo ao usuário um feedback educativo e amigável acerca de como está sendo seu padrão de alimentação, sono, atividade fisica e demais pontos existentes na anamnese desenvolvida de forma personalizada de acordo com os requisitos do cliente. 

---

#### Hard Skills

* **Python (FastAPI / ADK)**: Uso com autonomia;
* **RAG (Retrieval-Augmented Generation)**: Uso com autonomia;
* **PostgreSQL**: Uso com autonomia;
* **LangChain / ChromaDB**: Uso com autonomia;
* **Vue.js / Nuxt 3**: Uso com ajuda;
* **TailwindCSS**: Uso com ajuda;
* **Prompt Engineering**: Uso com ajuda;
* **GitFlow**: Uso com autonomia.

---

#### Soft Skills

* **Autonomia Técnica**: Fui responsável por conectar os módulos do sistema e implementar soluções de RAG e banco de dados, garantindo a consistência da base de conhecimento do agente.

* **Documentação e Clareza Técnica**: Mantive descrições completas sobre os prompts, fluxos de decisão e funções dos subagentes, facilitando a manutenção e o entendimento do time. Exemplo: criação de workflows e READMES.md bem descritivos. 

* **Resolução de Problemas**: Enfrentei desafios relacionados ao balanceamento de contexto e otimização de memória dos modelos de linguagem, aplicando estratégias de chunking e compressão vetorial.

* **Pesquisa Aplicada**: Investiguei técnicas modernas de RAG e ajuste de prompts baseadas em publicações recentes para maximizar a precisão das respostas geradas.

* **Colaboração Multidisciplinar**: Trabalhei junto a colegas das áreas de IA e Front-end, garantindo integração segura entre backend spring boot e as interfaces de usuário (Vue.js).

* **Adaptabilidade em Ambientes de Evolução Tecnológica**: Consegui me adaptar rapidamente a mudanças frequentes nas APIs, frameworks e bibliotecas de IA, revisando abordagens e incorporando novas ferramentas conforme surgiam, sem comprometer a estabilidade do sistema. Este foi um projeto bem diferentes dos anteriores APIs, isso porque o CRUD não foi o foco da solução desenvolvida.

* **Organização Pessoal**: Utilizei pela primeira a ferramenta Jira, e foi de grande importância para organização de tempo, para entender o que os demais integrantes estavam realizando, quais tarefas já foram finalizadas, e quais ainda estavam pendentes.

---

<div align="center">
  <img src="./Imagens/banner-nutrixpert.png" alt="NutriXpert Banner" />
</div> 