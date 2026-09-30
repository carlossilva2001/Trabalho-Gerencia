# Casos de teste da Baseline v1.0

**Versão:** v1.0  
**Data:** 30/09/2026  
**Autor:** NomeDaEquipe  

## Histórico de alterações

| Versão | Data | Autor | Alteração |
|---|---|---|---|
| v1.0 | 30/09/2026 | NomeDaEquipe | Criação dos casos de teste dos fluxos essenciais, alternativos e de erro. |

## CT-01 — Escolher lanche com sucesso

- **Requisito relacionado:** US-01
- **Pré-condição:** O totem está na tela de escolha e há lanches disponíveis.
- **Ação do usuário:** Selecionar um lanche e acionar `AVANCAR`.
- **Resultado esperado:** O lanche fica destacado e o sistema abre a tela de pagamento.

## CT-02 — Tentar avançar sem escolher lanche

- **Requisito relacionado:** US-01
- **Pré-condição:** O totem está na tela de escolha e nenhum lanche está selecionado.
- **Ação do usuário:** Acionar `AVANCAR`.
- **Resultado esperado:** O sistema informa que é necessário selecionar um lanche e permanece na tela de escolha.

## CT-03 — Pagar com cartão de crédito aprovado

- **Requisito relacionado:** US-02
- **Pré-condição:** Um lanche foi selecionado e a tela de pagamento está aberta.
- **Ação do usuário:** Selecionar crédito, inserir ou aproximar um cartão válido e confirmar o pagamento.
- **Resultado esperado:** O sistema informa a aprovação e permite seguir para a geração da senha.

## CT-04 — Pagar com cartão de débito recusado

- **Requisito relacionado:** US-02
- **Pré-condição:** Um lanche foi selecionado e a tela de pagamento está aberta.
- **Ação do usuário:** Selecionar débito, inserir ou aproximar um cartão recusado e confirmar o pagamento.
- **Resultado esperado:** O sistema informa que o pagamento foi recusado e permite tentar novamente.

## CT-05 — Gerar senha após pagamento aprovado

- **Requisito relacionado:** US-03
- **Pré-condição:** O pagamento do pedido foi aprovado.
- **Ação do usuário:** Solicitar a finalização do pedido.
- **Resultado esperado:** O sistema gera uma senha única e a exibe em destaque na tela de pedido confirmado.

## CT-06 — Tentar gerar senha sem pagamento aprovado

- **Requisito relacionado:** US-03
- **Pré-condição:** O pagamento está recusado ou ainda não foi concluído.
- **Ação do usuário:** Tentar finalizar o pedido ou gerar a senha.
- **Resultado esperado:** O sistema não gera senha e orienta o cliente a concluir um pagamento aprovado.
