# IMG-007 — Remoção seletiva de objetos

**Categoria:** `image-editing/object-removal`  
**Modalidade:** `reference_edit`  
**Técnica:** `localized-inpainting`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Remoção seletiva de objetos com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{imagem_base}`: fornecer valor contextual específico antes da execução.
- `{objeto_remover}`: fornecer valor contextual específico antes da execução.
- `{regiao_edicao}`: fornecer valor contextual específico antes da execução.
- `{textura_referencia}`: fornecer valor contextual específico antes da execução.
- `{elementos_protegidos}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Edite {imagem_base} para remover {objeto_remover} apenas na área {regiao_edicao}. Reconstrua a região com base em {textura_referencia}, respeitando linhas, textura, iluminação e continuidade geométrica. Preserve integralmente {elementos_protegidos} e evite deslocar o restante da cena. Não remova marcas de autoria, evidências, sinais obrigatórios ou informações documentais. Se o fundo não puder ser reconstruído sem inventar conteúdo relevante, indique a limitação.
```

## Avaliação sugerida

- Ausência de vestígios, continuidade de padrões e ausência de alterações fora da máscara.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
