# Olá, eu sou o Victor Teles! 👋

**Desenvolvedor Backend Python** — em transição de carreira, construindo sistemas robustos com arquitetura limpa.

[![Portfólio](https://img.shields.io/badge/Portfólio-121212?style=for-the-badge&logo=githubpages&logoColor=white)](https://victor-telesf.github.io/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:victortf986@gmail.com)

---

## 🎯 Sobre mim

Sou desenvolvedor backend especializado em **Python**, com foco em **arquitetura de software** e **qualidade de código**. Minha abordagem prioriza a separação da lógica de negócio de frameworks e infraestrutura, aplicando princípios **SOLID**, **Clean Architecture** e **Domain-Driven Design**.

Atualmente curso **Ciência da Computação** na UNINTER (previsão 2026) e consolido base matemática e analítica de forma autodidata para projetar arquiteturas complexas com rigor.

**Busco oportunidades como Desenvolvedor Backend Python Júnior.**

---

## 🛠 Stack Principal

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-05998B?style=for-the-badge&logo=fastapi&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-DC382D?style=for-the-badge&logo=sqlalchemy&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-2E6BFF?style=for-the-badge&logo=pydantic&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

---

## 🚀 Projetos em Destaque

### 🏦 [FinTrack API](https://github.com/Victor-TelesF/FinTrack)

API REST para gestão de **carteiras de investimento diversificadas** (renda fixa, variável, cripto). Arquitetura de domínio limpa com cálculos polimórficos de rentabilidade e indexadores dinâmicos (CDI, IPCA, Selic).

| Métrica | Valor |
|---------|-------|
| Testes unitários | **110+** |
| Cobertura da camada de domínio | **100%** |
| Padrões aplicados | Strategy, Factory, Protocol, Template Method |
| Precisão numérica | `Decimal` em todo o domínio |
| Status | Domínio, persistência e schemas concluídos. Error handling implementado. API REST e autenticação em desenvolvimento. |

**Destaques técnicos:**
- Camada `domain/` 100% isolada de frameworks — Python puro, testável independentemente
- Hierarquia polimórfica de ativos mapeada via **Joined Table Inheritance** (SQLAlchemy 2.0)
- Camada `schemas/` com **discriminated unions** (Pydantic v2) para validação polimórfica de ativos
- `error_handlers.py` traduz exceções de domínio em respostas HTTP (404, 409, 422, 400)
- Injeção de dependência via **Protocol** para fontes de preço (testável com mocks)
- Posição de carteira **calculada**, não persistida — elimina dessincronização

> 💡 **Próxima exploração (sem data definida):** uma simulação gravitacional N-corpos (Cosmic Sandbox), integrando cálculo numérico e álgebra linear vetorizada.

---

## 📚 O que estou construindo agora

- **FinTrack:** domínio, persistência e schemas concluídos — agora migrando para a camada de service, endpoints REST e autenticação JWT
- **Base matemática:** consolidando cálculo e álgebra linear de forma autodidata, para dar suporte a arquiteturas mais exigentes no futuro

---

## 📬 Vamos nos conectar?

- 🌐 **Portfólio:** [victor-telesf.github.io](https://victor-telesf.github.io/)
- 📧 **Email:** [victortf986@gmail.com](mailto:victortf986@gmail.com)

---

*Sempre aberto a trocas técnicas sobre arquitetura, design patterns e boas práticas de engenharia de software.*
