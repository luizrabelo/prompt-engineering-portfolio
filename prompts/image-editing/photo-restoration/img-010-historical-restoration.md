# IMG-010 — Restauração conservadora de fotografia antiga

**Categoria:** `image-editing/photo-restoration`  
**Modalidade:** `reference_edit`  
**Técnica:** `historical-restoration`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Restauração conservadora de fotografia antiga com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{digitalizacao_original}`: fornecer valor contextual específico antes da execução.
- `{defeitos_visiveis}`: fornecer valor contextual específico antes da execução.
- `{nivel_intervencao}`: fornecer valor contextual específico antes da execução.
- `{tratamento_cor}`: fornecer valor contextual específico antes da execução.
- `{preservacao_historica}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Restaure {digitalizacao_original} removendo apenas {defeitos_visiveis} no nível {nivel_intervencao}. Priorize {preservacao_historica}: mantenha idade, rostos, roupas, inscrições, enquadramento, textura do suporte e sinais históricos. Siga {tratamento_cor}; qualquer colorização deve ser reconhecida como interpretação, não evidência. Não invente feições, textos ou objetos nas áreas sem informação visual. Conserve o original intacto e diferencie o arquivo restaurado.
```

## Avaliação sugerida

- Rastreabilidade das alterações, ausência de reconstrução fantasiosa e integridade histórica.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
