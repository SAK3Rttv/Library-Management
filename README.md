
# Data Structure and Algorithm Project

Library management system is a simple application to be built using the Balanced Binary Search Tree
(TreeMap) in Java.

## Information

Programming language: Java

Compiler: javac 1.8.0_301

Program: Simple Library Management System

## Installing

- Prefer to use [Apache NetBeans IDE 13](https://netbeans.apache.org/download/nb13/nb13.html).
- You should have JDK FX , I prefer to use zulu18.28.13 of JDK 18.0 , you can download it [here](https://cdn.azul.com/zulu/bin/zulu18.32.13-ca-fx-jdk18.0.2.1-win_x64.zip).
- Import .zip project file to your software programming.

## Important notes

- Project based on TreeMap bulit in java and HashMap.
- Use String title of Book as Key of TreeMap (It's not the best).
- Use HashMap to link between String title and ID of Book.
- Give the user a listener to buy book then using getBook for TreeMap.
- Used Json File to store Data , but purchased books and dates not saved in file.


## Java Packages

### librarymanagement  package

- **Register.java**
```
1.Contains all the functions needed to handle people trying to log in to the system.

2.Have most of relations between classes such as booksHash , dateHash , treeBook.

```

- **TreeBook.java**
```
This Class contains all the functions necessary to handle the basic operations that
will be available to be performed on books stored within the system,
as follows:
           ❑ Add a book into The Books Tree.
           ❑ Delete a Specified book from The Books Tree.
           ❑ Edit The information of a Specified book from The Books Tree.
           ❑ Get a book from The Books Tree.
```


- **saveBooksData.java**
```
This Class contains all the functions necessary to handle the The process of saving the 
new Books, using Json file including the processes of modification, Deletion and addition
to this file.
```

- **saveUsersData.java**
```
This Class contains all the functions necessary to handle the The process of saving the
users inside the Json file, and it also includes the processes of modification and 
addition to this file.
```


## Participants
*This is a pair project (a team of 2 students) who are as follows:*

  - **Abdullah Ahmed Muhaisen** - *120201347*
  - **Hasan Younis Sammour** -    *120201047*



## responsibilities and the timeline
We divided the project into sections, taking into account the strengths and weaknesses

of each of us, and the division was as follows:

- **Book and User Classes:** Written by Hasan Sammour in (18/12/2022).

- **GUI Handeling:** Written by Abdullah Muhisen (Between 20/12/2022 and 24/12/2022)

- **Other classes** TreeMap and HashMap are used to make the functions we need to
    handle with the Basic Operation that our system will handle with.

It was written in cooperation between the two students, as we were meeting
during the period from 18/12/2022 to 28/12/2022 to consult, put forward ideas,
and cover the weaknesses of each of us, either at the university or by communicating
on WhatsApp.

### Notes
* Some modifications and reforms were added to the codes during
  the exams period by the student Abdullah Muhaisen,
  to bring you the Program that is in your hands.


* We met again to discuss the amendments that were made during
  the exams period on Wednesday 11/1/2023 and two days later
  to bring you the Program that is in your hands.
  we started preparing the (README.md) file that you have now
  , and then handing over the project.