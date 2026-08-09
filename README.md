# Benchmark de Segurança da Informação — Quitandinha Online

**Data:** 10/08/2026  
**Sistema:** Quitandinha Online  
**Objetivo:** Avaliar a segurança do supermercado online com base nos pilares da Segurança da Informação.

---

## Pilares avaliados

| Pilar | Objetivo |
|---|---|
| **Confidencialidade** | Garantir que informações sejam acessadas somente por pessoas autorizadas. |
| **Integridade** | Garantir que os dados não sejam alterados de forma indevida. |
| **Disponibilidade** | Garantir que o sistema e os serviços estejam disponíveis quando necessários. |
| **Autenticidade** | Garantir que usuários e sistemas sejam realmente quem afirmam ser. |
| **Não Repúdio** | Garantir que uma ação realizada não possa ser negada posteriormente. |

---

# Caso 1 — Acesso e proteção dos dados do cliente

### Cenário

Um cliente acessa sua conta no Quitandinha Online para consultar seus dados pessoais, endereço, histórico de pedidos e informações relacionadas às compras.

### Objetivo

Verificar se o sistema protege as informações do cliente contra acessos não autorizados.

### Pilares envolvidos

- **Confidencialidade**
- **Autenticidade**
- **Integridade**

### Teste

1. O usuário deve realizar login utilizando suas credenciais.
2. O sistema deve validar corretamente usuário e senha.
3. Após a autenticação, o cliente deve conseguir acessar somente seus próprios dados.
4. Deve ser verificado se um usuário consegue acessar informações pertencentes a outro cliente.
5. Alterações nos dados cadastrais devem exigir uma sessão autenticada.

### Resultado esperado

- Usuários não autenticados não devem acessar dados privados.
- Um cliente não deve conseguir visualizar dados de outro cliente.
- As credenciais devem ser protegidas.
- Alterações não autorizadas nos dados devem ser impedidas.
- O sistema deve manter a integridade das informações armazenadas.

### Avaliação

| Critério | Resultado esperado |
|---|---|
| Login | Funcionamento correto |
| Controle de acesso | Usuário acessa somente seus dados |
| Proteção de dados | Dados privados protegidos |
| Integridade | Alterações somente por usuários autorizados |
| Autenticidade | Identidade do usuário validada |

---

# Caso 2 — Indisponibilidade do sistema durante uma compra

### Cenário

Um grande número de clientes acessa o Quitandinha Online simultaneamente para realizar compras.

### Objetivo

Verificar se o sistema consegue permanecer disponível e preservar as informações das compras durante um período de alta demanda.

### Pilares envolvidos

- **Disponibilidade**
- **Integridade**
- **Confidencialidade**

### Teste

1. Simular vários acessos simultâneos ao sistema.
2. Realizar pesquisas de produtos.
3. Adicionar produtos ao carrinho.
4. Simular a finalização de pedidos.
5. Verificar o comportamento do sistema durante o aumento da quantidade de acessos.
6. Verificar se os pedidos e valores permanecem corretos.

### Resultado esperado

- O sistema deve permanecer disponível durante períodos de alta demanda.
- O carrinho não deve perder produtos indevidamente.
- Os valores dos produtos devem permanecer íntegros.
- Pedidos não devem ser duplicados ou alterados incorretamente.
- Informações dos clientes devem continuar protegidas.

### Avaliação

| Critério | Resultado esperado |
|---|---|
| Disponibilidade | Sistema continua acessível |
| Carrinho | Produtos permanecem corretos |
| Integridade | Dados do pedido não são alterados |
| Processamento | Pedidos processados corretamente |
| Confidencialidade | Dados dos clientes continuam protegidos |

---

# Conclusão

A benchmark do **Quitandinha Online**, realizada em **10/08/2026**, avalia situações relacionadas aos principais pilares da Segurança da Informação.

O **Caso 1** concentra-se principalmente na **Confidencialidade, Autenticidade e Integridade**, verificando a proteção das informações dos clientes e o controle de acesso.

O **Caso 2** concentra-se principalmente na **Disponibilidade e Integridade**, verificando se o sistema permanece funcional durante períodos de alta demanda sem comprometer os dados das compras.

A aplicação desses testes permite identificar possíveis falhas de segurança e verificar se o Quitandinha Online mantém seus dados e serviços protegidos.
