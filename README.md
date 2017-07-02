# Basic Programming Concept
Basic Programming Concept

# 1. Digital

## a. Number Systems:

Like many words and phrases, the phrase "number system"​ has more than one meaning.

Meaning I​: A collection of things (usually called numbers) together with operations on those

numbers and the properties that the operations satisfy.

Example: The counting numbers (1, 2, 3, ...) together with the operations of addition,

subtraction, multiplication, and division and the properties they satisfy. These properties include:

● Two counting numbers can always be added to give a result that is a counting number.

● You can only subtract a counting number from another counting number and obtain a

counting number as the result if the number you subtract is smaller than the number you

subtract from.

● The associative property for addition: (a + b) + c = a + (b + c) for every three counting

numbers a, b, and c.

● The commutative property for addition: a + b = b + c for every two counting numbers a

and b.

● The distributive property of multiplication over addition: a(b + c) = ab + ac for every

three counting numbers a, b, and c.

Meaning II​: A system for representing (that is expressing or writing) numbers of a certain type.

Example: There are several systems for representing the counting numbers. These include:

● The usual "base ten" or "decimal" system: 1, 2, 3, ... , 10, 11, 12, ... 99, 100, ....

● Roman numerals: I, II, III, IV, V, VI, VII, VIII, IX, X, ...

