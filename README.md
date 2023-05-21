# Close-Hashing
A hash table is a data structure that stores key-value pairs. In this implementation, Close Hashing is used, which means that when a collision occurs (i.e., when two keys are mapped to the same slot in the hash table), the keys are stored in the next available slot in the table.
The function Close_Hashing takes in an array of input_keys and the size of the hash table. The keys are then stored in the hash table using the hash function mod(key, M), where key is the input key and M is the size of the hash table.
If a collision occurs, the function will store the key in the next available slot in the table. The function returns the hash table after all the keys have been stored. Any unfilled values in the hash table are represented by -1.
