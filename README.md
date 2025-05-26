# Projeto Sistema de Ponto e Geração de Relatórios

![sqlutions logo](https://github.com/user-attachments/assets/4884e8b3-b59a-45ba-ad13-13faa8d4d9b3)

### Bem-vindo ao repositório do nosso projeto _**Sistema de Ponto e Geração de Relatórios**_, desenvolvido pela equipe _**SQLutions**_ do curso Banco de Dados 3º Semestre da Fatec de São José dos Campos.

---

<div align="center">

[Sobre](#-sobre-o-projeto) | [Backlogs e User Stories](#-backlogs--user-stories) | [Documentação](#%EF%B8%8F-documentação) | [Tecnologias](#%EF%B8%8F-tecnologias) | [Equipe](#-equipe)

</div>

## 📑 Sobre o projeto

Navios são muito custosos em vários aspectos, sejam pelas suas dimensões, complexidades, entre outros fatores, e por estarem expostos ao ambiente marítimo, é necessário serem feitas manutenções periódicas, e essa situação geralmente resulta na contratação de uma empresa terceirizada para que a mesma seja encarregada da manutenção desses navios.

O cliente, nesse caso, a empresa Altave, surge com o seguinte problema: o proprietário daquele navio pode sofrer prejuízos milionários em virtude de atrasos na entrega do navio. Portanto, é interessante que ele tenha um meio de monitoramento dos funcionários da empresa terceirizada, a fim de garantir que os mesmos estão cumprindo com suas obrigações.

O produto solicitado pela Altave é um sistema de pontos que registra as movimentações dos funcionários, com dashboards de gráficos e geração de relatórios. O sistema deve ser capaz de registrar a entrada e saída dos funcionários, bem como a quantidade de horas trabalhadas, e gerar gráficos e relatórios com essas informações.

📌 Status do Projeto: Sprint 1

### 🏁 Entregas de Sprints

| Sprint | Previsão    | Status       | Histórico               |
|--------|-------------|--------------|-------------------------|
| 01     | 30/03/2025  | Etapa atual  | [Concluída](#sprint-1)  |
| 02     | 27/04/2025	 | Etapa futura | [Concluída](#sprint-2)  |
| 03     | 25/05/2025	 | Etapa futura | [Concluída](#sprint-3)  |

### 🎬 Apresentação Final

🔄 Em breve

[→ Voltar ao topo](#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 🎯 Backlogs & User Stories

### Backlog do Produto

#### ✅ Requisitos Funcionais

| Código | Descrição                                                                         | Prioridade | Fator | Sprint |
|:------:|-----------------------------------------------------------------------------------|:----------:|:-----:|:------:|
|  RF-1  | Desenvolver uma interface de cadastro de empresas e profissionais, incluindo foto |  🔴 Alta   |   1   |   1    |
|  RF-2  | Dashboard com lista de registros                                                  |  🔴 Alta   |   2   |   1    |
|  RF-3  | Permitir a visualização e edição de registros de movimentação                     |  🔴 Alta   |   3   |   1    |
|  RF-4  | Desenvolver filtragem por data, empresa e profissional                            |  🔴 Alta   |   4   |   2    |
|  RF-5  | Dashboard com gráficos                                                            |  🔴 Alta   |   5   |   2    |
|  RF-6  | Permitir a extração de relatórios                                                 |  🟡 Média  |   6   |   3    |
|  RF-7  | API para consumo dos dados                                                        |  🟢 Baixa  |   7   |   2    |


#### ✔️ Requisitos Não Funcionais

| Código | Descrição                   |
|:------:|-----------------------------|
| RNF-1  | Front Minimalista           |
| RNF-2  | Guia de instalação          |
| RNF-3  | Documentação API            |
| RNF-4  | Modelagem do Banco de Dados |

---

### Backlog das Sprints

### 1️⃣ Sprint 1

[Sprint planning](https://github.com/SQLutions-FATEC/API-3-Semestre/tree/docs/main/docs#1%EF%B8%8F%E2%83%A3-sprint-1)

| Épico |  ID  |  Sprint  | Descrição                                                                                    |
|:-----:|:----:|:--------:|----------------------------------------------------------------------------------------------|
|   1   | US-1 | Sprint 1 | Permitir que o usuário altere o horário de entrada de um funcionário para corrigir falhas.   |
|   3   | US-3 | Sprint 1 | Possibilitar o cadastro, visualização e edição de funcionários com foto.                     |
|   1   | US-4 | Sprint 1 | Implementar o cadastro, visualização e edição de empresas para associá-las aos funcionários. |

### 2️⃣ Sprint 2

[Sprint planning](https://github.com/SQLutions-FATEC/API-3-Semestre/tree/main/docs#2%EF%B8%8F%E2%83%A3-sprint-2)

| Épico |  ID  |  Sprint  | Descrição                                                                                  |
|:-----:|:----:|:--------:|--------------------------------------------------------------------------------------------|
|   2   | US-2 | Sprint 2 | Permitir exportar movimentações filtradas para planilhas .xlsx.                            |
|   4   | US-6 | Sprint 2 | Adicionar filtros por funcionário, empresa, função e data aos registros de movimentações.  |
|   5   | US-7 | Sprint 2 | Implementar visualização das funções já cadastradas no sistema.                            |

### 3️⃣ Sprint 3

[Sprint planning](https://github.com/SQLutions-FATEC/API-3-Semestre/tree/main/docs#3%EF%B8%8F%E2%83%A3sprint-3)

| Épico |  ID  |  Sprint  | Descrição                                                                                      |
|:-----:|:----:|:--------:|------------------------------------------------------------------------------------------------|
|   6   | US-5 | Sprint 3 | Permitir criar, visualizar e editar contratos dos funcionários com período de vigência.        |
|   7   | US-8 | Sprint 3 | Implementar gráficos com base nas movimentações para análises gerenciais.                      |

---

### User Stories

| Épico |  ID  |  Sprint  | Descrição                                                                                    |
|:-----:|:----:|:--------:|----------------------------------------------------------------------------------------------|
|   1   | US-1 | Sprint 1 | Permitir que o usuário altere o horário de entrada de um funcionário para corrigir falhas.   |
|   2   | US-2 | Sprint 2 | Permitir exportar movimentações filtradas para planilhas .xlsx.                              |
|   3   | US-3 | Sprint 1 | Possibilitar o cadastro, visualização e edição de funcionários com foto.                     |
|   1   | US-4 | Sprint 1 | Implementar o cadastro, visualização e edição de empresas para associá-las aos funcionários. |
|   6   | US-5 | Sprint 3 | Permitir criar, visualizar e editar contratos dos funcionários com período de vigência.      |
|   4   | US-6 | Sprint 2 | Adicionar filtros por funcionário, empresa, função e data aos registros de movimentações.    |
|   5   | US-7 | Sprint 2 | Implementar visualização das funções já cadastradas no sistema.                              |
|   7   | US-8 | Sprint 3 | Implementar gráficos com base nas movimentações para análises gerenciais.                    |

[→ Voltar ao topo](#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 🖥️ Documentação

Como planejamento foi feito wireframe para validação do fluxo com o cliente, assim como fluxograma e a modelagem de banco de dados que estão acessíveis [na documentação](https://github.com/SQLutions-FATEC/API-3-Semestre/tree/main/docs)

> 🔗 **Links da documentação**<br>
>
> - Início: [API - Checkpoint](https://github.com/SQLutions-FATEC/API-3-Semestre/tree/main/docs)
> - Backlog: [Informações](#-backlogs--user-stories)
> - Modelagem do Banco de Dados: [Link](https://github.com/SQLutions-FATEC/API-3-Semestre/tree/main/docs#1%EF%B8%8F%E2%83%A3-sprint-1)

[→ Voltar ao topo](#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 🛠️ Tecnologias

As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:

[![Vue](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vue.js&logoColor=4FC08D)](https://vuejs.org/) [![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)](https://www.java.com/) [![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)](https://www.postgresql.org/) [![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/seu-usuario) [![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/) [![Slack](https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white)](https://slack.com/) [![Notion](https://img.shields.io/badge/Notion-336791?style=for-the-badge&logo=notion&logoColor=white)](https://www.notion.so/) [![Google Docs](https://img.shields.io/badge/Google_Docs-4285F4?style=for-the-badge&logo=google-docs&logoColor=white)](https://docs.google.com/) [![Figma](https://img.shields.io/badge/Figma-0ACF83?style=for-the-badge&logo=figma&logoColor=white)](https://www.figma.com/)

[→ Voltar ao topo](https://github.com/SQLutions-FATEC/API-3-Semestre/blob/main/README.md#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)

## 👥 Equipe

|                                                                                             | Função         | Nome                             | Redes                                                                                                                                                                                                                                                                                                           |
|---------------------------------------------------------------------------------------------|----------------|----------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| ![davi](https://github.com/user-attachments/assets/08f611cd-614b-41b8-a7a7-cab3065e9aeb)    | Product Owner  | Davi Soares Fernandes dos Santos | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/dsf21/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DaviSFS21)                         |
| ![tiago](https://github.com/user-attachments/assets/2715b681-6533-41bd-a176-4ec9130a1a90)   | Scrum Master   | Tiago Torres dos Reis            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tiago-torres-dos-reis/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/TiagoTReis)        |
| ![augusto](https://github.com/user-attachments/assets/642849b4-3329-4e61-8d77-9a4b84f258de) | Desenvolvedor  | Augusto de Moraes Piatto         | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/augusto-piatto/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/augustopiatto)            |
| ![bryan](https://github.com/user-attachments/assets/ee31c3b5-3ba6-4019-8c95-ba03cfa94d4c)   | Desenvolvedor  | Bryan Matheus                    | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/bryan-matheus-5aa0a3302/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/BryanARMatheus)  |
| ![caina](https://github.com/user-attachments/assets/a6f52b8c-11c7-4f20-9647-004cd04c60bc)   | Desenvolvedor  | Cainã Nascimento Melo            | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/cain%C3%A3-melo/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/CainaNascimentoMelo)     |
| ![enzo](https://github.com/user-attachments/assets/3211d516-d4a0-48fc-af1d-e1cbef5d1a1e)    | Desenvolvedor  | Enzo Lemos Franco                | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/enzo-lemos-franco-002651293/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/EnzoLFranco) |
| ![gloria](https://github.com/user-attachments/assets/2de16de0-fd28-4700-b5b5-a00702dfce10)  | Desenvolvedora | Glória Brito                     | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gloriafbrito/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/GloBrito)                   |
| ![joao](https://github.com/user-attachments/assets/984a1b7c-e4fa-4b78-84f1-0391f0f08de5)    | Desenvolvedor  | João Tuschtler Paulista          | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/joaopaulista/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/joaopaulista)               |
| ![lucas](https://github.com/user-attachments/assets/2a1afdae-7de8-4449-9fea-28fac568e960)   | Desenvolvedor  | Lucas Souza                      | [![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-souza-a67a52165/) [![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/JayWeinberg123)    |

[→ Voltar ao topo](https://github.com/SQLutions-FATEC/API-3-Semestre/blob/main/README.md#projeto-sistema-de-ponto-e-gera%C3%A7%C3%A3o-de-relat%C3%B3rios)
