# NServiceBus

Despliegue a Pivotal como microservicios.

Se reemplazaron las referencias a proyectos por paquetes NuGet.

URL
```
POST	https://dycsw-nservicebus-sales-api-fearless-quokka.cfapps.io/v1/Sales
```

Request
```
{
"OrderId": 120,
"OrderData": "Hello world"
}
```


Response
```
{
    "orderId": "7b048eda-49ff-48cc-a25d-e5878c16fa75",
    "orderData": "Hello world"
}
```