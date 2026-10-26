[Início](../../README.md) · [English](../en/qualidade.md)

# Como conferir o resultado


Uma tela bonita pode esconder uma função quebrada. A verificação precisa acompanhar a finalidade da mudança.

## Quatro estados diferentes

1. **Arquivo presente:** existe um guia ou uma configuração.
2. **Instalado:** o componente foi adicionado ao ambiente.
3. **Reconhecido:** o cliente consegue descobrir e acessar o componente.
4. **Testado no fluxo:** uma tarefa real ou um caso de teste representativo funcionou.

Registre o estado real. Um exemplo com dados fictícios não prova uma integração externa, e uma conexão bem-sucedida não prova todos os fluxos.

## O que verificar

| Mudança | Evidência útil |
| --- | --- |
| Texto e documentação | Links abrem, imagens existem e o texto descreve a versão atual. |
| Interface | Fluxo principal, teclado, tamanhos de tela e mensagens de erro. |
| Regra de negócio | Casos normais, limites e falhas relevantes. |
| Integração | Serviço correto, permissões mínimas e comportamento quando ele falha. |
| Configuração de agentes | Descoberta das ferramentas e uma tarefa pequena concluída. |

Use os comandos do próprio projeto. Verificação de tipos, análise estática, testes e compilação verificam aspectos diferentes. Não remova uma proteção para apenas obter um resultado verde.

Em mudanças de maior impacto, uma revisão independente ajuda. Faça a revisão da alteração e das partes conectadas a ela. Depois de corrigir, repita os testes afetados; repetir tudo sem motivo não melhora a evidência.

## Publicar a apresentação

Escolha explicitamente os arquivos públicos. Confira capturas, nomes, links, dados de exemplo e credenciais. Este guia não precisa do código privado dos aplicativos usados nos exemplos.

Use o [registro de verificação](../../modelos/pt/verificacao.md). Os [limites documentados do toolkit original](https://github.com/soumatheusgomes/vibe-coding-toolkit/blob/790a895304e0c08b70a5b215c9d334f1c86b816c/docs/05-toolkit-validation.md) pertencem àquela versão e não são resultados desta adaptação.


[Créditos e origem](../../CREDITOS.md)
