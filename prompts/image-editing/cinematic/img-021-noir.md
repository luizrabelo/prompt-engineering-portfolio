# IMG-021 — Retrato noir monocromático

**Categoria:** `image-editing/cinematic`  
**Modalidade:** `reference_edit`  
**Técnica:** `noir`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **retrato noir monocromático** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{fonte_luz}`: valor fornecido pelo usuário para orientar a edição.
- `{contraste}`: valor fornecido pelo usuário para orientar a edição.
- `{textura}`: valor fornecido pelo usuário para orientar a edição.
- `{clima}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Reinterprete {foto} em preto e branco noir: luz {fonte_luz}, contraste {contraste}, textura {textura} e clima {clima}. Preserve informação em olhos e contornos, mantendo gradação tonal entre luz e sombra. O dramatismo deve vir da composição e não de novos objetos como armas ou cigarros.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Faixa tonal sem clipping.
- [ ] Olhos legíveis.
- [ ] Sem props inventados.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
