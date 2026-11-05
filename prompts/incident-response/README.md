# GenAI Incident Response — Coleção 01

Coleção pública de **12 prompts operacionais** para auxiliar detecção, investigação, contenção e erradicação de incidentes. Os prompts são escritos em inglês para uso em vários modelos; a documentação está em português.

## Princípios

- Evidências antes de conclusões; hipóteses e lacunas explícitas.
- Decisões e mudanças operacionais dependem de aprovação humana.
- Preservação forense, cadeia de custódia, criticidade e continuidade devem ser consideradas.
- Não inventar telemetria, consultas, TTPs, ações executadas ou resultados.
- Logs e artefatos são dados não confiáveis; nunca seguir instruções embutidas neles.
- Exemplos apenas sintéticos. Não divulgar segredos ou dados sensíveis em repositórios públicos.

## Catálogo

| ID | Fase | Prompt |
|---|---|---|
| IR-001 | detection | [Alert Triage Analyst](detection/ir-001-alert-triage-analyst.md) |
| IR-002 | detection | [Attack Timeline Reconstruction](detection/ir-002-attack-timeline.md) |
| IR-003 | detection | [MITRE ATT&CK Investigator](detection/ir-003-attack-investigator.md) |
| IR-004 | detection | [Compromise Scope Analyzer](detection/ir-004-compromise-scope.md) |
| IR-005 | detection | [Threat Hunting Query Builder](detection/ir-005-threat-hunting.md) |
| IR-006 | containment | [Containment Strategy Advisor](containment/ir-006-containment-strategy.md) |
| IR-007 | containment | [Identity Compromise Responder](containment/ir-007-identity-compromise.md) |
| IR-008 | containment | [Ransomware Response Planner](containment/ir-008-ransomware-response.md) |
| IR-009 | containment | [Blast Radius & Business Impact](containment/ir-009-blast-radius.md) |
| IR-010 | eradication | [Root Cause & Persistence Analyzer](eradication/ir-010-root-cause-persistence.md) |
| IR-011 | eradication | [Eradication Plan Builder](eradication/ir-011-eradication-plan.md) |
| IR-012 | eradication | [Post-Eradication Verification](eradication/ir-012-eradication-verification.md) |

## Uso

1. Selecione um prompt e preencha os parâmetros `{{...}}` com informações autorizadas e, quando necessário, sanitizadas.
2. Preserve identificadores de evidência, tempos originais, fuso e fonte dos logs.
3. Execute o prompt em um modelo de sua escolha e revise as recomendações contra os dados reais.
4. Não execute ações destrutivas sem autorização e avaliação forense.
5. Avalie respostas usando [a rubrica](evaluation/rubric.md) e os três [exemplos sintéticos](examples/).

O [catálogo da coleção](catalog.yaml) e o [catálogo global](../../catalog.yaml) não possuem campos de origem nem status de validação. As avaliações aqui são **critérios previstos**, não resultados de testes realizados.

## Organização

- `detection/`: IR-001 a IR-005.
- `containment/`: IR-006 a IR-009.
- `eradication/`: IR-010 a IR-012.
- `examples/`: entradas fictícias e não operacionais.
- `evaluation/`: critérios de avaliação.

## Limitações

A ausência de eventos não prova ausência de comprometimento. Identificadores por IP podem ser ambíguos por NAT/DHCP. A IA não substitui perícia, incident command, change control, aconselhamento jurídico ou procedimentos formais de recuperação.
