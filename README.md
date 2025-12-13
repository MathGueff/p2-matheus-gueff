## Trabalho p2 Matheus Gueff
API REST desenvolvida para a disciplina IEC, demonstrando um pipeline completo de CI/CD com análise de segurança (SAST) e deploy automatizado.

## 🛠️ Tecnologias e Ferramentas
- Linguagem: Node.js
- Framework: Express.js
- Banco de Dados: PostgreSQL
- Documentação: Swagger UI (swagger-ui-express)
- Containerização: Docker
- Registry: Docker Hub
- Cloud Hosting: Render
- Orquestração: GitHub Actions
- SAST (Static Application Security Testing): SonarCloud
- Análise de Qualidade: SonarQube Quality Gates

## 🚀 Pipeline CI/CD
O fluxo de automação definido no GitHub Actions segue estas etapas:

- Test: Execução de testes unitários (npm test).

- SAST: Análise de código via SonarCloud em busca de vulnerabilidades.

- Build: Criação da imagem Docker.

Teste:

Esse é um teste para ver como estão as coisas

- Push: Envio da imagem para o Docker Hub.

- Deploy: Atualização automática do serviço no Render.

## 🔗 Links do Projeto
API em Produção: [https://api-p2-latest.onrender.com](https://api-sast-matheus-gueff.onrender.com)

teste novo