● The binary system: 1, 10, 11, 100, 101, ...(read as "one", "one, zero", "one, one", "one,

zero, zero", etc.) This system used in computer science. We will discuss this and other

systems of representing numbers later in this class.

Meaning III​: A combination of Meanings I and II. In other words, a collection of numbers

together with operations, properties of the operations, and a system of representing these

numbers.

Example: If we consider the counting numbers as a number system using Meaning I, it wouldn't

matter whether we expressed 4 as 4 (decimal), IV (Roman numeral), or 100 (binary), but using

Meaning III, it would matter.

## b. Binary:

Binary​ is a base 2 numbering system. Which means each digit can be one of two values, a 1 or

a 0. The value of binary is read from right to left and each digit's value is one more than every

previous digit combined (which is the same as 2x the digit immediately before it). It's easier for

me to show than explain:

0001 = 1

0010 = 2

0011 = 3

0100 = 4

1000 = 8

## c. Octal:

Octal​ numbers are a way of counting. They system uses the numbers 0 through 7.

An octal number: 372 (subscript 8)

To find the decimal number:

3 x (8^2) + 7 x (8^1) + 2 x (8^0) = 3 x 64 + 7 x 8 + 2 x 1

The final answer is 250 (subscript 10) .

## d. Hex:

The hexadecimal numeral system​, also known as just hex​, is a numeral system made up of

16 symbols (base 16). Hexadecimal uses the decimal numbers and includes six extra symbols.

There are no symbols that mean ten, or eleven etc. so these symbols are letters taken from the

English alphabet: A, B, C, D, E and F. Hexadecimal A = decimal 10, and hexadecimal F =

decimal 15.

## e. Decimal:

Decimal​ is a term that describes the base-10 number system, probably the most commonly

used number system. The decimal number system consists of ten single-digit numbers: 0, 1, 2,

3, 4, 5, 6, 7, 8, and 9. The number after 9 is 10. The number after 19 is 20 and so forth.

Additional powers of 10 require the addition of another positional digit.

## f. Gates (logic):

A logic gate​ is an elementary building block of a digital circuit. Most logic gates​ have two

inputs and one output. At any given moment, every terminal is in one of the two binary

conditions low (0) or high (1), represented by different voltage levels.

### i. And:

The AND​ gate is an electronic circuit that gives a high​ output (1) only if all​ its inputs are high. A

dot (.) is used to show the AND operation i.e. A.B. Bear in mind that this dot is sometimes

omitted i.e. AB

### ii. OR:

The OR​ gate is an electronic circuit that gives a high output (1) if one or more​ of its inputs are

high. A plus (+) is used to show the OR operation.

### iii. XOR:

The 'Exclusive-OR​' gate is a circuit which will give a high output if either, but not both,​ of its

two inputs are high.

### iv. NOT:

The NOT​ gate is an electronic circuit that produces an inverted version of the input at its output.

It is also known as an inverter. If the input variable is A, the inverted output is known as NOT A.

This is also shown as A', or A with a bar over the top, as shown at the outputs.

## g. Boolean Algebra:

Boolean algebra​ is the branch of algebra in which the values of the variables are the truth

values true and false, usually denoted 1 and 0 respectively.

Laws of Boolean Algebra:

Every law has two expressions, (a) and (b). This is known as duality. These are obtained by

changing every AND(.) to OR(+), every OR(+) to AND(.) and all 1's to 0's and vice-versa.

### T1 : Commutative Law

(a) A + B = B + A

(b) A B = B A

### T2 : Associate Law

(a) (A + B) + C = A + (B + C)

(b) (A B) C = A (B C)

### T3 : Distributive Law

(a) A (B + C) = A B + A C

(b) A + (B C) = (A + B) (A + C)

### T4 : Identity Law

(a) A + A = A

(b) A A = A

### T5 : Redundance Law

(a) A + A B = A

(b) A (A + B) = A

### T6 : De Morgan's Theorem

(a) (A + B)' = A' . B'

(b)(A . B)' = A' + B'

# 2. Operating System:

An Operating System (OS)​ is an interface between a computer user and computer hardware.

An operating system is a software which performs all the basic tasks like file management,

memory management, process management, handling input and output, and controlling

peripheral devices such as disk drives and printers.

## a. Process:

In computing, a process​ is an instance of a computer program that is being executed. It

contains the program code and its current activity. Depending on the operating system(​ OS​), a

process​ may be made up of multiple threads of execution that execute instructions

concurrently.

## b. Thread:

A thread​ is a path of execution. In it's simplest form think of it as a simple program that

executes a loop. The more of these that you can run, in parallel, the more work can be done.

## c. Scheduling:

Scheduling​ is the method by which threads, processes or data flows are given access to

system resources (e.g. processor time, communications bandwidth). This is usually done to load

balance and share system resources effectively or achieve a target quality of service.

## d. Deadlocks:

A deadlock​ is a situation which occurs when a process or thread enters a waiting state because

a resource requested is being held by another waiting process, which in turn is waiting for

another resource held by another waiting process.

## e. Virtual Memory:

Virtual memory​ is a memory​ management technique that is implemented using both hardware

and software. It maps memory​ addresses used by a program, called virtual​ addresses, into

physical addresses in computer memory​.

# 3. Data Structures:

## a. What are they?

Data can be organised and represented in a number of ways depending upon our need. The

way data is organised, stored and retrieved in a computer is called Data structure.​

## b. Array:

Array is a container which can hold fix number of items and these items should be of same

type. Most of the data structure make use of array to implement their algorithms. Following are

important terms to understand the concepts of Array.

● Element​ − Each item stored in an array is called an element.

● Index − Each location of an element in an array has a numerical index which is used to

identify the element.

### Basic Operations:

● Traverse​ − print all the array elements one by one.

● Insertion​ − add an element at given index.

● Deletion​ − delete an element at given index.

● Search​ − search an element using given index or by value.

● Update​ − update an element at given index.

## c. Link List:

Link List is a sequence of links which contains items. Each link contains a connection to

another link. Linked list the second most used data structure after array. Following are

important terms to understand the concepts of Linked List.

● Link​ − Each Link of a linked list can store a data called an element.

● Next​ − Each Link of a linked list contain a link to next link called Next.

● Linked List​ − A Linked List contains the connection link to the first Link called First.

### Basic Operations:

● Insertion​ − This operation is used to insert a new node in the linked list.

● At the beginning of the list,

● At a certain position and

● At the end.

● Deletion​ − This operation is used delete node from the list.

● At the beginning of the list,

● At a certain position and

● At the end.

● Display​ − displaying complete list.

● Search​ − search an element using given key.

## d. Tree:

Trees​ show a relationship among a collection of objects (nodes), where relationships are one

way and only one object (node) is at the head of every arrow.

Following are important terms with respect to tree.

● Path​ - the set of edges from the root to a node

● Root​ - node with no parent

● Parent​ - node at the tail of an arrow

● Child​ - node at the head of an arrow

● Leaf​ - node with no child

● Subtree​ - represents descendents of a node.

### Binary Search Tree:

A Binary Search Tree​ (BST​) or "ordered binary tree"​ is a type of binary tree​ where the nodes

are arranged in order: for each node, all elements in its left subtree are less to the node (<), and

all the elements in its right subtree are greater than the node (>).

## e. Maps:

A Map​ is an abstract data structure (ADT) that stores key-value (k,v) pairs and there cannot be

duplicate keys . They are useful in situations where a key can be viewed as a unique identifier

for the object . They are mostly used in searching for their fast lookup.

## f. Dictionary:

Dictionary​ is an abstract data type composed of a collection of (key, value) pairs, such that

each possible key appears at most once in the collection. It is same as Maps but maps are fast.

## g. Hashing based collections:

Hashing​ means using some function or algorithm to map object data to some representative

integer value. This so-called hash code​ (or simply hash​) can then be used as a way to narrow

down our search​ when looking for the item in the map.

### Basic Operations

● Search​ − search an element in a hashtable.

● Insert​ − insert an element in a hashtable.

● delete​ − delete an element from a hashtable

## h. Stack:

Last in First out

A Stack​ ADT is linear structure . Items are added and removed from only one end of a stack

like you put the dishes into a box, when you want to take back them, the last one will be taken

first .

### Basic Operations:

● push()​ − storing an element on the stack.

● pop()​ − removing an element from the stack.

● peek()​ − get the top data element of the stack, without removing it.

● isFull()​ − check if stack is full.

● isEmpty()​ − check if stack is empty.

## i. Graph:

A Graph​ consist of a finite set of elements called nodes or vertices together with a finite set of

arcs or edges that connect pair of vertices.

Graph Data Structure:

In the above graph,

Vertices ​=> {a, b, c, d, e}

Edges ​=> {ab, ac, bd, cd, de}

Adjacency​ => b​ is adjacent to a​ , d​ is adjacent to b

Path ​=> abde​ represents a path from a​ to e​.

### Basic Operations:

● Add Vertex​ − add a vertex to a graph.

● Add Edge​ − add an edge between two vertices of a graph.

● Display Vertex​ − display a vertex of a graph.

## j. Queue:

First in First out

A Queue​ is similar to a list but adds items only to the rear of the list and removes them only

from the front look like you are in line to enter the stadium to watch a match, first people in the

line will enter the stadium first.

### Basic Operations:

● enqueue()​ − add an item to the queue.

● dequeue()​ − remove an item from the queue.

● peek()​ − get the element at front of the queue without removing it.

● isfull()​ − checks if queue is full.

● isempty()​ − checks if queue is empty.

## k. Heap:

A binary heap​ is a complete binary tree which satisfies the heap ordering property. The

ordering can be one of two types:

​ ● the min-heap property: the value of each node is greater than or equal to the value of

its parent, with the minimum-value element at the root.

​ ● the max-heap property: the value of each node is less than or equal to the value of its

parent, with the maximum-value element at the root.

# 4. Programming /Algo:

## a. What is it?

Programming ​is the process of converting an algorithm into code that could be executed by a

computer.

Algorithm ​is a finite sequence of steps for solving a particular problem.

## b. Variable:

● Variables ​are placeholders for values that you will assign and potentially modify later in

the program.

● Variables ​is a name given to a storage area that our programs can manipulate.

## c. Function / Procedure:

Function ​/ Procedure​ ​is used when we need to perform certain operations repeatedly,used to

increase the readability as well as decrease the size of the code. They both are same but

function returns a value while procedure just executes commands.

## d. Methods:

Method ​in object-oriented programming is a procedure associated with a class. A method

defines the behavior of the objects that are created from the class. Another way to say this is

that a method is an action that an object is able to perform.

## e. Decisions:

Decision ​structures are that the programmer specifies one or more conditions to be evaluated

and perform specific operations based on the condition examples are if/else and switch

conditions .

## f. Loops:

Loops ​are used to repeat the same operations a certain number of times, which could even

vary based on some runtime conditions. Different types of loops are while , for , do-while etc.

## g. Methods:

### i. Iteration:

Iteration​ is a form of repetition , It's a design structure to repeat a body of code (a small amount

of code) a number of times, while changing the variables in the code. Here's an example:

