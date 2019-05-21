# api-test

# /POSTS
## GET
### Request:
curl -i -X GET api.softhouse.rocks/posts
### Response
`Status code: 200 (OK)`
```
[
  {
    "_id": "5caaef896b334800cbf6634a",
    "userId": 2,
    "id": 15,
    "title": "eveniet quod temporibus",
    "body": "reprehenderit quos placeat\nvelit minima officia dolores impedit repudiandae molestiae nam\nvoluptas recusandae quis delectus\nofficiis harum fugiat vitae",
    "__v": 0
  },

´´´
##POST
### Request:

curl -i -X POST -H "Content-Type:application/json" http://api.softhouse.rocks/posts -d '{"title":"Hi, World",
"body":"Fresh as morning dew", "userId": "5"}'

### Response
´´´
`Status code: 201 Created`

´´´
