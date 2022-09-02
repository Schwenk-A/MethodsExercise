## Exercise 1:

Write a C# program that takes user input and creates a story. Ask the user for things like a name, color, an animal, etc. Make up a story and be creative.
Hint: Use Console.ReadLine() to take user input and store the input into a variable.

Ask the user “What is your name?”
Store the input.

EXAMPLE:
```
Console.WriteLine("What is your name?"); // output
var name = Console.ReadLine(); // input
```
Record user input, for each of these. Combine all answers for a fun, short story.


EXAMPLES:

>Name: Michael
>
>Favorite Color: Blue
>
>Favorite Animal: Walrus
>
>Favorite Band: The Beatles

Extra points - turn the answers into a fun short story!
Save, commit, and push to Github


## Exercise 2:
Write different methods that use each math operator, but allows you to plug in different integers.
Calling the different methods would look like:
```
Sum(2,4) // would return 6
Multiply(10,2) // would return 20 
```

For Example:
```
namespace MethodsExercise
{
    internal class Program
    {
        static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");

            var name = Console.ReadLine();

            var result = Add(10, 20);
        }
 ```


## Challenge mode using the params keyword:
Change the functions to use the params keyword to support a range of arguments.

Sum(2,4) would return 6.

Sum(2,4,6) would return 12.

Sum(1,1,1,1,1) would return 5.

- This way we could plug in multiple different values, and the method we write will still calculate it correctly, we could add, subtract, etc - as many values as we want.

### Save, commit, and push to Github
