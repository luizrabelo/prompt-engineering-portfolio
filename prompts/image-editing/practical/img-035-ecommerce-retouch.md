# IMG-035 — Foto de produto para e-commerce

**Categoria:** `image-editing/practical`  
**Modalidade:** `reference_edit`  
**Técnica:** `ecommerce-retouch`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **foto de produto para e-commerce** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{produto}`: valor fornecido pelo usuário para orientar a edição.
- `{fundo}`: valor fornecido pelo usuário para orientar a edição.
- `{luz}`: valor fornecido pelo usuário para orientar a edição.
- `{cor_referencia}`: valor fornecido pelo usuário para orientar a edição.
- `{formato}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Aprimore {foto} do produto real {produto} para catálogo comercial com fundo {fundo}, iluminação {luz}, cor de referência {cor_referencia} e formato {formato}. Preserve geometria, detalhes, inscrições, materiais e imperfeições relevantes para compra. Remova apenas distrações externas à representação honesta do produto. Não invente recursos ou acessórios.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Fidelidade do produto.
- [ ] Sem atributos fictícios.
- [ ] Material e sombra coerentes.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
