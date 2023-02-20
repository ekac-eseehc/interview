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
