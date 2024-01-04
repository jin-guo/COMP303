# COMP303 Software Design (Winter 2024)


## General Information
|   |  |
| :---: | ------------- |
| Instructor    | [Jin Guo](http://jguo-web.com/index.html)|
| Lecture Date and Time    | TR 2:35 pm - 3:55 pm | 
| Location | SADB M-1 |
| Q&A and Discussion Forum | Ed discussion (access through myCourses) |
| Instructor Office Hour | TBD (MC328)| 
 
 

## TA Office Hours  (TBD)
| Time | TA | 
| :---: | :---: |



## Description
This course provides an in-depth introduction to the discipline of software design for building realistic and high-quality software applications. It will focus on object-oriented programming techniques, and cover topics related to managing software complexity and verifying that they work as expected. It will use Java for all the code examples and assignments. However, the considerations during the design process apply in all languages for practical software development.

## Expected Outcome

After completing this course successful students should be able to:

- Properly explain and apply general Design Principles (separation of concerns, encapsulation, substitutability, interface segregation, etc.) and important Design patterns;
- Properly explain and apply design techniques such as UML Diagrams and Design by Contract;
- Effective use programming language mechanisms such as exception handling and reflection;
- Analyze and evaluate the quality of design solutions; correctly identify design smells and apply appropriate refactoring to eliminate them;
- Gain experience on software development tools such as modern IDEs, automatic documentation and testing tools, and version control system.

## Reference Material
- **Required Textbook**: 
  - [Introduction to Software Design with Java, 2nd edition (referred to as SD in the schedule)](https://link.springer.com/book/10.1007/978-3-030-97899-0). The electronic version of this book is **free** for McGill users with library access. For those who optionally want a print version, the [Paragraph Bookstore](http://paragraphbooks.com/) will stock a limited number of copies;
  - [Companion Website](https://github.com/prmr/DesignBook) for source code, exercises, and solutions.
  - [Casdoc Tool](https://cs.mcgill.ca/~martin/casdoc/). Chapter and solution code from the textbook companion website with extra in-line annotations of examples and explanations.
  
- **Other Recommended References:** 
  - [The Pragmatic Programmer (referred to as PP)](https://www.oreilly.com/library/view/the-pragmatic-programmer/9780135956977/), by David Thomas, Andrew Hunt, Addison-Wesley Professional;
  - [Effective Java (referred to as EJ)](https://www.oreilly.com/library/view/effective-java-3rd/9780134686097/), by Joshua Bloch, Addison-Wesley Professional.

- **Sample Projects:** 
  - [Inclass demos](https://github.com/jin-guo/COMP303_CodeDemos);
  - [Minesweeper](https://github.com/prmr/Minesweeper);
  - [Solitaire](https://github.com/prmr/Solitaire).

- **Diagramming Tool (and Sample Project):** 
  - [JetUML](https://github.com/prmr/JetUML/blob/master/README.md)

## Prerequisites
COMP 206 and COMP 250. Please also perform the [self assessment](https://github.com/prmr/COMP303/blob/master/Assessment.md) within the first week of the class to determine if you are ready to take this course.


## Assessment and Evaluation:
*Subject to minor adjustments*


| Evaluation Methods                         | Weight |
| ------------------------------------------ | ------ |
| Participation              | 5%    |
| Lab Tests         | 20%    |
| Midterm Exam | 25%    |
| Final Exam                                 | 50%    |


- Accommodation 1 (exams): If the grade of the final exam exceeds that of the midterm, the grade of the final exam will replace the grade of the midterm. This accommodation covers the case where students are unable to write the midterm.
- Accommodation 2 (labs): The grade of the lab tests will be the average of the grades of the best lab tests (with the one least performing lab test dropped). This accommodation covers the case where students are unable to complete a lab test.

- Our TA will try their best to support your learning. But considering this is a big class – many of you will have similar questions or concerns and many of you have will answers to other people’s questions, we encourage you to discuss your questions about the lectures and exercises online;
- Every module of the lecture will come with [exercises provided by the textbook](https://github.com/prmr/DesignBook). Those are for your practice and will not be graded. Instead, your practical skills will be evaluated through a series of design assignments and lab tests throughout the semester. 
- The `lab tests` complement the exercises and will be in person. During each lab test, you will be asked to complete a series of tasks given by our TAs. You are responsible to book the slot of each lab test in advance with the TAs. 
- Any form of plagiarism, cheating is strictly banned throughout the semester. Integrity is crucial to this course and your future career. Any violation against academic integrity will be taken very seriously. For more information, please refer [here](https://www.mcgill.ca/students/srr/academicrights/integrity).


## Schedule (Tentative)
*Subject to adjustments*

| Lecture | Date | Content | Reading | Exercise | 
| :---: |:---:| :---: | :---: | :---: | 
|1	|  4 Jan  | Introduction | SD: Chapter 1| | 
|2	|  9 Jan | Encapsulation - 1 | SD: Chapter 2 | [Exercise 0](m0.md) <br> [Exercise 1-5 in SD: Chapter 2](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter2.md) | 
|3	|  11 Jan | Encapsulation - 2 | EJ: Item 15-17, [Tutorial on Enum Types](https://docs.oracle.com/javase/tutorial/java/javaOO/enum.html)  | [Exercise 6-9 in SD: Chapter 2 <br> (omit the exercise related to Design by Contract and Assertion which will be introduced later in the course)](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter2.md) | 
|4	|  16 Jan | Types and Polymorphism - 1 | SD: Chapter 3 | [Exercise 1-2 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) | 
|5	|  18 Jan | Types and Polymorphism - 2 | EJ: Item 14 | [Exercise 3-6 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) | 
|6	|  23 Jan | No Class | | | 
|7	|  25 Jan | Types and Polymorphism - 3 | | [Exercise 7-12 in SD: Chapter 3](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter3.md) | 
|8	|  30 Jan | Object State - 1 | SD: Chapter 4, EJ: Item 10, 11 | [Exercise 1-5 in SD: Chapter 4](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter4.md) | | 
|9	|  1 Feb | Object State - 2 | EJ: Item 1, 3 | [Exercise 6-11 in SD: Chapter 4](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter4.md) | 
|10	|  6 Feb  | Design for Robustness - 1 | PP: Topic 23, 24, 25|  | 
|11  | 8 Feb | Design for Robustness - 2 | EJ: Item 69 - 72 | | 
|12	| 13 Feb | Unit Testing - 1 | SD: Chapter 5  | 
|13	|  15 Feb | Unit Testing - 2| SD: Chapter 5 | [Exercise 1-11 in SD: Chapter 5](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter5.md) | 
|14	|  20 Feb | Content Review | | | 
|15	|  22 Feb | Composition - 1 | SD: Chapter 6 | | 
|16	|  27 Feb | Composition - 2 | SD: Chapter 6 |[Exercise 1-5 in SD: Chapter 6](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter6.md) | 
|17	|  29 Feb | Composition - 3 | SD: Chapter 6 | [Exercise 6-19 in SD: Chapter 6](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter6.md) | | 
|**	|  5 Mar | READING WEEK | | | 
|**	|  7 Mar | READING WEEK | | | 
|18	|  12 Mar | TBD | Midterm  | | 
|19	|  14 Mar | Inheritance - 1 | SD: Chapter 7, EJ:Item 19,20| [Exercise 1-5 in SD: Chapter 7](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter7.md) |  
|20	|  19 Mar | Content Review | | |  
|21	|  21 Mar |  Inheritance - 2  | SD: Chapter 7, EJ:Item 18 | [Exercise 6-10 in SD: Chapter 7](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter7.md) | | 
|22	|  26 Mar |  Inversion of Control - 1 | SD: Chapter 8 | [Exercise 1-7 in SD: Chapter 8](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter8.md) | | 
|23 |  28 Mar | Inversion of Control - 2 | SD: Chapter 8 | [Exercise 9-11 in SD: Chapter 8](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter8.md)  | | 
|24 |  2 Apr | Inversion of Control - 3 | SD: Chapter 8 | [Exercise 12-13 in SD: Chapter 8](https://github.com/prmr/DesignBook/blob/master/exercises/e-chapter8.md)  | | 
|25 |  4 Apr | Concurrency - 1 |[Java Concurrency in Practice Chapter 1,2,3](https://learning.oreilly.com/library/view/java-concurrency-in/0321349601/)| | 
|26 |  9 Apr | Concurrency - 2 and Wrap Up | |



## Lab Test (TBD)

| Test | Start Date | End Date | Scope | Note | 
| :---: |:---:| :---: | :---: | :---: | 



