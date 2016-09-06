# lab03

## What do you think is the type of each of the following fields? 
* private int count; --int
* private Student representative; --Student
* private Server host; --Server

## What are the names of the following fields? 
* private boolean alive; --alive
* private Person tutor; --tutor
* private Game game; --game

## From what you know about the naming conventions for classes, which of the type names in the above questions would you say are class names? --I'd say Student, Server, Person, and Game are class names.

## In the following field declaration from the `TicketMachine` class  
```
private int price;
```
does it matter which order the three words appear in? Edit the TicketMachine class to try different orderings. After each change, close the editor. Does the appearance of the class diagram after each change give you a clue as to whether or not other orderings are possible? Check by pressing the Compile button to see if there is an error message. Make sure that you reinstate the original version after your experiments!
--It appears that it definitely matters what order the words are in, as I got an error message when I tried to switch them around.


## Is it always necessary to have a semicolon at the end of a field declaration? Once again, experiment via the editor. The rule you will learn here is an important one, so be sure to remember it.
-- Yes, it is always neccessary to have a semicolon.

## Write in full the declaration for a field of type `int` whose name is `status`.
-- private int status

## To what class does the following constructor belong?
```
public Student(String name)
```
--It belongs to class "Student".

## How many parameters does the following constructor have, and what are their types?
```
public Book(String title, double price)
```
-- There are two parameters, and their types are "title" and "price".

## Can you guess what types some of the `Book` class’s fields might be, from the parameters in its constructor? Can you assume anything about the names of its fields?
-- I'm guessing that the fields are "title" (which I assume is the title of the book), and "price" (which I assume is the price of the book).

## Suppose that the class `Pet` has a field called `name` that is of the type `String`. Write an assignment statement in the body of the following constructor so that the `name` field will be initialized with the value of the constructor’s parameter.
```
public Pet(String petsName)
{
name = petsName
}
```
## The following object creation will result in the constructor of the `Date` class being called. Can you write the constructor’s header?
```
new Date("March", 23, 1861)

public Date(String monthName, int dateNumber, int yearNumber)
```
Try to give meaningful names to the parameters.
