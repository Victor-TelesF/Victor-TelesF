# Victor Teles

**Backend Python · SQL · Análise de Dados**

Desenvolvo projetos para entender como regras de negócio viram APIs e como dados
ajudam a responder perguntas. Estou em formação e busco oportunidades de
**estágio em Backend Python ou Dados**.

[**Portfólio**](https://victor-telesf.github.io/) · [**LinkedIn**](https://www.linkedin.com/in/victor-telesf/) · [**E-mail**](mailto:victortf986@gmail.com)

## O que venho construindo

### [CotaFlow API](https://github.com/Victor-TelesF/CotaFlow-API) · Backend e domínio financeiro

Meu principal projeto de backend: API REST para acompanhar uma carteira de ações
e FIIs brasileiros, do registro de compras e vendas à avaliação com cotações da brapi.

- Autenticação JWT e senhas com Argon2, com histórico e posições por usuário.
- Preço médio, custo e resultado não realizado com `Decimal`; validação de saldo
  em todo o histórico, inclusive em operações retroativas.
- Clean Architecture, PostgreSQL e Alembic, com testes de domínio, contratos HTTP
  e integração para isolamento de usuários, rollback e concorrência.

[Código](https://github.com/Victor-TelesF/CotaFlow-API) · [Experimentar no Swagger](https://cotaflow-api.onrender.com/docs) · [Arquitetura e exemplo](https://github.com/Victor-TelesF/CotaFlow-API#arquitetura)

<sub>Primeira versão implementada. A validação integrada da versão publicada é a próxima etapa. Escopo: uma carteira em BRL por usuário, com ações e FIIs.</sub>

### [API Performance Monitor](https://github.com/Victor-TelesF/api-performance-monitor) · Backend e análise de dados

API para armazenar medições de latência, calcular estatísticas e gerar cinco
tipos de gráficos em PNG com NumPy e Matplotlib.

- Datasets e medições persistidos em PostgreSQL, com validação de entradas e paginação.
- Média, mediana, dispersão, percentis, análise por limite e possíveis outliers.
- Cálculos de domínio separados das rotas, com testes, migrações e CI.

[Código](https://github.com/Victor-TelesF/api-performance-monitor) · [Swagger](https://api-performance-monitor-0vke.onrender.com/docs) · [Exemplo visual](https://github.com/Victor-TelesF/api-performance-monitor#experimente-em-três-passos)

<sub>Em desenvolvimento: utiliza medições enviadas pelo usuário. A coleta automática de APIs externas está planejada.</sub>

### [Nexus Cloud](https://github.com/Victor-TelesF/Nexus-Cloud) · SQL e regras de negócio

Laboratório de análise com dados fictícios de uma empresa de serviços de nuvem,
organizado em perguntas das áreas comercial, financeira e de infraestrutura.

- Consultas PostgreSQL com relacionamentos, agregações e interpretação de indicadores.
- Análises sobre clientes, serviços, contratos, cobranças e receita recebida.
- Roteiro de 30 desafios; gráficos em Jupyter e dashboard em Streamlit são etapas de evolução.

[Código](https://github.com/Victor-TelesF/Nexus-Cloud) · [Desafios SQL](https://github.com/Victor-TelesF/Nexus-Cloud/blob/main/docs/02-desafios-sql.md)

## Ferramentas que utilizo

| Área | Tecnologias |
| --- | --- |
| Backend e segurança | Python, FastAPI, Pydantic, APIs REST, JWT e Argon2 |
| Dados e persistência | SQL, PostgreSQL, SQLAlchemy e Alembic |
| Estatística e visualização | NumPy, Matplotlib e estatística descritiva |
| Desenvolvimento | pytest, Git, GitHub Actions, Docker Compose, uv e Render |

Estou aprofundando testes de regras de negócio, SQL, estatística, segurança de
APIs e fundamentos de algoritmos. Também reúno exercícios de matemática e
programação no [Server Lab](https://github.com/Victor-TelesF/server-lab).

No [portfólio](https://victor-telesf.github.io/), apresento o contexto dos projetos,
as decisões técnicas e os links para experimentar as APIs.
