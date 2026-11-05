# IMG-020 — Sujeito nítido com multidão em movimento

**Categoria:** `image-editing/cinematic`  
**Modalidade:** `reference_edit`  
**Técnica:** `motion-freeze`  
**Modelos-alvo:** Gemini e ChatGPT (adaptação pode ser necessária)

## Objetivo

Aplicar a proposta visual **sujeito nítido com multidão em movimento** à imagem fornecida, mantendo controle sobre as mudanças e sobre a fidelidade de elementos protegidos.

## Parâmetros

- `{foto}`: valor fornecido pelo usuário para orientar a edição.
- `{sujeito_protegido}`: valor fornecido pelo usuário para orientar a edição.
- `{elementos_moveis}`: valor fornecido pelo usuário para orientar a edição.
- `{direcao}`: valor fornecido pelo usuário para orientar a edição.
- `{tempo_simulado}`: valor fornecido pelo usuário para orientar a edição.

## Prompt

```text
Atue como editor fotográfico e diretor de arte. Trate a fotografia anexada como referência principal. Preserve elementos não explicitamente autorizados a mudar.

Mantenha {sujeito_protegido} nítido na imagem {foto} enquanto {elementos_moveis} recebem desfoque por movimento na direção {direcao}, correspondente à exposição simulada {tempo_simulado}. Aplique trajetórias físicas às áreas móveis, preserve contornos e anatomia do sujeito e não multiplique pessoas nem membros.

Restrições gerais:
- Mantenha reconhecíveis as pessoas e os elementos preservados explicitamente.
- Não acrescente assinatura, marca, selo, logotipo ou texto que não foi solicitado.
- Não apresente composições ou transformações como registro documental original.
- Ao encontrar conflito entre estilo e identidade, priorize preservar identidade.
- Se uma capacidade de edição estiver indisponível, declare a limitação em vez de alegar que conseguiu executá-la.

Entregue somente a imagem editada quando a ferramenta suportar edição. Caso contrário, informe precisamente qual operação não pôde realizar.
```

## Critérios de revisão

- [ ] Foco do sujeito correto.
- [ ] Desfoque direcional.
- [ ] Sem duplicações.
- [ ] Sem artefatos graves em olhos, mãos, textos, bordas e sombras.
- [ ] Uso autorizado das referências.

## Limitações

A qualidade depende do modelo e das imagens fornecidas. Resultados sintéticos não substituem registros originais.
