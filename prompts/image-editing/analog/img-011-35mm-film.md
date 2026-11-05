# IMG-011 — Retrato analógico 35 mm

**Categoria:** `image-editing/analog`  
**Modalidade:** `reference_edit`  
**Técnica:** `35mm-film`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **retrato analógico 35 mm** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{perfil_filme}`: valor fornecido pelo usuário para orientar a edição.
- `{granulacao}`: valor fornecido pelo usuário para orientar a edição.
- `{temperatura_cor}`: valor fornecido pelo usuário para orientar a edição.
- `{intensidade}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Reinterprete {foto} como negativo 35 mm com perfil {perfil_filme}. Construa transição tonal contínua, grão {granulacao} que varie de modo orgânico, temperatura de cor {temperatura_cor} e efeito de intensidade {intensidade}. Preserve anatomia, fisionomia, textura natural da pele e geometria; evite filtros de ruído digital uniforme. Luzes e sombras devem sugerir captura ótica real, não colagem.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Grão natural.
- [ ] Identidade preservada.
- [ ] Sem halos.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
