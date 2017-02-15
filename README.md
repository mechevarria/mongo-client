# mongo-client

This is an implementation of the MongoDB client [quickstart](http://mongodb.github.io/node-mongodb-native/2.2/quick-start/quick-start/)

The `insert .js` script takes the included json document which contains an array of [GeoJSON](http://geojson.org/geojson-spec.html) features for US states and then inserts into a Mongo Collection

## To get started

`npm install`

Edit `config.json` to point to change the url, document and collection if needed.  Out of the box Mongo creates the `test` db

## To run

`node insert.js`

## To Undo

`node clean.js`