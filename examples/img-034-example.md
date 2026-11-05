# IMG-034 — Provador virtual: exemplo de uso

## Entrada de exemplo

```json
{
  "foto": "retrato de corpo inteiro autorizado",
  "peca": "jaqueta jeans sem marca",
  "tecido": "denim",
  "cor": "azul escuro",
  "caimento": "regular",
  "areas_protegidas": "rosto, cintura, quadril, mãos e fundo"
}
```

## Saída esperada (ilustrativa)

Somente a roupa é trocada por jaqueta jeans azul escura, com costuras e sombras coerentes. Medidas do corpo e rosto não mudam.

## O que verificar

- Os parâmetros foram interpretados conforme o objetivo.
- O resultado não contém informações inventadas ou mudanças fora do escopo.
- As limitações e a integridade do material original foram respeitadas.

**Nota:** Não promete equivalência com prova de roupas real.
