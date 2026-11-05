# IMG-013 — Retrato pop anos 1980

**Categoria:** `image-editing/retro-portraits`  
**Modalidade:** `reference_edit`  
**Técnica:** `eighties-studio`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **retrato pop anos 1980** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{paleta}`: valor fornecido pelo usuário para orientar a edição.
- `{figurino}`: valor fornecido pelo usuário para orientar a edição.
- `{cabelo}`: valor fornecido pelo usuário para orientar a edição.
- `{cenario}`: valor fornecido pelo usuário para orientar a edição.
- `{luz}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Recrie {foto} como ensaio de estúdio ficcional dos anos 1980: paleta {paleta}, figurino {figurino}, tratamento de cabelo {cabelo}, cenário {cenario} e iluminação {luz}. Preserve medidas essenciais do rosto e idade aparente. Faça as escolhas estéticas convergirem em linguagem de época sem copiar capas de artistas ou registrar eventos que não ocorreram.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Identidade reconhecível.
- [ ] Coerência temporal.
- [ ] Luz e figurino compatíveis.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
