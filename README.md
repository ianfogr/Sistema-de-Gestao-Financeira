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

O Sistema de Gestão Financeira surge como uma solução digital web e mobile projetada para otimizar o controle do fluxo de caixa e o planejamento orçamentário de microempresas e pessoas físicas. Em um cenário onde o controle manual de despesas e receitas frequentemente gera erros e perda de tempo, a aplicação centraliza todas as movimentações financeiras em um painel intuitivo e em tempo real.

O sistema destina-se a empreendedores, autônomos e gestores financeiros que buscam maior transparência e previsibilidade sobre a saúde de seus negócios ou finanças pessoais. Através de ferramentas automatizadas de categorização e relatórios visuais, a plataforma capacita o usuário a identificar gargalos de gastos, evitar inadimplências e tomar decisões estratégicas mais assertivas.

### Objetivos
- **Objetivo geral:** Desenvolver uma aplicação integrada para o gerenciamento automatizado de finanças, proporcionando controle rigoroso de receitas, despesas e relatórios gerenciais.
- **Objetivos específicos:**
  - Permitir o cadastro, autenticação e gerenciamento seguro de perfis de usuários.
  - Registrar, categorizar e consultar lançamentos de receitas e despesas por data, categoria e conta bancária.
  - Emitir alertas de vencimento de contas e relatórios consolidados de fluxo de caixa (diário, mensal e anual).

### Público-alvo
- Empreendedores individuais e gestores de micro e pequenas empresas
- Profissionais liberais e autônomos
- Pessoas físicas focadas em organização e planejamento orçamentário pessoal
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
