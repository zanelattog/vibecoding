[Início](../../README.md) · [English](../en/agentes.md)

# Agentes, ferramentas e divisão do trabalho


![Planejamento, construção e revisão](../../imagens/agentes.png)

## O que é cada coisa

| Termo | Explicação prática |
| --- | --- |
| Modelo de IA | O sistema que interpreta informações e produz respostas. |
| Agente | Usa um modelo, instruções e ferramentas para avançar em uma tarefa. |
| Ferramenta | Uma capacidade concreta, como ler arquivos ou consultar um serviço. |
| Plugin | Um pacote que pode disponibilizar ferramentas, instruções ou integrações. |
| Skill | Instruções reutilizáveis para uma categoria de trabalho. |
| MCP | Um protocolo usado por algumas integrações para disponibilizar ferramentas e contexto ao cliente. |

Um agente não exige um plugin próprio. Vários agentes podem usar o mesmo modelo, com tarefas e contextos diferentes. O acesso às ferramentas depende do cliente, da autenticação e das permissões.

## Quando dividir

Uma divisão útil tem tarefas independentes. Por exemplo, uma pessoa ou agente revisa os textos de uma lista de tarefas enquanto outro verifica a função de desfazer. Quem coordena confere o conjunto depois.

Defina para cada tarefa: objetivo, arquivos envolvidos, limites, dependências e como verificar. Evite dois agentes alterando o mesmo arquivo ao mesmo tempo. Um revisor pode trabalhar somente em leitura.

Se as tarefas dependem umas das outras, faça em sequência. Se a mudança é pequena, use um agente só. Mais agentes podem aumentar custo, repetição e conflitos.

## O que conferir na entrega

Não basta cada agente dizer que terminou. Confira os arquivos, execute as verificações necessárias e veja se as partes funcionam juntas. Se um teste não rodou, registre o motivo em vez de apresentar a tarefa como validada.

[Referência da base sobre coordenação](https://github.com/soumatheusgomes/vibe-coding-toolkit/blob/790a895304e0c08b70a5b215c9d334f1c86b816c/docs/tools/02-subagent-orchestration.md).


[Créditos e origem](../../CREDITOS.md)
