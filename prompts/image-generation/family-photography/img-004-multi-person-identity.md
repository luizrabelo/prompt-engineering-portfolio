# IMG-004 — Fotografia de casal ou família

**Categoria:** `image-generation/family-photography`  
**Modalidade:** `multi_reference_edit`  
**Técnica:** `multi-person-identity`  
**Modelo-alvo:** Gemini (portável mediante adaptação)

## Objetivo

Fotografia de casal ou família com entradas parametrizadas e restrições explícitas.

## Parâmetros

- `{referencias_individuais}`: fornecer valor contextual específico antes da execução.
- `{quantidade_pessoas}`: fornecer valor contextual específico antes da execução.
- `{relacoes}`: fornecer valor contextual específico antes da execução.
- `{local}`: fornecer valor contextual específico antes da execução.
- `{atividade}`: fornecer valor contextual específico antes da execução.
- `{iluminacao}`: fornecer valor contextual específico antes da execução.
- `{proporcao}`: fornecer valor contextual específico antes da execução.

## Prompt

```text
Combine {referencias_individuais} em uma única cena familiar, contendo exatamente {quantidade_pessoas} pessoas com relações {relacoes}. Situe o grupo em {local}, durante {atividade}, sob {iluminacao}, com proporção {proporcao}. Preserve individualmente as identidades, diferenças de estatura e idade aparente; não misture traços entre pessoas nem acrescente participantes. Componha interações naturais e sombras consistentes. Se alguma identidade não puder ser mantida, priorize preservar as referências em vez de fabricar aproximações.
```

## Avaliação sugerida

- Contagem de pessoas, identidade de cada participante, mãos e sobreposições, consistência da luz.
- Inspecionar qualidade técnica, coerência da cena e aderência aos parâmetros.
- Para imagens de pessoas, conferir fidelidade à referência e autorização de uso.
- Repetir a geração em variações relevantes antes de generalizar resultados.

## Limites

Não tratar imagens editadas como registros originais. Recursos e resultados variam conforme o modelo e suas capacidades de edição.
