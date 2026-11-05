# IMG-023 — Capa editorial fictícia

**Categoria:** `image-editing/compositing`  
**Modalidade:** `reference_edit`  
**Técnica:** `editorial-cover`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **capa editorial fictícia** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{nome_ficticio}`: valor fornecido pelo usuário para orientar a edição.
- `{chamada}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{area_livre}`: valor fornecido pelo usuário para orientar a edição.
- `{formato}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Monte uma capa editorial claramente fictícia com {foto}, título exato {nome_ficticio}, chamada exata {chamada}, paleta {paleta} e espaço tipográfico {area_livre} em {formato}. Proteja rosto e informações importantes. Se a ferramenta não renderizar texto com precisão, deixe o espaço vazio e indique que a tipografia precisa ser aplicada em editor gráfico.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Texto exato ou área reservada.
- [ ] Hierarquia tipográfica.
- [ ] Sem marca real.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
