# Alura JS Assincrono - Projeto Petshop
<p>Este projeto é voltado ao JS na web com método CRUD utilizando JavaScript assíncrono da Alura.</p>

<img src="https://i.imgur.com/M3PR76r.png">

## Funcionalidades

<p>Através deste projeto é possível verificar:</p>

- Criação, alteração e exclusão de Cadastro de Cliente
- Verificação em tempo real das alterações ocorrendo no db.json
- Utilização do localStorage

## Rodando a Aplicação

<p>Estes são os passos que deve seguir para utilizar a aplicação:</p>

### Rodar o JSON Server: 

> Obs.: É necessário rodar o JSON Server para que as alterações feitas com a aplicação em produção. Com este comando o projeto rodará em http://localhost:3000

```js
json-server --watch db.json
```
### Rodar da aplicação: 

> Obs.: É necessário rodar o comando abaixo em outro terminal (abrir um novo terminal). Pois com o JSON Serve estará funcionando na porta 3000, nisso este comando abre um novo servidor na porta 5000.  

```js
browser-sync start --server --file . --host --port 5000 --startPath telas/lista_cliente.html
```

:heartbeat: Paixão por Desenvolver :heartbeat:
