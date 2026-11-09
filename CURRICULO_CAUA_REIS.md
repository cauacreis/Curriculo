# CAUÃ FELYPE CAETANO REIS
**Desenvolvedor Full-Stack · Engenheiro de Software & IA · Java 21 / Python / TypeScript**  
Itaguaru, GO — Brasil · (62) 9 9452-1953 · [caua.reis.dev@gmail.com](mailto:caua.reis.dev@gmail.com)  
[linkedin.com/in/cauafelypereis](https://linkedin.com/in/cauafelypereis) · [github.com/cauacreis](https://github.com/cauacreis) · [Portfólio / Vercel](https://gymflow-weld.vercel.app)

---

## RESUMO PROFISSIONAL

Engenheiro de Software e Desenvolvedor Full-Stack (4º período na UniEVANGÉLICA) com histórico comprovado de concepção, arquitetura e entrega de produtos digitais de alta complexidade em produção. Arquiteto e operador do **SKZ Trading**, plataforma SaaS de arbitragem algorítmica com 11 microserviços assíncronos em Python rodando 24/7 (99,9% uptime, latência < 100ms e liquidação PIX automatizada). Coautor de artigo científico submetido à **IEEE Transactions on Software Engineering** sobre IA Explicável (XAI/SHAP) e arquitetura Multi-Agentes (MAS/MoE) na plataforma mineral **OrenAI**. Experiência sólida em sistemas concorrentes de alta escala com **Java 21 (Virtual Threads, Spring Boot 3)**, pipelines assíncronos em **Python (AsyncIO, FastAPI)**, frontend moderno com **React 19 / Next.js / TypeScript**, engenharia de agentes autônomos de IA e fundamentos de baixo nível em **C (desenvolvimento de microkernel x86)**.

---

## HABILIDADES TÉCNICAS

- **Linguagens:** TypeScript, JavaScript (ESNext), Python 3.11+, Java 21, C, PHP, SQL
- **Frontend & Mobile:** React Native (Expo SDK 58), Next.js (App Router), React 19/18, TypeScript, Tailwind CSS, Vite, Three.js (WebGL 3D), Capacitor (Android/Play Store), PWA, Recharts, Lucide Icons
- **Backend & Arquitetura:** Java 21 (Virtual Threads, Spring Boot 3.3, Spring Security, JPA), Python (AsyncIO, aiohttp, FastAPI), Node.js, PHP, Multi-Tenant SaaS (`TenantContext`), Arquitetura Hexagonal, Microserviços, WebSockets em tempo real, REST APIs
- **IA, Agentes & LLMs:** Sistemas Multi-Agentes (MAS), Mixture of Experts (MoE), XAI (SHAP), Claude Sonnet, OpenAI API, Groq (Llama 3), Google Gemini API, RAG, Engenharia de Prompt, WhatsApp Automation (Baileys & Meta Business API), Telegram Bots API
- **Bancos de Dados:** PostgreSQL, MySQL, Supabase, SQLite (Local-First / Outbox), Redis, H2 In-Memory, PostGIS
- **Cloud, DevOps & Ferramentas:** Docker, Docker Compose, Linux/VPS, Nginx, PM2, Vercel, Oracle Cloud Infrastructure, Git/GitHub, CI/CD (GitHub Actions), Bash/PowerShell
- **Segurança & Resiliência:** Hardening OWASP Top 10, Criptografia AES / Ed25519, Row-Level Security (RLS), JWT com claims multi-tenant, Rate Limiting (Bucket4j), Optimistic Locking (`@Version`), Prevenção de XSS/SQLi
- **Metodologias:** Scrum (SFC™ Certified), Agile, Design Thinking, Clean Code & AOP

---

## EXPERIÊNCIA PROFISSIONAL

### **Full-Stack Developer & Arquiteto de Software** | SKZ Trading (*skztrading.com*)
*Jul 2026 – Presente | Produção 24/7*
*Plataforma SaaS de arbitragem automatizada e liquidação de ativos digitais integrada à API DMarket v2.*
- **Arquitetura de Microserviços:** Arquitetei e implantei 11 microserviços assíncronos em Python (`asyncio`, `aiohttp`) orquestrados via PM2 em VPS Linux, automatizando 100% do ciclo de descoberta, precificação e execução com varredura a cada 20 segundos.
- **Motor de Precificação Dinâmica:** Desenvolvi algoritmo proprietário com score de liquidez (0–100 em 4 camadas de análise), aplicando desconto mínimo de 12% na compra, margem líquida alvo de 15% na venda e trava anti-prejuízo que impossibilita alienações abaixo do custo.
- **Pipeline Financeiro & Multi-Tenant:** Modelei banco MySQL e pipeline automatizado de comissionamento sobre o lucro líquido (30%), com liquidação instantânea via webhooks do Mercado Pago (PIX) e bloqueio automático por inadimplência.
- **Painel em Tempo Real & Métricas:** Desenvolvi dashboard executivo em React (Vite) + PHP com autenticação 2FA por QR Code, inventário em tempo real e tracking operacional — somando mais de 200 operações concluídas e 99,9% de uptime mantido.
- **Hardening de Segurança:** Implementei criptografia assimétrica/simétrica local no servidor (Ed25519/AES) alinhada ao OWASP Top 10, eliminando a exposição de chaves privadas em trânsito e assegurando segredo absoluto de credenciais.

---

## PROJETOS DE ENGENHARIA EM DESTAQUE

### **OrenAI — SaaS B2B de Prospectividade Mineral & Artigo Científico (IEEE TSE)**
*Líder Técnico & Arquiteto de Software / MAS | 2025 – Presente*
- **Arquitetura Multi-Agentes (MAS / MoE):** Arquitetei sistema distribuído em contêineres Docker isolados por commodity mineral, reduzindo o risco e custo de furos secos de sondagem (mercado global de US$ 12B/ano).
- **Ensemble MAPDA & XAI:** Co-desenvolvi motor preditivo combinando Gradient Boosting (XGBoost/LightGBM) para dados geoquímicos tabulares com CNNs para imagens espaciais, integrando interpretabilidade matemática via SHAP (100% dos alvos explicados sem modelo caixa-preta).
- **Interface HITL & Visualização 3D:** Desenvolvi visualizador 3D de subsuperfície em Three.js/WebGL com malhas e nuvens de pontos de corpos mineralizados, mapa geoespacial 2D interativo e fluxo Human-in-the-Loop com Active Learning.
- **Artigo IEEE:** Coautor de artigo científico submetido à conceituada revista *IEEE Transactions on Software Engineering* (status: aguardando aprovação dos autores), responsável pelos diagramas de arquitetura, modelagem lógica de dados e especificação formal.

### **Bodega do Vidigal — Sistema de Gestão de Pedidos Offline-First (POS & KDS)**
*Arquiteto de Software & Engenheiro Mobile | React Native (Expo SDK 58) | 2026*
- **Arquitetura Offline-First & P2P Sem Internet:** Concepção e entrega de ecossistema completo de Ponto de Venda (POS) e Tela de Cozinha (KDS) operando 100% offline via roteador Wi-Fi direto do aparelho móvel (hotspot local), sincronizando comandas por WebSockets com latência < 10ms e zero custo de infraestrutura de rede ou dados móveis.
- **Persistência Local & Outbox Pattern:** Modelei banco local SQLite com arquitetura transacional tolerante a falhas (Outbox pattern), assegurando persistência atômica, histórico de turnos e zero duplicidade de comandas mesmo em caso de desligamento abrupto de terminais.
- **Fila FIFO & "Contador de Carnes" Touchless:** Desenvolveu interface KDS desenhada para operação sob calor e gordura na chapa, integrando somador automático em tempo real da quantidade de blends necessários por prioridade cronológica (FIFO) sem necessidade de toque constante na tela.
- **Testes & Confiabilidade Operacional:** Implementou esteira de 37 testes automatizados (unitários e ponta a ponta via Jest) cobrindo ciclo de vida de pedidos, confirmação de entrega pelo balcão, observações customizadas por item e auto-reset programado no fechamento.

### **GymFlow — Plataforma Mobile-First Smart Gym SaaS**
*Arquiteto de Software & Engenheiro Full-Stack | Set 2026 | [gymflow-weld.vercel.app](https://gymflow-weld.vercel.app)*
- **Arquitetura Mobile-First & Play Store Ready:** Desenvolvido em Next.js 14, TypeScript e Tailwind CSS, otimizado para smartphones com viewport nativo (`viewport-fit=cover`), navegação háptica e ponte Capacitor Android pronta para empacotamento APK/AAB.
- **Catraca Digital Anti-Fraude (GymFlow Pass):** Criei token rotativo criptografado em QR Code de alta resolução com renovação a cada 30 segundos em memória, prevenindo compartilhamento indevido de telas ou fraudes de portaria.
- **Ficha Interativa & Carga Dinâmica:** Implementei construtor de treinos (Split A/B/C) com contagem regressiva háptica de descanso e cálculo em tempo real de tonelagem e volume de carga levantada.
- **GymBot AI & Monetização:** Integrei assistente com motor duplo (conhecimento biomecânico determinístico + Google Gemini API) e checkout com Mercado Pago (PIX e cartão de crédito).

### **LeadProspector & LinkedinTalk — Agentes Autônomos de IA & Prospecção B2B**
*Arquiteto de Software & Engenheiro de IA (Open Source) | 2025 – 2026*
- **Agente Autônomo WhatsApp (LeadProspector):** Construí sistema autônomo (Python 3.11, Docker Compose, Redis, PostgreSQL) que integra 9 fontes de dados (Apollo, Hunter, Google Maps, LinkedIn), scoring híbrido de ICP (regras 40% + LLM 60%) e máquina de estados de 8 estágios com suporte dual a Baileys e Meta Business API.
- **Copiloto Human-in-the-Loop (LinkedinTalk):** Criei copiloto de personal branding em Python (FastAPI) e TypeScript com banco Postgres/SQLite, arquitetura defensiva anti-ban, testes automatizados e esteira de CI/CD via GitHub Actions.

### **CoreSync CRM & NexoTrade-OS — Engenharia Backend de Alta Performance**
*Engenheiro Backend Java 21 / Spring Boot 3 | 2026*
- **Isolamento Multi-Tenant (CoreSync CRM):** Projetei SaaS B2B com Spring Boot 3.2 e Java 21, utilizando partição de inquilinos em memória com `TenantContext` via `ThreadLocal` ancorado no token JWT, auditoria limpa com Spring AOP e orquestração via Telegram Bot com Groq (Llama 3) e Whisper.
- **Motor Financeiro de Baixa Latência (NexoTrade-OS):** Desenvolvi engine de paper trading consumindo stream de cotações em tempo real da Binance via WebSockets, orquestrado com Java 21 Virtual Threads e robô autônomo de arbitragem por volatilidade de Média Móvel (SMA-50).

### **MicroOS — Microkernel x86 32-bit em C do Zero**
*Desenvolvedor de Sistemas Operacionais | 2026*
- Desenvolvi microkernel educacional x86 em C e Assembly (GAS) executado no QEMU via Multiboot, com paginação de 2 níveis, isolamento de processos em Ring 3, escalonador round-robin preemptivo (PIT 100Hz), troca de contexto, IPC por portas/mensagens e drivers em userspace.

---

## FORMAÇÃO ACADÊMICA

- **Bacharelado em Engenharia de Software** — UniEVANGÉLICA (Anápolis, GO)  
  *Fev 2025 – Dez 2028 (Previsão) · 4º Período*
  - **Liderança & Atividades:** Vice-Presidente do Diretório Acadêmico CodeUp; Diretor de Artes & Cultura (E-games / Robocode).
  - **Reconhecimentos:** Finalista do Start Agro Innovation 2025; Participante do PuzzleWeek 2025.
- **Trilha de Certificação: Programador Desktop** — Instituto Mix  
  *Out 2022 – Jun 2024*  
  - Formação prática em Banco de Dados, C#, Java, Lógica de Programação, POO e Modelagem UML.

---

## CERTIFICAÇÕES & IDIOMAS

- **Certificações:**  
  - Scrum Fundamentals Certified (SFC™) — SCRUMstudy (ID Cert: 03/2026)  
  - Storytelling e Comunicação Técnica — UniEVANGÉLICA (2025)
- **Idiomas:**  
  - Português: Nativo  
  - Inglês: Avançado (Leitura técnica, escrita de artigos científicos e conversação profissional)  
  - Espanhol: Básico
