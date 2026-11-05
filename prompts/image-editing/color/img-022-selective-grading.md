# IMG-022 — Color grading cinematográfico seletivo

**Categoria:** `image-editing/color`  
**Modalidade:** `reference_edit`  
**Técnica:** `selective-grading`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **color grading cinematográfico seletivo** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{cor_sombras}`: valor fornecido pelo usuário para orientar a edição.
- `{cor_luzes}`: valor fornecido pelo usuário para orientar a edição.
- `{intensidade}`: valor fornecido pelo usuário para orientar a edição.
- `{cores_protegidas}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Trabalhe {foto} como colorista: sombras {cor_sombras}, altas luzes {cor_luzes}, intensidade {intensidade} e preservação explícita de {cores_protegidas}. Mantenha luminosidade local, textura e neutralidade de materiais importantes; evite saturação forçada, banding e perda de detalhes.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Cores protegidas íntegras.
- [ ] Sem banding.
- [ ] Graduação consistente.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
