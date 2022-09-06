Goal
Building on your GitHub Java project from assignment 1, implement basic tree data structures
including a binary tree, AVL tree, and N-ary tree from scratch without the use of any built in
libraries or utilities.
YOUR SOLUTIONS MUST BE IMPLEMENTED FROM SCRATCH! MAY NOT USE LIBRARIES
OR PACKAGES LIKE java.util.TreeMap OR java.util.TreeSet!!!! This will result in a 0 for the
entire assignment!
Requirements
1. Create a new `BinaryTree.java` class that performs as a binary tree for string data type.
a. Include an attribute `Node root` to point to the root Node.
b. Include an attribute `int nodeCount` to keep track of the number of nodes in the
tree.
c. Include method to insert. `Node insert(String newData)`
d. Include method to remove. `Node remove(String data)`
e. Include method to search. `Node search(String data)`
f. Include a method to return the tree contents as a String. `String treetoString()`
2. Create a new `AVLTree.java` class that performs as an AVL tree for string data type.
a. Include an attribute `Node root` to point to the root Node.
b. Include an attribute `int nodeCount` to keep track of the number of nodes in the
tree.
c. Include method to insert. `Node insert(String newData)`
d. Include method to remove. `Node remove(String data)`
e. Include method to search. `Node search(String data)`
f. Include a method to return the tree contents as a String. `String treetoString()`
3. Create a new `Nary.java` class that performs as an N-ary tree for string data type.
a. Include an attribute `Node root` to point to the root Node.
b. Include an attribute `int nodeCount` to keep track of the number of data nodes in
the tree.
c. Include an attribute `int M` to keep track of the order of the tree.
d. Include method to insert. `Node insert(String newData)`
e. Include method to remove. `Node remove(String data)`
f. Include method to search. `Node search(String data)`
g. Include a method to return the tree contents as a String. `String treetoString()`
4. Using the features you created in assignment 0, read in the contents of a file specified
on the command line, like ‘data/input0.txt’.
a. Create an empty tree of each type binary, AVL, and 5-ary.
b. Insert each line of the file as a node data value into the tree.
c. Print a summary after generating the trees containing the type, node count, root
key/content, and number of levels. Expected output example will be posted.
