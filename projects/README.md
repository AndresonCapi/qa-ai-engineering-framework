# Projects

Projetos práticos completos — cada um com problema real, solução, e o que foi aprendido. Esta é a pasta que mais importa para quem está avaliando este repositório: é aqui que a teoria vira evidência.

## Índice

| Projeto | Fase | Status | Descrição |
|---|---|---|---|
| `01-bug-report-structurer` | Fase 3 | 🔜 planejado | CLI que usa tool use da API Anthropic para estruturar bug reports em texto livre |
| `02-test-docs-rag-assistant` | Fase 4 | 🔜 planejado | Assistente RAG que responde perguntas sobre documentação de testes própria |
| `03-testcase-generator-agent` | Fase 5 | 🔜 planejado | Agente que gera casos de teste + esqueleto de automação a partir de uma especificação |
| `04-rag-eval-suite` | Fase 6 | 🔜 planejado | Suíte de avaliação automatizada (fidelidade, relevância, casos adversariais) para o projeto 02 |

## Convenção

Cada projeto vive em sua própria subpasta numerada, com:
- `README.md` próprio (problema, solução, como rodar, principais decisões técnicas)
- Código-fonte
- `results/` ou `evidencias/` quando aplicável (prints, métricas, logs de teste)

Isso mantém o histórico de decisão visível — não só o resultado final, mas o raciocínio por trás.
