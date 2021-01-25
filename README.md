# 3013-Algorithms

### Roster
![](https://d3vv6lp55qjaqc.cloudfront.net/items/220B0V0H3c041K2p251Z/google-sheets-16.png?X-CloudApp-Visitor-Id=1094421) [Class Roster](https://docs.google.com/spreadsheets/d/1pljpeLsxiFMn4G_oHD-0Ix5b7lTIT_O5P_XSL7ZiQbQ/edit?usp=sharing)


### General Course Info
- __Days:__ TTh 12:30 a.m. - 1:50 p.m. 
- __Location:__ BO 320
- [__Semester:__](https://msutexas.edu/registrar/_assets/files/pdfs/acadcal2021.pdf) Monday January 11<sup>th</sup> - Friday April 23<sup>rd</sup>
- [__Holidays:__](https://msutexas.edu/registrar/_assets/files/pdfs/acadcal2021.pdf)
  - __Martin Luther King Jr. Day__ Monday January 18<sup>th</sup>
  - __"Holiday Break" (lol):__ Wednesday March 31<sup>st</sup> - Monday April 5<sup>th</sup> 
- [__Last Day for “W”:__](https://msutexas.edu/registrar/_assets/files/pdfs/acadcal2021.pdf)  Friday April 23<sup>rd</sup>
- [__Last Day of Class:__](https://msutexas.edu/registrar/_assets/files/pdfs/acadcal2021.pdf) Friday April 23<sup>rd</sup>
- [__Final Exam:__](https://msutexas.edu/registrar/_assets/files/pdfs/spring20finals.pdf) Thursday April 29<sup>th</sup> @ 10:30am

### Resources

Here are some open source books for the course. I hope you guys appreciate the amount of effort it takes to put material together and then put it on the internet for free.

- [Discrete Structures for Computer Science: Counting, Recursion, and Probability](http://cglab.ca/~michiel/DiscreteStructures/)
  - Thanks To: [Michiel Smid](http://people.scs.carleton.ca/~michiel/)
- [Open Data Structures](https://opendatastructures.org/ods-cpp.pdf)
  - Code available [HERE](https://github.com/patmorin/ods)
  - Thanks To: [Pat Morin](http://cglab.ca/~morin/)
- [Algorithms](http://jeffe.cs.illinois.edu/teaching/algorithms/)
  - Thanks To: [Jeff Erickson](http://jeffe.cs.illinois.edu/)
- [Wikipedia Collection of Data Structures](https://en.wikipedia.org/wiki/Book:Data_structures)

### Assumed

- This course assumes know what `array based data structures` and `list based data structures` are.
- For example you should be able to write (from scratch) an `array based stack` and `queue` along with a `list based stack` and `queue`. If you cannot, go study.
- You should have a general understanding of recursive functions.
- You should have a general understanding on graph structures more specifically be able to write and traverse a basic Binary Search Tree (BST).
- Basic OOP programming skills are also assumed. 
  

#### Algorithm Categories

- Recursion
- Greedy Algorithms
- Backtracking
- Dynamic Programming

#### Topics List

I will try to go over the list of topics in the order they are listed. However, jumping
around is a necessary evil. There are always multiple ways to implement every data structure. For example there is a data structure called a **priority queue**. It can be implemented by storing a representation of a binary tree in an array, called a **binary heap**. Another way of implementing a priority queue is by using an ordered **singly linked list**. And lets not stop there! There is a third way of implementing a priority queue that uses a doubly circular linked list. Its known as a **Fibonacci Heap**! So please understand that there is no real single simple path through all of these data structures. All I can promise is that we will try to stay on the path, but we probably won't.... 

- [x] Array Based vs List Based Structures
- [x] [Array Based Implementations](https://opendatastructures.org/ods-cpp/2_Array_Based_Lists.html)
- [ ] Complexity 
  - [ ] Introduction 
  - [ ] Will be discussed with each data structure
- [ ] Linked List Types
  - [x] [Singly Linked List](https://opendatastructures.org/ods-cpp/3_1_Singly_Linked_List.html)
  - [ ] [Doubly Linked List](https://opendatastructures.org/ods-cpp/3_2_Doubly_Linked_List.html)
  - [ ] [Circular List](https://www.geeksforgeeks.org/circular-linked-list/)
- [ ] Stack, Queue, Priority Queue, Deque
- [x] Array Based Binary Search
- [x] Binary Tree's
  - [x] Components
  - [x] Array Based
- [ ] Binary Heap (Array Based)
- [ ] Fibonacci Heap (**Possibly**)
- [ ] Binary Tree Implementation (List Based)
- [ ] Balanced Tree's
  - [ ] AVL
  - [ ] Red Black (**Possibly**)
- [ ] [Hash Tables](https://opendatastructures.org/ods-cpp/5_Hash_Tables.html)
- [ ] Graphs 
  - [ ] Array Based and List Based Implementations
  - [ ] [Basic Graph Algorithms](http://jeffe.cs.illinois.edu/teaching/algorithms/book/05-graphs.pdf)
  - [ ] [DFS (Depth-First Search)](http://jeffe.cs.illinois.edu/teaching/algorithms/book/06-dfs.pdf)
  - [ ] [BFS (Breadth-First Search)](https://opendatastructures.org/ods-cpp/12_3_Graph_Traversal.html)
  - [ ] [Minimum Spanning Trees](http://jeffe.cs.illinois.edu/teaching/algorithms/book/07-mst.pdf) 
    - [ ] Prim's Algorithm (Minimum Spanning Tree)
    - [ ] Kruskal's Algorithm (Minimum Spanning Tree)
  - [ ] [Shortest Path](http://jeffe.cs.illinois.edu/teaching/algorithms/book/08-sssp.pdf)
    - [ ] Dijkstra's Algorithm (One Way Shortest Path)
    - [ ] A-Star Algorithm (**Possibly**)
- [ ] Sorting:
  - [ ] Merge Sort
  - [ ] Quick Sort




### Resources

- http://opendatastructures.org/ods-cpp/
- https://github.com/ippeb/ACM-ICPC

## Grading

| Categories                                   |       | Grade |          |
| :------------------------------------------- | :---: | :---: | :------: |
| Exams (3)<sup>**1**</sup>                    |  40%  |   A   |  89-100  |
| Programs (3-5)<sup>**2**</sup> & Assignments |  30%  |   B   |  79-88   |
| Final<sup>**4**</sup>                        |  20%  |   C   |  69-78   |
| Github Portfolio                             |  10%  |   D   |  59-68   |
|                                              |       |   F   | below 59 |

>**1**. Lowest exam grade replaced by Final Exam grade (Not a "right" but a privilege based on effort and attendance).
>
>**2**. Despite the low overall value of the programming portion of the course, ALL programs must be turned in running to pass the course.  They don't have to be necessarily correct, but they must run and they need to at least approach the solution (a "Hello World" program will not work). 
>
>**3**. The worth of the "homework/quizzes" section of the course will be calculated by a function based on the number of assignments and quizzes. If zero homeworks / quizzes are assigned then they will be assigned a 0% portion. If at least 10 are assigned then the full 25% will be assigned as its weight. If the full weight is not used the class will decide how the remaining percentage points will be assigned. 
>
>**4**. Plane ticket prices, events like weddings, or trips out of the country are not valid excuses for missing the final exam at its scheduled time. I will not make accommodations for anything other than an issue vetted by the dean of students. 

## Misc

- https://repl.it
- https://code.visualstudio.com/download

- Attending class is one of the primary keys to doing well in this class. Students may be dropped for excessive absences. There is no distinction made between excused and unexcused. 

- Make-up exams are not given. If I see fit, then I will replace a missed exam with your final exam test grade. If you do miss an exam without prior approval, a letter from the dean of students will be needed as an excuse.

- A number of programming assignments will be made to code and execute. Microsoft Visual Studio 2015 / 2017 is recommended or just Visual Studio Code.

- Programs containing syntax errors are unacceptable and will be returned without grading (your programs must work). All submitted programs need to be submitted via Github.

- Periodically homework assignments will be taken up and graded. It is the student's responsibility to keep up with assignments and to ask questions over the assigned work, even if absent. All homework assignments are due at the specified time that may or may not be in conjunction with a class day. All assignments / homeworks will be uploaded via Github.
