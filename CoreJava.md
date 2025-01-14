1. final keyword usage
   
2.
String a = "Tata";
String b = a;
a = "Birla";
b = ?

3. Java immutability - write a sample class and ensure fields are not modified from the outside

4. What's concurrentModificationException?
 
Many users are accessing same list (adding, removing and deleting the records). does java provides any out of the box solution for that?

2 ways to create a string? what's the difference ?

Q1 Overloading vs Overriding.
Q2 Java work as Pass by value or Pass by reference (It was tricky question)
Q3 Executor Service (It was tricky question)
Q4 countdownlatch vs cyclicbarrier
Q5 Types Of thread pool
Q6 Difference between Thread pool(It was tricky question)
Q7 Use of Default method
Q8 Difference between Abstract class vs Interface
Q9 Ways to create thread.
Q10 Best Approach to create Thread.
Q11 Map vs FlatMap
Q12 Parallel Stream internal working
Q13 when we choose Stream over parallel Stream (It was tricky question)
Q14 Explain completablefuture.
Q15 What is Future Object
Q16 HashMap internal working
Q17 equal and hashcode method contract
Q18 If we override only equal method, will it work. (It was tricky question)


class Test{
String name;
Int age;
Test(String name , int age){
this.name = name;
this.age = age;
} }
Class MainExp{
Main(){
Test t1= new Test(“ElonMusk”,43);
Test t2= new Test(“ElonMusk”,43);
Set<Test> set = new HashSet<>();set.add(t1);
set.add(t2);
set.size(); // Q1 what will be the size of set
//Q2 if they are not consider equal(i.e set.size() == 2) then what do we have to do to make
them equal

} }
garbage collection

Comparator vs Comparable ? explain with example? why we have two different sorting mech?

Why do  use an array to keep track of the minimum sum in a recursive function,
 and how does it help update the value within the recursive call?

7. What is a connection pool in the context of database management, 
and what are the advantages of using it?

8. How does implement a connection pool class as a singleton, 
and why is it important to provide a get connection method?

9. What is the purpose of the double-checked locking pattern in a multithreaded environment,
 and how does it prevent race conditions?

10. Why is it important to perform a null check before acquiring a synchronized block in a double-checked locking pattern?

11. Deep Cloning

12. Shallow Cloning

13. Deep cloning implementation

14. What is the use of try with resources
8. Use of finally





