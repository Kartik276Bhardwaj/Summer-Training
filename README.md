# Summer-Training



SIX WEEKS SUMMER TRAINING REPORT 
ON
DATA STRUCTURES AND ALGORITHIMS

NAME: KARTIK BHARDWAJ
Registration No: 12105309
Program Name: BTECH  (CSE)


Under the Guidance of
AKSHAY MITTAL
ORGANIZATION:  BOARD INFINITY

School of Computer Science & Engineering
Lovely Professional University, Phagwara
06 June – 17 July 2023
DECLARATION

I hereby declare that I have completed my six weeks summer training at Board Infinity from 6th June 2023 to 17th July 2023 under the guidance of AKSHAY MITTAL. I declare that I have worked with full dedication during these six weeks of training and my learning outcomes fulfil the requirements of training for the award of degree of B.Tech.(Computer Science & Engineering) at Lovely Professional University, Phagwara.


     KARTIK BHARDWAJ
Registration No: 12105309

Date: 25-08-2023















ACKNOWLEDGEMENT

I would like to acknowledge Mr Akshay Mittal, the mentor of our Training. He has been instrumental in guiding and helping us while undergoing the planning phase of our project and helped clear the concepts related to the topics and project. Because the Training and Placement Cell of School of Computer Science & Engineering has allowed me to do the summer training, I would like to thank for the same. I would like to thank Boards Infinity also for organizing such a wonderful summer training program.

Later, I would like to confer the flower of acknowledgment to our parents because of whom we got the existence in the world for the inception and the conception of this training and project. Rest all those people who helped us are not only a matter of acknowledgment but also authorized to share our success.















CERTIFICATE















TABLE OF CONTENTS
 


1.	Introduction
2.	Technology Learnt
2.1	 Data Structures
2.2	 Asymptotic Analysis
2.3	 Arrays
2.4	 Linked List 
2.5	 Stack and Queue 
2.6	 Binary Trees
2.7	 Heap 
2.8	 Graphs 
3.	Reason for choosing this technology Profile of the Problem
4.	Problem Analysis
5.	Software Requirement Analysis
6.	Implementation
7.	Screenshots 
8.	Learning Outcome from training
9.	Gantt Chart
10.	References

 

1.	Introduction
In the world of computers, understanding Data Structures and Algorithms (like building blocks and problem-solving methods) is really important. This report is all about my experience as a participant in the Board Infinity Summer Training Program that focused on teaching these important concepts.
For a certain period of time, I got to learn a lot about Data Structures and Algorithms. This report explains what I learned, how the teaching was done, and what I gained from it.
I talk about how the training was planned, how I went from knowing little to understanding a lot about these concepts. The trainers used smart ways to help us understand difficult ideas and put them into practice.
I also share about the challenges I faced while doing practical coding exercises and how I managed to find solutions. These challenges helped me get better at solving problems and thinking in a smarter way.
Throughout this summer training program, I had the privilege of being mentored by experts in the field who guided me through the intricacies of data structures and algorithms. From mastering fundamental concepts to exploring advanced techniques, the program has provided a comprehensive journey, deepening my understanding of how algorithms power the digital world we inhabit.
Additionally, I look at how the training changed me. I talk about what new skills I acquired and how my way of thinking about problems got better. I even include interviews and thoughts from both trainers and other participants to show how the training worked for all of us.
To sum it up, this report is like a diary of my adventure with Data Structures and Algorithms during the Board Infinity Summer Training Program. As you read through it, you'll get a clear picture of what I learned, how I grew, and why learning about these computer concepts is so valuable.
2. Technology Learnt

During the 6-week online summer training “Solving Competitive Problems using Data Structures”, I have learnt basics of Data Structures and applied those concepts in solving some standard competitive coding problems using C++. The brief outlines of the contents covered is as following:
Data Structures:
Data Structure is a systematic way to organize data in order to use it efficiently. Following terms are the foundation terms of a data structure.
•	Interface − Each data structure has an interface. Interface represents the set of operations that a data structure supports. An interface only provides the list of supported operations, type of parameters they can accept and return type of these operations.
•	Implementation − Implementation provides the internal representation of a data structure. Implementation also provides the definition of the algorithms used in the operations of the data structure.
Algorithm is a step-by-step procedure, which defines a set of instructions to be executed in a certain order to get the desired output. Algorithms are generally created independent of underlying languages, i.e, an algorithm can be implemented in more than one programming language.
From the data structure point of view, following are some important categories of algorithms: 
•	Search − Algorithm to search an item in a data structure.
•	Sort − Algorithm to sort items in a certain order.
•	Insert − Algorithm to insert item in a data structure.
•	Update − Algorithm to update an existing item in a data structure.
•	Delete − Algorithm to delete an existing item from a data structure.
Time Complexity
Time complexity of an algorithm represents the amount of time required by the algorithm to run to completion. Time requirements can be defined as a numerical function T(n), where T(n) can be measured as the number of steps, provided each step consumes constant time.
For example, addition of two n-bit integers takes n steps. Consequently, the total computational time is T(n) = c ∗ n, where c is the time taken for the addition of two bits. Here, we observe that T(n) grows linearly as the input size increases.
Classification of Data Structures

 
Figure 2.1: Classification of Data Structures

