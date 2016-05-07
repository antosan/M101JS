# M101JS
MongoDB for Node.js Developers Course

Get the MongoMart application up and running.

1. Clone the repo.

2. Install the dependencies: `npm install`

3. Make sure you have a mongod running version 3.2.x of MongoDB.

4. Import the "item" collection: `mongoimport -d mongomart -c item data/items.json`

5. Import the "cart" collection: `mongoimport -d mongomart -c cart data/cart.json`

6. Run the application by typing `node mongomart.js` in the mongomart directory.

7. In your browser, visit [http://localhost:3000](http://localhost:3000)
