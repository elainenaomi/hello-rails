# Hello Rails

[Apresentação do Bootcamp](https://speakerdeck.com/elainenaomi/bootcamp-de-rails-caquicoders-meetup)

# Criando o projeto

`rails new hello-rails`

# Iniciando a aplicação

`rails s` ou `rails server`


# Criando um CRUD para criar/listar/atualizar/apagar anotações

`rails generate scaffold Notes content:string`


# Estrutura de diretórios


`app`: contém os controllers, models, views, helpers, mailers, jobs, assets para sua aplicação.

`bin`: contém os scripts para iniciar a sua aplicação, atualizar, fazer deploy, etc.

`config`: contém as configurações de rotas, banco de dados, etc.

`db`: contém o esquema do seu banco de dados e as migrações necessárias para atualizar seu esquema.

`Gemfile`: arquivo para especificar as dependências da sua app Rails.

`Gemfile.lock`: especifica as versões das gems utilizadas no seu projeto. Evita que cada desenvolvedor tenha uma versão diferente de um gem localmente. O Bundler utiliza esses arquivos.

`lib`: módulos complementares da sua app

`log`: arquivos de log da app

`public`: o único diretório público. Cuidado com o que colocar aqui. Pode colocar arquivos estáticos e assets compilados.

`test`: testes de unidade, integração, feature, fixtures, etc.

`tmp`: arquivos temporários como cache.

`vendor`: usado pelas gems. Contém código de terceiros.

`.ruby-version`: contém a versão do ruby utilizada



# Acessando a aplicação via console

`rails c`


# Por que não usar o scaffold?

- Normalmente aplicações reais não são tão simples e o `scaffold` não atende a essa necessidade.

- Ele pode criar mais código do que você precisa para resolver seu problema
