
# API Med Volume 1

Nesta API, foi criado um sistema de cadastro para médicos e pacientes. 
Foi implementada uma estrutura completa de "CRUD", permitindo realizar as seguintes operações:

- Create (Criação): Inserir novos registros ou dados por meio da API;
- Read (Leitura): Recuperar, visualizar ou ler dados por meio da API;
- Update (Atualização): Modificar ou atualizar dados existentes por meio da API;
- Delete (Exclusão): Remover registros ou dados por meio da API.

Essa abordagem proporciona uma gestão abrangente e eficiente dos dados relacionados a médicos e pacientes, 
permitindo a interação fluida e organizada com a API para realizar diversas operações essenciais no contexto da saúde.




## Documentação da API

#### Retorna todos os Medicos

```http
  GET /medicos
```

| Parâmetro   | Tipo       | 
| :---------- | :--------- | 
| `nome` | `string` | 
| `email` | `string` | 
| `crm` | `string` | 
| `especialidade` | `Especialidade` | Enum
| `logradouro` | `string` | 
| `bairro` | `string` | 
| `cep` | `string` | 
| `cidade` | `string` |
| `uf` | `string` |
| `complemento` | `string` |
| `numero` | `string` |

#### Retorna um Medico

```http
  GET /medicos/${id}
```

| Retorno todos os dados acima de apenas um medico conforme o ID desejado   |
| :---------- |

#### Retorna todos os pacientes

```http
  GET /pacientes
```

| Parâmetro   | Tipo       | 
| :---------- | :--------- | 
| `nome` | `string` | 
| `email` | `string` | 
| `cpf` | `string` | 
| `logradouro` | `string` | 
| `bairro` | `string` | 
| `cep` | `string` | 
| `cidade` | `string` |
| `uf` | `string` |
| `complemento` | `string` |
| `numero` | `string` |

#### Retorna um Paciente

```http
  GET /pacientes/${id}
```

| Retorno todos os dados acima de apenas um paciente conforme o ID desejado   |
| :---------- |




## Stack utilizada

**Back-end:** Java, MySql


## Aprendizados


Neste projeto, houve um aprimoramento significativo do conhecimento relacionado a APIs, 
com ênfase na implementação de um CRUD abrangente por meio dos verbos HTTP: GET, POST, PUT e DELETE. 

Essa abordagem proporcionou uma compreensão mais sólida e prática sobre como estruturar e interagir com APIs, 
permitindo operações completas de criação, leitura, atualização e exclusão de dados. 
O entendimento aprofundado desses verbos HTTP não apenas fortaleceu a capacidade de desenvolver sistemas mais eficientes, 
mas também estabeleceu uma base sólida para a construção de interfaces de programação de aplicações.


## Autor

- [@wilsonfirmino](https://www.github.com/wilsonfirmino)

