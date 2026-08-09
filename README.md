# Benchmark — Quitandinha Online

**Data:** 10/08/2026
**Sistema:** Quitandinha Online
**Objetivo:** Avaliar o desempenho, a usabilidade e o funcionamento do supermercado online em situações comuns de compra.

## Caso 1 — Realização de uma compra

**Cenário:** Cliente acessa o Quitandinha Online e realiza uma compra com diferentes produtos.

**Procedimento:**

1. Acessar o site do Quitandinha Online.
2. Pesquisar por produtos, como arroz, feijão, leite e frutas.
3. Adicionar os produtos ao carrinho.
4. Conferir quantidades e valores.
5. Informar o endereço de entrega.
6. Selecionar a forma de pagamento.
7. Finalizar o pedido.

**Resultado esperado:**

* Os produtos devem ser adicionados corretamente ao carrinho.
* Os preços e quantidades devem ser calculados corretamente.
* O endereço deve ser validado.
* O pedido deve ser confirmado sem erros.
* O cliente deve receber uma confirmação do pedido.

## Caso 2 — Produto indisponível

**Cenário:** Cliente tenta comprar um produto que está sem estoque.

**Procedimento:**

1. Acessar o Quitandinha Online.
2. Pesquisar por um produto indisponível.
3. Tentar adicionar o produto ao carrinho.
4. Verificar a mensagem apresentada pelo sistema.

**Resultado esperado:**

* O sistema deve informar claramente que o produto está indisponível.
* O produto não deve ser adicionado ao carrinho como se estivesse disponível.
* O cliente deve receber uma alternativa, quando possível, como escolher outro produto ou ativar uma notificação de disponibilidade.

## Critérios avaliados

| Critério               | Caso 1 | Caso 2 |
| ---------------------- | ------ | ------ |
| Funcionamento do site  | ✓      | ✓      |
| Busca de produtos      | ✓      | ✓      |
| Carrinho               | ✓      | ✓      |
| Controle de estoque    | —      | ✓      |
| Cálculo de preços      | ✓      | —      |
| Finalização da compra  | ✓      | —      |
| Mensagens de erro      | —      | ✓      |
| Experiência do usuário | ✓      | ✓      |

## Conclusão

A benchmark realizada em **10/08/2026** tem como objetivo verificar se o Quitandinha Online consegue atender corretamente às principais necessidades de seus clientes. Os dois casos analisam tanto o fluxo normal de uma compra quanto uma situação excepcional de produto indisponível, permitindo identificar possíveis problemas de funcionamento, estoque e experiência do usuário.
