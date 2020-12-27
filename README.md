# FileBasedKeyValueDataStore
#Implemented using Python
#It supports all the crud operations
#File Size not exceed 1GB
This is a Python module that provides an interface, the `KeyValueDatabaseInterface()` class, for a simple Key-Value 
Database.  If such a database does not exists, it creates ones using [SQLAlchemy](https://www.sqlalchemy.org/). 
The interface has several CRUD methods so that it can interface with the database.

#Supporting Methods

1- get_all() : A method that returns all the Key-Value pairs in the database
2- get_multiple(keys): Returns a list of entries associated with the provided keys.
3- get(key): Returns the entry associated with the key.
4- KeyValueDatabaseInterface(): An interface class for a simple Key-Value Relational Database. Has several different
CRUD methods
5-insert(self, key, value): Insert a single entry into the database
6- insert_multiple(kv_values): Insert multiple Key-Value entries.
7-remove(keys): Remove the entries associate with the keys provided.
8-update(key, value): Updates the entry associated with the key with the value provided.
