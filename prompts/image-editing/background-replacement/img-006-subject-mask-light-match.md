# IMG-006 — Substituição de fundo

**Categoria:** `image-editing/background-replacement`  
**Modalidade:** `reference_edit`  
**Técnica:** `subject-mask-light-match`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Substituição de fundo com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{imagem_base}`: fornecer valor contextual específico antes da execução.
- `{novo_fundo}`: fornecer valor contextual específico antes da execução.
- `{sujeito_protegido}`: fornecer valor contextual específico antes da execução.
- `{ambiente_luminoso}`: fornecer valor contextual específico antes da execução.
- `{proporcao}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Na imagem {imagem_base}, substitua exclusivamente o plano de fundo por {novo_fundo}. Preserve {sujeito_protegido}, incluindo silhueta, rosto, vestuário e bordas finas de cabelo. Harmonize iluminação e sombras com {ambiente_luminoso}, sem alterar a identidade do sujeito. Respeite perspectiva, escala e profundidade, produzindo saída em {proporcao}. Não adicione objetos próximos ao corpo que possam confundir a separação entre primeiro plano e fundo.
```

## Avaliação sugerida

- Bordas sem halos, direção de sombra, perspectiva e integridade do sujeito.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