Asymptotic Analysis
Asymptotic analysis refers to computing the running time of any operation in mathematical units of computation. For example, the running time of one operation is computed as f(n) and may be for another operation it is computed as g(n2). This means the first operation running time will increase linearly with the increase in n and the running time of the second operation will increase exponentially when n increases. Similarly, the running time of both operations will be nearly the same if n is significantly small.
Usually, the time required by an algorithm falls under three types −
•	Best Case − Minimum time required for program execution.
•	Average Case − Average time required for program execution.
•	Worst Case − Maximum time required for program execution.
Asymptotic Notations
Following are the commonly used asymptotic notations to calculate the running time complexity of an algorithm.
•	Ο − Big Oh Notation
•	Ω − Big Omega Notation
•	Θ − Theta Notation
Big Oh Notation, Ο
The notation Ο(n) is the formal way to express the upper bound of an algorithm's running time. It measures the worst case time complexity or the longest amount of time an algorithm can possibly take to complete.

For example, for a function f(n)
Ο(f(n)) = { g(n) : there exists c > 0 and n0 such that g(n) ≤ c.f(n) for all n > n0. }
Example
Let us consider a given function, f(n) = 4.n3+10.n2+5.n+1.
Considering g(n) = n3
    f(n) ≥ 5.g(n) for all the values of n > 2.
Hence, the complexity of f(n) can be represented as O (g (n) ) ,i.e. O (n3).
Big Omega Notation, Ω
The notation Ω(n) is the formal way to express the lower bound of an algorithm's running time. It measures the best case time complexity or the best amount of time an algorithm can possibly take to complete.

For example, for a function f(n)
Ω(f(n)) ≥ { g(n) : there exists c > 0 and n0 such that g(n) ≤ c.f(n) for all n > n0. }
Example
Let us consider a given function, f(n) = 4.n3+10.n2+5.n+1
Considering g(n) = n3 , f(n) ≥ 4.g(n) for all the values of n > 0.
Hence, the complexity of f(n) can be represented as Ω (g (n) ) ,i.e. Ω (n3).
Theta Notation, θ
The notation θ(n) is the formal way to express both the lower bound and the upper bound of an algorithm's running time. Some may confuse the theta notation as the average case time complexity; while big theta notation could be almost accurately used to describe the average case, other notations could be used as well. It is represented as follows −
 
θ(f(n)) = { g(n) if and only if g(n) = Ο(f(n)) and g(n) = Ω(f(n)) for all n > n0. }
Example
Let us consider a given function, f(n) = 4.n3+10.n2+5.n+1
Considering g(n) = n3 , 4.g(n)≤ f(n)≤ 5.g(n) for all the values of n.
Hence, the complexity of f(n) can be represented as Ɵ (g (n) ) ,i.e. Ɵ (n3).

Arrays
Array is a type of linear data structure that is defined as a collection of elements with same or different data types. They exist in both single dimension and multiple dimensions. These data structures come into picture when there is a necessity to store multiple elements of similar nature together at one place.
 
Figure 2.5 Array Representation


Applications of Array Data Structures:
a)	Storing and accessing data: Arrays are used to store and retrieve data in a specific order. For example, an array can be used to store the scores of a group of students, or the temperatures recorded by a weather station.
b)	Sorting: Arrays can be used to sort data in ascending or descending order. Sorting algorithms such as bubble sort, merge sort, and quicksort rely heavily on arrays.
c)	Searching: Arrays can be searched for specific elements using algorithms such as linear search and binary search.
d)	Matrices: Arrays are used to represent matrices in mathematical computations such as matrix multiplication, linear algebra, and image processing.
e)	Stacks and queues: Arrays are used as the underlying data structure for implementing stacks and queues, which are commonly used in algorithms and data structures.
f)	Dynamic programming: Dynamic programming algorithms often use arrays to store intermediate results of subproblems in order to solve a larger problem.

