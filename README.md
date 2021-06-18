# CMSC-21-Blogs

# Week 1

Maintaining huge complex data is difficult to overcome. That is why functions and structures are an important part when writing the logic of a program. Using these C features will help to debug the program easily. This week's topic is just a review for me because I already had sight of these in CMSC 11. 

Functions
When using functions, I always imagine that it is a magic box that transforms the input data into the desired output. 

Recursions
I had a lot of trouble understanding recursions at first. But after watching Neso Academy's youtube video about it, I realized that it was the easiest topic this week. I also made a habit of creating some diagrams first to visualize how the recursion will happen.

Insert video link

Structures
Last semester, I had trouble understanding this topic because I do not have an idea how to pass structure values in functions. I've watched tons of other youtube videos, but I still don't get how it works with arrays and functions. I'm looking forward to learn more about it along the way of this course.



# Week 2

Before this topic was introduced, I thought that there are only one-dimensional arrays in writing a code. I realized that it is inconvenient to use when implementing a relational database (ex. grades of students). Multidimensional arrays are like egg trays. It collects elements of the same type, and it forms a table with rows and columns.

Tic-tac-toe
The first part of my program checks if the inputs for rows and columns are valid. Only numbers 1-3 are allowed because there are only three rows and three columns in the tic-tac-toe. Then, it checks if the dimension entered was occupied. If not, then it checks the horizontal, vertical, and diagonal of the table to know if there is a winner. 

I decided to write most of the program inside the main instead of creating a function because I am not familiar with passing and keeping the values. I tried creating a function for printing the table and XOs, but it did not go as I planned because the table only prints one letter.

In printing the table, I did not bother to copy exactly what the example displays. I only cared about how the main game will run.

Object Counting
This may be the most challenging exercise that I have encountered so far. I've watched videos so I can make my own logic, but it did not help. Fortunately, a consultation class was held, and I get to witness a live coding session by sir Eli. 

The key logic here is to group the neighbors of a pixel. When it encounters a pixel, all eight neighbors are individually checked. Then, the neighbor pixels (and their neighbors) are then set to the current value. 



# Week 3 and Week 4

I'm actually excited because I had trouble implementing structures last semester. But, it turns out to be the most exhausting week for me (especially the snakes and ladders part) :kekw:

Sorting
I didn't really have a hard time programming this because we've been practised with a lot of sorting problems last semester. Fortunately, I still have a copy of my notes, and I used it to do this exercise.

Snakes and Ladders
I can definitely say that this is the most challenging machine problem that I have encountered in this course. I was actually disappointed with myself when I learned that my coursemates did this in less than a day because I finished mine in like four days. 

It took me that much time because I was unaware that I did not have complete knowledge about passing by values and passing by references. I have no idea why it was not discussed last semester and this semester too. I didn't know that it was my problem until I posted my situation in a forum. I just hope that there is a section about pass-by-values and pass-by-reference in the module. It would've been easy for me to do passing inputs between structures and functions if I know this earlier. Luckily, there is a Facebook page of CMSC 21 from UPLB that has a lecture video about passing parameters in C. After learning about parameters, it became easy for me to do this exercise. 

My snakes and ladders program does not actually look like the example flow that was posted. I focused more on how the main game will be implemented and not how the snakes and ladders were printed.

Programs operate on memory that has been allotted to them. They can be larger or smaller, depending on the program's requirements. Variables are like boxes in a big warehouse, if you think about it. The position where the box is located, say aisle 59 on the third shelf, is your reference. It just tells you where to seek for the information you need, which is your data. Now pointers do the same way. Pointers acts as if it were a street address. It's supposed to point to a person's actual residence. It's not a fictitious address, but their genuine address. 



# Week 5

I've only dealt with static memory allocation before, and I think it is fascinating that there is an option to allocate memory dynamically. Variables allocated on the stack are stored directly in memory, which is very fast to access, and its allocation is handled when the program is compiled. The problem with the stack is that it is not advantageous when conserving the computer's memory because the compiler will set the size and storage. Unlike in memory from the heap, the exact amount of space does not have to be known by the compiler.  

