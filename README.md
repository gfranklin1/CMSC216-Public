# CMSC216 - Intro to Computer Systems

Welcome to my repository for ```CMSC216: Introduction to Computer Systems``` at the ```University of Maryland, College Park```. This repository includes a summary and the grade received for the projects and exercises I completed throughout this course. Due to university policies, the code for these projects is not publicly available. If you are an employer or have a legitimate request to view the code, please contact me directly.

## Projects and Exercises

### Project 1: **Grades Calculator**
**Description:**  
- Developed a command-line program in C for calculating and managing assignment grades based on user inputs.
- Reads user input assignment details, including scores, weights, and days late, and calculates a numeric score after applying penalties for late submissions.
- Handles dropping the lowest scores based on user specifications.
- Can optionally provide statistical information about the grades, such as the mean and standard deviation. 

**Grade:** 100/100

---

### Project 2: **Document Manager**
**Description:**  
- Developed a C library for managing a document structure, allowing users to create, modify, and print documents composed of multiple paragraphs and lines.
- Implemented essential functionalities, including initializing documents, adding/removing paragraphs and lines, loading content from an array, and replacing/highlighting/removing text within the document.

**Grade:** 95/100
- Passed 21/22 tests.

---

### Project 3: **User Interface**
**Description:**  
- Developed a text-based user interface in C for the document management system implemented in Project 2.
- Allows users to interact with documents by adding paragraphs and lines, removing lines, and highlighting or replacing text through command-line input.
- Implemented additional functionalities like loading and saving documents from/to files, appending lines, and resetting documents to their initial state.

**Grade:** 96/100
- Passed 32/34 tests.

---

### Project 4: **Calendar**
**Description:**  
- Implemented a calendar application in C using dynamic memory allocation, linked lists, and function pointers.
- The application supports functionalities such as:
  - Adding, removing, and listing events for specific dates.
  - Dynamic memory management to handle varying numbers of events efficiently.
- Focused on developing robust data structures for storing calendar events and ensuring proper memory allocation and deallocation.

**Grade:** 95/100
- Passed every test, but lost 5 points for code duplication.

---

### Project 5: **Assembly Language Programming**
**Description:**  
- Developed AVR assembly routines to mirror the behavior of provided C functions.
- Implemented the following routines:
  - **Palindrome Check**: Verified if a string is the same forward and backward using pointer-based memory access.
  - **Fibonacci Calculation**: Recursively computed the nth Fibonacci number.
  - **Integer Square Root**: Calculated square roots using a bitwise algorithm with logical shift instructions.
  - **Reverse Prefix Sum**: Transformed an array recursively by adding each element to the sum of subsequent elements.
- Focused on proper register usage, following callee-save and caller-save conventions.
- Ensured code clarity with extensive comments and clean formatting.

**Grade:** [Grade Received]

---

### Project 6: **Project Title**
**Description:**  
A brief description of what this project entailed, key components, and any significant achievements or challenges faced.

**Grade:** [Grade Received]

---

### Exercise 1: **Draw Figures**
**Description:**  
- Developed a command-line program in C that allows users to draw geometric shapes based on their input.
- Users can choose to draw a rectangle or a triangle:
  - **Rectangle:** Drawn using two characters, where alternate rows use different characters. Users provide width and length for the rectangle.
  - **Triangle:** Drawn using two characters with random placement determined by a seed value. Users provide the size of the triangle and a random seed for the pattern.
- Includes input validation to ensure valid values for characters and dimensions.

**Grade:** 100/100

---

### Exercise 2: **Text Manipulation**
**Description:**  
- Implemented two functions in C: `remove_spaces` and `center`, aimed at practicing string and pointer manipulation.
  - **remove_spaces**: This function removes leading and trailing spaces from a given string and places the cleaned string in the result parameter.
  - **center**: This function centers a given string within a specified width by calculating the required number of spaces on both sides.
- This implementation shows rigorous specifications regarding input validation, string handling, and proper null-termination, ensuring the code adheres to good programming style.

**Grade:** 100/100

---

### Exercise 3: **Photo Album**
**Description:**  
- Implemented a dynamic photo album application in C, practicing dynamic memory allocation.
- The application supports functionalities such as:
  - Creating and printing photos with descriptions.
  - Initializing and printing albums.
  - Adding photos to an album while ensuring memory management best practices are followed.
- Focused on ensuring proper memory allocation and deallocation for the photo and album structures.
  
**Grade:** 100/100

---

### Exercise 4: **AVR Assembly Basics**
**Description:**  
- Implemented several assembly functions to practice basic operations and familiarize with assembly language syntax and calling conventions.
- Functions implemented:
  - **Five**: Returns the constant value `5` as a `uint16_t`.
  - **Max**: Returns the greater of two `uint8_t` values passed as arguments.
  - **Strlen**: Computes the length of a string (given as a pointer) and returns it as a `uint16_t`.
- Focused on using registers directly, handling loads and stores, and performing branching and looping operations.

**Grade:** 100/100

---

### Exercise 5: **Shell Jr ("Shellito")**
**Description:**  
- Implemented a basic shell program in C.
- Supports built-in commands and Linux commands with `fork()` and `execvp()`.
- Key features:
  - **Build-in Commands**
    - `exit`: Exit the shell.
    - `cd`: Change the current directory.
  - **Linux Commands**
    - Executes commands such as `pwd`, and `ls` by forking a child process.

**Grade:** 100/100

---

### Exercise 6: **Exercise Title**
**Description:**  
A brief description of the exercise, including objectives and outcomes.

**Grade:** [Grade Received]

---

## Disclaimer

**## CONTACT ME IF YOU WOULD LIKE TO SEE THE CODE, UNDER UNIVERSITY RULES I AM NOT ALLOWED TO POST PUBLICLY ON HERE**

If you are interested in reviewing the code or have any questions related to the projects, please reach out to me directly.
