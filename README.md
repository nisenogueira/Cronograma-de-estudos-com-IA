# Potencializando Estudos e Carreira com IA

Projeto desenvolvido para o desafio da [Digital Innovation One](https://www.dio.me/) com foco em planejamento de carreira e produtividade usando inteligência artificial.

Este repositório documenta um experimento prático em que uma necessidade real foi transformada em resultado por meio de quatro ferramentas de IA: um chatbot, o GitHub Copilot, o agente Antigravity e o Lovable.

> **Foco do projeto:** o processo colaborativo entre pessoa e IA — não o conteúdo do cronograma em si.

## Visão geral

A atividade de estudo começou com a reflexão sobre transição de carreira e disponibilidade limitada para aprender. Em seguida, o conteúdo foi produzido e reaproveitado em etapas:

```text
Contexto da usuária
        ↓
Chatbot: identificação de áreas e tópicos
        ↓
Copilot: organização do plano de 30 dias
        ↓
Agente Antigravity: criação dos arquivos Markdown
        ↓
Lovable: transformação dos arquivos em aplicativo gamificado
```

O cronograma de Análise de Dados e os materiais de estudo são artefatos intermediários usados para demonstrar esse encadeamento.

## Fluxo de criação

| Etapa | Ferramenta | Contribuição | Resultado |
|---|---|---|---|
| 1 | Chatbot | Explorou interesses, experiência e tempo disponível | Áreas compatíveis e tópicos iniciais |
| 2 | GitHub Copilot | Estruturou o plano de estudos em um roteiro organizado | Objetivos, cronograma e referências |
| 3 | Agente Antigravity | Materializou o plano em arquivos Markdown | Cronograma, recursos e diário de estudo |
| 4 | Lovable | Reaproveitou os artefatos para criar uma interface gamificada | Study Quest |

Os prompts e o registro de cada etapa estão disponíveis em [`etapas/`](etapas/).

## Artefatos produzidos

- [`etapas/01-chatbot.md`](etapas/01-chatbot.md) — contexto e prompt de exploração de carreira.
- [`etapas/02-copilot.md`](etapas/02-copilot.md) — solicitação usada para estruturar o plano.
- [`etapas/03-antigravity.md`](etapas/03-antigravity.md) — documentação da criação dos arquivos pelo agente.
- [`etapas/04-lovable.md`](etapas/04-lovable.md) — descrição da etapa de gamificação.
- [`cronograma.md`](cronograma.md) — plano de 30 dias produzido na etapa do agente.
- [`recursos.md`](recursos.md) — referências organizadas por semana.
- [`anotacoes/semana-01.md`](anotacoes/semana-01.md) — modelo de diário para acompanhar o estudo.

## Study Quest

O **Study Quest** foi criado no Lovable a partir dos arquivos produzidos nas etapas anteriores. O aplicativo apresenta o plano como missões, metas e recompensas, adicionando elementos como XP, moedas, níveis e acompanhamento diário.

- [Abrir o aplicativo](https://questbound-study-planner.lovable.app)
- [Abrir o projeto no Lovable](https://lovable.dev/projects/fe170609-1673-4dc6-9d96-151c53874550)
- [Ver a documentação da etapa](lovable/README.md)

## Como navegar

1. Leia o [`README de cada etapa`](etapas/) para conhecer os prompts e os objetivos.
2. Consulte o [`cronograma.md`](cronograma.md) como exemplo da saída produzida pelo agente.
3. Explore o [`Study Quest`](https://questbound-study-planner.lovable.app) para ver como os materiais foram transformados em experiência gamificada.

## Aprendizados

- Contexto claro e instruções específicas produzem resultados mais úteis.
- O resultado de uma ferramenta pode ser reaproveitado como entrada da seguinte.
- Agentes podem transformar conteúdo em arquivos estruturados e prontos para colaboração.
- É necessário revisar informações geradas por IA, confirmar links e avaliar coerência antes da publicação.
- Gamificação pode ser usada como camada adicional para aumentar engajamento em uma rotina de estudos.

## Privacidade

Os prompts e arquivos compartilhados neste repositório não incluem dados pessoais, senhas, credenciais ou informações confidenciais. Antes de adaptar o projeto, remova dados privados de conversas, documentos e integrações.

## Tecnologias e conceitos envolvidos

IA conversacional, GitHub Copilot, agentes de desenvolvimento, Lovable, Markdown, gamificação e organização de estudos.

## Licença

Este projeto está licenciado sob a [MIT License](LICENSE).
