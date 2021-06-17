# hash table
 hash table is a data structure that implements an associative array abstract data type, a structure that can map keys to values. Usually used for security and encryption


hash table is fast because keys are assigned values ​​using A hash , hash is the ability to encode the key that will eventually map to a specific location in the data structure 

Effectiveness  of the hash table :
O(1) time
O(1) space

collision
A collision occurs when more than one key hashes to the same index in an array

Example :
```
SUM HASHED: Pioneer Square = 1379
SUM HASHED: Alki Beach = 884
SUM HASHED: U District = 955

BUCKET SIZE=99
SUM INDEX: 1379 % 99 = 92
SUM INDEX:  884 % 99 = 92
SUM INDEX:  995 % 99 = 64
```

Bucket Sizes : 
As the number of Buckets increases, the density will be densely full

Internal Methods of hash table :
Add() : used to add a new key/value pair to a hashtable
Find() :used to search for the hash using a key
Contains() : Check for hash in the table or not
GetHash() : The GetHash will accept a key as a string, conduct the hash

