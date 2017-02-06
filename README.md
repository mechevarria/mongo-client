# mongo-client

For the lazy, this is an implementation of the MongoDB client [quickstart](http://mongodb.github.io/node-mongodb-native/2.2/quick-start/)

## To get started

`npm install`

Edit `var url = 'mongodb://demo-vm:27017/test';` to point to the mongodb server you are testing.  Out of the box Mongo creates the `test` db

## To run

`node app.js`

The output should be
**Connected successfully to mongodb://demo-vm:27017/test**

## Problems?
If you are connecting to a remote server make sure the server is listening on all interfaces.  In `/etc/mongod.conf` comment out the ` bindIp` variable
