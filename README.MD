<div align="center">

# Juliana Chaves Palm

### Software Engineer · Solution Design & SDD · Data Analytics & IA · Backend Java de Alta Escala

[![LinkedIn](https://img.shields.io/badge/LinkedIn-julianachavespalm-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/julianachavespalm)
[![GitHub](https://img.shields.io/badge/GitHub-julianachavespalm-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/julianachavespalm)
[![Localização](https://img.shields.io/badge/Rio%20de%20Janeiro-Brasil-009c3b?style=for-the-badge&logo=googlemaps&logoColor=white)](#)

</div>

---

## O que eu entrego

> Engenheira de software que transforma **necessidades de negócio em soluções técnicas end-to-end** — da especificação à implementação, com arquitetura sólida, dados e IA integrados.

Não entrego apenas código. Entrego **soluções desenhadas, especificadas, implementadas, testadas e observáveis**, com rastreabilidade entre a demanda do stakeholder e a entrega em produção.

| Entrega | Como | Evidência |
|---|---|---|
| **Desenho de soluções end-to-end** | Recebo demandas de stakeholders e conduzo arquitetura + especificação com **Spec-Driven Development (SDD)** | Ciclo completo: especificação → arquitetura → implementação → validação |
| **Backend de alta escala** | **Java**, Spring Boot, microsserviços, **Kafka**, concorrência e paralelismo distribuído | Sistemas críticos do setor financeiro |
| **Dados & IA aplicados** | **BigQuery**, PostgreSQL/MySQL, chave-valor, agentes e **GitHub Copilot Extensions** | Soluções de dados end-to-end e IA no ciclo de desenvolvimento |
| **Qualidade e estabilidade** | **TDD**, Clean Architecture, SOLID, observabilidade, war rooms | Serviços sustentáveis, testados e observáveis |

---

## Como eu trabalho

```mermaid
flowchart LR
    A[Stakeholders] --> B[Especificação<br/>SDD]
    B --> C[Arquitetura<br/>Clean Architecture + SOLID]
    C --> D[Implementação<br/>Java + Kafka + Dados]
    D --> E[Validação<br/>TDD]
    E --> F[Produção<br/>Observabilidade]
    F -.feedback.-> A
```

**Cada prática tem uma função clara no ciclo:**
- **SDD** conduz o ciclo de **especificação e arquitetura** — o *quê* e o *porquê*, antes do código.
- **Clean Architecture** e **SOLID** estruturam o **código** — o *onde* e o *como*, com baixo acoplamento.
- **TDD** valida o **comportamento das regras de negócio** — a garantia de que a entrega funciona e não regride.
- **Observabilidade** garante que a entrega **permanece estável** em produção.

---

## Stack e competências

<table>
<tr>
<td valign="top" width="50%">

### Solução & Processo
- Desenho end-to-end a partir de stakeholders
- **Spec-Driven Development (SDD)**
- Colaboração em tríade com Data Science e Data Analytics
- IA aplicada ao ciclo: **GitHub Copilot, Claude Code, Codex**

### Backend & Distribuídos
- **Java**, Spring Boot, APIs REST
- Microsserviços e integração assíncrona
- **Kafka**, resiliência, idempotência
- Concorrência e paralelismo distribuído

</td>
<td valign="top" width="50%">

### Dados & IA
- **BigQuery** e bases analíticas
- **PostgreSQL**, **MySQL**, chave-valor
- SQL Server, DB2
- **GitHub Copilot Extensions** e agentes de IA

### Engenharia & Arquitetura
- **Clean Architecture**, **SOLID**, **TDD**
- Testes: RestAssured, Appium/Maestro, Selenium/Selenide
- Observabilidade, alertas, war rooms
- CI/CD: GitHub Actions, Azure DevOps

</td>
</tr>
</table>

---

## Experiência em destaque

### Capgemini · Engenharia de Software
**Entregas principais:**
- **Desenho de soluções end-to-end** a partir de demandas de stakeholders, com arquitetura e especificação via **SDD**.
- Atuação em **Data Analytics e IA**, em colaboração com times de Data Science e Data Analytics.
- Desenvolvimento de **sistemas críticos do setor financeiro**, com backend Java e integrações assíncronas.
- Arquitetura e implementação de **GitHub Copilot Extensions**, levando IA ao ciclo de desenvolvimento.
- Arquiteturas de **dados sintéticos em larga escala** (DB2, Javelin).
- Liderança técnica em **prevenção de falhas** e automação ponta a ponta.

---

## Projetos em destaque

<table>
<tr>
<td width="50%" valign="top">

### afrobank-ledger
Core bancário de liquidação financeira e conta-corrente de alta escala com **Java 17, Spring Boot e Apache Kafka**.

**Decisões e Padrões Arquiteturais:**
- **Prevenção de Deadlocks:** Ordenação determinística de recursos em bloqueios pessimistas (`SELECT FOR UPDATE`).
- **Transactional Outbox Pattern:** Eliminação de escrita dupla (*dual-write*) com mensageria Kafka ordenada e contingência via Dead Letter Queue (DLQ).
- **Idempotência & Consistência:** Suporte a `X-Idempotency-Key` (RFC 7807) e precisão contábil com `BigDecimal (HALF_EVEN)`.
- **Validação Automatizada:** Suíte de 17 testes cobrindo domínio puro, serviços e contratos REST.

**Evidência:** Backend financeiro crítico, resiliência distribuída e concorrência.

[![Ver repositório](https://img.shields.io/badge/Repositório-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/julianachavespalm/afrobank-ledger)

</td>
<td width="50%" valign="top">

### acordes
Guia normativo de teoria harmônica e piano acústico interativo em **ES6 nativo com Zero Runtime Dependencies**.

**Decisões e Padrões Arquiteturais:**
- **Governança SDD:** Ciclo completo com 12 ADRs e 10 Especificações de Features formalizadas em `.specs/`.
- **Acessibilidade Universal (WCAG 2.1 AAA):** Falsa tabela ABNT, semântica editorial DPUB, Skip-Links e princípio do silêncio auditivo.
- **Domínio Puro & Áudio Acústico:** Modelagem harmônica isolada do DOM, pool de 26 amostras acústicas reais e analisador físico via Web Audio.
- **Rigor de Qualidade:** **96.61% de cobertura de testes** em runner nativo do Node.js (`node --test`).

**Evidência:** Solution Design, Spec-Driven Development (SDD) e A11y Assistive-First.

[![Ver repositório](https://img.shields.io/badge/Repositório-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/julianachavespalm/acordes)
[![Aplicação Online](https://img.shields.io/badge/Aplicação%20Online-009c3b?style=flat-square&logo=googlechrome&logoColor=white)](https://julianachavespalm.github.io/acordes/)

</td>
</tr>
</table>

---

## Em constante evolução

- **Streaming, processamento batch e feature stores**, a partir de uma base sólida de engenharia.
- **Modelos e agentes de IA integrados a pipelines de dados analíticos**.
- **Metodologias estatísticas aplicadas às ciências humanas** — unindo análise de dados sociais e inovação tecnológica.

---

## Vamos conversar?

<div align="center">

Aberta a oportunidades em **engenharia de backend, design de soluções e sistemas de dados**.

[![LinkedIn](https://img.shields.io/badge/Fale%20comigo%20no%20LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/julianachavespalm)

</div>

---

<div align="center">
<sub>README construído para traduzir entregas, não apenas tecnologias.</sub>
</div>