Basic Operations in the Arrays
The basic operations in the Arrays are insertion, deletion, searching, display, traverse, and update. These operations are usually performed to either modify the data in the array or to report the status of the array.
Following are the basic operations supported by an array.
•	Traverse − print all the array elements one by one.
•	Insertion − Adds an element at the given index.
•	Deletion − Deletes an element at the given index.
•	Search − Searches an element using the given index or by the value.
•	Update − Updates an element at the given index.
•	Display − Displays the contents of the array.

Insertion Operation
In the insertion operation, we are adding one or more elements to the array. Based on the requirement, a new element can be added at the beginning, end, or any given index of array. This is done using input statements of the programming languages.
#include <stdio.h>
int main(){
int LA[3], i;
printf("Array Before Insertion:\n");
for(i = 0; i < 3; i++)
printf("LA[%d] = %d \n", i, LA[i]);
printf("Inserting Elements.. ");
printf("The array elements after insertion :\n"); // prints array values
for(i = 0; i < 3; i++) {
LA[i] = i + 2;
printf("LA[%d] = %d \n", i, LA[i]);
}
return 0;
}
Deletion Operation
In this array operation, we delete an element from the particular index of an array. This deletion operation takes place as we assign the value in the consequent index to the current index.
#include <stdio.h>
void main(){
   int LA[] = {1,3,5};
   int n = 3;
   int i;
   printf("The original array elements are :\n");
   for(i = 0; i<n; i++)
      printf("LA[%d] = %d \n", i, LA[i]);
   for(i = 1; i<n; i++) {
      LA[i] = LA[i+1];
      n = n – 1;
   }
   printf("The array elements after deletion :\n");
   for(i = 0; i<n-1; i++)
      printf("LA[%d] = %d \n", i, LA[i]);
}
Search Operation
Searching an element in the array using a key; The key element sequentially compares every value in the array to check if the key is present in the array or not.
#include <iostream>
using namespace std;
int main(){
   int LA[] = {1,3,5,7,8};
   int item = 5, n = 5;
   int i = 0;
   cout << "The original array elements are : " <<endl;
   for(i = 0; i<n; i++) {
      cout << "LA[" << i << "] = " << LA[i] << endl;
   }
   for(i = 0; i<n; i++) {
      if( LA[i] == item ) {
         cout << "Found element " << item << " at position " << i+1 <<endl;
      }
   }
   return 0;
}

Table: Comparison of Complexities of different Searching Algorithms
Searching Algorithm	Best Case	Average Case	Worst Case
Linear Search	1	n	n
Binary Search	1	log n	log n

Table: Comparison of Complexities of different Sorting Algorithms
Sorting Algorithm	Best Case	Average Case	Worst Case
Bubble Sort	n2	n2	n2
Selection Sort	n2	n2	n2
Insertion Sort	n	n2	n2
Quick Sort	n log2 n	n log2 n	n2
Merge Sort	n log2 n	n log2 n	n log2 n

 
Linked List
A linked list is a collection of “nodes” connected together via links. These nodes consist of the data to be stored and a pointer to the address of the next node within the linked list. In the case of arrays, the size is limited to the definition, but in linked lists, there is no defined size. Any amount of data can be stored in it and can be deleted from it.
 
Figure 2.6 Representation of Singly Linked List
•	When should you use Linked List over Array
	When you do not know the total number of elements to be processed, this is because, in the array, we must predefine the size and length of an array, which should be followed during the whole code unless changed at the root (where declaration takes place).
	When elements could increase or decrease during run time.
	When the probability of insertion and deletion at the end or in the beginning position is more, just like in the implementation of stack and queue, a linked List is always preferred over the array. As we have discussed earlier, we must push the elements to add a new element in the array.

Types of Linked List
	Singly Linked List: It is a very simple type of Linked List with a linear structure with a data section and a next section.
 
	Doubly Linked List: Doubly linked list contains one extra part than the singly linked list, that is, the previous section along with data and the next.
 
	Circular Linked List: Circular linked List is a linked list that does not have any predefined starting and end. You can start from any node. We can say that a circular linked List is a singly linked list in which the next of the last node is pointing to the first node or head.
 
	Circular Doubly Linked List: It is a combination of a circular linked List and a doubly linked List.
 
