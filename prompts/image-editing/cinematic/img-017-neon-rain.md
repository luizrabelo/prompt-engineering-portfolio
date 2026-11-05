# IMG-017 — Cenário neon e chuva cinematográfica

**Categoria:** `image-editing/cinematic`  
**Modalidade:** `reference_edit`  
**Técnica:** `neon-rain`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **cenário neon e chuva cinematográfica** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta_neon}`: valor fornecido pelo usuário para orientar a edição.
- `{intensidade_chuva}`: valor fornecido pelo usuário para orientar a edição.
- `{cenario}`: valor fornecido pelo usuário para orientar a edição.
- `{reflexos}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Transforme {foto} em cena noturna chuvosa em {cenario}, usando paleta {paleta_neon}, chuva {intensidade_chuva} e reflexos {reflexos}. Posicione fontes luminosas para que reflexos em água, pele e vidro sejam fisicamente coerentes; mantenha rosto legível e sujeito reconhecível. Não insira letreiros ou texto imaginário e não altere pessoas não indicadas.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Reflexos consistentes.
- [ ] Rosto legível.
- [ ] Profundidade realista.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
