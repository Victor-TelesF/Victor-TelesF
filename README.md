# Olá, eu sou Victor Teles! 👋

Estou me desenvolvendo em **Backend Python e Análise de Dados**, construindo projetos com APIs REST, bancos de dados relacionais, estatística e visualização de dados. Busco oportunidades de **estágio nessas áreas** para aplicar meus conhecimentos e aprender com uma equipe.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-telesf/)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:victortf986@gmail.com)
[![Portfólio](https://img.shields.io/badge/Portfólio-181717?style=flat-square&logo=github&logoColor=white)](https://victor-telesf.github.io/)

## Sobre mim

Aprendo construindo projetos e investigando problemas: como representar uma regra de negócio, preservar a consistência dos dados, calcular medidas estatísticas e visualizar resultados para facilitar sua interpretação.

Meus projetos conectam programação a matemática, estatística e problemas de negócio, com aplicações em carteiras de investimento, análise de latência e consultas sobre uma empresa fictícia de serviços de nuvem. No backend, tenho praticado a separação entre domínio, API e persistência. Na área de dados, exploro consultas SQL, validação de medições, estatística descritiva e criação de gráficos com Python.

## Tecnologias que utilizo nos projetos

| Área | Tecnologias e ferramentas |
| --- | --- |
| Backend | Python, FastAPI, Pydantic e APIs REST |
| Banco de dados | SQL, PostgreSQL, SQLAlchemy e Alembic |
| Análise e visualização de dados | Python, NumPy, Matplotlib e estatística descritiva |
| Testes e integração contínua | pytest, HTTPX e GitHub Actions |
| Ambiente e deploy | Git, Docker, Docker Compose, uv e Render |

## Projetos em destaque

### 🏦 [FinTrack API](https://github.com/Victor-TelesF/FinTrack)

API REST para registrar operações e consolidar carteiras com renda fixa, ações, fundos imobiliários e criptomoedas. O desafio central é representar ativos com diferentes regras de rentabilidade em uma estrutura de domínio comum.

**O que desenvolvi e pratiquei:**

- Modelagem de ativos, posições e transações com regras de negócio separadas do FastAPI e do SQLAlchemy;
- Cálculos financeiros com `Decimal` e estratégias de cálculo para diferentes indexadores;
- Autenticação com JWT, validação com Pydantic e persistência com PostgreSQL;
- Migrações com Alembic e testes de domínio e integração com pytest e HTTPX;
- GitHub Actions configurado para aplicar migrações e executar a suíte de testes com PostgreSQL;
- Gerenciamento de dependências com uv, ambiente com Docker Compose e deploy no Render.

Um dos aprendizados do projeto foi corrigir a ordenação de compras e vendas realizadas na mesma data, acompanhando a correção com testes de regressão para saldo e preço médio.

[Código e documentação](https://github.com/Victor-TelesF/FinTrack) · [Swagger da API](https://fintrack-ye2t.onrender.com/docs) · [Interface demonstrativa](https://fintrack-ui-eight.vercel.app)

> A interface demonstrativa foi prototipada com geração por prompt em uma ferramenta da Vercel. Meu foco técnico no projeto está no backend, no domínio e na persistência.

### 📊 [API Performance Monitor](https://github.com/Victor-TelesF/api-performance-monitor)

Projeto em desenvolvimento que une **backend e análise de dados** para armazenar conjuntos de medições de latência, calcular estatísticas e gerar visualizações. As consultas estatísticas são disponibilizadas por uma API HTTP, e os gráficos são gerados pela camada de visualização do projeto. A versão atual utiliza medições fornecidas pelo usuário; a coleta automática de APIs externas ainda não está implementada.

**O que estou praticando:**

- Criação e consulta de conjuntos de dados, com inclusão e remoção de medições;
- Validação de medições para rejeitar valores negativos, booleanos e valores não finitos;
- Média, mediana, variância, desvio padrão, percentis e identificação de outliers;
- Histogramas e boxplots para visualizar a distribuição das latências;
- Separação dos cálculos de domínio das rotas e da persistência;
- PostgreSQL, SQLAlchemy e migrações com Alembic;
- Visualizações em PNG na camada de visualização, com NumPy e Matplotlib;
- Documentação da API com Swagger e ambiente com uv e Docker Compose.

### ☁️ [Nexus Cloud](https://github.com/Victor-TelesF/Nexus-Cloud)

Laboratório de **SQL e análise de dados** com dados fictícios de uma empresa de serviços de nuvem. O projeto propõe responder a pedidos das áreas comercial, financeira e de infraestrutura utilizando PostgreSQL.

**O que estou praticando:**

- Consultas sobre clientes, serviços, contratos e infraestrutura;
- Relacionamento entre tabelas para analisar contratações e identificar clientes sem contratos ativos;
- Agregações para estudar preços e serviços mais contratados;
- Interpretação de regras de negócio para transformar perguntas em consultas SQL;
- Uso de PostgreSQL em um ambiente local com Docker Compose.

O projeto está em andamento. O roteiro também prevê relatórios financeiros, análises com gráficos e um dashboard executivo como próximas etapas.

## Aprofundando atualmente

- Estatística descritiva, distribuição de dados, percentis e outliers;
- Análise e visualização de dados com Python, NumPy e Matplotlib;
- Testes automatizados de regras de negócio e integração de APIs;
- SQL, modelagem relacional e consistência dos dados;
- Organização de aplicações backend e tratamento de erros;
- Autenticação e segurança de APIs;
- Estruturas de dados, algoritmos e fundamentos matemáticos.

## Vamos conversar?

Estou aberto a oportunidades de **estágio em Backend Python ou na área de Dados**, especialmente em atividades com Python, SQL, análise e visualização de dados.

[LinkedIn](https://www.linkedin.com/in/victor-telesf/) · [E-mail](mailto:victortf986@gmail.com) · [Portfólio](https://victor-telesf.github.io/)
