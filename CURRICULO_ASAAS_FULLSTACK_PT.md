# CAUÃ FELYPE CAETANO REIS
**Engenheiro(a) de Software Full Stack · TypeScript, Node.js, Java (Spring Boot), Python & Bancos Relacionais**  
Goiás — Brasil (100% Remoto) · (62) 9 9452-1953 · [caua.reis.dev@gmail.com](mailto:caua.reis.dev@gmail.com)  
[linkedin.com/in/cauafelypereis](https://linkedin.com/in/cauafelypereis) · [github.com/cauacreis](https://github.com/cauacreis) · [Portfólio / Vercel](https://gymflow-weld.vercel.app)

---

## RESUMO PROFISSIONAL

Engenheiro de Software Full Stack (cursando **Engenharia de Software** na UniEVANGÉLICA — 4º período, aulas noturnas com disponibilidade integral) com foco em entregas sólidas, código limpo e sistemas transacionais críticos em produção. Arquiteto e operador do **SKZ Trading**, plataforma SaaS financeira rodando 24/7 com liquidação instantânea e conciliação de comissões via **webhooks PIX (Mercado Pago)**, bloqueio automático por inadimplência e **99,9% de uptime**. Criador do **PersonalAgro ("Zé Agro")** no **NASA Space Apps Challenge**, ecossistema full-stack em **Node.js / Express + PostgreSQL (Supabase)** com 15 mil+ linhas em 30 módulos, 10 endpoints REST, arquitetura multi-agente com failover e **925 asserções de testes automatizados**. Forte domínio em **POO**, **Java 21 / Spring Boot 3**, **TypeScript / React / Next.js**, **Python**, bancos relacionais (**PostgreSQL, MySQL, SQL Server**), pipelines CI/CD com **Git**, princípios **SOLID/Clean Code** e coautoria científica submetida à **IEEE TSE**, com inglês avançado.

---

## HABILIDADES TÉCNICAS & BOAS PRÁTICAS

- **Backend, POO & APIs REST:** TypeScript, Node.js (Express), Java 21 (Spring Boot 3.3, Spring Security, JPA, AOP, Virtual Threads), Python (FastAPI, AsyncIO), C# (.NET), Integração entre Serviços via APIs RESTful, Webhooks Idempotentes e WebSockets
- **Frontend Web:** HTML5, CSS3, JavaScript (ESNext), TypeScript, React 19/18, Next.js (App Router), Vue.js, Tailwind CSS, Vite, Design Responsivo
- **Bancos de Dados Relacionais:** PostgreSQL, Supabase (RLS, PostGIS), MySQL, SQL Server (T-SQL), SQLite (Outbox Pattern), Redis, Modelagem Relacional (3FN), Joins, Índices e Transações ACID
- **Qualidade, Testes & Engenharia de Software:** Clean Code, Princípios SOLID, Design Patterns, Modelagem UML, Testes Automatizados (**925 asserções** no PersonalAgro, **37 testes Jest** no Bodega, JUnit/Pytest), Hardening OWASP Top 10 e Criptografia Ed25519/AES
- **Deploy, Versionamento & Agilidade:** Git & GitHub (GitFlow, Pull Requests, Code Review), CI/CD (GitHub Actions), Docker, Docker Compose, Linux/VPS, PM2, Nginx, Vercel, Scrum (Certificação SFC™)
- **IA Aplicada & Multimídia:** Sistemas Multi-Agentes (MAS/MoE), XAI (SHAP), Groq, Gemini, Cerebras, Whisper/TTS, FFmpeg, Failover Multi-Provedor e Otimização de Contexto/Tokens

---

## EXPERIÊNCIA EM PRODUÇÃO & SISTEMAS FINANCEIROS

### **Desenvolvedor Full Stack & Arquiteto de Software** | SKZ Trading (*skztrading.com*)
*Jul 2026 – Presente | Produção 24/7 — Ambiente Financeiro Real*
- **Conciliação Financeira, PIX & Regra de Inadimplência:** Modelei banco relacional MySQL com transações ACID e pipeline de cobrança automatizado sobre lucro líquido (30%), realizando liquidação instantânea via **webhooks do Mercado Pago (PIX)** e bloqueio automático por inadimplência.
- **Integrações REST, Concorrência & Disponibilidade:** Arquitetei 11 microsserviços assíncronos em Python (`asyncio`, `aiohttp`) orquestrados via PM2 em VPS Linux, integrados à API DMarket v2 com latência < 100ms e **99,9% de uptime** em mais de 200 operações concluídas.
- **Motor Anti-Prejuízo & Painel Executivo:** Desenvolvi algoritmo de precificação com score de liquidez (0–100) e trava contra vendas abaixo do custo, além de painel web em React (Vite) + PHP com 2FA por QR Code e criptografia Ed25519/AES (OWASP Top 10).

### **PersonalAgro ("Zé Agro") — Full-Stack Node.js, PostgreSQL & Multi-Agentes | NASA Space Apps Challenge**
*Criador & Engenheiro Full Stack / IA | Node.js, Express, Supabase/PostgreSQL | 2026*
- **Arquitetura Modular & Testes (925 Asserções):** Construí codebase completo com **15 mil+ linhas em 30 módulos**, motor determinístico de rotação de culturas, painel geoespacial (`/rotacao`) e **10 endpoints REST** em Node.js/Express + PostgreSQL, sustentado por **925 asserções em 4 suítes de testes automatizados**.
- **Integração Multi-API & Ciência Espacial:** Integrei em tempo real APIs da **NASA POWER** (`GWETROOT`), **NASA GIBS** (MODIS NDVI e SMAP L4), Open-Meteo (FAO ET0 14d), IBGE (SIDRA PAM), CEASA e ANP/Diesel com foco em confiabilidade e simplicidade de uso.
- **Multi-Agentes de Baixo Custo & Validação Real:** Orquestrei **10 agentes especialistas** e 16 ferramentas com failover automático (Groq, Gemini, Cerebras), reduzindo contexto Embrapa em >55%, schema em até 75% e modo degradado em 98% (`24,2k → 493 chars`), além de WhatsApp acessível (`FFmpeg` + Whisper/Gemini + TTS fonético) e trava anti-efeito manada (CEASA, cooperativas e CONAB/PAA/PNAE) validado com **26 usuários reais**.

---

## PROJETOS DE ENGENHARIA WEB, JAVA/SPRING & TESTES

### **CoreSync CRM & NexoTrade-OS — Java 21, Spring Boot 3 & Multi-Tenant SaaS**
*Desenvolvedor Backend Java / Spring Boot | 2026*
- **Spring Boot 3, POO & Auditoria Limpa:** Projetei SaaS B2B Multi-Tenant em **Java 21 e Spring Boot 3.2** utilizando partição segura por inquilino com `TenantContext` (`ThreadLocal` ancorado no token JWT), auditoria declarativa com **Spring AOP** e engine em tempo real consumindo WebSockets com Virtual Threads.

### **GymFlow — Aplicação Web SaaS Full-Stack (Next.js / TypeScript / PIX)**
*Arquiteto & Desenvolvedor Full Stack | Set 2026 | [gymflow-weld.vercel.app](https://gymflow-weld.vercel.app)*
- Entreguei plataforma web em **Next.js 14, TypeScript e Tailwind CSS** com deploy em CI/CD na Vercel, catraca digital com token QR rotativo criptografado a cada 30 segundos, integração GymBot AI (Gemini) e checkout **Mercado Pago (PIX e cartão)**.

### **Bodega do Vidigal & OrenAI — Persistência Transacional & Pesquisa Científica (IEEE TSE)**
*Engenheiro de Software | React Native, SQLite, Jest, Docker, Python | 2025 – 2026*
- **Bodega do Vidigal:** Modelei POS/KDS offline-first via WebSockets P2P (< 10ms) com **Outbox pattern** em SQLite garantindo consistência atômica sem duplicidade, validado por **37 testes automatizados no Jest**.
- **OrenAI:** Líder técnico e coautor de artigo científico submetido à revista **IEEE Transactions on Software Engineering (IEEE TSE)** sobre sistemas multi-agente Dockerizados e IA Explicável (XGBoost/CNN + SHAP).

---

## FORMAÇÃO ACADÊMICA, CERTIFICAÇÕES & IDIOMAS

- **Bacharelado em Engenharia de Software** — UniEVANGÉLICA (Anápolis, GO) · *4º Período (Fev 2025 – Dez 2028) · Aulas noturnas (100% disponível em horário comercial)*
  - Vice-Presidente do Diretório Acadêmico CodeUp; **NASA Space Apps Challenge**; Finalista Start Agro Innovation 2025.
- **Trilha Programador Desktop (Banco de Dados SQL, C#, Java, POO, UML)** — Instituto Mix *(Out 2022 – Jun 2024)*
- **Certificações & Idiomas:** Scrum Fundamentals Certified (SFC™ — 03/2026) · Storytelling e Comunicação Técnica (2025) · **Inglês Avançado** · **Português Nativo**.
