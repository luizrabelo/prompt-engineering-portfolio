# IMG-025 — Scrapbook artesanal

**Categoria:** `image-editing/compositing`  
**Modalidade:** `reference_edit`  
**Técnica:** `scrapbook`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **scrapbook artesanal** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{fotos}`: valor fornecido pelo usuário para orientar a edição.
- `{tema}`: valor fornecido pelo usuário para orientar a edição.
- `{numero_quadros}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{decoracoes}`: valor fornecido pelo usuário para orientar a edição.
- `{formato}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Crie página de scrapbook usando somente {fotos}, tema {tema}, exatamente {numero_quadros} quadros, paleta {paleta} e decorações {decoracoes}, em {formato}. Use papéis, fitas e sombras de sobreposição plausíveis, sem cobrir rostos. Não misture traços entre pessoas nem crie lembranças ou legendas factuais ausentes.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Contagem correta.
- [ ] Fotos reconhecíveis.
- [ ] Composição legível.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
