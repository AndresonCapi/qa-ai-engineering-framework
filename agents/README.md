# Agents

Agentes construídos com tool use da API Anthropic — sistemas onde o LLM decide dinamicamente os próximos passos, em vez de seguir um fluxo fixo.

## Contexto pessoal

Meu background com **Kafka e RabbitMQ** (arquitetura orientada a eventos) e com **automações no Jira Service Management** (regra → condição → ação) me deu uma base útil para entender agentes: em ambos os casos, algo reage a um estímulo e decide uma ação. A diferença aqui é que a "lógica de decisão" passa a ser um modelo de linguagem em vez de código determinístico — o que muda completamente como se testa e valida o sistema.

## Convenção

Cada agente documenta:
- O problema que resolve
- As ferramentas (tools) que expõe ao modelo
- Os limites de autonomia definidos (quando o agente age sozinho vs. quando exige aprovação humana — human-in-the-loop)
- Casos de falha conhecidos e como foram mitigados

## Planejado

- `testcase-generator/` — recebe uma especificação de funcionalidade e gera casos de teste + esqueleto de script de automação
