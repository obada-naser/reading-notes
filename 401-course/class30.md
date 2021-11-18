# Hash Tables


we have something in java called key/value pairs libraries and they provide a faster storing and writing in them here in hash tables we have the same concept hashing means we can generate A key and be able to look for the key using it's value with Big O(1) time complexity. This same idea was provided by the arrays where it can search for the value and gets the key but however the array can't provide the same time complexity as the hash tables as it needs to search every index and gets the value from it and that takes Big O(n) time complexity.

## producing Hash tables

when we have a key and value strings for example and we need to save them in the array we can use some calculations and produce an index that can be mapped to it. the index here is a part of an array and we can call it as a buckets that can stores in it a pair key/values. And if nothing in the bucket it can be empty.

if we have a key/value who has a specific index and we needed to store on it another key/value pair we will then have a collision and that could lead to losing the data so there are many ways that solved this problem one of them is by using the linked list and making the bucket it self contain more than one index of keys and values and this also can be called as chaining.

## Size for buckets

There are problem to choose the size of the hash map as if we had a few number of buckets we will have many collisions that will occur and on the other side we can't many buckets as it will leave more empty spaces and either way we will always have have a collision because the collision depends on the number of the index.


## Methods in hash tables

to interact with a hash table there are a multiple methods that can be used such as:

1. Add: this one is used to add a new key/value pair to which index.

2. Find: this one takes the key or value and search for it without using any loops or iteration.
3. contains: used to also search for a pair but it returns boolean.

4. GetHash: it returns the index of the pair where can be added by using the hash.

## more information

1. The hashing is done using a hash function. 
2. The most neat hashing is to have an good hash function and by having easy to calculate algorithm, good distribution, and as we said the lowest collisions.


