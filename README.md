# Angular_APIREST_SpringBoot
Projeto Criado durante a realização do curso Angular, REST SpringBoot

Infelizmente só criei esse repositorio em uma determinada etapa mais avançada do curso. 

# Diario de Bordo

Até onde ja foi visto: 

- Conexão com o MYSQL
- Migração de dados com Flyway
- consultando o primeiro recurso com GET
- Criando nova categoria
- Validações
- Utilização de eventos
- Delete 

Postman: 

![Postman](https://user-images.githubusercontent.com/75328283/126040641-ef3e6cce-3b0f-4f57-be3f-a1a309d9430e.png)

# Dia 17/07/2021

- função de delete para as categorias implementadas, antes eu só tinha adicionado em pessoas

Delete:
![deletarCategoria](https://user-images.githubusercontent.com/75328283/126044292-e1d9a1dd-e498-4731-a6da-21c566cbcccd.png)


- Função de Put(Update) em Pessoa implementada + Put parcial(apenas de uma pripriedade em especifica)

Updade: 
![AtualizarPessoa](https://user-images.githubusercontent.com/75328283/126044315-b32852ac-e5e3-425c-817b-1a97578c0081.png)

Updade na pripriedade Ativo em Pessoa: 
![AtualizaçãoParcial](https://user-images.githubusercontent.com/75328283/126044338-3412e857-77c3-4f48-a766-71cbae615683.png)

- Migration e model de Lançamento foram implementadas.

# Dia 19/07/2021

- Resource, Repository de lançamento foram implementados.
- Requisição Get e Requisição Get by id em lançamento implementadas.

GET REQUEST
![ListarLancamento](https://user-images.githubusercontent.com/75328283/126201761-1489bf1c-04ba-4c9b-84f1-3e92ac55b13d.png)

GET by ID
![Lista lancamento by id](https://user-images.githubusercontent.com/75328283/126201802-4461992f-9a06-4a99-a39c-61e5c32a0cc2.png)

- Validando incosistencias em lançamento

![Validando Icoerencias](https://user-images.githubusercontent.com/75328283/126210898-264e73b6-837a-4c4b-a479-c54ecd218534.png)

-  Validando Lançamento com Bean validetion 

![Validando Lançamento com BEAN Validation](https://user-images.githubusercontent.com/75328283/126211173-cb4005c9-19ae-487f-89f9-ca10ad8dcd85.png)

- Implementando pesquisa de lancamento com Metamodel
- Paginação implementada 
 
![Paginação](https://user-images.githubusercontent.com/75328283/126239644-40c30900-e607-4b46-a0b7-52daf5d255cd.png)

- Autenticação basica implementada

![AuthBasico](https://user-images.githubusercontent.com/75328283/126244900-3cb0952f-bff9-4a48-9487-8e8b1ba5d7f2.png)

# Dia 23/11/2021

- Autenticação O Auth2 e JWToken implementados

![OAuth2](https://user-images.githubusercontent.com/75328283/143110355-41bce256-14aa-40e2-b7ef-b5b451fbcb50.png)

![JWToken](https://user-images.githubusercontent.com/75328283/143110459-5aaafc31-63ac-4d61-ae80-a9cb600d1867.png)

# Dia 25/11/2021

- Refresh token implementado

# Dia 26/11/2021

- Transferir o Refresh token para dentro de um Cookie implementado

![Colocar o refresh token dentro de um cookie](https://user-images.githubusercontent.com/75328283/143624654-5d5cec98-c286-4416-80dc-cf4c0f426777.png)

# Dia 01/12/2021

- CORS implementado
- Moção de usuario para o banco de dados implementada
- Permissões de acesso implementadas
- Logout implementado
- Projeção de lançamento implementa

# Dia 14/12/2021

- Profiles do Spring implementados
- Nome do usuario no JWToken implementado
- Alternância entre Oauth2 e Basic Security implementada
- Pesquisa de pessoa implementada
- Atualização de Lançamento implementada

 *APIREST - SPRINGBOOT FINALIZADA

Obs: A parte de Bakend com Springboot foi finalizada pelo dia 03/12 porém havia esquecido de fazer a atualização aqui no git. 

# Dia 05/01/2022

Primeiro commit da parte do frontend do projeto

Partes teóricas:

- components
- Introdução a data binding
- Interpolação
- Event binding
- Variável de referência
- Property binding
- Two-way data binding
- diretivas
- diretiva ngFor
- @input
- @output e EventEmitter
- CSS dinâmico com ngStyle
- Classes CSS dinamicas com ngClass

Pratica:

- Protótipo do projeto criado
- Protótipo de pesquisa de Lançamentos implementado
- Protótipo de tabela de dados implementado
- ng-template implementado

![Protótipo pesquisa e tabela de dados de lançamentos](https://user-images.githubusercontent.com/75328283/148245235-30e3bac0-46ec-4742-af12-e77d1441d0ce.png)

# Dia 28/01/2022

Obs:  uma boa parte do projeto já foi frontend já foi feita então o proximo commit provavelmente será o ultimo. 

- paginação dos dados implementada
- componente barra de navegação implementado
- componente de pesquisa de lançamento implementada
- menu intercambiável implementado 
- Ngform Implementado
- Protótipo de cadastro de Lançamento implementado
- Validação de controles de formulário implementada
- Serviço de consulta de lançamento implementado
- Filtro por descrição na  pesquisa de lançamentos implementado
- Filtro por datas na pesquisa de lançamentos implementado
- Implementação de paginação no serviço de lançamento
- Paginação lazy implementada e configurada
- Consulta e listagem de pessoa implementadas
- Serviço de exclusão e decorador @ViewChild implementados
- Mensagens e ConfirmDialog implementados
- Serviço de tratamento de erros implementado
- Serviço de exclusão de pessoa implementado
- errorHendlerService aprofundada
- Mudança de status de pessoa Implementada

