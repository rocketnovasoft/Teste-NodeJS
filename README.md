# Teste Técnico - Desenvolvedor(a) Full Stack Node.js

Quando finalizar o teste, publique tudo no seu [Github](https://github.com) de modo público e envie por email com o título `[Teste Full Stack Node.js] Finalizado` para vagas@rocketnova.com.br

## Backend

Desenvolver uma **API JSON RESTful** em **Node.js**, utilizando **Express**, com os métodos (`GET`, `POST`, `PUT`, `DELETE`).
Salvar dados em um banco de dados MySQL, utilizando **Knex**.

### Especificação

Monte uma base de veículo com a seguinte estrutura:

```
veiculo:   string
marca:     string
ano:       integer
descricao: text
vendido:   bool
created:   datetime
updated:   datetime
```

Utilize **MySQL** através do **Knex** para armazenar os dados que a **API** irá consumir.

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

Desenvolver **UI (User Interface)** baseado no escopo que está na pasta [layout](https://github.com/rocketnova-dev/Teste-NodeJS/tree/master/layout), utilizando HTML, CSS e Javascript (Pode usar jQuery).

### Especificação

- Consumir **API** criada acima
- Criar uma tela que tenha:
    - Listagem de veículos
    - Detalhe do veículo
    - Busca
    - Formulário de novo/edição de veículos

### Dica

Você poderá utilizar bootstrap para auxiliar no desenvolvimento da interface, encontrado através do link:

- http://getbootstrap.com/css/

## Dúvida

Se tiver qualquer dúvida sobre esse teste, envie um email com o título `[Teste Full Stack Node.js] O assunto que vc deseja` para vagas@rocketnova.com.br
