# 💼 Hub de Currículos, Projetos & Habilidades — Cauã Felype Reis

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Cauã_Felype_Reis-0077b5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/cauafelypereis)
[![GitHub](https://img.shields.io/badge/GitHub-cauacreis-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/cauacreis)
[![Portfólio](https://img.shields.io/badge/Portfólio-Live_Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://gymflow-weld.vercel.app)
[![Email](https://img.shields.io/badge/Email-caua.reis.dev@gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:caua.reis.dev@gmail.com)

**Engenheiro de Software & Desenvolvedor Full-Stack**  
*4º período na UniEVANGÉLICA · Anápolis / Goiás — Brasil*  
*Sistemas Concorrentes · Microserviços 24/7 · IA & Multi-Agentes (Coautor IEEE TSE) · Mobile Offline-First*

</div>

---

## 📌 Sobre este Repositório

Este repositório centraliza e documenta todo o ecossistema de **currículos profissionais adaptados**, **habilidades técnicas**, **projetos de engenharia em produção** e **métricas de impacto** de Cauã Felype Caetano Reis.

Cada versão de currículo aqui contida foi desenvolvida seguindo os padrões rigorosos de:
- **Parseamento Semântico para ATS / IAs de Recrutamento** (Gupy, InHire, Greenhouse, Lever, Workday, LinkedIn Recruiter).
- **Fórmula de Conquistas (Google XYZ / STAR):** Ação técnica + contexto arquitetural + resultado e métricas de produção.
- **Design Executivo e Escaneabilidade Humana:** Tipografia *Plus Jakarta Sans*, espaçamento cirúrgico e paginação simétrica sem sobras de linhas.

---

## 🚀 Versões dos Currículos Disponíveis

Abaixo estão todas as versões segmentadas por mercado, stack e oportunidade. Clique no link para visualizar o Markdown ou baixar o PDF compilado:

| Segmento / Vaga | Foco Técnico Principal | Idioma | 📥 Download PDF | 📝 Fonte Markdown |
|---|---|:---:|:---:|:---:|
| **Currículo Geral (Carro-Chefe)** | React Native, Python, Java 21, Next.js, SQLite, P2P | PT-BR | [Baixar PDF](./Curriculo_Caua_Felype_Reis_Geral.pdf) | [Ver Markdown](./CURRICULO_CAUA_REIS.md) |
| **FIAP — Desenvolvedor(a) .NET** | C#, .NET 8–10, EF Core, SQL Server, AI Codex, Worker Services | PT-BR | [Baixar PDF](./Caua_Reis_Desenvolvedor_DotNet_FIAP.pdf) | [Ver Markdown](./CURRICULO_FIAP_DOTNET_C_SHARP_PT.md) |
| **NTT DATA — Dev ERP & Sistemas** | Java 21, ERP Multi-Tenant, SQL, Arquitetura Hexagonal | PT-BR | [Baixar PDF](./Caua_Reis_Dev_Sistemas_ERP_NTT_Data.pdf) | [Ver Markdown](./CURRICULO_NTT_DATA_SAP_ERP_PT.md) |
| **BairesDev — Junior Java Developer** | Java 21, Virtual Threads, Spring Boot 3, REST APIs | EN-US | [Baixar PDF](./Caua_Reis_Java_Developer_BairesDev.pdf) | [Ver Markdown](./CURRICULO_BAIRESDEV_JAVA_EN.md) |
| **micro1 — AI Software Engineer** | AI Agents, Python FastAPI, Next.js, LLMs, Coding Agents | EN-US | [Baixar PDF](./Caua_Reis_Micro1_AI_Software_Engineer.pdf) | [Ver Markdown](./CURRICULO_MICRO1_AI_ENGINEER_EN.md) |
| **micro1 — Data Platforms Engineer** | Data Delivery, Python, TypeScript, Relational Schemas | EN-US | [Baixar PDF](./Caua_Reis_Micro1_Data_Platforms_Engineer.pdf) | [Ver Markdown](./CURRICULO_MICRO1_DATA_PLATFORMS_EN.md) |
| **Jobgether — Dev de Sistemas Jr.** | C#, .NET, SQL Server, Regras Corporativas de Negócio | PT-BR | [Baixar PDF](./Caua_Reis_Dev_Sistemas_Jr_Jobgether.pdf) | [Ver Markdown](./CURRICULO_SISTEMAS_JR_CSHARP_PT.md) |
| **Infraestrutura & Suporte N1** | Manutenção de PCs, Redes TCP/IP, Windows/Linux, Help Desk | PT-BR | [Baixar PDF](./Caua_Reis_Suporte_Infra_N1.pdf) | [Ver Markdown](./CURRICULO_SUPORTE_INFRA_N1_PT.md) |

---

## 🛠️ Stack Tecnológico Dominado

```
Linguagens:        TypeScript, JavaScript (ESNext), Python 3.11+, Java 21, C, C#, PHP, SQL
Mobile & Front:    React Native (Expo SDK 58), Next.js (App Router), React 19/18, Tailwind CSS, Three.js (WebGL 3D), Capacitor
Backend & Srv:     ASP.NET Core (.NET 8-10), Spring Boot 3.3 (Virtual Threads), FastAPI (AsyncIO), Node.js, Worker Services
IA & Agentes:      OpenAI Codex, Claude, Gemini API, Groq (Llama 3), Multi-Agent Systems (MAS/MoE), XAI (SHAP)
Bancos & Cache:    PostgreSQL, SQL Server, MySQL, SQLite (Outbox / Local-First), Redis, Supabase, H2
Infra & DevOps:    Docker, Docker Compose, Linux/VPS, Nginx, PM2, Git/GitHub Actions, IIS, Bash/PowerShell
Segurança:         OWASP Top 10, Criptografia AES / Ed25519, JWT Multi-Tenant, Row-Level Security (RLS)
Metodologias:      Scrum Fundamentals Certified (SFC™), Clean Code, SOLID, Design Patterns
```

---

## 🏆 Projetos de Engenharia em Destaque

### 1. **SKZ Trading** (*skztrading.com*)
*Plataforma SaaS de arbitragem algorítmica de ativos digitais operando 24/7 em produção.*
- **Arquitetura:** 11 microsserviços assíncronos em Python (`asyncio`, `aiohttp`) orquestrados via PM2 em VPS Linux, com varreduras a cada 20s e latência < 100ms.
- **Motor Financeiro:** Algoritmo proprietário de precificação dinâmica com trava anti-prejuízo, comissionamento automático de 30% do lucro líquido e conciliação instantânea via webhooks Mercado Pago (PIX).
- **Resultados:** Mais de 200 operações financeiras concluídas e 99,9% de uptime mantido.

### 2. **Bodega do Vidigal — Sistema de POS & KDS Offline-First**
*Ecossistema completo de Ponto de Venda e Tela de Cozinha operando 100% offline.*
- **Arquitetura P2P:** Comunicação direta entre dispositivos via WebSockets em rede móvel local (hotspot direto do aparelho), sem gastar 1 MB de dados e com latência < 10ms.
- **Resiliência:** Banco de dados local SQLite com padrão de resiliência *Outbox pattern*, assegurando persistência atômica e zero duplicidade de comandas.
- **UX Operacional Touchless:** "Contador de Carnes" somando blends em tempo real por ordem cronológica (FIFO) para operação sem toque na chapa.
- **Qualidade:** 37 testes automatizados (unitários e ponta a ponta) no Jest.

### 3. **OrenAI — Pesquisa de Ponta em IA (Artigo IEEE TSE)**
*SaaS B2B de prospectividade mineral e redução de furos secos de sondagem.*
- **Arquitetura:** Sistema Multi-Agentes distribuído em contêineres Docker isolados por commodity mineral.
- **XAI & Machine Learning:** Motor preditivo combinando Gradient Boosting com CNNs geoespaciais e interpretabilidade matemática total via SHAP.
- **Artigo Científico:** Coautor de paper submetido à conceituada revista **IEEE Transactions on Software Engineering (IEEE TSE)**.

### 4. **GymFlow — Plataforma Smart Gym Mobile-First** (*gymflow-weld.vercel.app*)
*SaaS mobile-first para gestão de academias e alunos.*
- Desenvolvido em Next.js 14, Tailwind e TypeScript com empacotamento Android via Capacitor.
- **Catraca Digital Anti-Fraude:** Token rotativo em QR Code dinâmico renovado a cada 30 segundos em memória.
- Assistente biomecânico integrado via Google Gemini API e checkout PIX/Cartão Mercado Pago.

### 5. **CoreSync CRM & NexoTrade-OS**
- **CoreSync CRM:** B2B Multi-Tenant em Java 21 / Spring Boot 3 com partição em memória via `TenantContext` + `ThreadLocal`, auditoria via Spring AOP e orquestração de bots com Groq e Whisper.
- **NexoTrade-OS:** Engine de paper trading consumindo stream de WebSockets da Binance em tempo real com Java 21 *Virtual Threads*.

### 6. **MicroOS — Microkernel x86 32-bit do Zero**
- Microkernel educacional desenvolvido em C e Assembly (GAS) executado no QEMU via Multiboot.
- Paginação de 2 níveis, isolamento de processos em Ring 3, escalonador preemptivo Round-Robin (PIT 100Hz), chaveamento de contexto e IPC por portas/mensagens.

---

## 🎓 Formação Acadêmica & Certificações

- **Bacharelado em Engenharia de Software** — UniEVANGÉLICA (4º Período · Previsão 2027/2028)
  - Vice-Presidente do Diretório Acadêmico CodeUp | Diretor de Artes & Cultura
- **Trilha de Certificação: Programador Desktop (C#, Java, SQL, UML)** — Instituto Mix (2022–2024)
- **Scrum Fundamentals Certified (SFC™)** — SCRUMstudy (ID: 03/2026)
- **Storytelling e Comunicação Técnica** — UniEVANGÉLICA (2025)

---

## 📬 Contato

- **Telefone / WhatsApp:** [+55 (62) 9 9452-1953](https://wa.me/5562994521953)
- **E-mail:** [caua.reis.dev@gmail.com](mailto:caua.reis.dev@gmail.com)
- **LinkedIn:** [linkedin.com/in/cauafelypereis](https://linkedin.com/in/cauafelypereis)
- **GitHub:** [github.com/cauacreis](https://github.com/cauacreis)
