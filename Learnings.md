## 06/2026
At the beggining of this month i participated in the "Rinha de Backend 2026" challenge. I chose Golang for acomplishing it, as i have been 
desiring to learn this language for some time and i judge it to have a great balance between performance/development-speed.

Initial learnings in the challenge:
- Vectorial Searching
- Creating an API using fasthttp in Golang

Some other Learnings:
- How to build an IVF index for querying the vectors in an optmized way
- How to do quantization of vectors so less memory is used for storing and managing the index
- K-means++ initialization of IVF index centroids
- Converting clusters to an IVF index struct that stores a header(makes sure the right file is being read) and writes the struct into a binary file
