# Hazelcast 3.X.X MapStore MongoDB Sample

This is an example of how to use `MapStore` and `MongoDB`.

Required properties:

- `uri` - Mongo connection string. See more here: https://docs.mongodb.com/manual/reference/connection-string/
- `database` - The database

## Classes

- [Person](src/main/java/sample/com/hazelcast/cloud/mapstore3/mongo/Person.java) Entity class
- [MognoPersonRepository](src/main/java/sample/com/hazelcast/cloud/mapstore3/mongo/MongoPersonRepository.java)
  MongoDB implementation for Person Entity.
- [PersonMapStore](src/main/java/sample/com/hazelcast/cloud/mapstore3/mongo/MongoPersonMapStore.java) MapStore
  implementation for Person Entity.
- [PersonMapStoreTest](src/test/java/sample/com/hazelcast/cloud/mapstore3/mongo/MongoPersonMapStoreTest.java)
  Person MapStore tests.

