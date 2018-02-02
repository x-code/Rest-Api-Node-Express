# RESTful API built with Node.js, Express.js and MongoDB.

## RESTful API endpoints

### GET `/api/items`

Get all items.

+ Method: `GET`
+ URL: `/api/items`

### POST `/api/items`

Create a new item.

+ Method: `POST`
+ URL: `/api/items`
+ Body:

```js
{
  "name": "Iphone X",
  "description": "Lorem ipsum",
  "quantity": "20"
}
```

### GET `/api/items/:itemId`

Get item with specific id.

+ Method: `GET`
+ URL: `/api/items/1`

### PUT `/api/items/:itemId`

Update entire item with specific id.

+ Method: `PUT`
+ URL: `/api/items/1`
+ Body:

```js
{
  "name": "Iphone IX",
  "description": "Lorem ipsum",
  "quantity": "20"
}
```

### PATCH `/api/items/:itemId`

Update part of the item with specific id.

+ Method: `PATCH`
+ URL: `/api/items/1`
+ Body:

```js
{
  "quantity": "30"
}
```

### DELETE `/api/items/:itemId`

Delete item with specific id.

+ Method: `DELETE`
+ URL: `/api/items/1`

## Install

`npm install`

## Run

1. Make sure MongoDB is running
2. `npm run start`
