# Hash Tables

### What are Hash Tables?

  > Hash Tables hold key value pairs by `Hashing` the key. This enables different pairs to be assigned an index. This important part of this is that the hash has to be extensive enough that every key that gets hashed doesn't end up with the same index.
  
 ### But what if two pairs have the same index?
 
  > That is ok because we can actually make each index extend into it's own hash table or maybe a linked list. However you dea with it you end up having "sub- indexes".
  
 ### What functionality does a Hash Table need?
 
  > add(): adds a pair to the table
  get(): finds the index of the pair being searched for
  contains(): returns boolean if the pair is in the table or not
  hash(): takes the key and hashes to define said pairs value

