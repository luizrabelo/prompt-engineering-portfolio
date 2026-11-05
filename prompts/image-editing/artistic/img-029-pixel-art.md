# IMG-029 — Avatar pixel art 16-bit

**Categoria:** `image-editing/artistic`  
**Modalidade:** `reference_edit`  
**Técnica:** `pixel-art`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **avatar pixel art 16-bit** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{grade}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{pose}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.
- `{contorno}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Redesenhe {foto} como sprite autoral de pixel art 16-bit com grade {grade}, paleta {paleta}, pose {pose}, fundo {fundo} e contorno {contorno}. Forme sombras por agrupamentos intencionais de pixels, sem antialiasing exagerado. Mantenha traços identificáveis e evite copiar personagens ou cenários de jogos existentes.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Pixelização consistente.
- [ ] Legibilidade pequena.
- [ ] Design original.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
