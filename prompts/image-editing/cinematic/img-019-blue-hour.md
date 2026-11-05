# IMG-019 — Rooftop na blue hour

**Categoria:** `image-editing/cinematic`  
**Modalidade:** `reference_edit`  
**Técnica:** `blue-hour`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **rooftop na blue hour** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{horizonte}`: valor fornecido pelo usuário para orientar a edição.
- `{ceu}`: valor fornecido pelo usuário para orientar a edição.
- `{luzes_cidade}`: valor fornecido pelo usuário para orientar a edição.
- `{flash}`: valor fornecido pelo usuário para orientar a edição.
- `{formato}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Construa retrato em terraço durante a blue hour com horizonte {horizonte}, céu {ceu}, luzes urbanas {luzes_cidade} e flash {flash}. Preserve rosto, pose e escala do sujeito; trabalhe equilíbrio entre luz ambiente azul e iluminação de primeiro plano. Entregue composição {formato}, sem inventar marcos geográficos reconhecíveis.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Horizonte plausível.
- [ ] Equilíbrio de luz.
- [ ] Sem cenário factual inventado.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
