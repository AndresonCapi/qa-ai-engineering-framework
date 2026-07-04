# Prompts

Biblioteca de prompts testados e versionados. Tratados como código: com histórico de iteração, não só a versão final.

## Convenção de cada arquivo

```
## Objetivo
O que este prompt resolve.

## Versão 1 (data)
[prompt]
Resultado: [o que funcionou / não funcionou]

## Versão 2 (data) — iteração sobre V1
[prompt]
Resultado: [melhoria observada]
```

Manter o histórico de versões é intencional: mostra o processo de refinamento baseado em evidência (mesma lógica de um relatório de bug com passos de reprodução), não só o prompt "que funcionou".

## Categorias planejadas

- `casos-de-teste/` — geração e análise de cobertura de casos de teste
- `bug-reports/` — estruturação de relatos de bug em texto livre
- `evals/` — prompts usados como "juiz" (LLM-as-judge) na avaliação de outros sistemas de IA
