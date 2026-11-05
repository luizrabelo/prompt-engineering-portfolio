# IMG-027 — Sticker chibi personalizado

**Categoria:** `image-editing/artistic`  
**Modalidade:** `reference_edit`  
**Técnica:** `chibi-sticker`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **sticker chibi personalizado** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{expressao}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{acessorio}`: valor fornecido pelo usuário para orientar a edição.
- `{contorno}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Transforme a pessoa de {foto} em personagem chibi original com expressão {expressao}, paleta {paleta}, acessório autorizado {acessorio}, contorno {contorno} e fundo {fundo}. Exagere proporções ilustrativas de maneira controlada, preservando cabelo, rosto e pistas de identidade. Produza silhueta adequada para sticker, sem copiar personagens licenciados.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Silhueta clara.
- [ ] Identidade inferível.
- [ ] Sem personagem copiado.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
