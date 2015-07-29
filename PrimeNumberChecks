using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;

namespace _08.PrimeNumberCheck
{
    class PrimeNumberCheck
    {
        static void Main(string[] args)
        {
            int number = int.Parse(Console.ReadLine());

            bool isPrimeNumber = true;

            if (number <=1)
            {
                isPrimeNumber = false;
            }

            for (int i = 2; i < number; i++)
            {
                
                if (number % i == 0)
                {
                    isPrimeNumber = false;
                    break;
                }
            }

            Console.WriteLine(isPrimeNumber);
        }
    }
}
