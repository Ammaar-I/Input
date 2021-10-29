## Input
There are many different ways to get user input. We are going to use `Scanner` class.
In order to use the class to get input, we must

1. `import java.util.Scanner;`
2. Create a Scanner object
3. Output prompt to guide user

`Scanner user = new Scanner(System.in);`

### Input Types
1. `nextInt()` reads ineger value from user 
2. `nextFloat()` reads a decimal value from user
3. `nextBoolean()` reads boolean value from user
4. `nextLine()` reads a String value

## String
A collection of characters. Strings are immutable,  which means they cannot be changed

Ex: `"My name is Mr. Nick"`

Ex: `"I have 4 dogs"`

### Constructing String Objects

We can create string object similar to primitive data types.

`String name = "Nick";`

### Concatentation of Strings

String can be added  together using an operator called concatentation. (+)

Example:

`String fristName = "Matt";`

`String lastName = "Jones";`

`String fullName = fristName + lastName;`

Example

`String id = 5`

### Comparing Strings

In Java you can compare strings using two different methods.
- `equals()` method
- `compareTo()` method

**For the equals() method:**

`string1.equals(sting2);`, this returns a boolean value, either true if the two strings are equal, or false otherwise.

Example: 

`Sting dog = "Dog";`

`Sting cat = "Cat";`

`System.out.println(dog.equals(cat));` results is false

**For the compareTo() method:**

`string1.equals(sting2);`

This method returns: 
- Returns 0 if the two strings are equal
- Returns a value less than 0 if the frist strings precedes the second strings in the dictionary 
- Returns a value greater than 0 if the second string precedes the frist sting in the dictionary

"Miles".compareTo(Ryan):

1. "Miles"

2. "Ryan"

Frist Character: "M" - "R" = 77 - 82 = -5

### Indexing Sting

Even though strings are immutable, you are able to take parts of a string to use for a new string.

**Method: subtring()**

The substing() method his two diffrerent forms:
- `string1.substring(Integer num);`
  - The frist for takes a single integer input and returns the characters of the strings from the index of the input to the end.

Example:

`String dinosaur = "Triceratops";`

`String half = dinosaur.substing(5);`

- `string1.substring(Integer num1, Integer num2);`
  - The second form takes two integer inputs and returns the characters of the string from the index of the frist input to the character before the index of the second input.
  
Example: 

`String dinosaur = "Triceratops";`

`Sting part = dinosaur.substing(2,6);`

### Other String methods

There are other string methods that are useful for you!!

String Length:

To find the length of a string, you can use the method length(). This method returns the lengthof the string as an integer.

Example:

`String name = "Nicholas";`

`int length = name.length();` returns the integer value 8.