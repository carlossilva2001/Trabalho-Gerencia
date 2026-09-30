# Requisitos da Baseline v1.0

**Versão:** v1.0  
**Data:** 30/09/2026  
**Autor:** NomeDaEquipe  

## Histórico de alterações

| Versão | Data | Autor | Alteração |
|---|---|---|---|
| v1.0 | 30/09/2026 | NomeDaEquipe | Criação das três user stories essenciais e seus critérios de aceite. |

## US-01 — Escolher lanche

**User Story:** Como cliente, quero escolher um lanche disponível, para montar o pedido que desejo consumir.

### Critérios de aceite

**CA-01.1 — Seleção realizada**

- **Dado** que o cliente está na tela de escolha de lanche e existem lanches disponíveis
- **Quando** o cliente seleciona um lanche
- **Então** o sistema deve destacar o lanche escolhido e permitir avançar para o pagamento

**CA-01.2 — Nenhum lanche selecionado**

- **Dado** que o cliente está na tela de escolha de lanche
- **Quando** o cliente tenta avançar sem selecionar um lanche
- **Então** o sistema deve informar que é necessário selecionar um lanche e permanecer na tela de escolha

## US-02 — Pagar com cartão

**User Story:** Como cliente, quero pagar o pedido com cartão de crédito ou débito, para concluir a compra no totem.

### Critérios de aceite

**CA-02.1 — Pagamento aprovado**

- **Dado** que o cliente selecionou um lanche e está na tela de pagamento
- **Quando** o cliente escolhe crédito ou débito e confirma um cartão válido
- **Então** o sistema deve informar que o pagamento foi aprovado e permitir a geração da senha do pedido

**CA-02.2 — Pagamento recusado**

- **Dado** que o cliente está na tela de pagamento
- **Quando** o cliente confirma um cartão e a transação é recusada
- **Então** o sistema deve informar que o pagamento não foi aprovado e permitir tentar novamente

## US-03 — Gerar senha do pedido

**User Story:** Como cliente, quero gerar uma senha do pedido após o pagamento, para acompanhar a preparação e retirar meu lanche.

### Critérios de aceite

**CA-03.1 — Senha gerada**

- **Dado** que o pagamento foi aprovado
- **Quando** o cliente solicita a finalização do pedido
- **Então** o sistema deve gerar uma senha única e exibi-la de forma destacada

**CA-03.2 — Pagamento não aprovado**

- **Dado** que o pagamento não foi aprovado
- **Quando** o cliente tenta gerar a senha do pedido
- **Então** o sistema não deve gerar senha e deve orientar o cliente a concluir um pagamento aprovado
