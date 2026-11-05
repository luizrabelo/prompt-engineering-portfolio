# IMG-012 — Digicam Y2K com flash frontal

**Categoria:** `image-editing/analog`  
**Modalidade:** `reference_edit`  
**Técnica:** `y2k-digicam`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **digicam y2k com flash frontal** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{forca_flash}`: valor fornecido pelo usuário para orientar a edição.
- `{tonalidade}`: valor fornecido pelo usuário para orientar a edição.
- `{ruido}`: valor fornecido pelo usuário para orientar a edição.
- `{proporcao}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Converta {foto} para estética de câmera digital compacta do início dos anos 2000. Simule flash frontal {forca_flash}, tonalidade {tonalidade}, ruído cromático {ruido}, contraste de sensor pequeno e proporção {proporcao}. Preserve pessoas e objetos reconhecíveis; evite datar o registro, fabricar EXIF ou acrescentar a assinatura de um aparelho específico.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Flash plausível.
- [ ] Rostos intactos.
- [ ] Sem metadados falsos.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
