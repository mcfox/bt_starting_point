# setup-starting-point

run this script to:

```
./setup-starting-point

```

- Atualizar o Gemfile com as novas gems:
  - dotenv-rails
  - diffy
  - aws-sdk-s3
  - caxlsx
  - caxlsx_rails
  - roo
  - honeybadger
- Configurar o tema (gray, navigation left, logo enabled)
- Aplicar customizações de Menu e UI (Sidekiq, Swagger, Logo)
- Adicionar suporte a Logo e Home URL no modelo Team
- Configurar a Documentação Swagger
- Copiar os arquivos de documentação e diretório .junie
- Criar a configuração do Honeybadger


para executar esse script, va para a pasta raiz do projeto e execute:

```
curl -fsSL https://raw.githubusercontent.com/mcfox/bt_starting_point/main/setup-starting-point | ruby
```