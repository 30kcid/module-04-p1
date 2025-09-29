using System;

public class Math
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Let's do some math!");
        Console.WriteLine("Give me a number:");
        string firstText = Console.ReadLine();

        Console.WriteLine("Give me another number:");
        string secondText = Console.ReadLine();

        try
        {
            // Try to change the words into numbers
            int num1 = Convert.ToInt32(firstText);
            int num2 = Convert.ToInt32(secondText);

            // Do the math!
            int result = num1 / num2;

            // Tell us the answer
            Console.WriteLine("The answer is " + result);
        }
        catch
        {
            // If something goes wrong, tell us it's broken
            Console.WriteLine("Uh oh! Something went wrong. Maybe you used a word instead of a number, or you tried to divide by zero.");
        }
    }
}
