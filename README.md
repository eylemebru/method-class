# method-class
csharp
using System;

class MathOperations
{
    // Method that takes two integers as parameters
    public void PerformOperation(int num1, int num2)
    {
        // Performing a math operation on the first integer (addition) and displaying the second integer
        int result = num1 + 5; // Adds 5 to the first integer
        Console.WriteLine("The result of adding 5 to num1 is: result");
        Console.WriteLine("The second integer is: {num2}");
    }
}

class Program
{
    static void Main(string[] args)
    {
        // Creating an instance of the MathOperations class
        MathOperations math = new MathOperations();
        
        // Calling the method with two numbers
        math.PerformOperation(10, 20); // Pass numbers 10 and 20 to the method
        
        // Calling the method with parameters by name
        math.PerformOperation(num1: 15, num2: 25); // Specify the parameters by name
    }
}
