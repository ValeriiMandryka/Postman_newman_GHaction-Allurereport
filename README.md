# Postman + newman + github actions (Simple store template)


2. Download this repo.`git clone https://github.com/ValeriiMandryka/Postman_newman_GHaction-HTML-reoport.git`
3. Run `npm i` (install node.js dependencies)
4. Run `npm install -g newman`
5. To run testing server locally run first this command into GitBash or CMD line `npm run tern-on-api`
6. Then run `newman run store.postman_collection.json` into your IDE (for example - VSC)

### Local server testing
 Below is a table of supported operations with `products` as example resource. The same operations are also supports for `orders/` and `users/`.

| VERB     |Route          | Input      | Output             |
|----------|---------------|------------|--------------------|
| GET      | /products     | *None*     | **Array**          |
| GET      | /products/:id |  **e.g 3** | **Object**         |
| POST     | /products     | **object** | **Created object** |
| PUT      | /products     | **object** | **Updated object** |
| DELETE   | /products/:id | **e.g 3**  | **Deleted object** |

