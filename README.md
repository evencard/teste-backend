# Teste de dev backend da Even

Este teste é aplicado aos candidatos as vagas de desenvolvimento backend.

### O Desafio

O objetivo desse teste é desenvolver uma api com os métodos abaixo:

-   Listar estabelecimentos
-   Obter um estabelecimento pelo id
-   Incluir um novo estabelecimento
-   Alterar o nome fantasia e valor de faturamento mensal de um estabelecimento

##### Campos

-   Nome Fantasia
-   CNPJ
-   Valor de Faturamento Mensal
-   Data de Início de Relacionamento

#### Requisitos

-   A primeira página deve exibir uma lista de estabelecimentos, e pra cada registro ter a opção de detalhar / editar o mesmo;
-   Ainda na página de listagem deve existir uma maneira de criar um novo estabelecimento.
-   Na página de detalhe deve ser possível editar os dados;
-   Fazer a persistência dos dados num arquivo `json` ou algum banco de dados da sua escolha (pode ser em memória);
-   Linguagem livre

Para ter o estado inicial da lista de estabelecimentos, pode usar o exemplo abaixo:

```json
[
    {
        "nomeFantasia": "Acme Software ME",
        "cnpj": "92.211.058/0001-00",
        "valorFaturamentoMensal": 300000.0,
        "dataInicio": "2020-03-01"
    },
    {
        "nomeFantasia": "Contoso Financeira SA",
        "cnpj": "98.024.704/0001-07",
        "valorFaturamentoMensal": 1500000.0,
        "dataInicio": "2018-09-01"
    },
    {
        "nomeFantasia": "Adventureworks  Veículos Ltda",
        "cnpj": "20.234.033/0001-03",
        "valorFaturamentoMensal": 2000000.0,
        "dataInicio": "2016-12-01"
    }
]
```

#### Plus:

-   Utilizar algum framework de documentação automática (Ex.: swagger)
-   Permitir excluir um registro;
-   Testes unitários;

#### O que esperamos:

-   Que a aplicação funcione
-   Padrão de Projeto e boas práticas de Orientação a Objetos;
-   Criar um passo a passo de como rodar sua aplicação [(Sugestão)](https://github.com/wearehive/project-guidelines/blob/master/README.sample.md);
-   Criar uma breve descrição da solução utilizada.

### Forma de Entrega

Pode utilizar alguma das formas abaixo:

-   Subir o código no seu github pessoal ou similar e nos enviar o link
-   Fazer um PullRequest
-   Subir o zip do código no seu drive e compartilhar conosco (dropbox, google drive, one drive, etc)
-   Enviar o zip por email para provas@evencard.com.br

**_ Use sua criatividade _**
