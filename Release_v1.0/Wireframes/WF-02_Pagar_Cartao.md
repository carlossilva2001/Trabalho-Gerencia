# WF-02 — Pagar com cartão

**Versão:** v1.0  
**Data:** 30/09/2026  
**Equipe:** RLC Software

## Histórico de alterações

| Versão | Data | Equipe | Alteração |
|---|---|---|---|
| v1.0 | 30/09/2026 | RLC Software | Criação do wireframe de pagamento por cartão. |

**Requisito relacionado:** US-02

## Wireframe de baixa fidelidade

```text
+------------------------------------------------+
|              PAGAMENTO DO PEDIDO                |
+------------------------------------------------+
| Lanche selecionado: Lanche 1                    |
| Total: R$ 00,00                                 |
|                                                |
| Escolha a modalidade                            |
|                                                |
|       ( ) CARTÃO DE CRÉDITO                    |
|       ( ) CARTÃO DE DÉBITO                     |
|                                                |
| Insira ou aproxime o cartão                    |
|                                                |
| Status: aguardando pagamento                    |
|                                                |
| [ CONFIRMAR PAGAMENTO ]   [ VOLTAR ]           |
|                                                |
| Mensagem:                                      |
|                                                |
+------------------------------------------------+
```

## Legenda

- `Lanche selecionado`: resumo do item escolhido.
- `Total`: valor total ilustrativo do pedido.
- `( )`: opções de cartão de crédito ou débito.
- `Insira ou aproxime`: orientação para uso do cartão.
- `Status`: retorno do processamento do pagamento.
- `[ CONFIRMAR PAGAMENTO ]`: inicia ou confirma a transação.
- `[ VOLTAR ]`: retorna à escolha de lanche.
- `Mensagem`: área para aprovação, recusa ou orientação de nova tentativa.
