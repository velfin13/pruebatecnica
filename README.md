
# Prueba Tecnica

para levantar la aplicación ejecute este comando

```
docker compose up -d
```

una vez levantado en su navegador

http://localhost:8080/swagger-ui/index.html

este es el del servicio de hub!

en la peticion post debe enviar como cuerpo

```
{
    "hotelId": 2,
    "checkIn": "2018-10-20",
    "checkOut": "2018-10-25",
    "numberOfGuests": 3,
    "numberOfRooms": 2,
    "currency": "EUR"
}
```

para ver la api que se esta usando como mock vea en el navegador

http://localhost:8088/swagger-ui/index.html

en la peticion post enviar como cuerpo

```
{
    "hotel": 4,
    "checkInDate": "2018-10-20",
    "numberOfNights": 5,
    "guests": 3,
    "rooms": 2,
    "currency": "EUR"
}
```