# sodexo
Módulo não oficial para consulta de saldo dos cartões sodexo.

## Instalação

    $ npm i sodexo-api

## Uso

```javascript
const sodexo = require('sodexo-api');

// passe como parâmetros o número do cartão e o cpf do titular
sodexo.saldo(cartao, cpf)
  .then((res) => {
    console.log(res);
  });
```

## Licença
MIT
