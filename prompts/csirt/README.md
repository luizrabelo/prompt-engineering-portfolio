# CSIRT — Coleção de prompts operacionais

Dez prompts para a coordenação humana de incidentes: intake, qualificação, escalonamento, incident command, evidências, comunicação, terceiros, exercícios e melhoria contínua. Complementa a coleção de resposta técnica sem duplicá-la.

## Índice

| ID | Capacidade | Prompt |
|---|---|---|
| CSIRT-001 | intake | [Incident Intake & Qualification](intake/csirt-001-incident-intake-qualification.md) |
| CSIRT-002 | governance | [Severity & Escalation Matrix](governance/csirt-002-severity-escalation-matrix.md) |
| CSIRT-003 | command | [Incident Commander Decision Brief](command/csirt-003-incident-commander-decision-brief.md) |
| CSIRT-004 | communications | [Stakeholder Communication & TLP Planner](communications/csirt-004-stakeholder-communication-tlp.md) |
| CSIRT-005 | forensics | [Evidence & Chain-of-Custody Planner](forensics/csirt-005-evidence-custody-planner.md) |
| CSIRT-006 | coordination | [War Room Coordination & Action Tracker](coordination/csirt-006-war-room-action-tracker.md) |
| CSIRT-007 | coordination | [Third-Party & Supplier Incident Coordination](coordination/csirt-007-third-party-incident-coordination.md) |
| CSIRT-008 | governance | [Notification Obligations Triage](governance/csirt-008-notification-obligations-triage.md) |
| CSIRT-009 | readiness | [CSIRT Tabletop Exercise Designer](readiness/csirt-009-csirt-tabletop-exercise.md) |
| CSIRT-010 | improvement | [Post-Incident Review & Improvement Backlog](improvement/csirt-010-post-incident-review-backlog.md) |

## Como usar

1. Escolha o caso de uso e forneça valores autorizados para os parâmetros `{{...}}`. Dados desconhecidos devem permanecer desconhecidos.
2. Preserve referências a evidências e datas. Não envie relatórios restritos, TLP ou dados sensíveis a modelos não autorizados.
3. Faça revisão humana dos resultados, principalmente decisões de incidente, compartilhamento de inteligência, mudanças operacionais e obrigações legais.
4. Teste em cenários sintéticos e registre resultados em uma rubrica antes de considerar o prompt adequado a processos críticos.

## Princípios operacionais

- Fato observado ≠ relato de terceiro ≠ inferência ≠ hipótese.
- As ferramentas não são assumidas: acesso a feeds, análise de logs, validação de schemas ou buscas só podem ser declarados se realizados.
- O assistente oferece análises e minutas; não executa modificações, nem autoriza divulgação.
- Confiança precisa de justificativa e pode ser inconclusiva.
- Indicadores são temporais, contextuais e podem gerar falsos positivos.
- Compartilhamento segue regras de confidencialidade e TLP 2.0. TLP:AMBER+STRICT exige atenção ao escopo mais restrito.

## Materiais complementares

- [Índice YAML](catalog.yaml)
- [Rubrica de revisão](evaluation/rubric.md)
- [Exemplos sintéticos](examples/)

**Uso responsável:** os exemplos são totalmente fictícios. Não há alegação de teste ou validação em ambiente real. Todos os prompts estão em Markdown; a versão 1.0 é uma base para validação por analistas.
