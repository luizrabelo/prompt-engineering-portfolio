# IMG-016 — Moda urbana com flash noturno

**Categoria:** `image-editing/cinematic`  
**Modalidade:** `reference_edit`  
**Técnica:** `night-fashion-flash`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **moda urbana com flash noturno** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{local}`: valor fornecido pelo usuário para orientar a edição.
- `{figurino}`: valor fornecido pelo usuário para orientar a edição.
- `{distancia_camera}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.
- `{contraste}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Transforme {foto} em editorial de rua noturno em {local}. Produza flash direto sobre o sujeito com contraste {contraste}, sombra consistente e queda de iluminação para {fundo}. Adapte somente o figurino {figurino}, conservando pose e fisionomia, a uma distância de câmera {distancia_camera}. A textura da roupa e as superfícies urbanas devem respeitar iluminação e perspectiva.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Sombra coerente.
- [ ] Tecidos críveis.
- [ ] Identidade intacta.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
