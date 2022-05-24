# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Abaixo teremos as descrições das personas, histórias dos usuários, além de levantar requisitos funcionais e não funcionais especificando também as restrições.


## Personas

Isabela tem 21 anos, é estudante e estagiária. Pensa em organizar suas finanças com mais praticidade/facilidade. Hoje no mercado as aplicações são muito complexas dificultando a experiencia do usuário, com interfaces pouco intuitivas sente que não auxiliam no controle de suas finanças.

Luan tem 20 anos, é estudante e autônomo. Tem controle de suas finanças sem a necessidade de anotações/planilhas. Busca uma aplicação simples que possa o auxiliar melhor nesse controle sem ocupar muito de seu tempo.

Fabrício tem 40 anos, é graduado e tem um emprego comum. Hoje faz o seu controle por meio de planilhas/dashboards, sente dificuldade em manipula-las no dia a dia, pois a um nível de complexidade alto. Busca algo que leve e fluído para controlar suas finanças.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:


|EU COMO... `USUÁRIO`| QUERO/PRECISO ... `REGISTRAR RECEITAS/DESPESAS` |PARA ... `CONTROLE`                     |
|--------------------|-------------------------------------------------|----------------------------------------|
| Usuário do sistema | Identificar minhas receitas e despesas          | Controlar meu orçamento                |

|EU COMO... `USUÁRIO`| QUERO/PRECISO ... `VERIFICAR SALDO`             |PARA ... `PLANEJAR GASTOS`              |
|--------------------|-------------------------------------------------|----------------------------------------|
| Usuário do sistema | Visualizar a quantidade de dinheiro que possuo  | Saber se posso gastar                  |

|EU COMO... `USUÁRIO`| QUERO/PRECISO ... `SEPARAR EM CATEGORIAS`                          |PARA ... `CATEGORIZAR`                  |
|--------------------|--------------------------------------------------------------------|----------------------------------------|
| Usuário do sistema | Classificar minhas receitas e despesas por meio de categorias      | Verificar valores por categorias       |


## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito                  | Prioridade |
|------|-----------------------------------------|------------|
|RF-001| Permitir que o usuário cadastre receitas e despesas | ALTA | 
|RF-002| Criar categorias | ALTA |
|RF-003| Visualizar histórico de receitas e despesas | ALTA |
|RF-004| Cadastrar usuário | ALTA |
|RF-005| Visualizar saldo | ALTA |
|RF-006| Identificação de pagamento (PAGO/NÃO PAGO) | MÉDIA |
|RF-007| Notificação de vencimento | MÉDIA | 
|RF-008| Visualização em gráficos de despesas e receitas | BAIXA |
|RF-009| Permite que o usuário defina um limite de gasto mensal | BAIXA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  | Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 5s |  BAIXA | 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
|03| O projeto deve ser desenvolvido nas linguagens HTML/CSS/JavaScript |
