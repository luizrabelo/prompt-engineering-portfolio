# IMG-031 — Retrato surreal botânico

**Categoria:** `image-editing/artistic`  
**Modalidade:** `reference_edit`  
**Técnica:** `botanical-surreal`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **retrato surreal botânico** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{plantas}`: valor fornecido pelo usuário para orientar a edição.
- `{area_integracao}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{intensidade}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Crie fotomontagem explicitamente fantástica com {foto}, integrando {plantas} em {area_integracao}, paleta {paleta}, intensidade {intensidade} e fundo {fundo}. Faça a integração por volume e luz, preservando feições e anatomia; não simule ferimentos ou condição corporal real.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Surrealismo claro.
- [ ] Anatomia preservada.
- [ ] Iluminação integrada.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
