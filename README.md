# README

## init Ror project

```bash
# Ejecución en db mysql
rails new . --api -d mysql -T
# Ejecución en db potgresql
rails new . --api -d postgresql -T
 # abrir postgresql 
 # ejecutar rails db:create
```

## ejecution project

```
rails s
```

## Install gem's project
```
rails webpacker:install
```

## MYSQL DB correction

```bash
# Esto por lo general se instala una sola vez

gem install mysql2 --platform=ruby -- '--with-mysql-lib="C:\mysql-connector\lib" --with-mysql-include="C:\mysql-connector\include" --with-mysql-dir="C:\mysql-connector"'
```

## Generar controlador
```
rails g controller Subject index show edit new delete
rails g controller page index show edit new delete

rails destroy controller subject index show edit new delete
```

## Generar Modelos
```
rails g model Subject name:string position:integer visible:boolean
rails db:migrate 
```