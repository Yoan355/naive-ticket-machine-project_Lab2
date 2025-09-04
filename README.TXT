Project: naive-ticket-machine
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling
   Pearson Education

It is discussed in chapter 2.

Purpose of project: To illustrate the basics of fields, constructors, and methods.
How to start this project: Create one or more TicketMachine objects.


/////////////////////Awnsers to questions in pdf////////////////////////


Q2: After we print out the ticket, the returned value is 0$


Q3: I do notice strange stuff on the machine's behaviour, even if I insert too much money
or a small amount of money, I can print out an infinite amount of tickets, even though
the minimal price I set was 350 cents.
I do not receive any refund, in fact, there isn't a mthod for a refund available.

Q5: No, there is no difference between the ticket from the new machine and the ticket
   from the old machine except for the minimal amount of money I have to insert
   which I customized myself.
   
 Q7: After changing public class TicketMachine to class public TicketMachine, The error
 In the code is "< identifier > expected" and "class,interface,enum or record expected"
 It shows us that there is infact an error in the class identifier, which makes it clear
 we swapped public and class spots.
 
 Q8: Yes it is possible to remove the word public, It does not cause any errors and everything stays the same.
 
 Q9: It is not possible to remove the word class without it giving us errors.It gave us this following error:
     "class,interface,enum or record expected".
     
 Q10: Methods:
1.public int getPrice()
2.public int getBalance()
3.public void insertMoney(int amount)
4.public void printTicket()

Constructor:

1. public TicketMachine(int cost)

Fields:

1.private int price;
2.private int balance;
3.private int total;


Q11: The two features of the constructor that make it look significantly different from the methods
of the class are that the constructor has the sanme name as the class and it has no return type.