Basic Operations in the Linked Lists
Insertion at Beginning
In this operation, we are adding an element at the beginning of the list.
void insertatbegin(int data){
   //create a link
   struct node *lk = (struct node*) malloc(sizeof(struct node));
   lk->data = data;
   
   // point it to old first node
   lk->next = head;
   
   //point first to new first node
   head = lk;
}
Insertion at Ending
In this operation, we are adding an element at the ending of the list.
void insertatend(int data){

   //create a link
   struct node *lk = (struct node*) malloc(sizeof(struct node));
   lk->data = data;
   struct node *linkedlist = head;

   // point it to old first node
   while(linkedlist->next != NULL)
      linkedlist = linkedlist->next;

   //point first to new first node
   linkedlist->next = lk;
}
Deletion at Beginning
In this deletion operation of the linked, we are deleting an element from the beginning of the list. For this, we point the head to the second node.
void deleteatbegin(){
   if(!head) return;
   head = head->next;
}
Deletion at Ending
In this deletion operation of the linked, we are deleting an element from the ending of the list.
void deleteatend(){
   struct node *linkedlist = head;
   while (linkedlist->next->next != NULL)
      linkedlist = linkedlist->next;
   linkedlist->next = NULL;
}
Search Operation
Searching for an element in the list using a key element. This operation is done in the same way as array search; comparing every element in the list with the key element given.
int searchlist(int key){
   struct node *temp = head;
   while(temp != NULL) {
      if (temp->data == key) {
         return 1;
      }
      temp=temp->next;
   }
   return 0;
}
  Stack and Queue
Stack: A stack is an Abstract Data Type (ADT), that is popularly used in most programming languages. It is named stack because it has the similar operations as the real-world stacks, for example – a pack of cards or a pile of plates, etc.
 
Queue: Queue, like Stack, is also an abstract data structure. The thing that makes queue different from stack is that a queue is open at both its ends. Hence, it follows FIFO (First-In-First-Out) structure, i.e, the data item inserted first will also be accessed first. The data is inserted into the queue through one end and deleted from it using the other end. 
Implementation of Stack using Array
class Stack {
    int stack[100], n=100, top=-1;
    	    public:
    		void push(int val) {
        		if(top>=n-1)
        			cout<<"Stack Overflow"<<endl;
        		else {
            			top++;
            			stack[top]=val;
        		}
    		}
    		int pop() {
        		if(top<=-1)
            			return -1;
        		int temp=stack[top];
        		top--;
        		return temp;
    		}
    		int top() {
        		if(top==-1){
            			return -1;
        		}
            		return stack[top];
    		}
     };

Implementation of Queue using Array
class Queue {
    int cqueue[5];
    int front = -1, rear = -1, n=5;
    public:
        void insertCQ(int val) {
            if ((front == 0 && rear == n-1) || (front == rear+1)) {
                cout<<"Queue Overflow \n";
                return;
            }
            if (front == -1) {
                front = 0; rear = 0;
            } else {
                if (rear == n - 1) rear = 0;
                else rear = rear + 1;
            }
            cqueue[rear] = val ;
        }
        int deleteCQ() {
            if (front == -1) {
                return -1;
            }
            int temp=cqueue[front];
            if (front == rear) {
                front = -1; rear = -1;
            } else {
                if (front == n - 1)
                	front = 0;
                else
                	front = front + 1;
            }
            return temp;
        }
        int front(){
            if(front==-1){
                return -1;
            }
            return cqueue[front];
        }
};
Implementing Queue using Stack
struct Queue {
    stack<int> s1, s2; 

    void enQueue(int x){
        while (!s1.empty()) {
            s2.push(s1.top()); s1.pop();
        }
        s1.push(x);
        while (!s2.empty()) {
            s1.push(s2.top());   s2.pop();
        }
    }

    int deQueue(){
        if (s1.empty()) {
            return -1;
        }
        int x = s1.top(); s1.pop();
        return x;
    }
};
Binary Trees
The Binary tree means that the node can have maximum two children. Here, binary name itself suggests that 'two'; therefore, each node can have either 0, 1 or 2 children.
 
Figure: Binary Tree
Tree Terminology
	Root: In a tree data structure, the first node is called as Root Node.
	Child: In a tree data structure, the node which is descendant of any node is called as Child Node.
	Parent: In a tree data structure, the node which is a predecessor of any node is called as Parent Node.
	Siblings: In a tree data structure, nodes which belong to same Parent are called as Sibling.
	Leaf: In a tree data structure, the node which does not have a child is called as LEAF Node.
	Internal Nodes: In a tree data structure, the node which has at least one child is called as Internal Node.
