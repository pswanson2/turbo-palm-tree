# X-Team 31 Project Proposal *Password Puppy*

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

Briefly describe a problem that your team would like to solve.  
Describe at a high level a program that could solve that problem.

*People in an increasingly digital world have usernames and passwords to countless websites.
Remembering all of their credentials can be a daunting task. Our program seeks to enable
users to have a safe place to store all of their usernames and passwords so that they
never again have to click on that dreaded "Forgot your password?" button.*

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

*Password Puppy*

2. Output: Describe the output your program will produce.  Include and example format of the output produced.
It will output a list of website, username, and password pairs.


3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
Input your username and password for *Password Puppy*.


4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface.
The user interface will be a simple white background containing a two blank text boxes. The user will input their username into the first box and their password into the second box. The user's password information will appear if their username and password match. There will also be add, delete, and update buttons to add website, username, and password combinations. 
See figure 1 for an example.   


5. Types List: Break your solution idea down into units that you think can be implemented with a single class.
First we want to implement the user's array of nodes for each website, then we would implement the hashtable that holds the nodes. Once these are all working, we would then work on the graphic user interface starting with the home screen followed by the main screen once the user is logged in.


6. Name each interface or class and briefly describe its function or purpose.
HashTableADT: Interface that defines the hash table
HashTable: Data structure to hold Nodes containing each user's username and password for each website.
Node: static class in the HashTable class representing a single user's data.


## Edit and Submit this file and any figures referenced by this document.

