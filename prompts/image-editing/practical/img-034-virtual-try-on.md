# IMG-034 — Provador virtual sem alterar corpo

**Categoria:** `image-editing/practical`  
**Modalidade:** `reference_edit`  
**Técnica:** `virtual-try-on`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **provador virtual sem alterar corpo** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{peca}`: valor fornecido pelo usuário para orientar a edição.
- `{tecido}`: valor fornecido pelo usuário para orientar a edição.
- `{cor}`: valor fornecido pelo usuário para orientar a edição.
- `{caimento}`: valor fornecido pelo usuário para orientar a edição.
- `{areas_protegidas}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Na imagem {foto}, troque somente o vestuário pela peça {peca}, material {tecido}, cor {cor} e caimento {caimento}. Preserve {areas_protegidas}, postura, medidas corporais aparentes, rosto, mãos e fundo. Simule dobras, iluminação e oclusões, sem fazer ajustes de emagrecimento ou prometer precisão real de tamanho.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Corpo sem alterações.
- [ ] Tecido coerente.
- [ ] Sem alegação de ajuste garantido.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
