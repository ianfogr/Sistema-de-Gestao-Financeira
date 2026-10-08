# Sistema-de-Gestao-Financeira

[![Status](https://img.shields.io/badge/status-[em_desenvolvimento]-yellow)]()
[![Versão](https://img.shields.io/badge/versão-[0.1.0]-blue)]()
[![Licença](https://img.shields.io/badge/licença-[acadêmica]-lightgrey)]()

* **Instituição:** CEUB - Asa Norte
* **Curso:** Ciência da Computação
* **Disciplina:** Nome da disciplina
* **Turma / Semestre:** Turma B, 4º Semestre
* **Professor(a):** Felippe Pires
* **Status do projeto:** Protótipo / MVP / Em desenvolvimento / Concluído
---
## Sumário

- [1. Descrição do projeto](#1-descrição-do-projeto)
- [2. Funcionalidades](#2-funcionalidades)
- [3. Demonstração](#3-demonstração)
- [4. Tecnologias utilizadas](#4-tecnologias-utilizadas)
- [5. Arquitetura](#5-arquitetura)
- [6. Organização dos diretórios](#6-organização-dos-diretórios)
- [7. Participantes](#7-participantes)
- [8. Como executar](#8-como-executar)
- [9. Configuração](#9-configuração)
- [10. Testes](#10-testes)
- [11. Uso de inteligência artificial](#11-uso-de-inteligência-artificial)
- [12. Contribuição e fluxo de trabalho](#12-contribuição-e-fluxo-de-trabalho)
- [13. Histórico de versões](#13-histórico-de-versões)
- [14. Limitações e próximos passos](#14-limitações-e-próximos-passos)
- [15. Licença, referências e contato](#15-licença-referências-e-contato)

---

## 1. Descrição do projeto

Muitos jovens adultos, estudantes universitários e profissionais em início de carreira enfrentam dificuldades significativas no planejamento financeiro a médio e longo prazo. A ausência de uma ferramenta integrada que una o rastreamento diário de despesas a mecânicas inteligentes de projeção de orçamentos dificulta a poupança para projetos futuros — como viagens internacionais e intercâmbios —, resultando em desorganização e perda de poder de compra devido a variações cambiais.

Para solucionar esse problema, o projeto consiste no desenvolvimento de um sistema web de gestão de finanças pessoais focado em proporcionar previsibilidade e controle rigoroso. A plataforma introduz regras claras de distribuição de rendimentos (como a alocação de orçamentos em cascata) e automatiza o acompanhamento de contas em diferentes moedas. Com isso, o usuário consegue gerenciar suas finanças de forma sustentável e consolidar valores em contas dolarizadas em tempo real por meio de integração com API de câmbio externa.

### Objetivos
- **Objetivo geral:** Desenvolver uma aplicação web robusta e integrada para o gerenciamento de finanças pessoais, automatizando o planejamento orçamentário e o acompanhamento de metas internacionais.
- **Objetivos específicos:**
  - Proporcionar um controle rigoroso, categorizado e seguro de receitas e despesas (CRUD completo e busca avançada).
  - Automatizar o planejamento financeiro por meio de regras de alocação de orçamento em cascata.
  - Facilitar o acompanhamento de metas financeiras internacionais consumindo uma API externa de cotação de moedas para cálculo do câmbio atualizado.
  - Disponibilizar um painel interativo (dashboard) e uma API REST própria para exportação de dados consolidados do orçamento.

### Público-alvo
- Jovens adultos, estudantes universitários e profissionais em início de carreira que necessitam organizar suas finanças pessoais.
- Pessoas com objetivos claros de poupança a médio e longo prazo, focadas em realizar intercâmbios ou viagens internacionais.
---
## 2. Funcionalidades

*Lista das funções implementadas e previstas no sistema:*

| Funcionalidade | Descrição | Status |
| --- | --- | --- |
| **Autenticação e Acesso** | Login, logout, recuperação de senha e controle de acesso por perfis. | Implementada |
| **Gestão de Contas** | Cadastro e gerenciamento de contas bancárias, cartões e carteiras digitais. | Implementada |
| **Lançamentos Financeiros** | Registro, edição e exclusão de receitas, despesas e transferências entre contas. | Implementada |
| **Categorização e Tags** | Organização de despesas e receitas por categorias personalizadas. | Em andamento |
| **Painel de Controle (Dashboard)** | Gráficos interativos de fluxo de caixa, saldo atual e projeção mensal. | Em andamento |
| **Relatórios e Exportação** | Geração e exportação de extratos e balanços financeiros em formatos como PDF e CSV. | Planejada |
| **Alertas e Notificações** | Avisos de contas a pagar e faturas próximas ao vencimento. | Planejada |

### Requisitos não funcionais

*Restrições de qualidade e especificações técnicas da aplicação:*

- **Desempenho:** Respostas das rotas da API e carregamento do painel em menos de 2 segundos sob condições normais de uso.
- **Segurança:** Armazenamento de senhas utilizando criptografia de hash (`bcrypt`), proteção contra injeção de dados e uso de tokens JWT para autenticação.
- **Usabilidade:** Interface totalmente responsiva e intuitiva, adaptada para telas de desktop, tablets e dispositivos móveis.
- **Disponibilidade e Confiabilidade:** Aplicação estruturada para ambiente acadêmico/local, com suporte a containerização (Docker) para fácil replicação e testes.
---

## 4. Tecnologias utilizadas

*Informe as tecnologias de fato usadas no projeto. Remova as linhas que não se aplicarem.*

| Camada | Tecnologia | Versão |
| --- | --- | --- |
| Linguagem | Python | [Ex.: 3.12] |
| Frontend | HTML e CSS | [Ex.: 18] |
| Backend | Python e Django | [Ex.: 3.x] |
| Banco de dados | SQLite | [Ex.: 16] |
| Testes | pytest | [Ex.: 8] |
| Infraestrutura | GitHub Actions | — |
| Outras ferramentas | Git e Figma | — |
