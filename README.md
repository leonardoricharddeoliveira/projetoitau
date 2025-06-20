## Sistema de Investimentos - Desafio Técnico Itaú

Este projeto implementa um sistema de controle de investimentos em renda variável. O sistema contempla operações de compra e venda de ativos, cálculo de posição, integração com dados externos e exposição via APIs RESTful.

**Desafio - Apoiar três desenvolvedores, no Papel de Scrum Master, utilizando o framework Scrum.**

---
## **Informações sobre o Desafio Itaú**
## ✅ Objetivo
Desenvolver uma aplicação robusta com base em .NET Core, MySQL e boas práticas de engenharia de software, seguindo os critérios técnicos fornecidos pelo Itaú.

---

## 🚀 Tecnologias Utilizadas
- MySQL (modelagem e índices)
- .NET Core com C#
- Entity Framework / Dapper
- Kafka (integração de cotações)
- xUnit / MSTest
- OpenAPI 3.0 / Swagger

---

## 📂 Estrutura do Projeto
- `/sql/` – Scripts de criação de tabelas e índices
- `/src/` – Código-fonte da aplicação
- `/tests/` – Testes unitários
- `/docs/` – Documentação técnica e OpenAPI
- `/workers/` – Serviços de integração Kafka

---

## 🧠 Funcionalidades
- Registro de operações (compra/venda)
- Cálculo de posição por ativo e global
- Cálculo de P&L e preço médio
- Consumo de cotações em tempo real
- APIs RESTful com endpoints financeiros
- Tolerância a falhas com fallback e circuit breaker

---

## 🧪 Testes
- Testes unitários cobrindo lógica de cálculo
- Testes de erro: listas vazias, quantidade zero
- Mutação simulada para verificação de robustez

---

## 📄 Documentação
- OpenAPI 3.0 disponível em `/docs/openapi.yaml`
- Instruções de execução no `README.md`
- Justificativa técnica para modelagem no `/docs/`

---

## 📝 Execução
1. Subir banco MySQL e executar scripts SQL
2. Configurar `appsettings.json` com string de conexão
3. Rodar aplicação com `dotnet run`
4. Acessar APIs REST conforme documentação

---

## 🧾 Backlog do Desafio
![image](https://github.com/user-attachments/assets/72135a12-d520-4684-8352-ef882512d255)