for(i = 0; i < 10; i++){

printf("%d\n",i);

}

### ii. Traverse:

#### 1. Breadth First:

Breadth first search​ is a simple strategy in which the root node is expanded first, then all the

successors of the root node are expanded next, then their successors and so on until the best

possible path has been found.

#### 2. Depth First:

In Depth first search​ , start at the top most node in a tree and then follow the leftmost branch

until there exists no more leafs in that branch. At that point you will search the nearest ancestor

with unexplored nodes until such time as you find the goal node.

# 5. DBMS:

## a. Relations:

Relation ​is a set of ordered pairs also represented as table , it is predefined row/column format

for storing information in a relational database.

In terms of math:

A relation is simply a set of ordered pairs.

This mapping shows a relation from set A into set B.

This relation consists of the ordered pairs (1,2), (3,2), (5,7), and (9,8).

## b. Functions:

Every Function ​is a relation , There are several functions that a DBMS performs to ensure data

integrity and consistency of data in the database.

In terms of math:

A function is a set of ordered pairs in which each x-element has only ONE y-element associated

with it.

The relations shown above are NOT functions because certain x-elements are paired with more

than one unique y-element.

This mapping shows function: {(1,2), (2,4), (3,5)}.

## c. Relational Algebra Intro:

Relational Algebra​ is procedural query language. It consists of a set of operations that take

