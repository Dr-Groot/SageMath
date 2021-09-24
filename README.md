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

And for 3d Graph version we will go with **show.3d()** and we will get :
 
![Screenshot 2021-09-24 at 8 48 30 PM](https://user-images.githubusercontent.com/63160825/134699520-1c93f7ab-e063-4f9e-b404-4111f41e4a38.png)

> Cube Graph are use in CPU's now they gave small little CPU's as you can in those node and they are connected to each other and this mean of quad core dual core and so on. 


**EMPTY GRAPH**

Now lets create an empty graph wich means graph of 0 vertices, it is created by **Graph()** or by **graphs.EmptyGraph()**.

I can proove that both can create an Empty Graph by comparing them:

![Screenshot 2021-09-24 at 9 08 37 PM](https://user-images.githubusercontent.com/63160825/134702573-0bf83132-4b01-4785-ab6c-30c80d51e7d4.png)


**LETS PLAY WITH THE GRAPHS**

Now if i want to create a graph with 5 vertex, we just go with **Graph(5)** :

![Screenshot 2021-09-24 at 9 12 41 PM](https://user-images.githubusercontent.com/63160825/134703235-6dd2f3d3-75f4-4c61-bb25-ef9f65ae56b8.png)

We can add vertex to the **Graph G** by **g.add_vertex(6)** and then display **g** 

![Screenshot 2021-09-24 at 9 17 00 PM](https://user-images.githubusercontent.com/63160825/134703831-526eb967-b20c-4f5f-8d70-62873909c797.png)

Something is like missing out, Edges Right!

So if we want to add edge between vertex 0 and 1 then we will go with **g.add_edge(0, 1)**

![Screenshot 2021-09-24 at 9 19 33 PM](https://user-images.githubusercontent.com/63160825/134704195-21b20d15-bfc0-43f2-8f4a-c95107a8a9cc.png)

And So on we can go with this command to add edges.

Now lets display the vertex and edges by :

![Screenshot 2021-09-24 at 9 26 50 PM](https://user-images.githubusercontent.com/63160825/134705185-225d2503-4963-46e0-9f37-90b7e7e3558b.png)

It is showing 0 and 1 edges that i have created now.

We can add multiple Edges by :

![Screenshot 2021-09-24 at 9 32 26 PM](https://user-images.githubusercontent.com/63160825/134706003-f3a01754-44b9-4555-9c7d-72005ccd4369.png)

Now lets look over to the Total Edges we have:

![Screenshot 2021-09-24 at 9 34 08 PM](https://user-images.githubusercontent.com/63160825/134706223-e6989487-3b21-4814-ac37-54c9e4da098d.png)

if i want a Graph with 0 vertex connected to 1,2,3,4,5,6 and 7 
Then:

![Screenshot 2021-09-24 at 9 49 02 PM](https://user-images.githubusercontent.com/63160825/134708167-373c25cf-1bd3-431e-ad90-74da107d6840.png)

Want a Graph with vertex 0 connected to 1, 2 and 1 to 2,3 and 2 to 3
So then:

![Screenshot 2021-09-24 at 9 51 48 PM](https://user-images.githubusercontent.com/63160825/134708477-a6c8495f-662c-4b7e-8ea7-f0042a3908f2.png)

Giving each edge a name, we have to write like:

**G = Graph({0:{1:'x',2:'z', 3:'a'}, 2:{5:'out'}})** and with that we have to specfy **G.show(edge_label=True)** to ensure labels are visible.

![Screenshot 2021-09-24 at 10 06 45 PM](https://user-images.githubusercontent.com/63160825/134710382-bebfb057-b704-4c55-aa8c-073e4f4b26e3.png)

If we want to change the edge name between 0 to 2  as **changed** we can do like this:

**G.add_edge(0,2, label='changed')** and **G.show(edge_label=True)**

![Screenshot 2021-09-24 at 10 13 08 PM](https://user-images.githubusercontent.com/63160825/134711169-ec44e779-29eb-4d60-ad08-17fbe1e83329.png)


## Want to know which command does what?

Its easy to find this just give **?** after each command to know about what it does.

Lets say whats **graphs.CompleteGraph()** do we just write **graphs.CompleteGraph?** and we get a pop up window like this -

![Screenshot 2021-09-24 at 8 44 27 PM](https://user-images.githubusercontent.com/63160825/134698878-6ab1eada-f6fc-47f6-b397-29b00714ea9b.png)

Following with the instructions how to use this following statement.





