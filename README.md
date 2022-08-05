# Teste Técnico - Desenvolvedor(a) Full Stack

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) de modo público e envie por email com o título `[Teste Full Stack Node.js] Finalizado` para rocketnovasoft@gmail.com

## Backend

Desenvolver uma **API JSON RESTful** em **Node.js**, utilizando **Express** ou algum framework (utilizamos **TypeORM**, **AdonisJS** e **Prisma** em nossos projetos, se fizer em um deles, seria massa), com os métodos (`GET`, `POST`, `PUT`, `DELETE`).
Salvar dados em um banco de dados MySQL ou Postgres.

### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
marca:     string
ano:       integer
descricao: string
vendido:   bool
created:   datetime
updated:   datetime
```

### API Endpoint

`GET /veiculos`

Retorna todos os veículos

---

`GET /veiculos` (Bônus, não obrigatório :star:)

Retorna os veículos de acordo com filtros passados através de query string

---

`GET /veiculos/{id}`

Retorna os detalhes do veículo

---

`POST /veiculos`

Adiciona um novo veículo

---

`PUT /veiculos/{id}`

Atualiza os dados de um veículo

---

`DELETE /veiculos/{id}`

Apaga o veículo


## Frontend

Desenvolver **UI (User Interface)** baseado no escopo que está na pasta [layout](https://github.com/rocketnova-dev/Teste-NodeJS/tree/master/layout), utilizando React (se usar Material-UI vai fazer nossos olhos brilharem).

### Especificação

- Consumir **API** criada acima
- Criar UI que tenha:
    - Listagem de veículos
    - Detalhe do veículo
    - Busca
    - Formulário de novo/edição de veículos (não obrigatório)

## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Full Stack Node.js] O assunto que vc deseja` para rocketnovasoft@gmail.com
