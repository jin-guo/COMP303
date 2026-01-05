# COMP303 Software Design (Winter 2026)


## General Information
|   |  |
| :---: | ------------- |
| Instructor    | [Jin Guo](https://cs.mcgill.ca/~jguo/)|
| Lecture Date and Time    | TR 11:35 pm - 12:55 pm |
| Location | SADB M-1 |
| Q&A and Discussion Forum | Ed discussion (access through myCourses) |
| Instructor Office Hour | Thursdays 9-10am |
 
 

## TA Office Hours  (TBD)
| Day of the Week | Time | 
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
  - [Introduction to Software Design with Java, Third edition (referred to as SD in the schedule)](https://link.springer.com/book/10.1007/978-3-032-11821-9). The electronic version of this book is **free** for McGill users with library access. For those who optionally want a print version, the [Paragraph Bookstore](http://paragraphbooks.com/) will stock a limited number of copies;
  - [Companion Website](https://github.com/prmr/DesignBook) for source code, exercises, and solutions.
  - [Addtional Examples](https://codesample.info/)). Sample code from the textbook companion website with extra in-line annotations of examples, explanations, and best practices.
  
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
- Accommodation 2 (labs): The grade of the lab tests will be the average of the grades of the best lab tests with the one least performing lab test dropped. This accommodation covers the case where students are unable to complete a lab test.
- Accommodation 3 (participation): Similar to the lab, one missing participation input will be dropped when calculating the participation grade. This accommodation covers the case where students are unable to attend the class.

- Our TA will try their best to support your learning. But considering this is a big class – many of you will have similar questions or concerns and many of you have will answers to other people’s questions, we encourage you to discuss your questions about the lectures and exercises online;
- Every module of the lecture will come with [exercises provided by the textbook](https://github.com/prmr/DesignBook). Those are for your practice and will not be graded. Instead, your practical skills will be evaluated through a series of design assignments and lab tests throughout the semester.
- The `lab tests` complement the exercises and will be in person. During each lab test, you will be asked to complete a series of tasks given by our TAs. You are responsible to book the slot of each lab test in advance with the TAs.
- Any form of plagiarism, cheating is strictly banned throughout the semester. Integrity is crucial to this course and your future career. Any violation against academic integrity will be taken very seriously. For more information, please refer [here](https://www.mcgill.ca/students/srr/academicrights/integrity).


## Schedule (Tentative)
*Subject to adjustments*

| Lecture | Date | Content | Reading | Exercise | 
| :---: |:---:| :---: | :---: | :---: | 
|1	|  6 Jan  | Introduction | SD: Chapter 1| [Exercise 0](m0.md)| 
|2	|  8 Jan | Encapsulation - 1 | SD: Chapter 2 | | 
|3	|  13 Jan | Encapsulation - 2 | EJ: Item 15-17, [Tutorial on Enum Types](https://docs.oracle.com/javase/tutorial/java/javaOO/enum.html)  | | 
|4	|  15 Jan | Types and Polymorphism - 1 | SD: Chapter 3 | | 
|5	|  20 Jan | Types and Polymorphism - 2 | EJ: Item 14 | | 
|6	|  22 Jan | Types and Polymorphism - 3 | | |  
|7	|  27 Jan | Object State - 1 | SD: Chapter 4, EJ: Item 10, 11 | | | 
|8	|  29 Jan | Object State - 2 | EJ: Item 1, 3 | | 
|9	|  3 Feb | Design for Robustness - 1 | PP: Topic 23, 24, 25|  | 
|10	|  5 Feb  | Design for Robustness - 2 | EJ: Item 69 - 72 | | 
|11  | 10 Feb | Unit Testing - 1 | SD: Chapter 5  | 
|12	| 12 Feb | Unit Testing - 2| SD: Chapter 5 | | 
|13	|  17 Feb | Composition - 1 | SD: Chapter 6 | | 
|14	|  19 Feb | Composition - 2 | SD: Chapter 6 | | 
|15	|  24 Feb | Composition - 3 | SD: Chapter 6 | | | 
|16	|  26 Feb | Content Review | |
|**	|  3 Mar | READING WEEK | | | 
|**	|  5 Mar | READING WEEK | | | 
|17	|  10 Mar (Location: SABD 2/36, SABD M-1, SABD 1/12, and ENGTR 0100, Time: 6-8:15pm) | Midterm  | | 
|18	|  12 Mar | Inheritance - 1 | SD: Chapter 7, EJ:Item 19,20| |  
|19	|  17 Mar | Inheritance - 2  | SD: Chapter 7, EJ:Item 18 | | |
|20	|  19 Mar | Inversion of Control - 1 | SD: Chapter 8 | | | 
|21	|  24 Mar | Inversion of Control - 2 | SD: Chapter 8 | | | 
|22 |  26 Mar | Inversion of Control - 3 | SD: Chapter 8 | | | 
|23 |  31 Mar | TBD | | 
|24 |  2 Apr | TBD | |
|25 |  7 Apr | TBD | |
|26 |  9 Apr | Content Review | |



## Lab Test (Tentative)

| Test | Start Date | End Date | Scope | Note | 
| :---: |:---:| :---: | :---: | :---: | 
|Lab Test Mock Up| 14 Jan| 16 Jan | Warm Up||
|Lab Test 1|19 Jan|30 Jan|Encapsulation||
|Lab Test 2|9 Feb|20 Feb|Types and Polymorphism, Object State||
|Lab Test 3|16 Mar|27 Mar|Design for Robustness, Unit Testing, Composition|
|Lab Test 4|30 Mar|14 Apr|Inheritance, Inversion of Control|No lab test on 3 Apr and 6 Apr|


