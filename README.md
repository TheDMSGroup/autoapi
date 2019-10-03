#Auto API
----
#### Makes and Models Data in Static JSON files, served on GitHub's GitPages service. Cached behind CloudFlare!

```
./makes/
    2002
    2003
    2004
    ...
    2018
```

```
./models/
    Audi
    Ford
    Fiat
    ...
    Volvo
```

*Grabbing a list of makes for 2003*
GET Request to [autoapi.domain]/makes/2003
Returns:
```
{"count":47,"data":[{"year":2002,"name":"Acura"},{"year":2002,"name":"Alfa Romeo"},{"year":2002,"name":"Aston Martin"},{"year":2002,"name":"Audi"},{"year":2002,"name":"Bentley"},{"year":2002,"name":"BMW"},{"year":2002,"name":"Buick"},{"year":2002,"name":"Cadillac"},{"year":2002,"name":"Chevrolet"},{"year":2002,"name":"Chrysler"},{"year":2002,"name":"Daewoo"},{"year":2002,"name":"Dodge"},{"year":2002,"name":"Fiat"},{"year":2002,"name":"Ford"},{"year":2002,"name":"GMC"},{"year":2002,"name":"Honda"},{"year":2002,"name":"Hummer"},{"year":2002,"name":"Hyundai"},{"year":2002,"name":"Infiniti"},{"year":2002,"name":"Isuzu"},{"year":2002,"name":"Jaguar"},{"year":2002,"name":"Jeep"},{"year":2002,"name":"Kia"},{"year":2002,"name":"Land Rover"},{"year":2002,"name":"Lexus"},{"year":2002,"name":"Lincoln"},{"year":2002,"name":"Lotus"},{"year":2002,"name":"Maserati"},{"year":2002,"name":"Mazda"},{"year":2002,"name":"Mercedes Benz"},{"year":2002,"name":"Mercury"},{"year":2002,"name":"Mini"},{"year":2002,"name":"Mitsubishi"},{"year":2002,"name":"Nissan"},{"year":2002,"name":"Oldsmobile"},{"year":2002,"name":"Pontiac"},{"year":2002,"name":"Porsche"},{"year":2002,"name":"Rolls Royce"},{"year":2002,"name":"Saab"},{"year":2002,"name":"Samsung"},{"year":2002,"name":"Saturn"},{"year":2002,"name":"Smart"},{"year":2002,"name":"Subaru"},{"year":2002,"name":"Suzuki"},{"year":2002,"name":"Toyota"},{"year":2002,"name":"Volkswagen"},{"year":2002,"name":"Volvo"}]}
```

*Grabbing a list of Volvo models*
GET Request to [autoapi.domain]/models/Volvo
```
{"count":15,"data":[{"name":"C30"},{"name":"C70"},{"name":"S40"},{"name":"S60"},{"name":"S80"},{"name":"V40"},{"name":"V50"},{"name":"V60"},{"name":"V60 Cross Country"},{"name":"V70"},{"name":"X670"},{"name":"XC60"},{"name":"XC70"},{"name":"XC90"},{"name":"YCC"}]}
```