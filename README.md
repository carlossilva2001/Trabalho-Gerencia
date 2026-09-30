# Sistema de Totem de Autoatendimento para Lanchonete

**Versão:** v1.0  
**Data:** 30/09/2026  
**Autor:** NomeDaEquipe  

## Histórico de alterações

| Versão | Data | Autor | Alteração |
|---|---|---|---|
| v1.0 | 30/09/2026 | NomeDaEquipe | Criação da Baseline v1.0 com requisitos, wireframes, testes e matriz de rastreabilidade. |

## Objetivo

Esta pasta documenta a Baseline v1.0 do sistema de totem de autoatendimento para uma lanchonete. O escopo contempla a escolha do lanche, o pagamento por cartão de crédito ou débito e a geração da senha do pedido.

## Estrutura

- `Release_v1.0/Requisitos/`: user stories e critérios de aceite.
- `Release_v1.0/Wireframes/`: wireframes de baixa fidelidade em ASCII, um por user story.
- `Release_v1.0/Testes/`: casos de teste dos fluxos felizes e alternativos/erros.
- `Release_v1.0/Matriz_Rastreabilidade/`: relação entre requisito, wireframe e caso de teste.

## Convenção de IDs

- `US-XX`: User Story, requisito funcional.
- `WF-XX`: Wireframe associado a uma user story.
- `CT-XX`: Caso de teste associado a um requisito.

O sufixo numérico é mantido entre os artefatos relacionados sempre que houver correspondência direta. Cada requisito possui pelo menos um wireframe e casos de teste para fluxo feliz e fluxo alternativo ou de erro.

## Convenção de commits e tags

- Commits devem usar mensagens curtas, no imperativo, identificando a entrega ou alteração documental.
- O commit da entrega inicial usa a mensagem `Baseline v1.0`.
- A tag `v1.0` identifica o estado aprovado da Baseline v1.0.

## Integrantes

| Responsável | Papel |
|---|---|
| Integrante 1 | Responsável |
| Integrante 2 | Responsável |
| Integrante 3 | Responsável |
| Integrante 4 | Responsável |
| Integrante 5 | Responsável |

## Suposições

- O totem exibe um lanche por vez ou uma lista simples de lanches disponíveis.
- O pagamento é realizado exclusivamente por cartão de crédito ou débito nesta fase.
- A senha é gerada somente após a confirmação do pagamento aprovado.
- Não foram definidos valores, nomes comerciais, imagens ou regras de negócio específicas; os wireframes usam rótulos genéricos.
- A v2.0 será entregue em uma etapa posterior e não faz parte desta baseline.
