# Homework 10 - Binary Search Trees

For this homework, you will explore writing a Binary Search Tree, and some
utility functions for the tree. You will also explore the concept of
recursion, and how it can be used to simplify your code.

## Provided Files
This project has a number of provided files. We split up your "implementation" code so it 
looks more like a real project.  The files we provided are:

* [my_bst.h](../my_bst.h) - This is the header file for your bst.  It contains the function prototypes for the functions you will implement.
* [my_bst.c](../my_bst.c) - This is the implementation file for your bst.  It contains the function definitions for the functions you will implement related to the **structure** of the bst.
* [my_bst_printer.c](../my_bst_printer.c) - This is the implementation file for your bst printer.  It contains the function definitions for the functions you will implement related to **printing** the bst. Most of this code can be copied from Lab 10 with minor modifications.
* [my_bst_util.h](../my_bst_util.h) - This is the header file for your bst utility functions.  It contains the function prototypes for the functions you will implement related to **utility** functions for the bst, such as sum, min, and max.
* [my_bst_util.c](../my_bst_util.c) - This is the implementation file for your bst utility functions.  It contains the function definitions for the functions you will implement related to **utility** functions for the bst, such as sum, min, and max.
* [bst_main.c](../bst_main.c) - This is the main file for your bst.  It contains the main function, and the code to test your bst.  You should add your tests to this file, and run it to test your bst.
* [Makefile](../Makefile) - This is the makefile for your bst.  It contains the rules to build your bst.  You should not need to modify this file, but you should look at it to see how it compiles all the files. As a reminder from the lab, to build your bst, use "make" in the directory with the Makefile.  To clean up your directory, use "make clean".


👉🏽 **Task** 👈🏽 Take time to go through the files. They should compile without  modification at this point. You will want to take this project in steps, so as you look through the files, make sure to plan out your approach to building the BST. 




## 📝 Grading Rubric




1. Learning (AG)
   * bst_add correctly adds in some simple bst configurations
   * bst exists correctly returns true for some simple bst configurations
   * bst size correctly returns the size of some simple bst configurations
   * bst is empty correctly returns true for some simple bst configurations
2. Approaching  (AG)
   *  bst_add correctly adds in some more complex bst configurations
   *  bst exists correctly returns true or false for some more complex bst configurations
   *  bst size correctly returns the size of some more complex bst configurations
3. Meets  (AG)
   *  sum works for a variety of bst configurations
   *  min works for a variety of bst configurations
   *  max works for a variety of bst configurations
   *  print inorder, postorder, and preorder work for a simple bst configuration
4. Exceeds  (MG)  
   * Reviews code for comments, style, and properly completed functions (including free)
   * Uses recursive add, find, and free
   * All questions in README.md answered correctly


AG - Auto-graded  
MG - Manually graded


## 📚 Resources
Use this section to keep the homework description shorter, and instead talk about additional resources down here (such as tools to use, websites to review, etc)