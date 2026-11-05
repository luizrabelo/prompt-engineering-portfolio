# IMG-009 — Correção conservadora de fotografia

**Categoria:** `image-editing/enhancement`  
**Modalidade:** `reference_edit`  
**Técnica:** `conservative-photo-correction`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Correção conservadora de fotografia com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{imagem_base}`: fornecer valor contextual específico antes da execução.
- `{exposicao}`: fornecer valor contextual específico antes da execução.
- `{balanco_branco}`: fornecer valor contextual específico antes da execução.
- `{contraste}`: fornecer valor contextual específico antes da execução.
- `{nitidez}`: fornecer valor contextual específico antes da execução.
- `{restricoes}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Aprimore {imagem_base} de forma conservadora. Ajuste exposição conforme {exposicao}, balanço de branco {balanco_branco}, contraste {contraste} e nitidez {nitidez}. Respeite {restricoes}. Preserve estrutura facial, texturas, cores identificadoras, composição e conteúdo documental. Evite HDR excessivo, redução de ruído que destrua detalhes e halos nas bordas. Faça correções globais pequenas e intervenções locais apenas quando necessárias.
```

## Avaliação sugerida

- Naturalidade de pele, ausência de halos, retenção de sombras e preservação de detalhes.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
