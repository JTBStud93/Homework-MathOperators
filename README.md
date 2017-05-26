# Homework-MathOperators
Watch read and practice from the module: Variables and Math Operators. Write your understanding of the topic using comments and examples (at least 10 examples) to the instructor and describe them in your own words to the best of your knowledge. Put your work to GIT. Submit the GIT url to canvas. 


The following information is provided by TutorialsPoint.com
https://www.tutorialspoint.com/csharp/csharp_operators.htm


Assume variable "A" holds 10, & variable "B" holds 20.


// 1) + (Add) ... A + B = 30

The "+" is used to combine the numbers (with their values) togehter.

// 2) - (Subtract) ... A - B = -10

The "-" is used to take a number, and decrease (minus) it with another number to obtain a new value.

// 3) * (Multiply) ... A * B = 200

The "Asterik" is used to duplicate one number by the amount of another; i.e. 20 + 20 + 20 + 20 + 20 + 20 + 20 + 20 + 20 + 20 = 200, "Ten 20s (or Twenty 10s) added together make 200."

// 4) / (Divide) ... B / A = 2

The / splits the "numerator by the de-numerator". i.e. 10 can go into 20, 2 times.

// 5) ++ (Increment) ... A++ = 11 OR B++ = 21

This operator simply increases the number by 1.

// 6) -- (Decrement) ... A-- = 9 OR B-- = 19

This operator simply decreases the number by 1.

// 7) = (Assignment) ... C = A + B; The value of A + B is "assigned" to the value of C.

This single equal sign is used to assign one thing to something else; i.e. int myint = 5;

// 8) == (Equality Check) ... A == B are not equal, therefore, it is not true.

Two equal signs together are used to compare one thing to another; if they are the same, then they are true; but if not, then they are false.

// 9) > (Greater Than) ... A > B is false, 10 is not greater than 20.

This operator determines if the number on the left is higher than the number on the right, if it is higher, then it is true.

// 10) < (Less Than) ... A < B is true, 10 is less than 20.

This operator determines if the number on the left is lower than the number on the right, if it is lower, then it is true.

using System;
namespace OperatorsAppl
{

  class Program
  {
  
    static void Main(string[] args)
    {
      int A = 10;
      int B = 20;
      int C;
      
      C = A + B;
      Console.WriteLine("Line 1 - Value of C is {0}", C);
     
      C = A - B;
      Console.WriteLine("Line 2 - Value of C is {0}", C);
      
      C = A * B;
      Console.WriteLine("Line 3 - Value of C is {0}", C);
      
      C = B / A;
      Console.WriteLine("Line 4 - Value of C is {0}", C);
      
      C = A++;
      Console.WriteLine("Line 5 - Value of C is {0}", C);
      
      C = A--;
      Console.WriteLine("Line 6 - Value of C is {0}", C);
      
      C = A;
      Console.WriteLine("Line 7 - Value of C is {0}", C);
      
      if (A == B)
      {
        Console.WriteLine("Line 8 - A is equal to B");
      }
      else
      {
        Console.WriteLine("Line 8 - A is not equal to B");
      }
      
      if (A > B)
      {
        Console.WriteLine("Line 9 - A is greater than B");
      }
      else
      {
        Console.WriteLine("Line 9 - A is not greater than B");
      }
      
      if (A < B)
      {
        Console.WriteLine("Line 9 - A is less than B");
      }
      else
      {
        Console.WriteLine("Line 9 - A is not less than B");
      }
      
    }
    
  }
  
}
