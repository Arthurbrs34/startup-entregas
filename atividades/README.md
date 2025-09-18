# Diagramas de Atividades – startup de entregas

Este repositório possui os **diagramas de atividades detalhados** para cada User Story (US) do projeto.  
Os diagramas representam o **fluxo passo a passo das ações do usuário**, incluindo as validações e decisões**.

## Estrutura dos diagramas

- **Início:** círculo preto (`Início`).  
- **Ações/passos:** retângulos, mostrando ação do usuário.  
- **Decisões:** losango, indicando validações ou erros.  
- **Fim:** duplo círculo (`Fim`).  

## Diagramas por User Story

### US01 – Cadastro de usuário
Usuário cadastra-se informando nome, email e senha. Validações de dados e email existente incluídas.  
![US01](US01(CADASTRO).png)

### US02 – Login no sistema
Usuário realiza login com usuário/email e senha. Validações das credenciais incorretas incluídas.  
![US02](US02(LOGIN).png)

### US03 – Criar pedido de entrega
Cliente cria pedido informando item e endereço, com validação de dados.  
![US03](US03(CRIARPEDIDO).png)

### US04 – Listar meus pedidos
Cliente visualiza todos os pedidos realizados e acompanha os status.  
![US04](US04(LISTARPEDIDOS).png)

### US05 – Ver pedidos disponíveis
Entregador visualiza pedidos pendentes para escolher qual aceitar.  
![US05](US05(VERPEDIDOS).png)

### US06 – Aceitar pedido
Entregador aceita o pedido para realizar entrega.  
![US06](US06(ACEITARPEDIDO).png)

### US07 – Marcar pedido como entregue
Entregador finaliza entrega e atualiza status do pedido.  
![US07](US07(ENTREGUE).png)

### US08 – Gerenciar usuários
Gerente visualiza lista de usuários e detalhes.  
![US08](US08(GERENCIARUSUARIOS).png)

### US09 – Excluir pedido
Gerente exclui pedidos incorretos ou inválidos, verificando de erros.  
![US09](US09(EXLUIRPEDIDO).png)

### US10 – Logs de alteração
Gerente visualiza histórico de alterações e pode filtrar as informações.  
![US10](US10(LOGS).png)
