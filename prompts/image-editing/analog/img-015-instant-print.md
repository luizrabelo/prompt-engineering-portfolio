# IMG-015 — Fotografia instantânea retrô

**Categoria:** `image-editing/analog`  
**Modalidade:** `reference_edit`  
**Técnica:** `instant-print`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **fotografia instantânea retrô** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{ambiente}`: valor fornecido pelo usuário para orientar a edição.
- `{temperatura_luz}`: valor fornecido pelo usuário para orientar a edição.
- `{margem}`: valor fornecido pelo usuário para orientar a edição.
- `{desgaste}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Apresente {foto} como impressão instantânea simulada em {ambiente}. Use temperatura de luz {temperatura_luz}, margem branca {margem} e desgaste de papel {desgaste}. Mantenha o conteúdo fotográfico e a fisionomia originais; trabalhe exposição e textura irregular discreta, sem inventar datas, assinaturas ou identidades.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Moldura consistente.
- [ ] Efeito de impressão realista.
- [ ] Sem informação histórica inventada.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
