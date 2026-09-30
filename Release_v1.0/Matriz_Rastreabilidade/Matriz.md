# Matriz de rastreabilidade da Baseline v1.0

**Versão:** v1.0  
**Data:** 30/09/2026  
**Equipe:** RLC Software

## Histórico de alterações

| Versão | Data | Equipe | Alteração |
|---|---|---|---|
| v1.0 | 30/09/2026 | RLC Software | Criação da matriz cruzada entre requisitos, wireframes e casos de teste. |

## Rastreabilidade

| Requisito | Descrição resumida | Wireframe | Caso(s) de teste |
|---|---|---|---|
| US-01 | Escolher um lanche disponível para montar o pedido. | WF-01 | CT-01, CT-02 |
| US-02 | Pagar o pedido com cartão de crédito ou débito. | WF-02 | CT-03, CT-04 |
| US-03 | Gerar uma senha após o pagamento aprovado. | WF-03 | CT-05, CT-06 |

## Verificação de cobertura

| Verificação | Resultado |
|---|---|
| Todos os requisitos possuem wireframe | Atendido: US-01/WF-01, US-02/WF-02, US-03/WF-03 |
| Todos os requisitos possuem caso de teste | Atendido: cada requisito possui fluxo feliz e fluxo alternativo/erro |
| Todos os wireframes apontam para requisito | Atendido: WF-01 -> US-01, WF-02 -> US-02, WF-03 -> US-03 |
| Todos os casos de teste apontam para requisito | Atendido: CT-01 a CT-06 referenciam US-01, US-02 ou US-03 |
