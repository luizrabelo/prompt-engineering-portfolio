# IMG-008 — Expansão de enquadramento

**Categoria:** `image-editing/outpainting`  
**Modalidade:** `reference_edit`  
**Técnica:** `outpainting-preserve-canvas`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Expansão de enquadramento com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{imagem_base}`: fornecer valor contextual específico antes da execução.
- `{direcoes_expansao}`: fornecer valor contextual específico antes da execução.
- `{proporcao_final}`: fornecer valor contextual específico antes da execução.
- `{ambiente}`: fornecer valor contextual específico antes da execução.
- `{elementos_protegidos}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Amplie o quadro de {imagem_base} nas direções {direcoes_expansao}, até {proporcao_final}. Mantenha todos os pixels e elementos centrais de {elementos_protegidos}, sem redimensionar ou reconstruir o sujeito original. Complete apenas as áreas adicionais com cenário compatível com {ambiente}, perspectivas e iluminação existentes. Evite criar pessoas, textos, logotipos ou objetos sem continuidade plausível com a fotografia.
```

## Avaliação sugerida

- Sem costuras visíveis, perspectiva constante e manutenção da área original.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
