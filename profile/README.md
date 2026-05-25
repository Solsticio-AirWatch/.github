# 🌍 Solstício – AirWatch

**Plataforma de Monitoramento de Qualidade do Ar**  
*Global Solution 2026/1 – FIAP | 2TDS Fevereiro*

[![ODS 3](https://img.shields.io/badge/ODS-3-green)](https://sdgs.un.org/goals/goal3)
[![ODS 11](https://img.shields.io/badge/ODS-11-orange)](https://sdgs.un.org/goals/goal11)
[![ODS 13](https://img.shields.io/badge/ODS-13-blue)](https://sdgs.un.org/goals/goal13)

---

## 📖 Sobre o projeto

O **AirWatch** é uma plataforma que permite que cidadãos, prefeituras e órgãos ambientais acompanhem a qualidade do ar em tempo real.  
Utilizamos dados de satélites (Sentinel-5P / ESA) via APIs públicas gratuitas (OpenAQ, Open-Meteo) e complementamos com sensores IoT locais (ESP32).

**Problema resolvido:**  
A poluição do ar mata ~7 milhões de pessoas por ano (OMS). Dados existem, mas estão dispersos e são de difícil acesso. Pequenas cidades não possuem sistemas próprios de monitoramento.

**Solução:**  
- Centralização de dados de satélite e IoT  
- Cadastro de cidades/bairros com alertas configuráveis  
- Dashboard simples e acessível  
- Alerta para populações vulneráveis (asmáticos, idosos)

---

## 🎯 ODS atendidas

- **ODS 3** – Saúde e bem-estar  
- **ODS 11** – Cidades e comunidades sustentáveis  
- **ODS 13** – Ação contra a mudança global do clima  

---

## 🧰 Tecnologias utilizadas

| Área | Tecnologias |
|------|--------------|
| Back-end (API principal) | Java 17, Spring Boot, Spring Security + JWT, Swagger |
| Back-end (API secundária) | C#, ASP.NET Core, EF Core |
| Banco de dados | Oracle (relacional) + MongoDB/Redis (NoSQL) |
| Front-end / Mobile | React Native (Expo) |
| IoT | ESP32 (Wokwi), DHT22, MQ-135, LCD 16x2, LED RGB, Buzzer, MQTT |
| DevOps | Docker, Docker Compose, Railway |
| Arquitetura | TOGAF / ArchiMate |

---

## 👥 Equipe – Solstício

| Nome | RM | Turma |
|------|----|-------|
| Felipe Kirschner Modesto | RM561810 | 2TDS Fevereiro |
| Enrico Delesporte | RM565760 | 2TDS Fevereiro |
| Vitor Dias dos Santos | RM565422 | 2TDS Fevereiro |

> *A equipe é responsável por todas as entregas das disciplinas: Java Advanced, .NET, DevOps, IoT, Banco de Dados Oracle, Mobile, QA/TOGAF.*

---

## 📂 Repositórios do projeto

| Projeto | Link |
|---------|------|
| API Java (Spring) | *(em breve)* |
| API .NET | *(em breve)* |
| App Mobile (React Native) | *(em breve)* |
| IoT (ESP32 + Wokwi) | *(em breve)* |
| Banco Oracle (PL/SQL) | *(em breve)* |

---

## 🚀 Como acompanhar

Este repositório (organizacional) é apenas o ponto de entrada.  
Os códigos e documentações completas estão nos repositórios listados acima.

---

## 📅 Cronograma (resumido)

| Período | Atividade |
|---------|-----------|
| 26–27/05 | Estrutura e fundação |
| 28–30/05 | Desenvolvimento core |
| 02–04/06 | Integração e conteúdo |
| 05–06/06 | Deploy e documentação |
| 07–09/06 | Buffer e entrega final (09/06 23h55) |

---

## 📫 Contato

Para dúvidas ou sugestões, abra uma *issue* no repositório correspondente ou entre em contato com a equipe.

---

*Projeto desenvolvido para a Global Solution 2026/1 – FIAP – Economia Espacial & ODS.*
