# MongoDB

## `mongo` Shell Quick Reference

- [document](https://docs.mongodb.com/manual/reference/mongo-shell/)

```js
show dbs
use <db>
show collections
show users
show databases
```

### Basci Shell

```js
db.colelction.find();
db.collection.updateMany();
```

## Add new field to every document in a MongoDB collection

- [db.collection.updateMany](https://docs.mongodb.com/manual/reference/method/db.collection.updateMany/)

```js
db.collections.updateMany({}, {$set, {"order":0}})
```

## Check if MongoDB shel has been installed

1. Login MongoDB Atlas
2. Select your collection
3. Click on `Cmd Line Tools tab`
4. Click on `Connect with the MongoDB Shell`
5. Run shell if you have installed MongoDB Shell

   ```js
   % mongosh --version
    1.2.2
   ```

## How to import data into MongoDB

## `mongoimport` command

**Example**

```js
mongoimport --db mongo-exercises --collection courses --drop --file exercise-data.json --jsonArray
```

**Syntax** -[mongoimport document](https://docs.mongodb.com/manual/reference/program/mongoimport/#cmdoption-mongoimport-jsonarray)

**Options**

> --db [database]

> --collection [collection]

> --file [filename]

> --drop

> --jsonArray
> Accepts the import of data expressed with multiple MongoDB documents within a single JSON array.
