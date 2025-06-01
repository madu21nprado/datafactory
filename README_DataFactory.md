
# 📦 Projeto: Integração Azure Data Factory com Azure DevOps

**Autor(a): Maria Eduarda Prado**

## 📘 Descrição

Este projeto tem como objetivo demonstrar a criação e versionamento de pipelines no **Azure Data Factory (ADF)** integrando com **Azure DevOps**. A proposta é aplicar na prática os conceitos aprendidos, configurar repositório Git no ADF, realizar deploys e versionamentos para um controle mais robusto e profissional dos dados e processos.

---

## 🛠️ Tecnologias Utilizadas

- Azure Data Factory
- Azure DevOps (Repos e Pipelines)
- Git
- JSON (para templates de pipeline)
- GitHub (opcional)
- VS Code (para edição de artefatos, opcional)

---

## 🚀 Etapas do Projeto

### ✅ 1. Criação do Repositório no Azure DevOps

- Acesse Azure DevOps → Criar um novo projeto → Adicionar repositório Git privado
- Estrutura do repositório:
```
adf-pipelines/
├── ARMTemplate/
│   ├── LinkedService.json
│   ├── pipeline1.json
│   └── parameters.json
└── .gitignore
```

📸 *Print da criação do repositório*
> ![Repositório DevOps](imagens/repositorio-devops.png)

---

### ✅ 2. Integração do Azure Data Factory com o Repositório

- Acesse o ADF Studio → Git Configuration
- Vincule ao repositório Azure DevOps criado
- Crie branches de desenvolvimento e use pull requests para versionamento

📸 *Print da configuração Git no ADF*
> ![Configuração Git](imagens/configuracao-git.png)

---

### ✅ 3. Criação de Pipeline Simples

- Pipeline com **Copy Data Activity** simulando ingestão de dados de um blob storage para um SQL Server
- Publicação e salvamento automático no repositório Git

📸 *Print do pipeline*
> ![Pipeline ADF](imagens/pipeline-adf.png)

---

## 💡 Insights e Aprendizados

- Compreendi a importância do versionamento em projetos de engenharia de dados
- Aprendi a configurar e sincronizar ADF com Azure Repos
- Entendi o fluxo de trabalho com branches e PRs no ciclo de vida de um pipeline
- Ampliei meu domínio sobre DevOps aplicado à dados

---

## 🌟 Possibilidades Futuras

- Configurar CI/CD completo com YAML Pipelines para deploy automático
- Criar pipelines mais complexos com parâmetros, triggers e datasets vinculados
- Integrar com Power BI para visualização dos dados ingeridos

---

## 📂 Estrutura Recomendada

```
azure-datafactory-devops/
├── imagens/
│   ├── repositorio-devops.png
│   ├── configuracao-git.png
│   └── pipeline-adf.png
├── templates/
│   └── pipeline1.json
├── README.md
```

---

## 📎 Link para o Projeto na DIO

[🔗 Acesse aqui o projeto na plataforma da DIO](https://www.dio.me/) <!-- Atualize com o link do projeto entregue -->

---

**Maria Eduarda Prado** ✨  
[GitHub](https://github.com/) • [LinkedIn](https://linkedin.com/)
