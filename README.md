### Olá, eu sou o Lucas 👋

**IA generativa aplicada ao setor público:** agentes de LLM, RAG com citação de fonte e automação de processos administrativos.

Sou cientista social e de dados em Curitiba. Trabalho onde a burocracia encontra a IA. Sou servidor da UFPR desde 2017 e pesquiso automação de processos administrativos com IA. No Estúdio de Inovação do TCE-PR, desenvolvo ferramentas de IA generativa de apoio à auditoria. Antes, trabalhei com pesquisas amostrais e base territorial no IBGE (PNAD Contínua, PeNSE). Gosto de sistemas que mostram de onde tiraram cada resposta e que deixam a decisão com quem é responsável por ela.

[LinkedIn](https://www.linkedin.com/in/lucas-martins-sorrentino/) · [Lattes](COLE_AQUI_O_LINK_DO_LATTES) · [ORCID](COLE_AQUI_O_LINK_DO_ORCID)

---

#### Projetos em destaque

| Projeto | O que faz | Stack |
|---|---|---|
| [**ufpr-rag-api**](https://github.com/lucasmsorrentino/ufpr-rag-api) | Perguntas e respostas sobre ~3.400 normas da UFPR (35 mil trechos indexados), com citação obrigatória da fonte. Duas VMs na Oracle Cloud: o modelo fica numa rede privada, sem porta exposta. [App no ar](https://ufpr-rag.tail9f5159.ts.net) | FastAPI, LanceDB, multilingual-e5-large, NVIDIA NIM |
| [**monitor_concursos_ti**](https://github.com/lucasmsorrentino/monitor_concursos_ti) | Scraping *AI-first*: uma LLM lê o HTML, extrai dados estruturados e classifica a fase de cada concurso. Só avisa no Telegram quando a fase avança. 149 testes. | Python, Ollama / Claude, BeautifulSoup, SQLite, pytest |
| [**AgenteAgenda**](https://github.com/lucasmsorrentino/AgenteAgenda) | Agente pessoal no Telegram que liga Google Calendar e Anytype. Entende recorrência em linguagem natural e faz busca semântica nas notas. | Python, Claude Code headless, APScheduler |
| [**observatorio-digital-bigdata-arch**](https://github.com/lucasmsorrentino/observatorio-digital-bigdata-arch) | Arquitetura Lambda para monitorar desinformação e redes de bots em mídias sociais. | Kafka, Spark, HDFS, persistência poliglota |
| [**ProdGenAI**](https://github.com/lucasmsorrentino/ProdGenAI) | Chatbot de engenharia de prompt com Llama 3.3 70B, do zero até produção numa VM ARM. | Streamlit, NVIDIA NIM, Oracle Cloud |
| [**visuDados-storyTelling**](https://github.com/lucasmsorrentino/visuDados-storyTelling) | Storytelling com dados do SUS: desigualdades raciais em internações hospitalares. | pandas, Base dos Dados, matplotlib |

#### Pesquisa

**Memorial de projetos (TCC):** *Agentes de IA generativa para automação de processos burocráticos: fundamentos científicos e estratégia de auto-otimização.* Especialização em Inteligência Artificial Aplicada, UFPR, 2026. Orientador: Prof. Dr. Jaime Wojciechowski. [PDF](COLE_AQUI_O_LINK_DO_TCC)

**Protótipo do TCC** (código privado): agentes em LangGraph que classificam demandas administrativas, consultam normas por RAG vetorial (34 mil trechos, com RAPTOR) e por um grafo de conhecimento em Neo4j (1.757 nós, com a vigência de cada norma) e preparam rascunhos para revisão humana. Nada sai sem uma pessoa aprovar. Inclui playbook determinístico para casos recorrentes, memória de erros passados e 897 testes automatizados.

Alguns projetos são privados porque envolvem sistemas institucionais. Posso apresentá-los em conversa.

Interesses: agentes de LLM com supervisão humana, otimização automática de prompts, RAG híbrido (vetor + grafo) para documentos normativos e ciência social computacional (desinformação, precificação algorítmica, desigualdades em saúde).

#### Ferramentas

**IA e dados:** Python, LangChain, Ollama, LanceDB, Milvus, Pinecone, TensorFlow/Keras, pandas, R<br>
**Back-end e infraestrutura:** FastAPI, Flask, SQL Server, SQLite, Docker, Oracle Cloud, Tailscale<br>
**Também:** JavaScript, Flutter, C#/.NET, Microsoft Power Platform

#### Formação

- Especialização em IA Generativa, UFPR (2026–2027, em andamento)
- Especialização em Inteligência Artificial Aplicada, UFPR (2025–2026)
- Tecnologia em Análise e Desenvolvimento de Sistemas, UNINTER (2023–2025)
- Bacharelado em Ciências Sociais, UFPR (2006–2012)

<details>
<summary><b>English</b></summary>

I'm a social and data scientist in Curitiba, Brazil, working on **generative AI for the public sector**: LLM agents, retrieval-augmented generation with mandatory source citation, and automation of administrative processes. I have been a public servant at the Federal University of Paraná (UFPR) since 2017, and I am an intern at the Innovation Studio of the Paraná State Court of Audit (TCE-PR), building generative AI tools that support audit work. Before that, I worked on household surveys and territorial mapping at IBGE, Brazil's national statistics office. I hold a BA in Social Sciences (UFPR) and a degree in Systems Analysis and Development (UNINTER).

My specialization thesis prototype (private code) is a LangGraph multi-agent pipeline that classifies administrative requests, retrieves regulations through vector RAG (34k chunks, RAPTOR) and a Neo4j knowledge graph (1,757 nodes, tracking whether each rule is in force), and drafts replies for human review. Nothing goes out without a person's approval. 897 automated tests.

Research interests: human-in-the-loop LLM agents, automatic prompt optimization, hybrid vector-graph RAG over regulatory documents, and computational social science.

</details>
