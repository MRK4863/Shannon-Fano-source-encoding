# Shannon-Fano-source-encoding
## THEORY:
 
 Shannon Fano Algorithm is an entropy encoding technique for lossless data compression of multimedia. Named after Claude Shannon and Robert Fano, it assigns a code to each symbol based on their probabilities of occurrence. It is a variable length encoding scheme, that is, the codes assigned to the symbols will be of varying length.
Data Compression, also known as source coding, is the process of encoding or converting data in such a way that it consumes less memory space. Data compression reduces the number of resources required to store and transmit data.


## ALGORITHM:

The steps of the algorithm are as follows:
1. Create an array of probabilities for the given set of symbols and assign to the root node.
2. Sort the list of symbols in decreasing order of probability.
3. Split the list into two sub-array, with the total probability of both the parts being as close to each other as possible.
4. Assign the code “0” to the left sub-array and “1” to the right sub-array.
5. Repeat the steps 3 and 4 for each part, until all the symbols are split into individual sub-arrays.
