# Victor Teles

**Backend Python · SQL · Análise de Dados**

Desenvolvo projetos para entender como regras de negócio viram APIs e como dados
ajudam a responder perguntas. Estou em formação e busco oportunidades de
**estágio em Backend Python ou Dados**.

[![Portfólio](https://img.shields.io/badge/Portfólio-071019?style=for-the-badge&logo=github&logoColor=white)](https://victor-telesf.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/victor-telesf/)
[![E-mail](https://img.shields.io/badge/E--mail-334155?style=for-the-badge&logo=gmail&logoColor=white)](mailto:victortf986@gmail.com)

## O que venho construindo

### [FinTrack API](https://github.com/Victor-TelesF/FinTrack) · Backend e domínio

API REST para registrar operações e consolidar carteiras de investimentos com
renda fixa, ações, fundos imobiliários e criptomoedas.

- Regras de rentabilidade separadas da API e da persistência, com `Decimal` nos cálculos financeiros.
- Autenticação JWT, PostgreSQL, migrações com Alembic e testes automatizados.
- Um aprendizado concreto: corrigir a ordem de compras e vendas na mesma data,
  com testes de regressão para saldo e preço médio.

[Código](https://github.com/Victor-TelesF/FinTrack) · [Swagger](https://fintrack-ye2t.onrender.com/docs) · [Demonstração](https://fintrack-ui-eight.vercel.app)

<sub>Meu foco no FinTrack é o backend. A interface demonstrativa foi prototipada com geração por prompt em uma ferramenta da Vercel.</sub>

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
| Backend | Python, FastAPI, Pydantic e APIs REST |
| Dados e persistência | SQL, PostgreSQL, SQLAlchemy e Alembic |
| Estatística e visualização | NumPy, Matplotlib e estatística descritiva |
| Desenvolvimento | pytest, Git, GitHub Actions, Docker Compose, uv e Render |

Estou aprofundando testes de regras de negócio, SQL, estatística, segurança de
APIs e fundamentos de algoritmos. Também reúno exercícios de matemática e
programação no [Server Lab](https://github.com/Victor-TelesF/server-lab).

No [portfólio](https://victor-telesf.github.io/), apresento o contexto dos projetos,
as decisões técnicas e os links para experimentar as APIs.
