# Easy-Addition
ou are given a tree with N nodes and each has a value associated with it. You are given Q queries, each of which is either an update or a retrieval operation.

Initially all node values are zero.

The update query is of the format

a1 d1 a2 d2 A B
The retrieval query is of the format

i j
You need to return the sum of the node values lying in the path from node i to node j modulo 1000000007.

Note:

First all update queries are given and then all retrieval queries.
Distance between 2 nodes is the shortest path length between them taking each edge weight as 1.
Input Format

The first line contains two integers (N and R respectively) separated by a space.

In the next N-1 lines, the ith line describes the ith edge: a line with two integers x y separated by a single space denotes an edge between nodes x and y.

The next line contains 2 space separated integers (U and Q respectively) representing the number of Update and Query operations to follow.

U lines follow. Each of the next U lines contains 6 space separated integers (a1,d1,a2,d2,A and B respectively).

Each of the next Q lines contains 2 space separated integers, i and j respectively.

Output Format

It contains exactly Q lines and each line containing the answer of the ith query.

Constraints

2 <= N <= 105
2 <= R <= 109
1 <= U <= 105
1 <= Q <= 105
1 <= a1,a2,d1,d2 <= 108
1 <= x, y, i, j, A, B <= N
