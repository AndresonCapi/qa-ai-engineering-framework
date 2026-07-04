# Workflows

Pipelines de CI/CD para testar e avaliar sistemas de IA automaticamente — aplicando a mesma disciplina de integração contínua que já uso em automação de testes tradicional (GitHub Actions, ArgoCD) ao contexto de avaliação de LLMs.

## Planejado

- `.github/workflows/eval-on-pr.yml` — roda a suíte de avaliação (ver `playbooks/`) automaticamente a cada pull request que altera prompts ou lógica de RAG
