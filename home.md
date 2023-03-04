# RESTful Authors API - API Catalog CLI Demo

## Note: This is a dummy documentation

Show Authors details for specific given Id

**URL** : `/api/authors, /api/authors/:id`

**Resources** : `Authors, Authors/{id}`

**Methods** : `GET`

**Auth required** : Yes

## Success Response

**Code** : `200 OK`

**Content Example**: ```json
[{
	  "authorId": "1",
	  "name": "Jeanette Penddreth",
	  "email": "jeanette.p@mulesoft.com",
	  "phone": "9781593275846",                  
	  "isbn": "isbn-59327-asfn"
  }, {
	  "authorId": "2",
	  "name": "Giavani Frediani",
	  "email": "g.f@apisero.com",
	  "phone": "9781593275846",
	  "isbn": "isbn-12345-asfn"
  }]
```
## Error Responses

**Code** : `404 NOT FOUND`

**Content Example** : `{ "Message": "Resource not found!!"}`