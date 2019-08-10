# This is UBER APPLICATION

## User (Accounts)
- Drivers * 
- Clients *

## Items (Orders)
- Orders *
- Payments *

## Items (Others)
- Cars

## Items (user specific data)
- Localizations

## Items (Score system)
- Rate

## Features
- Order car and driver for ride *
- Pay for a ride * 
- Rate a driver for a ride


## Endpoint
URL = http://api.app.cpm/login

    POST http://api.app.cpm/login
    GET http://api.app.cpm/logout
    GET http://api.app.cpm/orders/ = get list
    POST http://api.app.cpm/orders/ = create
    GET http://api.app.cpm/order/12 = get one item
    POST http://api.app.cpm/order/12 - update one item
    DELETE http://api.app.cpm/order/12 - delete one item
    http://api.app.cpm/order/12/cars
    http://api.app.cpm/settings
    GET /nearby_drivers = get driver list