one or two relations as input and produce a new relation.The main application of relational

algebra is providing a theoretical foundation for relational databases, particularly query

languages such as SQL.

### Relational Algebra Operations:

● Select ​- Selects a subset of rows from relation.

● Project ​- Deletes unwanted columns from relation.

● Rename ​- Renames attributes and relation

● Union ​- Tuples in relation 1 and in relation 2.

● Set Difference ​- Tuples in relation 1, but not in relation 2.

● Cartesian Product - ​ Allows us to combine two relations.

## d. Tables:

The data in relational database is stored in database objects called tables.​ The table is a

collection of related data entries and it consists of columns and rows. A table​ has a specified

number of columns, but can have any number of rows.

## e. Keys:

Each row has one or more attributes, known as relation key, which can identify the row in the

relation uniquely.

Superkey​ - an attribute or set of attributes that uniquely identifies an entity--there can be many

of these

Composite key​ - a key requiring more than one attribute

Candidate key​ - a superkey such that no proper subset of its attributes is also a superkey

(minimal superkey – has no unnecessary attributes)

Primary key​ - the candidate key chosen to be used for identifying entities and accessing

records. Unless otherwise noted "key" means "primary key"

Alternate key​ - a candidate key not used for primary key

Secondary key​ - attribute or set of attributes commonly used for accessing records, but not

necessarily unique

Foreign Key​ -They are columns that point to primary key columns of another table for

referencing records.

## f. Normalization:

Normalization ​is a method to remove all these anomalies or to minimize data redundancy and

bring the database to a consistent state.

### i. 1st Normal Form:

​ A table (relation) is in 1

​ st

​ Normal Form (1NF) if

● There are no duplicated rows in the table.

● Each cell is single-valued (i.e., there are no repeating groups or arrays).

● Entries in a column (attribute, field) are of the same kind.

### ii. 2nd Normal Form:

​ A table is in 2

​ nd

​ Normal Form (2NF) ​if it is in 1NF and if all non-key attributes are dependent on

all of the key or if it has no partial dependencies.

In mathematics and logic, a partial dependency is a functional dependency X -> Y that holds for

a relation where X is a proper subset of one of the candidate keys of that relation.

### iii. 3rd Normal Form:

​ A table is in 3rd Normal Form (3NF) if it is in 2NF and if it has no transitive dependencies.

In mathematics and logic, a transitive relationship is a relationship of the following form: "If A

implies B, and if also B implies C, then A implies C." An example is: "If John Doe is a human,

and if every human is a primate, then John Doe must be a primate."

We have: [(A → B) and (B → C)] → (A → C)

## g. Transactions:

A Transactions​ is an event which occurs on the database. Generally a transaction reads a

value from the database or writes a value to the database. A read operation does not change

the image of database but write operation change the image of database.

Transactions in a database system must conforms the ACID properties:

### Atomicity:

It ensures that either all of the instructions within the transaction will be reflected in database , or

none of them will be reflected.

### Consistency:

It ensures that the transactions will yield the same expected result.

### Isolation:

It ensures that the transactions operate independently and transparent to each other .

### Durability:

It ensures that once the transactions has been complete the changes it has made should be

permanent.

## h. Relation cardinality & modularity:

Cardinality ​specifies how the number of occurrences of one object are related to number of

occurrences of another object .

