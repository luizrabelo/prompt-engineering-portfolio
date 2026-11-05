# IMG-001 — Retrato corporativo

**Categoria:** `image-generation/professional-portraits`  
**Modalidade:** `reference_edit`  
**Técnica:** `professional-portrait`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Retrato corporativo com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{foto_referencia}`: fornecer valor contextual específico antes da execução.
- `{uso}`: fornecer valor contextual específico antes da execução.
- `{vestuario}`: fornecer valor contextual específico antes da execução.
- `{fundo}`: fornecer valor contextual específico antes da execução.
- `{expressao}`: fornecer valor contextual específico antes da execução.
- `{enquadramento}`: fornecer valor contextual específico antes da execução.
- `{proporcao}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Produza um retrato corporativo realista para {uso} a partir da fotografia {foto_referencia}. Preserve fisionomia, idade aparente, tonalidade de pele, cabelo e sinais distintivos. Ajuste exclusivamente {vestuario}, {fundo}, {expressao} e {enquadramento}, com proporção {proporcao}. Utilize luz difusa, pele com textura natural e profundidade fotográfica convincente. Não invente logotipos, crachás ou símbolos de cargo. O resultado deve funcionar como avatar sem depender de recorte posterior.
```

## Avaliação sugerida

- Identidade facial, naturalidade da pele, contorno do cabelo e legibilidade em tamanho pequeno.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
