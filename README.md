# Trilha .NET

![.NET_logo](https://upload.wikimedia.org/wikipedia/commons/thumb/7/7d/Microsoft_.NET_logo.svg/100px-Microsoft_.NET_logo.svg.png)

## 📌 Sobre o Repositório

Este repositório reúne os projetos e atividades desenvolvidos durante a **Trilha .NET** da Residência TIC18. O foco principal é a aplicação de boas práticas de desenvolvimento, incluindo **Git Flow**, **Clean Architecture** e **Entity Framework Core**.

> **Nota:** Cada projeto está versionado em seu respectivo *branch* para manter a organização e o histórico de evoluções.

## Branch da Trilha .NET

Este branch é dedicado à trilha básica da Residência de Software, abrigando as atividades propostas realizadas pelos seguintes integrantes do grupo:

1. Alan Carlos - Repositório no GitHub [AlanSantos01](https://github.com/AlanSantos01)
2. Marcelo Cruz - Repositório no GitHub [Marckcruz](https://github.com/Marckcruz)
3. Daniel Coutinho - Repositório no GitHub [danielcoutinhoneto](https://github.com/danielcoutinhoneto)
4. Franklin - Repositório no GitHub [FranklinPereira2309](https://github.com/FranklinPereira2309)
5. Breno Rios - Repositório no GitHub [Repositório no GitHub](https://github.com/brenoriios)
6. Ezequiel Lobo - Repositório no GitHub [EzekLobo](https://github.com/EzekLobo)

## 🚀 Projetos Desenvolvidos

### 1. Projeto ResTIConnect
**🔗 Branch:** [Acessar ResTIConnect](https://github.com/EzekLobo/Trilha_DotNet_Projetos-ResTIC18/tree/ResTIConnect)

**Objetivo:** Introduzir o Entity Framework Core, realizar modelagem de dados relacional e fomentar o trabalho em equipe utilizando Git Flow.

**📋 Entregas Principais:**
- [x] Criação das camadas: *Domínio, Infraestrutura e Testes*.
- [x] Implementação do `DbContext` e entidade `Logs` com Migration inicial.
- [x] Modelagem e Migrations das entidades `Perfis`, `Endereços` e `Usuários`.
- [x] CRUD completo das entidades `Usuários`, `Eventos` e `Sistemas`.

**🛠 Padrão de Versionamento:**
Branches criadas seguindo o padrão:
`DOTNET-P006/id_tarefa-descricao_breve` (PRs revisados no branch protegido).

---

### 2. Projeto TechMed
**🔗 Branch:** [Acessar TechMed_Grupo](https://github.com/EzekLobo/Trilha_DotNet_Projetos-ResTIC18/tree/TechMed_Grupo)

**Objetivo:** Finalizar o sistema TechMed aplicando conceitos avançados de **Clean Architecture**, separação de configurações do EF Core e fluxo rigoroso de Git Flow.

**📋 Entregas Principais:**
- [x] Estruturação das camadas: *Domínio, Infraestrutura, Aplicação e API*.
- [x] Configuração do EF Core utilizando classes de mapeamento separadas (`IEntityTypeConfiguration`).
- [x] Gerenciamento de Migrations na camada de Infraestrutura (string de conexão na API).
- [x] **Implementação dos Endpoints:**
    - `GET medico/{id}/atendimentos`
    - `GET paciente/{id}/atendimentos`
    - `GET atendimentos/porPeriodo/{inicio}/{fim}`

**🛠 Padrão de Versionamento:**
Branches criadas seguindo o padrão:
`DOTNET-P008/id_tarefa-descricao_breve` (PRs revisados no branch protegido).

---
### 3. Projeto Ordem de Serviço (Auth)
**🔗 Branch:** [Acessar ProjetoEquipe_Auth](https://github.com/EzekLobo/Trilha_DotNet_Projetos-ResTIC18/tree/ProjetoEquipe_Auth)

**Objetivo:** Desenvolvimento de uma API RESTful versionada (`v0.1`) para gerenciamento de ordens de serviço, implementando autenticação e relacionamentos complexos.

**📡 Estrutura da API (Endpoints):**

<details>
<summary><strong>📂 Clique para expandir a lista de rotas</strong></summary>

| Contexto | Método | Endpoint Base |
| :--- | :---: | :--- |
| **Cliente** | `CRUD` | `/api/v0.1/cliente` |
| **Prestador** | `CRUD` | `/api/v0.1/prestador-de-servico` |
| **Ordem de Serviço** | `CRUD` | `/api/v0.1/ordem-de-servico` |
| **Serviço** | `CRUD` | `/api/v0.1/servico` |
| **Pagamento** | `CRUD` | `/api/v0.1/pagamento` |

> *Todos os recursos suportam operações de Listagem (GET All), Detalhes (GET ID), Criação (POST), Atualização (PUT) e Exclusão (DELETE).*

</details>

---

## 🏆 Competências Desenvolvidas

Durante a execução da Trilha .NET, a equipe consolidou conhecimentos práticos nas seguintes áreas:

* **Arquitetura de Software:**
    * [x] Implementação de **Clean Architecture** em projetos .NET.
    * [x] Configuração e separação de camadas (*Domínio, Infraestrutura, Aplicação e API*).
    * [x] Modelagem de dados complexa a partir de diagramas **UML**.

* **Desenvolvimento Back-End:**
    * [x] Utilização avançada do **Entity Framework Core** com Migrations.
    * [x] Mapeamento e configuração de entidades utilizando classes separadas (`IEntityTypeConfiguration`).
    * [x] Criação de **endpoints REST** e implementação de operações CRUD completas.

* **DevOps & Trabalho em Equipe:**
    * [x] Aplicação do **Git Flow** com padronização de nomes de branches.
    * [x] Processo de Code Review através de Pull Requests.
    * [x] Integração contínua e colaboração ágil em equipe.
