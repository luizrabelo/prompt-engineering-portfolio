# IMG-005 — Preservação de identidade após edição

**Categoria:** `image-editing/identity-preservation`  
**Modalidade:** `two_image_edit`  
**Técnica:** `identity-anchor-differential`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Preservação de identidade após edição com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{foto_original}`: fornecer valor contextual específico antes da execução.
- `{versao_editada}`: fornecer valor contextual específico antes da execução.
- `{regiao_protegida}`: fornecer valor contextual específico antes da execução.
- `{ajustes_a_preservar}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Compare {foto_original} com {versao_editada}. Corrija na segunda imagem os desvios de identidade observados na primeira, concentrando-se em {regiao_protegida}. Preserve deliberadamente {ajustes_a_preservar}, desde que não distorçam a identidade. Reconstitua características realmente visíveis na foto original, sem inventar detalhes ocultos. Mantenha enquadramento e estilo da versão editada. Entregue somente a imagem corrigida e sinalize limitações que exijam inspeção humana.
```

## Avaliação sugerida

- Semelhança com o original, proteção da região designada e manutenção dos ajustes permitidos.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
