# IMG-030 — Aquarela de cena cotidiana

**Categoria:** `image-editing/artistic`  
**Modalidade:** `reference_edit`  
**Técnica:** `watercolor`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **aquarela de cena cotidiana** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{ambiente}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{textura_papel}`: valor fornecido pelo usuário para orientar a edição.
- `{simplificacao}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Reinterprete {foto} como aquarela autoral em {ambiente}, paleta {paleta}, papel {textura_papel} e simplificação {simplificacao}. Trabalhe pigmento diluído e bordas orgânicas sem aplicar mero filtro. Preserve posição, expressões e características reconhecíveis; não emule exclusivamente a assinatura de artista vivo.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Lavagens convincentes.
- [ ] Rostos reconhecíveis.
- [ ] Composição fiel.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
