# IMG-033 — Cartão-postal de viagem retrô

**Categoria:** `image-editing/compositing`  
**Modalidade:** `reference_edit`  
**Técnica:** `retro-postcard`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **cartão-postal de viagem retrô** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{destino_confirmado}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{tipografia}`: valor fornecido pelo usuário para orientar a edição.
- `{textura}`: valor fornecido pelo usuário para orientar a edição.
- `{proporcao}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Transforme {foto} em cartão-postal criativo com nome {destino_confirmado}, paleta {paleta}, tipografia {tipografia}, textura impressa {textura} e proporção {proporcao}. Preserve a paisagem e o sujeito; apenas use o destino se confirmado. A peça deve ser claramente design gráfico e não evidência de viagem, data ou carimbo postal real.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Nome geográfico correto.
- [ ] Imagem preservada.
- [ ] Texto legível.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
