# IMG-018 — Golden hour com contraluz

**Categoria:** `image-editing/cinematic`  
**Modalidade:** `reference_edit`  
**Técnica:** `golden-hour`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **golden hour com contraluz** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{posicao_sol}`: valor fornecido pelo usuário para orientar a edição.
- `{ambiente}`: valor fornecido pelo usuário para orientar a edição.
- `{temperatura}`: valor fornecido pelo usuário para orientar a edição.
- `{flare}`: valor fornecido pelo usuário para orientar a edição.
- `{intensidade}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Reilumine {foto} como fotografia na hora dourada, com sol em {posicao_sol}, ambiente {ambiente}, temperatura {temperatura}, flare {flare} e intensidade {intensidade}. Modele contorno luminoso no cabelo e sombras coerentes sem aplicar filtro laranja uniforme. Preserve olhos, fisionomia e características da pele, com equilíbrio de exposição.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Direção de luz única.
- [ ] Tons de pele plausíveis.
- [ ] Sem flare sobre olhos.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
