# IMG-032 — Paisagem tilt-shift em miniatura

**Categoria:** `image-editing/artistic`  
**Modalidade:** `reference_edit`  
**Técnica:** `tilt-shift`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **paisagem tilt-shift em miniatura** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{faixa_foco}`: valor fornecido pelo usuário para orientar a edição.
- `{altura_aparente}`: valor fornecido pelo usuário para orientar a edição.
- `{desfoque}`: valor fornecido pelo usuário para orientar a edição.
- `{saturacao}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Simule efeito tilt-shift sobre {foto} com faixa de foco {faixa_foco}, altura aparente {altura_aparente}, desfoque periférico {desfoque} e saturação {saturacao}. Construa uma cena que lembre maquete sem distorcer prédios, ruas ou pessoas. Respeite a profundidade real da imagem.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Profundidade coerente.
- [ ] Geometria intacta.
- [ ] Efeito de miniatura crível.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
