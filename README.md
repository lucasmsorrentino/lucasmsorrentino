### Hi, I'm Lucas 👋

**I build LLM agents, RAG and GraphRAG systems, and automation for document-heavy, regulated workflows.**

I hold a technologist degree in Systems Analysis and Development (UNINTER) and a postgraduate specialization in Applied Artificial Intelligence (UFPR), and I'm now pursuing a second one, in Generative AI (UFPR). At the Innovation Studio of the Paraná State Court of Audit (TCE-PR), I develop generative AI tools that support audit work. I've been a public servant at the Federal University of Paraná (UFPR) since 2017, where I research AI for administrative processes. I also hold a BA in Social Sciences and spent three years on household surveys and territorial mapping at IBGE, Brazil's national statistics office.

I like systems that show where every answer came from and leave the decision with the person who is accountable for it.

Curitiba, Brazil (UTC−3) · [LinkedIn](https://www.linkedin.com/in/lucas-martins-sorrentino/)

---

#### Featured projects

| Project | What it does | Stack |
|---|---|---|
| [**ufpr-rag-api**](https://github.com/lucasmsorrentino/ufpr-rag-api) | Q&A over ~3,400 UFPR regulations (35k indexed chunks) with mandatory source citation. Two VMs on Oracle Cloud: the model sits on a private network with no exposed port. [Live app](https://ufpr-rag.tail9f5159.ts.net) | FastAPI, LanceDB, multilingual-e5-large, NVIDIA NIM |
| [**monitor_concursos_ti**](https://github.com/lucasmsorrentino/monitor_concursos_ti) | *AI-first* scraping: an LLM reads raw HTML, extracts structured data and classifies the stage of each public job exam. Telegram alerts only when the stage moves forward. 149 tests. | Python, Ollama / Claude, BeautifulSoup, SQLite, pytest |
| [**AgenteAgenda**](https://github.com/lucasmsorrentino/AgenteAgenda) | Personal Telegram agent connecting Google Calendar and Anytype, with natural-language recurrence and semantic search over notes. | Python, Claude Code (headless), APScheduler |
| [**observatorio-digital-bigdata-arch**](https://github.com/lucasmsorrentino/observatorio-digital-bigdata-arch) | Lambda architecture for monitoring disinformation and bot networks on social media. | Kafka, Spark, HDFS, polyglot persistence |
| [**ProdGenAI**](https://github.com/lucasmsorrentino/ProdGenAI) | Prompt-engineering chatbot on Llama 3.3 70B, taken from zero to production on an ARM VM. | Streamlit, NVIDIA NIM, Oracle Cloud |
| [**visuDados-storyTelling**](https://github.com/lucasmsorrentino/visuDados-storyTelling) | Data storytelling with Brazilian public health (SUS) data: racial inequalities in hospital admissions. | pandas, Base dos Dados, matplotlib |

#### Research

**Specialization thesis** (Applied AI, UFPR, 2026): *Generative AI agents for automating bureaucratic processes: scientific foundations and a self-optimization strategy.* Advisor: Prof. Jaime Wojciechowski, PhD.

**Thesis prototype** (private code): a LangGraph multi-agent pipeline that classifies administrative requests, retrieves the applicable rules through vector RAG (34k chunks, with RAPTOR) and a Neo4j knowledge graph (1,757 nodes, tracking whether each rule is still in force), and drafts replies for human review. Nothing goes out without a person's approval. It includes a deterministic playbook for recurring cases, a memory of past mistakes and 897 automated tests.

Some projects are private because they involve institutional systems. I'm happy to walk through them in a conversation.

Interests: human-in-the-loop LLM agents, automatic prompt optimization, hybrid vector-graph RAG over regulatory documents, and computational social science (disinformation, algorithmic pricing, health inequalities).

#### Toolbox

**AI & data:** Python, LangGraph, LangChain, LiteLLM, Ollama, LanceDB, Milvus, Pinecone, Neo4j, TensorFlow/Keras, pandas, R<br>
**Backend & infra:** FastAPI, Flask, SQL Server, SQLite, Docker, Oracle Cloud, Tailscale<br>
**Also:** JavaScript, Flutter, C#/.NET, Microsoft Power Platform

#### Education

- Postgraduate Specialization in Generative AI, UFPR (2026–2027, in progress)
- Postgraduate Specialization in Applied Artificial Intelligence, UFPR (2025–2026)
- Technologist degree in Systems Analysis and Development, UNINTER (2023–2025)
- BA in Social Sciences, UFPR (2006–2012)

<details>
<summary><b>Versão em português</b></summary>

<br>

**Construo agentes de LLM, sistemas de RAG e automações para processos regulados e cheios de documentos.**

Sou tecnólogo em Análise e Desenvolvimento de Sistemas (UNINTER) e especialista em Inteligência Artificial Aplicada (UFPR), e curso uma segunda especialização, em IA Generativa (UFPR). No Estúdio de Inovação do Tribunal de Contas do Estado do Paraná (TCE-PR), desenvolvo ferramentas de IA generativa de apoio à auditoria. Sou servidor da Universidade Federal do Paraná (UFPR) desde 2017, onde pesquiso IA para processos administrativos. Também sou bacharel em Ciências Sociais e trabalhei três anos no IBGE, com pesquisas domiciliares e base territorial.

Gosto de sistemas que mostram de onde tiraram cada resposta e que deixam a decisão com quem é responsável por ela.

Curitiba, Brasil · [LinkedIn](https://www.linkedin.com/in/lucas-martins-sorrentino/)

#### Projetos em destaque

| Projeto | O que faz | Stack |
|---|---|---|
| [**ufpr-rag-api**](https://github.com/lucasmsorrentino/ufpr-rag-api) | Perguntas e respostas sobre ~3.400 normas da UFPR (35 mil trechos indexados), com citação obrigatória da fonte. Duas VMs na Oracle Cloud: o modelo fica numa rede privada, sem porta exposta. [App no ar](https://ufpr-rag.tail9f5159.ts.net) | FastAPI, LanceDB, multilingual-e5-large, NVIDIA NIM |
| [**monitor_concursos_ti**](https://github.com/lucasmsorrentino/monitor_concursos_ti) | Scraping *AI-first*: uma LLM lê o HTML, extrai dados estruturados e classifica a fase de cada concurso. Só avisa no Telegram quando a fase avança. 149 testes. | Python, Ollama / Claude, BeautifulSoup, SQLite, pytest |
| [**AgenteAgenda**](https://github.com/lucasmsorrentino/AgenteAgenda) | Agente pessoal no Telegram que liga Google Calendar e Anytype, com recorrência em linguagem natural e busca semântica nas notas. | Python, Claude Code (headless), APScheduler |
| [**observatorio-digital-bigdata-arch**](https://github.com/lucasmsorrentino/observatorio-digital-bigdata-arch) | Arquitetura Lambda para monitorar desinformação e redes de bots em mídias sociais. | Kafka, Spark, HDFS, persistência poliglota |
| [**ProdGenAI**](https://github.com/lucasmsorrentino/ProdGenAI) | Chatbot de engenharia de prompt com Llama 3.3 70B, do zero até produção numa VM ARM. | Streamlit, NVIDIA NIM, Oracle Cloud |
| [**visuDados-storyTelling**](https://github.com/lucasmsorrentino/visuDados-storyTelling) | Storytelling com dados do SUS: desigualdades raciais em internações hospitalares. | pandas, Base dos Dados, matplotlib |

#### Pesquisa

**TCC da especialização** (IA Aplicada, UFPR, 2026): *Agentes de IA generativa para automação de processos burocráticos: fundamentos científicos e estratégia de auto-otimização.* Orientador: Prof. Dr. Jaime Wojciechowski.

**Protótipo do TCC** (código privado): pipeline multiagente em LangGraph que classifica demandas administrativas, busca as normas aplicáveis por RAG vetorial (34 mil trechos, com RAPTOR) e por um grafo de conhecimento em Neo4j (1.757 nós, com a vigência de cada norma) e prepara rascunhos de resposta para revisão humana. Nada sai sem uma pessoa aprovar. Inclui playbook determinístico para casos recorrentes, memória de erros passados e 897 testes automatizados.

Alguns projetos são privados porque envolvem sistemas institucionais. Posso apresentá-los em conversa.

Interesses: agentes de LLM com supervisão humana, otimização automática de prompts, RAG híbrido (vetor + grafo) para documentos normativos e ciência social computacional (desinformação, precificação algorítmica, desigualdades em saúde).

#### Ferramentas

**IA e dados:** Python, LangGraph, LangChain, LiteLLM, Ollama, LanceDB, Milvus, Pinecone, Neo4j, TensorFlow/Keras, pandas, R<br>
**Back-end e infraestrutura:** FastAPI, Flask, SQL Server, SQLite, Docker, Oracle Cloud, Tailscale<br>
**Também:** JavaScript, Flutter, C#/.NET, Microsoft Power Platform

#### Formação

- Especialização em IA Generativa, UFPR (2026–2027, em andamento)
- Especialização em Inteligência Artificial Aplicada, UFPR (2025–2026)
- Tecnologia em Análise e Desenvolvimento de Sistemas, UNINTER (2023–2025)
- Bacharelado em Ciências Sociais, UFPR (2006–2012)

</details>
