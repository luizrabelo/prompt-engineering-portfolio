# CTI — Coleção de prompts operacionais

Dez prompts de inteligência de ameaças orientada a decisões, da formulação de requisitos e avaliação de confiança à produção de detecções e intercâmbio STIX 2.1.

## Índice

| ID | Capacidade | Prompt |
|---|---|---|
| CTI-001 | requirements | [Priority Intelligence Requirements Planner](requirements/cti-001-priority-intelligence-requirements.md) |
| CTI-002 | assessment | [Source Reliability & Analytic Confidence](assessment/cti-002-source-reliability-confidence.md) |
| CTI-003 | indicators | [Indicator Qualification & Enrichment](indicators/cti-003-indicator-qualification-enrichment.md) |
| CTI-004 | tradecraft | [ATT&CK TTP Intelligence Mapper](tradecraft/cti-004-ttp-intelligence-mapping.md) |
| CTI-005 | assessment | [Attribution Skeptic & Competing Hypotheses](assessment/cti-005-attribution-competing-hypotheses.md) |
| CTI-006 | campaigns | [Campaign Clustering & Activity Correlation](campaigns/cti-006-campaign-clustering.md) |
| CTI-007 | vulnerabilities | [Exploitation Risk Prioritizer (KEV/EPSS/Exposure)](vulnerabilities/cti-007-exploitation-risk-prioritizer.md) |
| CTI-008 | detection | [Intelligence-to-Detection Requirements](detection/cti-008-intelligence-to-detection-requirements.md) |
| CTI-009 | dissemination | [Audience-Specific Threat Brief & Dissemination](dissemination/cti-009-audience-threat-briefing.md) |
| CTI-010 | exchange | [STIX 2.1 Package Quality Gate](exchange/cti-010-stix-21-quality-gate.md) |

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
