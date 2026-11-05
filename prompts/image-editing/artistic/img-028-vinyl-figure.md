# IMG-028 — Miniatura de vinil colecionável

**Categoria:** `image-editing/artistic`  
**Modalidade:** `reference_edit`  
**Técnica:** `vinyl-figure`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **miniatura de vinil colecionável** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{base}`: valor fornecido pelo usuário para orientar a edição.
- `{acabamento}`: valor fornecido pelo usuário para orientar a edição.
- `{acessorios}`: valor fornecido pelo usuário para orientar a edição.
- `{escala}`: valor fornecido pelo usuário para orientar a edição.
- `{cenario}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Transforme o sujeito de {foto} em conceito de miniatura original de vinil, sobre {base}, com acabamento {acabamento}, acessórios autorizados {acessorios}, escala {escala} e cenário {cenario}. Converta materiais humanos para plástico pintado com coerência de reflexos, mantendo pistas de identidade. Não simule produto vendido ou embalagem oficial.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Material de vinil crível.
- [ ] Pose estável.
- [ ] Sem marca ou produto falso.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
