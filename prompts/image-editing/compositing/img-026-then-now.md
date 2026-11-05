# IMG-026 — Díptico passado e presente

**Categoria:** `image-editing/compositing`  
**Modalidade:** `reference_edit`  
**Técnica:** `then-now`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **díptico passado e presente** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto_antiga}`: valor fornecido pelo usuário para orientar a edição.
- `{foto_atual}`: valor fornecido pelo usuário para orientar a edição.
- `{ano_antigo}`: valor fornecido pelo usuário para orientar a edição.
- `{ano_atual}`: valor fornecido pelo usuário para orientar a edição.
- `{divisoria}`: valor fornecido pelo usuário para orientar a edição.
- `{formato}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Organize {foto_antiga} e {foto_atual} lado a lado em {formato}, com divisória {divisoria}, alinhando escalas sem modificar a idade real dos sujeitos. Exiba {ano_antigo} e {ano_atual} apenas se os anos tiverem sido confirmados. Trate o resultado como montagem editorial, não como encontro real das pessoas em épocas distintas.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Duas fontes preservadas.
- [ ] Datas corretas.
- [ ] Montagem explícita.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
