# IMG-024 — Tira fotográfica de quatro quadros

**Categoria:** `image-editing/compositing`  
**Modalidade:** `reference_edit`  
**Técnica:** `photobooth-four`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **tira fotográfica de quatro quadros** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{expressoes}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.
- `{orientacao}`: valor fornecido pelo usuário para orientar a edição.
- `{acabamento}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Monte uma tira de cabine com exatamente quatro quadros da mesma pessoa em {foto}, explorando {expressoes}, fundo consistente {fundo}, orientação {orientacao} e acabamento {acabamento}. Preserve roupa, identidade, acessórios e proporções entre quadros. Varie apenas expressões e gestos plausíveis; mantenha margens regulares e iluminação de uma sessão única.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Exatamente quatro quadros.
- [ ] Rosto consistente.
- [ ] Margens regulares.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
