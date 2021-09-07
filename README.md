#Microservice Product



### Endpoints:


#### SaveProduct

...........
POST /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:passport)
Content-Type: application/json
Content-Length: 43

{
"name":"test-1",
"price":1.2
}
...........

#### Get Products

.......
GET /api/product HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:passport)

.....

#### Delete Product

......
DELETE /api/product/2 HTTP/1.1
Host: localhost:3333
Authorization: Basic base64(username:passport)
.....