One-to-one​: X-Y is 1:1 when each entity in X is associated with at most one entity in Y, and

each entity in Y is associated with at most one entity in X.

One-to-many​: X-Y is 1:M when each entity in X can be associated with many entities in Y, but

each entity in Y is associated with at most one entity in X.

Many-to-many​: X:Y is M:M if each entity in X can be associated with many entities in Y, and

each entity in Y is associated with many entities in X ("many" =>one or more and sometimes

zero).

Modularity​ is the degree to which a system's components may be separated and recombined.

## i. Function dependencies:

Functional dependency​ is a relationship that exists when one attribute uniquely determines

another attribute.

X →Y is an assertion about a relation R that whenever two tuples of R agree on all the attributes

of X, then they must also agree on all attributes in set Y .

emp_id--> emp_name . "employee name is functionally dependent upon employee id." we can

find the name of an employee if we have his employee id because employee id is unique.

emp_name ---> emp_id , is not unique because multiple employees can have the same name.

# 6. OOP:

## a. What is OOP?

Object​-oriented programming​ (OOP​) is a programming model that simulate real life objects

and their behaviors using computer programming.

In OOP , there are classes with methods and properties, and objects that are instances of those

classes.

Inheritance , encapsulation , abstraction and polymorphism are the pillars of OOP.

## b. Procedural programming / Function programming:

Procedural programming​ uses a list of instructions to tell the computer what to do step by

step. Procedural programming relies on procedures, also known as routines. A procedure

contains a series of computational steps to be carried out.Examples of procedural languages

include Fortran, COBOL and C.

Functional programming​ is an approach to problem solving that treats every computation as a

mathematical function. The outputs of a function rely only on the values that are provided as

input to the function and don't depend on a particular series of steps that precede the function.

Examples of functional programming languages include Erlang, Haskell, Lisp and Scala.

## c. Classes:

A class​ is kind of a prototype or template that refer to the methods and attributes that will be in

each object. Its is composed of three things : its name , attributes / properties and methods.

## d. Access Modifier:

Access modifiers help us in implement of Encapsulation (information hiding). They tell the

compiler which other classes should have access to the field or method being defined.

Private , Protected and Public are access modifiers:

● Private​ - Only the current class will have access to the field or method.

● Protected​ - Only the current class and subclasses of this class will have access to the

field or method.

● Public​ - Any class can refer to the field or call the method.

## e. Object / Instance:

An Object​ is an Instance​ of a class.

- Classname objectname;

Object is declared in above statement but does not occupy any memory.

- Classname objectname = new Classname();

Instance of class is created and some memory is occupied.

## f. Member:

Everything which is a part of a class, is it's member. A property is one kind of member. Others

might be constructors, methods, fields, nested types, conversions, indexers etc.

## g. Method and Signature:

Method ​is a collection of statements that are grouped together to perform an operation.

Method signature​ consists of the method’s name and the data types of the method’s

parameters, in the order that they appear. The return type is not part of the signature.

-add(int , int)

-add(string, string)

## h. Constructor / Destructor:

Constructor​ : A procedure that is used for creating and initializing objects. In C++, constructor

is called after the object has been created and is used mainly to initialize the object's internal

state.

Destructor​ : A function that cleans up or deinitializes each object of a class immediately before

the object is destroyed. Destructors execute when the program leaves the scope in which

objects are defined and when any object is destroyed by delete . Destructors have the same

name as their class, prefixed by a tilde, ~.

## i. Overloading / Overriding:

Overloading​ is when you dene two methods with the same name, in the same class,

distinguished by their signatures.

Overriding​ is when you redene a method that has already been dened in a parent class

(using the exact same signature).

Overloading is resolved at compile time while Overriding is resolved at runtime (based on

the type of the implicit rst parameter).

## j. Object Model:

Object Model​ deals with object oriented "blueprint" of your system. This includes, class

diagrams (classes you will be creating), relationship between these classes, methods in the

classes, properties etc.

## k. Generalization / Specialization / Inheritance:

Generalization ​is the result of taking the union of two or more lower level entity sets to produce

a higher level entity sets.

Specialization ​is the result of taking subsets of higher level entity set to form a low level entity

sets.

Inheritance ​is The ability of creating a new class from an existing class.

The base class(the Parent class) has properties and methods that will be inherited by the sub

class(child class) and it can have additional properties or methods.

