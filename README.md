# Prompt Engineering Portfolio

Catálogo global de prompts organizado por finalidade. Cada caso de uso é um arquivo Markdown parametrizado, com modalidade, técnica e modelos-alvo registrados no [`catalog.yaml`](catalog.yaml).

## Navegação rápida

| Quero... | Acessar |
| --- | --- |
| Encontrar um prompt pela categoria ou modelo | [Catálogo YAML](catalog.yaml) |
| Explorar estilos e edição de fotos | [Galeria visual](#galeria-visual) · [Coleção fotográfica](docs/collection-04-photo-trends.md) |
| Ver como preencher variáveis e interpretar saídas | [Exemplos práticos](examples/README.md) |
| Trabalhar com documentos, decisões e produtividade | [Workflows profissionais](docs/collection-02-workflows.md) |
| Investigar e coordenar incidentes | [Incident Response](prompts/incident-response/README.md) · [CSIRT](prompts/csirt/README.md) |
| Investigar tendências e ameaças | [CTI](prompts/cti/README.md) |

## Coleções

| Coleção | Escopo | Prompts |
| --- | --- | ---: |
| 01 — Fotografia e imagem | Geração, edição e restauração fotográfica | 10 |
| [02 — Workflows profissionais](docs/collection-02-workflows.md) | Documentos, reuniões, dados, decisões, planejamento, aprendizagem, carreira, vendas e governança de IA | 16 |
| [03 — Incident Response](prompts/incident-response/README.md) | Detecção, contenção e erradicação de incidentes | 12 |
| [04 — Edição fotográfica e tendências](docs/collection-04-photo-trends.md) | 25 estilos e workflows de edição visual | 25 |
| [05 — CSIRT](prompts/csirt/README.md) | Gestão, coordenação e governança de incidentes | 10 |
| [06 — CTI](prompts/cti/README.md) | Inteligência de ameaças para decisões defensivas | 10 |
| **Total** | | **83** |

## Galeria visual

As imagens abaixo são **demonstrações sintéticas e ilustrativas dos efeitos visuais**. Não foram obtidas executando os prompts do catálogo e não constituem evidência de desempenho. Elas servem para explorar os casos de uso e suas entradas parametrizadas.

[![Seleção visual de cinco técnicas fotográficas: filme analógico, neon com chuva, tira de cabine, provador virtual e produto para e-commerce](assets/gallery/photographic-strip.jpg)](docs/collection-04-photo-trends.md)

| Analógico 35 mm · IMG-011 | Neon e chuva · IMG-017 |
| --- | --- |
| [![Comparação sintética do estilo filme 35 mm](assets/gallery/img-011-photographic.jpg)](prompts/image-editing/analog/img-011-35mm-film.md) | [![Comparação sintética de retrato noturno com neon e chuva](assets/gallery/img-017-photographic.jpg)](prompts/image-editing/cinematic/img-017-neon-rain.md) |
| [Abrir prompt](prompts/image-editing/analog/img-011-35mm-film.md) · [Entrada de exemplo](examples/img-011-example.md) | [Abrir prompt](prompts/image-editing/cinematic/img-017-neon-rain.md) · [Entrada de exemplo](examples/img-017-example.md) |

| Photobooth · IMG-024 | Provador virtual · IMG-034 |
| --- | --- |
| [![Montagem sintética de tira fotográfica de quatro quadros](assets/gallery/img-024-photographic.jpg)](prompts/image-editing/compositing/img-024-photobooth-four.md) | [![Comparação sintética de edição de vestuário](assets/gallery/img-034-photographic.jpg)](prompts/image-editing/practical/img-034-virtual-try-on.md) |
| [Abrir prompt](prompts/image-editing/compositing/img-024-photobooth-four.md) · [Entrada de exemplo](examples/img-024-example.md) | [Abrir prompt](prompts/image-editing/practical/img-034-virtual-try-on.md) · [Entrada de exemplo](examples/img-034-example.md) |

| Produto para e-commerce · IMG-035 |
| --- |
| [![Comparação sintética de apresentação de produto antes e depois de iluminação de estúdio](assets/gallery/img-035-photographic.jpg)](prompts/image-editing/practical/img-035-ecommerce-retouch.md) |
| [Abrir prompt](prompts/image-editing/practical/img-035-ecommerce-retouch.md) · [Entrada de exemplo](examples/img-035-example.md) |

[Ver a coleção fotográfica completa](docs/collection-04-photo-trends.md) · [Ver exemplos textuais](examples/README.md)

## Exemplos práticos

[Entradas e saídas esperadas, com critérios de revisão](examples/README.md) — exemplos ilustrativos, não evidências de testes executados.

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

## Coleção 03 — Incident Response

- [Ver os 12 prompts operacionais](prompts/incident-response/README.md) de triagem, investigação, contenção e erradicação.
- [Catálogo da coleção](prompts/incident-response/catalog.yaml), [cenários sintéticos](prompts/incident-response/examples/) e [rubrica de avaliação](prompts/incident-response/evaluation/rubric.md).

Os prompts exigem evidências rastreáveis, incerteza explícita e aprovação humana para mudanças operacionais.

## Coleções 05 e 06 — CSIRT & CTI

- [CSIRT: 10 prompts para coordenação e governança de incidentes](prompts/csirt/README.md).
- [CTI: 10 prompts para inteligência de ameaças acionável](prompts/cti/README.md).
- Ambas incluem exemplos sintéticos, catálogo por coleção e rubrica de avaliação.

As respostas da IA exigem revisão humana. Nenhum prompt pressupõe aprovação para mudanças, divulgação, atribuição ou conclusão jurídica.

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
- `prompts/incident-response/`: resposta técnica a incidentes, exemplos e rubrica.
- `prompts/csirt/`: gestão e coordenação de incidentes.
- `prompts/cti/`: inteligência de ameaças, priorização e disseminação.
- `docs/`: índices e guias de coleções.
- `assets/gallery/`: cartões visuais de navegação do README.
- `templates/`: estrutura reutilizável de novos prompts.

## Segurança e uso responsável

Este repositório publica exclusivamente exemplos genéricos e sintéticos, sem referências a organizações ou ambientes corporativos identificáveis. Consulte a [política de publicação e confidencialidade](docs/publication-policy.md) antes de qualquer contribuição.


Não envie dados sigilosos a sistemas não autorizados. Os arquivos podem ser adaptados para diferentes modelos e situações, mas devem ser revisados antes de decisões importantes.

## Licença

Licença ainda não definida. Nenhuma autorização de redistribuição é presumida.