•	Degree: In a tree data structure, the total number of children of a node is called as Degree of that Node. Maximum degree in a binary tree is two.
	Height: In a tree data structure, the total number of edges from leaf node to a particular node in the longest path is called as HEIGHT of that Node
	Depth: In a tree data structure, the total number of edges from root node to a particular node is called as Depth of that Node. 
	Level: In a tree data structure, the root node is said to be at Level 0 and the children of root node are at Level 1 and the children of the nodes which are at Level 1 will be at Level 2 and so on...
	Sub Tree: In a tree data structure, each child from a node forms a subtree recursively. Every child node will form a subtree on its parent node.
 
Traversals in a Binary Tree
There are mainly three types of Traversals of a Binary Tree:
i.	In order Traversal 
void printInorder(struct Node* node){
    if (node == NULL)
        return;
    printInorder(node->left);
    cout << node->data << " ";
    printInorder(node->right);
}
ii.	Preorder Traversal
void printPreorder(struct Node* node){
    if (node == NULL)
        return;
    cout << node->data << " ";
    printPreorder(node->left);
    printPreorder(node->right);
}

iii.	Post order Traversal
void printPostorder(struct Node* node){
    if (node == NULL)
        return;
    printPostorder(node->left);
    printPostorder(node->right);
    cout << node->data << " ";
}
 
Figure: Binary Tree
Different Types of Traversals on the Binary Tree mentioned above:
	Inorder: H, D, I, B, J, L, E, A, F, C, K, G
	Preorder: A, B, D, H, I, E, J, L, C, F, G, K
	Postorder: H, I, D, L, J, E, B, F, K, G, C, A
	Level Order: A, B, C, D, E, F, G, H, I, J, K, L
Heap
Heap is a special case of balanced binary tree data structure where the root-node key is compared with its children and arranged accordingly. There are mainly two types of heaps:
	Max Heap: In a Max-Heap, the greatest element is located at the root of the tree in the max heap such that it is easier to pick the largest element when heap pop is performed.
 
Figure: Max Heap
	Min Heap: In a Min-Heap, the smallest element is located at the root of the tree in the min heap such that it is easier to pick the smallest element when heap pop is performed.
 
Figure: Min Heap
Building Heap from Array
Heapify is an algorithm used to re-arrange the heap if the root node violates the heap property (child subtrees must be heaps!). Build Heap is a function to create a heap from a given array.
void heapify(int arr[], int N, int i){
    int largest = I;
    int l = 2 * i + 1, r = 2 * i + 2;
    if (l < N && arr[l] > arr[largest])
        largest = l;
    if (r < N && arr[r] > arr[largest])
        largest = r;
    if (largest != i) {
        swap(arr[i], arr[largest]);
        heapify(arr, N, largest);
    }
}
void buildHeap(int arr[], int N) {
    int startIdx = (N / 2) - 1;
    for (int i = startIdx; i >= 0; i--) {
        heapify(arr, N, i);
    }
    } 
Deletion in a Heap 
Since deleting an element at any intermediary position in the heap can be costly, so we can simply replace the element to be deleted by the last element and delete the last element of the Heap.
void deleteRoot(int arr[], int& n){
        int lastElement = arr[n - 1];
        arr[0] = lastElement;
        n = n - 1;
        heapify(arr, n, 0);
}
  
Figure: Deletion in a Heap
Insertion in a Heap
Elements can be inserted to the heap following a similar approach as discussed above for deletion. The idea is to: First increase the heap size by 1, so that it can store the new element. Then, insert the new element at the end of the Heap. Then, this newly inserted element may distort the properties of Heap for its parents. So, in order to keep the properties of Heap, heapify this newly inserted element following a bottom-up approach.
void insertNode(int arr[], int& n, int Key){
    n = n + 1;
    arr[n - 1] = Key;
    heapify(arr, n, n - 1);
}
  


Graphs
A Graph is a non-linear data structure consisting of vertices and edges. The vertices are sometimes also referred to as nodes and the edges are lines or arcs that connect any two nodes in the graph. More formally a Graph is composed of a set of vertices(V) and a set of edges(E). The graph is denoted by G(E, V).
 
Figure: Graph Representation
Graph Traversals
A graph traversal finds the edges to be used in the search process without creating loops. This means that, with graph traversal, we can visit all the vertices of the graph without getting into a looping path. There are two graph traversal techniques:
a.	DFS (Depth First Search)
b.	BFS (Breadth First Search)
Depth-first search is an algorithm for traversing or searching tree or graph data structures. The algorithm starts at the root node (selecting some arbitrary node as the root node in the case of a graph) and explores as far as possible along each branch before backtracking. This algorithm uses Stack data structure.
Code:
void DFSRec(vector<int> adj[], int s, bool visited[]) { 	
    visited[s]=true;
    cout<< s <<" ";
    for(int u:adj[s]){
        if(visited[u]==false)
            DFSRec(adj,u,visited);
    }
}
void DFS(vector<int> adj[], int V, int s){
    bool visited[V]; 
	for(int i = 0;i<V; i++) 
		visited[i] = false;
    DFSRec(adj,s,visited);
}
        
