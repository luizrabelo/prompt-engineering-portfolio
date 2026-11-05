# IMG-014 — Retrato de anuário retrô

**Categoria:** `image-editing/retro-portraits`  
**Modalidade:** `reference_edit`  
**Técnica:** `yearbook-1990s`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **retrato de anuário retrô** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.
- `{roupa}`: valor fornecido pelo usuário para orientar a edição.
- `{expressao}`: valor fornecido pelo usuário para orientar a edição.
- `{enquadramento}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Converta {foto} em um retrato ficcional de anuário dos anos 1990. Use fundo {fundo}, roupa {roupa}, expressão {expressao} e enquadramento {enquadramento}. Recrie iluminação plana de estúdio e impressão suavemente texturizada. Não invente nome de escola, turma, data, certificado nem instituição; preserve traços faciais e proporções.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Retrato legível.
- [ ] Sem credenciais falsas.
- [ ] Anatomia preservada.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
