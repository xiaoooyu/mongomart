This is the final exam project of MongoDB for NodeJS developer at Mongo University.

Get the MongoMart application up and running. It doesn't do much (yet), but you should be able to run it and experiment with the UI.

1. Install the dependencies.
2. Make sure you have a mongod running version 3.2.x of MongoDB.
3. Import the "item" collection: mongoimport --drop -d mongomart -c item data/items.json
4. Import the "cart" collection: mongoimport --drop -d mongomart -c cart data/cart.json
5. Run the application by typing "node mongomart.js" in the mongomart directory.