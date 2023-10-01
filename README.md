# micro-pos-backend-spring

SIMPLE DEMO - Point of sale.

Spring - hibernate - postgret



## Servidor Node.js con Fastify

Este repositorio contiene un servidor Node.js que utiliza el micro-framework Fastify.

### Inicialización del Proyecto

Sigue estos pasos para inicializar el proyecto:

1. Instala las dependencias utilizando npm:

   ```shell
   npm install

2. Inicializar proyecto:

    ```shell
   npm run start 

## Obtener Todos los Métodos de Pago

### Método

**GET**

### URL

`http://localhost:3000/api/payment-method/`

### Parámetro Opcional

Para filtrar por tipo, proporciona el siguiente parámetro:

```json
{
  "params": {
    "type": "<string, uno de [credit_card, debit_card]>"
  }
}
```

## Obtener Método de Pago Filtrado por ID
### Método
**GET**

### URL
`http://localhost:3000/api/payment-method/{id}/`

## Eliminar Método de Pago por ID
### Método
**DELETE**

### URL
`http://localhost:3000/api/payment-method/{id}/`

## Obtener Todos los Métodos de Pago en Formato CSV
### Método
**GET**

### URL
`http://localhost:3000/api/payment-method/csv-format/`

