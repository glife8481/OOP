# Object-Oriented Programming in Java

Java programs written for my Object-Oriented Programming course at B.M.S. College of Engineering (B.E. Computer Science and Engineering). New programs are added as each topic is covered in class.

**Author:** Pranav Kulkarni

## Programs

| Program | What it models | OOP concepts |
| --- | --- | --- |
| [`Book.java`](Book.java) | Library books with ID, title, author and price | Classes and objects, constructors, methods |
| [`Student.java`](Student.java) | Student records read from the keyboard | Classes, arrays of objects, `Scanner` input |
| [`Vehicle.java`](Vehicle.java) | Parking bill for each vehicle | Classes, methods, calculations on object data |
| [`Course.java`](Course.java) | A course and an online course | Inheritance (`extends`), `super(...)` constructor calls |
| [`MediaPlayer.java`](MediaPlayer.java) | Audio and video players | Abstract classes, method overriding, runtime polymorphism |
| [`EnergySourceMain.java`](EnergySourceMain.java) | Solar and wind energy sources | Abstract methods, inheritance, dynamic method dispatch |
| [`Reservation.java`](Reservation.java) | Seat booking that rejects double bookings | Custom checked exception, `throw`/`throws`, `try`/`catch`/`finally` |
| [`array.java`](array.java) | Calculations on numbers entered by the user | Arrays, loops, `Scanner` input |
| [`Integer.java`](Integer.java) | Splits a number into integer and decimal parts | Type casting between `double` and `int` |

## Build and run

Needs JDK 17 or newer.

```bash
javac Reservation.java
java Reservation
```

Some files contain more than one class or a class whose name differs from the file name. Run the class that holds `main`, for example `javac Course.java` and then `java OnlineCourse`.

## Coming next

Interfaces, packages, collections, file handling and multithreading, as the course covers them.
