# planning-poker

## Room Object
```
// ROOM_OBJECT
{
  name: 'citystack',
  token: 'X7J6',
  cards: [ 1, 2, 3, 5, 8, ? ]
}
```


## POST: /poker/rooms
### Request:
```
{
  name: 'citystack',
  cards: [ 1, 2, 3, 5, 8, ? ]
}
```
### Response:
```
ROOM_OBJECT
```

## GET: /poker/rooms
### Request:
No request data.
### Response:
```
{
  data: [
    ROOM_OBJECT,
    ROOM_OBJECT,
    ROOM_OBJECT,
  ]
}
```

## GET: /poker/rooms/{token}
### Response:
```
{
  data: ROOM_OBJECT
}
```

##
