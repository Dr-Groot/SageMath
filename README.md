# Welcome to Sage Math for Graph Theory.

---
> Follow us on [Instagram](https://www.instagram.com/datascience.drgroot/) || 
> Follow us on [Twitter](https://twitter.com/DrGroot7) || 
> Follow us on [GitHub](https://github.com/Dr-Groot)

![image](https://user-images.githubusercontent.com/63160825/134688378-2bbf2822-38a2-4959-aa58-ef09630aea13.png)

<br />

## Installation

For MacOS and Window go with [Download SageMath](https://www.sagemath.org/download.html) to Download the Software, its open source so no trouble in downloading.

After **SageMath** is installed, see that you have **Jupyter Notebook** if not go with link to download [CLICK HERE](https://test-jupyter.readthedocs.io/en/latest/install.html).

<br />

We will be using **Jupyter Notebook** as our primary workspace, So lets get Start now.

<br />

---

## SageMath for Graph Theory

For making a complete graph we use **graphs.CompleteGraph()** as in arguement we can give the number of vertices or nodes.

 A Complete Graph is a graph in which all nodes are connected to all other nodes.

For Example:

Lets say we want to make a Complete Graph with 5 vertices then we will go with **graphs.CompleteGraph(5)** on our Jupyter Notebook.

![Screenshot 2021-09-24 at 7 53 47 PM](https://user-images.githubusercontent.com/63160825/134690696-44ace409-b013-4f96-81cc-27d8df47c7a9.png)

Lets define a variable K5 and store **graphs.CompleteGraph(5)** in it. And to display the K5 we use **K5.show()**

![Screenshot 2021-09-24 at 7 56 50 PM](https://user-images.githubusercontent.com/63160825/134691186-8331ed54-af11-47d3-8619-06bb58b1c956.png)

Lets make it more excited by building a **3D COMPLETE GRAPH** with 5 Vertice just going with **K5.show3d()**.

![Screenshot 2021-09-24 at 8 09 18 PM](https://user-images.githubusercontent.com/63160825/134693275-5e084a5f-3cac-4b5c-b60c-6c2e413aa8d5.png)

Amazing thing about 3d Graph is, you can Rotate it using your cursor or you can go with **spin = True** as an arguement of **show3d()**

> 3D Graphs feature is supported by Safari and Internet Explorer Web Browser and JDK should be installed.

<br />

**PETERSEN GRAPH**

The Petersen Graph is a named graph that consists of 10 vertices and 15 edges, usually drawn as a five-point star embedded in a pentagon.

The Petersen Graph is a common counterexample. For example, it is not Hamiltonian.

For this we have to go wtih **graphs.PetersenGraph()** and then **show()**

![Screenshot 2021-09-24 at 8 25 15 PM](https://user-images.githubusercontent.com/63160825/134695905-4b4454e0-a270-4889-b5b2-f8dcb9388475.png)

And For 3d we will go with same command **show3d()**

![Screenshot 2021-09-24 at 8 27 09 PM](https://user-images.githubusercontent.com/63160825/134696220-78620f6d-f42a-43d7-b8f8-fa0a6b43f263.png)

Basically 3D graphs are used for finding Isomorphism or comparing two graphs together.

<br />

**CUBE GRAPH**

Just go with **graphs.CubeGraph(n)**

Return the n-cube graph, also called the hypercube in n dimensions.

The hypercube in n dimension is build upon the binary strings on n bits, two of them being adjacent if they differ in exactly one bit.
Hence, the distance between two vertices in the hypercube is the Hamming distance.

![Screenshot 2021-09-24 at 8 41 02 PM](https://user-images.githubusercontent.com/63160825/134698392-b52d41b4-32c7-4a96-ae89-ffd6b6929c06.png)

## Want to know which command does what?

Its easy to find this just give **?** after each command to know about what it does.

Lets say whats **graphs.CompleteGraph()** do we just write **graphs.CompleteGraph?** and we get a pop up window like this -

![Screenshot 2021-09-24 at 8 44 27 PM](https://user-images.githubusercontent.com/63160825/134698878-6ab1eada-f6fc-47f6-b397-29b00714ea9b.png)

Following with the instructions how to use this following statement.





