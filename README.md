# QA → AI Engineering Framework

> Framework pessoal de transição de **Quality Engineering** para **Engenharia de IA Aplicada**, construído em público, com projetos reais, prompts testados e uma abordagem de qualidade (Shift Left) aplicada a sistemas de IA.

Mantido por [Andreson dos Santos](https://www.linkedin.com/in/andresonsantos) — Quality Engineer com background em automação de testes (Robot Framework, API Testing, arquitetura orientada a eventos), aplicando os mesmos princípios de rigor e prevenção de defeitos ao desenvolvimento e avaliação de sistemas de IA.

---

## Por que este repositório existe

A maioria dos frameworks de "estudo de IA" no GitHub são coleções de anotações de curso. Este é diferente: cada pasta corresponde a uma fase de um plano de estudos estruturado, e cada entrega é um artefato que resolve um problema real do meu dia a dia em QA — não um exercício isolado.

A tese central: **testar sistemas de IA é uma extensão natural de Quality Engineering**, não uma disciplina totalmente nova. Alucinação, comportamento não determinístico e regressão silenciosa em prompts são só novas formas de bug — e quem vem de QA com cultura de Shift Left já tem a mentalidade certa para lidar com isso. Este repositório é a prova disso, construída projeto por projeto.

## Estrutura

| Pasta | Propósito |
|---|---|
| [`projects/`](./projects) | Projetos práticos completos (RAG, agentes, evals) — o núcleo do portfólio |
| [`prompts/`](./prompts) | Biblioteca de prompts testados e versionados, com histórico de iteração |
| [`agents/`](./agents) | Agentes construídos com tool use da API Anthropic, incluindo padrões de orquestração |
| [`playbooks/`](./playbooks) | Guias passo a passo reutilizáveis (ex: "como montar uma suíte de evals") |
| [`knowledge/`](./knowledge) | Notas de estudo, glossários e sínteses (parte gerada com apoio do NotebookLM) |
| [`skills/`](./skills) | Módulos reutilizáveis de conhecimento aplicado (analogia direta a "skills" de agentes de IA) |
| [`templates/`](./templates) | Templates de plano de testes e relatórios de avaliação adaptados para sistemas de IA |
| [`workflows/`](./workflows) | Pipelines de CI/CD para testar e avaliar sistemas de IA automaticamente |
| [`docs/`](./docs) | Documentação de arquitetura e decisões técnicas |
| [`assets/`](./assets) | Diagramas e imagens de apoio |

## Roadmap

O progresso completo, fase a fase, está em [`ROADMAP.md`](./ROADMAP.md).

## Stack

`Python` · `Claude API (Anthropic)` · `Robot Framework` (background) · `RAG / Embeddings` · `Tool Use / Agentes` · `LLM Evals (Ragas)`

## Contato

[LinkedIn](https://www.linkedin.com/in/andresonsantos) · andresoncapi@gmail.com