Fractions
I was confused at first because I was trying to implement malloc in any parts of the code. Then, I realized that the program does not necessarily need to have a dynamic memory allocation. It was late for me to notice that there was no such instructions like it.

Last weeks 3 and 4, I was actually questioning the need to use pointers in doing the two exercises. And now it made more sense to me because I got to understand why we really need to practice pointers. I am uncomfortable using it at first, but I am certain that I will eventually get used to it. Pointers are essential for dynamic memory allocation. Malloc, a built-in function, is used to dynamically allocate memory to pointers. This function takes the amount of memory required for the pointer as an input, and malloc allocates that amount of memory to the pointer variable. Thus, dynamic memory allocation is more practical because we can use it to grow and shrink the storage or space depending on the requirement.



# Week 6 and Week 7

Last week, I learned about the difference between using memory from the stack and memory from the heap. Their main difference is the flexibility of the size during runtime. Now, we can also use this comparison to differentiate array and linked lists. An array's size is fixed. It is difficult to change the size of an array after it has been created since we must know its size at runtime. Linked lists, on the other hand, are dynamic in nature. As a result, we can modify their size as needed.

I have watched many youtube lectures about lists. I learned that there are other types, such as doubly-linked lists and circular linked lists, but I learned that our course focused mostly on singly-linked lists. Lists were the most challenging topic for me in the whole course. Until now, I still haven't fully grasped the concept of this. However, I believe that I will eventually learn more about this because it is the most used data structure. 



# Week 8

File handling was a fun topic! In programming, we may need a specific piece of input data to be generated multiple times. It is not always sufficient to just display data on the console. The data to be displayed may be large, and only a limited amount of data may be displayed on the console; additionally, because memory is volatile, it is hard to restore programmatically created data repeatedly. If we need to save something, we can do so on the local file system, which is volatile and accessible at any time. This necessitates the use of file management in C. In simple terms, it provides a system for collecting a program's output in a file and then performing numerous operations on it. It's a really coool topic.

Sequential Access to a data file indicates that the computer system reads or writes data to the file in a logical order, commencing at the beginning and working its way through the file one step at a time. Random Access to a file, on the other hand, indicates that the computer system can read or write data from any location in the data file. This process is also known as "Direct Access" since the computer system knows where the data is stored (thanks to Indexing) and so reads it "directly."

There are only three basic modes to remember when opening different file opening modes:  r for reading, w for writing, and a for append. Then, we add a plus (+) sign for updating the file. And adding "b" when you want to open it in a binary file.



# Week 9-11

I was worried when I knew that we were going to study another programming language because I was not ready yet. But after reading the module, I learned that it was not that different from C. C++ is actually an increment of C. That is why I expect that it will be better than C. 

My intuitions were not wrong because I realized that the basic functions/commands of C++ are better than C. For example, the use of cout and cin instead of putting printf and parenthesis. The use of arrows,<< and >>, can also be self-explanatory or common sense.

I have yet to familiarize myself with file reading in C++.  File handling in C++ almost looks like file handling functions in C. It uses the same words except that there are dots in C++ (example: fopen in C is f.open in C++).

Classes are a cool feature of C++ because they are like structs, but they carry functions that can act on itself. It's a user-defined data type with its own set of data members and member functions that can be accessed and used by establishing a class instance.



# Week 12

Although I am still confused about code reuse, I can definitely say that it is useful. The thing about studying a new language is that new concepts are being introduced, which seems to be complicated at first. 

The C++ classes can be utilized in a number of different ways. Once a class has been written and tested, it can be modified to meet the needs of another programmer. This is accomplished primarily by creating new classes that reuse the properties of existing ones. That is why code reuse is an essential function in C++.

Overall, I find code reuse interesting, and I'm looking forward to learning more about this topic.



# Week 13

Polymorphism is a cool and interesting topic. Polymorphism refers to the fact that something exists in multiple forms. Polymorphism, in simple terms, is the ability of a message to be displayed in multiple formats. A real-life example of polymorphism is when a human in a society have distinct characteristics at the same time. For example, a man is a father, a spouse, and a worker in a company. As a result, the same person behaves differently in different settings. I think this topic is challenging. I believe that I need more beginner practice in order to fully understand how to use this in complicated or huge program writing.
