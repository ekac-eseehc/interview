# JAVA
## what is JVM?
## why is Java called the 'Platform Indpenent Pragraming Language'?
> * JVM - byte code executor , platform dependent
> * Cross Platform - write once , run anywhere ( `WORA` )

---

## what is the diffrence among JVM , JRE and JDK?
> * JVM - byte code executor
> * JRE - Runtime Environment , JVM + Class Loader + Bytecode Verifier
> * JDK - JRE + tool set

---

## what is Autoboxing and unboxing?
> * autoboxing - complier automatically converts primitive to wrapper object
> * unboxing - complier automatically converts wrapper object to primitive data let developers write cleaner code , make it easier to read
> * J2SE5 ↑

---

## what is memory structure for Java Stack and Heap?
> * Stack - light weight ( primitive data , reference )
> * Heap - heavy weight ( object ) , Garbage Collection

---

## what is the diffrence between String and StringBuffer?
> * String - Immutable
> * StringBuffer - Mutable , synchronous
> * StringBuilder - Mutable , Performance ( speed ↑ non-synchronous )

---

## what is the function over-riding and over loading in Java?
> | over-riding | over-loading |
> | :--: | :--: |
> | inheritance | normally within same class | 
> | parameter must be same | parameter must be diffrent |
> | return type same or subclass | return type same or diffrent |

---

## what is the diffrence between creating String as new() and lieral?
> * new() generates String object in heap memory
> * String literal generates in String Pool , reusable heap memory
> * == operator comperes String references
> * equals() method compares String contents

---

## what is the 'static' keyword means?
> * initialized when the class is first loaded
> * class level access , accessible before creating object
> * static variables , static methods

---

## what is the diffrence between abstract class and interface using for?
> | abstract class | interface |
> | :--: | :--: |
> | single inheritance | multiple implementations |
> | all access modifier | only public |
> | variables , constants | only constants |
> | abstract methods , concrete methods | only abstract methods |

---

## what is Java Exception?
> * Exception - Unexpected situation , can be hardled
> * Error - Server exeception
> * Exception Handling
>   + try / catch
>   + throws

---

## what is diffrence among errors , unchecked exception and checked exception ?
> * checked exception - ( compile time , IDE ) IOException , SQLException
> * unchecked exception - ( runtime ) NullPointerException , ArrayIndexOutOfBoundException
> * error - ( secere exception ) OutOfMemory 

---

## what is the diffrence between throw and throws in Java Exception Handling?
> * throws
>   + declare exception class name at method signature
>   + single or multiple exception throws
> * thorw
>   + create an exception object and throw it explicitly
>   + within method
>   + single exception throw

---

## what is the diffrence between byte stream
> | byte stream | character stream |
> | :--: | :--: |
> | reading / writing of any bytes , row data | reading / writing of charcters , text |
> | contains 8 bits | contains 16 bits unicode |
> | InputStream / OutputStream classes | Reader / Writer classes |

---

## what will happen if you call System.out on try or catch block?
## will finally block execute?
> * finally block is execute regardless of error condition
> * will not execute when is meets 'System.exit()'
> * will execute even with 'return' statement 

---

## what is the diffrence between ArrayList and LinkedList?
> * Vector
>   + sysnchronised elements , huge size increase
> * ArrayList
>   + better for random accessing elements by index , slow for add / remove 
> * LinkedList
>   + large number of add / remove operations but rarely random access of elements

---

## Explain the diffrence between Enumeration and Iterator
> * Enumeration
>   + a few Collection support
>   + Snap-shot
> * Iterator
>   + all Collection support
>   + Fil-fast
>   + remove() method

---

## what is the use of the 'SimpleDateFormat' and how can you use it to display system format?
> * flexible date & time format
> * using standard pattern
> * format() & parse method

---

## what is the marker interface in Java?
> * No constants or methods , empty body , called as a Tag interface
> * Indicate special function to compiler or JVM
> * Can be replaced with annotation from Java 5
>   + ex) Junit class @Test

---

## Explain diffrent ways of creating thread
> * Java supports multi thead
> * shard resource , deadlock
> * extends Thread
> * implements Runnable (Referable)

---

## What is deadlock?
> * Situation where multiple threads are blocked forever
> * Ways to prevent a deadlock
>   + Avoid having more than one lock
>   + Avoid nested locks
>   + Lock order
>   + Single thread

---

## What if the static modifier is removed from main method?
> * Starting point of program
> * it doesn't work without 'static' modifier
> * `static public` void main()
> * public static `final` void main()

---

## What is the advantage of PreparedStatement over Statement?
> * Statement is good for one time execution such as DDL statement
> * preparedStatement executes parameterised query
> * Faster than statement
> * Better in security aspect
> * CallableStatement triggers stored procedures or functions in DB

---

## What is basic principle of RMI architecture?
> * method invocationin distributed environments
> * RMI Server registers remote object by bind() to RMI Registry
> * centralise complicated business logic at server
> * enable thin client

---

## What are the steps in the JDBC connection?
> * javaAPI to connect and execute query with databases
> * Load Driver & Establish the connection
> * Create a Statement & Execute a query
> * Process the result as ResultSet

---

## How can we store and retrieve images from the database?
> | Disc approach | Database approach |
> | :--: | :--: |
> | save images on disc | save images in database |
> | Image size is not small | Image size is small |
> | setString(FILE_PATH) | setBinaryStream() |
> | much faster | slow performance |
> | multiple datavases share | only one database uses |