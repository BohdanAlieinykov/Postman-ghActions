# Postman + newman + github actions & pages🏞️
----
 __This project contains 15 api request on local server:__
- __5 for /users__
- __5 for /orders__
- __5 for /products__
##### Each request has specific tests inside. Github Actions & Pages runs every push.
----

## Steps to reproduce💻
1. Download this repo.
2. Run `npm i` (install node.js dependencies)
3. Run `npm run tern-on-api`(to run testing server locally )

### Overview👀
Routes `/products`, `/orders` and `/users`. Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /products     | *None*     | **Array**          |
| GET      | /products/:id |  **e.g 3** | **Object**         |
| POST     | /products     | **object** | **Created object** |
| PUT      | /products     | **object** | **Updated object** |
| DELETE   | /products/:id | **e.g 3**  | **Deleted object** |


5. Upload `Postman-newman.postman_collection.json` in Postman app. 
6. Run collection in Postman
----
## Additional info🔍
[Click here to observe HTML report](https://markuslarson.github.io/Postman-ghActions/)