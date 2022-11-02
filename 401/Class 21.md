## Hash Table

The Hash Table is a data structure that maps keys to values, that allows you to retrieve a value via a key.

The code below represents a simple implementation of Hash Table in JavaScript:

```
var simplehash = new Object();
// or
// var simplehash = {};

simplehash['key1'] = 'value1';
simplehash['key2'] = 'value2';
simplehash['key3'] = 'value3';

for (var key in simplehash) {
  // use hasOwnProperty() to filter out properties from Object.prototype
  if (simplehash.hasOwnProperty(key)) {
    console.log('key is: ' + key + ', value is: ' + simplehash[key]);
  }
} 
````
An object contains the hash table in which the data is stored. It holds all the “key-value” pairs of the hash table. Also, its size should be determined by the size of expected data. In Hash Tables, there are different techniques used in open addressing are such as

1. Linear Probing
2. Quadratic Probing
3. Double hashing

These techniques are used to resolve collision. 

There is something called Hash Fucntion, which is defined for a hash table to find out the “index” of the given key-value pair. This function accepts a “key” as an input and then assigns a specific “index” and sets that as the return case. There is also another thing called 'Good Function'. A good hash function may not prevent the collisions completely however it can reduce the number of collisions like Division Method.  
