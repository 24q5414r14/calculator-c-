# calculator-c- 
using System;
class program
{
    static void Main()
    {
        Console.WriteLine("Calculator");
        int Num1 = int.Parse(Console.ReadLine());
        string operation = Console.ReadLine(); // cuz i want to make it like an actual calculator
        int Num2 = int.Parse(Console.ReadLine());
        double sum1 = 0;
        if (operation == "+")
        {
             sum1 = Num1 + Num2;
        }
        else if (operation == "-")
        {
             sum1 = Num1 - Num2;
        }
        else if (operation == "*")
        {
             sum1 = Num1 * Num2;
        }
        else if (operation == "/")
        {
             sum1 = Num1 / Num2;
        }
        else
        {
            Console.WriteLine("you used an invalid operator");
        }
        Console.WriteLine(sum1);

    }
}
