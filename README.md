# Teste Product Owner - Shipay

### 1) Conheça um pouco mais sobre a hierarquia de cadastro na Shipay:

O cadastro básico de um cliente Shipay consiste em:

**(i)   Conta Shipay:** Conta do lojista cadastrado na Shipay 
 - Dados necessários: nome da conta e email de cadastro

**(ii)  Usuário do Painel Shipay:** permite login no Painel Shipay
- Dados necessários: nome, cpf, telefone, e-mail do usuário e senha

**(iii) Loja:** Necessário para o cliente conseguir gerar cobranças via PIX e carteiras digitais 
- Dados necessários: CNPJ, endereço, nome da loja, quantidade de caixas

---

Atualmente só é possível cadastrar essas entidades separadamente, ou seja, primeiro é necessário cadastrar a **(i) Conta Shipay**, depois deve ser cadastrado o **(ii) Usuário do Painel Shipay** e após, deve ser cadastrada uma **(iii) Loja** na Conta do cliente Shipay. Cada um desses cadastros é feito por um usuário administrador em formulários separados.


Considerando esse cenário, um parceiro estratégico trouxe a seguinte demanda para você, Product Owner da Shipay:


*"Gostaria de ter a possibilidade de cadastrar a **(i) Conta Shipay**, o **(ii) Usuário do Painel Shipay** e uma **(iii) Loja** com um único formulário para não ter que acessar 3 formulários separados para concluir o cadastro do Lojista na Shipay."*


Você entendeu a demanda e pediu auxílio do time de Design de Produto para desenhar uma tela com essa funcionalidade. O time de Design te entregou o seguinte modal de cadastro:

![modal_de_cadastro_completo](https://user-images.githubusercontent.com/59707512/137926227-831000a7-ae66-4b34-80d3-d45fda7f909f.png)


#### Você aprovou o design da tela e deve priorizar essa atividade junto ao time de desenolvimento. Escreva a user-story para essa funcionalidade:

**Resposta:** 

**User Story 123:** Unificação de formulários para cadastro de logista.

**Prioridade "1"**

**Solicitante:** Usuário Administrador

Eu como usuário administrador, gostaria de cadastrar a (i) Conta Shipay, o (ii) Usuário do Painel Shipay e uma (iii) Loja com um único formulário para não ter que acessar 3 formulários separados para concluir o cadastro do Lojista na Shipay.

**Critérios de Aceitação:** O formulário unificado precisa conter todos os campos obrigatórios para a criação de um novo cadastro de logista na Shipay e contemplar o os cadastros  **(i) Conta Shipay**, o **(ii) Usuário do Painel Shipay** e uma **(iii) Loja simultaneamente, sem gerar impacto para outras funcionalidades. 

**Resultado Esperado:** Concluir um cadastro de Lojista na Shipay através de um único formulário. 


---


### 2) O time de desenvolvimento concluiu o desenvolvimento da funcionalidade descrita na questão anterior. Quais testes funcionais você faria para validar essa funcionalidade?

**Resposta:** Teste de Caixa Preta para garantir que atende os requisitos e cumpre com as funções que deve executar, e teste de usabilidade com objetivo de verificar se a nova funcionalidade pode ser facilmente compreendida pelo usuário final, homologação com o solicitante antes de disponibilizar a nova funcionalidade em produção. 
