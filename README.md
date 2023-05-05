Download Link: https://assignmentchef.com/product/solved-cse222_505-hw7-self-balanced-binary-trees-skip-list
<br>
<strong>Q1:</strong>

Build the following data structures by using the sequence of integers “20, 30, 8, 47, 39, 18, and ‘last four digits of your student number in two-digit format’ (i.e. 181041356 as 13 and 56)”. After you build the data structure, remove all the items one by one in the same order (first in, first out).

<ul>

 <li>AVL Tree</li>

 <li>Red-Black Tree</li>

 <li>2-3 Tree</li>

 <li>Skip List</li>

 <li>B-Tree with order 4</li>

</ul>

Show your work step by step and make your explanation. Write your solution by latex, word or handwriting (scan or take picture) and upload it as a single <em>StudentNumber.pdf</em> file.

<strong>Q2: </strong>

Modify the skip list implementation in the book so that each node in the lowest-level list keeps several elements instead of just one element as in a B-tree node.

<ul>

 <li>The maximum and the minimum number of elements in a node should be specified during the construction of the data structure. The number of elements at each node should be smaller than the maximum. The number of elements at each node should be larger than the minimum, except in the case of one node skip list.</li>

 <li>You should insert the new element into the corresponding node. You may need to split the node when it is necessary.</li>

 <li>After a deletion operation, the number of elements in a node may become smaller than the minimum. In that case, you should combine the node with its predecessor or successor.</li>

</ul>

<strong>Q3:</strong>

Compare the performance of the following data structures.

<ul>

 <li>Regular binary search tree</li>

 <li>Red-Black tree implementation in the book</li>

 <li>Red Black tree implementation in java</li>

 <li>B-tree implementation in the book</li>

 <li>Skip list implementation in the book</li>

 <li>Skip list implementation in java</li>

 <li>Skip list in question Q2</li>

</ul>

For each data structure, do the following:

<ul>

 <li>Insert a collection of randomly generated numbers. Perform this operation 10 times for 10.000, 20.000, 40.000 and 80.000 random numbers (10 times for each). So, you will have 10 instances of each data structure for each 4 different sizes. There should be 240 data structure in total.</li>

 <li>Verify that data structures are built correctly (for example, for BST, perform an inorder traversal).</li>

 <li>Compare the run-time performance of the insertion operation for the data structures. Insert 10 extra random numbers into the structures you built. Measure the running time and calculate the average running time for each data structure and four different problem size. Compare the running times and their increase.</li>

 <li>Compare the run-time performance of the deletion operation for the data structures. Perform 10 successful deletion operations from the structures you built. Measure the running time and calculate the average running time for each data structure and four different problem size.</li>

</ul>

Compare the running times and their increase.

<strong>Q4:</strong>

Implement a menu-driven program for managing a software store. The system has two types of users: administrators who can update information and users who browse software. To update the information, administrators have to enter the system with a password (a single general password is sufficient). Software search is a public feature. The system maintains the information about each software which at least includes name (including version), quantity, and price. The system should be included at least the following functionalities:

<ul>

 <li>Administrator enters the system with a password, to be able to add, delete, update information.</li>

 <li>Search by name, quantity etc. should be available.</li>

 <li>The program should allow the tree to be updated when new software packages arrive at the store and when a software package is sold.</li>

 <li>If a package is sold out, the information about the package should be deleted.</li>

</ul>

Your implementation should use a search tree interface. So, it should be possible to use any data structure implanting search tree interface in your implementation. When it is invoked, your program should automatically create a data structure including the following software packages; Adobe Photoshop 6.0, Adobe Photoshop 6.2, Norton 4.5, Norton 5.5, Adobe Flash 3.3, Adobe Flash 4.0.

<strong>RESTRICTIONS:</strong>

<ul>

 <li>Use only specified data types</li>

 <li>Can be only one main class in each question</li>

 <li>Don’t use any other third part library</li>

</ul>

<strong>GENERAL RULES:</strong>

<ul>

 <li>For any question firstly use course news forum in Moodle, and then the contact TA.</li>

 <li>You can submit assignment one day late and will be evaluated over sixty percent (%40).</li>

</ul>

<strong>TECHNICAL RULES:</strong>

<ul>

 <li>Use given CSE222-VM to develop and test your Homeworks (your code must be working on CSE222-VM), CSE222-VM download link will be given on Moodle.</li>

 <li>Implement <a href="https://www.google.com.tr/search?q=clean+code+standart&amp;oq=clean+code+standart&amp;aqs=chrome..69i57j0.3015j0j4&amp;sourceid=chrome&amp;es_sm=122&amp;ie=UTF-8">clean code standards</a> in your code; o Classes, methods and variables names must be meaningful and related with the functionality.</li>

</ul>

o Your functions and classes must be simple, general, reusable and focus on one topic. o Use standard <a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">java code name conventions</a><a href="https://www.oracle.com/technetwork/java/javase/documentation/codeconvtoc-136057.html">.</a>

<strong>REPORT RULES:</strong>

<ul>

 <li>Add all <a href="http://www.oracle.com/technetwork/articles/java/index-137868.html">javadoc</a> documentations for classes, methods, variables …etc. All explanation must be meaningful and understandable.</li>

 <li>You should submit your homework code, Javadoc and report to Moodle in a</li>

</ul>

“studentid_hw3.tar.gz” file.

<ul>

 <li>Use the given homework format including selected parts from the table below:</li>

</ul>

Detailed system requirements

Use case diagrams (extra points)

Class diagrams                                                                          X

Other diagrams

Problem solutions approach                                                     X

Test cases                                                                                  X