# Projeto de Agendamento de Consultas Médicas

Repositório de documentação de gestão de riscos e comunicação do projeto de desenvolvimento de um aplicativo móvel para agendamento de consultas médicas.

## Sobre o Projeto

O aplicativo tem como objetivo facilitar o agendamento de consultas médicas, oferecendo funcionalidades como:

- Cadastro de usuários
- Gestão de agenda médica
- Agendamento de consultas
- Notificações
- Integração com sistema externo de prontuário

O projeto encontra-se na **fase intermediária de desenvolvimento**, com parte das funcionalidades já implementadas e outras em progresso.

## Contexto

Nas últimas semanas, o projeto enfrentou desafios relevantes:

- **Integração com o prontuário:** instabilidade causada por documentação incompleta da API e mudanças recentes no sistema externo.
- **Mudanças de requisitos:** stakeholders solicitaram alterações no fluxo de agendamento, incluindo novas validações e regras de negócio.
- **Carga de trabalho:** a equipe relatou dificuldades para cumprir os prazos inicialmente estimados.

### Equipe

| Papel           | Quantidade |
| --------------- | ---------- |
| Desenvolvedores | 4          |
| Tester          | 1          |

A integração com o sistema externo de prontuário é **crítica** para a entrega do projeto.

## Estrutura do Repositório

```
projeto_agendamento_consultas/
├── README.md
├── riscos/
│   ├── identificacao.md    # Riscos identificados e contextos de ocorrência
│   ├── analise.md          # Análise qualitativa, impactos e fatores condicionantes
│   └── respostas.md        # Estratégias de resposta e ações associadas
└── comunicacao/
    └── status-stakeholders.md  # Relatório de status para stakeholders
```

## Documentação

### Gestão de Riscos

| Documento | Descrição |
| --------- | --------- |
| [Identificação de Riscos](riscos/identificacao.md) | Lista dos 6 riscos identificados, com descrição e contexto de ocorrência |
| [Análise de Riscos](riscos/analise.md) | Análise qualitativa (probabilidade e impacto), impactos no projeto e fatores condicionantes |
| [Respostas aos Riscos](riscos/respostas.md) | Estratégias de resposta (mitigar/aceitar), justificativas e ações associadas |

### Comunicação

| Documento | Descrição |
| --------- | --------- |
| [Status para Stakeholders](comunicacao/status-stakeholders.md) | Relatório de status com situação atual, riscos, ações em andamento e decisões solicitadas |

## Principais Riscos

1. Falha na integração com o sistema de prontuário
2. Mudanças frequentes nos requisitos
3. Atraso no cronograma do projeto
4. Sobrecarga da equipe de desenvolvimento
5. Defeitos na qualidade do software
6. Dependência de fornecedor ou sistema externo

## Status Atual

| Funcionalidade | Status |
| -------------- | ------ |
| Cadastro de usuários | Implementado |
| Gestão de agenda médica | Parcialmente implementado |
| Fluxo de agendamento | Em desenvolvimento |
| Notificações | Em desenvolvimento |
| Integração com prontuário | Em desenvolvimento |

O projeto permanece viável e apresenta evolução consistente, porém exige acompanhamento contínuo dos riscos identificados e participação ativa dos stakeholders.

