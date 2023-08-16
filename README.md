# enumeration-of-complete-subgraphs

Finding number of complete subgraph of size k of a graph efficiently using GPU.
Instructions on how to compile and execute the code on the inputs:

1. Go in the folder in which code and inputs are present.
	ex. cd/drive/GPU_CP

2. Compile the code using below given command
     !nvcc main.cu

3. Suppose we want to execute on input1.txt, write the below command
    !./a.out ./input1.txt

Now, we have to enter the value of k (where k is the size of clique) 

Output:- It will the number of possible complete subgraph(i.e. clique) of size k in the given graph with execution time.
