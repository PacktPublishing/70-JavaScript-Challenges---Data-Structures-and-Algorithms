# 70-JavaScript-Challenges---Data-Structures-and-Algorithms
Traversy JS Challenges, Data Structures, and Algorithms
This is a sandbox for my upcoming JavaScript challenges, data structures, and algorithms course. Just about all of the concepts that are included, also exist in other languages. So, if you are not a JavaScript developer, you can still follow along and learn from this course/repo.

This course/repo goes over everything from basic loop challenges, recursion, complexity, data structures, and algorithms. It is meant to be a complete course on the subject. It is not meant to be a course on JavaScript fundamentals. You should already know the basics of JavaScript.

File Structure
Each folder includes:

readme.md - The challenge/code instructions. This also includes hints, tests and a dropdown with the solution code as well as the explanation of the solution code.
[name].js - This is your working file. It has the name of the function and the function is exported. No parameters are passed to the function. That is up to you to add.
[name]-run.js - File to run the code manually. The function is already imported and called with expected parameters.
[name]-solution.js The solution code with heavy commenting. Some challenges have multiple solutions. If you want the solution without comments, look in the readme.md file.
[name]-test.js - Jest tests for the solution code. You will need to rename this file to [name].test.js to run the tests.
Learning Modules/Lessons
Some lessons/modules are not challenges, they are more like mini-lessons. I don't just throw you a challenge using a new concept (Trees, Stacks, Bubble Sorts, etc) without explaining it first. I try to explain the concept and then give you a challenge to practice or implement it. So some folders will not have a challenge, just a readme file.

Running Tests
In order for the Jest tests to run, you need to rename the test file to [name].test.js. For example, if you are working on the hello-world challenge, you need to rename the hello-world-test.js file to hello-world.test.js. This is because Jest looks for files with the .test.js extension.

Run the command npm run test from the root directory and it will run all the tests.

These Don't Have to be "Challenges"
Some people, such as myself are not great at doing this stuff off the top of their head. Even though most of the code is setup as a challenge, you can certainly just follow along with the course and/or just study the solutions and learn from them.

You can use the tests to see if your code passes, but use the run files to run the code manually. This is so that you can experiment, console.log, etc.

Getting Started
Clone the repo
Run npm install
Run npm run test to run the tests. Again, you will need to rename the test files and replace the -test with .test to run the tests.
Index of Challenges/Lessons
01. Basic Challenges 1
These are mostly challenges that have to do with loops, conditionals, and string manipulation. I do not go over fundamentals like "what is a for loop". You should already know the basics of JavaScript.

Hello World Test Challenge
Get Sum Test Challenge
Calculator
Count Occurrences
Find Max Number
Title Case
Reverse String
Palindrome
Count Vowels
Remove Duplicates
02. Basic Challenges 2
These are more challenges that have to do with iteration. They are slightly harder than the first set of challenges.

FizzBuzz Array
Array Intersection
Display Likes
Find Missing Number
Find Missing Letter
Are All Characters Unique
First Non-Repeating Character
Dice Game Simulation
Format Phone Number
Validate Email
03. High Order Array Methods
The next set of challenges/lessons will have to do with high order array methods such as map, filter, reduce, sort, etc. Even though most of these can be done with a for loop, I want you to practice using these methods.

Simple Examples
Sum Of Even Squares
Calculate Total Sales
Highest Scoring Word
Valid Anagrams
HashTag Generator
Valid IPv4 Address
Analyze Car Milage
Password Validator
Find Missing Letter Refactor
04. Recursion
The next batch of challenges/lessons will have to do with recursion. We will first talk about what recursion is and then we can look at some challenges.

Recursion Intro (Count Down)
Unwinding (Sum Up To)
Reverse String Recursion
Fibonacci Sequence
Factorial
Power
Array Sum
Number Range
Flatten Array
Permutations
05. Complexity
This is more of a learning section than a challenge section. We will talk about Big O notation and how to calculate the time complexity of an algorithm. We will also talk about space complexity and how to calculate that as well. We will talk about the different types of complexity such as constant, linear, quadratic, etc.

What Is Time Complexity?
Big O Notation
Constant Time Complexity
Linear Time Complexity
Quadratic Time Complexity
Logarithmic Time Complexity
Space Complexity
Max Subarray Quadratic
Sliding Window Technique
Space Complexity
06. Hash Tables, Maps & Sets
In this section, we will start to look at data structures. We will start with a data structure called a hash table. This will include maps and sets, which are built-in JavaScript data structures that are similar to hash tables. We will also create a custom hash table class and use it in a couple challenges.

What Are Data Structures?
Hash Table Intro
Maps
Word Frequency Counter
Phone Number Directory
Anagram Grouping
Sets
Symmetric Difference
Two Sum
Longest Consecutive
Custom Hash Table
Word Instance Counter
Add getValues() Method
Add getValues() Method
07. Stacks, Queues & Linked Lists
In this section, we will look at working with data structures such as stacks, queues, and linked lists. We will also look at fast and slow pointers.

What Is A Stack?
Stack Implementation
Reverse String With Stack
Balanced Parentheses
What Is A Queue?
Queue Implementation
Reverse String With Queue
Palindrome With Queue & Stack
What Is A Linked List?
Linked List Implementation
Reverse String With Linked List
Fast & Slow Pointers
Find Middle
What Is A Doubly Linked List?
Doubly Linked List Implementation
Find Pair Sum
08. Binary Trees & Binary Search Trees & Graphs
In this section, we will look at trees and graphs. We will start with binary trees and binary search trees. We will also look at graphs and graph traversal.

What Is A Tree?
Tree Node Class
Depth First Traversal
Depth First Traversal Recursive
Breadth First Traversal
Maximum Depth
What Is A Binary Search Tree?
Binary Search Tree Implementation
Validate BST
What is a Graph?
Adjacency Matrix & Adjacency List
Graph Implementation
Graph Traversal
Graph Depth First Traversal
Graph Breadth First Traversal
09. Sorting Algorithms
In this section, we will get into sorting algorithms. We will start with bubble sort, which is very popular in interviews. We will also look at selection sort, insertion sort, merge sort, and quick sort.

What Are Sorting Algorithms?
Bubble Sort Algorithm
Bubble Sort Implementation
Insertion Sort Algorithm
Insertion Sort Implementation
Selection Sort Algorithm
Selection Sort Implementation
Merge Sort Algorithm
Merge Sort Implementation
Quick Sort Algorithm
Quick Sort Implementation
