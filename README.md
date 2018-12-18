# MongoDB

## How to import data into MongoDB

## `mongoimport` command

**Example**
```js
mongoimport --db mongo-exercises --collection courses --drop --file exercise-data.json --jsonArray
```

**Syntax**
-[mongoimport document](https://docs.mongodb.com/manual/reference/program/mongoimport/#cmdoption-mongoimport-jsonarray)

**Options**
>--db [database] 
--collection [collection]
--file [filename]
--drop
--jsonArray 
>>Accepts the import of data expressed with multiple MongoDB documents within a single JSON array.


