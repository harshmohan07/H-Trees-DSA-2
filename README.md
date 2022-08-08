# Implementation of H Tree and Lookup Optimisations in the Implementation.

## H Tree is a data structure deviced for fast path-retrivels in rooted trees. 
## Implemented the H Tree having look up ratio of standard <a href="https://corpus.canterbury.ac.nz/descriptions/#cantrbry">data set</a> matching with the ones published in the <a href="https://github.com/harshmohan07/H-Trees-DSA-2/blob/main/Lookup%20Optimisations%20of%20H-Tree.pdf">research paper</a> releated to its implementation.
## Also optimised the lookup operation in the implementation by balancing the Huffman Tree formed while encoding a given file.


### Working of Algorithm :

1. Initially makes the Hash Map of characters in the file to be encoded mapped with their frequencies.
2. Creates a balanced Huffman tree from the frequencies and encodes the file. Also creates a H Tree.
3. Decodes the file using H Tree. 

### To run this project

`Clone the repository`

```
#Build the project
make main_encode_unbalanced.c

#Run the program with the file to be encoded
Run ./a.out filename
```