Figure: Output after performing DFS on the given graph 
BFS (Breadth First Search)
Starting from the root, all the nodes at a particular level are visited first and then the nodes of the next level are traversed till all the nodes are visited. To do this a queue is used. All the adjacent unvisited nodes of the current level are pushed into the queue and the nodes of the current level are marked visited and popped from the queue.
Code:
void bfs(vector<vector<int>> adj, int start){
    vector<bool> visited(adj.size(), false);
    vector<int> q;       q.push_back(start);
    visited[start] = true; 
    int vis;
    while (!q.empty()) {
        vis = q[0];   cout << vis << " ";
        q.erase(q.begin());
        for (int i = 0; i < adj[vis].size(); i++) {
            if (adj[vis][i] == 1 && (!visited[i])) {
                q.push_back(i);    visited[i] = true;
            }
        }
}
   
Figure: Output for performing BFS on given graph













3. Reason for choosing this technology
•	Foundational Knowledge: Data structures are fundamental concepts in computer science and programming. They provide the basis for organizing and managing data effectively.
•	Algorithm Efficiency: Understanding different data structures helps you choose the right one for specific tasks, optimizing the efficiency of algorithms and reducing time and memory overhead.
•	Problem Solving: Learning about data structures enhances your problem-solving skills. You'll be better equipped to tackle complex programming challenges and develop innovative solutions.
•	Coding Interviews: Many technical interviews for software engineering and programming positions focus on data structures and algorithms. A strong understanding of these topics can significantly improve your performance in interviews.
•	Real-world Applications: Data structures are used extensively in real-world applications like databases, operating systems, game development, and more. Understanding these concepts is crucial for building robust and efficient software.
•	Code Optimization: By using appropriate data structures, you can optimize code execution speed and memory usage, leading to better overall performance of your software.
•	Critical Thinking: Learning about different data structures encourages you to think critically about trade-offs, pros, and cons of each structure in different scenarios.
•	Personal Growth: Mastering data structures can be intellectually rewarding and boost your confidence as a programmer. 
 Profile of the Problem
•	Problem Statement: The Library Management System project is a comprehensive software solution designed to streamline and automate the operations of a library. This system enhances the efficiency of managing various library tasks, such as cataloguing books, tracking borrowing and returning, managing user records, and generating reports. It serves as an essential tool for librarians, administrators, and library patrons.
4. Problem Analysis
•	Challenges:
	Space Optimization: Efficiently allocating and optimizing available parking spots to maximize space utilization.
	Real-time Monitoring: Developing a system to monitor each and every book in real-time and update availability status.
	User Experience: Designing an intuitive and user-friendly interface for users to easily get information about any book.
	Algorithmic Complexity: Developing algorithms for efficient finding book, issuing book and getting information about the borrower.
	Fault Tolerance: Creating a system that can handle hardware or software failures without significant disruption.
	Maintenance: Providing a maintenance plan to ensure the system's longevity.
•	Benefits:
	Improved parking space utilization and reduced congestion.
	Enhanced user experience and convenience.
	Efficient management of library resources.
	Reduced waiting times for issuing or returning books.
5. Software Requirement Analysis
•	Stakeholders:
	Library owner
	System administrators
	Librarian
	Borrower of the books
	Software developers
•	Functional Requirements:
	List All Books:
The system should be able to list the details of all the books that are currently present in the library or are issued to some student. It should contain the details of the student. 
	Adding a Book
The system should be able to add any book manually. So that if any new book arrives in the library, then the librarian should be able to add the details of the book on the database for the issuing. 
	Issuing a Book
The system should be able to issue any book that are available in the library at that moment of time. It should not be able to issue the book to any student if it is already issued to someone else.
	Returning a Book
The system should be able to update the status of the book as returned or available whenever someone returns a particular book. So that the book returned can be issued to somebody else.
	Deleting a Book
The system should be able to delete any book when the book is no longer available in the library. The system should delete only those books that are neither in the library nor issued to anyone.
•	Non-Functional Requirements
	Usability
	Performance
	Reliability
 
6. Implementation
#include <iostream>
#include <string>
#include <iomanip>
using namespace std;

void printLine();
struct BookNode {
    int id;
    string title;
    string author;
    bool isIssued;
    string issuedTo;
    BookNode* next;
};
class LibraryManagementSystem {
private:
    BookNode* head;
public:
    LibraryManagementSystem() {
        head = NULL;
        string books[]={"Anna Karenin", "Madame Bovary", "War and Peace", "The Great Gatsby", "Lolita"};
        string authors[]={"Leo Tolstoy", "Gustave Flaubert", "Leo Tolstoy", "F. Scott Fitzgerald", "Vladimir Nabokov"};
        for(int i=0;i<5;i++){
            addBook(i+1, books[i], authors[i]);
        }
    }
    int addBook(int id, string title, string author) {
        if(isPresent(title, id)){
            return 0;
        }
        BookNode* newBook = new BookNode;
        newBook->id = id;
        newBook->title = title;
        newBook->author = author;
        newBook->isIssued = false;
        newBook->next = NULL;
        if (head == NULL) {
            head = newBook;
        } else {
            BookNode* ptr = head;
            while (ptr->next !=NULL) {
                ptr = ptr->next;
            }
            ptr->next = newBook;
        }
        return 1;
    }
    void searchBookByID(int id) {
        BookNode* ptr = head;
        while (ptr != NULL) {
            if (ptr->id == id) {
                displayBookDetails(ptr);
                return;
            }
            ptr = ptr->next;
        }
        cout << "Book not found!" << endl;
    }
    void searchBookByTitle(const string& title) {
        BookNode* ptr = head;
        while (ptr !=NULL) {
            if (ptr->title == title) {
                displayBookDetails(ptr);
                return;
            }
            ptr = ptr->next;
        }
        cout << "Book not found!" << endl;
    }
    void displayBookDetails(BookNode* book) {
        cout<<endl;
        printLine();
        cout<<left<<setw(10)<<"ID"<<setw(25)<<"TITLE"<<setw(25)<<"AUTHOR"<<setw(15)<<"STATUS"<<"ISSUED TO"<<endl;
        printLine();
        cout<<left<<setw(10)<<book->id<<setw(25)<<book->title<<setw(25)<<book->author<<setw(15)<<(book->isIssued ? "Issued" : "Available")<<(book->isIssued ? book->issuedTo:"-")<<endl;
        printLine();
    }
    int issueBook(int id, string student) {
        BookNode* ptr = head;
        while (ptr != NULL) {
            if (ptr->id == id) {
                if (ptr->isIssued) {
                    return -1;
                } else {
                    ptr->isIssued = true;
                    ptr->issuedTo = student;
                    return 1;
                }
            }
            ptr = ptr->next;
        }
        return 0;
    }
    int returnBook(int id) {
        BookNode* ptr = head;
        while (ptr != NULL) {
            if (ptr->id == id) {
                if (!ptr->isIssued) {
                    return -1;
                } else {
                    ptr->isIssued = false;
                    ptr->issuedTo = "";
                    return 1;
                }
            }
            ptr = ptr->next;
        }
        return 0;
    }
    int deleteBook(int id){
        if(head==NULL){
            return 0;
        }
        if(head->id==id){
            BookNode* temp=head;
            head=head->next;
            delete temp;
            return 1;
        }
        BookNode* pre=NULL;
        BookNode* ptr=head;
        while(ptr!=NULL && ptr->id!=id){
            pre=ptr;
            ptr=ptr->next;
        }
        if(ptr==NULL){
            return 0;
        } else {
            pre->next=ptr->next;
            delete ptr;
            return 1;
        }
    }
    void listAllBooks(){
        BookNode* ptr=head;
        cout<<endl;
        printLine();
        cout<<left<<setw(10)<<"ID"<<setw(25)<<"TITLE"<<setw(25)<<"AUTHOR"<<setw(15)<<"STATUS"<<"ISSUED TO"<<endl;
        printLine();
        while(ptr!=NULL){
            cout<<left<<setw(10)<<ptr->id<<setw(25)<<ptr->title<<setw(25)<<ptr->author<<setw(15)<<(ptr->isIssued ? "Issued" : "Available")<<(ptr->isIssued ? ptr->issuedTo:"-")<<endl;
            printLine();
            ptr=ptr->next;
        }
        cout<<endl;
    }
    bool isPresent(string s, int id=-1){
        BookNode* ptr=head;
        while(ptr!=NULL){
            if(ptr->title.compare(s)==0 || ptr->id==id){
                return true;
            }
            ptr=ptr->next;
        }
        return false;
    }
};

void printLine(){
    for(int i=0;i<90;i++)cout<<"-";
    cout<<endl;
}

int main() {
    LibraryManagementSystem library;
    // library.listAllBooks();
    printLine();
    cout<<"Library Management System"<<endl;
    printLine();
    bool flag=true;
    while(flag){
        cout<<endl<<"Choose one of the operations mentioned below:"<<endl;
        cout<<"1. Add Book"<<endl;
        cout<<"2. Search Book"<<endl;
        cout<<"3. Issue a Book"<<endl;
        cout<<"4. Return a Book"<<endl;
        cout<<"5. Delete a Book"<<endl;
        cout<<"6. List all Books"<<endl;
        cout<<"7. Exit"<<endl;
        cout<<"Enter your choice : ";
        int choice;
        cin>>choice;
        string title, author, studentName;
        int id, i;
        switch(choice){
            case 1:
                cout<<"Id of Book : ";
                cin>>id;
                cout<<"Name of Book : ";
                cin.ignore();
                getline(cin, title);
                cout<<"Author of Book : ";
                getline(cin, author);
                i=library.addBook(id, title, author);
                if(i==0){
                    cout<<"Book is already present (Same ID or Title)"<<endl;
                } else {
                    cout<<"Book added successfully"<<endl;
                }
                break;
            case 2:
                int c;
                cout<<"Enter 1 for Search by id or 2 for Search by title : ";
                cin>>c;
                if(c==1){
                    cout<<"Enter the id : ";
                    cin>>id;
                    library.searchBookByID(id);
                } else {
                    cout<<"Enter the title : ";
                    cin.ignore();
                    getline(cin, title);
                    library.searchBookByTitle(title);
                }
                break;
            case 3:
                cout<<"Enter the id of Book : ";
                cin>>id;
                cout<<"Enter the name of Student : ";
                cin.ignore();
                getline(cin, studentName);
                i=library.issueBook(id, studentName);
                if(i==0){
                    cout<<"Book not found!"<<endl;
                } else if (i==-1){
                    cout<<"Book is already issued!"<<endl;
                } else {
                    cout<<"Book issued!"<<endl;
                }
                break;
            case 4:
                cout<<"Enter the id of the Book : ";
                cin>>id;
                i=library.returnBook(id);
                if(i==0){
                    cout<<"Book not found!"<<endl;
                } else if (i==-1) {
                    cout<<"Book is not issued!"<<endl;
                } else {
                    cout<<"Book returned!"<<endl;
                }
                break;
            case 5:
                cout<<"Enter the id of the Book : ";
                cin>>id;
                i=library.deleteBook(id);
                if(i==0){
                    cout<<"Book not found!"<<endl;
                } else {
                    cout<<"Book deleted successfully!"<<endl;
                }
                break;
            case 6:
                library.listAllBooks();
                break;
            case 7:
                cout<<"Thank you for using LMS"<<endl;
                flag=false;
                break;
            default:
                cout<<"Wrong Choice!!"<<endl;
        }
    }
    return 0;
}
 
7.SCREENSHOTS
 
8. Learning Outcomes from training
•	Understand fundamental data structures like arrays, linked lists, stacks, queues, trees, and graphs. Implement essential algorithms such as searching, sorting etc. And apply DSA concepts to efficiently solve complex programming challenges.
•	Identify problem-solving patterns in competitive programming questions. Formulate effective strategies for tackling various problem types and levels of difficulty. Develop the ability to dissect problems, extract key information, and translate it into algorithmic solutions.
•	Utilize time and space complexity analysis to design optimal algorithms. Apply optimization techniques to reduce computational overhead and improve code efficiency. Implement solutions that not only work correctly but also perform well within competitive time limits.
•	Write clean, modular, and well-documented code for better readability. Debug and troubleshoot code effectively to identify and fix errors quickly. Adapt to different coding environments and online judges used in competitive programming platforms.
•	Develop the ability to approach novel problems with confidence and a systematic mindset. Apply transferable problem-solving skills gained from DSA to tackle a wide range of challenges. Learn to break down complex problems into manageable sub-problems for easier resolution.
•	Cultivate a passion for continuous learning and self-improvement in the field of programming and problem solving. Explore advanced topics beyond the scope of the training to further enhance coding skills. Stay updated with new developments in DSA and competitive programming to remain competitive in the field.







9. Gantt Chart
 


10. References
•	https://www.tutorialspoint.com/data_structures_algorithms/index.htm
•	https://www.programiz.com/dsa
•	https://www.w3schools.com/
•	https://docs.oracle.com/en/java/
•	https://www.boardinfinity.com/
•	https://devdocs.io/cpp/