## l. Polymorphism:

Polymorphism ​is the ability of an object to take on many forms. The most common use of

polymorphism in OOP occurs when a parent class reference is used to refer to a child class

object.

Virtual Functions​ have a body (the function may be reimplemented in child classes, but it isn't

required).

    class Foo

    {

      virtual void bar()
			
      {

        do stuff;
				
      }

    }

Pure Virtual Functions​ have no body (the function must be implemented in child classes)

    class Foo

    {

    virtual void bar() = 0;

    }

## m. Encapsulation:

Encapsulation ​means preventing access to some piece of information or functionality.

An abstract specification tells us what an object does but not how it does it (information I

functionality hiding). With encapsulation we can design a program in a way that changing its

internal implementation will have no effect on the rest of the program or its users.

Example: a stack can be implemented at first using an array, we can later change this to a

single linked list. It should not affect the users of the class Stack.

## n. Virtual methods / vtable:

A member of a class that can be redefined in its derived classes is known as a virtual member.

Once a method is declared as virtual, it is virtual in all derived classes too.

vtable ​: A virtual method table is to support run-time method binding.

Typically, the compiler creates a separate vtable for each class. When an object is created, a

pointer to this vtable, called the virtual table pointer, v pointer or VPTR, is added as a hidden

member of this object.

## o. Interface:

An Interface ​is a programming structure/syntax that allows the computer to enforce certain

properties on an object (class). For example, say we have a car class and a scooter class and a

truck class. Each of these three classes should have a start_engine() action. How the "engine is

started" for each vehicle is left to each particular class, but the fact that they must have a

start_engine action is the domain of the interface.

## p. Packages:

● A package is a collection of classes (a library).

● Characteristic of a package

● Organized in a hierarchy

● Uses the file system for implementing the hierarchy

● A package corresponds to a directory

● Every package is a name space.

● By default, classes belong to the unnamed package.

● Packages introduce new scope rules.

# 7. Design Pattern:

## a. What are they?

A Design pattern​ is:

• a standard solution to a common programming problem

• a design or implementation structure that achieves a particular purpose

Types of Design Patterns:

● Creational Design patterns - ​ How create objects.

● Structural design patterns​ - How compose objects.

● Behavioral design patterns​ - How communicate between objects.

## b. Singleton:

The Singleton Pattern​ is a creational p​ attern which specifies that only a single instance of a

class should exist with a global point of access. This works well when modeling real-world

objects only having one instance:

    public class Singleton {

     private static Singleton instance = null;

     public static Singleton getInstance() {

       if (instance == null) {

         instance = new Singleton();

       }

       return instance;

     }

    }

The above class “hides” the creation of the single instance behind the static method

getInstance() to ensure you only initialize the class once. When you need to access the

singleton object, you simply make a call as follows: Singleton.getInstance();

## c. Strategy:

The Strategy pattern​ is a behavioural p​ attern , it specifies that if there are several ways

(algorithms) to perform the same operation and application requires to pick the specific way

based on the parameters or the conditions.

Strategy pattern​ used to manage algorithms, relationships and responsibilities between

objects.

A very simple example for this article would be the sorting feature. For example, we have

multiple algorithms for sorting arrays, but based on the number of elements of the array, we

should choose which algorithm to use that yields the best performance.

## d. Factory:

The Factory​ Pattern​ is a creational p​ attern , It is an object that is responsible for creating and

delivering other objects based on incoming parameters.

There are three variations of the factory pattern:

● Simple Factory Pattern​ - This allows interfaces for creating objects without exposing

the object.

● Factory Method Pattern​ - This allows interfaces for creating objects, but allow

subclasses to determine which class to instantiate.

● Abstract Factory Pattern​ - Unlike the above two patterns, an abstract factory is an

interface to create of related objects without specifying/exposing their classes.

## e. MVC:

The Model-View-Controller (MVC) ​design pattern assigns objects in an application one of

three roles: model, view, or controller. The pattern defines not only the roles objects play in the

application, it defines the way objects communicate with each other.

● The Model​ is where data resides or The object that holds application data and

defines how to manipulate it.

● The View​ layer is the face of application or The objects that are in charge of the

visual representation of the Model and the controls the user can interact with.

● The Controller​ communicate between the view and the model or It accesses the

data from the model and displays it with the views, listens to events and

manipulates the data as necessary.
