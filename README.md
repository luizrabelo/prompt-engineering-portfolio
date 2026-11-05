# Prompt Engineering Portfolio

Catálogo global de prompts organizado por finalidade. Cada caso de uso é um arquivo Markdown parametrizado, com modalidade, técnica e modelos-alvo registrados no [`catalog.yaml`](catalog.yaml).

## Coleções

| Coleção | Escopo | Prompts |
| --- | --- | ---: |
| 01 — Fotografia e imagem | Geração, edição e restauração fotográfica | 10 |
| [02 — Workflows profissionais](docs/collection-02-workflows.md) | Documentos, reuniões, dados, decisões, planejamento, aprendizagem, carreira, vendas e governança de IA | 16 |
| **Total** | | **26** |

## Acesso rápido à coleção 02

- [WORK-001 — Resumo executivo com rastreabilidade](prompts/work/document-analysis/work-001-evidence-indexed-synthesis.md)
- [WORK-002 — Ata acionável e registro de decisões](prompts/work/meetings/work-002-decision-action-extraction.md)
- [WORK-003 — Revisão de texto com mapa de alterações](prompts/work/communication/work-003-constrained-rewrite-diff.md)
- [WORK-004 — Revisão crítica de apresentação executiva](prompts/work/executive-communication/work-004-adversarial-board-review.md)
- [DATA-001 — Análise de variações e anomalias](prompts/data-analysis/diagnostics/data-001-fact-hypothesis-separation.md)
- [DEC-001 — Pré-mortem de decisão estratégica](prompts/decision-making/risk/dec-001-premortem-assumption-testing.md)
- [DEC-002 — Comparação multicritério com sensibilidade](prompts/decision-making/alternatives/dec-002-weighted-decision-sensitivity.md)
- [DEC-003 — Planejamento por cenários e sinais](prompts/decision-making/scenarios/dec-003-scenario-trigger-mapping.md)
- [PLAN-001 — Agenda semanal com capacidade real](prompts/productivity/planning/plan-001-capacity-constrained-scheduling.md)
- [PLAN-002 — Plano de execução de 90 dias](prompts/productivity/execution/plan-002-milestone-backplanning.md)
- [LEARN-001 — Tutor por recuperação ativa e feedback](prompts/learning/study/learn-001-retrieval-practice-adaptive.md)
- [CAREER-001 — Análise de vaga e entrevista adaptativa](prompts/career/interviews/career-001-competency-gap-interview-loop.md)
- [SALES-001 — Discovery comercial com hipóteses auditáveis](prompts/sales/discovery/sales-001-hypothesis-driven-discovery.md)
- [SALES-002 — Pós-reunião comercial e CRM consistente](prompts/sales/crm/sales-002-structured-crm-extraction.md)
- [AIGOV-001 — Priorização de casos de uso de IA](prompts/ai-governance/use-case-prioritization/aigov-001-value-risk-feasibility-gates.md)
- [AIGOV-002 — Due diligence de fornecedor de IA](prompts/ai-governance/vendor-assessment/aigov-002-claim-evidence-control-mapping.md)

## Como usar

1. Selecione o caso pela finalidade, não pelo nome de uma ferramenta.
2. Abra o `.md`, preencha todas as variáveis `{parametro}` e forneça materiais autorizados.
3. Execute em modelo com recursos compatíveis (texto, imagem, anexos ou cálculo, conforme o caso).
4. Verifique dados, premissas e aderência às restrições antes de empregar o resultado.

Os nomes de modelos são sugestões de uso; não constituem declaração de teste ou desempenho. Não há campo de validação no catálogo.

## Organização

- `prompts/image-generation/` e `prompts/image-editing/`: imagem.
- `prompts/work/`, `prompts/data-analysis/`, `prompts/decision-making/`: trabalho, análise e decisão.
- `prompts/productivity/`, `prompts/learning/`, `prompts/career/`: execução e desenvolvimento.
- `prompts/sales/` e `prompts/ai-governance/`: operações comerciais e governança.
- `docs/`: índices e guias de coleções.
- `templates/`: estrutura reutilizável de novos prompts.

## Segurança e uso responsável

Não envie dados sigilosos a sistemas não autorizados. Os arquivos podem ser adaptados para diferentes modelos e situações, mas devem ser revisados antes de decisões importantes.


## Coleção 02 — Incident Response

Novos **12 prompts operacionais de resposta a incidentes**, organizados por detecção, contenção e erradicação. Consulte [`prompts/incident-response/README.md`](prompts/incident-response/README.md), [`prompts/incident-response/catalog.yaml`](prompts/incident-response/catalog.yaml) e a [rubrica de avaliação](prompts/incident-response/evaluation/rubric.md).

O repositório contém exemplos sintéticos. As recomendações de IA requerem validação humana antes de qualquer alteração operacional.

## Licença

Licença ainda não definida. Nenhuma autorização de redistribuição é presumida.
